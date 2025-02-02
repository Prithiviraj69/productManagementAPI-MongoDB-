# productManagementAPI-MongoDB-
### ***Assignment 5***
##### *It's a simple app with MongoDB.*

## FRAMEWORKS
![nodejs](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) ![postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)


## DATABASE
![mongodb](https://img.shields.io/badge/MongoDB-white?style=for-the-badge&logo=mongodb&logoColor=4EA94B)

## SCHEMA

#### PRODUCT
- product id : String
- title : String
- price : String
- category : Array of String
- company id : String
- seller id : Array of String


#### COMPANY
- company id : String
- name : String
- product ids : Array of String


#### SELLER 
- seller id : String
- name : String
- product ids : Array of String


## *POST REQUESTS:*


#### ADD 
- add new company
- add new seller
- add new product


#### RETRIEVE 
- fetch company details based on product name
- fetch seller details based on product name
- fetch all products of a company
- fetch all products of a seller


#### UPDATE 
- update company (add/remove products)
- update seller (add/remove products)
- update product (add/remove category)


#### DELETE 
- delete company
- delete seller
- delete product

## ***SCREENSHOTS***
- [Click Here](https://github.com/mr-sudheeshkumar/Product-Management-APIs-MongoDB-/tree/main/assignment5/Postman)

#### ***SCREENSHOTS DEMO***
![1.png](https://github.com/Prithiviraj69/productManagementAPI-MongoDB-/blob/main/assignment5/Postman/1.png)
![2.png](https://github.com/Prithiviraj69/productManagementAPI-MongoDB-/blob/main/assignment5/Postman/5.png)
