# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="header">
        <h1>Welcome to My Styled Page</h1>
        <p class="subtitle">A demonstration of CSS styling.</p>
    </div>

    <div class="content">
        <p>This is some example text within the content area. We can style this text and other elements using CSS.</p>
        <img src="https://via.placeholder.com/200" alt="Placeholder Image" class="styled-image">
        <p>More text to illustrate the effects of margin, padding, and borders.</p>
        <div class="bordered-box">
            This is a bordered box.
        </div>
    </div>

    <div id="footer">
        <p>&copy; 2024 My Styled Page</p>
    </div>
</body>
</html>



/* style.css */

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

#header {
    background-color: #3498db;
    color: white;
    text-align: center;
    padding: 20px 0;
}

#header h1 {
    margin-bottom: 10px;
}

.subtitle {
    font-style: italic;
    color: #ecf0f1;
}

.content {
    width: 80%;
    margin: 20px auto;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.styled-image {
    display: block;
    margin: 20px auto;
    border-radius: 50%;
    border: 4px solid #3498db;
    padding: 5px;
}

.bordered-box {
    border: 2px solid #e74c3c;
    padding: 15px;
    margin-top: 20px;
    border-radius: 5px;
    background-color: #fde0d9;
    color: #e74c3c;
    font-weight: bold;
}

#footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: sticky;
    bottom: 0px;
    width: 100%;
}
