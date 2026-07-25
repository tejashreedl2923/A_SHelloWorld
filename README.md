# Hello World Android Application

## Experiment 1 – Develop a Simple "Hello World" Android Application

### Student Details

- **Name:** Tejashree DL
- **USN:** 25MCAR0124

---

## Objective

To develop a simple Android application using Android Studio that displays the text **"Hello World"** on the screen. This experiment introduces the Android development environment, project structure, and the basic components of an Android application.

---

## Concept

Android applications are developed using **Android Studio** with **Kotlin** or **Java**. Every Android application starts with an **Activity**, which represents a single screen of the application. In this experiment, the application contains one activity (`MainActivity`) that displays a simple "Hello World" message using a `TextView`.

---

## Scenario

A beginner Android application that displays a welcome message when launched. This experiment demonstrates the basic workflow of creating, building, and running an Android application on an Android Emulator.

---

## Technologies Used

- Android Studio
- Kotlin
- Android SDK
- XML Layout
- Gradle

---

## Project Structure

```
HelloWorld/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/hello/
│   │   │   │       └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── values/
│   │   │   │   └── drawable/
│   │   │   └── AndroidManifest.xml
│   │
│   └── build.gradle.kts
│
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

---

## Features

- Displays "Hello World"
- Simple and user-friendly interface
- Runs on Android Emulator
- Beginner-friendly Android project

---

## Output

<img width="1366" height="720" alt="Screenshot 2026-07-25 200904" src="https://github.com/user-attachments/assets/31fc026e-60df-44e8-a22b-6a7b1cedde2b" />


Example:

```
-------------------------
|                       |
|                       |
|      Hello World      |
|                       |
|                       |
-------------------------
```

---

## Test Cases

### Test Case 1

**Test:** Launch the application

**Expected Result:**
Application opens successfully and displays "Hello World".

**Actual Result:**
Pass

**Screenshot:**
<img width="1366" height="720" alt="Screenshot 2026-07-25 200904" src="https://github.com/user-attachments/assets/16494362-f436-4a6b-abbd-58f237f00ec2" />


---

### Test Case 2

**Test:** Rotate the emulator

**Expected Result:**
The application continues to display "Hello World" without crashing.

**Actual Result:**
Pass

**Screenshot:**
<img width="1366" height="720" alt="Screenshot 2026-07-24 224714" src="https://github.com/user-attachments/assets/086852b7-cc9f-4e9e-be3a-dd7d185b8b5d" />


---

### Test Case 3

**Test:** Display student details in the application.

```
Hello World

Name : Tejashree DL
USN  : 25MCAR0124
```

**Expected Result:**
The application displays the student name and USN correctly.

**Actual Result:**
Pass

**Screenshot:**
<img width="1366" height="720" alt="Screenshot 2026-07-25 202031" src="https://github.com/user-attachments/assets/5d35b865-458b-45b1-b273-4cb160622358" />


---

## Learning Outcomes

- Learned the Android Studio development environment.
- Understood Android project structure.
- Learned how Activities work.
- Learned to create a simple user interface using XML.
- Learned how to run an Android application on an emulator.

---

## Author

**Tejashree DL**

**USN:** 25MCAR0124
