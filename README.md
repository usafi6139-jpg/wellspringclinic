# well-spring-clinic
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WellSpring Family Clinic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>WellSpring Family Clinic</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a
/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

/* Header */
header {
  background: #0077b6;
  color: white;
  padding: 15px;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 15px;
  padding: 0;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

/* Hero Section */
.hero {
  background: #caf0f8;
  text-align: center;
  padding: 50px 20px;
}

/* Footer */
footer {
  background: #03045e;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Services - WellSpring Clinic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Services</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="appointment.html">Appointments</a></li>
        <li><a href="bmi.html">BMI Calculator</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section>
    <h2>Healthcare Services</h2>
    <ul>
      <li>General Check-ups</li>
      <li>Pediatrics</li>
      <li>Women’s Health</li>
      <li>Vaccinations</li>
      <li>Chronic Disease Management</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 WellSpring Family Clinic</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Appointment - WellSpring Clinic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Book an Appointment</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="appointment.html">Appointments</a></li>
        <li><a href="bmi.html">BMI Calculator</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="form-section">
    <h2>Schedule Your Visit</h2>
    <form>
      <label for="name">Full Name:</label>
      <input type="text" id="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" required>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BMI Calculator - WellSpring Clinic</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>
  <header>
    <h1>BMI Calculator</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="appointment.html">Appointments</a></li>
        <li><a href="bmi.html">BMI Calculator</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="form-section fade-in">
    <h2>Check Your BMI</h2>
    <label for="weight">Weight (kg):</label>
    <input type="number" id="weight">

    <label for="height">Height (cm):</label>
    <input type="number" id="height">

    <button onclick="calculateBMI()">Calculate</button>
    <p id="bmi-result"></p>
  </section>

  <footer>
    <p>&copy; 2025 WellSpring Family Clinic</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - WellSpring Clinic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>About Us</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="appointment.html">Appointments</a></li>
        <li><a href="bmi.html">BMI Calculator</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="about fade-in">
    <img src="images/clinic.jpg" alt="WellSpring Clinic Building">
    <h2>Who We Are</h2>
    <p>
      WellSpring Family Clinic has been serving the community for over 15 years.
      Our mission is to provide compassionate healthcare for families, blending
      modern medical practices with personal care. 
    </p>
  </section>

  <footer>
    <p>&copy; 2025 WellSpring Family Clinic</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - WellSpring Clinic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="appointment.html">Appointments</a></li>
        <li><a href="bmi.html">BMI Calculator</a></li>
        <li><a href="about.html">About Us</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="form-section">
    <h2>Get in Touch</h2>
    <form>
      <label for="name">Full Name:</label>
      <input type="text" id="name">

      <label for="email">Email:</label>
      <input type="email" id="email">

      <label for="message">Message:</label>
      <textarea id="message"></textarea>

      <button type="submit">Send Message</button>
    </form>

    <h3>Find Us</h3>
    <iframe src="https://maps.google.com/maps?q=New%20York&t=&z=13&ie=UTF8&iwloc=&output=embed"
      width="100%" height="250" style="border:0;" allowfullscreen></iframe>
  </section>

  <footer>
    <p>&copy; 2025 WellSpring Family Clinic</p>
  </footer>
</body>
</html>
function calculateBMI() {
  let weight = document.getElementById("weight").value;
  let height = document.getElementById("height").value;

  if (weight > 0 && height > 0) {
    let bmi = (weight / ((height / 100) ** 2)).toFixed(2);
    let message = "";

    if (bmi < 18.5) {
      message = "Underweight 😔";
    } else if (bmi < 24.9) {
      message = "Normal weight 🙂";
    } else if (bmi < 29.9) {
      message = "Overweight 😐";
    } else {
      message = "Obese 😟";
    }

    document.getElementById("bmi-result").innerText = `Your BMI is ${bmi} (${message})`;
  } else {
    alert("Please enter valid values!");
  }
}
/* Animations */
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeIn 1.5s forwards;
}

@keyframes fadeIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Forms */
form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  max-width: 400px;
  margin: auto;
}

form input, form textarea, form button {
  padding: 10px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

form button {
  background: #0077b6;
  color: white;
  cursor: pointer;
  transition: background 0.3s;
}

form button:hover {
  background: #023e8a;
}

/* Image Styling */
.about img {
  max-width: 100%;
  border-radius: 10px;
  margin-bottom: 20px;
}
