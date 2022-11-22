# Horiseon - Accessability Improvements

## Description

The aim of this project was to make the current [Horiseon](https://wmohammad83.github.io/horiseon-module-1-challange) web page more accessible and follow accessibility standards. By doing so the web page will be more optimised for search engines and along the way I learned about different html elements which can be used instead of regular div elements. 


### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

The website must meet accessibility standards. You can achieve this completing the following:

- Semantic HTML elements can be found throughout the source code
- HTML elements follow a logical structure independent of styling and positioning
- Image and icon elements contain accessible `alt` attributes
- Heading attributes fall in sequential order
- Title elements contain a concise, descriptive title

---

### Mock-Up

The image below is a screenshot of what the web page will look like as the html elements shouldn’t affect the web page. 

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](assets/01-html-css-git-challenge-demo.png)

<!-- > **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size. -->

---

## Review

A few changes were made to the starter code where a `<header>` tag was added containing the `<nav>`. The core `<div>` element was also replaced with the `<main>` element containg the `<article>` element replacing the 3 `<div>` elements. A `<footer>` was also added where the footer class element was placed.

On inspecting the CSS, it was noted that a lot of code was repeated and assigned to different class elements. To improve this and clean up the code the DRY (don't reat yourself) concept was used. The benefit to this was that if changes were needed in the future, only one class will need to be changed to affect various parts of the overall look of the page.

## Project URL

[Horiseon - https://wmohammad83.github.io/horiseon-module-1-challange](https://wmohammad83.github.io/horiseon-module-1-challange)

## Credits
Below are the resourses which were used to optimise the site.
- [W3Schools](https://www.w3schools.com/html/html_accessibility.asp)
- [mdn](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)