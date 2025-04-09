<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Test Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        h1 {
            margin: 0;
        }
        nav {
            background-color: #f2f2f2;
            padding: 10px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        nav a {
            margin-right: 15px;
            text-decoration: none;
            color: #333;
        }
        section {
            margin-bottom: 30px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #f2f2f2;
            border-radius: 5px;
            font-size: 0.9em;
        }
        .test-button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px 2px;
            cursor: pointer;
            border-radius: 5px;
        }
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sample Test Page</h1>
        <p>A basic HTML page for testing purposes</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to Our Test Page</h2>
        <p>This is a sample HTML page that includes various elements you might want to test:</p>
        <ul>
            <li>Headings and paragraphs</li>
            <li>Links and navigation</li>
            <li>Forms and input fields</li>
            <li>Buttons and interactive elements</li>
            <li>Basic styling with CSS</li>
        </ul>
        <button class="test-button">Click Me</button>
    </section>

    <section id="about">
        <h2>About This Page</h2>
        <p>This page was created to demonstrate basic HTML structure and common elements. It's not connected to any backend systems and is purely for frontend testing purposes.</p>
        <p>You can modify this page as needed for your specific testing requirements.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div style="display: flex; justify-content: space-between;">
            <div style="width: 30%; padding: 10px; background-color: #fff; border-radius: 5px;">
                <h3>Web Design</h3>
                <p>Creating beautiful, responsive websites.</p>
            </div>
            <div style="width: 30%; padding: 10px; background-color: #fff; border-radius: 5px;">
                <h3>Development</h3>
                <p>Building robust web applications.</p>
            </div>
            <div style="width: 30%; padding: 10px; background-color: #fff; border-radius: 5px;">
                <h3>Testing</h3>
                <p>Ensuring quality and performance.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Your name..">

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Your email..">

            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject" placeholder="Subject..">

            <label for="message">Message:</label>
            <textarea id="message" name="message" placeholder="Write something.." style="height:150px"></textarea>

            <input type="submit" class="test-button" value="Submit">
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Sample Test Page. All rights reserved.</p>
    </footer>
</body>
</html>
