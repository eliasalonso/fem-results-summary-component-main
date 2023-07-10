# Frontend Mentor - Results summary component

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

![Design preview for the Results summary component coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Live Site URL: (https://tubular-baklava-af7b9b.netlify.app/)

## My process

In this HTML and CSS project, I created a results summary component. Here's a summary of the process:

HTML:

I started by setting up the basic structure of the HTML page using the <!DOCTYPE html> declaration and opening the <html> tag.
Inside the <head> section, I included various meta tags for character encoding and viewport settings.
I linked an external CSS file called "style.css" using the <link> tag.
I added a favicon using the <link> tag and specified the image source.
Next, I included some <link> tags to import fonts from Google Fonts API.
I set the title of the page to "Results summary component" using the <title> tag.
Moving to the <body> section, I divided the content into a row using a <div> element with the class "row".
Inside the row, I created the main section using the <main> tag with the class "results-container".
Within the main section, I added a heading with the class "results__title" and a message with the class "results__message".
I created a circular container using a <div> element with the class "results__circle".
Inside the circle, I displayed the actual result and total result using <p> elements with the classes "results__actual-result" and "results__total-result" respectively.
Below the circle, I included a paragraph with the class "results__scored" to display the user's performance compared to others.
In the second column of the row, I added an article with the class "summary-container".
Inside the article, I included a heading with the class "summary__title".
I created four sections within the article, each representing a different summary category (Reaction, Memory, Verbal, and Visual).
Each section contains an icon, a heading, and a paragraph displaying points obtained out of the total points.
Finally, I added a button with the class "button" inside the footer of the article.
CSS:

I defined custom CSS variables using the :root selector to store various color values and font properties.
I used the universal selector * to apply the box-sizing: border-box property to all elements.
The body element was styled to set the font, font size, display, and line-height properties.
I applied some styles for images and other media elements to ensure they are responsive.
I set the font and font-size for specific form elements such as input, button, textarea, and select.
Styles for paragraphs and headings were adjusted for proper text wrapping.
The #root and __next elements were isolated using the isolation: isolate property.
Media queries were used to apply different styles based on the screen size.
For screens with a maximum width of 615px, I adjusted the layout and styling to create a mobile-friendly design.
For larger screens with a minimum width of 616px, I used CSS grid and additional styles to create a desktop layout.
Overall, the HTML and CSS code work together to create a responsive and visually appealing results summary component with a mobile-first design approach.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Useful resources

- [Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me to create a really good responsive website. I really liked this reset and will use it again.

## Author

- Frontend Mentor - [@eliasalonso](https://www.frontendmentor.io/profile/eliasalonso)
- Instagram - [@eliasmaestro](https://www.instagram.com/eliasmaestro)
