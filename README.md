# Ecommerce Microservice

This repository holds setup, configs  and resources shared between the microservices, such as  docs, pkgs, message brokers etc



## Applications

* ## [Jaeger](https://www.jaegertracing.io/)

  * Jaeger is an **open source software for tracing transactions between distributed services**.
* ## [Nats](https://nats.io)

  * NATS is **an open-source messaging system** (sometimes called message-oriented middleware).


### Usage

To install / run the applications shared by the services just run the command:

```bash
docker-compose up
```


## Requirements

The application requires the following:

* Go (v 1.5+)
* Docker (v3+)
* Docker Compose


## Other Micro-Services

* #### [User Service](https://github.com/wisdommatt/ecommerce-microservice-user-service)
* #### [Product Service](https://github.com/wisdommatt/ecommerce-microservice-product-service)
* #### [Notification Service](https://github.com/wisdommatt/ecommerce-microservice-notification-service)
* #### [Cart Service](https://github.com/wisdommatt/ecommerce-microservice-cart-service)


## Public API

The public graphql API that interacts with the microservices internally can be found in [https://github.com/wisdommatt/ecommerce-microservice-public-api](https://github.com/wisdommatt/ecommerce-microservice-public-api).
