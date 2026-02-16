<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Apostle | Developer Portfolio</title>

<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: 'Segoe UI', sans-serif;
    background:#0d1117;
    color:#c9d1d9;
    scroll-behavior:smooth;
}

/* NAVIGATION */
nav{
    display:flex;
    justify-content:space-between;
    padding:20px 50px;
    background:#161b22;
    position:sticky;
    top:0;
}

nav h2{
    color:#58a6ff;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav ul li a{
    color:#c9d1d9;
    text-decoration:none;
    transition:0.3s;
}

nav ul li a:hover{
    color:#58a6ff;
}

/* HERO SECTION */
.hero{
    display:flex;
    flex-wrap:wrap;
    align-items:center;
    justify-content:center;
    padding:80px 20px;
    gap:40px;
}

.hero img{
    width:220px;
    height:220px;
    border-radius:50%;
    border:4px solid #58a6ff;
    object-fit:cover;
    box-shadow:0 0 30px #58a6ff;
}

.hero-text{
    max-width:500px;
}

.hero-text h1{
    font-size:40px;
    color:#58a6ff;
}

.hero-text p{
    margin:15px 0;
}

.btn{
    display:inline-block;
    padding:10px 25px;
    margin:10px 10px 0 0;
    background:#238636;
    color:white;
    text-decoration:none;
    border-radius:5px;
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.1);
}

/* SECTIONS */
section{
    padding:60px 20px;
    max-width:1000px;
    margin:auto;
}

h2{
    text-align:center;
    margin-bottom:40px;
    color:#58a6ff;
}

/* PROJECTS */
.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#161b22;
    padding:20px;
    border-radius:8px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
    background:#21262d;
}

/* SOCIAL */
.social{
    text-align:center;
    margin-top:20px;
}

.social a{
    color:#58a6ff;
    font-size:25px;
    margin:0 15px;
    transition:0.3s;
}

.social a:hover{
    color:white;
}

/* FOOTER */
footer{
    text-align:center;
    padding:20px;
    background:#161b22;
}
</style>
</head>

<body>

<nav>
    <h2>Apostle.dev</h2>
    <ul>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<div class="hero">
    <img src="profile.jpg" alt="Apostle Photo">
    <div class="hero-text">
        <h1>Hello, I'm Apostle</h1>
        <p>
            ICT Student | Software Developer | Graphic Designer.
            I build digital systems and solve real-world problems using technology.
        </p>
        <a href="Apostle_CV.pdf" download class="btn">Download CV</a>
        <a href="mailto:danielelijahangel7@gmail.com" class="btn">Hire Me</a>

        <div class="social">
            <a href="#"><i class="fab fa-github"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-facebook"></i></a>
        </div>
    </div>
</div>

<section id="projects">
    <h2>Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Student Management System</h3>
            <p>C++ application for managing student records and results.</p>
        </div>
        <div class="card">
            <h3>Portfolio Website</h3>
            <p>Responsive website built with HTML, CSS and JavaScript.</p>
        </div>
        <div class="card">
            <h3>Graphic Branding Design</h3>
            <p>Logo and digital poster designs for clients.</p>
        </div>
        <div class="card">
            <h3>Network Setup Project</h3>
            <p>Configured LAN networks and OS installations.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">
        Email: danielelijahangel7@gmail.com
    </p>
</section>

<footer>
    © 2026 Apostle | Developer Portfolio
</footer>

</body>
</html>
