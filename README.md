# 🏀 Dribbble Landing Page Clone

A pixel-perfect, responsive frontend clone of the iconic **[Dribbble](https://dribbble.com)** landing page, built from scratch using pure **HTML5**, modern **CSS3**, and **Vanilla JavaScript**. 

This project was developed as a hands-on learning project to master real-world frontend web development, modern CSS layout architectures (Flexbox & CSS Grid), seamless infinite animations, and interactive DOM manipulation without relying on external UI frameworks.

---

## 🌟 Key Features

- **🎯 Pixel-Perfect Hero Section**:
  - Catchy typography featuring Dribbble's signature serif and sans-serif fonts.
  - Smooth, infinite auto-scrolling hero cards marquee without stutter or loop breaks.
  - Hover effects with designer badge overlays and direct action buttons.

- **📱 Fully Responsive Navigation**:
  - Centered branding logo matching official design specifications.
  - Quick action buttons for **Log in** and **Sign up**.
  - Mobile slide-out navigation drawer with smooth backdrop transitions for small screens.

- **🖼️ Interactive Design Showcase Grid**:
  - Responsive multi-column CSS Grid showcasing trending creative shots.
  - Hover overlays with like, bookmark, and shot details.

- **🔐 Interactive Authentication (Modal & Standalone Pages)**:
  - Interactive popup modal on the homepage with smooth tab switching between **Sign Up** and **Sign In**.
  - Google OAuth button simulation and form submission states.
  - Dedicated standalone auth pages: [`login.html`](login.html) and [`signup.html`](signup.html).

- **♾️ Infinite Category Ticker**:
  - Seamless marquee animation highlighting creative design categories (Animation, Branding, Web Design, etc.).
  - Automatic pause on hover for easy interaction.

- **📐 Clean & Polished Footer**:
  - Proportional spacing, curated links, social icons, and copyright details.

---

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=black&logoColor=black)

- **Semantic HTML5**: Clean, accessible markup structure.
- **Modern CSS3**:
  - CSS Flexbox & CSS Grid layouts
  - Custom Keyframe Animations (`@keyframes`) for seamless infinite scrolling
  - Fluid media queries (`@media`) for cross-device responsiveness
  - Modern typography with Google Fonts (`Source Serif 4`, `Open Sans`, `Inter`)
  - Icons powered by **Remix Icon**
- **Vanilla JavaScript**:
  - Dynamic modal controls (open/close, ESC key dismiss, backdrop click)
  - Mobile hamburger drawer toggle
  - Interactive form validations and state transitions

---

## 📂 Project Structure

```bash
dribbble-landing-page-clone/
├── index.html           # Main landing page with integrated auth modal
├── login.html           # Standalone dedicated Log In page
├── signup.html          # Standalone dedicated Sign Up page
├── style.css            # Complete stylesheet with animations & media queries
├── animation2/          # Footer carousel category thumbnail assets
│   ├── 1.png ... 8.png
├── images/              # Creative shot assets and artwork
│   ├── 1.png ... img29.jpg
│   └── auth-art.png
└── README.md            # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### 1. Clone the repository
```bash
git clone https://github.com/arnavprajapati/dribbble-landing-page-clone.git
```

### 2. Navigate to the project directory
```bash
cd dribbble-landing-page-clone
```

### 3. Open the project
- Simply double-click `index.html` to open it in your default browser, or
- Use the **Live Server** extension in VS Code for live reloading:
  - Right-click `index.html` → **Open with Live Server**.

---

## 💡 What I Learned

Through building this project hands-on, I gained practical experience with:
- Implementing continuous **infinite linear marquee animations** using duplicated tracks and CSS transforms without visual breaks.
- Building **complex responsive navigation systems** with slide-in drawers for mobile viewports.
- Structuring scalable CSS with **CSS Grid** (`repeat(auto-fill, minmax(...))`) and Flexbox.
- Creating reusable modal dialog patterns and smooth modal interactions using vanilla JavaScript.
- Handling cross-device typography and spacing hierarchy.

---

## 👤 Author

**Arnav Prajapati**
- GitHub: [@arnavprajapati](https://github.com/arnavprajapati)

---

## 📄 License

This project is created for educational and practice purposes only. Design inspirations and brand assets belong to [Dribbble](https://dribbble.com).
