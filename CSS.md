```css
/* Introduction to CSS (Cascading Style Sheets) */

/* CSS is used to style and layout web pages. */

/* 1. Basic Syntax */
selector {
    property: value;
}

/* Example: Changing the text color of all paragraphs */
p {
    color: blue;
}

/* 2. Selectors */
/* Selecting elements by tag */
h1 {
    font-size: 2em;
}

/* Selecting elements by class */
.example-class {
    background-color: lightgray;
}

/* Selecting elements by ID */
#example-id {
    border: 1px solid black;
}

/* 3. Fonts and Text */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* 4. Colors */
/* Named color */
header {
    background-color: lightblue;
}

/* Hexadecimal color */
footer {
    color: #333333;
}

/* RGB color */
nav {
    background-color: rgb(240, 240, 240);
}

/* 5. Box Model */
/* Understanding margin, border, padding, and content */
div {
    margin: 20px; /* Space outside the element */
    border: 2px solid red; /* Border around the element */
    padding: 10px; /* Space between content and border */
}

/* 6. Layouts */
/* Flexbox */
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Grid */
.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 10px;
}

/* 7. Transitions and Animations */
button {
    background-color: lightgreen;
    transition: background-color 0.3s;
}

button:hover {
    background-color: darkgreen;
    color: white;
}

/* Animation example */
@keyframes example-animation {
    from {
        transform: translateX(0);
    }
    to {
        transform: translateX(100px);
    }
}

.animated {
    animation: example-animation 2s infinite alternate;
}

/* 8. Responsive Design */
@media (max-width: 600px) {
    body {
        font-size: 14px;
    }
}

/* Keep practicing CSS to build visually appealing web pages! */

```css
