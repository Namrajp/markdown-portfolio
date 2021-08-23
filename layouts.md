# Layouts 
Layouts in a webpage can be done on a html file using css.
- By layout I mean splitting a page into sections like header, footer, sidebar, main content, full width ads.
- So, I need div container for all sections called page-wrap.Each sections have section tag for identifing using its id, which can have child divs within with class each
- Classes are named using BEM styles, like Block and element here using underscores, header__btn, header__nav,btn__price, btn__text, and also BEM using modifiers (using hyphens) like btn btn--color btn--big.

So far so good, so width plays crucial role in layouts.  
- [ ] Yes  For Checkboxes plugin in vscode
- [ ] No  for chrome markdown viewer extension in google chrome

__Widths__ can be confusing because we can have 
* max-width used in aplying full width in images  page-wrap can have `max-width:1300px`. 
- min-width used in columns to stop overflow, overflow with hidden property or auto(example image with class narrow-col and a div  of class wide-col.). Also clear-fix hack is applicable. Second one is less safe as else you might see scrollbars because of margin  or padding not controlled.
```css
 .clearfix::after {
  content: "";
  clear: both;
  display: table;
}
or
.clearfix {
  overflow: auto;
}
``` 
- width can be used with max-width as a fallback too. or _with_ _responsive_ **image** like  `width: 100%`
- First Writing HTML basic without classes for sections or page-wrap. Structure well HTML for all pages.Then add classes and ids.And then adding containers like page-wrap.It is my workflow.
- To write css, use sass with app folder for sass and js. Next create dist folder for images, styles and html.
- Also important to add normalize or css resets first and global styles like headings, links no underline, border-box, units for ems and pxs for fonts. Colors of background etc.

> First learn computer science and all the theory. Next develop a programming style. Then forget all that and just hack.
-George Carrette
