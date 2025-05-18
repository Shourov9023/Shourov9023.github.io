<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Al-Amin Wazed Shourov | Portfolio</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav id="navbar">
        <div class="container">
            <h1 class="logo">Shourov</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Hi, I'm <span>Al-Amin Wazed Shourov</span></h1>
                <p>Web Developer | Programmer | Tech Enthusiast</p>
                <a href="#contact" class="btn">Get in Touch</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <img src="img/profile.jpg" alt="Al-Amin Wazed Shourov">
                <div class="bio">
                    <h3>Who Am I?</h3>
                    <p>
                        I'm a passionate developer with expertise in web development, programming, and problem-solving. 
                        I love building projects that make an impact. Currently, I'm focused on improving my skills in 
                        JavaScript, React, and backend technologies.
                    </p>
                    <a href="files/resume.pdf" class="btn" download>Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <img src="img/project1.jpg" alt="Project 1">
                    <h3>E-Commerce Website</h3>
                    <p>A full-stack e-commerce platform built with React and Node.js.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <img src="img/project2.jpg" alt="Project 2">
                    <h3>Portfolio Website</h3>
                    <p>A responsive portfolio website using HTML, CSS, and JavaScript.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <img src="img/project3.jpg" alt="Project 3">
                    <h3>Task Manager App</h3>
                    <p>A task management application with Firebase backend.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2>My Skills</h2>
            <div class="skills-list">
                <div class="skill">
                    <i class="fab fa-html5"></i>
                    <span>HTML5</span>
                </div>
                <div class="skill">
                    <i class="fab fa-css3-alt"></i>
                    <span>CSS3</span>
                </div>
                <div class="skill">
                    <i class="fab fa-js"></i>
                    <span>JavaScript</span>
                </div>
                <div class="skill">
                    <i class="fab fa-react"></i>
                    <span>React</span>
                </div>
                <div class="skill">
                    <i class="fab fa-node-js"></i>
                    <span>Node.js</span>
                </div>
                <div class="skill">
                    <i class="fas fa-database"></i>
                    <span>MongoDB</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Get In Touch</h2>
            <div class="contact-form">
                <form action="#" method="POST">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <textarea name="message" placeholder="Your Message" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
                <div class="social-links">
                    <a href="https://github.com/Shourov9023" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://linkedin.com/in/yourusername" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="mailto:shourov9023@gmail.com"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Al-Amin Wazed Shourov. All Rights Reserved.</p>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
