<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Gurudattarayan | Computer Science Lecturer</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            background: #0f172a;
            color: white;
            line-height: 1.6;
        }

        header {
            display: flex;
            justify-content: space-between;
            padding: 20px 10%;
            align-items: center;
            background: #020617;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h2 {
            color: #38bdf8;
            margin: 0;
        }

        nav a {
            margin-left: 20px;
            color: white;
            text-decoration: none;
            transition: 0.3s;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 80px 10%;
            min-height: 400px;
        }

        .hero-text h1 {
            font-size: 45px;
            margin-bottom: 10px;
        }

        .hero-text span {
            color: #38bdf8;
        }

        .btn {
            background: #38bdf8;
            padding: 12px 25px;
            border-radius: 6px;
            color: #0f172a;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 20px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #7dd3fc;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            border-bottom: 2px solid #38bdf8;
            display: inline-block;
            margin-bottom: 30px;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }

        .card {
            background: #1e293b;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid transparent;
            transition: 0.3s;
        }

        .card:hover {
            border-color: #38bdf8;
            transform: translateY(-5px);
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .project {
            background: #1e293b;
            padding: 20px;
            border-radius: 10px;
        }

        .project h3 {
            color: #38bdf8;
            margin-top: 0;
        }

        .contact {
            text-align: center;
            background: #1e293b;
            margin: 40px 10%;
            border-radius: 15px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            font-size: 0.9em;
            color: #94a3b8;
        }
    </style>
</head>
<body>

<header>
    <h2>Dr. Gurudattarayan</h2>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Courses</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-text">
        <h1>Hi, I'm <span>Dr. Gurudattarayan</span></h1>
        <p>Computer Science Lecturer passionate about teaching programming, artificial intelligence, and modern computing technologies.</p>
        <a href="#contact" class="btn">Contact Me</a>
    </div>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        Experienced Computer Science Lecturer with expertise in teaching
        Data Structures, Algorithms, Artificial Intelligence and Programming.
        Focused on helping students develop strong technical and problem solving skills.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="skills">
        <div class="card">Python</div>
        <div class="card">Java</div>
        <div class="card">C++</div>
        <div class="card">Data Structures</div>
        <div class="card">Algorithms</div>
        <div class="card">Artificial Intelligence</div>
    </div>
</section>

<section id="projects">
    <h2>Courses Taught</h2>
    <div class="projects">
        <div class="project">
            <h3>Data Structures</h3>
            <p>Teaching algorithms, stacks, queues, trees and graphs.</p>
        </div>
        <div class="project">
            <h3>Database Management</h3>
            <p>Concepts of SQL, relational databases and normalization.</p>
        </div>
        <div class="project">
            <h3>Artificial Intelligence</h3>
            <p>Machine learning basics and intelligent systems.</p>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: <strong>drgurudattarayan@email.com</strong></p>
    <p>Phone: <strong>+91 9750147247</strong></p>
</section>

<footer>
    <p>© 2026 Dr. Gurudattarayan | Computer Science Educator</p>
</footer>

</body>
</html>
