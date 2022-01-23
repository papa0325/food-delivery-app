# Food Delivery Web Application Sample
![GitHub Repo size](https://img.shields.io/github/repo-size/bardsnight/dsdeliver-sds2?style=flat-square)
![GitHub Languages](https://img.shields.io/github/languages/count/bardsnight/dsdeliver-sds2?style=flat-square)
![GitHub Issues](https://img.shields.io/github/issues/bardsnight/dsdeliver-sds2?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/bardsnight/dsdeliver-sds2?style=flat-square)
![License](https://img.shields.io/github/license/bardsnight/dsdeliver-sds2?style=flat-square)
> This project was developed with the intent of learning full-stack development with Springboot and React.
> <br>Live preview is available and source code if completely free to use.

Single page food delivery (SPA) web application powered by React, TypeScript and Node on the front end that requests a RESTful API made in Java with SpringBoot hosted on Heroku.

   The app's function is to show the products available to the customer through the products page and perform the transaction with the REST API endpoint, where the data is recorded in the PostgreSQL relational database.
Two many-to-many tables are used where the minimum of products in an order is 1, and the minimum of orders related to a product is zero.
A third table listing ORDERS and PRODUCTS is used to return the information.

Due to the Heroku server going into sleep mode (free version), the first product page load may take a minute or two before it works perfectly.