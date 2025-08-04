# 🥗 Tracalorie JS Project

A lightweight calorie tracking web application built with **Vanilla JavaScript**, following the **Module Controller Pattern** and using **IIFEs** for encapsulation and separation of concerns. It allows users to track meals and their calorie intake with persistent data storage using `localStorage`.

---

## 📌 Project Purpose

This project was built to:

- Practice **modular programming** with JavaScript.
- Implement **IIFE-based module patterns** to organize code into logical units (UI Controller, Storage Controller, App Controller, etc.).
- Understand **state management** without frameworks.
- Store and manage data using the **browser's localStorage API**.
- Build a responsive and interactive UI with **vanilla JS, HTML, and CSS**.

---

## 🚀 Features

- ✅ Add meals and their calorie counts  
- ✅ Edit existing meals  
- ✅ Delete individual meals  
- ✅ View total calories consumed  
- ✅ Clear all meals at once  
- ✅ Persist data using `localStorage`  
- ✅ Fully modular code using **IIFE + Controller pattern**

---

## 🧠 Tech Highlights

### ✅ Module Controller Pattern

The project is broken into 4 key modules, all implemented using IIFE:

1. **Storage Controller**:  
   - Handles all `localStorage` interactions  
   - Persists, retrieves, updates, and deletes data

2. **Item Controller**:  
   - Manages app state and data model  
   - Handles logic for adding, updating, deleting items

3. **UI Controller**:  
   - Manages DOM manipulation  
   - Updates HTML based on app state

4. **App Controller**:  
   - Initializes the app  
   - Sets up event listeners  
   - Acts as the central communication point between all modules

Each module is **encapsulated** using an IIFE, exposing only necessary methods (public API) and keeping internal functions private.

---

## 📁 Project Structure

Tracalorie-JS-Project --> [index.html, js --> [app.js # (Using Plain JS), main.js # (Using Module Structure and IFFE)], .gitignore, README.md]

---

## 💾 LocalStorage Integration

- Every meal item is stored in the browser's `localStorage` under the key `meals`.
- Modifying or clearing data automatically reflects in localStorage.
- No backend or database needed.

---

## ▶️ Getting Started

### Clone and Run

```bash
git clone https://github.com/leonsitheczar/tracalorie_project.git
cd tracalorie_project
