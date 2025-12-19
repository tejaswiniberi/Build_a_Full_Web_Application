# Build_a_Full_Web_Application
A modern, dark-themed developer portfolio built with Vanilla JavaScript and CSS Grid. Features dynamic project rendering, glassmorphism UI effects, and a fully responsive mobile-first layout.

# ⚡ DevCore | Modern Developer Portfolio

## 📖 Project Overview
**DevCore** is a sleek, high-performance portfolio template designed for developers. Built with a "mobile-first" approach, it features a modern **Dark UI** aesthetic with Emerald Green accents.

Unlike static HTML templates, this project utilizes **Vanilla JavaScript** to dynamically render project data, making it easy to add or remove portfolio items by simply modifying a JSON-like array.

---

## 🎨 Key Features

### 💎 Modern UI/UX
* **Glassmorphism Navigation:** Sticky header with a backdrop-blur effect.
* **Dark Mode Design:** A sophisticated color palette using CSS Variables (`--dark-bg`, `--primary`) for easy theming.
* **Interactive Hover Effects:** Project cards transition from grayscale to full color on hover.

### ⚙️ Technical Implementation
* **Dynamic Content Rendering:** Project cards are injected into the DOM using JavaScript ES6 `map()` and template literals, keeping the HTML clean.
* **CSS Grid & Flexbox:** Fully responsive layout that adapts to mobile, tablet, and desktop screens.
* **Smooth Scrolling:** Native CSS smooth scrolling for navigation links.

---

## 🛠️ Tech Stack
* **Structure:** HTML5 (Semantic)
* **Styling:** CSS3 (Variables, Grid, Flexbox, Media Queries)
* **Logic:** Vanilla JavaScript (ES6+)
* **Fonts:** Inter (via Google Fonts)

---

## 🚀 How to Use / Customize
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/yourusername/devcore-portfolio.git](https://github.com/yourusername/devcore-portfolio.git)
    ```
2.  **Open:** Simply open `index.html` in your browser.
3.  **Add Your Projects:**
    Open the `<script>` tag at the bottom of `index.html` and modify the `projectData` array:
    ```javascript
    const projectData = [
        {
            title: "Your Project Name",
            desc: "Short description...",
            img: "image-url.jpg"
        },
        // Add more objects here
    ];
    ```

Created with by Tejaswini. Beri
