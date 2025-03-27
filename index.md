<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            max-width: 900px;
            background: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        header {
            background: #6a11cb;
            color: white;
            padding: 20px;
            border-radius: 10px 10px 0 0;
        }
        h1 {
            margin: 0;
        }
        section {
            margin: 30px 0;
        }
        .button {
            display: inline-block;
            padding: 12px 24px;
            background: #6a11cb;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: transform 0.3s ease, background 0.3s ease;
        }
        .button:hover {
            background: #2575fc;
            transform: scale(1.1);
        }
        .projects {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .project {
            background: #f7f7f7;
            padding: 20px;
            border-radius: 10px;
            width: 280px;
            text-align: center;
            transition: transform 0.3s ease;
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
        }
        .project:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>My Portfolio</h1>
        </header>
        <section>
            <h2>About Me</h2>
            <p>Hello! I am Naveen Kumar E, a passionate developer. Explore my projects and skills.</p>
        </section>
        <section>
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <h3>Project 1</h3>
                    <p>A brief description of the project.</p>
                    <a href="https://github.com/NAVEENKUMAR4325/IBM-Z-Datathon---ML-model-for-Transportation" class="button" target="_blank">View</a>
                </div>
                <div class="project">
                    <h3>Project 2</h3>
                    <p>A brief description of the project.</p>
                    <a href="https://github.com/JudeSamJ/techmavericks_KSP" class="button" target="_blank">View</a>
                </div>
                <div class="project">
                    <h3>Project 3</h3>
                    <p>A brief description of the project.</p>
                    <a href="https://github.com/NAVEENKUMAR4325/Problem_Solving_with_Team" class="button" target="_blank">View</a>
                </div>
            </div>
        </section>
        <section>
            <h2>Contact</h2>
            <p>Email: naveen@example.com</p>
        </section>
    </div>
</body>
</html>
