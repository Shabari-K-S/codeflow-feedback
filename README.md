# CodeFlow 🌊

**See your code come to life.**
*A powerful, real-time code execution visualizer that transforms static code into dynamic, interactive flowcharts.*

[**Visit the App**](https://codeflow-app.vercel.app) • [**Report a Bug**](https://github.com/Shabari-K-S/codeflow-feedback/issues) 

---

## 📖 Overview

**CodeFlow** is designed to bridge the gap between reading code and understanding its execution. By parsing standard source code, it generates accurate, real-time flowcharts and visualizes the step-by-step execution state.

Whether you are debugging complex logic, teaching algorithms, or simply exploring how code works under the hood, CodeFlow provides the visual context you need.

## ✨ Key Features

### 🔍 Deep Execution Visualization
- **Line-by-Line Tracing**: Watch the instruction pointer move through your code in real-time.
- **Variable Inspector**: Monitor the state of local/global variables, arrays, and objects as they mutate.
- **Sandboxed Environment**: Safe execution with support for standard built-ins.
- **Call Stack Tracking**: Visualize stack frames pushing and popping during function calls.
- **Execution Timeline**: Scrub through execution history to pinpoint logic errors.

### 🎨 Dynamic Flowcharts
- **Auto-Generation**: Instantly converts code into an SVG-based flowchart.
- **Control Flow**: Visualizes loops (`for`, `while`), conditionals (`if/else`, `switch`), and exception handling (`try/catch`).
- **Smart Layout**: Automatically arranges nodes for maximum readability.

### 🛠️ Multi-Language Support
- 🟨 **JavaScript/TypeScript**: Custom AST interpreter using `@babel/parser`.
- 🟦 **Python**: Client-side execution powered by `filbert`.
- ⬜ **C/C++**: Custom memory simulator with support for pointers and `malloc`/`free`.
- ☕ **Java**: Supported via `java-parser` and a custom Java runtime simulator.

---

> [!IMPORTANT]
> ## 🤝 Community Feedback & Issues
> We're building **CodeFlow** to help developers learn and build faster. Your feedback is essential to making this tool more reliable.

Found a bug or have a feature idea? Please follow these steps:

1. **Check for duplicates**: Browse [existing issues](https://github.com/Shabari-K-S/codeflow-feedback/issues) first.
2. **Open a new issue**: Use the [feedback repository](https://github.com/Shabari-K-S/codeflow-feedback/issues/new/choose).
3. **Share your code**: Include the snippet that caused the issue using **Markdown code blocks**:
   ```
   ```javascript
   // Your code here
   ```⠀
   ```
4. **Visual Context**: If the flowchart looks incorrect, please **attach a screenshot**! 
5. **Environment**: Mention your browser (e.g., Chrome, Safari) and OS.

<div align="center">
  <br />
  Made with 💙 by <b>Shabari K S</b>
</div>
