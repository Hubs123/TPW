# ConcurrentProgramming – Multithreaded Bouncing Balls Simulation

This project was created as part of the **Concurrent Programming** course.  
It demonstrates the use of **multithreading** in C# by simulating bouncing balls moving inside a frame and colliding with each other.

## 📌 Project Description
The application is a simple graphical simulation where multiple balls move within a defined frame:

- Each ball runs in its own thread, updating its position concurrently.  
- Collisions are detected both with the frame boundaries and with other balls.  
- Synchronization mechanisms are used to prevent race conditions and ensure correct physics calculations.  

The project illustrates common challenges of concurrent programming, such as:

- thread management,  
- synchronization of shared resources,  
- avoiding race conditions and inconsistent state,  
- handling continuous updates in a graphical environment.

## 🛠️ Technologies

- **Language:** C#  
- **Framework:** .NET  
- **Environment:** Visual Studio  


