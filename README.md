# MicroservicesApp.RESTCommunicationBetweenTwoMicroservices

This project extends the previous step by enabling **REST communication** between the `OrderingService` and the `CatalogService`.  
Orders now query product data from the Catalog API when creating a new order.

## Features
- Ordering microservice fetches product data via HTTP from the Catalog microservice
- DTOs to separate internal and external communication
- REST endpoints preserved in both services

## Technologies
- ASP.NET Core 8
- Entity Framework Core
- HttpClient for inter-service communication
- SQL Server

## Purpose
This step demonstrates **synchronous communication** between two microservices using REST.
