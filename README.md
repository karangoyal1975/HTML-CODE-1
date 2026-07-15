
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio | Akshyat</title>
</head>
<body>
    <!--NAVIGATION-->
     <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
        <a href="#learning-journey">Learning Journey</a>
     </nav>  
      
     <!--HERO SEction-->
     <header>
        <h1>Hi, I'm Karan👋</h1>
        <p>I'm a passionate web developer with a love for creating beautiful and functional websites.</p>
        <a href="#contact">Get in Touch</a>
     </header>
    

     <!--ABOUT SECTION-->
     <section id="about">
        <h2>About Me</h2>
        <img src="blank_profile.png" alt="Karan's Profile Picture" width="200" height="200">
        <p>I am a web developer with experience in HTML, CSS, JavaScript, and various frameworks. I enjoy building responsive and user-friendly websites that provide great user experiences.</p>
     </section>

     <!--SKILLS SECTION-->
     <section id="skills">
        <h2>Skills</h2>
        <ol>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <li>React.js</li>
        </ol>
    </section>
    <!--LEARNING JOURNEY SECTION-->
    <section id="learning-journey">
     <h2>My Learning Journey</h2>

  <ol>
    <li>Learn HTML basics</li>
    <li>Learn to add images</li>
    <li>Learn to add links</li>
    <li>Learn to add contact information</li>
  </ol>
    </section>

    <!--PROJECTS SECTION-->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>Project 1: Portfolio Website</h3>
            <p>A personal portfolio website showcasing my skills and projects.</p>
            <a href="#" class="btn">View Project</a>
        </div>
    </section>
    
  <h3>Project 2: KA-chess-play</h3>
  <p>A chess app with options to play against an AI bot or in local PvP mode.</p>
  <p><a href="https://github.com/Akshyat-2007/Ak-chess-play" target="_blank">View Project</a></p>


  <h3>Project 3: Arogya AI Agent</h3>
  <p>An AI-powered agent project built to assist with health-related queries.</p>
  <p><a href="https://github.com/Akshyat-2007/Arogya-AI-Agent" target="_blank">View Project</a></p>

    <!--CONTACT SECTION-->
    <section id="contact">
    <h2>Contact Me</h2>
    <P>Have a project you'd like to collaborate on? Feel free to reach out!</P>
    <form action="#" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>

        <label for="subject">Subject:</label>
        <select id="subject" name="subject" required>
            <option value="">-- Select Subject --</option>
            <option value="general">I want to hire you</option>
            <option value="project">I want to collaborate on a project</option>
            <option value="other">Other</option>
        </select>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" placeholder="Describe your project or inquiry..." required></textarea>
        
        <button type="submit">Send Message🚀</button>
    <p>Email: <a href="mailto:karangoyal2007@outlook.com">karangoyal2007@outlook.com</a><br>
       GitHub: <a href="https://github.com/Karan-2007" target="_blank">Karan-2007</a><br>
       LinkedIn: <a href="https://www.linkedin.com/in/karan-goyal-573b35383/" target="_blank">Karan Goyal</a><br>
    </p>
    </section>
    
    <!--FOOTER SECTION-->
    <footer>
        <p>&copy; 2026 Karan. All rights reserved.</p>
    </footer>

</body>
</html>
