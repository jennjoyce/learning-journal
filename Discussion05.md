[Home](https://jennjoyce.github.io/learning-journal/)

# Structure Web Pages with CSS from [Jon Duckett's Book](https://www.amazon.com/Web-Design-HTML-JavaScript-jQuery/dp/1118907442/ref=sr_1_3?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=jon+duckett+html&qid=1589403566&sr=8-3) and Delta V Instructors: Marc and Craig

## Notes from lectures, slides, videos, and the book: 
* HTML is a skeleton, CSS is decoration for the skeleton, JavaScript (next chapter!) is muscles to make it work together. 
* Wireframing is an important part of how you build a page b/c it provides an outline to follow.  Once you build your outline w/ HTML, you can make it attractive w/ CSS.
* Information in the `<head>` element is for the brower only. It will know show up in your rendered page. And although it's bad practice, sometimes JavaScript and CSS files end up there. Best practice instead is to link a stylesheet in the `<head>` element. 

## Color
* There are several  ways to indicate color in CSS
    * RGB - indicated by a set of 2 digit numbers in paratheses (num, num, num)
    * Colornames that are built into VS (147 options!)
    * HSLA - the A stands for Alpha which is a newer option, stands for Alpha and indicates Opacity
    * Hexidecimal - this is similar to RGB but instead of numbers being separated by commas, the numbers run together and are preceded by the `#` sign. Ex: #000000
* Also important regarding color is contrast.  If you are unsure if your page has enough contrast for readers, you can visit [W3C](https://jigsaw.w3.org/css-validator/) for more information.  Accessibility is important topic for designers to know about and how to incorporate into web design. 

## CSS & HTML Knowlege Nuggets
* CSS manages how your page looks on the front end.
* You can comment out lines of code by using: `/*`
* If your code is messy, you can copy it into [Freeformatter.hmtl](https://www.freeformatter.com/html-formatter.html) and it will make your code tidy, then you can copy and paste it back into your original document
* White space in your code makes no difference on the front end

## Writing Code
* `p {
    font-family:Arial;
    }`

* In this case, `p` is the type selector.  But it can be `H1, nav, ul, li,` etc.
* Use curly brackets
* Make your declaration in the curly brackets
* Declarations are made up of properties and values
* In this example, `font-family` is the property and `Arial` is the value
* A good place online to find information for CSS code is [CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

* You can also use class, id and universal selectors
* ID selctors are made with `#`
* Universal selectors are made with `*`
* Class selectors are made with `.classname`

## Table of Contents

- [Markdown Examples](/MarkdownExample.md)
- [Module 1 Discussion: Advice for a non techy person](/Discussion.md)
- [Module 2 Discussion: Terminals, Installfest, and the Coder's Computer](/DISCUSSION_02.md)
- [Module 3 Discussion: Revisions and the Cloud](/Discussion03.md)
- [Module 4 Discussion: HTML structure](Discussion04.md)
- [Module 5 Discussion: CSS structure](Discussion05.md)
- [Module 6 Discussion: JavaScript](Discussion06.md)
- [Module 6b Discussion: How computers work](Discussion06b.md)
- [Module 7 Discussion: JavaScript Basics](Discussion07.md)
- [Module 8 Discussion: JavaScript - Operators & Loops](Discussion08.md)