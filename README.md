# Item Management REST API - This is a simple Spring Boot REST API for managing items using in-memory storage.
---

## How to Run

- Install Java 17+
- Import project into Eclipse
- Run `ItemApiApplication.java`
---
## API Endpoints
Use **POSTMAN**  
Server runs on: `http://localhost:8080`

---
### 1. POST /api/items  
- Adds a new item  
- Validates required fields  
**URL:** http://localhost:8080/api/items
**Request Body (JSON):**
```json
{
  "name": "Laptop2",
  "description": "HP Laptop",
  "price": 40000
}

2. GET /api/items/{id} - Fetch item by ID
URL: http://localhost:8080/api/items/2

Data Storage - In-memory ArrayList

Tech Stack - Java
             Spring Boot
