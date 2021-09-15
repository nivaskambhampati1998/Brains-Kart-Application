
# BrainsKart Application (MERN Stack / Full stack)
------------------------------------------------
### client : React + Bootstrap
### Server : Express + Node + Mongodb (mongoose)

# Client side Features
--------------------
-> React Hooks
-> React Redux
-> Routings , navigation
-> form validation
-> authentication

# server side Features
---------------------
-> password encription
-> JWT Authentication
-> Creditcard Payments
-> deployment to Heroku

-----------------------------------------
# Folder Structure
------------------------------------------
## brainsKart-react
	-> client 
		-> react code
	        -> server code

# Client Side Setup
------------------
-> Create a react project with the name "client"
	npx create-react-app client 

-> Install all the required npm modules

	npm install axios react-router-dom redux react-redux redux-thunk redux-logger redux-devtools-extension mdbootstrap @fortawesome/fontawesome-free uuid
		
-> configure bootstrap , fontawesome for the project
	
-> users , products , orders , layout

# React Modules
products , orders , users	

## -> each module have its own things
	components 
-> Users Module :
		components : login , register , profile
-> Products module :
		components : mens-wear , kids-wear , women-wear, upload 
## product-details
-> Orders module : 
		components : cart , checkout , order-list , order-success

# Server Side Setup
------------------
## User Router 
 -> Register a User, Login a User, Get User Info, Create/Update Address
## Update a Router
-> Update a product, Get Men's collection, Get women's collection, Get Kid's collection, Get a Product
## Order Router
->To place an order, get all orders
## Payment router
-> Accept stripe payments

