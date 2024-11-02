1. Basic Syntax:
```css
selector {
    property: value;
}
```

2. Common ways to add CSS:
```html
<!-- External CSS -->
<link rel="stylesheet" href="styles.css">

<!-- Internal CSS -->
<style>
    p { color: blue; }
</style>

<!-- Inline CSS -->
<p style="color: blue;">Text</p>
```

3. Essential properties:
```css
/* Colors */
color: blue;
background-color: #FF0000;

/* Text */
font-size: 16px;
font-family: Arial, sans-serif;
font-weight: bold;

/* Layout */
margin: 10px;
padding: 15px;
width: 200px;
height: 100px;

/* Display */
display: block;
position: relative;
```

4. Selectors:
```css
/* Element selector */
p { color: blue; }

/* Class selector */
.highlight { background-color: yellow; }

/* ID selector */
#header { font-size: 24px; }

/* Descendant selector */
div p { margin: 10px; }
```
