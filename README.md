# day-36-mongodb-task-1

db.products.find({})


db.products.find({product_price:{$gt:400,$lt:800}})


db.products.find({product_price:{$not:{$gt:400,$lt:800}}})


db.products.find({product_price:{$gt:500}}).limit(4)


db.products.find({},{product_name:1,product_material:1})


db.products.find({}).limit(10)


db.products.find({},{product_name:1,product_material:1})


db.products.find({product_material:{$eq:"soft"}})


db.products.find({product_color:{$eq:"indigo"}},{product_price:{$eq:492}})

