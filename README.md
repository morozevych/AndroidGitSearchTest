# Android Developer Test

### Project Description
This Android application is developed using Kotlin (version 1.8.0) and utilizes various libraries and components for network operations and user interface management. It uses the Retrofit library for data exchange with a server and employs Android architecture components, including View Models, for managing the user interface state. Additionally, it integrates data binding for seamless data presentation and interaction.

### Assumptions:
The total results show the total repos matching terms string, not just the first 1000 that meet search conditions(including repos with empty languages). It is done based on the fact that in the task example, the total is not equal to the sum in the table.

### Requirements
An Android device or emulator with Android version 8.0 (Oreo) or higher is required to run the application. The minimum SDK version specified in the project is 26, and the target SDK version is 33.

### Dependencies
The project utilizes the following dependencies:
 * Kotlin: Kotlin programming language (version 1.8.0)
 * Retrofit: Library for network operations.
 * View Models: Android architecture components for managing the user interface state.
 * Data Binding: Android library for declarative data presentation and interaction.
 
### Instructions how to run: 
Just download the project from git and open it in the latest stable version Android Studio. After that, press the Run 'app' button.

In the unlikely event that Android Studio wouldn't be able to locate the SDK directory, you need to add local.properties file in the main project folder and add the Android SDK path.

For Mac:
```sdk.dir = /Users/USERNAME/Library/Android/sdk```
where USERNAME is your Mac username

For Windows: 
```sdk.dir=C\:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk```
where USERNAME is your Windows username

For Linux: 
```sdk.dir = /home/USERNAME/Android/Sdk```
where USERNAME is your Linux username


