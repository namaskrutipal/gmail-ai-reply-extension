# Email Writer AI  

A full-stack project that generates professional or casual email replies using **Spring Boot, Spring AI, and React**.  
The frontend works as a browser extension and integrates with Gmail DOM via `MutationObserver`, enabling AI-powered reply suggestions directly inside Gmail.  

---

## Features  
- ✉AI-generated professional or casual email replies  
- Integration with Gmail DOM (via MutationObserver)  
- Full-stack implementation (Spring Boot backend + React frontend)  
- Browser extension APIs  
- Powered by LLMs through Spring AI  

---

## Tech Stack  
**Backend:** Spring Boot, Spring AI, Maven  
**Frontend:** React, Vite, JavaScript  
**Other:** Browser Extension APIs, Gmail DOM Integration, Git  

---

Setup Instructions  

Backend (Spring Boot)  
1. Navigate to the backend folder:  
   ```bash
   cd email-writer-sb
2. Build and run the application:
   ./mvnw spring-boot:run
   
Frontend (React)
1. Navigate to the frontend folder:
   cd email-writer-react
2. Install dependencies:
   npm install
3. Run locally:
    npm run dev

Browser Extension
Build the React app:

npm run build


Open Chrome → Extensions → Manage Extensions → Load unpacked.

Select the dist folder from the React project.

Open Gmail and see the AI email reply suggestions in action.
