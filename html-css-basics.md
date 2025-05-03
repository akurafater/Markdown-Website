
- **[Back](index.md)**

# HTML & CSS Basics

**HTML** (HyperText Markup Language) and **CSS** (Cascading Style Sheets) are the foundational technologies for building web pages. HTML structures the content, while CSS controls its appearance. Together, they enable developers to create visually appealing and well-structured websites.

---

## What is HTML?

**HTML** is the standard language used to create and organize content on the web.

### Key Uses:
- Define page structure using elements like `<header>`, `<main>`, and `<footer>`.
- Embed media such as images, videos, and audio.
- Add interactive elements like forms and buttons.
- Use semantic tags to improve accessibility and SEO.

---

## What is CSS?

**CSS** is used to style and layout HTML elements.

### Key Uses:
- Set colors, fonts, margins, and spacing.
- Position elements using layout models like Flexbox and Grid.
- Create responsive designs for different screen sizes.
- Add animations and transitions for visual effects.

---

## Key Benefits of HTML & CSS

- **Separation of Concerns:** Structure (HTML) is kept separate from presentation (CSS).
- **Accessibility:** Semantic HTML improves screen reader and keyboard support.
- **Custom Design:** CSS allows complete control over how elements look and behave.
- **Responsive Layouts:** Adapt content for phones, tablets, and desktops.
- **Browser Support:** Universally supported across all modern web browsers.

---

## Getting Started

To begin building web pages with HTML and CSS, follow these steps:

### 1. Set Up Your Project Folder

Create a folder on your computer to store your HTML and CSS files. For example:

```
my-website/
├── index.html
└── styles.css
```

### 2. Create the HTML File

Create a file named `index.html`. This will be your main HTML file, where you structure your content.

Basic template:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is my first web page.</p>
  </body>
</html>
```

### 3. Create the CSS File

In the same folder, create a file named `styles.css`. This file contains all your visual styles.

Basic example:
```css
/* General page styles */
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
  color: #333;
  padding: 20px;
}

/* Heading styles */
h1 {
  color: #007acc;
  font-size: 2.5em;
}

/* Paragraph styles */
p {
  font-size: 1.1em;
  line-height: 1.6;
}
```

### 4. Link CSS to HTML

Inside the `<head>` tag of your HTML, include the `<link>` tag to connect your CSS file:

```html
<link rel="stylesheet" href="styles.css">
```

This tells the browser to apply the styles in `styles.css` to the HTML content.

### 5. Open in Browser

To view your website:
- Double-click the `index.html` file.
- Or, right-click it and choose “Open with” → your preferred web browser.

You'll see your styled web page.

---

### Optional Tools for Beginners

- **Text Editors:** Use editors like VS Code, Sublime Text, or Notepad++ for writing code.
- **Live Preview:** Use VS Code extensions like “Live Server” to see changes instantly.
- **Browser DevTools:** Press F12 in your browser to inspect HTML/CSS and debug styling issues.

---
