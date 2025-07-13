# HTML
<br>
🌐 HTML Basics Cheat Sheet
📘 Introduction to HTML
HTML (HyperText Markup Language) is the standard language used to create webpages. It structures content using elements (tags), which define the meaning and structure of the text.

HTML documents start with <!DOCTYPE html>

The root element is <html>, and it contains:

<head>: Metadata, title, links to CSS, etc.

<body>: Visible content of the webpage


<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>This is a basic HTML page.</p>
  </body>
</html>
🧭 Headings
HTML provides six levels of headings:


<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3>
...
<h6>Smallest heading</h6>
<h1> is the most important, and <h6> is the least.

Headings help with SEO and document structure.

📊 Tables
Tables are used to display data in rows and columns.


<table border="1">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>24</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>30</td>
    </tr>
  </tbody>
</table>
Key tags:

<table>: Wraps the whole table

<tr>: Table row

<th>: Table header

<td>: Table data cell

📋 Forms
HTML forms are used to collect user input.


<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <input type="submit" value="Submit">
</form>
Common input types:

text, email, password, radio, checkbox, submit

🧩 Semantic HTML
Semantic tags clearly describe their meaning in a human- and machine-readable way.


<header>Site Header</header>
<nav>Navigation Links</nav>
<main>Main Content</main>
<article>Blog Post</article>
<section>Section of Content</section>
<aside>Sidebar</aside>
<footer>Footer Content</footer>
Benefits:

Better SEO

Improved accessibility

Easier maintenance

🎥 Media in HTML
🔊 Audio

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
📺 Video

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
🖼️ Images

<img src="image.jpg" alt="Description of image" width="300">
