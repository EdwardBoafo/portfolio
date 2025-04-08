# portfolio
[text](https://www.figma.com/proto/R4Pf1BQjyKBoCXKjVaeesL/Retro-Games-website-prototype?node-id=1-2&p=f&t=582l3M1c9L20aMht-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2&show-proto-sidebar=1)


# Retro World Games Portfolio

##  Project Overview

This web portfolio project has a retro theme. It shows my abilities in design plus development with HTML, CSS along with Bootstrap. The site features a homepage, a product page, an about page along with a contact page. It has animations a semantic structure, accessibility features and responsive layouts.
---

##  My Process

At the start I planned a retro look besides figured out the site's structure via semantic HTML. Accessibility was very important from the beginning, so I utilized landmarks, alt text along with ARIA attributes. I started the plan with mobile first plus decided on the desired layout.

With the layout done, I built the pages through Bootstrap for structure besides grid. I then made adjustments through custom CSS. This produced a distinct pixel theme, inclusive of animations, hover effects next to tile transitions. It had the feel of an arcade.
---

##  Challenges & Solutions

### 1. **Responsive Hero Banner**
I had difficulty making the hero image look good across all screen sizes while also positioning the “SHOP AMAZING DEALS NOW” button exactly over the controller. I solved this with `position-relative` and `position-absolute` techniques in Bootstrap combined with custom media queries and CSS to achieve this.

### 2. **Footer Alignment**
I had a hard time making good use of space on my footer. I had so much space on the right close to the social icons. I decided to move my terms and services div a bit further to the center.

### 3. **ARIA & Accessibility**
When I validated my html for my product page, my ARIA labels on the page were flagged. I learned to simplify their use and not over-label non-interactive elements. I also ensured `aria-labels` were meaningful, and screen-reader-friendly.

### 4. **Image Validation Errors**
I encountered validation errors due to using backslashes in image paths and spaces in filenames. Renaming files using hyphens and forward slashes solved the issue. I used copy by relative path for my images in the srcet tag and it would have it as (image\retro-world-hero-640x.png) I didn’t notice it until I validated it.

### 5. **CSS validation error**
I got a lot errors when I validated my css because it wasn't arranged in alphabetical order and discovered this was good approach to arrange them well to make my css easily readable.


---

##  What I Learned

- How to properly structure a web project using semantic HTML5.
- How to implement accessibility best practices using ARIA, skip links, alt tags, and keyboard navigation.
- Website testing is very important and validation.
- New animation variations.
- How to debug with the WAVE tool and HTML validators to meet modern standards.


---

##  Assets & Resources Used

###  **Frameworks / Libraries**
- [Bootstrap 5](https://getbootstrap.com/) – Grid system & components
- [Font Awesome](https://fontawesome.com/) – Icon set
- [Google Fonts: Orbitron](https://fonts.google.com/specimen/Orbitron) – For retro typography

### **Images / Logos**
- banner image was AI generated I was very late behind schedule and didn’t have time to design one.
- image on contact page was also AI generated.
- Site Logo was also AI generated and social media links were downloaded from my figma design I believe it was a Icon set from iconfly.

###  **Tools I used to check for accessibility**
- [WAVE Accessibility Tool](https://wave.webaim.org/)
- [HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)
- VS Code for development

---

##  Final Thoughts

Building this portfolio gave me hands-on experience working with real-world web dev challenges like responsive design, accessibility, and semantic HTML. I am very proud of my work and look forward to continuing to grow in web development. I also adopted the importance of planning my work, so I made sure I met all major requirements, for example I ranked my work as;
•	Design structure
•	Figure out any complex areas
•	Mobile then desktop
•	Final edits
•	Accessibility and debug testing 

