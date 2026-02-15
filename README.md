# 🌌 CS Level 5: Digital Garden (The Nexus)

![Project Status](https://img.shields.io/badge/Status-Active-emerald?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20Tailwind%20%7C%20JS-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

> **"Knowledge Blooms Here."** > A next-generation, interactive study hub transforming the CS Level 5 curriculum into a visual masterpiece.

---

## 📖 Overview

**CS Level 5 Digital Garden** is not just a collection of notes; it is a **Single-Page Application (SPA) experience** built with pure HTML5 and Tailwind CSS. It transforms static university slides (SEU) into an immersive, responsive, and interactive web environment.

Designed for Computer Science students, this project replaces boring PDFs with **Holographic UI**, **Interactive Quizzes**, and **Deep-Dive Summaries**, all wrapped in a stunning Ethereal Glass aesthetic.

---

## ✨ Key Features

### 🎨 **Ethereal Glass UI**
A state-of-the-art interface featuring **Frosted Glassmorphism**, 3D Tilt effects, and fluid animations. The design is built to reduce cognitive load while maintaining a high-tech vibe.

### 🌗 **Dynamic Day/Night Cycle**
* **☀️ Morning Aurora:** A soft, pastel gradient mesh for focused daytime study.
* **🌑 Deep Space Nebula:** A dark, glowing environment for late-night coding sessions.
* *Switch seamlessly with a single toggle.*

### 🌍 **Bilingual Accessibility**
Designed with the local context in mind, the architecture supports **Arabic/English** toggling to assist students in bridging language gaps in complex technical concepts.

### ⚔️ **The Gauntlet (Interactive Quizzes)**
A robust JavaScript-based Quiz Engine:
* **70+ Questions** per subject (Midterm & Final scopes).
* **Real-time Scoring** and feedback.
* **Professor's Insight:** Detailed explanations for every answer.

### 🧠 **The Vault (Summaries)**
Comprehensive "Type C" review pages that aggregate entire modules into a single "Visual Compendium," replacing the need for textbooks during exam weeks.

---

## 📚 The Curriculum

This repository covers the complete **Level 5 Computer Science** track:

| Code | Course Name | Theme Color | Focus |
| :--- | :--- | :--- | :--- |
| **CS353** | 🧩 **Design and Analysis of Algorithms** | `Rose (Red)` | Complexity, Big O, Graph Theory |
| **CS352** | 📊 **System Analysis and Design** | `Blue` | SDLC, UML, Architecture |
| **CS350** | 🗄️ **Introduction to Database** | `Amber (Orange)` | SQL, Normalization, Storage |
| **CS351** | 💻 **Operating Systems** | `Emerald (Green)` | Kernel, Process Mgmt, Security |

---

## 🛠️ Technical Architecture

This project follows a **"Zero-Build"** philosophy. No npm, no React, no build steps. Just pure, optimized web technologies.

* **Core:** Semantic HTML5.
* **Styling:** Tailwind CSS (via CDN) for utility-first design.
* **Logic:** Vanilla JavaScript (ES6+) for the Quiz Engine, Theme Toggling, and 3D Tilt effects.
* **Icons:** FontAwesome 6.
* **Fonts:** `Outfit` (Modern Sans) & `Cairo` (Arabic Support).

### Project Structure
```bash
CS-lvl5/
├── index.html          # The Root Portal (Holographic Dashboard)
├── CS351/              # Operating Systems Module
│   ├── index.html      # Subject Hub
│   ├── module1.html    # Deep Dives...
│   ├── ...
│   ├── midterm-quiz.html  # JS Quiz Engine
│   └── final-review.html  # Visual Summary
├── CS350/              # Database Module
├── CS352/              # System Analysis Module
└── CS353/              # Algorithms Module