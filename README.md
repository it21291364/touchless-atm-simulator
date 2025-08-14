# Touchless ATM Simulator 🏦💳

A **browser-based, touchless ATM simulator** powered by **MediaPipe Hand Tracking** that lets you navigate menus, enter PINs, and withdraw cash **without touching your keyboard or mouse** — just using your hand gestures in front of your webcam.  

This project mimics a **real ATM user experience**, complete with:
- Card insertion animations
- PIN entry and validation
- Multiple transaction types
- Receipts
- Balance display
- Mini statements
- Cash counting animations
- Dwell-to-click gesture control

---

## 🚀 Features

- **Touchless Control:** Use your index finger to point at on-screen buttons; dwell for 0.75 seconds to click.
- **Realistic ATM UX:**
  - Welcome screen with card insert prompt
  - Card reading animation
  - PIN entry with masking and retries
  - Transaction menu
  - Withdraw (preset & custom amounts)
  - Balance inquiry
  - Mini statement
  - Receipt printing
  - Card ejection flow
- **Custom Withdrawal Amount:** On-screen numeric keypad for entering amounts.
- **Backspace Support:** Remove the last digit when entering PIN or amounts.
- **Smooth Pointer Tracking:** Interpolated pointer for stable gesture control.
- **Mirrored Movements:** Pointer follows your hand naturally (move left, pointer goes left).
- **Responsive Design:** Works in modern browsers on desktop/laptop with webcam.

---

## 🛠️ Technologies Used

- **HTML5 / CSS3 / JavaScript (Vanilla)**
- **MediaPipe Hands** for real-time hand landmark detection
- **Canvas API** for pointer rendering
- **Web Audio API** for feedback beeps

---

## 📦 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/touchless-atm-simulator.git
   cd touchless-atm-simulator
