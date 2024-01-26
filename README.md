<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title> - Portfolio</title>
</head>

<body>
    <header>
        <div class="container">
            <h1>Your Name</h1>
            <p>Web Developer</p>
        </div>
    </header>

    <section class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my portfolio! I am a passionate web developer with experience in HTML, CSS, and JavaScript.
                Check out my projects below and feel free to connect with me on social media.</p>
        </div>
    </section>

    <section class="projects">
        <div class="container">
            <h2>Projects</h2>
            <!-- Add your projects here -->
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of Project 1.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Description of Project 2.</p>
            </div>
        </div>
    </section>

    <section class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me through the following channels:</p>
            <ul>
                <li>Email: your.email@example.com</li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/yourname" target="_blank">LinkedIn Profile</a></li>
                <li>GitHub: <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>

</html>
//css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
}

header p {
    margin: 0;
}

.about,
.projects,
.contact {
    margin: 40px 0;
}

.projects .project {
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
