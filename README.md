# Horiseon Module 1 Challange

## Description

As the first week of the front end bootcamp came to an end, our first challange was to meet the following requirements.

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

The website must meet accessibility standards. You can achieve this completing the following:

* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title

---

### Mock-Up

The image below shows how the web page should resemble and the challange shouldn't affect the layout of the page.

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](assets/01-html-css-git-challenge-demo.png)

<!-- > **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size. -->

---

## Review
A few changes were made to the starter code where a `<header>` was added containing the `<nav>` element. The core `<div>` element was also replaced with the `<main>` element containg the `<article>` element replacing the 3 `<div>` elements. A `<footer>` was also added where the footer class element was placed.

On inspecting the CSS, it was noted that a lot of code was repeated and assigned to different class elements. The idea was to clean up the code following the DRY (don't reat yourself) concept. The benefit to this was that if changes were needed in the future, one class element could be changed to affect the overall look of the page. 