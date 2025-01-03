Work Manager Application:
- Review the work manager class from Android Jetpack

What is Work Manager?
- It is the recommended solution for persistent work. Work is persistent when it remains scheduled through app restarts and system reboots. Because most background processing is best accomplished through persistent work, WorkManager is the primary recommended API for background processing. Work manager simplifies and manages background tasks in android apps. It allows you to schedule and run tasks in the background, even when the app is not currently in the foreground.
- Work manager offers several advantages such as:
    - Handling tasks efficiently
    - Considering network connectivity
    - Considering device state
    - Supporting periodic scheduling
- Work Manager Definitions:
    - Worker:
        - Is a class that performs a background task. 
    - Work Request:
        - Defines the task to be executed and its constrains. Types of WorkRequest:
            - OneTimeWorkRequest
            - PeriodicWorkRequest
    - Work Manager:
        - The central component of managing background tasks. It is responsible for scheduling and executing (enqueing)
- Such tasks above include networking

Credits go to Abbass Masri
from The Complete Android 14 Developer Course
