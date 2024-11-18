[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Innovations Showcase</title>

</head>
<body>
    <header>
        <h1>Tech Innovations Showcase</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#technologies">Technologies</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Our Tech Journey</h2>
            <article>
                <p>We are passionate about exploring cutting-edge technologies that shape our digital future. Our mission is to highlight innovative solutions that transform how we live and work.</p>
                <img src="/api/placeholder/400/250" alt="Tech Innovation Lab" style="max-width: 100%;">
            </article>
        </section>

        <section id="technologies">
            <h2>Key Technologies We Explore</h2>
            <ul>
                <li>Artificial Intelligence</li>
                <li>Machine Learning</li>
                <li>Blockchain</li>
                <li>Internet of Things (IoT)</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Connect With Us</h2>
            <p>Interested in learning more? Check out our resources:</p>
            <ol>
                <li><a href="https://example.com/blog" target="_blank">Tech Blog</a></li>
                <li><a href="https://example.com/newsletter" target="_blank">Monthly Newsletter</a></li>
            </ol>
        </section>
    </main>

    <footer>
        <p>© 2024 Tech Innovations Showcase. All rights reserved.</p>
    </footer>
</body>
</html>

