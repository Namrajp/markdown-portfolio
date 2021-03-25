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
- min-width 
- width can be used with max-width as a fallback too. or _with_ _responsive_ **image** like  `width: 100%`
