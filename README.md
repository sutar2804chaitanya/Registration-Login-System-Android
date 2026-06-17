# 🔐 Android Login & Registration App

A simple Android application developed using **Java**, **XML**, and **Android Studio** that allows users to register, log in, and access a personalized dashboard. User information is stored locally using **SharedPreferences**, demonstrating basic authentication and session management concepts in Android.

## 📖 Project Overview

This project was created as part of the **Mobile Application Development** coursework to demonstrate user authentication using local storage. The application allows users to create an account, store their credentials, log in with registered details, and navigate to a dashboard screen.

The project focuses on implementing multiple activities, data persistence, intent-based navigation, and user validation.

## 🎯 Aim

To develop an Android application that:

* Registers a new user.
* Stores user information using SharedPreferences.
* Authenticates users through a login screen.
* Redirects authenticated users to a dashboard.
* Demonstrates Android activity navigation and local data storage.

## ✨ Features

* User Registration Form
* User Login Authentication
* Local Data Storage using SharedPreferences
* Dashboard Screen after successful login
* Input collection using EditText
* Credential verification
* Toast messages for invalid login attempts
* Activity navigation using Intents
* Logout functionality
* Beginner-friendly Android project

## 🛠️ Technologies Used

| Technology        | Purpose                       |
| ----------------- | ----------------------------- |
| Java              | Application Logic             |
| XML               | User Interface Design         |
| Android Studio    | Development Environment       |
| Android SDK       | Android Application Framework |
| SharedPreferences | Local Data Storage            |
| Intent            | Activity Navigation           |

## 📂 Project Structure

```text
Android-Login-Registration-App/
│
├── app/
│   ├── src/main/
│   │
│   ├── java/com/example/assignment6/
│   │   ├── RegistrationActivity.java
│   │   ├── LoginActivity.java
│   │   └── DashboardActivity.java
│   │
│   ├── res/layout/
│   │   ├── activity_main.xml
│   │   ├── activity_login.xml
│   │   └── activity_dashboard.xml
│   │
│   └── AndroidManifest.xml
│
└── README.md
```

## ⚙️ Application Workflow

### Step 1: User Registration

The user enters:

* Name
* Email Address
* Password
* Phone Number

After clicking **Register**:

* User details are stored using SharedPreferences.
* The application redirects the user to the Login screen.

### Step 2: User Login

The user enters:

* Registered Email
* Registered Password

The application compares entered credentials with stored credentials.

### Step 3: Authentication

#### Successful Login

* User is redirected to Dashboard Activity.
* Access to the application dashboard is granted.

#### Failed Login

* A Toast message displays:

  * "Invalid email or password"

### Step 4: Dashboard

The dashboard displays:

* Welcome Message
* User Access Confirmation
* Logout Button

### Step 5: Logout

* User session ends.
* User can return to the login screen.

## 📸 Screenshots

### Registration Screen

* Name, Email, Password, and Phone Number fields
* Register button

### Login Screen

* Email and Password fields
* Login button

### Dashboard Screen

* Welcome message
* Logout button

> Add screenshots in a `screenshots` folder and update this section.

## 🧠 Android Concepts Implemented

* Activities
* Intents
* SharedPreferences
* EditText
* TextView
* Button Click Events
* User Authentication
* Data Persistence
* Form Handling
* Toast Notifications
* Activity Lifecycle
* Session Management Basics

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Android-Login-Registration-App.git
```

2. Open the project in Android Studio.

3. Sync Gradle files.

4. Connect an Android device or launch an emulator.

5. Click **Run** ▶️.

## 📚 Learning Outcomes

This project helped in understanding:

* Android Activity Navigation
* User Registration Process
* Login Authentication Logic
* Local Data Storage using SharedPreferences
* Handling User Inputs
* Intent-Based Screen Navigation
* Form Validation Techniques
* Building Multi-Screen Android Applications

## 🔮 Future Enhancements

* Password Encryption
* Forgot Password Feature
* Email Verification
* Profile Management
* SQLite Database Integration
* Firebase Authentication
* Remember Me Functionality
* Dark Mode Support
* Material Design UI
