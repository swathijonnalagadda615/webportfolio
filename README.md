#webportfolio
1.HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jonnalagadda Swathi | AI & Software Developer</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
  <h2>Swathi</h2>
  <div>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<header class="hero">
  <h1>HELLO, I'M</h1>
  <h2>Jonnalagadda Swathi</h2>
  <p>ECE Student | AI & Software Developer</p>
  <button onclick="scrollToSection()">Explore My Work</button>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>Motivated Electronics and Communication Engineering student passionate about AI, Computer Vision, Embedded Systems, IoT and Python.</p>
</section>

<section id="skills">
  <h2>Technical Toolkit</h2>
  <ul>
    <li>Python</li>
    <li>C Programming</li>
    <li>OpenCV</li>
    <li>Machine Learning</li>
    <li>Embedded Systems</li>
    <li>IoT</li>
    <li>Git & GitHub</li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>
  <h3>Smart Pill Box</h3>
  <p>IoT-based medication reminder system.</p>

  <h3>Facial Detection System</h3>
  <p>Real-time face detection using Python and OpenCV.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: jonnalagaddaswathi149@gmail.com</p>
  <p>Phone: +91 9063232924</p>
  <p>Location: Guntur, Andhra Pradesh</p>
</section>

<script src="script.js"></script>
</body>
</html>

2.style.css

body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#08111f;
  color:white;
}
nav{
  display:flex;
  justify-content:space-between;
  padding:15px 30px;
  background:#0b1628;
}
nav a{
  color:#00d4ff;
  margin-left:15px;
  text-decoration:none;
}
.hero{
  text-align:center;
  padding:100px 20px;
}
button{
  background:#00d4ff;
  color:#000;
  border:none;
  padding:12px 20px;
  border-radius:20px;
}
section{
  padding:40px 20px;
}
 
3.script.js

function scrollToSection() {
  document.getElementById("about").scrollIntoView({
    behavior: "smooth"
  });
}