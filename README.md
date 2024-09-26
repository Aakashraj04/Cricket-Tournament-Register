<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XYZ Cricket Tournaments</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@500;700&display=swap" rel="stylesheet">
    <style>
      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          font-family: 'Inter', sans-serif;
      }
      body {
          background-color: #191035;
          color: #fff;
          scroll-behavior: smooth; /* Default smooth scrolling */
      }
      .container {
        max-width: 1200px;
          margin: 0 auto;
          padding: 20px;
          display:  flex;
          justify-content: space-between;
          align-items: center;
          min-height: 100vh;
      }
      .text-section {
          max-width: 50%;
          margin-bottom: -100px;
          animation: fadeIn 5s;
      }
      .text-section h1 {
          font-size: 3rem;
          margin-bottom: 20px;
          font-family: myFont;
          src:url('C:\Users\SEC\Desktop\Cicket Register\Futura Heavy Italic font.ttf');
          
      }
      @keyframes fadeIn {
          0% { opacity: 0; }
          100% { opacity: 1; }
       }
      .text-section p {
          font-size: 1.2rem;
          line-height: 1.6;
          margin-bottom: 30px;
          opacity: 0.9;
          margin-left: -20px;
          margin-top: -20px;
      }
      .hashtag {
          background-color: #8d69f1;
          display: inline-block;
          padding: 10px 20px;
          border-radius: 25px;
          font-weight: 500;
          margin-bottom: 15px;
          margin-left: -20px;
      }
      .welcome {
        margin-left: -20px;
        margin-bottom: 35px;
        font-family: myFont;
          src:url('C:\Users\SEC\Desktop\Cicket Register\Futura Heavy Italic font.ttf');
      }
      .btn {
          display: inline-block;
          padding: 15px 30px;
          background-color: #fff;
          color: #000;
          border: none;
          border-radius: 50px;
          font-size: 1.2rem;
          font-weight: 700;
          text-decoration: none;
          display: flex;
          align-items: center;
          margin-left: -10px;
          margin-right: 425px;
          gap: 10px;
          transition: background-color 0.3s;
      }

      .btn:hover {
          background-color: #e6e6e6;
      }

      .btn svg {
          width: 20px;
          height: 20px;
      }

      /* Video background for home page */
      #home {
          position: cover;
          overflow: hidden;
      }
      #home video {
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          object-fit: cover;
          z-index: -1; /* Place the video behind the content */
      }
      .navbar {
          display: flex;
          justify-content: space-between;
          padding: 20px;
          color: white;
          position: fixed;
          top: 0;
          width: 100%;
          z-index: 1000;
      }

      .navbar ul {
          display: flex;
          list-style: none;
          margin-right: -700px;
          padding: 20px 20px;
      }

      .navbar ul li {
          margin: 0 15px;
      }

      .navbar ul li a {
          text-decoration: none;
          color: white;
          font-weight: 500;
          padding: 10px 15px;
          border-radius: 10px;
          transition: background-color 0.3s ease;
      }

      .navbar ul li a:hover {
          background-color: rgba(255, 255, 255, 0.2);
      }
      .navbar .logo h1{
        font-family: myFont;
        src:url('C:\Users\SEC\Desktop\Cicket Register\SIMPLIFICA Typeface.ttf');
      }
      .navbar .login {
          background-color: rgb(229, 251, 133);
          color: black;
          padding: 10px 20px;
          margin-top: 10px;
          margin-right: 20px;
          border-radius: 25px;
          font-weight: 900;
          height: fit-content;
          text-decoration: none;
      }

      section {
          padding: 80px 20px;
          min-height: 100vh;
      }
      #about-us {
        background-color: whitesmoke;
        color:#000;
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
        font-family: myFont;
        src:url('C:\Users\SEC\Desktop\Cicket Register\Raleway-VariableFont_wght.ttf');
        background-color: #ffffff;
        color: #000;
        }
        .about-us {
        text-align: center;
        padding: 50px 20px;
        }
        .aboutustitle{
            color: black;
            font-size: 2.5rem;
            font-weight: 500;
            padding-top: 50px;
            padding-bottom: 70px;
            text-align: center;
            font-family: myFont;
            src: url('C:\Users\SEC\Desktop\Cicket Register\SIMPLIFICA Typeface.ttf');
        }
.about-content {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 50px;
}
.about-content h2{
    font-size: 2.0rem;
    font-weight: 500;
    font-family: myFont;
    src: url('C:\Users\SEC\Desktop\Cicket Register\SIMPLIFICA Typeface.ttf');
}

.about-image-container {
  width: 45%;
  display: flex;
  justify-content: center;
  margin: 20px;
}

.about-image {
  width: 100%;
  border-radius: 50px;
  height: auto;
}
.about-text, .tournament-text {
  width: 45%;
  font-size: 1.2rem;
  line-height: 1.6;
  font-weight: 400;
  font-family: 'Roboto', sans-serif;
  padding: 20px;
}
.tournament-text h2{
    font-size: 2.5rem;
    font-weight: 500;
    font-family: myFont;
    src: url('C:\Users\SEC\Desktop\Cicket Register\SIMPLIFICA Typeface.ttf');
}
.left {
  justify-content: flex-start;
  text-align: center;
}

.right {
  justify-content: flex-end;
  text-align: center;
  font-family: myFont;
  src:url('C:\Users\SEC\Desktop\Cicket Register\Fontspring-DEMO-theseasons-bdit.otf');
}

/* Zigzag Flexbox Layout for Paragraphs and Images */
.zigzag-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.zigzag-container .about-text .para1{
  order: 1; /* Paragraphs on the left */
  font-family: myFont;
  src:url('C:\Users\SEC\Desktop\Cicket Register\Fontspring-DEMO-theseasons-bdit.otf');
}

.zigzag-container .about-image-container {
  order: 2; /* Images on the right */
}

.zigzag-container:nth-child(even) .about-text {
  order: 2; /* On even containers, reverse the order */
  text-align: center;
  font-family: myFont;
  src:url('C:\Users\SEC\Desktop\Cicket Register\Fontspring-DEMO-theseasons-bdit.otf');
}

.zigzag-container:nth-child(even) .about-image-container {
  order: 1; /* On even containers, reverse the order */
}

/* Media Queries for Smaller Screens */
@media (max-width: 768px) {
  .about-content {
    flex-direction: column;
  }

  .about-text, .tournament-text{
    width: 90%;
    text-align: center;
    margin-bottom: 20px;
    font-family: myFont;
    src:url('C:\Users\SEC\Desktop\Cicket Register\Raleway-Italic-VariableFont_wght.ttf');
  }
  .about-image-container {
    width: 90%;
  }
}         
      }
      #contact {
        background-color: #fff;
        background-image: url('contactbg1.jpg'); /* Add a serene background image */
        margin-top: 30px;
            background-size: cover;
            background-position: center;
        body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: black;
}
        .contact-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin-top: 50px;   
            padding: 0 20px;
            box-sizing:border-box;
        }
        .contact-info {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 35px ;
    margin-bottom: 175px;
    max-width: 400px;
    border-radius: 100px;
    margin-right: 500px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .contact-info h2 {
    font-size: 25px;
    margin-bottom: 50px;
    margin-left: 70px;
    color: #333;
        }
        .contact-info p {
    font-size: 16px;
    margin-left: -100px;
    color: #555;
    margin: 10px 0;
}

.social-media {
    margin-top: 20px;
}

.social-media a {
    color: #333;
    text-decoration: none;
    margin-right: 10px;
}

.social-media a:hover {
    text-decoration: underline;
}

/* Right Side: Contact Form */
.contact-form {
    background-color: rgba(255, 255, 255, 0.8);
    padding: 40px 50px;
    margin-bottom: 200px;
    max-width: 500px;
    width: 100%;
    border-radius: 50px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.contact-form h2 {
    font-size: 24px;
    margin-bottom: 20px;
    margin-left: 100px;
    color: #333;
}

.input-group {
    margin-bottom: 20px;
}

.input-group input,
.input-group textarea {
    width: 100%;
    padding: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

textarea {
    resize: none;
    height: 120px;
}

/* Subtle Button */
.btn {
    padding: 10px 40px;
    background-color: #5cb85c;
    color: white;
    border: none;
    border-radius: 50px;
    margin-left: 130px;
    font-size: 14px;
    cursor: pointer;
}

.btn:hover {
    background-color: #4cae4c;
}

/* Responsive Design */
@media (max-width: 768px) {
    .contact-container {
        flex-direction: column;
    }

    .contact-info {
        margin-bottom: 20px;
    }
}
      }
      h2 {
          font-size: 2.5rem;
          margin-bottom: 20px;
          font-family: myFont;
          src:url('C:\Users\SEC\Desktop\Cicket Register\SIMPLIFICA Typeface.ttf');
          margin-left: 250px;
          margin-top: 50px;
          color:black;
      }
      .text-section1 p{
        color:black;
        text-align: center;
        font-size: x-large;
      }
      .logo {
          display: flex;
          align-items: center;
      }
      .logo img {
          width: 90px;
          height: 90px;
          margin-left: 5px;
      }
      .button {
  border-radius:20px; ;
  color: white;
  padding: 5px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

.button1 {background-color: #1877F2;}
.button2 {background-color:  #ee2a7b;}
    </style>
</head>
<body>
    <!-- Navbar Section -->
    <nav class="navbar">
        <div class="logo">
            <img src="logo.png" alt="Logo"> <!-- Add your logo file -->
            <h1>XYZ Organization</h1>
        </div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about-us">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <a href="login.html" class="login">Log In</a>
    </nav>

    <!-- Main Section with Video Background -->
    <div class="container" id="home">
        <video id="background-video" muted loop>
            <source src="https://gopani9-my.sharepoint.com/personal/st_gopani9_onmicrosoft_com/_layouts/15/download.aspx?share=EeF1GuEeoq9MgowptfBHNOwBYHyXjKgKg71LMX0UMi5Rnw" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <div class="text-section">
            <div class="hashtag">#crickettournaments</div>
            <div class="welcome"><h1>Welcome to the XYZ Cricket Tournaments</h1></div>
            <p>
                Welcome to the ultimate destination for cricket lovers! XYZ Cricket Organization is proud to present exciting cricket tournaments where teams of all levels can come together to showcase their talent and passion for the game. Whether you're an amateur player or a seasoned pro, our tournaments are designed to bring out the best in you!
            </p>
            <a href="login.html" class="btn">
                Sign Up
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
            </a>
        </div>
    </div>

    <!-- About Us Section -->
    <section id="about-us" class="about-us" >
        <h2 class="aboutustitle">ABOUT US</h2>
        <!-- First Image on Right and Paragraph on Left -->
        <div class="about-content zigzag-container">
          <div class="about-text left">
            <p class="para1">
                Welcome to XYZ Sports Organization, where we are passionate about promoting the spirit of cricket through engaging tournaments that bring together players, fans, and communities. Established with a vision to enhance the experience of cricket enthusiasts, our organization focuses on creating competitive platforms for both amateur and professional players.
            </p>
          </div>
          <div class="about-image-container right">
            <img src="aboutusimg1.png" alt="Cricket Players" class="about-image image1">
          </div>
        </div>
    
        <!-- Second Image on Left and Paragraph on Right -->
        <div class="about-content zigzag-container">
          <div class="about-image-container left">
            <img src="aboutusimg2.png" alt="Cricketer Batting" class="about-image image2">
          </div>
          <div class="tournament-text right">
            <p>
                <h2>Our Mission</h2><br>
                Our mission is to organize high-quality cricket tournaments that inspire athletes and create unforgettable moments for players and spectators alike. We aim to support emerging talents by providing them with opportunities to showcase their skills on a larger stage.
            </p>
          </div>
        </div>
    
        <!-- Third Image on Right and Paragraph on Left -->
        <div class="about-content zigzag-container">
          <div class="about-text left">
            <p>
                <h2>Exciting Tournaments</h2>Participate in a variety of tournaments tailored to different skill levels, ensuring everyone has a chance to play.<br><br>
                <h2>Professional Management</h2>Our experienced team is dedicated to organizing events that run smoothly, prioritizing player safety and enjoyment.<br><br>
                <h2>Community Engagement</h2>We actively engage with local communities to promote cricket and foster a love for the game among all age groups.
            </p>
          </div>
          <div class="about-image-container right">
            <img src="aboutusimg4.png" alt="Cricket Celebration" class="about-image image3">
          </div>
        </div>
      </section>

    <!-- Contact Us Section -->
    <section id="contact">
        <div class="contact-container">
            <!-- Left side: Contact details and social media links -->
            <div class="contact-info">
                <h2>Contact US</h2>
                <p><strong>&nbsp;&nbsp;&nbsp;&nbsp;Address:</strong> 123 Skyline Tower,US</p>
                <p><strong>&nbsp;&nbsp;&nbsp;&nbsp;Phone:</strong> +1 800 123 4567</p>
                <p><strong>&nbsp;&nbsp;&nbsp;&nbsp;Email:</strong> contact@example.com</p>
                <div class="social-media">
                    <button class="button button1" type="button" onclick="window.location.href='https://facebook.com/xyzsportsorganization'" >Facebook</button>
                    <button class="button button2" type="button" onclick="window.location.href='https://instagram.com/xyzsportsorganization'" >Instagram</button>
                </div>
            </div>
    
            <!-- Right side: Contact form -->
            <div class="contact-form">
                <h2>Send  us a message</h2>
                <form id="contact-form">
                    <div class="input-group">
                        <input type="text" id="name" placeholder="Your Name" required>
                    </div>
                    <div class="input-group">
                        <input type="email" id="email" placeholder="Your Email" required>
                    </div>
                    <div class="input-group">
                        <textarea id="message" placeholder="Your Message" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </div>
    </section>
    <script>
        // JavaScript for slow-motion smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                window.scrollTo({
                    top: target.offsetTop,
                    behavior: 'smooth',
                    duration: 2000 // Slow down scrolling (2000 ms = 2 seconds)
                });
            });
        });
        document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault(); // Prevent the form from submitting

    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    if (name && email && message) {
        alert("Message sent successfully!");
        document.getElementById('contact-form').reset(); // Clear the form
    } else {
        alert("Please fill in all fields.");
    }
});
document.addEventListener('DOMContentLoaded', function () {
    const navbar = document.querySelector('nav');
    const navLinks = document.querySelectorAll('nav ul li a'); // Select all the nav links
    const homeSection = document.querySelector('#home');
    const aboutUsSection = document.querySelector('#about-us');
    const contactSection = document.querySelector('#contact');

    function updateNavbarColor() {
        const homeBottom = homeSection.offsetTop + homeSection.offsetHeight;
        const aboutUsBottom = aboutUsSection.offsetTop + aboutUsSection.offsetHeight;

        if (window.scrollY >= homeBottom && window.scrollY < aboutUsBottom) {
            // Change navbar text and link colors to black in 'About Us' section
            navbar.style.color = 'black';
            navLinks.forEach(link => {
                link.style.color = 'black'; // Change each link color to black
            });
        } else if (window.scrollY >= aboutUsBottom) {
            // Change navbar text and link colors back to white in 'Contact' section
            navbar.style.color = 'white';
            navLinks.forEach(link => {
                link.style.color = 'white'; // Change each link color to white
            });
        } else {
            // Default navbar text and link colors for other sections
            navbar.style.color = 'white';
            navLinks.forEach(link => {
                link.style.color = 'white'; // Change each link color to white
            });
        }
    }

    // Update navbar color when the page is scrolled
    window.addEventListener('scroll', updateNavbarColor);

    // Smooth scroll behavior when clicking navigation links
    const links = document.querySelectorAll('nav a');
    links.forEach(link => {
        link.addEventListener('click', function (e) {
            e.preventDefault();
            const targetId = this.getAttribute('href');
            document.querySelector(targetId).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });
});
let prevScrollPos = window.pageYOffset;
  const navbar = document.querySelector(".navbar");
  let isScrolling;

  // Detect scroll and hide the navbar when scrolling down or up
  window.addEventListener('scroll', () => {
    let currentScrollPos = window.pageYOffset;

    // Hide navbar when scrolling (down or up)
    navbar.style.top = "-80px"; // Adjust this value to match your navbar's height

    prevScrollPos = currentScrollPos;

    // Clear the previous timeout if scrolling continues
    clearTimeout(isScrolling);

    // Set a timeout to show the navbar after scrolling stops
    isScrolling = setTimeout(() => {
      navbar.style.top = "0"; // Show navbar after user stops scrolling
    }, 200); // Adjust the delay based on preference
  });
  const video = document.getElementById('background-video');
    video.play().catch(error => {
        console.error('Error trying to play the video:', error);
    });
    </script>
</body>
</html>
