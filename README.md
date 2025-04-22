# Day05 – IT3213: Human Computer Interaction

This repository documents **Day 05** for the IT3213 – Human Computer Interaction course, focusing on **dynamic panels**, **scroll-triggered animations**, and **icon animations** using **Axure RP 9**.

---

## 🧪 Practical Overview
The goal of this session is to implement a **fixed navigation bar** and **animated UI elements** across two pages using Axure's interaction features.

---

## ✅ Progress Summary

### 📄 Page 01: Fixed Navigation Bar with Dynamic Panel 🔝
**Dynamic Panel Setup:**
- Grouped navbar icons into a dynamic panel.
- **Pinned to Browser**: Positioned at the top center of the screen.

**Scroll Interaction:**
- Show/hide the navbar dynamically based on scroll position (`Window.scrollY`).

---

### 📄 Page 02: Animated Navigation Bar with Bell Icon 🔔
**UI Elements:**
- Search button
- Axure logo
- Bell icon with animation

**Bell Icon Animation Logic:**
- **On Page Load:**
  - Rotate the bell icon **60° counterclockwise** (linear animation, 100ms duration)
  - Wait 100ms
  - Rotate the bell icon **60° clockwise** (linear animation, 100ms duration)
  - **Trigger the "Loaded" event again** to loop the animation indefinitely
    




