<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Janhvi Singh - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: rgb(0, 0, 34);
            color: white;
            font-family: 'Poppins', sans-serif;
        }
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 64);
        }
        nav ul {
            display: flex;
            justify-content: center;
        }
        nav ul li {
            list-style: none;
            margin: 0 23px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
        }
        nav ul li a:hover {
            color: rgb(153, 153, 226);
            font-size: 1.04rem;
        }
        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 60px 84px;
        }
        .left {
            font-size: 1.5rem;
        }
        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 80px 0;
        }
        .firstSection > div {
            width: 30%;
        }
        .leftSection {
            font-size: 3rem;
        }
        .leftSection .button {
            padding: 12px;
            background-color: black;
            color: white;
            border: 2px solid white;
            border-radius: 4px;
            font-size: 20px;
            cursor: pointer;
            margin-right: 10px;
        }
        .rightSection img {
            width: 200px; /* Adjust the size as needed */
            border-radius: 50%; /* Makes the image circular */
        }
        .text-gray {
            color: gray;
        }
        .secondSection {
            max-width: 80vw;
            margin: auto;
        }
        .secondSection h1 {
            font-size: 1.9rem;
        }
        footer {
            background-color: rgb(2, 30, 57);
            height: 233px;
        }
        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }
        .footer ul {
            list-style: none;
        }
        .contact-section {
            text-align: center;
            margin: 50px 0;
        }
        .contact-section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .contact-section a {
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            background-color: rgb(18, 18, 64);
            border: 2px solid white;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .contact-section a:hover {
            background-color: rgb(50, 50, 120);
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="left">Janhvi's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="#contact">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection"> 
            <div class="leftSection">
                Hi, my name is Janhvi Singh 
                <div>and I am a Passionate</div>
                <span id="element"></span>
                <div>
                    <!-- Resume Download Button -->
                    <a href="janhvi.resume.jpg.pdf" target="_blank" download>
                        <button class="button">Download Resume</button>
                    </a>
                    <!-- GitHub Button -->
                    <a href="https://github.com/janhvis250"_blank">
                        <button class="button">Visit GitHub</button>
                    </a>
                </div>
            </div>
            <div class="rightSection">
                <img src="janhvi.png.jpg" alt="Janhvi's Profile Photo" style="width: 200px; border-radius: 50%;">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <h1>About Me</h1>
            <p>
                I'm currently a B.Tech 2nd year student at KAMLA NEHRU INSTITUTE OF PHYSICAL & SOCIAL SCIENCES  FARIDIPUR, SULTANPUR (U.P.)
                , specializing in CSE with AI. I am learning web development and have a strong understanding of C language, Java, python and MySQL.
            </p>
        </section>
        <section id="services" class="secondSection">
            <h1>Services</h1>
            <ul>
                <li>Website development using HTML, CSS, JavaScript, Next.js, and Node.js</li>
                <li>Front-end and back-end web development</li>
                <li>Custom web solutions and design</li>
                <li>Java and Python programming solutions</li>
                <li>Database management using MySQL</li>
                <li>AI-related concepts and implementation</li>
            </ul>
        </section>
        <hr>
        <section class="secondSection">
            <h1>Projects</h1>
            <p>Currently, I Have Only one simple projects. It's based on real word problem;- Library Management System is one of the most common software development projects till date. In this article, we are going to make the Library Management System software development project, from scratch, for 2nd year students. We will be covering all the steps you have to do while developing this project.In Our project as we will be exploring about web application for Library Management system project so we will be required below skill sets. </p>
            <p> 1:- Front end Developer
                2:- Back end Developer 
                3:- Tester
                4:- Devops Developer </p>
        </section>
        
        <hr>
        <!-- New Contact Section -->
        <section class="contact-section">
            <h2>Interested? Contact Me!</h2>
            <p>If you're interested in working with me or have any inquiries, feel free to send me an email or give me a call!</p>
            <a href="mailto:singhjanhvi2006@gmail.com">Send an Email</a> 
            <br><br>
            <a href="tel:+91 9219435121">Call Me</a>
        </section>
        <hr>
        <section id="contact" class="secondSection">
            <h1>Contact Me</h1>
            <p>Email: <a href="mailto:singhjanhvi2006@gmail.com" style="color: white;">singhjanhvi2006@gmail.com</a></p>
            <p>Phone: <a href="tel:+919219435121" style="color: white;">+91 9219435121</a></p>
        </section>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h1>janhvi's Portfolio</h1>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>Contact</li>
                    <li>Projects</li>
                    <li>Services</li>
                </ul>
            </div>
            <div class="footer-third">
                <ul>
                    <li>Home</li>
                    <li>Contact</li>
                    <li>Projects</li>
                    <li>Services</li>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>Home</li>
                    <li>Contact</li>
                    <li>Projects</li>
                    <li>Services</li>
                </ul>
            </div>
        </div>
    </footer>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Web Designer', 'Data Analyst'],
            typeSpeed: 50,
        });
    </script>
</body>
</html>