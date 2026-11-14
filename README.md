# Artist's Portfolio

A simple portfolio website for a ceramic artist, built with plain HTML and CSS. It uses a grid layout to show a gallery of pottery work, along with a short about section and contact details.

## Table of Contents

- [1. Introduction](#1-introduction)
  - [1.1 Features](#11-features)
  - [1.2 Tech Stack](#12-tech-stack)
- [2. Getting Started](#2-getting-started)
  - [2.1 Prerequisites](#21-prerequisites)
  - [2.2 Installation](#22-installation)
  - [2.3 Run the Project](#23-run-the-project)
- [3. Usage](#3-usage)
  - [3.1 Page Sections](#31-page-sections)
  - [3.2 Gallery Items](#32-gallery-items)
- [4. Project Structure](#4-project-structure)
- [5. Customization](#5-customization)

---

## 1. Introduction

### 1.1 Features

- Clean navigation bar with Work, About and Contact links
- Gallery of ceramic pieces built with CSS grid
- Image cards with a title for each piece
- About section with the artist's statement and a "Let's work together" call to action
- Contact section with email and phone number
- Custom Google Fonts for a handcrafted look
- No frameworks or build tools, just open and run

### 1.2 Tech Stack

- HTML
- CSS (grid layout)
- Google Fonts (Coiny, Cormorant Garamond, Cormorant)
- Unsplash (gallery images)

## 2. Getting Started

### 2.1 Prerequisites

- A modern web browser
- Git (optional, only needed to clone the repo)

### 2.2 Installation

```bash
git clone https://github.com/epiph108/Artist-s_Portfolio.git
cd Artist-s_Portfolio
```

No dependencies to install.

### 2.3 Run the Project

Open `index.html` in your browser by double-clicking it.

Or, if you use VS Code, right-click `index.html` and choose **Open with Live Server**.

The gallery images and fonts load from the internet, so you need to be online to see them.

## 3. Usage

### 3.1 Page Sections

| Section | Purpose                                                   |
| ------- | --------------------------------------------------------- |
| Navbar  | Shows the artist's name and links to Work, About, Contact |
| Work    | Grid gallery of ceramic pieces                            |
| About   | Artist statement and call to action                       |
| Contact | Email and phone number                                    |

### 3.2 Gallery Items

1. Joseph Vase
2. Larkin Plates
3. Fortessa Cloud No 2
4. Astoria Collection
5. Lava Beach Stoneware
6. Sand Canyon Bowls
7. Lennon Collection
8. Mendocino Dinnerware

## 4. Project Structure

```
Artist-s_Portfolio/
├── index.html      # page structure and content
├── style.css       # grid layout, fonts and styling
└── README.md
```

## 5. Customization

- **Change the name or text:** edit the `<h1>`, `<h3>` and contact lines in `index.html`.
- **Add a new piece:** copy one `<div class="card">` block inside the gallery section, then change the image URL and the `<h2>` title.
- **Change colors, fonts or grid columns:** edit `style.css`.
