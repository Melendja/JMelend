<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jose Melendez - Hello World</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            background-color: #f4f4f4;
        }
        header {
            background-color: #003087;
            color: white;
            text-align: center;
            padding: 1em;
        }
        header h1 {
            margin: 0;
        }
        main {
            flex: 1;
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
        }
        .course-info {
            margin: 20px 0;
        }
        .course-info a {
            color: #003087;
            text-decoration: none;
        }
        .course-info a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #003087;
            color: white;
            text-align: center;
            padding: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hello World!</h1>
    </header>
    <main>
        <h2>Welcome to My Webpage</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/US_Department_of_Veterans_Affairs_vertical_logo.svg" alt="Veterans Affairs Logo">
        <div class="course-info">
            <p>Currently attending: <strong>Web Systems I_521F_FA25_ON</strong> at Daytona State College.</p>
            <p>Visit the course page: <a href="https://class.daytonastate.edu/d2l/home" target="_blank">Daytona State College</a></p>
        </div>
    </main>
    <footer>
        <p>Created by Jose A. Melendez</p>
    </footer>
</body>
</html>
