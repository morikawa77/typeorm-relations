<img alt="GoStack" src=".github/header-desafios-new.png" style="width: 100%;"/>

<h3 align="center">
  Challenge 07: GoFinances Web
</h3>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=15C3D6&labelColor=000000">
</p>

### 🚀 About the challenge

In this challenge, you will be creating a new application to learn new things and train what you have learned so far in Node.js alongside TypeScript, including using a database with TypeORM, and ManyToMany relationships!

This will be an application that should allow the creation of customers, products and orders, where the customer can generate new purchase orders for certain products, such as a small e-commerce.


### Tests Specification

<h4 align = "center">
  ⚠️ Before running the tests, create a database with the name "gostack_desafio09_tests" so that all tests can run correctly ⚠️
</h4>

- ** `should be able to create a new customer` **: For this test to pass, your application must allow a customer to be created, and return a json with the created customer.

- ** `should not be able to create a customer with one email thats already registered` **: In order for this test to pass, your application must return an error when you try to register a customer with an email that is already registered in the database.

- ** `should be able to create a new product` **: For this test to pass, your application must allow a product to be created, and return a json with the created product.

- ** `should not be able to create a duplicated product` **: In order for this test to pass, your application must return an error when you try to register a product with a name that is already registered in the database.

- ** `should be able to create a new order` **: For this test to pass, your application must allow an order to be created, and return a json with all the data of the created order.

- ** `should not be able to create an order with an invalid customer` **: In order for this test to pass, your application must not allow the creation of a new order with a customer that does not exist in the database, returning a error.

- ** `should not be able to create an order with invalid products` **: In order for this test to pass, your application must not allow the creation of a new order with products that do not exist in the database, returning an error if one or more of the products shipped does not exist in the database.

- ** `should not be able to create an order with products with insufficient quantities` **: In order for this test to pass, your application must not allow the creation of a new order with a product that has no quantity available, returning an error if one or more of the products shipped does not have the required quantity.

- ** `should be able to subtract an product total quantity when it is ordered` **: For this test to pass, your application must allow that, when a new order is created, the total quantity of products based on the quantity is changed requested.

- ** `should be able to list one specific order` **: In order for this test to pass, you must allow the ʻorders /: id` route to return an order, containing all the order information with the` customer relationship `and ʻorder_products`.


---

Made with ❤️ by morikawa77
