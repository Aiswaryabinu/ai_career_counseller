# 🤖 AI Virtual Career Counsellor – Internship Project Setup Guide

This project aims to build an AI-powered chatbot that recommends suitable career paths (Tech, Arts, Commerce, etc.) based on user interests, using Natural Language Processing (NLP) and interactive conversation.

This document covers the environment setup **up to creating and activating the virtual environment**.

---

## 📌 Why Python 3.10 (and NOT Python 3.12)?

As of now, **Rasa officially supports only up to Python 3.10**.  
Using newer versions like Python 3.12 will cause installation errors for Rasa and its dependencies.

> ✅ **Python 3.10 is stable, well-documented, and fully compatible with Rasa, NLTK, and Streamlit**.

---

## 📁 Project Folder Location

The entire project will be built inside this directory:

```
C:\Users\LENOVO\aicareerbot
```

You can open this path in **Command Prompt** or **VS Code Terminal**.

---

## ✅ Step-by-Step Setup (Up to Virtual Environment)

### 🔹 1. Download & Install Python 3.10

- Go to: https://www.python.org/downloads/release/python-31011/
- Download **Windows installer (64-bit)**.
- During installation, **check the box that says "Add Python to PATH"** ✅
- Complete the setup.

---

### 🔹 2. Verify Python Installation

After installing, open **Command Prompt** and run:

```bash
py -3.10 --version
```

You should see something like:

```
Python 3.10.11
```

If you see this — ✅ you're good to proceed.

---

### 🔹 3. Navigate to Your Project Folder

Open terminal and run:

```bash
cd C:\Users\LENOVO\aicareerbot
```

> This is where your entire chatbot project will live.

---

### 🔹 4. Create a Virtual Environment with Python 3.10

In the same terminal, run:

```bash
py -3.10 -m venv rasaenv
```

This creates a folder called `rasaenv` inside your project directory — it will contain all Python packages isolated from your system.

---

### 🔹 5. Activate the Virtual Environment

Run this command:

```bash
rasaenv\Scripts\activate
```

✅ You’ll know it’s activated when your terminal looks like this:

```
(rasaenv) C:\Users\LENOVO\aicareerbot>
```

From this point on, any Python packages (like Rasa or Streamlit) will be installed **only inside this virtual environment**.

---

## ✅ What's Next?

In the next phase, we will:

- Install Rasa, Streamlit, and NLTK
- Initialize a Rasa chatbot
- Create intents like `tech_interest`, `arts_interest`, etc.
- Build a Streamlit frontend

> 📄 This document ends at the virtual environment setup. Future phases will be documented separately.

---

## 👩‍💻 Developed by: [Your Full Name]  
Intern at Elevate Labs | July 2025
