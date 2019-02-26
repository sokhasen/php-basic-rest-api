`GET root/v1/categories/read.php : get all categories`
`GET root/v1/products/read.php : get all products`
`GET root/v1/products/find.php?id=1 : get product by id = 1`
`GET root/v1/products/search.php?s=books : search product relate the books`
`GET root/v1/products/paginate.php : get products as  paginations`
`POST root/v1/products/delete.php : delete any products where post request  {id:  1}`
`POST root/v1/products/create.php : create new product
{ 
	name: "Coca"
	price: 10.0
	description: "popular drink in town."
	category_id: 1
}`

`POST root/v1/products/update.php : update existing product
{ 
	id: 1,
	name: "Red Bull"
	price: 10.0
	description: "popular drink in town."
	category_id: 1
}`
