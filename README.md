# FAROOK5
A responsive personal portfolio website built with HTML, CSS, and JavaScript to showcase web design skills, projects, services, and contact information.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio | Freelance Web Designer</title>

    <meta name="description"
          content="Personal portfolio website showcasing web design services, projects, skills, and contact information.">

    <meta name="keywords"
          content="web designer, freelancer, portfolio, HTML, CSS, JavaScript">

    <meta name="author" content="Your Name">

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <nav>
            <h2>My Portfolio</h2>

            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>

        <section id="home">
            <h1>Hi, I'm Your Name</h1>
            <h2>Freelance Web Designer</h2>
            <p>
                I create modern, responsive and user-friendly websites
                for individuals and businesses.
            </p>

            <a href="#contact">Hire Me</a>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>
                I'm a beginner web designer passionate about creating
                beautiful and responsive websites using HTML, CSS and JavaScript.
            </p>
        </section>

        <section id="services">
            <h2>My Services</h2>

            <article>
                <h3>Website Design</h3>
                <p>Modern and responsive website designs.</p>
            </article>

            <article>
                <h3>Portfolio Websites</h3>
                <p>Professional personal portfolio websites.</p>
            </article>

            <article>
                <h3>Business Websites</h3>
                <p>Simple websites for small businesses and startups.</p>
            </article>
        </section>

        <section id="projects">
            <h2>My Projects</h2>

            <article>
                <h3>Portfolio Website</h3>
                <p>A responsive personal portfolio website.</p>
            </article>

            <article>
                <h3>Business Website</h3>
                <p>A modern website created for a business.</p>
            </article>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>

            <p>Email: your@email.com</p>

            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 Your Name. All Rights Reserved.</p>
    </footer>

</body>
</html>
