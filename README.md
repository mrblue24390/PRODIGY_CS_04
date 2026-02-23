# 🎓 Educational Keylogger – FOR LEARNING PURPOSES ONLY

<div align="center">

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Tests](https://img.shields.io/github/actions/workflow/status/yourusername/Educational-Keylogger/python-ci.yml)

**A Python tool to demonstrate keystroke logging mechanisms – strictly for educational use in controlled environments**

[Features](#features) • [Installation](#installation) • [Quick Start](#quick-start) • [Documentation](#documentation) • [Ethical Use](#-ethical-use--legal-warning)

</div>

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [How It Works](#how-it-works)
- [Usage Examples](#usage-examples)
- [Project Structure](#project-structure)
- [⚠️ Ethical Use & Legal Warning](#️-ethical-use--legal-warning)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## 🎯 Overview

The **Educational Keylogger** is a Python-based tool that demonstrates how keystroke logging works at a fundamental level. It captures keyboard events and logs them with timestamps. This project is intended **exclusively for educational purposes** – to help students and security enthusiasts understand:

- How keyloggers function
- The importance of defending against such tools
- Ethical considerations in cybersecurity

**⚠️ UNAUTHORIZED USE OF KEYLOGGERS IS ILLEGAL AND UNETHICAL. This tool must ONLY be used on systems you own or have explicit written permission to test.**

---

## ✨ Features

### 🔑 Core Functionality
| Feature | Description |
|---------|-------------|
| **Keystroke capture** | Records all key presses with timestamps |
| **Special key handling** | Detects Shift, Enter, Backspace, function keys, etc. |
| **Log to file** | Saves logs with timestamps and session metadata |
| **Auto‑stop safety** | Configurable time limit and emergency stop (ESC key) |

### 🛡️ Safety Features (Built‑in)
- **Explicit consent required** – user must accept terms before running
- **Time‑limited sessions** (default 5 minutes)
- **ESC key emergency stop** – press ESC to immediately terminate
- **File size limits** – prevents unlimited log growth
- **Log preview with warnings** – shows only first 500 chars with privacy notice
- **Automatic cleanup prompts** – asks to delete logs after session

### 📊 Output Options
- Console display with real‑time key logging
- Save logs to timestamped files
- Optional basic encryption demonstration

---

## 🛠️ Technology Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| **Python** | 3.8+ | Core programming language |
| **pynput** | 1.7.6+ | Keyboard event capture |
| **pytest** | 7.0+ | Unit testing framework |

---

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- Administrator/root privileges **not required** (but may be needed on some systems for global hooks)

### Step 1: Clone and Install

```bash
# Clone the repository
git clone https://github.com/yourusername/Educational-Keylogger.git
cd Educational-Keylogger

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
