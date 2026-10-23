# CalcBoard Duo 🧮✏️

A responsive dual-screen Calculator and Blackboard application built with **Angular 22** and **Ionic 7.2**, featuring modern standalone architecture and Signal-driven reactivity.

Designed to emulate dual-screen hardware like the Microsoft Surface Duo and web tablets, **CalcBoard Duo** provides a side-by-side computation and sketchpad experience when used in landscape mode, and collapses gracefully into a focused single-screen calculator in portrait mode.

---

## ✨ Features

- **📱 Adaptive Dual-Screen Layout**:
  - **Landscape / Tablet Mode**: Displays a split-screen view with a full-featured calculator on the left and a digital draft/blackboard canvas on the right.
  - **Portrait Mode**: Dynamically hides the sketchpad to offer an optimized single-column calculation experience.
- **🔢 Full Calculator & History**:
  - Basic arithmetic operations (`+`, `-`, `×`, `÷`, `%`).
  - Memory / computation history drawer with one-tap recall.
  - Clear history option and live equation preview.
- **✏️ Digital Blackboard & Sketchpad**:
  - HTML5 Canvas supporting smooth mouse and touch input.
  - Pen tool with color palette options (Chalk White, Math Yellow, Electric Cyan, Neon Pink, Mint Green).
  - Eraser tool, multi-level Undo stack, and canvas clearing.
- **⚡ Modern Stack**:
  - Built with **Angular Standalone Components** (`standalone: true`).
  - Utilizes Angular **Signals** for crisp reactive state updates.
  - Styled with Ionic UI components and utility-first CSS.

---

## 🚀 Tech Stack

- **Framework**: [Angular 22](https://angular.dev/)
- **UI Toolkit**: [Ionic 7.2](https://ionicframework.com/)
- **Icons**: [Ionicons](https://ionic.io/ionicons)
- **Language**: TypeScript
- **Architecture**: Standalone Components & Angular Signals

---

## 🛠️ Getting Started

### Prerequisites

Ensure you have Node.js installed along with the Angular and Ionic CLIs:

```bash
npm install -g @angular/cli @ionic/cli
```

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/geoffembuscad0/Basic-Angular-Ionic-Calculator.git
   cd Basic-Angular-Ionic-Calculator
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   ionic serve
   ```
   The application will automatically open in your browser at `http://localhost:8100`.

---

## 📂 Project Structure

```text
src/
└── app/
    ├── app.component.ts      # Main standalone app logic (Signals, Canvas & Calc logic)
    ├── app.component.html    # Split-screen responsive grid structure
    ├── app.component.scss    # Custom layout & responsive CSS rules
    └── app.routes.ts         # Standalone routing configuration
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/geoffembuscad0/Basic-Angular-Ionic-Calculator/issues).

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).