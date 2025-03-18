
DOCTYPE html>  <html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>My Portfolio</title>  
    <link rel="stylesheet" href="style.css">  
</head>  
<body>  
    <header>  
        <nav>  
            <ul>  
                <li><a href="#home">Home</a></li>  
                <li><a href="#about">About</a></li>  
                <li><a href="#portfolio">Portfolio</a></li>  
                <li><a href="#contact">Contact</a></li>  
            </ul>  
        </nav>  
    </header>  <section id="home">  
    <div class="hero">  
        <h1>Welcome to My Portfolio</h1>  
        <p> Passionate about technology and digital solutions. Explore my projects below! </p> 
        <a href="#about" class="btn">Learn More</a>  
    </div>  
</section>  

<section id="about">  
    <h2>About Me</h2>  
    <p>  
        I have completed IT System Support NQF Level 5 and have experience in creating web-based solutions such as quiz apps. My goal is to combine technical skills with creative thinking to drive innovation.  
    </p>  
</section>  

<section>
   <section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>HTML, CSS, & Python</li>
        <li>IT System Support</li>
        <li>Cybersecurity Fundamentals</li>
        <li>Data Analysis (Excel, SQL)</li>
    </ul>
</section>

<section id="portfolio">  
    <h2>My Projects</h2>  
    <div class="project">  
        <h3>SILC Web Quiz</h3>  
        <p>A web-based quiz to help children improve comprehension skills.</p>  
    </div>  
    <div class="project">  
        <h3>System Support Installation</h3>  
        <p>Hands-on experience with Windows 10 installation and antivirus setup.</p>  
    </div>  
</section>  

<section id="cv">  
    <h2>Download My CV</h2>  
    <a href="ELIHLENOBS.pdf" download class="btn">Download CV</a>  
</section>  

<section id="contact">  
    <h2>Contact Me</h2>  
    <form>  
        <label for="name">Name</label>  
        <input type="text" id="name" name="name" required>  

        <label for="email">Email</label>  
        <input type="email" id="email" name="email" required>  

        <label for="message">Message</label>  
        <textarea id="message" name="message" rows="5" required></textarea>  

        <button type="submit">Send</button>  
    </form>  
</section>  

<footer>  
    <p>&copy; 2025 Elihle | All Rights Reserved</p>  
</footer>  

<script src="script.js"></script>

</body>  
</html>  <style>  
  body {  
    font-family: Arial, sans-serif;  
    margin: 0;  
    padding: 0;  
    line-height: 1.6;  
    background-color: #f4f4f9;  
}  
  
header {  
    background: #333;  
    color: #fff;  
    padding: 10px 0;  
    position: sticky;  
    top: 0;  
    z-index: 1000;  
}  
  
header nav ul {  
    display: flex;  
    justify-content: center;  
    list-style: none;  
    margin: 0;  
    padding: 0;  
}  
  
header nav ul li {  
    margin: 0 15px;  
}  
  
header nav ul li a {  
    color: #fff;  
    text-decoration: none;  
    font-size: 18px;  
}  
  
.hero {  
    text-align: center;  
    padding: 50px 20px;  
    background: linear-gradient(45deg, #4caf50, #81c784);  
    color: black;  
}  
  
.hero h1 {  
    font-size: 2.5rem;  
}  
  
.hero p {  
    font-size: 1.2rem;  
    margin: 10px 0 20px;  
}  
  
.btn {  
    display: inline-block;  
    padding: 10px 20px;  
    background: #007bff;  
    color: darkblue;  
    text-decoration: none;  
    border-radius: 6px;  
    transition: background 0.3s;  
}  
  
.btn:hover {  
    background: #0056b3;  
}  
  
section {  
    padding: 40px 20px;  
    text-align: center;  
}  
  
.project {  
    margin-bottom: 20px;  
    padding: 20px;  
    background: #fff;  
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);  
    border-radius: 5px;  
}  
  
footer {  
    text-align: center;  
    background: #333;  
    color: #fff;  
    padding: 10px 0;  
    margin-top: 20px;  
}  
#skills {
    text-align: center;
    padding: 40px 20px;
    background: #e3f2fd; /* Light blue background */
}

.skills-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
    max-width: 800px;
    margin: 0 auto;
}

.skill {
    background: green;
    color: white;
    padding: 10px 20px;
    border-radius: 20px;
    font-size: 16px;
    font-weight: bold;
    text-transform: uppercase;
    box-shadow: 2px
  <\style>  
