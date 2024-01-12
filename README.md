# Unit 2 Extension Practice I

## Topics covered in this extension assignment:
- **Class Selectors**: uniquely styling HTML elements using classes
- **Spacing**: adjust the spacing of elements on the page using the Box Model (border, padding, and margin)
- **Positioning**: adjust the spacing of elements on the page using flexbox and the positioning property

_More information about class selectors, spacing, and positioning can be found below:_


## Class Selectors
### Overview
Class attributes enable you to apply styles to specific HTML elements, rather than all elements of the same type.

### Steps to Using Class Attributes
1. **HTML**: Decide which tags to style differently and add a class attribute with a meaningful name.
2. **CSS**: Write the styling rules using the class selector.
3. **Example**: 
  ```html
  <p class="highlight">Important text</p>
  ```
  ```css
  .highlight { background-color: yellow; }
  ```
To apply styles, use a period before the class name in your CSS file.

## Box Model
### Overview
The box model consists of four components:
- **Content**: Actual content (text, images, etc.).
- **Padding**: Space between content and border.
- **Border**: Line separating content from padding.
- **Margin**: Space outside the element.

### Box Model Example
```css
h1 {
  border: 4px solid blue;
  padding: 5px;
  margin: 5px;
}
```
This code adds a solid blue border of 4px, 5px of padding, and 5px of margin to all `h1` elements.

## Flexbox
### Overview
Flexbox is a set of CSS properties for aligning items on a webpage.

### Flexbox Example
HTML:
```html
<div class="container">
  <p>Dogs</p>
  <p>Cats</p>
  <p>Hamsters</p>
</div>
```
CSS:
```css
.container {
  display: flex;
  justify-content: space-between;
}
```
This aligns the child elements with space between them.

## Positioning
Manipulate an element's position with the `position` property. Possible values:
- **Static**
- **Relative**
- **Absolute**
- **Fixed**

Example:
```css
img {
  position: fixed;
  top: 0;
  right: 0;
}
```
This fixes an image at the top-right corner of the viewport.

Happy coding!
