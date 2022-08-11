In this project, we try to track the price of a [Remote controlled fan](https://www.amazon.in/dp/B077XRGKCZ/ref=twister_B08CNGNJ66?_encoding=UTF8&psc=1) sold on Amazon using web scrapping in python.

Libraries used: BeautifulSoup, pandas, smtplib, request

	1. First, we retrieve the HTML content of the page using it's URL
  
	2. Extract the Product title, Product price from the retrieved HTML using BeautifulSoup
  
	3. Clean the data by removing whitespaces and special characters 
  
	4. Write the Product title, price, current date and time into an Excel file
  
	5. Repeat the above step for every 10 seconds to keep track of the price
  
	6. Trigger a mail if the price drops below Rs.3600

