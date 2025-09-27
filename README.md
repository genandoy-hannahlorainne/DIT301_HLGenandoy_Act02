# Reflection on Activity 2

## What did I observe about the app lifecycle when switching between screens or minimizing the app?
I observed that when switching screens, the current **Activity** pauses and then stops, while the new Activity is created, started, and resumed. 
When I minimize the app, the current Activity pauses and stops, potentially saving its instance state if the system needs resources. When I return to a 
minimized app, the Activity restarts, starts, and resumes, and it may even be recreated if its process was killed. 

## What did I learn about the activity management in Android?
I learned that Android manages Activities using a stack, often referred to as the **back stack**. When a new Activity starts, it is pushed onto the top of 
the stack and becomes the active Activity. When I press the back button or the Activity finishes, it is popped off the stack, and the previous Activity in the stack resumes. 
This stack-based management dictates my navigation flow and how Activities transition through their lifecycle states.
