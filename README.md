<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Personal portfolio showcasing design, writing, and projects">
  <title>Your Name | Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <div class="intro">
      <h1>Hi, I'm [Your Name]</h1>
      <p>I'm a Designer, Writer, and Developer. I create beautiful designs and write compelling content.</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm [Your Name], a passionate designer and writer with experience in creating stunning visuals and engaging content. I specialize in [mention specific skills or tools you use].</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="project-card">
      <img src="project1.jpg" alt="Project 1">
      <h3>Project 1</h3>
      <p>A description of this project goes here.</p>
    </div>
    <div class="project-card">
      <img src="project2.jpg" alt="Project 2">
      <h3>Project 2</h3>
      <p>A description of this project goes here.</p>
    </div>
    <!-- Add more projects as needed -->
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form action="your-backend-script.php" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; [Your Name] - All Rights Reserved</p>
    <p>Connect with me: <a href="https://www.linkedin.com/in/yourprofile">LinkedIn</a> | <a href="https://github.com/yourprofile">GitHub</a></p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
