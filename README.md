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

## Database

This project uses **Cloud Firestore**, Firebase’s NoSQL cloud database.

Cloud Firestore is used to persist and retrieve application records for the CRUD workflow.

---

## Security Notes

When working with Firebase and public repositories:

- Do not commit private credentials.
- Review Firebase security rules before using the project in production.
- Avoid exposing sensitive project configuration.
- Use environment-specific Firebase projects when possible.
- Treat public repositories as visible to everyone.

---

## Testing

No custom automated tests were verified in the available repository view.

If Android tests are added in the future, they can typically be executed from Android Studio or through Gradle.

Example:

```bash
./gradlew test
```

---

## Screenshots

Screenshots are recommended to improve the visual presentation of this repository.

Suggested screenshots:

- Main application screen
- Record creation screen
- Record listing or consultation screen
- Record update screen
- Firebase/Firestore data example, if appropriate and without sensitive data

---

## Future Improvements

Potential improvements for this project include:

- Add screenshots to the README
- Document the Firestore collection structure
- Add form validation feedback
- Add delete operation if it is not already implemented
- Add automated tests for data operations
- Improve UI documentation
- Add a short demo GIF showing the CRUD flow
- Document Firebase security rules used during development

---

## Author

**Lucas Carvalho**

GitHub: [@lucaspc6](https://github.com/lucaspc6/)

1. Create a project in the Firebase Console.
2. Add an Android app to the Firebase project.
3. Enable Cloud Firestore.
4. Download the `google-services.json` file from Firebase.
5. Add the `google-services.json` file to the Android app module as required by Firebase.

> Do not expose private credentials, secrets, or production Firebase configurations in public repositories.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/lucaspc6/android-firestore-crud.git
```

Access the project directory:

