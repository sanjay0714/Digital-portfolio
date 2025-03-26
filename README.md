<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>N. Sanjay - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #b5e61d;
            text-align: center;
            padding: 20px;
        }
        .header h1 {
            margin: 0;
            color: white;
        }
        .nav {
            display: flex;
            justify-content: center;
            background-color: #d41226;
            padding: 10px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 0 15px;
            font-size: 18px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
        }
        .resume-btn {
            display: block;
            text-align: center;
            padding: 10px;
            background: black;
            color: white;
            text-decoration: none;
            width: 150px;
            margin: 20px auto;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background: #d41226;
            color: white;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>N. Sanjay</h1>
        <p>BCA Student</p>
    </div>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        <div class="section" id="about">
            <h2>About Me</h2>
            <p>I am a student studying BCA at Prince Shri Venkateshwara Arts and Science.</p>
        </div>

        <div class="section" id="education">
            <h2>Education</h2>
            <p>Bachelor of Computer Applications (BCA)</p>
        </div>

        <div class="section" id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>Java</li>
                <li>C++</li>
            </ul>
        </div>

        <div class="section" id="projects">
            <h2>Projects</h2>
            <p>No projects listed yet.</p>
        </div>

        <div class="section" id="resume">
            <h2>Resume</h2>
            <a href="#" class="resume-btn">Download CV</a>
        </div>
    </div>

    <div class="footer">
        © 2025 N. Sanjay
    </div>

</body>
</html>
