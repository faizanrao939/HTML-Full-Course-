 HTML Full Course — From Beginner to Advanced

 Learn HTML step by step with real examples and previewable code — perfect for web development beginners!


HTML (HyperText Markup Language) is the standard language for creating webpages.
It tells the browser what to display (text, images, links, buttons, etc.).

 Basic Structure of an HTML Page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Page</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is my first HTML page.</p>
</body>
</html>

 Explanation:


<!DOCTYPE html> → Declares HTML5 document


<html> → Root element


<head> → Page info (title, meta, links)


<body> → Visible content



 Headings and Paragraphs
<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<p>This is a simple paragraph.</p>


 Links and Images
<a href="https://www.google.com" target="_blank">Visit Google</a>

<img src="https://via.placeholder.com/150" alt="Sample Image">

 target="_blank" opens link in a new tab.

 Lists in HTML
<!-- Unordered List -->
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

<!-- Ordered List -->
<ol>
  <li>Introduction</li>
  <li>Basics</li>
  <li>Advanced</li>
</ol>


 Tables in HTML
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Faizan</td>
    <td>20</td>
  </tr>
</table>


 Forms in HTML
<form action="submit.php" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username"><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="useremail"><br><br>

  <input type="submit" value="Submit">
</form>


 Adding Style (Inline CSS)
<h1 style="color: blue; text-align: center;">Styled Heading</h1>
<p style="font-size: 18px; color: gray;">This paragraph is styled using inline CSS.</p>


 HTML Media (Video & Audio)
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support video tag.
</video>

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support audio element.
</audio>


 Semantic HTML Tags
These tags describe the meaning of content:
<header>Website Header</header>
<nav>Navigation Menu</nav>
<section>Main Section</section>
<article>Article Content</article>
<footer>Footer Section</footer>


 Meta Tags (for SEO & Info)
<meta charset="UTF-8">
<meta name="description" content="Free HTML course for beginners">
<meta name="keywords" content="HTML, CSS, Web Development">
<meta name="author" content="Rao Muhammad Faizan">


 HTML Entities
<p>Copyright &copy; 2025</p>
<p>2 &lt; 5 and 10 &gt; 2</p>


 HTML Comments
<!-- This is a comment -->
<p>This line is visible.</p>


 Embedding YouTube Videos
<iframe width="560" height="315" 
src="https://www.youtube.com/embed/tgbNymZ7vqY" 
frameborder="0" allowfullscreen></iframe>


 Best Practices
 Use proper indentation
 Close all tags properly
 Keep HTML semantic and clean
 Validate your code with W3 Validator

 Useful HTML Tools


 HTML Color Picker


 HTML Formatter


 W3Schools HTML Tutorial



 Project Example
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Portfolio</title>
  <style>
    body { font-family: Arial; margin: 0; padding: 0; text-align: center; }
    header { background: #4CAF50; color: white; padding: 20px; }
    section { padding: 20px; }
    footer { background: #333; color: white; padding: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>Rao Muhammad Faizan</h1>
    <p>Web Developer | Designer | Learner</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>I’m learning full-stack development and love creating modern websites.</p>
  </section>

  <footer>
    <p>&copy; 2025 My Portfolio</p>
  </footer>
</body>
</html





✨ Star this repo if you like this HTML Guide!

Would you like me to make a CSS course next (formatted the same way for your GitHub README)?
