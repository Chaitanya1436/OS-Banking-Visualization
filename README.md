### Deadlock and Concurrency Website live at - https://chaitanya1436.github.io/OS-Banking-Visualization/
The **Deadlock and Concurrency Website** is an interactive educational platform designed to help users understand and visualize critical concepts of operating systems such as **Lock Variables**, **Deadlocks**, **Banker’s Algorithm**, **Counting Semaphore**, and **Binary Semaphore**. The platform is specifically designed to simulate real-world banking scenarios, providing users with hands-on experience of how banks manage resources to ensure concurrency while avoiding deadlocks.

## 🌄 Project Preview
Here are some sample outputs and visualizations from the notebook:

<p align="center">
  <img src="OS Banking Gif.moov" alt="Gif from one of the algorithm" width="45%" />

</p>

### Objective
The main objective of this project is to offer an immersive learning experience where users can visualize and interact with the functioning of various OS concepts. By simulating resource management in a banking environment, the platform demonstrates how banks prevent and resolve deadlocks using different algorithms and techniques.

### Key Features
#### 🏠 Home Menu  
- A clean, user-friendly interface with a navigation menu.  
- Options include **Concurrency**, **Lock Variables**, **Deadlocks**, **Banker’s Algorithm**, **Counting Semaphore**, and **Binary Semaphore**.  

#### 🔄 Concurrency  
- Provides a detailed explanation of concurrency, demonstrating how multiple processes run simultaneously.  
- Simulates scenarios of parallel processing and process synchronization.  

#### 🔐 Lock Variable  
- Explains how lock variables prevent simultaneous access to shared resources.  
- Visualizes how locks ensure mutual exclusion and manage race conditions.  

#### ⚡ Deadlock  
- Illustrates real-world deadlock scenarios through simulations.  
- Explains how deadlocks occur when processes wait indefinitely for resources.  
- Demonstrates the conditions leading to a deadlock (**Mutual Exclusion, Hold and Wait, No Preemption, Circular Wait**).  

#### 🏦 Banker’s Algorithm  
- Offers an interactive simulation of **Banker’s Algorithm** to detect and prevent deadlocks.  
- Users can allocate and deallocate resources by selecting from different currency denominations (**₹10, ₹20, ₹50, ₹100, ₹500, ₹2000**).  
- Real-time visualization shows the state transitions of processes (e.g., **Waiting State, Blocked State, End State**).  
- Provides detailed reports indicating whether a deadlock has occurred and the actions taken to resolve it.  

#### 📊 Semaphore  
- Simulates both **Counting Semaphore** and **Binary Semaphore** concepts.  
- **Counting Semaphore** visualizes resource management when multiple instances are available.  
- **Binary Semaphore** showcases mutual exclusion using a simple lock/unlock mechanism.  
- Users observe how semaphores control access to critical sections.  

### Technologies Used
- **Frontend:** HTML, CSS, JavaScript for building an interactive and responsive user interface.  
- **Backend:** Python (if applicable) for processing data and logic management.  
- **Visualization Tools:** JavaScript-based libraries like **D3.js** or **Three.js** for visual simulations.  

### How it Works
1. **Interactive Selection:** Users select a desired concept from the homepage.  
2. **Simulation:** The system simulates a banking environment where currency denominations represent resources.  
3. **Visualization:** Users observe how processes interact with resources using **Lock Variables**, **Banker's Algorithm**, or **Semaphores**.  
4. **State Transition:** The website displays real-time state changes, e.g., processes moving from **Waiting** to **Blocked** or **End State**.  
5. **Deadlock Detection:** If a deadlock occurs, the system provides detailed feedback and possible resolutions.  

### Use Case Example
1. A user selects **Banker’s Algorithm** from the menu.  
2. They simulate a scenario by allocating resources like **₹100** and **₹500** to various processes.  
3. The system tracks resource requests and allocations.  
4. If a deadlock is detected, a notification is displayed, explaining the cause and suggesting preventive measures.  
5. The user can experiment with different scenarios to understand how deadlocks are avoided using the algorithm.  
