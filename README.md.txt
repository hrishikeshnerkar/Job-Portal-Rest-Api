# 🚀 Job Portal Application

A Backend job portal system built with **Spring Boot** using REST API and **React** for the frontend UI. This application allows users to view, add, update, and delete job listings with dynamic data rendering.

---

## 📁 Project Structure

| Layer      | Technology           | Description                         |
|------------|----------------------|-------------------------------------|
| Backend    | Spring Boot          | REST API for job listings           |
| Frontend   | React + Material-UI  | UI interface for job presentation   |

---

## ✨ Features

- View all job listings
- Access individual job post details
- Add new job entries
- Edit and update job information
- Delete job listings
- Responsive job card rendering with Material-UI

---

## ⚙️ Technologies Used

- Java 17 + Spring Boot
- React
- Material-UI
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

🎨 Frontend Setup

```bash
npm install
npm start

Runs at: ```http://localhost:3000

🖼️ UI Overview
The frontend displays job listings in card format, including:
- 🔹 Job title (postProfile)
- 🔹 Description (postDesc)
- 🔹 Required experience (reqExperience)
- 🔹 Skills (Tech stack → postTechStack)
Each card is styled with responsive design elements using Material-UI’s Grid, Card, and Typography components.
