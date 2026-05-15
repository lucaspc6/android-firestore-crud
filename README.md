
# Android Firestore CRUD

Android Firestore CRUD is a mobile application built with Kotlin and Jetpack Compose to demonstrate CRUD operations using Firebase Cloud Firestore as a NoSQL database.

The project focuses on basic mobile data management features, including registering, consulting, and updating records through an Android interface integrated with Cloud Firestore.

---

## Overview

This project was developed as an Android application using Kotlin, Jetpack Compose, Firebase, and Cloud Firestore.

The application demonstrates how an Android app can interact with a cloud-hosted NoSQL database to perform basic data operations.

The main goal of this project is to practice Android development fundamentals, Jetpack Compose UI construction, Firebase integration, and Cloud Firestore data persistence.

---

## Features

- Register records in Cloud Firestore
- Consult stored records
- Update existing records
- Android mobile interface built with Jetpack Compose
- Firebase project integration
- Cloud Firestore database usage
- Kotlin-based Android project structure

---

## Tech Stack

- **Kotlin**
- **Android**
- **Jetpack Compose**
- **Firebase**
- **Cloud Firestore**
- **Gradle Kotlin DSL**
- **Android Studio**

---

## Architecture

The project follows a standard Android project structure generated for Kotlin-based applications.

The visible repository structure includes:

- an `app/` module for the Android application;
- Gradle wrapper files for project execution;
- Kotlin-based Gradle configuration files;
- Firebase/Firestore integration requirements.

The application uses Cloud Firestore as the database layer for storing and retrieving application data.

---

## Project Structure

```text
android-firestore-crud/
├── .idea/
├── app/
├── gradle/
├── .gitignore
├── README.md
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
└── settings.gradle.kts
```

### Main Directories and Files

- `app/`  
  Contains the Android application source code and app-level configuration.

- `gradle/`  
  Contains Gradle wrapper files used to build and run the project consistently.

- `build.gradle.kts`  
  Root Gradle build configuration using Kotlin DSL.

- `settings.gradle.kts`  
  Defines project-level Gradle settings.

- `gradle.properties`  
  Stores Gradle-related project properties.

- `gradlew` and `gradlew.bat`  
  Gradle wrapper scripts for Unix-based systems and Windows.

- `README.md`  
  Project documentation.

---

## Prerequisites

Before running this project, make sure you have:

- Android Studio Koala Feature Drop 2024.1.2 Patch 1 or newer
- A Firebase account
- A Firebase project created
- Cloud Firestore enabled in the Firebase project
- Android development environment properly configured

---

## Firebase Setup

To run the application with FirebaseTo run the application with Firebase:
cd android-firestore-crud
```

Open the project in Android Studio.

Wait for Gradle sync to complete.

---

## Running the Project

To run the application:

1. Open the project in Android Studio.
2. Configure Firebase according to the Firebase setup section.
3. Select an Android emulator or physical device.
4. Run the application using Android Studio.

Alternatively, you can build the project using Gradle:

```bash
./gradlew build
```

On Windows:

```bash
gradlew.bat build
```

---
