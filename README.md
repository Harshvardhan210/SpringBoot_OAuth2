# 🌟🚀 Spring OAuth2 Practice Project 🌟

> *A clean and simple project where I practiced **OAuth2**, **Spring Security**, and secure authentication flows.*

---

## 1. **About the Project** ℹ️

**Project Name:** *SpringBoot_OAuth2*    
**Description:**  
This project demonstrates how to integrate **OAuth2 authentication** in a Spring Boot application.  
It includes:

**Tech Stack:** 
- 🍃 **Spring Boot**  
- ♨️ **Java**  
- 🔐 **Google OAuth2 Login**  
- 🗝️ **Github OAuth2 Login**

> _"Build fast. Ship faster."_ 🚀

---

## 2. **Project Structure** 📂

```bash
SpringOAuth2/
├─ .idea/                ← IntelliJ files (optional)
├─ .mvn/                 ← Maven wrapper
├─ src/
│  └─ main/
│     ├─ java/
│     │  └─ com.example.SpringOAuth2/
│     │     ├─ HelloController.java
│     │     ├─ SecurityConfig.java
│     │     └─ SpringOAuth2Application.java
│     └─ resources/
│        ├─ static/        ← CSS / JS
│        ├─ templates/     ← Thymeleaf pages
│        └─ application.properties
└─ pom.xml               ← Maven dependencies

```

## 🛠️ Setup Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
# 🔐 How to Create Google & GitHub OAuth2 Client ID and Client Secret

## 🟦 Google OAuth2 Setup

### ✅ Step 1: Open Google Cloud Console
Go to: https://console.cloud.google.com/

### ✅ Step 2: Create a New Project
- Click the **Project dropdown**
- Click **New Project**
- Enter a project name and **Create**

### ✅ Step 3: Set Up OAuth Consent Screen
- Left Menu → **APIs & Services**
- Click **OAuth consent screen**
- Select **External** → Continue
- Fill in:
  - App Name  
  - User Support Email  
- Click **Save and Continue** (you can skip scopes & test users)

### ✅ Step 4: Create OAuth Credentials
- Go to **APIs & Services → Credentials**
- Click **+ CREATE CREDENTIALS**
- Select **OAuth Client ID**

### ✅ Step 5: Select Application Type
Choose: **Web Application**

### ✅ Step 6: Add Redirect URI
Add this redirect URL for Spring Boot:

