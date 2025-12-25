# Web-Based Game Trilogy Using MediaPipe Hand Tracking Technology


|Bomber     |     Archer 1 |     Archer 2| 
|----------|-----------|--------------------------|
|![WhatsApp Image 2025-12-25 at 14 54 30 (2)](https://github.com/user-attachments/assets/915058b0-5b82-450c-8238-7cb44e20a3ed)|![WhatsApp Image 2025-12-25 at 14 54 30](https://github.com/user-attachments/assets/8273682f-c7e7-4f02-b1aa-2c0266e7bc04)|![WhatsApp Image 2025-12-25 at 14 54 30 (1)](https://github.com/user-attachments/assets/3446b167-d1a6-45de-b7d0-03a8c1fa6880)



This repository contains three web-based games that are fully controlled by hand movements (touchless) using Google’s **MediaPipe Hands** library.  
The project is built with **HTML5, CSS3, and JavaScript**.

---

## 🎮 About the Games

### 1. Bomber 
An action-based game where the player controls a character by moving their hand and destroys targets using specific gestures.

- **Mechanics:** Hand position tracking and closed-fist gesture interaction  
- **Objective:** Destroy all targets within the given time to advance to the next level

---

### 2. Archer 1 
A basic aiming game that combines a classic archery experience with webcam-based control.

- **Mechanics:** Single-hand cursor control and shooting at dynamic targets  
- **Visuals:** Traditional archery range theme

---

### 3. Archer 2 
An advanced archery simulation featuring physics-based arrows and a night-themed environment with platform-based enemies.

- **Mechanics:** Single-hand cursor control and shooting at static targets
- **Visuals:** Dark mode and platform-based level design

---

## ✨ Key Features

- **Real-Time Tracking:** Low-latency tracking of 21 3D hand landmarks using MediaPipe Hands  
- **No Additional Hardware Required:** Works with a standard webcam; no keyboard or mouse needed  
- **Gesture Recognition:** In-game actions triggered by gestures such as fist and open palm  
- **Web-Based:** Runs in modern browsers without additional installation

---

## 🚀 Installation and Running

## Clone the Repository
```bash
git clone https://github.com/mbahadirk/Mediapipe-on-Web-Games/
```
## Navigate to the Project Directory
```bash
cd Mediapipe-on-Web-Games
```
## Run the Project

Open [bomber.html](bomber.html) | [archer.html](archer.html) | [archer2.html](archer2.html) directly

OR run using a local server (e.g., VS Code Live Server)

Important: The getUserMedia API only works over HTTPS or on localhost (127.0.0.1) due to browser security policies.

## 🕹️ Controls and Gesture Guide

| Game     | Action    | Hand Movement / Gesture |
|----------|-----------|--------------------------|
| Bomber     | Throw Bomb| Move hand with closed palm |
| Bomber     | Drop Bomb | Opened fist |
| Archer 1&2 | Aim       | Closed hand with aiming to enemies |
| Archer 1&2 | Shoot     | Release your thumb  |

## 🛠️ Technologies Used

Frontend: HTML5, CSS3, JavaScript (ES6+)

Machine Learning: MediaPipe Hands

Infrastructure: TensorFlow.js

## 💡 Tips and Optimization

Lighting: Use a well-lit environment where the hand is clearly visible

Background: Prefer a plain background with a contrasting color

Camera Angle: Position the camera directly facing the hand at approximately 1 meter distance
