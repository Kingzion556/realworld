<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RealWorld - Your Digital Crypto Broker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin: 0;
            padding: 1em;
            background-color: #444;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            padding: 2em;
        }
        section {
            margin-bottom: 2em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        form input, form select, form textarea {
            display: block;
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            background-color: #333;
            color: white;
            padding: 0.5em 1em;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>RealWorld</h1>
        <p>Your Digital Crypto Broker</p>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#profile">Profile</a>
        <a href="#registration">Register</a>
        <a href="#resources">Resources</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>Welcome to RealWorld, your trusted digital crypto broker. We offer real-time trading, portfolio management, and comprehensive market analysis to help you make informed trading decisions.</p>
        </section>
        <section id="profile">
            <h2>Profile</h2>
            <p>Manage your profile and track your portfolio performance. Stay updated with the latest market trends and insights.</p>
        </section>
        <section id="registration">
            <h2>Register</h2>
            <form action="/submit_registration" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                
                <label for="experience">Trading Experience:</label>
                <select id="experience" name="experience" required>
                    <option value="beginner">Beginner</option>
                    <option value="intermediate">Intermediate</option>
                    <option value="expert">Expert</option>
                </select>
                
                <button type="submit">Register</button>
            </form>
        </section>
        <section id="resources">
            <h2>Resources</h2>
            <p>Access market analysis, trading tools, and educational materials to enhance your trading strategies and knowledge.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 RealWorld. All rights reserved.</p>
    </footer>
</body>
</html>
