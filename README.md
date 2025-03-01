# Portfolio

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Karthik Marupaka | Portfolio</title>
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background: linear-gradient(135deg, #f0f2f5, #ffffff);
    }
    /* Header */
    header {
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #fff;
      padding: 20px 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    header h1 {
      font-size: 2.5em;
      letter-spacing: 2px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2em;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-size: 1em;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #d1d1d1;
    }
    /* Main container */
    .container {
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
    }
    /* Hero Section */
    .hero {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      margin-bottom: 40px;
    }
    .hero img {
      width: 250px;
      height: 250px;
      border-radius: 50%;
      margin: 20px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      animation: float 3s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    .hero-text {
      max-width: 600px;
      text-align: center;
    }
    .hero-text h2 {
      font-size: 2em;
      color: #764ba2;
      margin-bottom: 20px;
    }
    .hero-text p {
      font-size: 1.1em;
      margin-bottom: 20px;
      text-align: justify;
    }
    .links {
      margin: 20px 0;
    }
    .links a {
      display: inline-block;
      background-color: #28a745;
      color: #fff;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 5px;
      text-decoration: none;
      transition: background-color 0.3s;
      font-size: 1.1em;
    }
    .links a:hover {
      background-color: #218838;
    }
    /* Section Titles */
    .section-title {
      text-align: center;
      margin: 40px 0 20px;
      font-size: 2em;
      color: #667eea;
    }
    /* Certifications Section */
    .certifications {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-bottom: 40px;
      padding: 0 20px;
    }
    .certification-card {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }
    .certification-card:hover {
      transform: translateY(-10px);
    }
    .certification-card img {
      width: 100%;
      display: block;
    }
    .certification-card .card-body {
      padding: 15px;
    }
    .certification-card h3 {
      font-size: 1.2em;
      margin-bottom: 10px;
      color: #764ba2;
    }
    .certification-card p {
      font-size: 0.9em;
      color: #555;
    }
    /* Contact Section */
    .contact {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      margin: 40px 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .contact table {
      width: 100%;
      border-collapse: collapse;
    }
    .contact th, .contact td {
      padding: 10px;
      border: 1px solid #ddd;
      font-size: 1em;
    }
    .contact th {
      background-color: #667eea;
      color: #fff;
    }
    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background-color: #f1f1f1;
      margin-top: 40px;
    }
    /* Responsive adjustments */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2em;
      }
      .hero {
        flex-direction: column;
      }
      .hero img {
        margin-bottom: 20px;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Karthik Marupaka</h1>
    <p>Agile-Driven Project Manager | Scrum Master | Healthcare & IT Specialist</p>
    <nav>
      <a href="#about">About</a>
      <a href="#certifications">Certifications</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  
  <div class="container">
    <!-- Hero / About Section -->
    <section class="hero" id="about">
      <img src="img/Digital Photo_Karthik Marupaka.jpg" alt="Karthik Marupaka">
      <div class="hero-text">
        <h2>Welcome to My Portfolio</h2>
        <p>
          With over a decade of experience in project management, I excel in driving Agile and Scrum methodologies to achieve exceptional results. My expertise in healthcare and IT has empowered cross-functional teams to innovate and excel in dynamic environments.
        </p>
        <div class="links">
          <a href="resume.pdf" target="_blank">View Resume</a>
          <a href="https://www.credly.com/users/karthik-marupaka.b34212d7" target="_blank">Credly Certifications</a>
          <a href="https://www.linkedin.com/in/karthik-marupaka-01071525a/" target="_blank">LinkedIn Profile</a>
        </div>
      </div>
    </section>
    
    <!-- Certifications Section -->
    <section id="certifications">
      <h2 class="section-title">Certifications</h2>
      <div class="certifications">
        <div class="certification-card">
          <img src="img/Professional Scrum Master I_Karthik Marupaka.jpg" alt="PSM-I">
          <div class="card-body">
            <h3>PSM-I</h3>
            <p>Certified Professional Scrum Master from Scrum.org</p>
          </div>
        </div>
        <div class="certification-card">
          <img src="img/Professional Scrum Product Owner I_page-0001.jpg" alt="PSPO-I">
          <div class="card-body">
            <h3>PSPO-I</h3>
            <p>Certified Professional Scrum Product Owner from Scrum.org</p>
          </div>
        </div>
        <div class="certification-card">
          <img src="img/SAfe 6.0 Scrum Master_page-0001.jpg" alt="SSM">
          <div class="card-body">
            <h3>SSM</h3>
            <p>Scaled Scrum Master certification from Scaled Agile</p>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contact" class="contact">
      <h2 class="section-title">Contact Information</h2>
      <table>
        <tr>
          <th>Name</th>
          <th>Email</th>
          <th>Phone Number</th>
          <th>Licenses</th>
        </tr>
        <tr>
          <td>Karthik Marupaka</td>
          <td>karthikoct13@gmail.com</td>
          <td>905-783-8689</td>
          <td>PSM-I, PSPO-I, SSM, AZ-900, JIRA Fundamentals</td>
        </tr>
      </table>
    </section>
  </div>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Karthik Marupaka. All rights reserved.</p>
  </footer>
</body>
</html>
