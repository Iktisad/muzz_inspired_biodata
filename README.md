# Muzz Inspired Biodata

This project is a personal biodata website inspired by the clean and mobile-friendly aesthetic of **Muzz**, a Muslim matrimonial application. It serves as a single-page profile, combining concise personal information with photos, icons, and interactive carousels. The page is built with **HTML** and styled using **Tailwind CSS**, compiled locally via the Tailwind CLI.

---

## ✨ Features

* **Hero & Quick Facts** – Full-screen background image with name and dynamically calculated age. Pill-shaped badges display details like location, profession, religiosity, and ethnicity.
* **Quotation Banner** – A short, personal quote beneath the hero section.
* **About Me** – Badge list showing attributes such as height, marital status, religious affiliation, and children.
* **Marriage Intentions Timeline** – A progress bar with labeled steps: *Match → Chatting → Meet → Marry*.
* **Lifestyle & Personality** – Pills that highlight traits such as simplicity, balance, helpfulness, and respect.
* **Education & Career Timeline** – Vertical timeline listing degrees and work experience (e.g., BSc, Software Engineer, Master’s degree).
* **Languages & Ethnicity** – Pills identifying cultural background and native languages.
* **Bio Section** – Paragraph summarizing interests and values: passion for technology, love of cooking, travel, and photography.
* **Family Gallery** – Scrollable carousel of family members with photos, names, and occupations, plus navigation dots.
* **Ice Breaker Questions** – Carousel of conversation starter cards.
* **Social Links** – Icon buttons linking to Facebook, Instagram, LinkedIn, and GitHub.
* **Dynamic Age Calculation** – Script computes and displays age based on birthdate.

---

## 🛠️ Technologies Used

* **HTML** – All content is contained within `index.html`.
* **Tailwind CSS** – Styling via utility classes. Built using `@tailwindcss/cli`.

  * `src/input.css` – Tailwind import file.
  * `src/output.css` – Compiled CSS.
* **JavaScript** – Handles carousel navigation updates and age calculation.
* **Assets** –

  * `imgs/` – Photos for background and family gallery.
  * `svg/` – Icons for flags, religion, professions, social media, and timeline steps.

---

## 📂 Repository Structure

```plaintext
├── index.html         # Main HTML page with all sections
├── src/
│   ├── input.css      # Tailwind import file
│   └── output.css     # Compiled Tailwind styles
├── imgs/              # Photographs (background, portraits, family)
├── svg/               # SVG icons (flags, badges, social media, etc.)
├── package.json       # Tailwind build scripts and dependencies
├── package-lock.json  # Auto-generated dependency tree
└── .gitignore
```

---

## 🚀 Installation & Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/Iktisad/muzz_inspired_biodata.git
   cd muzz_inspired_biodata
   ```

2. **Install dependencies**
   (Tailwind CLI is the only dependency)

   ```bash
   npm install
   ```

3. **Build CSS & start watcher**
   This processes `src/input.css` → `src/output.css` and watches for changes:

   ```bash
   npm start
   ```

4. **Open the site**
   Once CSS is built, open `index.html` in your browser.

   > No server required – simply double-click or run via a local web server.

---

## 🎨 Customization

* **Update images** – Replace files in `imgs/` and update `<img>` tags in `index.html`.
* **Change personal details** – Edit text in `index.html` (badges, timelines, bio, etc.).
* **Modify age** – Adjust the `birthDate` variable in the script at the bottom of `index.html`.
* **Edit ice breaker questions** – Update `<p>` tags in the “Ice Breaker Questions” section.
* **Tweak styling** – Edit `src/input.css` and recompile with `npm start`, or add Tailwind classes directly in `index.html`.

---

## 🙏 Credits

* Inspired by the design language of the **Muzz** app.
* Icons are stored locally in the `svg/` directory.
* Licensed under the **ISC License** (see `package.json`).
