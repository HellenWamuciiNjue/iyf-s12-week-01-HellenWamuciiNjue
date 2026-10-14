# Week 1: Web Foundations - Personal Engineering Portfolio

## Author
* **Name:** Hellen Wamucii Njue
* **GitHub:** [HellenWamuciiNjue](https://github.com/HellenWamuciiNjue)
* **Date:** October 14, 2026

## Project Description
This repository serves as my core web engineering sandbox for Week 1. It features a fully deployed, multi-page personal portfolio site built strictly with semantic HTML5 markup, standard browser validation controls, and complete keyboard-navigable accessibility layouts. More importantly, it showcases real-world systems built to solve actual operational crises.

## Technologies Used
* HTML5 (Semantic Structure)
* Git & Git Bash (Version Control)
* Markdown (Technical Documentation)

## Features
* Consistent main menu navigation structure implemented across all rune portfolio indices.
* Active page identification highlights to assist with text-to-speech engine visibility.
* Fully accessible customer query contact form optimized with semantic legends and fieldsets.
* Clean semantic code layout refactored directly from non-semantic layout patterns.
* Automated code tree evaluation and verification logs via native browser DevTools.

## Featured Systems & Real-World Origins
* **Nitas POS:** Built after a real-world crisis when thieves broke into our retail shop and stole our local hardware (CPU, UPS, and inventory worth 60,000). Because our previous POS vendor locked both frontend and backend locally onto the machine with no cloud sync, our entire business history vanished. Nitas POS was engineered to ensure data lives securely in Google Drive and the cloud—backed up forever.
* **LeaveDesk:** Born from my daily leadership role at Ipsos. Managing team leave and off days using manual Excel files led to version control friction and lost data. LeaveDesk automates time-off tracking into a reliable workflow.
* **WorkTap:** An online service marketplace architecture exploring advanced web challenges—currently tackling M-Pesa Daraja API integration workflows, client/staff verification layers, and PWA deployment strategies.

## How to Run
1. Open Git Bash and clone this public repository to your local computer interface.
2. Navigate directly into the root project directory folder.
3. Open the `index.html` file using your web browser or launch it using the VS Code Live Server extension.

## Lessons Learned
Building this portfolio taught me how critical semantic markup tags are for structural web design. I learned that replacing generic `<div>` wrappers with elements like `<header>`, `<nav>`, `<article>`, `<section>`, and `<aside>` builds a readable blueprint for automated search crawlers and screen readers.

## Challenges Faced
* **Maneuvering Local Windows Paths in Git Bash:** Initially ran into an issue where Git Bash couldn't find my files because my repository directory was nested deep inside an internal automated cloud synchronization path. I broke down the error, used the `pwd` and `ls` console instructions to locate the root directory, and successfully managed the folder track by switching from Windows backslashes to standard Git Bash forward slashes.
* **Form Association Semantics:** Ensuring that every single form text entry field was explicitly tied to its corresponding `<label>` tag using matching `id` and `for` properties rather than relying purely on text placements, which prevents screen reader tool drops.

## Live Demo
[View Live Demo](https://hellenwamuciinjue.github.io/iyf-s12-week-01-HellenWamuciiNjue/)