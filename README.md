📏 Resolution Scaler

`resolution_scaler.py` is a lightweight Python tool with a simple Tkinter-based UI that helps you quickly calculate and scale UI dimensions (in dp values) across multiple screen resolutions.
It’s designed for UI/UX designers and app developers who need consistent layouts across various device densities.

---

✨ Features

• Instant scaling — Updates all values as soon as you type (no “Calculate” button needed).
• Multiple presets — Comes with default resolutions:
320, 360, 400, 480, 600, 720, 800
• Two-column input — Supports both width and height scaling independently.
• Flexible — Works even if you only enter one of the two values (width or height).
• Expandable — Add or remove resolution presets directly from the UI.

---

🖥 How It Works

1. Enter a width or height value for any one resolution.
2. The app auto-calculates corresponding values for all other resolutions.
3. If you want, you can edit presets to add new resolutions or remove existing ones.

Scaling is calculated using proportional ratios based on the entered resolution value.

---

📷 Example Workflow

• Suppose you enter `48` for Width under resolution `360`.
• The tool instantly fills in proportional values for Width in all other resolutions.
• You can also enter a Height value — it will scale independently.

---

🚀 Installation & Usage

Prerequisites:
• Python 3.7+

Install Dependencies:
No extra dependencies are needed — uses only Python's built-in Tkinter library.

Run the Script:
python resolution\_scaler.py

---

🛠 UI Overview

Resolution List — Displays all available resolution presets (e.g., 320, 360, etc.).
Width Column — Enter a width value for any resolution — others update automatically.
Height Column — Enter a height value for any resolution — others update automatically.
Add Resolution — Add a custom resolution to the list.

---

📌 Notes

• Works best for dp/sp values used in mobile development.
• Calculations are real-time — no extra button clicks required.
• Both columns can be used independently.

---

📄 License

This project is licensed under the MIT License.

---

