# Yash Vardhan - Modern Personal Portfolio

A sleek, high-performance personal portfolio website built with **React**, **Vite**, and **Tailwind CSS** for **Yash Vardhan** (B.Tech Student at JECRC University, Jaipur | AI & Technology Enthusiast).

---

## 🚀 Features

- **Modern & Premium UI**: Dark/Light mode toggle, glowing gradient text, glassmorphism cards, and subtle hover animations.
- **Comprehensive Sections**:
  1. **Home / Hero**: Animated status badge, title, intro, "View Projects", "Contact Me", and quick-copy email button.
  2. **About Me**: Student-friendly professional story, core pillars, and highlights grid.
  3. **Education**: JECRC University, 1st Year B.Tech, coursework and learning areas.
  4. **Skills**: Interactive skill cards with proficiency meters for HTML, CSS, JavaScript, Python, AI, Generative AI, Web Development, and Digital Productivity.
  5. **Projects**: Detailed project cards with technology pills, direct GitHub links, and an interactive inspection modal.
  6. **Achievements**: Filterable categories (Certifications, Hackathons, Courses, Awards).
  7. **Contact**: One-click email copy, social cards (LinkedIn, GitHub), and interactive message form with instant feedback.
- **Easy Content Customization**: Centralized `src/data/portfolioData.js` allows updating all info, projects, skills, and links in one place.
- **Mobile Responsive**: Fully responsive navbar with a slide-out hamburger menu drawer for phones and tablets.
- **Vercel Ready**: Ready to deploy directly to Vercel with zero configuration.

---

## 🛠️ Tech Stack

- **Framework**: React 18
- **Bundler**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React

---

## 📦 Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### 3. Build for Production
```bash
npm run build
```

---

## ✏️ How to Customize Your Info

Open `src/data/portfolioData.js`:
- **Personal Info**: Change your LinkedIn, GitHub, email, or bio.
- **Skills**: Add or remove skills and change proficiency percentages.
- **Projects**: Add new projects with title, tech stack, and GitHub/demo links.
- **Achievements**: Add your hackathon prizes, certifications, and course completions.

---

## 🌐 Deploying to Vercel

1. Push this repository to your GitHub account:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository. Vercel will automatically detect Vite and configure the build command (`npm run build`) and output directory (`dist`).
4. Click **Deploy**!
