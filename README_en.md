# Genshin Kakimoto Homepage

This repository contains the source code for Genshin Kakimoto's personal homepage. The site introduces his profile, research interests, current work, certifications, and hobbies in both Japanese and English.

Live site:

- Japanese: https://kakimoto0225.github.io/homepage/
- English: https://kakimoto0225.github.io/homepage/index_en.html

Japanese README: [README.md](./README.md)

## About This Repository

This is a static website published with GitHub Pages. It is intentionally simple: the site is built with plain HTML and CSS, with no JavaScript framework, build step, or package installation required.

If you are visiting for the first time, the live site is the best place to start. The repository shows how the pages, styling, deployment workflow, and images are organized.

## Site Contents

- Profile: affiliation, seminar, and GitHub account
- Research: econometrics, causal inference, empirical industrial organization, and machine learning
- Work: papers, projects, and related links
- Credentials: TOEIC, Data Scientist Certification, EIKEN, and Statistics Certification
- Hobbies: movies, baseball, and orienteering

## Repository Structure

```text
homepage/
|-- index.html              # Japanese page
|-- index_en.html           # English page
|-- style.css               # Shared stylesheet
|-- README.md               # Japanese repository overview
|-- README_en.md            # English repository overview
|-- images/
|   |-- face.jpg
|   |-- profile_large.jpg
|   |-- profile_small.jpg
|   |-- hobby_movie.jpg
|   |-- hobby_baseball.jpg
|   `-- hobby_orienteering.jpeg
`-- .github/
    `-- workflows/
        `-- pages.yml       # GitHub Pages deployment workflow
```

## Local Preview

The site can be opened directly in a browser, but using a small local server is closer to the GitHub Pages environment.

```bash
git clone https://github.com/kakimoto0225/homepage.git
cd homepage
python -m http.server 4173
```

Then open:

- http://127.0.0.1:4173/index.html
- http://127.0.0.1:4173/index_en.html

## Technical Notes

- Static HTML5 pages
- Responsive layout with CSS Grid and Flexbox
- Google Fonts for Japanese and English typography
- GitHub Actions workflow for GitHub Pages deployment

## Maintainer

- GitHub: [kakimoto0225](https://github.com/kakimoto0225)

## License

Copyright (c) 2026 Genshin Kakimoto. All rights reserved.
