## Get All Categories
`GET root/v1/categories/read.php`

## Get All Products
`GET root/v1/products/read.php`

## Get Product By Id
`GET root/v1/products/find.php?id=1`

## Search Product Relate the Words
`GET root/v1/products/search.php?s=books`

## Get Product In  Paginations
`GET root/v1/products/paginate.php`

## Delete any Products Where Post ID Request
`POST root/v1/products/delete.php`

`{id:  1}`

## Create New Product
`POST root/v1/products/create.php`

`{ 
	name: "Coca"
	price: 10.0
	description: "popular drink in town."
	category_id: 1
}`


## Update Existed Product
`POST root/v1/products/update.php`

`{ 
	id: 1,
	name: "Red Bull"
	price: 10.0
	description: "popular drink in town."
	category_id: 1
}`
