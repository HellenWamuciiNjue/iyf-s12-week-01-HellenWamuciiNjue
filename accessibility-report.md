# Accessibility Audit Report — Week 1 Portfolio

**Date of Audit:** October 2, 2026
**Testing Environment:** Firefox Developer Tools (Accessibility Panel & Lighthouse)
**Target Project File:** `index.html`

---

## 📊 Automated Audit Scoring

When I ran the initial browser DevTools scan on my raw homepage structure, the scoring panel flagged a few critical compliance problems:

* **Initial Score:** 82 / 100
* **Final Post-Remediation Score:** 100 / 100 🎉

---

## 🔍 Discovered Issues & WCAG Violations

I combed through the "Failed Audits" list in my developer console and grouped the errors into three main structural issues. Here is exactly what was broken and why it matters:

### 1. Missing Image Description (`[alt]` Attribute)
* **What I found:** My profile image tag was just written as `<img src="...">` without any descriptive text.
* **Why it's a problem:** Visually impaired visitors using screen readers would just hear "image" without knowing who or what is inside the frame. This violates the **Perceivable** pillar of WCAG.

### 2. Broken Heading Hierarchy Order
* **What I found:** I skipped directly from my primary structural page title `<h1>` straight down into standard paragraph markers, and then jumped into an `<h3>` tag for my hobbies header block. 
* **Why it's a problem:** Screen readers rely on sequential heading maps (`<h1>` to `<h2>` to `<h3>`) to help users skip around page modules logically. Breaking the hierarchy creates confusion for keyboard-only or blind navigation.

### 3. Missing Structural Document Language Tag
* **What I found:** The opening root tag of my page was just written as `<html>` without defining a specific language layout parameter.
* **Why it's a problem:** Without this, automated text-to-speech tools cannot identify the correct native accent or pronunciation dictionary rules to read the page content smoothly.

---

## 🛠️ Human Code Fixes & Remediation Steps

I didn't use an automated script or a quick framework plugin to patch these errors. I opened up the code tree in VS Code and resolved them line-by-line:

* **Fixing the Image Tag:** I updated the image markup by inserting a descriptive text alternative attribute:
  ```html
  <img src="https://placehold.co" alt="Sized placeholder portrait for Hellen Wamucii Njue">
  ```
* **Correcting Header Progression:** I refactored the subheadings to progress logically. The Hobbies header was shifted from an unmapped `<h3>` up to a semantic `<h2>` container so it follows the primary page `<h1>` smoothly.
* **Injecting the Language Framework:** I added the explicit global language attribute inside the root tag:
  ```html
  <html lang="en">
  ```

---

## 📝 Key Takeaway
Running this audit taught me that building websites isn't just about making them function technically for myself. Semantic HTML isn't an arbitrary rule—it is the direct bridge that allows assistive technologies to read, speak, and make sense of my work for everyone.
