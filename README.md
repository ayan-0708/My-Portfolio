# Ayan Shaikh — Personal Portfolio Website

A clean, modern, and responsive personal portfolio website for **Ayan Shaikh**, a first-year undergraduate pursuing a B.Tech in Electronics and Telecommunication Engineering (ETC) at **DKTE Society’s Textile and Engineering Institute**, Ichalkaranji, Maharashtra, India.

---

## 🌟 Highlights & Features

- **Engineering & Student-Developer Aesthetic**: Crisp dark theme with cyan and teal circuit accents, plus an instant light mode toggle (saved in `localStorage`).
- **100% Dependency-Free**: Pure HTML5, modern CSS3, and vanilla JavaScript for lightning-fast loading, zero external package vulnerabilities, and full offline previewability.
- **Fully Responsive**: Optimized for smartphones, tablets, laptops, and wide desktop displays.
- **Real-World Student Showcases**:
  - **DKTE Bus Tracker**: Student transit tracking system prototype built with HTML5, CSS3, JavaScript, Leaflet maps, and Firebase Realtime Database. (Live: [bustracker-bbd8f.web.app](https://bustracker-bbd8f.web.app))
  - **EcoDiwali App**: Eco-friendly digital fireworks, greetings, and rangoli app exploring a cleaner celebration without smoke or noise pollution. (Live: [ayan-0708.github.io/ecodiwali-app](https://ayan-0708.github.io/ecodiwali-app/))
  - **StudyPilot (App Concept)**: Conceptual academic workflow and syllabus revision planner tailored for engineering students.
- **AICTE DKTE IDEA Lab "Waste to Best" Feature & Press Gallery**:
  - Highlights collaborative participation in the college initiative alongside peers from ETC, Mechanical, and AI-DS departments.
  - Interactive Lightbox modal viewer to inspect press coverage from Marathi dailies (*Sakal* and *Mahasatta*) and official institute posters.
- **Transparent Skill Ratings**: Clear distinction between practicing skills (HTML, CSS, JS, Git, VS Code), foundational academic coursework (C, C++), and active learning areas (Python, Firebase basics, Cybersecurity).
- **Direct Contact & Copy-to-Clipboard**: Direct email (`meetayan.shaikh@gmail.com`) with a 1-click clipboard button and toast notification, plus direct LinkedIn and GitHub profiles.

---

## 📁 Project Structure

```text
My portfolio/
├── index.html                   # Main semantic HTML5 document
├── css/
│   └── style.css                # Custom CSS styling (dark/light themes, responsive layout)
├── js/
│   └── main.js                  # Lightbox viewer, theme toggle, copy email, mobile menu
├── images/
│   ├── avatar.svg               # Engineering avatar badge
│   ├── favicon.svg              # Custom browser tab icon
│   ├── dkte-bus-tracker.jpg     # Bus Tracker poster & interface mockups
│   ├── idealab-waste-to-best.jpg# AICTE DKTE IDEA Lab showcase poster
│   ├── press-sakal.jpg          # Sakal newspaper clipping
│   ├── press-mahasatta.jpg      # Mahasatta newspaper clipping
│   └── press-digital-diwali.jpg # Regional news clipping of digital app
└── README.md                    # Project documentation & deployment guide
```

---

## 🚀 How to Preview the Site Locally

You can preview the portfolio locally using any of the following simple methods:

### Method 1: Direct Browser Open (Easiest)
1. Open File Explorer on your computer.
2. Navigate to `c:\Users\AYAN\Desktop\My portfolio`.
3. Double-click `index.html`. It will instantly open in your default web browser (Chrome, Edge, Firefox, Brave).

### Method 2: VS Code "Live Server" Extension (Recommended for editing)
1. Open the `My portfolio` folder in **Visual Studio Code**.
2. If you have the **Live Server** extension installed, right-click `index.html` and select **"Open with Live Server"**.
3. Any changes you make to the code will automatically refresh in the browser.

### Method 3: Using Node.js or Python from Terminal
Open your terminal in this directory and run:

```bash
# Using Node.js:
npx serve .
# or
npx http-server .
```

Then visit `http://localhost:3000` (or the port shown in your terminal).

---

## 🌐 How to Publish with GitHub Pages (Free Hosting)

GitHub Pages gives you free, permanent hosting for static websites with HTTPS.

### Step 1: Create a GitHub Repository
1. Log in to your GitHub account at [github.com](https://github.com).
2. Click the **+** (plus icon) in the top right and select **New repository**.
3. Name your repository:
   - For a user portfolio site: name it `ayan-0708.github.io` (Recommended - will automatically be accessible at `https://ayan-0708.github.io`).
   - Or name it `portfolio` (will be accessible at `https://ayan-0708.github.io/portfolio`).
4. Set the repository to **Public**.
5. Leave "Add a README file" unchecked (we already have one).
6. Click **Create repository**.

### Step 2: Push Your Code Using Git
Open PowerShell or your command prompt in this folder (`c:\Users\AYAN\Desktop\My portfolio`):

```bash
# 1. Initialize git
git init

# 2. Add all project files
git add .

# 3. Create initial commit
git commit -m "Initial release of Ayan Shaikh personal portfolio"

# 4. Set branch to main
git branch -M main

# 5. Link to your GitHub repo (replace with your repo URL)
git remote add origin https://github.com/ayan-0708/portfolio.git

# 6. Push files to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click on **Settings** (tab on the top right).
3. On the left sidebar, click **Pages**.
4. Under **Build and deployment > Source**, select **Deploy from a branch**.
5. Under **Branch**, select `main` and folder `/(root)`.
6. Click **Save**.
7. In 1–2 minutes, your website will be live at:
   - `https://ayan-0708.github.io/portfolio/` (or `https://ayan-0708.github.io/`)!

---

## ✏️ How to Update and Customize

- **Updating Personal Info or Bio**: Open `index.html` and edit the text inside `<section id="about">` or `<section id="home">`.
- **Adding a Photo**: Place your photo (e.g. `ayan.jpg`) into the `images/` folder and change `<img src="images/avatar.svg" ...>` to `<img src="images/ayan.jpg" ...>` in `index.html`.
- **Adding New Projects**: Duplicate one of the `<article class="project-card">` blocks inside `<div class="projects-grid">` in `index.html`.
- **Styling Changes**: Open `css/style.css` — theme colors are neatly centralized at the very top under `:root`.

---

© 2026 Ayan Shaikh. Crafted with semantic HTML, CSS, and JavaScript.
