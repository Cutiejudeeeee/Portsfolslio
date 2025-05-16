@Jude Mateo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Iconic Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
			text-shadow: 2px 2px Black;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: White;
			background-image: url('Related/nika.gif');
			background-size: cover;
			background-position: center;
			background-repeat: no-repeat;    
			background-attachment: fixed;
        }
		
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
			text-shadow: 2px 2px red;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background: #444;
            color: #fff;
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 0.5rem 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
            max-width: 900px;
            margin: auto;
			text-shadow: 3px 3px gray;
	
        }
        .projects img {
            width: 5%;
            height: 5%;
            display: none;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding-bottom: 1px;
            position: fixed;
            width: 100%;
            bottom: -10;
        }
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background: #444;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jude L. Mateo</h1>
        <p>Welcome to my Iconic portfolio!</p>
		<img src="Related/Gui.jpg" width="200" height="200">
		
    </header>
    <nav>
        <a href="#about">About</a>
		<a href="#about">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contacts</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>Hi! I'm Jude L. Mateo, a first year Computer Engineering specializing in University Of Bohol. I am passionate about learning Web Design. I live in Ubujan, Tagbilaran City, Bohol</p>
    </section>
	
	<section id="about">
		<h2>Education</h2>
		<h4>Ubujan Elementary School</h4>
		<p>2015-2018</p>
		<p>Best in Loyalty</p>
		<p>Best in Honesty</p>
		<p>Best in Attendance</p>
		<p>Best in Takyang</p>

		
		
		<h4>Dr. Cecilio Putong National High School</h4>
		<p>2018 - 2022</p>
		<p>With Highest Honors</p>
		<p>Valedictorian 2022</p>
		
		
		<h4>Dr. Cecilio Putong National Senior High School</h4>
		<p>2022 - 2024</p>
		<p>With Highest Honors</p>
		<p>Valedictorian 2024</p>
		
		
		
		
		<h4>University of Bohol</h4>
		<p>2024 - Present</p>
		<p>Magna Cumlaude</p>
		<p>Summa Cumlaude</p>
		
	</section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Coding</li>
            <li>Web Design</li>
            <li>Good at Sports and E-Sports</li>
            
        </ul>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <article>
            <h3>SUMOBOT</h3>
            <p>A Sumobot is exactly what it sounds like: a sumo-wrestling robot. More speciﬁcally, Sumobots are autonomous robots programmed to push other Sumobots out of a ring without getting pushed out themselves. <a href="#" class="btn">View Project</a></p>
            <img src="project-image-placeholder.jpg" alt="Project Image">
        </article>
        <article>
            <h3>WEBSITE</h3>
            <p>Short description of the project. <a href="#" class="btn">View Project</a></p>
            <img src="project-image-placeholder.jpg" alt="Project Image">
        </article>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me via the following:</p>
        <ul>
            <li>Email: <a href="jlmateo@universityofbohol.edu.ph" target="_blank">jlmateo@universityofbohol.edu.ph</a></li>
            <li>Phone: 09460178033</li>
            <li>LinkedIn: <a href="https://www.facebook.com/Cutiejudee" target="_blank">Ju Dey</a></li>
            <li>GitHub: <a href="https://github.com/Cutiejudeeeee" target="_blank">Jude Mateo</a></li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2025 Mateo. All rights reserved.</p>
    </footer>
</body>
</html>
