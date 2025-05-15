<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My portfolio</title>
  <link rel="stylesheet" href="port.css"/>
</head>
<body>
  <header>
    <nav>
      <h1>My portfolio</h1>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <div class="hero-content">
      <h2>Hello, I'm <span class="highlight">JOSH.</span></h2>
      <h3><P>A passionate web developer.</P></h3>
      <br>
      <a href="#projects" class="btn">See my work</a>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About me</h2>
    <p>I am a passionate web developer with experience in HTML and CSS a little of JS. I love creating beautiful and functional web applications.</p>
  </section>

  <section id="Projects" class="Projects">
    <h2>my Projects</h2>
    <div class="project-grid">
      <a href="http://127.0.0.1:5501/josh.html" target="_blank" class="project-site">
        <h3>Project one</h3>
        <p>This responsive company website was built using HTML,CSS, and JS.</p>
      </a>

      <a href="http://127.0.0.1:5502/BIGJOSH%20TUTORIAL/BIGJOSH%20TUTORIAL/josh.html" target="_blank" class="project-site">
        <h3>Project two</h3>
        <p>This mini saloon website was also built using HTML,CSS and a little of JS.</p>
      </a>
    </div>
  </section>

  <section id="contact" class="Contact">
    <h2>contact</h2>
    <p>if you have any questions or would like to work and make partnership with me, feel free to contact me.</p>
    <a href="mailto:kutijoshua76@gmail.com" class="btn">Email me</a>
  </section>

  <footer>
    <p>&copy; 2025 Bigjosh. All rights Reserved.</p>
  </footer>
  <script src="port.js"></script>
</body>
</html>
