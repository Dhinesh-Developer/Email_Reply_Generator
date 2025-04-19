# 💌 AI Email Reply Generator

An AI-powered Chrome Extension that helps users generate smart email replies directly from their inbox. This project integrates **React** for the frontend, a **Spring Boot** backend for handling AI logic, and utilizes **Chrome Extension APIs** to interact with the browser.

---

## 🚀 Features

- 🧠 AI-generated responses for emails  
- 🧩 Chrome Extension for easy access within Gmail or similar platforms  
- ⚡ Real-time suggestions powered by Spring Boot backend  
- 💾 Chrome Local Storage to manage user session/data  
- 🌐 Modern UI built with React  

---

## 🛠️ Tech Stack

### 🔷 Frontend
- React.js  
- Chrome Extension Scripts:
  - `manifest.json`
  - `content.js`

### 🔶 Backend
- Spring Boot (Java)  
- Dependencies used:
  - `spring-boot-starter-web`  
  - `spring-boot-starter-webflux`  
  - `spring-boot-devtools`  

### 📦 Storage
- Chrome Local Storage API

---

## 📁 Folder Structure


---

## 🔧 How It Works

1. **User installs the Chrome Extension.**  
2. **On opening an email**, the extension activates and shows a "Generate Reply" button.  
3. **When clicked**, the frontend sends the email content to the backend.  
4. **Backend processes the request** using AI logic (can be integrated with models like GPT).  
5. **A suggested reply** is returned and shown to the user for review/edit.  

---
![image](https://github.com/user-attachments/assets/48009baf-645b-4c07-b88d-725ace9f44b5)
![image](https://github.com/user-attachments/assets/4a8a7ddd-2ae7-4758-9522-ceaf51aadad9)


---
🧠 Future Improvements
Integration with OpenAI or other LLM APIs

User authentication and preferences

Context-aware reply suggestions

Support for multiple languages

---

## 📦 Installation & Setup

### Backend (Spring Boot)
```bash
cd backend
./mvnw spring-boot:run
cd frontend
npm install
npm start


Chrome Extension
Go to chrome://extensions/

Enable Developer Mode

Click Load unpacked and select the extension/ folder

You’re good to go!




