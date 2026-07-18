# Genshin Kakimoto Homepage

This repository contains the source code for the personal homepage of Genshin Kakimoto, an undergraduate student at the Faculty of Economics, Kyoto University.
The site showcases my research interests (Econometrics, Causal Inference, Empirical Industrial Organization, Machine Learning), ongoing projects, credentials, and hobbies in both English and Japanese.

**🌍 Live Site**
- English: [https://kakimoto0225.github.io/en/](https://kakimoto0225.github.io/en/)
- Japanese (日本語版): [https://kakimoto0225.github.io/](https://kakimoto0225.github.io/)

Japanese repository overview is available here: [README.md](./README.md)

---

## 🚀 About This Repository

This repository manages the source code for my static personal homepage hosted on GitHub Pages.
The frontend is built with plain HTML and CSS, intentionally avoiding heavy build tools (like Webpack or Vite) and external frameworks (like React or Vue) to maintain a simple, lightweight, and easy-to-maintain architecture.

For first-time visitors, checking out the [live site](https://kakimoto0225.github.io/en/) is the easiest way to grasp the overall content. Here in GitHub, you can see how the markup, styles, images, and CI/CD deployment configurations via GitHub Actions are implemented and managed.

## ✨ Features

- **Vanilla HTML/CSS**: Lightweight design with no external dependencies.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices utilizing CSS Grid and Flexbox.
- **Bilingual Support (i18n)**: Separate pages for English (`index_en.html`) and Japanese (`index.html`) with a simple language toggle navigation.
- **CI/CD Auto Deployment**: Automated deployment to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.

## 📖 Contents

The website is structured into the following main sections:

1. **Profile**
   - Academic affiliation (Faculty of Economics, Kyoto University), Seminar (Yanagi Seminar), and GitHub profile.
2. **Research**
   - Academic interests focusing on Econometrics, Causal Inference, Empirical Industrial Organization, and Machine Learning.
3. **Work**
   - Ongoing projects (e.g., Fine-tuning LLMs on Japanese financial datasets), future papers, and related links.
4. **Credentials**
   - Certifications and skills including TOEIC, Data Scientist Certification, EIKEN, and Statistics Certification.
5. **Hobbies**
   - Extracurricular activities such as watching movies, baseball, and orienteering.

## 📂 Directory Structure

```text
homepage/
├── .github/
│   └── workflows/
│       └── pages.yml           # CI/CD workflow for automated GitHub Pages deployment
├── images/                     # Image assets used across the site
│   ├── face.jpg                # Avatar image
│   ├── profile_large.jpg       # Hero background image
│   ├── profile_small.jpg       # Profile image for mobile view
│   ├── hobby_movie.jpg         # Hobby thumbnail (Movies)
│   ├── hobby_baseball.jpg      # Hobby thumbnail (Baseball)
│   └── hobby_orienteering.jpeg # Hobby thumbnail (Orienteering)
├── index.html                  # Japanese entry point page
├── index_en.html               # English entry point page
├── style.css                   # Shared stylesheet used across all pages (Vanilla CSS)
├── README.md                   # Repository overview in Japanese
└── README_en.md                # This file (Repository overview in English)
```

## 🛠️ Local Setup

Since this project relies purely on vanilla HTML and CSS, there are no special package installations required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/kakimoto0225/homepage.git
   cd homepage
   ```

2. **Preview in Browser**
   - You can simply drag and drop `index_en.html` or `index.html` into your preferred web browser (e.g., Chrome, Firefox, Safari).
   - If you are using VS Code, it is recommended to install the **Live Server** extension (by Ritwick Dey) and click the "Go Live" button at the bottom right corner to start a local development server with hot-reloading enabled.

## 📝 Future Plans (TODO)

- [ ] Add new academic papers and research notes (with PDF links)
- [ ] Enhance OGP (Open Graph Protocol) for better thumbnail previews on social media sharing
- [ ] Implement Dark Mode
- [ ] Improve website accessibility (a11y)

## 👤 Maintainer / Author

- **Genshin Kakimoto**
- GitHub: [@kakimoto0225](https://github.com/kakimoto0225)

## 📄 License

Copyright (c) 2026 Genshin Kakimoto. All rights reserved.

Reproduction, modification, or distribution of the code and visual assets (images) within this repository is prohibited without prior consent.
