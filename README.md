# a212577.github.io

# Diet Diary App

## Project Description
Diet Diary App is a mobile health monitoring application developed using Android Studio and Jetpack Compose. The application helps users track their Body Mass Index (BMI), daily activities, water intake, exercise recommendations, and weight progress. The goal is to encourage healthier lifestyle habits through simple health monitoring tools.

## SDG Theme

### SDG 3: Good Health and Well-Being

This application supports Sustainable Development Goal (SDG) 3 by helping users:

- Monitor BMI and weight status
- Track daily physical activities
- Monitor hydration through water intake tracking
- Track daily steps using smartphone sensors
- Receive exercise recommendations
- Maintain health records for long-term monitoring


## Features

### 1. BMI Calculator
- Calculate BMI using height and weight
- Display BMI category
- Provide diet suggestions

### 2. BMI History
- Save BMI records locally using Room Database
- View previous BMI calculations

### 3. Daily Diary
- Water intake tracking
- Step counter tracking using Android Sensor
- Weight tracking

### 4. Activity Tracker
- Add activities
- Delete activities
- Store activities using Room Database

### 5. Exercise Recommendations
- Display exercise suggestions
- Retrieve data from online API using Retrofit

### 6. Weight Progress
- Display weight progress visualization

### 7. Community Screen
- Community information and interaction page

### Database Implementation

Room Database is used for:
- BMI history records
- Activity records

Data remains available even after the application is closed.

### API Integration

Retrofit is used to fetch exercise recommendation data from an online API.

### Sensor Implementation

Android Step Counter Sensor is used to monitor the user's daily step count in real time.

## Technologies Used

- Kotlin
- Jetpack Compose
- Room Database
- Retrofit
- Android Step Counter Sensor
- Material 3 Design

## Setup Instructions

### Requirements
- Android Studio
- Android SDK 34 or later
- Internet connection

### Installation

1. Clone or download the project.
2. Open the project in Android Studio.
3. Allow Gradle Sync to complete.
4. Connect an Android device or start an emulator.
5. Run the application.

## Author
Aliya Putri Binti Roslan
A212577

### Permissions Required

The application requests:

```xml
<uses-permission android:name="android.permission.ACTIVITY_RECOGNITION"/>
This permission is used for step counting.
