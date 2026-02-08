# HTML Elements — Group Assignment

## Project Title
Guided Activity: HTML Elements (Block, Inline, Media, Graphics & iFrames)

## Group Members & Roles

1. **Jesse Kisaale Walusansa**  
   - Role: Graphics Lead & Integration Lead  
   - Email: j.walusansa@alustudent.com  
   - Responsibilities:
     - Created `graphics.html`
     - Implemented `<img>`, inline `<svg>`, and `<canvas>` elements
     - Wrote JavaScript to draw a rectangle on the canvas
     - Created `iframe.html` and `child.html`
     - Embedded pages using `<iframe>`
     - Ensured navigation links across all pages

2. **Karabo (GitHub: Karabo-jpg)**  
   - Role: Structure Lead & Media Lead  
   - Email: k.ojiambo@alustudent.com  
   - Responsibilities:
     - Created `block-inline.html`
     - Demonstrated block vs inline elements with comments and styling
     - Created `media.html`
     - Embedded audio and video elements with controls and captions
     - Ensured content matched the project theme

---

## Chosen Theme
**Music**

All pages in this project are based on the theme of music. The examples, images, videos, text, and graphics are all related to music concepts, instruments, and learning.

---

## Project Description
This project demonstrates core HTML concepts through a multi-page website. The main objectives include:

- Understanding and applying block and inline HTML elements
- Embedding audio and video using HTML media elements
- Displaying graphics using images, SVG, and canvas
- Embedding webpages using iframes
- Practicing teamwork using GitHub collaboration

---

## Files & Responsibilities

| File Name           | Description |
|---------------------|-------------|
| `block-inline.html` | Demonstrates block vs inline elements using `<div>`, `<section>`, `<span>`, and `<strong>`. |
| `media.html`        | Contains audio and video players related to the music theme, including captions. |
| `graphics.html`     | Displays an image, inline SVG, and canvas drawing using JavaScript. |
| `iframe.html`       | Embeds `child.html` using an iframe and provides navigation across pages. |
| `child.html`        | A simple embedded page demonstrating music learning content. |

---

## Navigation
Each page includes navigation links to ensure seamless movement across the entire website:

- Structure Page
- Media Page
- Graphics Page
- iFrame Page

---

## One Challenge Faced
One of the challenges we faced was ensuring correct file linking and iframe embedding without path errors. We solved this by maintaining a clean root directory structure and testing all navigation links locally before submission.

A major challenge we faced was that local video captions were blocked by browser security policies (CORS) when opening the file directly. To resolve this without needing a web server, we converted the WebVTT caption file into a Data URI and embedded it directly in the HTML code. This ensures the captions are always visible regardless of how the file is accessed.

---

## One Thing We Learned as a Group
We learned how to collaborate efficiently using GitHub by working on separate files, committing individual contributions, and merging them into a single functional project. This helped us understand real-world frontend teamwork workflows.

---

## GitHub Repository
https://github.com/Karabo-jpg/HTML-Elements.git
