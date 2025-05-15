# Amur Leopard Conservation Website

**A responsive, multi-page informational site dedicated to raising awareness and support for the critically endangered Amur leopard.**

---

## 🚀 Table of Contents

1. [About](#about)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Technologies](#technologies)
5. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Running Locally](#running-locally)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

---

## 📖 About

This static website provides visitors with:

- Interactive **biology**, **threats**, and **conservation** pages
- A **spotlight gallery** showcasing photos
- A “**Get Involved**” section with volunteer and sponsorship forms
- A **contact** page with a fully styled form
- Newsletter subscription

Designed for clarity, accessibility, and mobile responsiveness.

---

## ✨ Features

- **Responsive navigation** with sticky header and mobile hamburger menu
- **Hero section** with parallax-style background
- **Card-grid layouts** for highlights, threats, and conservation efforts
- **Full-bleed sections** for immersive imagery
- **Accessible forms** for volunteering, sponsoring, and contacting
- **Consistent styling** via CSS variables and utility classes

---

## 🗂 Project Structure

```
.
├── css/
│   └── style.css                   # Main stylesheet (variables, layouts, components)
├── images/                         # All .jpg and .png assets
│   ├── amur.jpg
│   ├── leaves.jpg
│   └── …  
├── pages/                          # Sub-pages
│   ├── biology.html  
│   ├── conservation.html  
│   ├── contact.html  
│   ├── get-involved.html  
│   ├── threats.html  
│   └── …  
├── index.html                      # Home page
└── README.md                       # ← You are here
```

---

## 🛠 Technologies

- **HTML5** & **Semantic Markup**
- **CSS3** (Flexbox, Grid, Variables, Media Queries)
- No frameworks—vanilla, dependency-free

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/MariaTze/amur-leopard-site.git
   cd amur-leopard-site
   ```

2. **Serve locally**  
   You can use any static-file server. For example, via **Python**:
   ```bash
   # Python 3.x
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.

### Running Locally

- **Live-reload** (optional): use tools like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for instant feedback when editing.

---

## 🎯 Usage

- **Navigate** via the top menu to explore pages.
- **Click** on cards (e.g. in “Threats” or “Conservation”) to open modal details.
- **Submit** forms on “Get Involved” or “Contact”—they currently log to console or can be wired to your backend.

---

## 🤝 Contributing

Contributions welcome! Please:

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/my-change`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/my-change`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📫 Contact

Project maintainer – *Maria Tzemanaki*  
Email: tzemanakimaria97@hotmail.com  
GitHub: [@MariaTze](https://github.com/MariaTze)

---

> “Every small step counts. Thank you for helping protect the Amur leopard.” 🐆  
