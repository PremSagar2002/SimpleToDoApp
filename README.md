# Android Simple To Do App

## Overview

This repository contains the source code for a simple yet valuable Task Reminder App for Android. The app is designed to help users keep track of their tasks by providing features such as task registration, displaying tasks in a list, and sending reminders through notifications.

## Features

1. **Task Registration:** Users can register new tasks, including setting the date and time for scheduling the job.
2. **Task List:** Display all the tasks in the form of a list using RecyclerView or ListView.
3. **Reminders:** Keep reminders for tasks through notifications.

## Flow of the Application

The application follows a user-friendly flow to ensure a seamless experience:

1. **Showing Reminders:** Utilizes RecyclerView or ListView to display reminders on the home screen.
2. **Adding Tasks:** Includes a floating action button on the home screen to allow users to add new tasks.
3. **Database Storage:** Stores reminders in an SQLite database.
4. **Alarm Setting:** Utilizes AlarmManager to schedule tasks and set alarms.
5. **Notification Display:** Uses NotificationManager and PendingIntent to display notifications.
6. **Manifest Declarations:** Updates the Manifest file with necessary declarations and permissions.



## Getting Started

Follow these steps to start working on the Android Task Reminder App:

1. Download and install Android Studio.
2. Extract the Zip folder.
3. Open the project in Android Studio.
4. Make sure to meet the prerequisites gradle 7.2 and Amdroid SDK 29
5. Build and run the app on an Android emulator or device.

## Technology Stack

- Android Studio
- Java
- XML
- SQLite Database
