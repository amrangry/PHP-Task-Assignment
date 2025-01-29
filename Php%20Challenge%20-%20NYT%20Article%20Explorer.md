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

## **Author**

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/2900952?s=400&u=41c504ca200e2f92638fc630e8361da78296b35c&v=4" width="180" alt="Amr Ahmed Elghadban"/>

  **Amr Ahmed Elghadban (AmrAngry)**

[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?logo=gmail)](mailto:amr.elghadban@gmail.com) [![WhatsApp](https://img.shields.io/badge/GitHub-Profile-blue?logo=whatsapp)](https://api.whatsapp.com/send/?phone=00971543233227&text=Hi%20&app_absent=0) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/amrelghadban/)

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/amrangry) [![StackOverflow](https://img.shields.io/badge/StackOverflow-Profile-orange?logo=stackoverflow)](https://stackoverflow.com/users/1316779/amrangry)

[![Twitter (formerly Twitter)](https://img.shields.io/badge/Twitter-Profile-blue?logo=twitter)](https://x.com/intent/follow?screen_name=amr_elghadban) [![Facebook](https://img.shields.io/badge/Facebook-Profile-blue?logo=facebook)](https://facebook.com/amr.elghadban) [![Website](https://img.shields.io/badge/Website-Visit%20Me-blue?logo=globe)](https://amrangry.github.io/)
       <div align="center" >
	       <a href = "https://www.buymeacoffee.com/amrangry">
		    <img src = "https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=your-username&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff"/>
                </a>
       </div>
  <!--  [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20Me-yellow?logo=buymeacoffee)](https://www.buymeacoffee.com/amrangry) -->
  <!--  [Email](mailto:amr.elghadban@gmail.com?subject=I%20checked%20your%20GitHub%20repo!): [amr.elghadban@gmail.com](mailto:amr.elghadban@gmail.com) -->
  <!-- [![Linkedin](https://img.shields.io/badge/Lets%20Connect%20via-LinkedIn-blue)](https://www.linkedin.com/in/amrelghadban/) -->
  <!-- [![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/amr_elghadban)](https://x.com/intent/follow?screen_name=amr_elghadban) -->
  
</div>

## **Contributing 🤘**

All your feedback and help to improve this project is very welcome. Please create issues for your bugs, ideas and enhancement requests, or better yet, contribute directly by creating a PR. 😎

When reporting an issue, please add a detailed instruction, and if possible a code snippet or test that can be used as a reproducer of your problem. 💥

When creating a pull request, please adhere to the current coding style where possible, and create tests with your code so it keeps providing an awesome test coverage level 💪

## **Code of Conduct**

I’m here to share my knowledge and findings as I work every day to improve our apps/demos for the community.
This is a space where we work together, openly and safely, as kind and considerate human beings.
We grow by giving and receiving positive, constructive feedback. 
Let’s keep learning and building, one step at a time.

## **License**

<details>
<summary>MIT License.</summary>
Distributed under MIT License.
Copyright &copy; 2025 Amr Elghadban
</details>
