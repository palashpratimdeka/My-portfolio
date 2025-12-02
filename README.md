<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style2.css" />
</head>
<body>

    <header>
        <nav class="navbar">
            <h2 class="logo">MyPortfolio</h2>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-text">
            <h1>Hello, I'm <span>Palash</span></h1>
            <p>A passionate JavaScript Developer & Engineering Student</p>
            <button onclick="window.location='#projects'" class="btn">Explore My Work</button>
        </div>
        <img src="scenary3.jpg" class="hero-img" alt="Profile" />
    </section>

    <section id="skills" class="skills-section">
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill-card">HTML</div>
            <div class="skill-card">CSS</div>
            <div class="skill-card">JavaScript</div>
            <div class="skill-card">Git & GitHub</div>
        </div>
    </section>

    <section id="projects" class="project-section">
        <h2>Projects</h2>
        <div class="project-grid">

            <div class="project-card">
                <img src="assets/project1.jpg" alt="Project 1" />
                <h3>Weather App</h3>
                <p>JavaScript </p>
            </div>

            <div class="project-card">
                <img src="assets/project2.png" alt="Project 2" />
                <h3>To-Do App</h3>
                <p> Functional task manager </p>
            </div>

        </div>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Me</h2>
        <p>Email: dekapalashpratim@gmail.com</p>
    </section>

    <footer>
        <p>© 2025 My Portfolio. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
