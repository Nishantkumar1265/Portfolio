# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Write something about yourself here.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li>
                    <h3>Project 1</h3>
                    <p>Description of project 1.</p>
                </li>
                <li>
                    <h3>Project 2</h3>
                    <p>Description of project 2.</p>
                </li>
                <li>
                    <h3>Project 3</h3>
                    <p>Description of project 3.</p>
                </li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>© 2023 My Portfolio</p>
    </footer>
</body>
</html>
