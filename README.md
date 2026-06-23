# AI Medical Symptom Router
<img width="1912" height="926" alt="Screenshot 2026-06-23 202919" src="https://github.com/user-attachments/assets/b4987b14-cf19-436d-ba86-227b579dd956" />
<img width="1893" height="917" alt="Screenshot 2026-06-23 202940" src="https://github.com/user-attachments/assets/206a137a-0706-45c1-bbdc-cf5bc3d6eb71" />


A clean, responsive web dashboard that helps patients find the right medical specialist based on the health symptoms they type. 

## 💡 The Problem & Solution
*   **The Problem:** Many patients do not know which doctor to visit when they feel sick. For example, they might visit a general doctor when they actually need a skin specialist (Dermatologist), wasting both time and money.
*   **The Solution:** This app lets patients type how they feel in plain English. The built-in AI logic instantly analyzes the text, recommends the correct specialist, and gives a simple reason why.

---

## 🛠️ Tech Stack

*   **HTML5:** For a clean, structured web layout.
*   **Tailwind CSS:** For a modern, clean, and mobile-friendly user interface.
*   **Vanilla JavaScript (ES6+):** For handling user clicks, processing data, and updating the screen without reloading.
*   **Vercel / Local Host:** For deploying and running the application smoothly.

---

## ⚡ Core Features

*   **Symptom Analyzer:** Takes everyday language (e.g., "itching skin" or "chest pain") and identifies the right doctor category.
*   **Dynamic Priority Tags:** Automatically displays a color-coded alert badge (**Red for Urgent Care**, **Green for Routine Checkups**) based on the severity of the symptoms.
*   **Demo Optimization Button:** Includes a 1-click "Load Sample" button to instantly fill in text and demonstrate the app quickly during interviews.
*   **State Management:** Shows a clean loading spinner while the AI logic processes the text in the background.

---

## 🚀 How to Run the Project

Since this project is built cleanly with pure frontend web standards, you can run it instantly without installing heavy packages.

### Option 1: Direct Run (Windows terminal)
Open your terminal in the project folder and type:
```bash
start symptom-router.html
