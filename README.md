# HTML
<br>
Basic HTML Interview Questions
What is HTML?

HTML (HyperText Markup Language) is the standard language for creating web pages and web applications.

What are tags in HTML?

Tags are the building blocks of HTML used to mark up content. Example: <p>, <a>, <div>.

What is the difference between HTML and HTML5?

HTML5 supports multimedia elements (<audio>, <video>), new semantic tags (<article>, <section>), and is more mobile-friendly.

What is the structure of a basic HTML document?

html
Copy
Edit
<!DOCTYPE html>
<html>
  <head>
    <title>Title</title>
  </head>
  <body>
    Content goes here.
  </body>
</html>
What is the purpose of the <!DOCTYPE html> declaration?

It defines the HTML version and ensures the browser renders the page correctly.

What is the difference between <div> and <span>?

<div> is a block-level element; <span> is an inline element.

What are void elements in HTML?

Elements that do not have a closing tag. Example: <br>, <img>, <input>

📋 Intermediate HTML Interview Questions
What is the difference between id and class attributes?

id is unique for an element; class can be shared among multiple elements.

What are semantic tags in HTML5?

Tags that convey the meaning of the content, e.g., <header>, <footer>, <article>, <main>

What is the use of the <meta> tag?

Provides metadata like character set, author, viewport settings for responsive design.

How does the <form> element work in HTML?

It collects user input and sends it to a server using action and method attributes.

How can you embed an image in a webpage?

html
Copy
Edit
<img src="image.jpg" alt="Description" width="200" height="100">
What is the use of the alt attribute in <img>?

It provides alternative text if the image fails to load and is important for accessibility.

Difference between <script> and <noscript> tags?

<script> runs JavaScript; <noscript> is shown if JS is disabled.

What is the purpose of the target="_blank" attribute in <a> tag?

Opens the linked document in a new tab.

💡 Advanced HTML Interview Questions
How do you make a website mobile-responsive in HTML?

Using <meta name="viewport" content="width=device-width, initial-scale=1.0">

What are custom data attributes in HTML5?

Attributes starting with data-, e.g., data-user-id="123", used to store extra data.

What is the difference between <section> and <article>?

<article> is self-contained content (like a blog post), while <section> groups related content.

How do you embed audio and video in HTML?

html
Copy
Edit
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
</audio>

<video controls width="300">
  <source src="movie.mp4" type="video/mp4">
</video>
Can you explain the difference between localStorage, sessionStorage, and cookies in the context of HTML5?

localStorage: Stores data with no expiration.

sessionStorage: Clears data when the page session ends.

Cookies: Stored on the server/client with expiry and sent with each request.
