<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aayush Paswan's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Reset and Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Global Text Color */
        body {
            font-family: 'Roboto', sans-serif;
            color: #333;  /* Dark Gray Color for Text */
            background-color: black;
            line-height: 1.6;
            height: 100%;
            overflow-x: hidden;
        }

        /* Header Section */
        header {
            padding: 50px 20px;
            text-align: center;
            background: linear-gradient(135deg, #d3d3d3, #a8c0ff); /* Gray-LightBlue Gradient */
        }

        header h1 {
            font-size: 3rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
            color: #fff;  /* White color for the header text */
            text-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
        }

        /* Navigation Styles */
        nav {
            display: flex;
            justify-content: center;
            gap: 2rem;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 10px;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 10;
        }

        nav a {
            color: #fff;  /* White color for navigation links */
            font-size: 1.1rem;
            font-weight: 500;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            padding: 14px 20px;
            transition: background-color 0.3s, transform 0.3s;
        }

        nav a:hover {
            background-color: #ff6d00;
            color: #fff;  /* Keeping white color on hover */
            transform: translateY(-3px);
        }

        /* Section Styles */
        section {
            padding: 80px 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            margin-bottom: 2rem;
            transition: transform 0.3s ease;
            background: linear-gradient(135deg, #d3d3d3, #a8c0ff); /* Gray-LightBlue Gradient */
        }

        section h2 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            color: #333;  /* Dark Gray for section headers */
        }

        section p {
            font-size: 1.1rem;
            color: #555;  /* Darker Gray for paragraphs to stand out from the background */
            line-height: 1.7;
        }

        /* Hover Animation for Sections */
        section:hover {
            transform: translateY(-5px);
        }

        /* Image Styling */
        .profile-image {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            margin: 30px auto;
            border: 5px solid #fff;
            transition: transform 0.3s ease-in-out;
        }

        .profile-image:hover {
            transform: scale(1.1);
        }

        /* Button Styling */
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 30px;
            background-color: #ff6d00;
            color: #fff;  /* White color for button text */
            font-size: 1.2rem;
            font-weight: 500;
            border-radius: 30px;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 0 10px rgba(255, 109, 0, 0.6); /* Initial glowing effect */
        }

        .btn:hover {
            background-color: #2575fc;
            color: #fff;  /* White color on hover */
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(255, 109, 0, 0.8), 0 0 40px rgba(255, 109, 0, 0.6); /* Stronger glowing effect on hover */
            text-shadow: 0 0 10px rgba(255, 109, 0, 1), 0 0 20px rgba(255, 109, 0, 0.7); /* Text glow */
        }

        /* Contact Form Styling */
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 12px 15px;
            margin: 10px 0;
            border: 2px solid #333;
            background-color: #222;
            color: #333;  /* Dark Gray Text Color for form fields */
            font-size: 1.1rem;
            border-radius: 8px;
            outline: none;
            transition: all 0.3s ease;
        }

        .contact-form input:focus,
        .contact-form textarea:focus {
            border-color: #ff6d00;
            box-shadow: 0 0 10px rgba(255, 109, 0, 0.6);
        }

        .contact-form button {
            padding: 12px 25px;
            background-color: #2575fc;
            color: #fff;
            font-size: 1.2rem;
            font-weight: 500;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #ff6d00;
            color: #fff;
            transform: scale(1.05);
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.8);
            color: #fff;  /* White color for footer text */
            font-size: 1rem;
            letter-spacing: 1px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        /* Gallery Styles */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 30px;
        }

        .gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.4);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }

            nav a {
                padding: 10px 0;
            }

            section {
                padding: 60px 20px;
            }

            .profile-image {
                width: 150px;
                height: 150px;
            }

            .gallery {
                grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            }
        }

        /* Social Media Icons Styles */
        .social-icons {
            display: flex; /* Use flexbox to arrange icons in a row */
            justify-content: center; /* Center the icons */
            list-style: none; /* Remove default list styling */
            padding: 0; /* Remove padding */
            margin-top: 20px; /* Add some space above the icons */
        }

        .social-icons li {
            margin: 0 15px; /* Add space between icons */
            transition: transform 0.3s; /* Animation for scaling */
        }

        .social-icons a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 60px; /* Width of the icon container */
            height: 60px; /* Height of the icon container */
            border-radius: 50%; /* Circular background */
            text-decoration: none; /* Remove underline from links */
            color: #fff; /* Default color for icons */
            font-size: 1.5rem; /* Size of the icons */
            transition: background-color 0.3s, box-shadow 0.3s; /* Smooth background transition on hover */
            position: relative; /* Position for glowing effect */
        }

        /* Specific background colors for each social media platform */
        .social-icons a.facebook {
            background-color: #3b5998; /* Facebook Blue */
        }

        .social-icons a.whatsapp {
            background-color: #25D366; /* WhatsApp Green */
        }

        .social-icons a.instagram {
            background-color: #E1306C; /* Instagram Pink */
        }

        .social-icons a.email {
            background-color: #D44638; /* Email Red */
        }

        .social-icons a:hover {
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.5), 0 0 40px rgba(255, 255, 255, 0.3); /* Glowing effect */
        }

        .social-icons li:hover {
            transform: scale(1.1); /* Scale effect on hover */
        }

    </style>
</head>
<body>

    <header> <br></br>
        <h1>Aayush Portfolio</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#interests">Interests</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <p>I’m a passionate web developer. A curious mind with a passion for technology, constantly exploring the endless possibilities of coding and problem-solving. Explore my work and contact me for collaborations.</p>
        <a href="#contact" class="btn">Get In Touch</a>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="https://i.pinimg.com/736x/50/87/e7/5087e7cc2cb8b58a3c316074afcd4d39.jpg" alt="profile image" class="profile-image">
        <p>Hi! I'm Aayush Paswan, a Class 11 student with a deep passion for ethical hacking, web development, and software development. I am dedicated to learning new skills and building innovative projects.</p>
    </section>

    <!-- Interests Section -->
    <section id="interests">
        <h2>My Interests</h2>
        <p>In my free time, I enjoy watching anime, playing games, and learning programming languages. I love exploring the intersection of creativity and technology.</p>
        <div class="gallery">
            <img src="https://preview.redd.it/5n8hs34ztzk61.png?width=1080&crop=smart&auto=webp&s=7c2760d11d87d21107ba5acea68fd1461183b3a3" alt="Photography"> 
            <img src="https://wallpapercave.com/wp/wp11550270.jpg" alt="Gaming">
            <img src="https://backiee.com/static/wallpapers/1920x1080/386745.jpg" alt="Tech Exploration">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you’d like to work together or have any questions, please don’t hesitate to get in touch.</p>
        <form action="submit_form.php" method="POST" class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>

        <!-- Social Media Links -->
        <h2>Follow Us on Social Media</h2>
        <ul class="social-icons">
            <li><a href="https://www.facebook.com/share/1688d2SZgQ/" target="_blank" class="facebook"><i class="fab fa-facebook-f"></i></a></li>
            <li><a href="https://wa.me/9823722475" target="_blank" class="whatsapp"><i class="fab fa-whatsapp"></i></a></li>
            <li><a href="https://www.instagram.com/ab_ayush67?igsh=MXJuNHk4cDJyMWF5cA==" target="_blank" class="instagram"><i class="fab fa-instagram"></i></a></li>
            <li><a href="mailto:aayushpaswan359@gmail.com" target="_blank" class="email"><i class="fas fa-envelope"></i></a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Aayush Paswan. All rights reserved.</p>
    </footer>

</body>
</html>
