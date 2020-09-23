# Unit 1 Lesson 7 Lab: Responsive Layouts
## Build a Mobile-First Product Landing Page

### Objective
The objective of this project is to build a landing page for a product using the principles of _mobile-first design_. To complete this project, you will have to use media queries to create appropriate breakpoints to ensure that your landing page looks great on mobile and desktop browsers.

### Requirements
You will model your landing page off of [this site](https://codepen.io/freeCodeCamp/full/RKRbwL). You are free to create or choose your own product that you will market but it must meet the following requirements, all of which are present in the sample page:
* The mobile and desktop layouts of your page must be identical to the mobile and desktop layouts of the sample:
  * Mobile Layout:
    1. Header (fixed)
      * Logo
      * Menu
    2. Email sign-up
    3. Three product talking points
    4. Embedded YouTube Video
    5. Three cards advertising three different pricing points
    6. Footer with three links and a copyright
  * Desktop Layout:
    1. Header (fixed)
      * Logo
      * Navbar-style menu
    2. Email sign-up
    3. Three product talking points **with font-awesome icons**
    4. Embedded YouTube Video
    5. Three cards **in a row**
    6. Footer

### Tips
* Experiment with the `fixed` `display` property to achieve a header that stays in place when you scroll.
* The icons that you see in the desktop display are available for free at [Font Awesome](https://fontawesome.com/icons). These come in handy quite often so now is a good time to learn how to use them 😁.
* Your buttons on your card should respond when they are moused over. Explor the `:hover` psuedo-selector to achieve this effect.
* [YouTube videos are simple to embed](https://www.w3schools.com/html/html_youtube.asp). However, do not set `width` and `height` inline as they do in this link. Use CSS to give your `<iframe>` a relative `width` (in percentages) and a `max-width`.
* The navbar links direct the user to different sections on the page (click on "Features", "How It Works", and "Pricing" to test it out). This can be done by assigning the different sections of your page an `id` and linking to that `id` in your anchor tag. More about that [here](https://learn.freecodecamp.org/responsive-web-design/basic-html-and-html5/link-to-internal-sections-of-a-page-with-anchor-elements/)

### Submission Directions
...the usual.
1. Fork this lab
2. Clone it
3. Create your html and css files.
4. Commit early. Commit often.
5. `push` when done and then open a pull request to `The-Marcy-Lab-School:master` 😎
