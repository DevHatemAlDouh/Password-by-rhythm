<div align="center">

# 🔐 Password by Rhythm

**A browser-based experiment in password and typing-rhythm comparison**

[![Platform](https://img.shields.io/badge/Platform-Web-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](#getting-started)
[![HTML](https://img.shields.io/badge/HTML-5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)

---

</div>

## 📖 Overview

**Password by Rhythm** is a small web prototype that compares the sequence of
input events and timing intervals from two password entries. It runs in the
browser using plain HTML, CSS, and JavaScript, with no package installation or
build step required.

> **Warning:** This is an experiment, not a secure authentication system. Do
> not enter real or reused passwords.

---

## ✨ Features

- **⌨️ Input Event Recording:** Records the input value and timestamp as the
  user types in each field.
- **⏱️ Rhythm Comparison:** Compares corresponding input-event intervals with
  a 200 ms tolerance.
- **🔄 Reset:** Clears the recorded data and re-enables the password field.
- **🧪 Lightweight Prototype:** Uses browser-native HTML, CSS, and JavaScript
  without external runtime dependencies.

---

## 🛠️ Tech Stack

| Layer        | Technology         |
| :----------- | :----------------- |
| **Markup**   | HTML               |
| **Styles**   | CSS                |
| **Behavior** | Vanilla JavaScript |
| **Runtime**  | Modern web browser |

---

## 📂 Project Architecture

```
Password_by_Rhythm/
├── index.html     # Page structure and input controls
├── Css.css        # Page styling
└── keylogger.js   # Input event recording and comparison
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser.

### Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/DevHatemAlDouh/Password_by_Rhythm.git
   cd Password_by_Rhythm
   ```

2. **Open the project:**
   Open `index.html` directly in your browser. Alternatively, serve the
   directory with any local static web server and open the local address.

3. **Try the prototype:**
   Type a test password in the first field and select **Submit**. Enter it
   again in the second field; comparison runs when that field changes, such
   as when it loses focus. Open the browser developer console to see the
   comparison result. Select **Reset** to start over.

---

## 🧭 Current Behavior and Limitations

- The **Set Rhythm** button currently has no implemented behavior.
- Results are logged to the browser developer console rather than displayed
  on the page.
- The comparison records `input` events, not individual physical keystrokes.
  Editing, pasting, and browser behavior can affect the event sequence.
- Password values are held in JavaScript memory while the page is open.
  There is no server-side authentication, secure password storage, or
  replay protection. A matching rhythm does not verify a user's identity.

<!-- {use profolio} -->
