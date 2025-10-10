# **Kard Race – Module 3 Public Report**

**August 4 – September 12, 2025**

## **About the Game**

This module marked a key milestone: the **integration of intelligent AI behaviors**, the **academic validation** of these systems, and the **expansion of interactive interfaces** for deckbuilding and telemetry.

---

## **Module 3 Sprint Highlights**

### **Sprint 1 – GOAP System & Debug HUD**

The first sprint delivered the **initial implementation of the GOAP (Goal-Oriented Action Planning)** system, enabling AI drivers to plan and execute decisions dynamically based on goals and world states.
A **Debug Telemetry HUD** was also developed to monitor vehicle data such as grip, speed, and slip in real time, facilitating fine-tuning of car physics and AI reactions.

**Key Achievements:**

* Modular GOAP system built with `GOAPAgent`, `GOAPAction`, and `GOAPPlanner` classes.
* Integration with car data sensors for world-state awareness.
* Real-time telemetry interface for development and balancing.

---

### **Sprint 2 – Tech Article & Deckbuilding HUD**

This sprint combined **academic structuring** and **player interface design**.
The first draft of the **technical article** was produced, defining the research scope, hypotheses, and evaluation methods for AI behavior in hybrid game systems.
Simultaneously, the **Deckbuilding HUD** was implemented, allowing players to visualize and interact with their cards, HP, and mana.

**Key Achievements:**

* Established methodology and metrics for AI adaptability and immersion evaluation.
* Created a modular card HUD based on MVC architecture.
* Enabled drag-and-drop card interaction and real-time resource display.
* Strengthened the academic and interactive layers of the project.

---

### **Sprint 3 – Integrated GOAP AI & Article Draft**

The third sprint delivered a **fully integrated and layered AI system** capable of coordinating multiple driving strategies—Normal, Attack, and Defense—based on GOAP planning and utility evaluation.
At the same time, the **article draft** evolved into an analytical document comparing predicted outcomes with experimental data from race simulations.

**Key Achievements:**

* Advanced **AI architecture** with clear separation between *Navigator (CarAI)* and *Driver (AdvancedDriver)*.
* Utility-based GOAP system evaluating combined strategies (≥3 actions).
* Real-time strategy switching based on race context (rivals ahead/behind).
* First **experimental validation** of AI adaptability and emergent behavior.
* Extended academic article with results and analysis on performance metrics such as lap consistency, overtakes, and collisions.

---

## **Key Achievements of Module 3**

* **Dynamic and intelligent AI** capable of adaptive driving strategies through GOAP and utility evaluation.
* **Research foundation established**, including hypothesis testing and result documentation for the academic article.
* **Deckbuilding interface completed**, offering a solid base for future gameplay integration.
* **Debug tools and telemetry HUD** implemented, supporting fine-tuning of vehicle and AI behaviors.

---

## **What’s Next (Module 4 Preview)**

Module 4 will focus on **finalizing the academic article**, implementing **sound and visual effects systems**, and introducing **player customization features** such as card and vehicle editors.
This phase will transition *Kard Race* toward a fully polished prototype, connecting technical research with player experience and presentation.
