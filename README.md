<h1>Hey You</h1>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Simple Website</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="content">
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website. You can add your content here.</p>
        </section>

        <section id="about">
            <h2>About</h2>
            <p>This is the about section. Write a little about yourself or the purpose of your website here.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Here you can put your contact information or a contact form.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Simple Website. All rights reserved.</p>
    </footer>

</body>
</html>

