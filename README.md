# Dynamic Mathematical Clock

An interactive algorithmic canvas clock that transforms standard digital timekeeping into a visual geometric experience using polar coordinates and trigonometric calculations.

---

## 📌 Project Overview
Dynamic Mathematical Clock uses polar coordinates and continuous angle mapping to draw concentric radial arcs representing elapsed hours, minutes, seconds, and milliseconds. Rather than traditional ticking hands, time is rendered as expanding colorful circular paths around a centered digital readout and polar-aligned numerals.

### Key Features
- **Trigonometric Coordinate Mapping**: Computes radial positions for numerals and concentric arcs using polar-to-Cartesian trigonometry ($\sin\theta$, $\cos\theta$).
- **Continuous Millisecond Tracking**: Features an inner high-speed sweep arc mapped to fractional milliseconds ($0$ to $1000\text{ ms} \rightarrow 0^\circ$ to $360^\circ$).
- **Real-Time Calendar & Digital Display**: Shows standard 12-hour AM/PM time and dynamic date display.
- **Pure Client-Side Rendering**: Uses HTML5 Canvas and p5.js with zero server requirements.

---

## 🛠️ Languages, Tools & Software Used
- **Languages**: JavaScript (ES6+), HTML5, CSS3
- **Libraries & Frameworks**: [p5.js](https://p5js.org/) (Creative Computing & Canvas API)
- **Development Tools & Software**: Visual Studio Code, Git, GitHub, Modern Web Browsers (Chrome, Edge, Firefox)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/KarimAL-Shamy/Dynamic-Mathematical-Clock.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Dynamic-Mathematical-Clock
   ```
3. Open `index.html` in any web browser:
   - On Windows: Double-click `index.html` or run:
     ```powershell
     Start-Process index.html
     ```
   - Or serve using VS Code Live Server / any static HTTP server.

---

## 👤 Author
**Karim Hassan**  
- Portfolio: [karimal-shamy.github.io](https://karimal-shamy.github.io/)  
- GitHub: [@KarimAL-Shamy](https://github.com/KarimAL-Shamy)
