# Charlie.Gateway (Ocelot)

This project implements a microservices-based architecture. The system leverages RabbitMQ for communication between services.The architecture is built using RESTful APIs, and MySQL databases back individual services.

![title](https://github.com/MrFrolin/Charlie.Gateway/blob/master/Charlie.Overview.png)


## How to run
1. Clone this repository.
2. Through the terminal, run:  
   ```bash
   docker-compose up --build

## Links

**Customer:**
- [Charlie.Customer.API](https://github.com/FiggeAhlberg/Charlie.Customer.API)
- [Charlie.Customer](https://github.com/FiggeAhlberg/Charlie.Customer)

**Product:**
- [Charlie.Product.API](https://github.com/MrFrolin/Charlie.Product.API)
- [Charlie.Product](https://github.com/MrFrolin/Charlie.Product)
  
**Order:**
- [Charlie.Order.API](https://github.com/AntonMalm/Charlie.Order.API)
- [Charlie.Order](https://github.com/AntonMalm/Charlie.Order)

**Payment:**
- [Charlie.Payment](https://github.com/tobiasehlme/Charlie.Payment)

# API Documentation for Charlie.Gateway (Ocelot Gateway)

This document provides an overview of the API routes configured in the Ocelot gateway.

## Base URL
All routes are prefixed with the following base URL:

```
http://localhost:5000
```



## Routes

### Products

- **POST /products**  
  **Description:** Creates a new product.  
  `http://localhost:5000/products`

- **GET /products/{id}**  
  **Description:** Retrieves a product by ID.  
  `http://localhost:5000/products/{id}`


### Orders

- **POST /orders**  
  **Description:** Creates a new order.  
 `http://localhost:5000/orders`

- **GET /orders/{id}**  
  **Description:** Retrieves an order by ID.  
  `http://localhost:5000/orders/{id}`


### Customers

- **POST /customers**  
  **Description:** Creates a new customer.  
  `http://localhost:5000/customers`

- **GET /customers/{id}**  
  **Description:** Retrieves a customer by ID.  
  `http://localhost:5000/customers/{id}`



