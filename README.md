**Inventory Management Web Application 📦**
Welcome to the Inventory Management Web Application! This application is built using the Flask framework and provides a user-friendly interface to manage inventory for a list of products in various warehouses. Whether you run a shop or manage a warehouse, this application will help you keep track of your products and their respective locations efficiently.

##Functionality 🛠️
The application covers the following key functionalities:

##Database Tables 🗄️
Product: This table stores information about various products. Each product is identified by a unique product_id.

Location: This table keeps track of different warehouse locations. Each location is identified by a unique location_id.

ProductMovement: This table records the movement of products between different locations. It includes movement_id, timestamp, from_location, to_location, product_id, and qty fields.

Note: The primary keys for tables can be of text/varchar type, and either or both from_location and to_location can be filled depending on the type of product movement (inward or outward).

##Views 👀
The application provides easy-to-use views for the following entities:

##Product:

Add new products.
Edit existing product details.
View the list of products with their respective information.
##Location:

Add new warehouse locations.
Edit existing location details.
View the list of warehouse locations with their respective information.
##ProductMovement:

Add new product movements to record the transfer of products between locations.
Edit existing movement details if necessary.
View the list of product movements with relevant information.
##Report 📊
The application generates a comprehensive report that displays the balance quantity of each product in each warehouse location. The report is presented in a grid view with the following columns:

Product: Name or identifier of the product.
Warehouse: Name or identifier of the warehouse location.
Qty: The quantity of the product available in the respective warehouse.
Use Cases 📋
To familiarize yourself with the functionality, follow these steps:

##Create 3 to 4 different products in the system.
Add 3 to 4 warehouse locations.
Record various product movements, which include:
Moving Product A to Location X.
Moving Product B to Location X.
Moving Product A from Location X to Location Y.
Repeat these movements for around 20 instances to simulate real-world scenarios.
Once you have performed these use cases, you can generate the product balance report to see the quantity of each product available in each warehouse location.

##Getting Started 🚀
To run the Inventory Management Web Application locally, follow these steps:

*Clone this repository to your local machine.
*Install the required dependencies using pip install -r requirements.txt.
*Run the Flask application using python app.py.
*Access the application in your web browser by visiting http://localhost:5000.
Note: Ensure you have Python and Flask installed on your system before starting the application.


##Happy inventory managing! 📦🚀
 
