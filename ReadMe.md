# Basic Rest API

- classes: Contains Relational Model
- common: Contains help class resuse everwhere.
- config: Contains configurarion file like mysql database engine etc.
- database: Contains sql table and dumpy data sql in sample.
- v1: stage api contains all resources provide to client side.




## Get All Categories
`GET root/v1/categories/read.php`

## Get All Products
`GET host /v1/products/read.php`

## Get Product By Id
`GET host /v1/products/find.php?id=1`

## Search Product Relate the Words
`GET host /v1/products/search.php?s=books`

## Get Product In  Paginations
`GET host /v1/products/paginate.php`

## Delete any Products Where Post ID Request
`POST host /v1/products/delete.php`

`{id:  1}`

## Create New Product
`POST host /v1/products/create.php`

`{ 
	name: "Coca"
	price: 10.0
	description: "popular drink in town."
	category_id: 1
}`


## Update Existed Product
`POST host /v1/products/update.php`

`{ 
	id: 1,
	name: "Red Bull"
	price: 10.0
	description: "popular drink in town."
	category_id: 1
}`
