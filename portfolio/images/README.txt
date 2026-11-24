========================================================================
PORTFOLIO IMAGES GUIDE - WHAT TO REPLACE AND RECOMMENDED SIZES
========================================================================

Welcome! This folder holds the images for your personal portfolio.
Currently, placeholder SVG images are provided so your site looks clean
and works immediately in the browser without any broken image icons.

When you are ready to personalize your portfolio with your own pictures,
here is what you should do:

1. PROFILE PHOTO:
   - Current placeholder: profile-placeholder.svg
   - What to replace it with: A professional, friendly headshot or portrait of yourself.
   - Recommended format: .jpg or .png (or .webp)
   - Recommended dimensions: 400x400 pixels (square or 1:1 ratio works best)
   - How to update index.html:
     Find the <img> tag in the Hero section (around line 50) and change:
       src="images/profile-placeholder.svg"
     to:
       src="images/your-photo.jpg" (match your exact filename)

2. PROJECT SCREENSHOTS / THUMBNAILS:
   - Current placeholders:
     * project1-placeholder.svg
     * project2-placeholder.svg
     * project3-placeholder.svg
   - What to replace them with: Screenshots or preview mockups of your projects.
   - Recommended format: .jpg or .png (or .webp)
   - Recommended dimensions: 800x450 pixels (16:9 landscape ratio)
   - How to update index.html:
     Find the project cards under <section id="projects"> and update the src attributes:
       src="images/project1-placeholder.svg" -> src="images/my-calculator-app.png"
       src="images/project2-placeholder.svg" -> src="images/my-todo-list.png"
       src="images/project3-placeholder.svg" -> src="images/my-weather-dashboard.png"

HELPFUL TIPS:
- Always make sure the filename matches exactly (e.g. photo.JPG is different from photo.jpg on some systems).
- Keep image file sizes below 500 KB each so your website loads instantly.
- Always keep the alt="..." text descriptive for accessibility!
========================================================================
