# 🍔 Burger Restaurant Rush (3D Interactive Simulation)

**Burger Restaurant Rush** is a 3D time-management and cooking simulation game developed in Unity. While designed as an engaging gameplay experience, the project's core architecture focuses on **dynamic object interaction, real-time state management, and user interface (UI) integration** using C#.

This project demonstrates my ability to build structured 3D environments, manage complex user-task evaluations (e.g., verifying if a customer's specific order matches the assembled ingredients), and create responsive UI systems.

## 🚀 Technical Highlights & Transferable Skills

The following systems were developed from scratch, showcasing skills directly applicable to interactive 3D applications, training simulators, and XR environments:

*   **Task Validation & Assessment Logic:** 
    *   Developed a dynamic order-tracking system. The system constantly evaluates the player's actions against a requested goal (customer order), tracks the sequence of actions, and calculates success/failure states in real-time. 
    *   *Technical aspect:* Object-Oriented C# scripts handling state machines and logical condition checking.
*   **3D Object Interaction & Physics:** 
    *   Implemented robust mechanics for selecting, grabbing, and combining 3D objects within the scene.
    *   *Technical aspect:* Utilizing Unity's Rigidbody, Colliders, and Raycasting systems to ensure smooth user interaction with environmental elements.
*   **Dynamic UI/UX Management:** 
    *   Created intuitive, real-time user interfaces that display current objectives, time limits, and feedback without breaking the 3D immersion.
    *   *Technical aspect:* Unity UI Canvas, event-driven UI updates, and dynamic text/image rendering based on game state.
*   **Level & Scene Architecture:** 
    *   Structured a multi-level progression system (3 distinct levels) with increasing difficulty, demonstrating the ability to manage scene loading, persistent data across scenes, and structured project hierarchies.

## 🛠️ Technologies Used
*   **Game Engine:** Unity 3D
*   **Programming Language:** C# (Object-Oriented Programming)
*   **Key Concepts:** Event Delegates, Collision Detection, UI Canvas Management, Scene Management, State Tracking.

## 🎮 Gameplay Overview
Players take on the role of a chef managing a busy burger restaurant. The core loop involves:
1.  **Receiving Orders:** UI displays randomized customer requests.
2.  **Preparation (Interaction):** Moving between stations to cook meat, chop vegetables, and assemble ingredients in the correct order.
3.  **Delivery & Evaluation:** The system checks the final assembled 3D object against the initial order data, scoring the player based on accuracy and speed.

## 📸 Screenshots & Gameplay

![Açıklama metni](images/1.png)

Figure 1: User Interaction & UI Mapping. Demonstrating the dynamic recipe tracking system (UI Canvas) and core interaction mapping (Grab/Drop/Process) utilizing Unity's Raycasting and Colliders.

![Açıklama metni](images/2.png)

Figure 2: Scene Architecture & Real-Time UI. The primary gameplay loop featuring a real-time timer, score tracking, and an active task list updating dynamically based on state logic.

![Açıklama metni](images/3.png)

Figure 3: Asynchronous State Management. Contextual UI (radial timer) triggered during object processing, demonstrating state tracking for independent 3D elements.

![Açıklama metni](images/4.png)

Figure 4: Task Validation System. The exact moment the system evaluates the assembled 3D object against the target data (customer order) to calculate the score and trigger NPC feedback.

![Açıklama metni](images/5.png)

Figure 5: Environmental Hazards & Level Progression. Advanced scene management showing dynamic obstacle integration (lava zones) and complex collision detection across different difficulty levels.

![Açıklama metni](images/6.png)
![Açıklama metni](images/7.png)
![Açıklama metni](images/8.png)

---
Bu README dosyası, projenin daha sonraki aşamalarında detaylı bilgilerle güncellenecektir.
