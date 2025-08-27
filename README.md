# 🚀 Job Portal Application

A Backend job portal system built with **Spring Boot** using REST API and **React** for the frontend UI. This application allows users to view, add, update, and delete job listings with dynamic data rendering.

---

## 📁 Project Structure

| Layer      | Technology           | Description                         |
|------------|----------------------|-------------------------------------|
| Backend    | Spring Boot          | REST API for job listings           |
| Frontend   | React                | Just for showing the UI             |

---

## ✨ Features

- View all job listings
- Add new job entries
- Edit and update job information
- Delete job listings

---

## ⚙️ Technologies Used

- Java 17 + Spring Boot
- React
- Axios for API communication
- json-server for mock testing

---

## 📡 API Endpoints

| Method | Endpoint             | Function                             |
|--------|----------------------|--------------------------------------|
| GET    | `/jobPosts`          | Retrieve all job listings            |
| GET    | `/jobPost/{postId}`  | Get details of a specific job post   |
| POST   | `/jobPost`           | Add a new job post                   |
| PUT    | `/jobPost`           | Update an existing job post          |
| DELETE | `/jobPost/{postId}`  | Delete a job post                    |

---

## 🚀 Getting Started

### 📌 Backend Setup

```bash
# Compile and run the Spring Boot backend
mvn spring-boot:run

Runs at: ```http://localhost:8080

```
### 🎨 Frontend Setup

```bash
npm install
npm start

Runs at: ```http://localhost:3000
```

🖼️ UI Overview
The frontend displays job listings in card format, including:
- 🔹 Job title (postProfile)
- 🔹 Description (postDesc)
- 🔹 Required experience (reqExperience)
- 🔹 Skills (Tech stack → postTechStack)
Each card is styled with responsive design elements using Material-UI’s Grid, Card, and Typography components.

---

# 📬 API Testing with Postman

🔍 Visualizing Backend Integration
To demonstrate the seamless connection between the Spring Boot backend and the React frontend, I used Postman to test all core API functionalities. Below are screenshots showing:
- ✅ Retrieving job listings (GET /jobPosts)
- ➕ Adding a new job post (POST /jobPost)
- ✏️ Updating job details (PUT /jobPost)
- ❌ Deleting a job post (DELETE /jobPost/{postId})
These actions reflect instantly on the frontend UI, validating the dynamic data flow between client and server.
1. Post a new Job
   <img width="1376" height="870" alt="image" src="https://github.com/user-attachments/assets/dec333d2-cefe-4a0a-ac1c-5faf53dbdf18" />

2. Update the Job
   <img width="1341" height="885" alt="image" src="https://github.com/user-attachments/assets/ab606ec0-1ca9-48c8-9eab-dd83f344f246" />

3. Get Job Details
   <img width="1390" height="964" alt="image" src="https://github.com/user-attachments/assets/09ef4762-a00c-444b-a511-e95e1c846505" />

4. Delete the Job
   <img width="1391" height="920" alt="image" src="https://github.com/user-attachments/assets/2a963d5d-a61e-4bb6-bf94-b32906c80972" />

5. Gettig all Jobs
   <img width="1337" height="887" alt="image" src="https://github.com/user-attachments/assets/791f1fb2-7b2f-4eaf-9176-78590caf9fc9" />

---

## 👤 Author

**Hrishikesh**  
Full-stack developer passionate about building secure, scalable, and well-documented web applications.  
Specialized in Spring Boot, React, and modern authentication flows.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/hrishikesh015)

---
