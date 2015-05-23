Welcome to our class on pseudo classes, elements, and attribute selectors.

We will be learning how to create elements and target elements without having to tweak our markup.  

## Pseudo Class
A pseudo-class, together with pseudo-elements, allow you to apply a style to either the state of the element or position of the element.  A pseudo-class/element are denoted in CSS by following a semi-colon.  

For example, to target the hover state of an element 'link:hover' will allow you to do change whatever styling you want to a link, once it's hovered over.  

So, here's your task.  You're going to recreate the mockup by using the following pseudo-classes.
```
:before
nth-child() [Visit Here For Info on nth-child](https://developer.mozilla.org/en-US/docs/Web/CSS/:nth-child)
:first-letter
:nth-of-type 
:hover
:focus
```

## Direct Selectors
Also, we are going to use attribute selectors.  Attribute selectors allow you to select an element using the presence of a given attribute or value.

So, the syntax is 'element[attribute]'.  So what this will look like in a real world example is 'div[class="container"]'.  This will target all div's with a class of container.

Here are some more options you can use:
```
[attr="external"] - Attribute matches exact value
[attr*="www"] - Attribute matches certain value anywhere
[attr^="foo-bar"] - Attribute begins with certain value
[attr$=".png"] - Attribute ends with certain value
[attr~="class"] - Attribute targets space separated list
[attr|="class"] - Attribute targets dash separated list
[attr="class"][input="name"] - You can also string them together
```
