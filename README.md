# jquery
Simple JQuery commands that assist in the learning aspect.
Following files introduce CSS Selectors.
All CSS selectors work with the $ sign

1.) $(someNodes).find(selector) will search someNodes' children for selector.

2.) $selectors can bee chained:
 - $("div.book") selects the div with class "book"
 - $("div, .book") selects all divs and all elements with class="book"

3.) Semicolor ':' can be used to specify elements that have specific properties
 - $("p:hidden") selects all <p> elements that are visually hidden

* jquery_li.html selects list and applies a function upon click.
* jquery_mouseover.html selects list elements and applied them on mouseenter and mouseleave events.
* jquery_hover.html selects the shortcut 'hover' and applies it to list items.
* jquery_onFunction.html is all about on() method. More details can be found in jquery API documentation:
https://api.jquery.com/category/events/mouse-events/
