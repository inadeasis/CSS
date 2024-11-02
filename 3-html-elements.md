Here are the key ways to apply CSS to HTML:

1. Inline styles
- Apply styles directly to an HTML element using the `style` attribute
- Example: `<p style="color: blue; font-size: 16px;">This is a paragraph.</p>`
- Best for one-off styles, but generally avoid as it mixes presentation with structure

2. Internal stylesheet
- Define styles in a `<style>` block within the `<head>` section of an HTML document  
- Applies styles to elements on that page
- Example:
```html
<head>
  <style>
    p {
      color: blue;
      font-size: 16px;  
    }
  </style>
</head>
<body>
  <p>This is a paragraph.</p>
</body>
```

3. External stylesheet
- Define styles in a separate .css file
- Link the stylesheet to the HTML document using a `<link>` tag in the `<head>`
- Most maintainable and reusable approach
- Separates presentation from structure  
- Example:
```html
<!-- HTML file -->  
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <p>This is a paragraph.</p>  
</body>
```
```css
/* styles.css file */
p {
  color: blue;
  font-size: 16px;
}
```

4. Using CSS selectors
- Target HTML elements to apply styles using CSS selectors
- Element selectors: Match elements by tag name, e.g. `p`, `div`, `a`
- Class selectors: Match elements with a specific class, denoted with a dot `.`, e.g. `.highlight` 
- ID selectors: Match a unique element with a specific ID, denoted with a hash `#`, e.g. `#header`
- Attribute selectors: Match elements based on attribute presence or value, e.g. `[type="text"]`
- Combinators: Combine selectors to target elements based on relationships, e.g. `div > p`, `a + span`
- Pseudo-classes: Target elements based on a certain state, denoted with a colon `:`, e.g. `a:hover`, `p:first-child`
- Pseudo-elements: Target a specific part of an element, denoted with double colon `::`, e.g. `p::first-letter`, `a::before`

The most common and recommended approach is to use an external stylesheet and link it to your HTML files. This keeps styles separate from markup, improves maintainability, and allows for reuse across multiple pages.
