## Assignment 5.3 — Typography Showcase Page

### 1. `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Typography Showcase</title>

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Roboto:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Typography Showcase</h1>

    <section>
        <h2>Heading Styles</h2>
        <h1>Main Heading</h1>
        <h2>Subheading</h2>
        <h3>Small Heading</h3>
    </section>

    <section>
        <h2>Paragraph Styles</h2>
        <p>Typography makes a webpage clear, attractive, and easy to read.</p>
        <p class="small">Good design improves the reading experience.</p>
    </section>

    <section>
        <h2>Text Emphasis</h2>
        <p><strong>Bold text</strong></p>
        <p><em>Italic text</em></p>
        <p><u>Underlined text</u></p>
    </section>
</body>
</html>
```

### 2. `style.css`

```css
body {
    font-family: 'Roboto', sans-serif;
    background-color: #f0f4f8;
    color: #333;
    line-height: 1.8;
    margin: 30px;
}

h1, h2, h3 {
    font-family: 'Poppins', sans-serif;
    color: navy;
}

h1 {
    font-size: 36px;
    font-weight: 700;
    text-align: center;
    letter-spacing: 2px;
}

h2 {
    font-size: 26px;
    text-decoration: underline;
}

h3 {
    font-size: 20px;
    font-weight: 600;
}

p {
    font-size: 18px;
}

.small {
    font-size: 14px;
    font-style: italic;
}
```

**Submission:** Save both files in the same folder and open `index.html` with Live Server. Google Fonts requires an internet connection.