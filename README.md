# **The Overdrive Challenge**
### Description
The Overdrive challenge is an opportunity for prospective developers to show off their skills and get a feel for the type of work we do.  The Overdrive challenge will explore your ability as a Javascript developer.  We don’t expect you to be a pro at all of the technologies that we use, but we are a team of learners and innovators and we often must learn on the fly with little to no supervision.

## Required Stack
* Server: NodeJS, ExpressJS
* Data-Tier: MySQL (Sequelize library)
* Front end: React

## Deployment
This app can be deployed on any of the below options
* Heroku
* AWS (_Bonus points here_)
* Firebase
* Digital Ocean

### Project Overview
You will be responsible for building a product profitability calculator.

The app consists of four major elements...
#### Home Page
This page is used for display a list of current products and navigating to subsequent pages
#### New Item Page
This page will contain an interactive form that will allow a user to POST a new product into inventory (and adding it to current products)
#### Edit Item Page
This page will replicate the new item page, but will be populated on loading with a SKU from a get parameter.
#### Calculator Page
This page contains a semi-interactive form where a user can test the pricing of a product and view profitability at certain points.

You will be responsible for building both the back-end RESTful API using NodeJS and ExpressJS with an integration to a MYSQL database and a react based front end web app with the following functionality:

### User Stories
**_As a user..._**
* ...I want to be able to add new items to quickly reference.
* ...I want to be able to edit/change the values of these items.
* ...I want to be able to remove items from the database
* ...I want to be able to enter a price for an item and see what it's profit and profit margin would be.


### Data Model
* **Sku** `string` Primary Key
* **Item Name** `string`
* **Product Cost** `float`
* **Freight** `float`

### API Route Suggestions
*	GET product/ - list all created products
*	POST product/ - add a new product
*	GET product/<SKU> - get a specific product (for edit or calculator)
*	PUT product/<SKU> - update a specific product
*	DELETE product/<SKU> - remove a specific product

### React (major) Component Suggestions
*	Home – list all products
*	Add – add a new product (can also be used to edit the item if you want to reuse the component)
*	Edit – edit a product (if you don’t want to reuse the above component)
*	Calculator – allow the user to play around with pricing on the item

## Resources
***
### Server
* #### ExpressJS
  * https://expressjs.com/
* #### Sequelize
  * https://sequelize.readthedocs.io/en/v3/

### Front End
* #### React
  * https://facebook.github.io/react/
  * https://github.com/facebookincubator/create-react-app
* #### React Router
  *	https://github.com/ReactTraining/react-router
* #### React-Bootstrap
  *	https://react-bootstrap.github.io/
* #### Axios
  * https://wwww.npmjs.com/package/axios

### Deployment
* #### Heroku
  * https://www.heroku.com/
* #### Amazon Web Services (AWS)
  * Elastic Cloud Compute (EC2)
    * http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html
  * Relational Database Service (RDS)
    * http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.html
    * http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/TUT_WebAppWithRDS.html
* #### Firebase
  * https://firebase.google.com/docs/hosting/deploying
* #### Digital Ocean
  * https://www.digitalocean.com/help/getting-started/setting-up-your-server/
