<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Manikanta Sai Pavan - Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(120deg, #232526, #414345);
      color: white;
    }
    .container {
      text-align: center;
      padding: 20px;
    }
    h1, h2 {
      margin: 10px 0;
      animation: fadeIn 2s ease-in-out;
    }
    p {
      font-size: 18px;
      animation: slideIn 1.5s ease-in-out;
    }
    .certifications img {
      width: 150px;
      height: auto;
      margin: 10px;
      transition: transform 0.3s;
    }
    .certifications img:hover {
      transform: scale(1.1);
    }
    .tech-stack div {
      display: inline-block;
      margin: 15px;
      text-align: center;
    }
    .tech-stack img {
      width: 70px;
      height: auto;
      transition: transform 0.3s;
    }
    .tech-stack img:hover {
      transform: scale(1.2);
    }
    .social-links a {
      text-decoration: none;
      color: white;
      margin: 0 10px;
      font-size: 24px;
      transition: transform 0.3s;
    }
    .social-links a:hover {
      transform: scale(1.2);
      color: #00acee;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes slideIn {
      from { opacity: 0; transform: translateX(-50px); }
      to { opacity: 1; transform: translateX(0); }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>👋 Hello, I'm TIPARANI MANIKANTA SAI PAVAN!</h1>
    <p>
      Harnessing the power of <strong>AWS</strong> and cutting-edge technologies to drive impactful solutions.
    </p>

    <h2>🎓 Certifications</h2>
    <div class="certifications">
      <a href="https://www.credly.com/badges/559c1cc5-609f-45de-8cc6-5a4dcae4815a/public_url" target="_blank">
        <img src="https://d1.awsstatic.com/logos/aws_logo_smile_1200x630.png" alt="AWS Cloud Practitioner">
      </a>
      <a href="https://www.credly.com/badges/cf16d0f4-a257-4fe9-9bc8-81f4e210a2c5/public_url" target="_blank">
        <img src="https://d1.awsstatic.com/logos/aws_logo_smile_1200x630.png" alt="AWS Solutions Architect">
      </a>
      <a href="https://www.credly.com/badges/ee574b74-8eca-4b10-95e8-dfd65300dbd1/public_url" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Red_Hat_Enterprise_Linux_Logo.svg" alt="Red Hat Certified Developer">
      </a>
    </div>

    <h2>🛠️ My Tech Stack</h2>
    <div class="tech-stack">
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
        <p>Java</p>
      </div>
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
        <p>React.js</p>
      </div>
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot">
        <p>Spring Boot</p>
      </div>
      <div>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB">
        <p>MongoDB</p>
      </div>
    </div>

    <h2>🌐 Let's Connect</h2>
    <div class="social-links">
      <a href="https://github.com/Pavan17-cpu" target="_blank"><i class="fab fa-github"></i></a>
      <a href="http://www.linkedin.com/in/manikanta-sai-pavan" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:mmsp13266@gmail.com"><i class="fas fa-envelope"></i></a>
    </div>
  </div>

</body>
</html>
