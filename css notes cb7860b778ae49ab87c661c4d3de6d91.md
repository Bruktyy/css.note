# css notes

# CSS

CSS (Cascading Style Sheets) is a language used to describe the presentation of HTML documents. It works in conjunction with HTML to provide the visual styling of web pages. CSS rules consist of a selector and a declaration block, which contains one or more declarations. Declarations consist of a property and a value. There are many CSS can be used to create responsive layouts, animations, and effects.

CSS tags:

1. `color`: Sets the color of text.
2. `font-family`: Sets the font family of text.
3. `font-size`: Sets the font size of text.
4. `background-color`: Sets the background color of an element.
5. `border`: Sets the border of an element.
6. `padding`: Sets the padding of an element.
7. `margin`: Sets the margin of an element.
8. `text-align`: Sets the horizontal alignment of text.
9. `display`: Sets how an element is displayed.
10. `position`: Sets the position of an element.e's an example of how to use the `col` class to create a responsive grid:

***CSS - Selectors**
Selectors can be • A tag name (i.e.
) —This will apply to all tags of that type in the document • An id (
**) —The style will apply to ANY tag with the named id.

• A class (
) The style will apply to ANY element with the named class)
CSS – Examples: Selectors**

**CSS - Borders**
CSS allows specification of the style, width and color of element borders • Attributes: • **border-style** : style keyword — includes dotted, dashed, solid, double, groove, ridge, inset, outset, none, hidden}

`• **border-width** : Value can be specified in pt, px, cm, em ; Value can use one of 3 keywords: thin, medium, thick`

In conclusion, HTML and CSS are essential web development technologies that work together to create visually appealing and interactive web pages. Developers use these technologies to create responsive and optimized web pages that provide an excellent user experience.
**Summary**
**HTML** — Hyper Text Markup Language used to describe most web page content Static — no 'execution' semantics. **CSS** — Cascading Style Sheets; Help customize look and feel of web pages; Numerous ways to address elements and groups of elements; Varied properties to produce rich styling.*

![https://github.com/EyoelGirma/web-class/raw/main/HTML%20and%20CSS/HTML%20and%20CSS%20b2d52bbdbcac4726b5042b204f17f0a2/Screenshot_2023-05-19_225256.png](https://github.com/EyoelGirma/web-class/raw/main/HTML%20and%20CSS/HTML%20and%20CSS%20b2d52bbdbcac4726b5042b204f17f0a2/Screenshot_2023-05-19_225256.png)

# CSS Margins

The CSS `margin` properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).

---

# Margin - Individual Sides

CSS has properties for specifying the margin for each side of an element:

- `margin-top`
- `margin-right`
- `margin-bottom`
- `margin-left`

All the margin properties can have the following values:

- auto - the browser calculates the margin
- *length* - specifies a margin in px, pt, cm, etc.
- *%* - specifies a margin in % of the width of the containing element
- inherit - specifies that the margin should be inherited from the parent element

**Tip:** Negative values are allowed.

# Example

Set different margins for all four sides of a <p> element:

```jsx
p {  margin-top: 100px;  margin-bottom: 100px;  margin-right: 150px;  margin-left: 80px;}
```