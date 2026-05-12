# Mayur Akewar GitHub Pages Website

This folder contains a complete static portfolio website for GitHub Pages.

## What is included

The website includes content from the CV, Google Scholar screenshot, LinkedIn URL provided by Mayur, and the current NERSC Berkeley Lab internship update.

- Research focused homepage for AI, systems, HPC, quantum AI, and AI for Science
- Current NERSC, Lawrence Berkeley National Laboratory internship highlighted in the hero, research, projects, and experience sections
- Expanded research section with AI for Systems, Agentic AI for HPC, Quantum AI and QML, and Systems for AI
- Moving animated lines and dots in the background using CSS only
- Updated LinkedIn link: `https://www.linkedin.com/in/mayur-akewar-88523421`
- Google Scholar profile link retained, but the large Scholar snapshot section was removed
- Updated publication list with SMARTTalk, KORAL, WSBD, CatRAG, and Variational Quantum Algorithms Are Lipschitz Smooth
- CV PDF included in `assets/Mayur_Akewar_CV.pdf`

## How to publish

1. Create a GitHub repository named exactly:

```text
yourusername.github.io
```

2. Upload all files from this folder to that repository.

3. Replace this placeholder in `index.html`:

```text
https://github.com/yourusername
```

4. Go to GitHub repository settings:

```text
Settings > Pages
```

5. Under source, choose the main branch and root folder.

6. Your website will be available at:

```text
https://yourusername.github.io
```

## Files

```text
index.html        Main website
styles.css        Visual design, animated background, and responsive layout
script.js         Menu, filtering, and animation
404.html          GitHub Pages fallback page
.nojekyll         Disables Jekyll processing
assets/           CV and visual assets
```

## Updating publications

Each publication is an HTML card inside the `publication-list` section in `index.html`. To add a new paper, copy one existing `publication-card` block and update the venue, status, title, authors, tags, and link.
