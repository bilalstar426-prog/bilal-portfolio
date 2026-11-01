<!DOCTYPE html>
<html>
<head>
  <title>bilal Portfolio</title>

  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: #0f172a;
      color: white;
    }

    header {
      text-align: center;
      padding: 40px;
      background: #1e293b;
    }

    h1 {
      margin: 0;
      font-size: 40px;
      color: #38bdf8;
      animation: fadeIn 1.5s ease-in-out;
    }

    section {
      margin: 20px;
      padding: 20px;
      background: #1e293b;
      border-radius: 10px;
    }

    span {
      background: #334155;
      padding: 5px 10px;
      border-radius: 5px;
      margin: 5px;
      display: inline-block;
    }

    .btn {
      background: #38bdf8;
      color: black;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      box-shadow: 0 0 10px #38bdf8;
    }

    a {
      text-decoration: none;
    }

    a[href^="tel"] {
      color: #38bdf8;
      font-weight: bold;
    }

    a[href^="mailto"] {
      color: #38bdf8;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>

<body>

  <header>
    <h1>mohamed bilal</h1>
    <p>B-TECH Student | AI & Web Developer</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      I am a passionate engineering student interested in Artificial Intelligence and Web Development.
      I love building smart and useful applications.
    </p>
  </section>

  <section>
    <h2>Skills</h2>
    <span>Python</span>
    <span>Java</span>
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
  </section>

  <section>
    <h2>Projects</h2>
    <p><b>Bus Booking System – Web Application</b></p>
    <p>
      A full-stack web application that allows users to search buses, view available routes, select seats, and book tickets online. The system provides a simple and responsive interface for users and stores booking data securely in a database.
    </p>
  </section>

  <section>
    <h2>Resume</h2>
    <!-- IMPORTANT: Replace resume.pdf with your uploaded file name -->
    <a href="="_blank">Download Resume</a>
  </section>

  <section>
    <p>📞 <a href="tel:8015399211">8015399211</a></p>
    <p>📧 <a href="bilalstar426@gmail.com">bilalstar426@gmail.com</a></p>
    <p>🔗 
      <a href="https://www.linkedin.com/in/mohamed-bilal01" target="_blank" style="color:#38bdf8; font-weight:bold;">
        View LinkedIn Profile
      </a>
    </p>
  </section>

</body>
</html>
