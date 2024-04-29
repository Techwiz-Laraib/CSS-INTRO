
# CSS INTRO




## 1. Selectors :
  
CSS works by selecting HTML elements on a webpage and applying styles to them. Selectors are patterns that identify which elements the styles should be applied to. For example, you can select all <p> elements (paragraphs) or only specific elements with a certain class or ID.


### Example

Paragraph Styling

```bash
  /* Selecting all paragraph elements */
p {
    color: blue;
}

/* Selecting elements with class "highlight" */
.highlight {
    background-color: yellow;
}

/* Selecting an element with ID "header" */
#header {
    font-size: 24px;
}

```
 
 ## 2. Properties And Values :

CSS properties define what aspects of the selected elements you want to style, and values specify how you want to style them. For example, you can set the color, font size, background color, margins, padding, etc.

```bash 
/* Setting color property to blue */
p {
    color: blue;
}

/* Setting background-color property to yellow */
.highlight {
    background-color: yellow;
}

/* Setting font-size property to 24 pixels */
#header {
    font-size: 24px;
}
```

## 3. Cascade And Specificity : 

 CSS is called "Cascading" because styles can cascade from one rule to another. If multiple rules target the same element, the browser determines which styles to apply based on specificity and the order of rules.

 ## 4. External, Internal, and Inline CSS :

 #### CSS can be applied to HTML documents in three ways:
  
  
 


- External CSS: 
The styles are stored in a separate file and linked to the HTML document using the <link> element.
- Internal CSS: 
The styles are defined within the HTML document using the <style> element in the <head> section.
- Inline CSS: 
Styles are applied directly to individual HTML elements using the style attribute.

```bash <!-- External CSS -->
<link rel="stylesheet" type="text/css" href="styles.css">

<!-- Internal CSS -->
<style>
    p {
        color: blue;
    }
</style>

<!-- Inline CSS -->
<p style="color: blue;">This is a blue paragraph.</p>
```
## 5. Box Model:

In CSS, every HTML element is considered a box, and the box model describes how these boxes are laid out on the webpage. Each box consists of content, padding, border, and margin.


 





![Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model/box-model.png)

- Content: The actual content of the element, such as text or images.
- Padding: Space between the content and the border.
- Border: A border surrounding the padding.
- Margin: Space outside the border, separating the element from other elements.
You can control the size and spacing of these elements using CSS properties like width , height , padding , margin, etc.