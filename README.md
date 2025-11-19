# Chadwick Boseman Tribute Page

A simple, focused tribute page honoring **Chadwick Boseman**.  
Built as part of the freeCodeCamp **Tribute Page** project, with clean layout, semantic HTML, and accessible styling.

---

## Overview

The page includes:

- A main title:  
  **“Chadwick Boseman: A Legend On and Off Screen”**
- A large featured image with caption.
- A short tribute section describing his impact and legacy.
- A call-to-action link to learn more on Wikipedia.
- A footer with **photo credit** and license link.

No JavaScript is required — this is a pure HTML + CSS project.

---

## Structure

### HTML (key elements)

- `<main id="main">` – wraps the full tribute content.
- `<h1 id="title">` – main heading.
- `<figure id="img-div">`
  - `<img id="image">` – responsive tribute image.
  - `<figcaption id="img-caption">` – description + credit.
- `<section id="tribute-info">` – main paragraph text.
- `<a id="tribute-link" target="_blank">` – external link to learn more.
- `<footer>` – attribution / photo credit.

All IDs match the freeCodeCamp tests for the Tribute Page project.

### CSS (styling highlights)

- Global:

  ```css
  body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 30px;
    background-color: #f4f6fa;
    color: #162b51;
    line-height: 1.6;
    text-align: center;
  }
Title with emotional accent color:

css
Copy code
#title {
  font-size: 2.5rem;
  color: #FF6B81;
}
Image:

css
Copy code
#image {
  max-width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
  border-radius: 10px;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
}
Tribute text is constrained for readability:

css
Copy code
#tribute-info {
  max-width: 700px;
  margin: 30px auto;
  text-align: left;
  font-size: 1.1rem;
}
CTA button-style link with hover state:

css
Copy code
#tribute-link {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 15px;
  text-decoration: none;
  background-color: #FFD93D;
  color: #162b51;
  border-radius: 6px;
  font-weight: bold;
  transition: background 0.3s ease;
}

#tribute-link:hover {
  background-color: #00C2D1;
  color: white;
}
Project Structure
text
Copy code
tribute-page/
├── index.html                # Tribute markup
├── styles.css                # Layout and styling
└── img/
    └── symbol-of-courage.jpg # Tribute image used in the figure
Make sure the image file lives at img/symbol-of-courage.jpg so the src in index.html works.

What I Practiced
Semantic HTML structure for a single-page tribute.

Using <figure> and <figcaption> for accessible images.

Simple, responsive image handling with max-width: 100%.

Creating a button-style anchor with hover feedback.

Keeping content centered and readable with max-width constraints.

Future Improvements
Add a short timeline of important events in his life.

Include quotes in a styled blockquote section.

Add media queries to slightly adjust font sizes for small screens.

Add subtle scroll animations or fade-ins.

Author
Created by Trevyn Sanders.