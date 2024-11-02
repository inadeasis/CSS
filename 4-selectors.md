CSS selectors are patterns used to select and style specific HTML elements on a web page. They are a fundamental part of CSS (Cascading Style Sheets) and allow developers to apply styles, layout, and formatting to the selected elements. Here are some commonly used CSS selectors:

1. Element Selector:
   - Syntax: `elementName`
   - Example: `p` selects all `<p>` elements

2. Class Selector:
   - Syntax: `.className`
   - Example: `.highlight` selects all elements with the class "highlight"

3. ID Selector:
   - Syntax: `#idName`
   - Example: `#header` selects the element with the ID "header"

4. Attribute Selector:
   - Syntax: `[attribute]`, `[attribute="value"]`, `[attribute~="value"]`, `[attribute|="value"]`, `[attribute^="value"]`, `[attribute$="value"]`, `[attribute*="value"]`
   - Example: `[type="text"]` selects all elements with the attribute "type" set to "text"

5. Descendant Selector:
   - Syntax: `selector1 selector2`
   - Example: `div p` selects all `<p>` elements that are descendants of `<div>` elements

6. Child Selector:
   - Syntax: `selector1 > selector2`
   - Example: `ul > li` selects all `<li>` elements that are direct children of `<ul>` elements

7. Adjacent Sibling Selector:
   - Syntax: `selector1 + selector2`
   - Example: `h1 + p` selects the first `<p>` element that comes immediately after an `<h1>` element

8. General Sibling Selector:
   - Syntax: `selector1 ~ selector2`
   - Example: `h1 ~ p` selects all `<p>` elements that are siblings of `<h1>` elements

9. Pseudo-class Selectors:
   - Syntax: `selector:pseudo-class`
   - Example: `a:hover` selects `<a>` elements when the mouse pointer is over them

10. Pseudo-element Selectors:
    - Syntax: `selector::pseudo-element`
    - Example: `p::first-letter` selects the first letter of all `<p>` elements
