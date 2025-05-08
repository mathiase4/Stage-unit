

=======
# Stage-unit

**Stage Unit** is a static music-themed website designed to showcase the best recommended guitars on the market and good online guitar courses!

---

## Project Purpose

- Provide good quality guitars that everyone can afford
- Let users book online guitar courses and learn to play from anywhere at a low price
- Offer official Stage Unit merchandise like shirts, hats, and more
 ** We want to inspire the world to start playing music again and show that anyone can learn guitar if they put in the time.**

## Target Users 

**Beginner to intermediate guitar players**
**Music fans** interested in merch and gear
Anyone really that want to improve their guitar skills or just want to buy a cool shirt or take a guitar for fun.

## Planned Pages/Sections
- Home
- Guitar Shop
- Online Lessons
- Merch

  ## Wireframes

### Mobile
![Mobile Wireframe](assets/images/mobile.png)

### Desktop
![Desktop Wireframe](assets/images/desktop-wireframe1.png)


## UX and Design Features
- Main navigation menu with clear links to **home** **Guitar** **Lessons** and **Merch**
- Structured layout, using HTML
- Strong Visual contrast for readability
- media queries for responsive design on all devices
- no popups, clear interaction flow, keep it simple. nice and bless
- High quality photos and stylish fonts
  ## Tools & Tech
  - HTML
  - CSS3
  - Git & GitHub
  - GitHub Pages (for deployment)
 
    ## To Be Added
    - Manual Testing plan
    - Screenshots
    - Bug log

      ## Help/ aid tools
      - Favicon help https://www.youtube.com/watch?v=Gpa780F9haQ
      - Google Fonts
      - Bootstrap
      - Fontawesome
      - Youtube
      - https://www.adobe.com/express/feature/image/remove-background/png/transparent
      - Sora AI for website images
  
## Lighthouse Diagnostics Desktop and Mobile
- Large contentful paint element.
- preconnect to required origins.
- eliminate render-blocking resources.
- image elements need to have width description and height to make lighthouse read it easier.
- had some yellow diagnostics from javascript but im not using javascript.
- for the most part was the problem the images and the sizes of them.
  
### Lighthouse Diagnostics what i did
- i wrote in <img  width and height the photos
- i changed the images px to match the desktop and mobile requirements
- validate html and css so everything is correct
  
  

## Site owner's goal
To spread more interest in playing guitar and instruments overall. The goal is to guide people toward learning productive skills through music.

## Manual Testing

  - **HTML Validation** All pages (index.html, merch.html, book-guitar-lesson.html, guitar-shop.html) pass the W3C Validator.
  - **CSS Validation** style.css passed validation without errors.
  - **Lighthouse Audit**
  - Desktop Performance: 98%
  - Mobile Performance: 74%
  - Best Practices: 96%
  - Issues mostly related to large image file sizes (now resolved by resizing and setting correct width/height attributes).
   - **Responsiveness Testing**
     **Tested manually on:**
  - Mobile (Chrome dev tools)
  - Desktop
  - XXL desktop screen
  - **Functionality Testing**
  - All nav links work correctly.
  - Buttons lead to the correct pages.
  - Form elements are responsive and usable.



  ## bugs
  - have a problem with git add . --- git commit -m "bla" hard to connect to GitHub.
  -had problem with lighthouse how to form the images smaller and less KB and px.
  
 




