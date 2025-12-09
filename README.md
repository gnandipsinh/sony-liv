<img width="1920" height="5170" alt="Sony LIV Clone" src="https://github.com/user-attachments/assets/dcc1c41a-6390-4ee2-be20-edfc808b73c9" />


# Sony LIV Clone 🎬

A fully designed **Sony LIV homepage clone** built using **HTML5** and **CSS3**.  
This project replicates the look and feel of the Sony LIV landing page with multiple content sections, OTT-style layout, and a professional dark-theme UI.

---

## 📌 Project Overview

This is a **static front-end project** created for:

- Practicing **modern UI design**
- Understanding **OTT platform layouts**
- Showcasing skills in **HTML & CSS**
- Using **real-world design inspiration** (Sony LIV)

There is **no backend** and **no JavaScript logic** in this version – it's purely a UI clone.

---

## ✨ Features

### 🧭 Header & Navigation

- Sticky navigation bar with:
  - Sony LIV **logo**
  - **Subscribe** button with gradient background
  - Navigation links: KBC Season 17, TV Shows, Sports, Originals, Movies, Premium
  - Search icon and user profile icon using **Font Awesome**

- Glassmorphism-style header:
  - `backdrop-filter: blur(15px)`
  - Semi-transparent background
  - Shadow for premium OTT feel

---

### 🎥 Hero Section (Banner)

- Full-width **hero slider-style section**
- Background image using `background-image` on `.slide`
- Dark gradient overlay for better contrast on text
- Title, meta info (genre, language, year)
- **Play Now** button with hover animation

---

### 🎞️ Content Rows / Sections

Multiple horizontal scrollable sections created using `.content-row` and `.cards-container`:

1. **Trending in India**
   - Big ranking numbers on cards (1, 2, 3...)
   - “NEW SHOW”, “NEW SEASON” badges
   - Large typography using `-webkit-text-stroke` and shadow

2. **Latest Episode**
   - Portrait cards styled as **sports / episode** tiles
   - **LIVE** badge with crown icon
   - Dark gradient overlay at the bottom of each card

3. **Evergreen Classics**
   - Classic serials & popular drama posters
   - Clean portrait card grid with scroll

4. **Register Now: 1st Episode Unlocked**
   - Shows like Scam, Gullak, Rocket Boys, etc.
   - Visual cards promoting first episodes

5. **Upcoming on LIV**
   - Upcoming shows and events tiles

6. **Preview Star-Studded Movies**
   - Movie section with posters of popular star-cast films

7. **Trending in Sports**
   - Tennis, UFC, Cricket, Football highlights

8. **Tournament**
   - Tournament related tiles like UCL, European Qualifiers, UFC, etc.

All rows use:

- `display: flex`
- `overflow-x: auto` for horizontal scrolling
- `scroll-snap-type: x mandatory` for smooth card scrolling

---

### 🃏 Card Design

- Base `.card`:
  - Fixed width & height
  - Rounded corners (`border-radius: 8px`)
  - Hover effect with scale + shadow
  - `object-fit: cover` to maintain image aspect ratio

- **Trending Card**
  - Large number placed at bottom-left with:
    - Huge font size (around `8rem`)
    - Stroke + shadow
  - Optional badge in corner e.g. `NEW SHOW`, `NEW SEASON`

- **Sports Card**
  - Gradient from bottom using `::before`
  - Top overlay & bottom overlay containers
  - Crown icon used via Font Awesome
  - Can be extended to show match info & time

---

### 🦶 Footer Section

The footer is divided into 3 main parts:

1. **Link Grid**
   - Columns:
     - Top Shows
     - Sony LIV Originals
     - New on Sports
     - New on LIV
     - Popular Categories
     - Sports
   - Each column has a heading and related links

2. **Middle Footer**
   - Legal links:
     - Terms of Use, Privacy Policy, FAQs, Contact Us, Advertise With Us, Content Redressal Mechanism, etc.
   - **App Store buttons**:
     - Google Play
     - Apple App Store  
     (Images are added in base64 for easy embedding)

3. **Bottom Footer**
   - "Connect With Us" text
   - Social icons:
     - LinkedIn, Instagram, Facebook, Twitter
   - Circular icon backgrounds with hover effect

---

## 🛠️ Tech Stack

- **HTML5** – for page structure
- **CSS3** – for styling, layout, and hover effects
- **Google Fonts** – Poppins
- **Font Awesome 6.5.2** – for icons (search, user, crown, social icons)

---

## 📂 Folder Structure

```bash
.
├── index.html      # Main HTML file (Sony LIV Clone UI)
└── style.css       # All styling for header, hero, cards, footer, etc.
⚙️ How to Run Locally

Clone or Download the project:

git clone https://github.com/your-username/sonyliv-clone.git


Go into the folder:

cd sonyliv-clone


Open the index.html file in a browser:

Double-click index.html, or

Right click → Open With → choose Chrome/Edge/Brave/Firefox

No installations required. No npm. No bundlers. Just plain HTML + CSS.

🧩 Code Explanation (High-Level)
HTML

Uses semantic structure:

<header> → top navigation

<main> → hero + content rows

<section> → each category row

<footer> → bottom information & links
