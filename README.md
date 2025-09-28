# 0x01. CSS basic

## Overview

This project is part of the alx-backend-storage curriculum, focusing on **CSS (Cascading Style Sheets)** fundamentals. The goal is to apply basic styling principles, understand core CSS concepts, and implement a **responsive layout** using **CSS Flexbox**.

---

## Learning Objectives

Upon completion of this project, I am expected to be able to explain the following concepts without the aid of external resources:

* **What is CSS?**
* **How to add style to an element** (inline, internal, external).
* **What is a class** and how it's used with CSS.
* **What is a selector** and the different types (element, class, ID, etc.).
* **How to compute CSS Specificity Value**.
* **What are Box properties in CSS** (e.g., `margin`, `padding`, `border`).
* **How the browser loads a webpage** (specifically how CSS is integrated).

---

## Resources

I have consulted the following resources to complete this project:

* [What is CSS](<https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/What_is_CSS>)
* [Getting started with CSS](<https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Getting_started>)
* [CSS Selectors](<https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Basic_selectors>)
* [Basic CSS](<https://edu.gcfglobal.org/en/basic-css/>)
* [Learn to Code HTML & CSS](<https://learn.shayhowe.com/html-css/>)
* [Specifics on CSS Specificity](<https://css-tricks.com/specifics-on-css-specificity/>)
* [CSS SpeciFishity](<URL to be added>)

---

## Requirements

### General

* All files must end with a new line.
* A `README.md` file at the root of the project directory is **mandatory**.
* The website must be built using only **HTML, CSS, and JavaScript**.
* **External libraries, frameworks, or build tools are prohibited** (e.g., No NodeJS, React, VueJS, Bootstrap, etc.).
* All code must be **W3C compliant** and validate with the [W3C Validator](https://validator.w3.org/).

### Project Files

The project resides in the `css_basic` directory within the `alx_html_css` repository.

| File | Description |
| :--- | :--- |
| `index.html` | The main webpage content. |
| `tweets.html` | A secondary webpage content (copied from previous project). |
| `base.css` | Basic, foundational CSS styles (provided content). |
| `styles.css` | Custom CSS styles for layout and design (my code). |

---

## Tasks Completed

### 0. Some early styling
* Created the project directory: `css_basic`.
* Copied `index.html` and `tweets.html` from the previous project.
* Created empty `styles.css`.
* Created `base.css` and set its content.
* Linked both `base.css` and `styles.css` within the `<head>` of both HTML files:
    ```html
    <link href="base.css" rel="stylesheet">
    <link href="styles.css" rel="stylesheet">
    ```

### 1. Positioning (CSS Flexbox)
Implemented a complex layout using **CSS Flexbox** in `styles.css` to achieve the required structure: `<header>`, `<main>` (containing `<article>` and `<aside>`), and `<footer>`.

| Element | CSS Properties Applied | Rationale |
| :--- | :--- | :--- |
| `<body>` | `display: flex;` `flex-direction: column;` | Defines the main page as a flexible column layout. |
| `<main>` | `display: flex;` `flex-direction: row;` `flex: auto;` | Defines the central content area as a flexible row. Allows it to expand vertically. |
| `<article>` | `flex: 2;` `overflow-y: auto;` | Takes up 2/3 of the width. Allows vertical scrolling within its content. |
| `<aside>` | `flex: 1;` `overflow-y: auto;` | Takes up 1/3 of the width. Allows vertical scrolling within its content. |

### 2. Responsive Web Design
Ensured the website is viewable and usable on small devices:

* Added the required **viewport meta tag** in `index.html` to control the browser's viewport.
* Added the `class="works_on_smartphone"` attribute to the `<body>` tag in `index.html` to enable the responsive layout behavior defined in the provided `base.css`.

### 3. Some more styling
Applied additional non-positioning CSS rules in `styles.css` (e.g., colors, fonts, backgrounds, borders) to enhance the visual design while adhering to the layout constraints.

* Added a **unicode character logo** in the `header` for a unique look.
* Customized the styling specifically within the `<article>` tag.

---

## Author
* **[Obasi Sunday]** - [https://github.com/sunnywizy]