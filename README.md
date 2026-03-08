# 🖥️💡 Computer Engineering Department — GPP Website 🎓🚀

A multi-page static website for the **Computer Engineering Department** at **Government Polytechnic Porbandar (GPP)** 🏫, built with HTML, Bootstrap 5, and Font Awesome. ⚡✨

---

## 📋 Table of Contents

- [🔍 Overview](#overview)
- [📄 Pages](#pages)
- [✨ Features](#features)
- [🛠️ Tech Stack](#tech-stack)
- [📁 Project Structure](#project-structure)
- [🚀 Getting Started](#getting-started)
- [🌙 Dark Mode](#dark-mode)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

---

## 🔍 Overview

This website serves as the official departmental portal for the Computer Engineering program at GPP 🏛️. The diploma program was established in **2001** 📅 with an initial intake of 30 students and has grown to accommodate **90 students** per year 📈. The site provides prospective and current students 👩‍🎓👨‍🎓, faculty 👩‍🏫, and the public with information about the department's programs, facilities, faculty, and more.

---

## 📄 Pages

| 📂 File | 📝 Description |
|------|-------------|
| `bhome.html` | 🏠 Landing page with department highlights |
| `babout_us.html` | ℹ️ Department history, mission, vision & stats |
| `badmission.html` | 🎟️ Admissions information and process |
| `bfaculty.html` | 👨‍🏫 Faculty profiles and contact details |
| `blab.html` | 🔬 Computer science lab facilities |
| `bclassroom.html` | 🏫 Classroom infrastructure overview |
| `bgallery.html` | 🖼️ Photo gallery of campus and events |
| `bcontact.html` | 📬 Contact form and department location |

---

## ✨ Features

- ✅ Fully responsive layout (mobile 📱, tablet 📟, desktop 🖥️)
- 🌙 Dark mode toggle (persists across pages via `localStorage`) ☀️
- 🧭 Sticky navigation bar with active page highlighting
- 📊 Stats section (students 👩‍🎓, faculty 👨‍🏫, years of excellence 🏆)
- 🕐 Department history timeline 📅
- 📬 Contact form with location info 📍
- 🖼️ Photo gallery 📸
- 🔗 Social media links in footer 🌐

---

## 🛠️ Tech Stack

- 🌐 **HTML5**
- 🎨 **Bootstrap 5.3** — layout, responsive grid, navbar
- 💎 **Font Awesome 6.4** — icons
- ⚙️ **Vanilla JavaScript** — dark mode toggle (`dark-mode.js`)

> 🎉 No build tools or package managers required — pure static files!

---

## 📁 Project Structure

```
/ 📦
├── bhome.html          🏠
├── babout_us.html      ℹ️
├── badmission.html     🎟️
├── bfaculty.html       👨‍🏫
├── blab.html           🔬
├── bclassroom.html     🏫
├── bgallery.html       🖼️
├── bcontact.html       📬
├── dark-mode.js        🌙
├── css/                🎨
│   └── bootstrap.min.css
└── img/                🖼️
    └── main logo.jpeg
```

---

## 🚀 Getting Started

No installation needed 🎉. Just clone the repo and open any HTML file in your browser 🌐.

```bash
git clone https://github.com/your-username/gpp-ce-department.git
cd gpp-ce-department
```

Then open `bhome.html` in your browser 🖥️ — or use a local server for best results:

```bash
# 🐍 Using Python
python -m http.server 8000
```

Then visit `http://localhost:8000/bhome.html` 🌍.

> ⚠️ **Note:** Make sure `css/bootstrap.min.css` and `img/main logo.jpeg` are present locally, or replace them with CDN links 🔗.

---

## 🌙 Dark Mode

Dark mode is powered by `dark-mode.js` ✨, which:

- 💉 Injects dark-mode CSS styles dynamically
- 🌙 Adds a 🌙/☀️ toggle button to the navbar automatically
- 💾 Saves the user's preference in `localStorage` so it persists across pages

To enable dark mode on any page, simply include the script before `</body>` 📝:

```html
<script src="dark-mode.js"></script>
```

---

## 🤝 Contributing

Contributions are welcome! 🙌 To contribute:

1. 🍴 Fork the repository
2. 🌿 Create a new branch (`git checkout -b feature/your-feature`)
3. ✏️ Make your changes
4. 📤 Commit and push (`git push origin feature/your-feature`)
5. 🔁 Open a Pull Request

---

## 📜 License

This project is intended for educational 🎓 and institutional 🏛️ use by **Government Polytechnic Porbandar**. All rights reserved © 2023 Computer Engineering Department GPP. 💙
"# gpp-porbander" 
