# PHP Recruitment Challenge: "NYT Article Explorer"

## Overview  
Use the **New York Times Developer API** ([https://developer.nytimes.com/](https://developer.nytimes.com/)) to allow users to search, view, and save favorite articles.  
This task is designed to simulate a real-world backend project suitable for **mobile integration** and **web**.  

---

## 📌 Features to Implement  

### ✅ RESTful API (Backend)  
Build a secure API that allows clients (e.g., mobile apps or web frontend) to perform the following:  
- **Search for articles** using the NYT API with **pagination** support to efficiently handle large datasets.  
- **View details** of a specific article.  
- **Manage the favorites list** (View, Add, Delete).  

### ✅ Web Frontend  
(Use any frontend framework like **Bootstrap** or **Vue.js**, etc.)  
- **Search for articles** using the API.  
- **Display a list of favorite articles**.  
- **Add or remove articles** from favorites.  

---

## 🔒 Security  
- The API **must be secured with JWT tokens** for authentication.  
- Validate all input parameters to prevent **injection attacks**.  

---

## 📜 Logging  
(File-based or database logging)  
- **Implement request/response logging** for both API and web interactions.  

---

## 🛠 Requirements  
- Use **pure PHP** (no frameworks).  
- Follow **Clean Architecture** and **SOLID** principles.  
- Ensure **secure API endpoints** (authentication, input validation).  
- Store favorite articles and authentication data in a local **SQLite database**.  
- Provide a **script to set up the schema** if needed.  
- Code should be appropriately **documented**.  

---

## ⭐ Bonus Points  
- Include a **user authentication system** for basic login.  
- **Cache NYT API responses** locally to reduce redundant calls.  
- Implement **rate limiting** for API endpoints to prevent abuse:  
  - After **5 requests within 5 minutes**, subsequent requests should return an **HTTP 429 status code**.  
  - The error response should include a **retry-after** time in seconds.  
- Add **unit tests** for core functionalities.  
- Provide a **Docker setup** for easy deployment and testing.  

---

## 📦 Deliverables  
- **README file** with setup and usage instructions.  
- **Source code** (backend and frontend) via **GitHub**.  
- **Database schema creation script**.  
- **API documentation** in any of the following:  
  - Markdown format  
  - Postman  
  - Swagger  
- **Log files** or instructions on how to view logs.  

---

> If you are invited for a follow-up **system design interview**, part of that will involve expanding upon your solution to the challenge. Keep that in mind as you design your system.

---
