<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aly Lakhani | Portfolio</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        h1, h2, h3, p {
            margin: 0;
            padding: 0;
        }
        .container {
            width: 90%;
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        /* Navigation Bar */
        nav {
            background-color: #333;
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 8px 16px;
            transition: background 0.3s;
        }
        nav ul li a:hover {
            background-color: #555;
            border-radius: 4px;
        }

        /* Header */
        header {
            text-align: center;
            padding: 80px 0;
            background: linear-gradient(135deg, #3498db, #8e44ad);
            color: white;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        /* Sections */
        section {
            margin-top: 50px;
            padding: 20px 0;
        }
        section h2 {
            font-size: 2rem;
            text-align: center;
            margin-bottom: 20px;
            color: #333;
        }
        section p {
            font-size: 1rem;
            line-height: 1.6;
            color: #666;
            text-align: center;
            margin: 0 auto;
            max-width: 600px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
        footer p {
            font-size: 0.9rem;
        }

        /* Responsiveness */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            nav ul li {
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Header -->
    <header>
        <div class="container">
            <h1>Welcome to Aly's Portfolio</h1>
            <p>Web Developer | Data Analyst | Tech Enthusiast</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Hello! I'm Aly Lakhani, a passionate web developer and data analyst with expertise in building and optimizing web-based solutions.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container">
        <h2>Projects</h2>
        <p>Here are some of my latest projects:</p>
        <ul>
            <li><strong>Project 1</strong>: Description of Project 1</li>
            <li><strong>Project 2</strong>: Description of Project 2</li>
            <li><strong>Project 3</strong>: Description of Project 3</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h2>Contact Me</h2>
        <p>Feel free to <a href="mailto:alylakhani@example.com">reach out</a> if you'd like to collaborate or chat!</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Aly Lakhani. All Rights Reserved.</p>
    </footer>

</body>
</html>
