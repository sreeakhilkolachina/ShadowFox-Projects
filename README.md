<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #103802;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .project {
            background: white;
            padding: 15px;
            margin: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(222, 215, 215, 0.1);
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>MY PORTFOLIO</h1>
        <nav>
            <ul>
                <li><a href="#about">ABOUT</a></li>
                <li><a href="#resume">RESUME</a></li>
                <li><a href="#portfolio">PORTFOLIO</a></li>
                <li><a href="#skills">SKILLS</a></li>
                <li><a href="#contact">CONTACT</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>ABOUT ME</h2>
        <p>Welcome to my portfolio!</p>
    </section>
    
    <section id="resume">
        <h2>RESUME</h2>
        <p><a href="/Users/sreeakhil/Downloads/Resume.pdf" download>Check My Resume</a></p>
    </section>
    
    <section id="portfolio">
        <h2>PORTFOLIO PROJECTS</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>As part of my web development internship, I designed and developed a fully responsive portfolio website to showcase my skills, projects, and experience. The website was built using HTML, CSS, and JavaScript, ensuring a modern and user-friendly design. Key features include a dynamic navigation menu, project showcase section, downloadable resume, and a contact form for professional networking. The project emphasized mobile-first design, accessibility, and performance optimization, demonstrating my ability to create visually appealing and functional web applications..</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>During the Java internship, I developed an Employee Management System (EMS), a web-based application designed to streamline employee data management. The system enables HR departments to efficiently manage employee records, track attendance, and generate reports.                .</p>
        </div>
    </section>
    
    <section id="skills">
        <h2>SKILLS</h2>
        <ul>
            <li>HTML | CSS | JAVA | Data Visualization</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>CONTACT</h2>
        <p>Email: sreeakhil.k47@gmail.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/sree-akhil-kolachina-1984472b9/">My LinkedIn Profile</a></p>
    </section>
</body>
</html>
