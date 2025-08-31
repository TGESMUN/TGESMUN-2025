# TGESMUN-2025
GES Madhapur Mun 2025
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TGES Madhapur MUN</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Logo -->
  <div class="logo">
    <img src="images/logo.png" alt="MUN Logo">
  </div>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="home.html">Home</a></li>
      <li><a href="resources.html">Resources</a></li>
      <li><a href="secretariat.html">Secretariat</a></li>
      <li><a href="registrations.html">Registrations</a></li>
      <li><a href="committees.html">Committees</a></li>
      <li><a href="allocation.html">Allocation Matrix</a></li>
    </ul>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="overlay"></div>
    <div class="hero-text">
      <h1>Welcome to TGES Madhapur MUN</h1>
      <h2>Global Agenda, Local Action</h2>
      <p>Be part of the solution.</p>
      <a href="https://forms.gle/gcxCrFbsD1n9YD5c7" target="_blank" class="btn">Register Now</a>
    </div>
  </section>
</body>
</html>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #fff;
  color: #333;
}

/* Logo */
.logo {
  text-align: center;
  background: #06284d;
  padding: 10px;
}
.logo img {
  height: 80px;
}

/* Navbar */
nav {
  background: #06284d;
  border-top: 2px solid #d4af37;
  border-bottom: 2px solid #d4af37;
}
nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  flex-wrap: wrap;
}
nav ul li {
  margin: 0 15px;
}
nav ul li a {
  text-decoration: none;
  color: #d4af37;
  font-weight: bold;
  font-size: 1rem;
  padding: 12px;
  transition: color 0.3s;
}
nav ul li a:hover {
  color: #fff;
}

/* Hero Section */
.hero {
  position: relative;
  background: url('images/hero.jpg') no-repeat center center/cover;
  height: 90vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.hero .overlay {
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: rgba(6,40,77,0.6);
}
.hero-text {
  position: relative;
  color: #d4af37;
  max-width: 800px;
  padding: 20px;
}
.hero-text h1 {
  font-size: 3rem;
  font-weight: bold;
  margin-bottom: 15px;
}
.hero-text h2 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}
.hero-text p {
  font-size: 1.2rem;
  margin-bottom: 20px;
  color: #fff;
}
.btn {
  background: #d4af37;
  color: #06284d;
  padding: 12px 25px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
  transition: background 0.3s;
}
.btn:hover {
  background: #fff;
}

