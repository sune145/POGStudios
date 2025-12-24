<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>POG Studios</title>
    <style>
        /* Basic reset and styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #121212;
            color: #ffffff;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            padding: 20px;
            text-align: center;
            background-color: #1e1e1e;
        }

        header h1 {
            font-size: 2.5rem;
        }

        nav {
            margin: 10px 0;
            text-align: center;
        }

        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff4757;
        }

        main {
            flex: 1;
            padding: 40px;
            text-align: center;
        }

        footer {
            padding: 20px;
            text-align: center;
            background-color: #1e1e1e;
        }

        button {
            padding: 10px 20px;
            font-size: 1rem;
            cursor: pointer;
            border: none;
            background-color: #ff4757;
            color: #fff;
            border-radius: 5px;
        }

        button:hover {
            background-color: #ff6b81;
        }
    </style>
</head>
<body>
    <header>
        <h1>POG Studios</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#games">Games</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>Welcome to POG Studios! We create awesome games that entertain and inspire.</p>
        </section>

        <section id="games">
            <h2>Our Games</h2>
            <p>Check out our games here. (Content will be added later)</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Reach out to us at: contact@pogstudios.com</p>
            <button onclick="contactAlert()">Click Me</button>
        </section>
    </main>

    <footer>
        &copy; 2025 POG Studios. All rights reserved.
    </footer>

    <script>
        function contactAlert() {
            alert("Thanks for reaching out! We'll get back to you soon.");
        }
    </script>
</body>
</html>
