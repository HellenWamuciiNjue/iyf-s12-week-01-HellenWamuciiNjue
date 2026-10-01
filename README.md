# Week 1: Web Foundations - Personal Engineering Portfolio

## Author
- **Name:** Hellen Wamucii Njue
- **GitHub:** [@HellenWamuciiNjue](https://github.com)
- **Date:** October 2, 2026

## Project Description
This repository serves as my core web engineering sandbox for Week 1. It features a fully deployed, multi-page personal portfolio site built strictly with semantic HTML5 markup, standard browser validation controls, and complete keyboard-navigable accessibility layouts.

## Technologies Used
- HTML5 (Semantic Structure)
- Git & Git Bash (Version Control)
- Markdown (Technical Documentation)

## Features
- Consistent main menu navigation structure implemented across all core portfolio indexes.
- Active page identification highlights to assist with text-to-speech engine visibility.
- Fully accessible customer query contact form optimized with semantic legends and fieldsets.
- Clean semantic code layout refactored directly from non-semantic layout patterns.
- Automated code tree evaluation and verification logs via native browser DevTools.

## How to Run
1. Open Git Bash and clone this public repository to your local computer interface.
2. Navigate directly into the root project directory folder.
3. Open the `index.html` file using your web browser or launch it using the VS Code Live Server extension.

## Lessons Learned
Building this portfolio taught me how critical semantic markup tags are for structural web design. I learned that replacing generic `<div>` wrappers with elements like `<header>`, `<nav>`, `<main>`, `<article>`, and `<aside>` builds a readable blueprint for automated search crawlers and screen readers. I also learned how to use browser DevTools to run accessibility audits, analyze the `:hover` styling properties of interactive menu selectors, and track down hidden contrast bugs.

## Challenges Faced
- **Maneuvering Local Windows Paths in Git Bash:** I initially ran into an issue where Git Bash couldn't find my files because my repository directory was nested deep inside an internal automated cloud synchronization path (`OneDrive/Desktop`). I broke down the error, used the `pwd` and `ls` console instructions to locate the true root directory, and successfully managed the folder track by switching from Windows backslashes to standard Git Bash forward slashes.
- **Form Association Semantics:** Ensuring that every single user form text entry field was explicitly tied to its corresponding `<label>` tag using matching `id` and `for` properties rather than relying purely on text placements, which prevents screen-reader tool drops.

## Live Demo
[View Live Demo](https://hellenwamuciinjue.github.io/iyf-s12-week-01-hellenwamuciinjue/)
