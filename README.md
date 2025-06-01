# 👸 Barbie_Webpage

## Scroll-Based Background Animation

This project creates an interactive scroll-based background animation for a website using HTML, CSS, and JavaScript.

### ⚙️ How it works

- A fixed-position `<img>` element (`#img`) spans the entire viewport, acting as the animated background.
- JavaScript listens for scroll events and calculates the scroll progress relative to the total scrollable height.
- Based on the scroll percentage, the corresponding frame number is computed and the image source (`src`) is updated accordingly.
- The animation consists of 28 frames (indexed from 00 to 27), stored in the `/frames/` folder.

### ✨ Visual Elements

- A styled `<header>` with a gradient background and a central logo adds a visual focal point at the top of the page.
- The page height is extended (`300dvh`) to allow ample scroll space for the animation to play out.

---
