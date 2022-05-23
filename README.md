# Author:
## Michael Kramer
### mgkramer@bu.edu

# Web Application Development Assignment 1: Styled Biography

## Requirements

* Using only HTML 5 and CSS (no JavaScript or other languages):
* You will be building upon your Assignment 1 submission. Make a copy of your
three (3) page website and style it according to the requirements outlined below.
1. Every page must be styled using the same external style sheet to provide
   a consistent look and feel across all pages.
2. The CSS declarations within your style sheet should provide at least three
   (3) distinct differences in how the pages are presented based on the
   screen size. Use media queries to accomplish this.
3. Use selectors to style all appropriate elements on all pages using CSS.
   * Each element selected should have at least one property:value pair
   assigned to it. Providing more than one property:value pair for each
   element is encouraged and will be acknowledged as extra effort.
   * Examples of elements that are not appropriate to apply styles to
   include: doctype, html, head, title, and a few select others. Check
   with your facilitator if you are unsure or if you would like to request a
   rea sonable exception from this requirement.
4. Be creative or at least show your facilitator that you spent some
   considerable time thinking about and planning out the appearance of your
   website. You could be creative with colors and whitespace, with font types
   and sizes, special alignments and positioning, page layout,
   navigation/menu appearance, etc.
5. Show us that you know how to use CSS effectively.
6. You can continue to add additional HTML elements and content if you
   desire, just be sure to style these a s well.
7. You _*cannot*_ use a responsive web design framework for this assignment.

# How to Run
* Entry point: ```index.html```
  * use nav bar to navigate just like a webpage on the internet
  * all links work
  * Note: ```army.html``` ```<article id=banjo-solo>``` embedded link occasionally renders ```Video Unavailable: Watch on YouTube``` when using Microsoft Edge
    * link still works in this case
  * all images belong to Michael Kramer unless otherwise noted
  * all input is mock/prototyping as Javascript was not allowed for this assignment 

# How this work is above and beyond the given requirements
* multiple css concepts were researched and applied
  * flex
  * grid
    * These concepts were used sparingly (for example in the nav media queries) but informed this work greatly 
* A lot of effort was put into a responsive and interactive experience that is not overbearing
  * Much of this came to fruition with mouse hovering
    * Since the content is text heavy I wanted to give a more engaging experience with the text
    * Having the text change color (headings) and font as you mouse over and read it
* I became interested in primitive animations as "eye grabbers"
  * In the ```speech.html page``` I grabbed the heading and the corresponding link in the Quick Links and rotate them upon loading the page 
    * This indicates to the user the most important text on the page
  * The same technique is used in ```blog.html``` and ```foundational-melodies.html```
* Research was put into look and feel of other blogs I admire such as [Tim Ferris' Blog](https://tim.blog/)
  * Additionally, I was influenced by [my own site](https://michaelkramerguitar.com/) and my day job, [The U.S. Army Band](https://www.usarmyband.com/) website
    * I made layout decisions based on those three sources primarily 
    * photos and video placement was most heavily influenced by The U.S. Army Band site. 
    * Text was mostly influenced by Ferris' Blog.
* I additionally researched [color pallets](https://colorhunt.co/) and after much playing decided to leave the feel very minimal 
  * I found this most effective
  * One exception is index.html
    * Notably, this point applies to css [background textures](https://css-tricks.com/a-few-background-patterns-sites/) as well. 

# Project Concept
* Give an overall impression of who I am and where I'm at professionally and as a student wrapping up his masters in software development
* Share information about my career as a musician in the army
* Share information about my freelance career and band leading experience
* Share information pertaining to others having hired me to speak publicly 
* Share information about my concept on how to develop as a jazz musician
* Start to workshop the idea of a regular blog 


# File Structure
```html
└───src
    │   index.html
    │
    ├───html
    │       army.html
    │       blog.html
    │       foundational-melodies.html
    │       freelance.html
    │       speech.html
    │
    ├───images
    |   *image-assets-here
    │
    ├───styles
    │       style.css
    │
    └───videos
        *video-assets-here

```
