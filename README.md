# CodeFlow 🌊

> **See your code come to life.**
> A powerful, real-time code execution visualizer that transforms static code into dynamic, interactive flowcharts.

![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-7.0-646CFF?logo=vite&logoColor=white)

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

## 💬 Issue Reporting

Since this is a **closed/private repository**, we rely on internal feedback to improve.

- **How to report**: Navigate to the [codeflow-feedback](https://github.com/Shabari-K-S/codeflow-feedback/issues) tab and use the provided templates.
- **What to include**:
    - A snippet of the code that caused the crash.
    - Expected vs. Actual flowchart output.
    - Browser version and OS.

---

**Made with 💙 by Shabari K S**
