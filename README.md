# 🏥 Unity Modular Health System & Debug UI

A clean, reusable, and event-driven Health System developed in Unity. This project features a built-in **Debug Dashboard** to test damage, healing, and death mechanics in real-time without needing to modify code during play mode.

## 📸 Preview
<img width="567" height="295" alt="Ekran görüntüsü 2025-12-17 160146" src="https://github.com/user-attachments/assets/cebc7bd5-8b17-432e-a043-016be4e7176e" />


## ✨ Key Features

### 1. Modular Health Logic (`PlayerHealth.cs`)
* **Event-Driven Architecture:** Uses C# Actions (`OnTakeDamage`, `OnHeal`, `OnDeath`) to decouple logic from UI.
* **Clean & Scalable:** Easy to integrate into any character or enemy script.

### 2. Debug & Testing Dashboard
Includes a custom UI panel to simulate gameplay scenarios instantly:
* **Variable Damage Testing:** Buttons to apply specific damage amounts (-10, -25, -50).
* **Healing Mechanics:** Test partial healing (+20) and full restore (Full Heal).
* **Kill & Reset:** Instantly trigger death events or reset the player's state.

### 3. Dynamic UI
* Real-time Health Bar (Slider) updates.
* Dynamic Health Text (e.g., "65/100") integration.

## 🚀 Getting Started

1.  Clone or download this repository.
2.  Open the project in Unity (2022.3 or later).
3.  Open the `SampleScene`.
4.  Press **Play** and use the on-screen dashboard to test the mechanics!

## 🛠️ Tech Stack
* **Engine:** Unity 2022+
* **Language:** C#
* **Patterns:** Observer Pattern (C# Events), UI Management

---
*Developed for educational purposes and rapid prototyping.*
