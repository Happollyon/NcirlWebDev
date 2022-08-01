# Web Application Assigments
## Web application requirements

### #shop

#### *Disclaimer: them images used in this project belong to www.ikea.ie*
Assume that you are responsible for developing, maintaining, and updating a third-party company's
web application. The web application provides information of all products manufactured by the
company and allows users to query the inventory for products availability.

Define an XML file structure that allows the exchange of products information listed in Table 1.
Each XML file may contain the information of at least 10 products. The code of the product should
be defined as an attribute of the product element rather than an element itself.

*table 1*

* Category
* code
* name
* image
* price
* description
* qty

Create an XML Schema that validates the received XML files before they are uploaded into the web application according to the datatype shown in Table 1.

Create a web application that:
Displays information about the products’ Code, Name, Quantity and Unit Price informationstored in the XML file.

Allows the searching of these products by providing a field that the user can enter a product code and button that when clicked should look for the product and present all the product's information to the user. If the product's code does not exist, the user should be notified.

The pages must have a navigation menu that allows the user to navigate through the different web application pages.

### #weather

Assume that OpenWeatherMap (https://openweathermap.org/) have contacted you to develop an application, with them providing a web service for you to use.

You need to develop an application that allows a user to enter a single city (on a HTML page) and request the OpenWeatherMap web service to retrieve this information and render this information to the web page.

Your application should be making a GET request to http://api.openweathermap.org/data/2.5/forecast?mode=json&q=[CITY]&appid=[API%20ID] to retrieve the information on the web page.