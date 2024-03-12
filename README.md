# Building a Spring Boot Application for a Cart Service

This is a simple API service that provides a cart service for a fake store. This is built using Spring Boot and Java.

## API Endpoints

### Get Cart
```
GET /carts
```
This endpoint returns the current cart.

### Add Item to Cart
```
POST /carts
```
### Remove Item from Cart
```
DELETE /carts/{id}
```
This endpoint removes an item from the cart.

### Update Item in Cart
```
PUT /carts
```
### Get Cart by ID
```
GET /carts/{id}
```
This endpoint returns the cart with the specified ID.

### Get Cart by User ID
```
GET carts/user/{userId}
```
This endpoint returns the cart with the specified user ID.

### Get Cart by Date
```
GET /carts/startDate/endDate
```
This endpoint returns the carts added between the specified dates

## Test Results

### Get all carts
![1.png](1.png)

### Get Cart by Id
![2.png](2.png)

### Get by userId
![3.png](3.png)

### Add new cart
![4.png](4.png)

### Update Product
![5.png](5.png)

### Delete Product
![6.png](6.png)

### Get Products Between the specified time period
![7.png](7.png)
