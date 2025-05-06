<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <nav>
      <h1>Asif</h1>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <h2>Hello, I'm Mohammed Asif</h2>
    <p>Aspiring Full Stack Developer</p>
    <button onclick="scrollToSection('projects')">View My Work</button>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate developer skilled in HTML, CSS, JavaScript, Node.js, and MySQL. I love building beautiful, responsive websites and web apps.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1: Portfolio Website</h3>
      <p>This is a responsive personal portfolio website built using HTML, CSS, and JavaScript.</p>
    </div>
    <div class="project">
      <h3>Project 2: Weather App</h3>
      <p>Used a weather API to display real-time weather info using JavaScript.</p>
    </div>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <a href=""C:\Users\91810\Downloads\Shaik_Asif.pdf"" download>Download Resume</a>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Mohammed Asif. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
