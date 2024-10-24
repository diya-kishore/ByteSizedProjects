<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diya's Coding Challenge</title>
    <style>
        /* CSS Styles */
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }

        header {
            background-color: #ffcccb;
            padding: 20px;
            border-radius: 10px;
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
        }

        header p {
            font-size: 1.2em;
            color: #333;
        }

        .projects {
            background-color: #e0ffff;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }

        .projects h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        #project-list {
            list-style: none;
            padding: 0;
        }

        #project-list li {
            background-color: #faf0e6;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        footer {
            margin-top: 20px;
            font-size: 0.9em;
            color: #555;
        }

        footer a {
            color: #ff4500;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🐾 Diya's Coding Challenge</h1>
            <p>Small steps, big learning! 🚀</p>
        </header>
        <main>
            <section class="projects">
                <h2>Projects</h2>
                <ul id="project-list">
                    <!-- JavaScript will dynamically add project items here -->
                </ul>
            </section>
        </main>
        <footer>
            <p>Follow my journey on <a href="https://github.com/your-username" target="_blank">GitHub</a>!</p>
        </footer>
    </div>
    <script>
        // JavaScript to dynamically add projects
        const projects = [
            "Project 1: Hello World App",
            "Project 2: Simple Calculator",
            "Project 3: Weather App",
            "Project 4: To-Do List",
            "Project 5: Random Quote Generator"
        ];

        const projectList = document.getElementById("project-list");

        projects.forEach((project) => {
            const listItem = document.createElement("li");
            listItem.textContent = project;
            projectList.appendChild(listItem);
        });
    </script>
</body>
</html>
