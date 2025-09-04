<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaurav's Resume</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #eef2f7;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #004080, #0066cc);
      color: white;
      padding: 50px 20px;
      text-align: center;
    }
    header img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid white;
      object-fit: cover;
      margin-bottom: 15px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.3);
    }
    header h1 {
      margin: 10px 0 5px;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
      margin: 0;
    }
    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
    }
    section {
      background: white;
      margin-bottom: 20px;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    }
    h2 {
      margin-top: 0;
      color: #004080;
      border-left: 5px solid #004080;
      padding-left: 10px;
    }
    ul {
      padding-left: 20px;
    }
    ul li {
      margin-bottom: 8px;
    }
    .download-btn {
      display: inline-block;
      padding: 10px 20px;
      margin-top: 10px;
      background: #004080;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      transition: 0.3s;
    }
    .download-btn:hover {
      background: #0066cc;
    }
    .social-links {
      margin-top: 10px;
    }
    .social-links a {
      display: inline-block;
      margin-right: 15px;
      text-decoration: none;
      color: white;
      background: #004080;
      padding: 8px 14px;
      border-radius: 20px;
      font-weight: bold;
      transition: background 0.3s ease, transform 0.2s ease;
    }
    .social-links a:hover {
      background: #0066cc;
      transform: translateY(-3px);
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #004080;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <img src="profile.jpg" alt="Profile Photo">
    <h1>Gauravsinh Bhati</h1>
    <p>Electrical Engineer | Project Engineer</p>
  </header>

  <div class="container">
    <!-- About Me -->
    <section>
      <h2>About Me</h2>
      <p>
        I am an <strong>Electrical Engineer</strong> with over 5 years of professional experience, currently working at 
        <strong>CMS Computers Ltd.</strong> since September 2020. My expertise lies in 
        <strong>Smart City Projects</strong>, <strong>electrical supervision</strong>, and 
        <strong>project execution</strong>, with hands-on experience in advanced systems such as 
        Variable Message Displays (VMS), Adaptive Traffic Control Systems (ATCS), CCTV, Public Announcement Systems (PAS), 
        and Emergency Call Boxes (ECB).
      </p>
      <p>
        I have a strong foundation in <strong>Smart City Projects</strong>, demonstrated through my final year 
        engineering project on <em>IoT and automation</em>. I am passionate about integrating technology into 
        urban infrastructure to make cities smarter, safer, and more efficient.
      </p>
      <p>
        Known for my technical problem-solving skills, documentation expertise, and on-site project management, 
        I strive to deliver reliable and innovative solutions in the field of electrical and smart city engineering.
      </p>
    </section>

    <!-- Experience -->
    <section>
      <h2>Experience</h2>
      <ul>
        <li><strong>Project Engineer</strong> – CMS Computers Ltd. (28 Sep 2020 – Present)<br>
          Working on Smart City Projects including Variable Message Display (VMS), Adaptive Traffic Control System, CCTV, Public Announcement Systems, and Emergency Call Boxes (ECB). 
          Responsible for project execution, supervision, and documentation.
        </li>
        <li><strong>IoT Based Home Automation</strong> – Final Year Engineering Project (2020)<br>
          Developed a smart home automation system using IoT technology. The project allowed remote control of appliances through mobile applications and sensors, improving energy efficiency and user convenience.
        </li>
      </ul>
    </section>

    <!-- Education -->
    <section>
      <h2>Education</h2>
      <ul>
        <li>B.E. Electrical Engineering – Gujarat Technological University (GEC, Bhuj) – 2020</li>
        <li>12th Science - GSHSEB - 2016</li>
        <li>10th - GSHSEB - 2014</li>
      </ul>
    </section>

    <!-- Skills -->
    <section>
      <h2>Core Competencies</h2>
      <ul>
        <li>Smart City Project Implementation & Management</li>
        <li>Project Documentation & Reporting</li>
        <li>Variable Message Display (VMS)</li>
        <li>Adaptive Traffic Control Systems (ATCS)</li>
        <li>Public Announcement Systems (PAS)</li>
        <li>Emergency Call Boxes (ECB)</li>
        <li>CCTV</li>
      </ul>
    </section>

    <!-- Personal Details -->
    <section>
      <h2>Personal Details</h2>
      <ul>
        <li><strong>Date of Birth:</strong> 16 March 1999</li>
        <li><strong>Age:</strong> 25</li>
        <li><strong>Marital Status:</strong> Single</li>
        <li><strong>Nationality:</strong> Indian</li>
        <li><strong>Languages:</strong> English, Hindi, Gujarati</li>
        <li><strong>Address:</strong> Bhati Vas, Mejarpura, Vadgam, Banaskantha, Gujarat, India - 385421</li>
      </ul>
    </section>

    <!-- Contact -->
    <section>
      <h2>Contact</h2>
      <p>Email: <a href="mailto:gauravb091@gmail.com">gauravb091@gmail.com</a></p>
      <p>Phone: <a href="tel:+917874960769">+91-7874960769</a></p>
      <p>Address: Bhati Vas, Mejarpura, Vadgam, Banaskantha, Gujarat, India - 385421</p>
      <div class="social-links">
        <a href="https://www.linkedin.com/in/gauravsinh-bhati" target="_blank">LinkedIn</a>
        <a href="https://twitter.com/" target="_blank">Twitter</a>
      </div>
      <a href="resume.pdf" class="download-btn" download>📄 Download Resume</a>
    </section>
  </div>

  <footer>
    &copy; 2025 Gauravsinh Bhati | Resume Website
  </footer>
</body>
</html>
