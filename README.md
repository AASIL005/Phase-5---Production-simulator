# Phase-5---Production-simulator (MongoDB Integration)

## Overview

In this phase, the Production Incident Simulator was upgraded from in-memory storage to persistent storage using MongoDB.

Previously, all incident data was stored in a HashMap and was lost whenever the application restarted. With MongoDB integration, incidents are now stored permanently and can be retrieved even after restarting the application.

This phase represents an important step toward making the simulator behave more like a real production system.



## Features

### Persistent Storage
- Incident data is stored in MongoDB.
- Data survives application restarts.
- Unique IDs are generated automatically by MongoDB.

### CRUD Operations
- Create incidents
- Retrieve all incidents
- Retrieve incidents by ID
- Delete incidents

### Spring Data MongoDB
- Repository-based data access
- Reduced boilerplate code
- Cleaner service layer implementation


## Technology Stack

- Java 17
- Spring Boot
- Spring Data MongoDB
- MongoDB
- Maven


## Architecture

Client
↓
REST Controller
↓
Service Layer
↓
Mongo Repository
↓
MongoDB


Learning Outcomes

Through this phase I learned:

Difference between in-memory and persistent storage
MongoDB document model
Spring Data repositories
Dependency injection with repositories
Data persistence in production systems
Basic NoSQL database integration
