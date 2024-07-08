### gRPC

- gRPC uses protobuf (Protocol buffers), language-and-platform neutral mechanisms for serializing structural data into small and compact messages both on server and client side.

- Compatible with multiple platforms and languages.

- Uses HTTP/2 over SSL/TLS to authenticate and encrypt data exchange.

- Performant and low latency


### Monolithic architecture

- Single-tiered and unified software application that can have FE, BE, DB modules all managed in one place.

- Helpfull when developing initial versions of a product.

- Easily scaled by using a load balancer enabling client requests.


### Microservice architecture

- This stule defines an application as a collection of services.

- Loosely coupled.

- Deployed and scaled independently.

- If one service fails, other services can continue to operate.


### Scale cube

- X-axis scaling is running multiple copies of the same application under a load balancer. 

- Z-axis scaling is similar to X-axis but the application is copied to instances, each application is responsible for just a subset of data.

- Y-axis is splitting the application by feature, similar to decompose an application into a set of services.