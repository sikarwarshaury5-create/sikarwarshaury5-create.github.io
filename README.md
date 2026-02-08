<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shaury Sikarwar | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: radial-gradient(circle at top, #0f2027, #000);
            color: white;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 40px;
            background: black;
            border-bottom: 1px solid cyan;
        }

        nav h1 {
            color: cyan;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: cyan;
        }

        .profile {
            text-align: center;
            padding: 60px 20px;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid cyan;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .profile h2 {
            margin-bottom: 5px;
        }

        .profile p {
            color: #aaa;
            margin-bottom: 20px;
        }

        .social a {
            display: inline-block;
            margin: 5px;
            padding: 8px 15px;
            border: 1px solid cyan;
            color: cyan;
            text-decoration: none;
            border-radius: 6px;
            transition: 0.3s;
        }

        .social a:hover {
            background: cyan;
            color: black;
        }

        .projects {
            text-align: center;
            padding: 60px 20px;
        }

        .projects h2 {
            margin-bottom: 30px;
        }

        .project-card {
            width: 300px;
            margin: auto;
            background: rgba(0, 0, 0, 0.6);
            border: 1px solid cyan;
            border-radius: 12px;
            padding: 15px;
            transition: 0.3s;
        }

        .project-card:hover {
            transform: scale(1.05);
        }

        .project-card img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 10px;
        }

        .project-card h3 {
            color: cyan;
        }

        .project-card p {
            font-size: 14px;
            color: #ccc;
            margin-bottom: 10px;
        }

        .project-card a {
            display: inline-block;
            padding: 6px 12px;
            border: 1px solid cyan;
            color: cyan;
            text-decoration: none;
            border-radius: 6px;
        }

        .project-card a:hover {
            background: cyan;
            color: black;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: black;
            border-top: 1px solid cyan;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <nav>
        <h1>Shaury Sikarwar</h1>
        <div>
            <a href="#home">Home</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section id="home" class="profile">
        <img src="WhatsApp Image 2026-02-06 at 12.13.22 PM.jpeg" alt="Shaury Sikarwar">

        <h2>Shaury Sikarwar</h2>
        <p>Student | Web Developer | Programmer</p>

        <div class="social">
            <a href="https://github.com/sikarwarshaury5-create" target="_blank">GitHub</a>
            <a href="https://www.linkedin.com/in/shaury-sikarwar-a2b003381" target="_blank">LinkedIn</a>
        </div>
    </section>

   
    <section id="projects" class="projects">
        <h2>My Project</h2>

        <div class="project-card">
            <img src="Screenshot 2025-12-02 135809.png" alt="Brandify Project">
            <h3>Brandify</h3>
            <p>E-commerce brand discovery website using HTML & CSS.</p>
            <a href="https://www.linkedin.com/in/shaury-sikarwar-a2b003381" target="_blank">
                View on LinkedIn
            </a>
        </div>
    </section>

    <footer id="contact">
        © 2026 Shaury Sikarwar | All Rights Reserved
    </footer>

</body>
</html>
