# Hassan Duffaydar
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="icon" type="image/png" href="path/to/favicon.png">
    <style>
        /* Global Styles */
        * {
            box-sizing: border-box;
        }

        body {
            background-color: #f5f5f5;
            color: #333;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px;
        }

        /* Header */
        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 60px;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        .profile-picture {
            width: 320px;
            height: 320px;
            border-radius: 50%;
            background-color: #ddd;
            /* Replace with your profile picture */
            background-image: url('images/profilepic.jpeg');
            background-size: cover;
            background-position: center;
        }

        /* Navigation */
        nav ul {
            display: flex;
            justify-content: center;
            margin-bottom: 60px;
        }

        nav ul li {
            margin-right: 40px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            font-size: 20px;
            transition: color 0.3s ease-in-out;
        }

        nav ul li a:hover {
            color: #ff7f50;
        }

        /* Sections */
        section {
            margin-bottom: 80px;
            padding-top: 80px;
            position: relative;
        }

        .section-heading {
            margin-bottom: 40px;
            font-size: 32px;
            text-transform: uppercase;
        }

        .section-content {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
        }

        .section-content .left-column {
            flex: 1;
            max-width: 50%;
        }

        .section-content .right-column {
            flex: 1;
            max-width: 40%;
            margin-top: 40px;
        }

        .section-content img {
            max-width: 100%;
            border-radius: 4px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .section-content p {
            line-height: 1.6;
            margin-bottom: 20px;
        }

        /* Contact Form */
        .contact-form {
            max-width: 500px;
            margin: 0 auto;
            text-align: center;
            position: relative;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
        }

        .contact-form button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #ff7f50;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out;
        }

        .contact-form button:hover {
            background-color: #ff6347;
        }

        .success-message {
            display: none;
            color: green;
            font-weight: bold;
            position: absolute;
            bottom: -30px;
            left: 50%;
            transform: translateX(-50%);
        }

        /* Social Links */
        .social-links {
            text-align: center;
            margin-top: 60px;
        }

        .social-links a {
            display: inline-block;
            margin: 0 10px;
            text-decoration: none;
            color: #333;
            background-color: #eee;
            padding: 12px 20px;
            border-radius: 4px;
            transition: transform 0.3s ease-in-out;
        }

        .social-links a:hover {
            transform: translateY(-3px);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        /* Animations */
        @keyframes fade-in {
            0% {
                opacity: 0;
            }

            100% {
                opacity: 1;
            }
        }

        @keyframes slide-up {
            0% {
                transform: translateY(50px);
                opacity: 0;
            }

            100% {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes slide-down {
            0% {
                transform: translateY(-50px);
                opacity: 0;
            }

            100% {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes rotate {
            0% {
                transform: rotate(0);
            }

            100% {
                transform: rotate(360deg);
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <header>
            <h1><img src="path/to/logo.png" alt="Logo" style="height: 40px;"></h1>
            <div class="profile-picture"></div>
        </header>

        <nav>
            <ul>
                <li><a href="#education">Education</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#about">About Me</a></li>
            </ul>
        </nav>

        <section id="education">
            <h2 class="section-heading">Education</h2>
            <div class="section-content">
                <div class="left-column">
                    <h3>University Degree</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod elit vel nibh efficitur
                        tincidunt. In hac habitasse platea dictumst.</p>
                </div>
                <div class="right-column">
                    <img src="path/to/education-image.jpg" alt="Education Image">
                </div>
            </div>
        </section>

        <section id="projects">
            <h2 class="section-heading">Projects</h2>
            <div class="section-content">
                <div class="left-column">
                    <h3>Project 1</h3>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod</p>
                </div
