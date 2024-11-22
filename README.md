<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Java Developer Portfolio</title>
  <style>
    /* Overall Page Style */
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f7fc;
      color: #333;
      margin: 0;
      padding: 20px;
      box-sizing: border-box;
    }
    h1, h2, h3 {
      color: #4CAF50;
      text-align: center;
    }

    /* Header */
    .header {
      background: linear-gradient(45deg, #4CAF50, #388E3C);
      color: white;
      padding: 40px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    /* 3D Card Effect */
    .card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin: 20px auto;
      padding: 20px;
      max-width: 80%;
      transform: perspective(600px);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: perspective(600px) rotateY(10deg) scale(1.05);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
    }

    /* Section Styling */
    .container {
      max-width: 1100px;
      margin: 30px auto;
      padding: 20px;
    }
    .section-title {
      font-size: 2em;
      color: #333;
    }
    .content {
      font-size: 1.1em;
      line-height: 1.6;
      color: #666;
    }

    /* Skill Tags */
    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
    }
    .tech-stack .tech {
      background-color: #388E3C;
      color: white;
      padding: 10px 20px;
      border-radius: 50px;
      font-weight: bold;
      text-transform: uppercase;
      transition: background-color 0.3s ease;
    }
    .tech-stack .tech:hover {
      background-color: #4CAF50;
      cursor: pointer;
    }

    /* Animation */
    @keyframes bounce {
      0% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
      100% { transform: translateY(0); }
    }

    /* Footer Styling */
    .footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9em;
      color: #888;
      animation: bounce 1s infinite;
    }

    /* Badge Styling */
    .badge {
      display: inline-block;
      background-color: #3c8dbc;
      color: white;
      padding: 5px 15px;
      border-radius: 20px;
      font-size: 1.1em;
      margin-top: 10px;
    }

    /* Button Styling */
    .contact-btn {
      background-color: #4CAF50;
      color: white;
      padding: 10px 20px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      text-transform: uppercase;
      display: inline-block;
      transition: background-color 0.3s ease;
    }
    .contact-btn:hover {
      background-color: #388E3C;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <div class="header">
    <h1>Welcome to My Java Developer Portfolio</h1>
    <p>Building Scalable and Efficient Applications with Java</p>
  </div>

  <!-- About Me Section -->
  <div class="container">
    <div class="card">
      <h2 class="section-title">About Me</h2>
      <p class="content">
        Hi, I'm <strong>[Your Name]</strong>, a passionate Java developer with a strong focus on building scalable, high-performance backend systems using Java and related technologies.
      </p>
    </div>
  </div>

  <!-- Technologies Section -->
  <div class="container">
    <div class="card">
      <h2 class="section-title">Technologies I Use</h2>
      <div class="tech-stack">
        <div class="tech">Java</div>
        <div class="tech">Spring Boot</div>
        <div class="tech">Hibernate</div>
        <div class="tech">Git</div>
        <div class="tech">Docker</div>
        <div class="tech">JUnit</div>
        <div class="tech">AWS</div>
        <div class="tech">Maven</div>
      </div>
    </div>
  </div>

  <!-- Projects Section -->
  <div class="container">
    <div class="card">
      <h2 class="section-title">Projects</h2>
      <p class="content">
        Here are a few of the exciting projects I've worked on:
      </p>
      <ul class="content">
        <li><strong>Project Name 1</strong>: A microservices-based e-commerce platform built with Java, Spring Boot, and MySQL.</li>
        <li><strong>Project Name 2</strong>: A full-stack application for task management with React.js and Spring Boot.</li>
      </ul>
    </div>
  </div>

  <!-- Contact Section -->
  <div class="container">
    <div class="card">
      <h2 class="section-title">Contact Me</h2>
      <p class="content">Feel free to reach out for collaborations, questions, or just to connect:</p>
      <a href="mailto:your.email@example.com" class="contact-btn">Email Me</a>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <p>&copy; 2024 [Your Name]. All rights reserved.</p>
  </div>

</body>
</html>
