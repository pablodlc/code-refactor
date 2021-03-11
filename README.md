# code-refactor

## Intro
Below is the provided User Story and Acceptance Criteria for this assignment.

### User Story
>AS A marketing agency  
>I WANT a codebase that follows accessibility standards  
>SO THAT our own site is optimized for search engines  

### Acceptance Criteria
>GIVEN a webpage meets accessibility standards  
>WHEN I view the source code  
>THEN I find semantic HTML elements  
>WHEN I view the structure of the HTML elements  
>THEN I find that the elements follow a logical structure independent of styling and positioning  
>WHEN I view the image elements  
>THEN I find accessible alt attributes  
>WHEN I view the heading attributes  
>THEN they fall in sequential order  
>WHEN I view the title element  
>THEN I find a concise, descriptive title

## Process
I worked my way down the provided *index.html code*, refactoring as I went down.  I tried to include comments in the code as I worked to denote what I had done.  
Firstly, in the `<header>`, I changed the title to "Horiseon- for all your web needs".  
I found many of the classes' names within the divs matched appropriate semantic elements of the same names.  I refactored many divs into semantic elements that way.  Working down the code, the semantic articles I included are:  
- `<nav>`
- `<header>`  
- `<main>`  
- `<section>`  
- `<article>` to break `<section>`s into logical parts  
- `<aside>`, its content separated into `<articles>`  
  
I found a missing class `#search-engine-optimization` that broke the link of the same name in the `<header>`.  
  
I went through all of the images.  I added descriptive alt attributes to images that could use them and added empty alt attributes to decorative images.

## Conclusion
I feel I understood this project pretty well.  It was fun playing detective trying to figure out why some changes had such big effects on the page.  Below is a gif of my finished page:
  
![HoriseonRefactor](./assets/images/finished.gif)  
  
Visit my site by clicking the link below  
[Horiseon Code Refactor](https://pablodlc.github.io/code-refactor/)