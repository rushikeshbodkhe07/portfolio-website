<!<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rushikesh_Bodkhe Portfolio</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        .profile-img {
            
    width: 180px;
    height: 180px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #00eaff;
    box-shadow: 0 0 20px #00eaff;
    margin-bottom: 20px;
  

}


        body {
            font-family: 'Poppins', sans-serif;
            background: #0e0e0e;
            color: white;
        }

        /* NAVBAR */
        nav {
            display: flex;
            justify-content: space-between;
            padding: 20px 40px;
            position: fixed;
            width: 100%;
            background: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(8px);
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: #00eaff;
            margin-left: 20px;
            text-decoration: none;
            font-size: 18px;
        }

        nav h2 {
            color: #00eaff;
        }

        /* HERO SECTION */
        .hero {
           
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            background: linear-gradient(135deg, #001f2f, #000000);
           
        }

        .hero h1 {
            font-size: 50px;
        }

        .hero h2 {
            font-size: 40px;
            margin-bottom: 10px;
        }
        
            
        

        .hero p {
            font-size: 20px;
            color: #ccc;
        }

        .btn {
            margin-top: 20px;
            padding: 12px 25px;
            border-radius: 30px;
            border: none;
            background: #00eaff;
            color: black;
            font-size: 18px;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            transform: scale(1.05);
            background: white;
        }

        /* SECTIONS */
        section {
            padding: 80px 20px;
            text-align: center;
        }

        h2 {
            font-size: 35px;
            margin-bottom: 20px;
            color: #00eaff;
        }

        p {
            color: #ccc;
            font-size: 18px;
        }

        /* SKILLS */
        .skills-box {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .skill {
            background: #111;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #00eaff;
            width: 180px;
        }

        /* PROJECTS */
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .project-card {
            background: #111;
            padding: 20px;
            border-radius: 15px;
            border: 1px solid #00eaff;
            transition: 0.3s;
        }

        .project-card:hover {
            transform: scale(1.03);
            box-shadow: 0 0 20px #00eaff;
        }

        /* FOOTER */
        footer {
            text-align: center;
            padding: 20px;
            background: #000;
            margin-top: 40px;
            color: #aaa;
        }

        /* Responsive */
        @media(max-width: 768px) {
            .hero h1 {
                font-size: 35px;
            }
            nav {
                padding: 15px 20px;
            }
        }
    </style>
</head>

<body>

    <!-- NAVBAR -->
    <nav>
        <h2>Rushikesh Bodkhe</h2>
        <div>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <!-- HERO -->
<section class="hero">
    <img src="profile.jpg" class="profile-img" alt="Profile Photo">

    <h1>Hi, I'm <span style="color:#00eaff;">Rushikesh</span></h1>
    <p>  front-end and back-end developer</p>

    <a href="#contact"><button class="btn">Hire me</button></a>
</section>


    <!-- ABOUT -->
    <section id="about">
        <h2>About Me</h2>
        <p><p>Hi, I’m Rushikesh Bodkhe...!</p>
I’m an aspiring Web Developer with a strong interest in building clean, modern, and responsive websites.
<p>I enjoy converting ideas into real web projects using HTML, CSS, and JavaScript.</p>

<p>Currently, I’m learning and improving in</p>

<p>Frontend Development </p>

<p>Responsive UI Design</p>

<p>JavaScript Basics</p>

<p>Modern Web Layouts</p>

<p>My goal is to become a Full-Stack Web Developer and build real-world applications that are fast, user-friendly, and visually appealing.</p>

I believe in continuous learning and improving myself every day.
<p>Scroll down to see my work...!</p>
    </section>

    <!-- SKILLS -->
    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills-box">
            <div class="skill">Java</div>
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
           
        </div>
    </section>

    

    <!-- PROJECTS -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project-card">
                <h3>Student Management System</h3>
                <p>Java-based CRUD project with file handling.</p>
            </div>

            <div class="project-card">
                <h3>To-Do App</h3>
                <p>Frontend project using HTML, CSS, JS.</p>
            </div>

            <div class="project-card">
                <h3>Password Strength Checker</h3>
                <p>Cybersecurity tool built using JavaScript.</p>
            </div>
        </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourmail@gmail.com</p>
        <p>LinkedIn: your-profile-link</p>
        <p>GitHub: your-link</p>
    </section>

    <!-- FOOTER -->
    <footer>
        © 2025 Rushikesh Portfolio | All Rights Reserved
    </footer>

</body>
</html>


 
