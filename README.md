Item Management REST API - This is a simple Spring Boot REST API for managing items using in-memory storage.
---

How to Run:
1. Install Java 17+
2. Import project into Eclipse
3. Run ItemApiApplication.java

---
API Endpoints: Use POSTMAN - Server runs on http://localhost:8080
1.POST /api/items
 - Adds a new item
 - Validates required fields
 - Ex:
      http://localhost:8080/api/items
      {
         "name": "Laptop2",
         "description": "HP Laptop",
         "price": 40000
      }

2.GET /api/items/{id}
 - Fetch item by ID
 - Ex:   http://localhost:8080/api/items/2

---
Data Storage:
- In-memory ArrayList
  
---
Tech Stack:
- Java
- Spring Boot

