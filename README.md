# CodeFlow 🌊

> **See your code come to life.**
> A powerful, real-time code execution visualizer that transforms static code into dynamic, interactive flowcharts.

## 📖 Overview

CodeFlow is a developer tool designed to bridge the gap between reading code and understanding its execution. By parsing standard JavaScript, TypeScript, Python, C, and **Java** code, CodeFlow generates accurate, real-time flowcharts and visualizes the step-by-step execution state.

Whether you are debugging complex logic, teaching algorithms, or simply exploring how code works under the hood, CodeFlow provides the visual context you need.

## ✨ Key Features

### 🔍 Deep Execution Visualization
- **Line-by-Line & Expression Tracing**: Watch the instruction pointer move through your code in real-time.
- **Variable Inspector**: Monitor the state of local/global variables, arrays, and objects as they mutate.
- **Sandboxed Environment**: Safe execution with support for standard built-ins.
- **Call Stack Tracking**: Visualize stack frames pushing and popping during function calls and recursion.
- **Execution Timeline**: Scrub through execution history to pinpoint logic errors.

### 🎨 Dynamic Flowcharts
- **Auto-Generation**: Instantly converts code into an SVG-based flowchart.
- **Control Flow**: Visualizes loops (`for`, `while`), conditionals (`if/else`, `switch`), and exception handling (`try/catch`).
- **Smart Layout**: Automatically arranges nodes for maximum readability using D3 and Dagre.

### 🛠️ Multi-Language Support
- **JavaScript/TypeScript**: Custom AST interpreter using `@babel/parser`.
- **Python**: Client-side execution powered by `filbert`.
- **C**: Custom memory simulator with support for pointers, structs, and `malloc`/`free`.
- **Java**: **[NEW]** Supported via `java-parser` and a custom Java runtime simulator.

## 🚀 Visit the App

You can access the live tool and start visualizing your code at:
**[codeflow-app.vercel.app](https://codeflow-app.vercel.app)**

---

## 🤝 Community Feedback & Issues

We're building **CodeFlow** to help developers visualize and understand their code better. Your feedback is essential to making this tool more powerful and reliable.

Found a bug? Have a feature request? Please let us know!

1. **Check for duplicates**: Browse [existing issues](https://github.com/Shabari-K-S/codeflow-feedback/issues) to see if your feedback has already been shared.
2. **Open a new issue**: Use our [issue templates](https://github.com/Shabari-K-S/codeflow-feedback/issues/new/choose).
3. **Share your code**: To help us debug, please include the snippet that caused the issue using **Markdown code blocks**:
   ```
   ```javascript
   // Your code here which you used in codeflow
   ```
   ```
4. **Visual Context**: If the flowchart looks incorrect or the UI crashed, please **attach a screenshot**! A picture is worth a thousand lines of code.
5. **Environment**: Mention your browser (e.g., Chrome, Firefox) and OS.

Thank you for helping us grow! 🌊

---

**Made with 💙 by Shabari K S**

