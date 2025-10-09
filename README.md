# Project Responsive Web Design using Bootstrap
# Date:09.10.25
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Responsive Website</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    html {
      scroll-behavior: smooth;
    }
    /* Header Gradient */
    header {
      background: linear-gradient(135deg, #007bff, #6610f2);
      color: tomato;
      padding: 40px 0;
      text-align: center;
    }

    /* Navbar */
    .navbar {
      background-color: greenyellow;
    }
    .navbar a:hover {
      color: #ffc107 !important;
    }

    /* Sections */
    section {
      padding: 60px 0;
    }

    #about {
      background-color:hotpink;
      
    }
    #services {
      background-color: hotpink;
    }
    #contact {
      background-color: violet;
    }

    /* Card Hover Effect */
    .card {
      transition: transform 0.6s, box-shadow 0.3s;
      border: none;
      border-radius: 10px;
      overflow: hidden;
    }
    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 6px 20px blueviolet;
    }

    /* Footer */
    footer {
      background-color: indianred;
      color: darkgoldenrod;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>My Responsive Website</h1>
    <p class="lead">Designed beautifully with Bootstrap 5</p>
  </header>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Brand of ishwarya</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="text-center">
    <div class="container">
      <h2 class="mb-4 text-primary fw-bold">Welcome to Our Website</h2>
      <p class="lead mb-5">We design modern, colorful, and responsive websites that adapt beautifully to all devices.</p>
      <div class="row">
        <div class="col-md-4 col-sm-12 mb-4">
          <div class="card">
            <img src="Screenshot 2025-10-09 215005.png" class="card-img-top" alt="Modern Office Workspace">
            <div class="card-body">
              <h5 class="card-title text-primary">Modern Office</h5>
              <p class="card-text">A clean and minimal workspace for productivity.</p>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-12 mb-4">
          <div class="card">
            <img src="Screenshot 2025-10-09 215026.png" class="card-img-top" alt="Laptop and Coffee on Desk">
            <div class="card-body">
              <h5 class="card-title text-success">Laptop & Coffee</h5>
              <p class="card-text">The perfect setup for coding and creativity.</p>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-12 mb-4">
          <div class="card">
            <img src="Screenshot 2025-10-09 215257.png" class="card-img-top" alt="Person Using Smartphone">
            <div class="card-body">
              <h5 class="card-title text-danger">Smartphone User</h5>
              <p class="card-text">Stay connected anywhere, anytime.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <div class="container text-center">
      <h2 class="text-primary fw-bold">About Us</h2>
      <p class="lead mt-3">We are a passionate team of designers and developers creating high-quality digital experiences.</p>
      <p>Our mission is to make every project not only functional but also visually stunning and user-friendly.</p>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services">
    <div class="container text-center">
      <h2 class="text-success fw-bold">Our Services</h2>
      <div class="row mt-4">
        <div class="col-md-4">
          <h5>💻 Web Design</h5>
          <p>Creative and responsive web design tailored to your brand.</p>
        </div>
        <div class="col-md-4">
          <h5 background="hotpink">⚙ Development</h5>
          <p>Building reliable and high-performance web applications.</p>
        </div>
        <div class="col-md-4">
          <h5>📱 Mobile Friendly</h5>
          <p>All our designs are optimized for any screen size or device.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container text-center">
      <h2 class="text-warning fw-bold">Contact Us</h2>
      <p class="lead">We’d love to hear from you! Get in touch for any inquiries.</p>
      <p>Email: <strong>info@example.com</strong></p>
      <p>Phone: <strong>+91 98765 43210</strong></p>
      <button class="btn btn-primary mt-3">Send Message</button>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Responsive Website | Built with ❤ using Bootstrap</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
# OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-09 224803" src="https://github.com/user-attachments/assets/d138725e-9036-415d-a106-9a45f976d3a0" />
<img width="1920" height="1080" alt="Screenshot 2025-10-09 224748" src="https://github.com/user-attachments/assets/39eaf1de-03f5-4655-8025-85a16b1fac79" />

<img width="1920" height="1080" alt="Screenshot 2025-10-09 224803" src="https://github.com/user-attachments/assets/59b863c4-1f45-4602-a1d8-c045b3c02455" />





# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
