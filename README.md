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

### Answers start here(code)

# Index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My week 3 styled page</title>
    
    <link rel="stylesheet" href="style.css"> <!-- Link to my external css file-->
</head>
<body>
    <header id="main-header">
        <h1>Welcome to Rego's computer software solutions</h1>
    </header>
    
	<section class="intro-section">
        <p>This is an introduction to CSS styling.</p>
    </section>
	
    <nav class="main-nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section class="content-section">
            <h2>About Us</h2>
            <p>We are a creative team dedicated to web design and development.</p>
            <img src="https://via.placeholder.com/400" alt="Sample image" class="featured-image">
        </section>
        
        <section class="content-section highlight">
            <h2>Our Services</h2>
            <p>We offer:</p>
            <ul>
                <li>Web Design</li>
                <li>Front-end Development</li>
                <li>UX Consulting</li>
            </ul>
        </section>
    </main>
	
	
    <footer>
        <p>&copy; 2023 My Website. All rights reserved.</p>
    </footer>
</body>
</html>


### style.css


p {
    line-height: 1.6;
    color: #333;
}


.content-section {
    padding: 20px;
    margin-bottom: 30px;
    border-radius: 5px;
    background-color: #f9f9f9;
}


#main-header {
    text-align: center;
    color: #2c3e50;
    padding: 20px 0;
    border-bottom: 3px solid #3498db;
}


.main-nav {
    background-color: #2c3e50;
    padding: 10px 0;
}

.main-nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

.main-nav a {
    color: white;
    text-decoration: none;
    font-family: 'Arial', sans-serif;
    font-weight: bold;
}


.featured-image {
    border: 5px solid #3498db;
    border-radius: 8px;
    margin: 20px auto;
    display: block;
    max-width: 100%;
    height: auto;
}


.highlight {
    background-color: #e8f4fc;
    border-left: 5px solid #3498db;
}


footer {
    text-align: center;
    padding: 15px;
    background-color: #2c3e50;
    color: white;
    font-family: 'Verdana', sans-serif;
}


body {
    font-family: 'Georgia', serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

h1, h2 {
    font-family: 'Helvetica', sans-serif;
}


.content-section {
    margin: 20px;
    padding: 25px;
    border: 1px solid #ddd;
}





