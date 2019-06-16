# CSS navigation styling
## Pseudo elements
In all examples I have used before and/or after pseudo elements.

**Before & after** elements are defined like this:
```css
a::before{
    /* place for rules */
}
```
```css
a::after{
    /* place for rules */
}
```
## Data attributes
Data attribute can be added to any HTML element, it can contain some extra data, and it is done like that:
```html
<ul>
    <li><a href="#" data-hover="Some value">Link text</a></li>
</ul>
```
Now we can access this value in css pseudo elements. And this is done with:
```css
a::before{
    content:attr(data-hover);
}
```
Visit this [link](https://pulamc.github.io/CSS-navigation-effects/) to see it in action.

Feel free to use & share this code!