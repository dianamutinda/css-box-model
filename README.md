<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [CSS box model](#css-box-model)
  - [The box model has four components:](#the-box-model-has-four-components)
    - [Content box](#content-box)
    - [Padding box](#padding-box)
    - [Border box](#border-box)
    - [Margin box](#margin-box)
  - [Box model image](#box-model-image)
    - [box model sample code](#box-model-sample-code)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


# CSS box model
The CSS box model is essentially a box that wraps around every HTML element. It consists of: content, padding, borders and margins.  
  
## The box model has four components:
### Content box
- The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
### Padding box
- The padding sits around the content as white space; size it using padding and related properties.
### Border box
- The border box wraps the content and any padding; size it using border and related properties.
### Margin box
- The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.
## Box model image
![sample of a box model](./assets/box%20model%20sample.png)

### box model sample code
An example of a box model
```css
.box-model{
  width: 300px;
  border: 15px solid ;
  padding: 50px;
  margin: 20px;
}
```
