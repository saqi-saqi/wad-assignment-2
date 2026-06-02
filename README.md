# WAD Assignment 2

## Assignment Overview
This repository contains **WAD Assignment 2** for Web Application Development.  
The assignment implements a multi-page departmental website (Computer Science Department, QAU) using static web technologies.

## Assignment Description
The goal of this assignment is to design and organize a structured academic website with multiple linked pages for key sections such as academics, admissions, faculty, research, and contact information.

## Learning Objectives
- Build semantic and well-structured HTML pages.
- Apply responsive UI styling using CSS utility classes.
- Organize a multi-page website with consistent navigation.
- Manage static assets (images and page links) in a clean repository structure.

## Requirements and Specifications
- Create and connect multiple HTML pages.
- Provide clear navigation between all major sections.
- Use consistent layout patterns (header, nav, content, footer).
- Include relevant content for academic/departmental website sections.
- Keep media assets in a dedicated folder.

## Technologies Used
- **HTML5** (page structure/content)
- **CSS** (styling through utility classes)
- **JavaScript** (Tailwind CSS CDN script usage)
- **Tailwind CSS (CDN)** for fast styling

## Project Structure
```text
wad-assignment-2/
├── index.html
├── academics.html
├── admissions.html
├── alumni.html
├── bs.html
├── ms.html
├── Phd.html
├── faculty.html
├── research.html
├── funded-projects.html
├── contact.html
├── sir_naqi.html
└── images/
    └── (department and content images)
```

## How to Run / View
Since this is a static web assignment, no build step is required.

### Option 1: Open directly
1. Open `/tmp/workspace/saqi-saqi/wad-assignment-2/index.html` in a web browser.
2. Navigate through pages using the top menu.

### Option 2: Run a local static server (recommended)
From the repository root:
```bash
cd /tmp/workspace/saqi-saqi/wad-assignment-2
python -m http.server 8000
```
Then open: `http://localhost:8000/index.html`

## Features and Functionality
- Multi-page academic website layout
- Cross-page navigation menu
- Program-focused pages (BS / MS / PhD)
- Faculty and research information sections
- Admissions and contact pages
- Responsive visual layout via Tailwind CSS classes

## Testing Procedures
This repository does not include an automated test suite.  
Use manual verification:

1. Open `index.html` and each linked page.
2. Confirm that primary navigation works across pages.
3. Confirm that images load from the `images/` folder.
4. Check page responsiveness by resizing browser width.
5. Validate HTML pages with an HTML validator if required by your course.

## Submission Requirements
- Submit all HTML files and the `images/` directory.
- Preserve relative paths and folder structure.
- Ensure the project opens from `index.html`.
- Include this README as assignment documentation.

## Evaluation Criteria
Typical WAD evaluation for this assignment may include:
- Correctness and completeness of required pages
- Navigation/linking between pages
- UI consistency and responsiveness
- Code structure/readability
- Content organization and presentation

## Resources and References
- [MDN Web Docs (HTML)](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs (CSS)](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Guide (MDN)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## Author Information
- **Repository Owner:** [saqi-saqi](https://github.com/saqi-saqi)
- **Course Context:** Web Application Development (WAD)

## Additional Notes
- This is an academic assignment repository and is intended primarily for learning and submission purposes.
- Some links may point to resources/pages not included in this repository snapshot, depending on assignment scope.
