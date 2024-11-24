# My-Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* CSS Boilerplate */

        
        * {
            box-sizing: border-box; 
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Roboto', sans-serif; 
            line-height: 1.6; 
            background-color: #f4f4f4; 
            color: #333; /* Default text color */
        }

        /* Header */
        header {
            background-color: #2E86C1; 
            color: white;
            padding: 20px;
            text-align: center;
        }

        img.profile {
            max-width: 150px;
            border-radius: 50%;
            margin: 20px 0;
        }

        /* Upper Section */
        .upper-section {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            margin: 10px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .upper-section div {
            flex: 1;
            margin: 0 10px;
            text-align: center;
        }

        /* Headings */
        h2 {
            color: #C0392B; /* A rich red to convey passion and creativity */
        }

        /* Buttons */
        button {
            background-color: #27AE60; 
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            margin-top: 10px;
        }

        button:hover {
            background-color: #2ECC71; 
        }

        /* Links */
        a {
            color: #2E86C1; 
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Contact Form */
        .contact-form {
            display: flex;
            flex-direction: column;
        }

        .contact-form input, .contact-form textarea {
            margin: 5px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* Footer */
        .footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px 0;
            background-color: #2E86C1; /* Keep footer consistent with header */
            color: white;
        }

        
        @media (max-width: 600px) {
            .upper-section {
                flex-direction: column;
            }
            .upper-section div {
                margin: 10px 0;
            }
            h2 {
                font-size: 1.5em;
            }
            button {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Austin Masaba </h1>
    <img src="YOUR_IMAGE_LINK" alt="My Profile Picture" class="profile">
</header>

<div class="upper-section">
    <div>
        <h2>About Me</h2>
        <p>I'm a passionate <strong>software engineer</strong> currently studying <strong>Computer Security and Forensics</strong> at Kabarak University. I love coding and exploring new technologies.</p>
    </div>
    <div>
        <h2>Interests</h2>
        <p>I enjoy <a href="https://www.google.com/search?q=traveling" target="_blank">traveling</a>, <a href="https://www.google.com/search?q=reading" target="_blank">reading</a>, and <a href="https://www.w3schools.com/" target="_blank">coding</a> in various languages including <a href="https://www.python.org/" target="_blank">Python</a>, <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">HTML</a>, <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank">CSS</a>, <a href="https://vitejs.dev/" target="_blank">Vite.js</a>, and <a href="https://reactjs.org/" target="_blank">React.js</a>.</p>
    </div>
    <div>
        <h2>Projects</h2>
        <p>Check out my external projects on <a href="https://github.com/Kipkoech78/Complete-Ecommerce" target="_blank">GitHub</a>.</p>
    </div>
</div>

<section>
    <h2>Contact Me</h2>
    <form class="contact-form" action="https://formspree.io/f/xwpknoad" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer class="footer">
    <p>&copy; 2024 My Portfolio</p>
</footer>

</body>
</html>
