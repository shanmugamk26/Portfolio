<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shanmugam K | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #080d19;
            color: white;
            line-height: 1.6;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 8%;
            background: #101a2e;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        header h2 {
            color: #00c8ff;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: #00c8ff;
        }

        section {
            padding: 80px 10%;
        }

        .hero {
            min-height: 90vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start;
            background: linear-gradient(120deg, #080d19, #142b4b);
        }

        .hero h1 {
            font-size: 55px;
            margin: 15px 0;
        }

        .hero h1 span {
            color: #00c8ff;
        }

        .hero p {
            max-width: 650px;
            color: #c4d0df;
            font-size: 18px;
        }

        .btn {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: #00c8ff;
            color: #08111e;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        .section-title {
            font-size: 32px;
            color: #00c8ff;
            margin-bottom: 30px;
            text-align: center;
        }

        .about {
            text-align: center;
        }

        .about p {
            max-width: 800px;
            margin: auto;
            color: #c4d0df;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background: #142238;
            padding: 25px;
            border-radius: 10px;
            border: 1px solid #263e5d;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-7px);
            border-color: #00c8ff;
        }

        .card h3 {
            color: #00c8ff;
            margin-bottom: 12px;
        }

        .card p {
            color: #c4d0df;
        }

        .contact {
            text-align: center;
        }

        .contact a {
            color: #00c8ff;
            text-decoration: none;
            margin: 10px;
            display: inline-block;
        }

        footer {
            background: #101a2e;
            text-align: center;
            padding: 20px;
            color: #aab7c8;
        }

        @media(max-width: 700px) {
            header {
                flex-direction: column;
                gap: 12px;
            }

            nav a {
                margin: 5px;
                font-size: 13px;
            }

            .hero h1 {
                font-size: 38px;
            }

            section {
                padding: 60px 7%;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>SHAN.</h2>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h3>Hello, I'm</h3>
        <h1>Shanmugam <span>K.</span></h1>

        <p>
            Aspiring Software Engineer | AI Developer |
            IoT Enthusiast | Creative Technology Explorer
        </p>

        <a href="#about" class="btn">Explore My Portfolio</a>
    </section>

    <section class="about" id="about">
        <h2 class="section-title">About Me</h2>

        <p>
            I am Shanmugam K, a BCA student and technology enthusiast
            passionate about Software Development, Artificial Intelligence,
            Internet of Things, Cybersecurity and 3D Printing.
            I enjoy exploring new technologies and building innovative
            projects that solve real-world problems.
        </p>
    </section>

    <section id="skills">
        <h2 class="section-title">My Skills</h2>

        <div class="skills">
            <div class="card">
                <h3>Programming</h3>
                <p>Python, Java, C Basics</p>
            </div>

            <div class="card">
                <h3>Web Development</h3>
                <p>HTML, CSS, JavaScript</p>
            </div>

            <div class="card">
                <h3>Technology</h3>
                <p>Artificial Intelligence, IoT, Cybersecurity</p>
            </div>

            <div class="card">
                <h3>Creative Technology</h3>
                <p>3D Modeling, 3D Printing, Product Design</p>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2 class="section-title">My Projects</h2>

        <div class="projects">

            <div class="card">
                <h3>AIoT Personal Assistant Robot</h3>
                <p>
                    An ESP32-based smart assistant robot featuring
                    voice interaction, OLED display, camera and
                    voice-controlled movement.
                </p>
            </div>

            <div class="card">
                <h3>VOXLON</h3>
                <p>
                    A 3D Printing and Creative Technology business
                    focused on customized toys, 3D modeling and
                    product design.
                </p>
            </div>

            <div class="card">
                <h3>Smart Shopkeeper App</h3>
                <p>
                    A digital inventory management application
                    concept for shopkeepers and suppliers.
                </p>
            </div>

        </div>
    </section>

    <section id="contact" class="contact">
        <h2 class="section-title">Contact Me</h2>

        <p>Let's connect and create something innovative!</p>

        <a href="mailto:yourmail@gmail.com">Email</a>

        <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>

        <a href="https://github.com/" target="_blank">GitHub</a>

        <a href="https://www.instagram.com/attitude_king__shan/"
           target="_blank">Instagram</a>
    </section>

    <footer>
        <p>© 2026 Shanmugam K. All Rights Reserved.</p>
        <p>Learn. Build. Innovate. Inspire.</p>
    </footer>

</body>
</html>
