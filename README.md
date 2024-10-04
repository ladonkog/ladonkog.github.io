# ladonkog.github.io
/portfolio
├── index.html
├── styles.css
└── images
    └── profile.jpg   (optional: your profile image)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Engineering Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <img src="images/profile.jpg" alt="Profile Image" class="profile-img">
            <h1>John Doe</h1>
            <p>Aerospace Engineer | Researcher | Dynamics & Control Specialist</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>I am an Aerospace Engineering student specializing in Dynamics and Control at Embry-Riddle Aeronautical University. I am passionate about advanced technologies in aerospace, and I have extensive research experience in test and manufacturing engineering. I am currently leading a project on NASA's Coaxial Continuous Fiber 3D Printing.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>NASA Coaxial Continuous Fiber 3D Printing</h3>
                <p>Developed innovative methods for printing in-space energy storage devices using continuous fiber 3D printing technologies. Managed the project as a leader in collaboration with NASA research teams.</p>
            </div>
            <div class="project">
                <h3>In-Space Energy Storage Devices Research</h3>
                <p>Conducted research on the dynamics of in-space energy storage devices, developing efficient energy solutions for long-duration space missions.</p>
            </div>
            <!-- Add more projects as needed -->
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>Dynamics and Control of Aircraft & Spacecraft</li>
                <li>Test Engineering & Manufacturing Engineering</li>
                <li>Matlab, Simulink, Python</li>
                <li>CAD (SolidWorks, CATIA)</li>
            </ul>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>If you'd like to get in touch, feel free to reach out through any of the following:</p>
            <ul>
                <li>Email: <a href="mailto:john.doe@email.com">john.doe@email.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/johndoe">linkedin.com/in/johndoe</a></li>
                <li>GitHub: <a href="https://github.com/johndoe">github.com/johndoe</a></li>
            </ul>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 John Doe | Aerospace Engineering Portfolio</p>
        </div>
    </footer>

</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

h1, h2 {
    text-align: center;
    color: #333;
}

/* Header */
header {
    background-color: #333;
    color: #fff;
    padding-top: 30px;
    padding-bottom: 30px;
    text-align: center;
}

.profile-img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    margin: 0 auto 20px;
}

header h1 {
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

/* Sections */
section {
    padding: 20px 0;
    margin: 20px 0;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

h2 {
    margin-bottom: 20px;
}

/* Projects */
.project {
    margin-bottom: 20px;
}

.project h3 {
    color: #333;
    margin-bottom: 10px;
}

/* Skills */
ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background: #f4f4f4;
    margin-bottom: 10px;
    padding: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

/* Contact */
a {
    color: #333;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
