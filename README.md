HTML Full Course — Beginner to Advanced

Welcome to the Complete HTML Course!
This guide will take you from the basics to advanced concepts with simple explanations and working code examples.

 1. What is HTML?

HTML (HyperText Markup Language) is the standard language used to create and structure web pages.
It uses tags to define elements like text, images, links, and forms.

 2. Basic HTML Structure
<!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first HTML page.</p>
  </body>
</html>

Explanation:

<!DOCTYPE html> → Defines the document type

<html> → Root element

<head> → Contains metadata (title, CSS links, etc.)

<body> → Contains visible content

 3. Common HTML Tags
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<p>This is a paragraph.</p>
<b>Bold Text</b>
<i>Italic Text</i>
<u>Underlined Text</u>
 4. Links and Images
<a href="https://github.com/">Visit GitHub</a>

<img src="https://via.placeholder.com/150" alt="Sample Image">

<a> → Creates a hyperlink

<img> → Displays an image

 5. Lists
<h3>Ordered List</h3>
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>

<h3>Unordered List</h3>
<ul>
  <li>Frontend</li>
  <li>Backend</li>
  <li>Database</li>
</ul>
 6. Tables
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Ali</td>
    <td>20</td>
  </tr>
</table>
 7. Forms
<form>
  <label>Name:</label>
  <input type="text" name="username"><br><br>

  <label>Email:</label>
  <input type="email" name="email"><br><br>

  <label>Password:</label>
  <input type="password" name="password"><br><br>

  <input type="submit" value="Submit">
</form>
 8. Multimedia
<video width="320" height="240" controls>
  <source src="sample.mp4" type="video/mp4">
</video>

<audio controls>
  <source src="sample.mp3" type="audio/mp3">
</audio>
 9. Semantic Tags (HTML5)
<header>Header Content</header>
<nav>Navigation Links</nav>
<section>Main Section</section>
<article>Article Content</article>
<footer>Footer Content</footer>
 10. Inline CSS in HTML
<p style="color: blue; font-size: 20px;">This is styled text!</p>
 11. HTML Comments
<!-- This is a comment -->

Comments are ignored by the browser.

 12. Embedding YouTube Video
<iframe width="560" height="315"
src="https://www.youtube.com/embed/dD2EISBDjWM"
title="YouTube video player" frameborder="0" allowfullscreen>
</iframe>
 13. HTML Entities
<p>&copy; 2025 MyWebsite</p>
<p>Use &lt;html&gt; tag for structure</p>
 14. HTML Form Validation (Basic)
<form>
  <input type="email" required>
  <input type="password" minlength="6" required>
  <input type="submit">
</form>
 15. Meta Tags
<head>
  <meta charset="UTF-8">
  <meta name="description" content="HTML Full Course">
  <meta name="keywords" content="HTML, Web, Tutorial">
  <meta name="author" content="Your Name">
</head>
 16. Full Example (Mini Webpage)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
    <nav>
      <a href="#about">About</a> |
      <a href="#projects">Projects</a> |
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a web developer learning HTML, CSS, and JavaScript.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Responsive Website</li>
      <li>Login Form</li>
      <li>Portfolio Page</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 My Portfolio</p>
  </footer>
</body>
</html>
 Summary
Topic	Description
Structure	<!DOCTYPE html>, <html>, <head>, <body>
Formatting	Headings, paragraphs, text styles
Links & Media	<a>, <img>, <video>, <audio>
Lists & Tables	<ul>, <ol>, <table>
Forms	<form>, <input>, <label>
Semantic	<header>, <footer>, <section>, <article>
Comments	<!-- comment -->
Entities	&lt;, &copy;
 

Created by: Faizan rao
Date: 11-42025
License: Free to use and share

 If you found this helpful, give it a star on GitHub!
