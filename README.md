# GramTech AI — Digital ZP School 2.0

GramTech AI is a student-built prototype exploring how accessible digital tools can support rural government schools through learning resources, career exploration and student innovation showcases.

> **Prototype status:** The learning assistant uses built-in sample responses. It does not connect to a live AI model, store student data, or provide formal career counselling.

## Why it matters
Rural students may have uneven access to digital learning resources, technology exposure and career awareness. GramTech AI explores a low-cost, responsive approach that can be tested with educators and improved using community feedback.

The project builds on experience creating a digital presence for ZP School Sarola, Maharashtra. That Google Sites project is separate from this code prototype.

## Current features
- Responsive landing page for desktop and mobile.
- Learning assistant demo with prepared sample explanations and practice questions.
- Dream → Learn → Build career exploration for five example pathways.
- Student innovation showcase with illustrative sample projects.
- No login, tracking, external API or personal-data collection.
- Dependency-free HTML, CSS and JavaScript.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Try the learning topics and career roadmap selector.

No package manager, build step or environment variables are required.

## Publish with GitHub Pages
1. Open repository **Settings** → **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. Wait for publication and use the URL shown on the Pages settings screen.

## Project structure
```text
gramtech-ai/
├── index.html
├── styles.css
├── script.js
├── README.md
├── LICENSE
├── docs/ARCHITECTURE.md
├── docs/TEST-CASES.md
├── sample-data/sample-projects.json
└── tests/manual-test-checklist.md
```

## Roadmap (proposed, not implemented)
- Review content with teachers and local-language educators.
- Add Marathi/Hindi content after validation.
- Explore a secure, privacy-conscious AI integration.
- Investigate offline lesson caching and synchronisation.
- Pilot with school approval and measure usage and learning feedback.

## Responsible use
This is an educational prototype, not an official government service. Do not enter children's personal or sensitive information. Any future school deployment should involve school approval, privacy safeguards, content review and accessibility testing.

## UN SDG alignment
- **SDG 4 — Quality Education**
- **SDG 9 — Industry, Innovation and Infrastructure**
- **SDG 10 — Reduced Inequalities**

See `LICENSE` for the MIT License.
