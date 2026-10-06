# Personal-Blog
# 🚀 Bhavasudhan S — Portfolio Building Journey

A modern, high-performance, single-page web portfolio documenting 12 Portfolio Building activities, competitive programming achievements, technical skills, and professional profiles for **Bhavasudhan S**, B.Tech CSE student at REVA University.

---

## ✨ Features & Highlights

- **🎨 Modern Glassmorphism Aesthetic**:
  - Curated color system with custom dark and light themes.
  - Ambient background gradient animation blobs.
  - Spotlight mouse-tracking card glow effects (`--mouse-x`, `--mouse-y`).
  - Google Fonts (*Outfit* & *Plus Jakarta Sans* typography).

- **🖱️ Interactive Custom Cursor Physics**:
  - Custom pointer dot (`#cursor-dot`) + LERP smooth follower ring (`#cursor-ring`).
  - Magnetic scale-up & glow on interactive elements (`<a>`, `<button>`, `.act-card`, `.skill-pill`, `.profile-card`).
  - Click shockwave ripple animation.

- **📜 Scroll Animations & Telemetry**:
  - Top scroll reading progress bar (`#scroll-progress`).
  - Scroll-triggered reveal animations via `IntersectionObserver` (`fade-up`, `zoom`).
  - Dynamic frosted glass navbar blur on scroll down.
  - Tick-up number counter animation for stats (12 Activities, 5 HackerRank Accepted, 6 Profiles).

- **🏷️ Activity Grid with Filtering**:
  - Interactive category filter buttons (`All`, `Coding`, `Profiles`, `Growth`) with badge counts.
  - 12 activity cards rendered with tag badges, activity numbers, and direct action links.

- **🌓 Dark & Light Theme Switcher**:
  - Toggle between sleek dark mode and crisp light mode with `localStorage` preference persistence.

---

## 📁 Project Structure

```text
website/
├── index.html       # Complete website UI (HTML5, Inline Glassmorphism CSS3, ES6 JavaScript)
└── README.md        # Documentation and customization guide
```

---

## ⚡ Quick Start

### Option 1: Open Directly in Browser
Simply double-click [`index.html`](file:///C:/Users/bhava/.gemini/antigravity-ide/scratch/website/index.html) or open it in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Run via Local Server (Recommended)
Launch a local development server using Python:

```bash
# Using Python
py -m http.server 3000 --directory C:\Users\bhava\.gemini\antigravity-ide\scratch\website
```
Then visit **`http://localhost:3000`** in your browser.

---

## 🔗 How to Customize the 12 Activity Links

Each of the 12 activity cards has a customizable URL placeholder in `index.html`.

1. Open `index.html` in your editor.
2. Locate the `acts` array in the `<script>` section (around line 1155):

```javascript
// Format: [id, title, description, category, linkUrl]
const acts = [
  [1, "C/C++ Dev Environment in VS Code", "Description...", "Coding", "https://your-github-repo-or-link-1"],
  [2, "VS Code Power Extensions Tour", "Description...", "Coding", "https://your-github-repo-or-link-2"],
  [3, "Collaborative Dev with GitLens & Live Share", "Description...", "Coding", "https://your-github-repo-or-link-3"],
  // ... edit URLs for activities 4 through 12
];
```

3. Replace `"https://example.com/activity-X"` with your actual GitHub repository links, LeetCode submissions, LinkedIn posts, or blog links.
4. Save the file and refresh your browser.

---

## 🛠️ Built With

- **HTML5**: Semantic tags (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3**: Vanilla CSS Custom Properties, Flexbox, Grid, Glassmorphism backdrop-filters, CSS keyframe animations.
- **JavaScript (ES6+)**: `IntersectionObserver`, LERP mouse physics, DOM event delegation, dynamic filtering.
- **Google Fonts**: [Outfit](https://fonts.google.com/specimen/Outfit) & [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans).

---

## 👤 Author

**Bhavasudhan S**  
- **Degree**: B.Tech Computer Science & Engineering, REVA University  
- **GitHub**: [github.com/bhavasudhan007](https://github.com/bhavasudhan007)  
- **LeetCode**: [leetcode.com/u/Bhavasudhan](https://leetcode.com/u/Bhavasudhan/)  
- **HackerRank**: [hackerrank.com/profile/bhavasudhan1300](https://www.hackerrank.com/profile/bhavasudhan1300)  
- **LinkedIn**: [linkedin.com/in/bhavasudhan-s-04a741384](https://www.linkedin.com/in/bhavasudhan-s-04a741384)  
- **Instagram**: [instagram.com/___bhavasudhan_](https://www.instagram.com/___bhavasudhan_/)  

---

*Portfolio Building Presentation & Showcase — 2026*
