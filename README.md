# Ex01 Portfolio
## NAME: DHARSHINI R
## REG NO: 212224220023
## Date: 28/07/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dharshini R | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">Dharshini R</div>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">

        <div class="hero-content">

            <h1>Hello, I'm <span>Dharshini R</span></h1>

            <h2>Java Developer | Backend Enthusiast | AI Explorer</h2>

            <p>
                Passionate about building backend applications,
                solving programming challenges, and exploring
                Artificial Intelligence to create innovative solutions.
            </p>

            <a href="projects.html" class="btn">View My Projects</a>

        </div>

    </header>

    <!-- About -->
    <section id="about">

        <h2>About Me</h2>

        <p>
            I am a B.Tech Information Technology student with a
            strong interest in Java programming, backend development,
            and Artificial Intelligence. I enjoy learning new
            technologies and building practical software projects
            that improve everyday life.
        </p>

    </section>

    <!-- Skills -->
    <section id="skills">

        <h2>My Skills</h2>

        <div class="cards">

            <div class="card">
                <h3>☕ Java</h3>
                <p>Object-Oriented Programming & Core Java</p>
            </div>

            <div class="card">
                <h3>⚙ Backend</h3>
                <p>Spring Boot, REST APIs & MySQL</p>
            </div>

            <div class="card">
                <h3>🤖 Artificial Intelligence</h3>
                <p>Prompt Engineering & AI Applications</p>
            </div>

            <div class="card">
                <h3>💻 Web Development</h3>
                <p>HTML, CSS & JavaScript</p>
            </div>

        </div>

    </section>

    <!-- Education -->
    <section>

        <h2>Education</h2>

        <div class="card education">

            <h3>B.Tech Information Technology</h3>

            <p>Saveetha Engineering College</p>

            <p>Currently Pursuing</p>

        </div>

    </section>

    <!-- Contact -->
    <section id="contact">

        <h2>Contact Me</h2>

        <div class="contact-box">

            <p><strong>Email:</strong> yourmail@example.com</p>

            <p><strong>GitHub:</strong> github.com/yourusername</p>

            <p><strong>LinkedIn:</strong> linkedin.com/in/yourprofile</p>

            <p><strong>Location:</strong> Chennai, India</p>

        </div>

    </section>

    <!-- Footer -->
    <footer>

        <p>© 2026 Dharshini R | Portfolio</p>

    </footer>

</body>
</html>
```
aboutme.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Dharshini R</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">Dharshini R</div>

        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="index.html#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- About Header -->
    <header class="hero small">
        <div class="hero-content">
            <h1>About Me</h1>
            <p>Get to know more about me and my interests.</p>
        </div>
    </header>

    <!-- About Content -->
    <section class="about-section">

        <div class="card">

            <h2>Who Am I?</h2>

            <p>
                Hello! I'm <strong>Dharshini R</strong>, a B.Tech Information
                Technology student with a passion for technology and continuous
                learning.
            </p>

            <p>
                My primary interest lies in <strong>Java Development</strong>,
                where I enjoy writing clean, efficient, and scalable code.
                I also have a strong interest in
                <strong>Backend Development</strong>, creating APIs,
                managing databases, and understanding how applications work
                behind the scenes.
            </p>

            <p>
                Along with backend development, I enjoy exploring
                <strong>Artificial Intelligence</strong> and learning how AI
                can be used to solve real-world problems.
            </p>

            <p>
                My goal is to become a skilled software developer by
                continuously improving my programming, problem-solving,
                and software design skills.
            </p>

        </div>

    </section>

    <!-- Strengths -->
    <section>

        <h2>My Strengths</h2>

        <div class="cards">

            <div class="card">
                <h3>☕ Java Programming</h3>
                <p>Strong understanding of Core Java and Object-Oriented Programming.</p>
            </div>

            <div class="card">
                <h3>⚙ Backend Development</h3>
                <p>Interested in Spring Boot, REST APIs, and MySQL.</p>
            </div>

            <div class="card">
                <h3>🤖 Artificial Intelligence</h3>
                <p>Exploring AI tools and intelligent software solutions.</p>
            </div>

        </div>

    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Dharshini R | Portfolio</p>
    </footer>

</body>
</html>
```
project.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Projects</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<nav>

<h2>Dharsh</h2>

<ul>
<li><a href="index.html">Home</a></li>
<li><a href="projects.html">Projects</a></li>
</ul>

</nav>

<header class="hero small">

<h1>My Projects</h1>

<p>Some projects I've worked on.</p>

</header>

<section>

<div class="cards">

<div class="card">

<h3>Student Management System</h3>

<p>
Java + MySQL application to manage student records.
</p>

</div>

<div class="card">

<h3>Portfolio Website</h3>

<p>
Responsive portfolio created using HTML and CSS.
</p>

</div>

<div class="card">

<h3>AI Finance Tracker</h3>

<p>
Expense tracker with AI-based predictions.
</p>

</div>

</div>

</section>

<footer>

<p>© 2026 Dharsh | Portfolio</p>

</footer>

</body>
</html>
```
contacts.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact | Dharshini R</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">Dharshini R</div>

        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <!-- Header -->
    <header class="hero small">
        <div class="hero-content">
            <h1>Contact Me</h1>
            <p>Feel free to reach out. I'd love to connect!</p>
        </div>
    </header>

    <!-- Contact Information -->
    <section>

        <h2>Get In Touch</h2>

        <div class="cards">

            <div class="card">
                <h3>📧 Email</h3>
                <p>dharshinirsvd2007@gmail.com</p>
            </div>

            <div class="card">
                <h3>📱 Phone</h3>
                <p>+91 8220877899</p>
            </div>

            <div class="card">
                <h3>💻 GitHub</h3>
                <p>github.com/yourusername</p>
            </div>

            <div class="card">
                <h3>💼 LinkedIn</h3>
                <p>linkedin.com/in/yourprofile</p>
            </div>

            <div class="card">
                <h3>📍 Location</h3>
                <p>Chennai, Tamil Nadu, India</p>
            </div>

        </div>

    </section>

    <!-- Contact Form -->
    <section>

        <h2>Send a Message</h2>

        <form class="contact-form">

            <input type="text" placeholder="Your Name" required>

            <input type="email" placeholder="Your Email" required>

            <textarea rows="6" placeholder="Your Message" required></textarea>

            <button type="submit" class="btn">Send Message</button>

        </form>

    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Dharshini R | Portfolio</p>
    </footer>

</body>
</html>
```
## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/7668ac08-36dd-46a6-bcd4-99e1ac3de629" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c84de61c-32c0-4d94-a882-6cb53ef1e94f" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d8a52d85-d41b-4926-80ad-f8b66da53aaf" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4cf8b0de-7a2e-40ca-8022-0c5ea665f153" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
