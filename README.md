<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Eng-Abdulaziz Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
    }

    header {
      display: flex;
      align-items: center;
      padding: 40px;
      background: rgba(0,0,0,0.5);
      backdrop-filter: blur(10px);
      animation: slideDown 1s ease;
    }

    header img {
      width: 120px;
      border-radius: 50%;
      border: 3px solid #00e5ff;
      margin-right: 25px;
      box-shadow: 0 0 20px #00e5ff;
    }

    h1 {
      font-size: 2.5em;
      color: #00e5ff;
    }

    section {
      padding: 40px;
      animation: fadeUp 1s ease;
    }

    h2 {
      color: #00e5ff;
      border-bottom: 2px solid #00e5ff;
      display: inline-block;
      padding-bottom: 5px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
      margin-top: 20px;
    }

    .skill-item {
      text-align: center;
      width: 120px;
      transition: 0.3s;
    }

    .skill-item i {
      font-size: 40px;
      color: #00e5ff;
    }

    .skill-item:hover {
      transform: scale(1.1);
    }

    .project {
      background: rgba(255,255,255,0.05);
      border-radius: 12px;
      padding: 20px;
      margin: 20px 0;
      transition: 0.4s;
      box-shadow: 0 10px 25px rgba(0,0,0,0.4);
    }

    .project:hover {
      transform: translateY(-10px) scale(1.02);
      box-shadow: 0 0 25px #00e5ff;
    }

    .social-icons a {
      font-size: 32px;
      margin: 10px;
      color: #00e5ff;
      transition: 0.3s;
    }

    .social-icons a:hover {
      transform: scale(1.2);
      color: #ffffff;
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<header>
  <img src="my_photo.png">
  <h1>Eng. Abdulaziz Elngar</h1>
</header>

<section>
  <h2>About Me</h2>
  <p>
I am a Computer Science student at Innovation University, passionate about building modern and efficient software solutions. I work as a Web Developer using HTML, CSS, JavaScript, PHP, and MySQL, with a strong focus on creating responsive, user-friendly, and well-structured websites.

I am also on my way to becoming a Mobile Application Developer using Flutter, aiming to build cross-platform applications with high performance and clean UI/UX. In addition, I have a growing interest in the field of Data Analysis, where I seek to transform raw data into meaningful insights that support decision-making.

I use tools such as VS Code and GitHub in my daily workflow and follow best practices in version control, clean code, and problem-solving. I am highly motivated to continuously learn new technologies, improve my technical skills, and work on real-world projects that make an impact.
  </p>
</section>

<section>
  <h2>Technical Skills</h2>
  <div class="skills">

    <div class="skill-item"><i class="fa-brands fa-html5"></i><p>HTML5</p></div>
    <div class="skill-item"><i class="fa-brands fa-css3-alt"></i><p>CSS3</p></div>
    <div class="skill-item"><i class="fa-brands fa-js"></i><p>JavaScript</p></div>
    <div class="skill-item"><i class="fa-brands fa-php"></i><p>PHP</p></div>
    <div class="skill-item"><i class="fa-solid fa-database"></i><p>MySQL</p></div>
<div class="skill-item">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Google-flutter-logo.png" alt="Flutter" style="width:40px; display:block; margin:0 auto;">
  <p>Flutter</p>
</div>
    <div class="skill-item"><i class="fa-brands fa-github"></i><p>GitHub</p></div>
    <div class="skill-item"><i class="fa-solid fa-code"></i><p>OOP</p></div>
    <div class="skill-item"><i class="fa-solid fa-network-wired"></i><p>REST APIs</p></div>
    <div class="skill-item"><i class="fa-solid fa-mobile-screen"></i><p>Responsive</p></div>

  </div>
</section>

<section>
  <h2>Projects</h2>

  <div class="project">
    <h3>Innovation Management System</h3>
    <p>Web-based system for managing university resources such as libraries, laboratories, and lecture halls.</p>
    <p><strong>Technologies:</strong> HTML, CSS, JavaScript, PHP, MySQL</p>
  </div>

  <div class="project">
    <h3>Personal Portfolio Website</h3>
    <p>A personal portfolio website to showcase my projects and skills.</p>
    <p><strong>Technologies:</strong> HTML, CSS, JavaScript</p>
  </div>

</section>

<section>
  <h2>Contact</h2>
  <div class="social-icons">
    <a href="mailto:abdelaziz.m.elnjjar@gmail.com"><i class="fa-solid fa-envelope"></i></a>
    <a href="tel:+201210959236"><i class="fa-solid fa-phone"></i></a>
    <a href="https://www.linkedin.com/in/abdulaziz-elngar-95a162383" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
    <a href="https://github.com/abdulaziz-elngr" target="_blank"><i class="fa-brands fa-github"></i></a>
  </div>
</section>

</body>
</html>