<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aly Lakhani | Simple Portfolio</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        h1, h2, h3, p {
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        /* Header */
        header {
            background-color: #333;
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        /* Section Styles */
        section {
            margin: 40px 0;
            text-align: center;
        }
        section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #444;
        }
        section p {
            font-size: 1rem;
            line-height: 1.6;
            max-width: 600px;
            margin: 0 auto;
            color: #555;
        }

        /* Buttons */
        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .button:hover {
            background-color: #2980b9;
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

        /* Media Queries */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            section h2 {
                font-size: 1.5rem;
            }
            .container {
                width: 90%;
                padding: 10px;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Web Developer | Data Analyst</p>
    </header>

    <!-- About Section -->
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I'm Aly Lakhani, a passionate web developer and data analyst with experience in building web-based solutions and automating data processes.</p>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>Projects</h2>
            <p>Explore some of my latest projects below:</p>
            <a href="https://github.com/alylakhani10" class="button">View My GitHub</a>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Me</h2>
            <p>Want to connect? <a href="mailto:alylakhani@example.com">Email me here</a>.</p>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Aly Lakhani. All rights reserved.</p>
    </footer>

</body>
</html>

