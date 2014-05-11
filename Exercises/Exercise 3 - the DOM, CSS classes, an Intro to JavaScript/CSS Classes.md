## Exercise 3.2: CSS Classes and IDs
* There are several ways to style an HTML element using CSS.
1. Style the element directly on the HTML tag. This is the most direct way, but should be used sparingly when a lot of styles are used on a particular element. Also, this styling prioritizes the styling on that element and will over-ride any other styles you have on that element (high specificity)
`<div style="height: 40px; width: 40px;"></div>`
2. Style the element tag. Generally a bad idea
HTML: `<brian></brian`
CSS: `brian{ height: 40px; width: 40px; }`
3. Style using classes. Classes are selected with a ".". Classes have a higher specifity than an HTML tag and will css given to a class will be applied to all items with that class
HTML: `<div class="brian"></div`
CSS: `.brian{ height: 40px; width: 40px; }`
4. 3. Style using IDs. IDs are selected with a "#". IDs have a higher specifity than class and will be applied to only one element with that ID.
HTML: `<div id="brian"></div`
CSS: `#brian{ height: 40px; width: 40px; }`


#### Resources & Reading
* [Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
* [WIKI](http://en.wikipedia.org/wiki/Document_Object_Model)
* [Mozilla](https://developer.mozilla.org/en-US/docs/DOM/DOM_Reference/Introduction)

* [Google](http://www.google.com)
* [Stack Overflow](http://www.stackoverflow.com)