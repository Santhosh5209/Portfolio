# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Santhosh Kumar - Personal Portfolio</title>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom right, rgba(238, 174, 202, 1), rgba(148, 187, 233, 1));
            color: #333;
            line-height: 1.6;
        }

        h1, h2, h3 {
            margin-bottom: 20px;
            color: #333;
        }

        h1 {
            font-size: 40px;
            font-weight: 700;
        }

        h2 {
            font-size: 30px;
            color: #2E3B4E;
        }

        h3 {
            font-size: 25px;
            color: #555;
        }

        p {
            font-size: 18px;
            margin-bottom: 20px;
            color: #444;
            line-height: 1.6;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 10px;
            font-size: 18px;
        }

        a {
            text-decoration: none;
            color: #fff;
            transition: all 0.3s ease;
        }

        a:hover {
            color: #FF5733;
        }

        /* Navigation Bar */
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav button {
            background-color: transparent;
            border: none;
            margin: 0 15px;
            font-size: 18px;
            font-weight: 600;
            color: #fff;
            cursor: pointer;
            padding: 10px 20px;
            border-radius: 5px;
            transition: all 0.3s ease;
        }

        nav button:hover {
            background-color: #FF5733;
            color: #fff;
        }

        /* Profile Picture */
        .profile-container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 100px;
        }

        .profile-container img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Content Sections */
        .section {
            max-width: 1200px;
            margin: 80px auto;
            padding: 40px 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section-header {
            text-align: center;
            margin-bottom: 30px;
        }

        .section-content {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .section-content div {
            width: 30%;
            margin-bottom: 20px;
        }

        .section-content div h3 {
            color: #FF5733;
            text-align: center;
        }

        .section-content ul {
            text-align: left;
        }

        .contact-form input {
            width: 100%;
            padding: 15px;
            border-radius: 5px;
            border: 1px solid #ddd;
            margin-bottom: 15px;
            font-size: 16px;
        }

        .contact-form button {
            background-color: #FF5733;
            color: #fff;
            font-size: 18px;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #333;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                align-items: center;
            }

            .section-content {
                flex-direction: column;
                align-items: center;
            }

            .section-content div {
                width: 80%;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav>
        <button><a href="#home">Home</a></button>
        <button><a href="#about">About</a></button>
        <button><a href="#skills">Skills</a></button>
        <button><a href="#interests">Interests</a></button>
        <button><a href="#contact">Contact</a></button>
    </nav>

    <!-- Profile Picture Section -->
    <div class="profile-container">
        <img src="santhoshpic.jpg" alt="Santhosh Kumar">
    </div>

    <!-- Home Section -->
    <div id="home" class="section">
        <div class="section-header">
            <h1>Hello, I am Santhosh Kumar</h1>
            <p>Student at Rajeev Gandhi Memorial College of Engineering and Technology</p>
        </div>
        <div class="section-content">
            <p>I am passionate about learning new technologies and improving my skills. I am always curious and motivated to work on various projects. I have acquired web development skills like HTML, CSS, and JavaScript.</p>
        </div>
    </div>

    <!-- About Section -->
    <div id="about" class="section">
        <div class="section-header">
            <h2>About Me</h2>
        </div>
        <div class="section-content">
            <div>
                <h3>Education</h3>
                <ul>
                    <li><strong>Rajeev Gandhi Memorial College of Engineering and Technology</strong> - B.Tech in Electronics and Communication, CGPA: 7.0</li>
                    <li><strong>Sri Chaitanya Junior College</strong> - Intermediate, MPC, Percentage: 75.2%</li>
                    <li><strong>Lakshmi EM High School</strong> - CGPA: 9.0</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Skills Section -->
    <!-- Skills Section -->
<div id="skills" class="section">
    <div class="section-header">
        <h2>Skills</h2>
    </div>
    <div class="section-content">
        <div>
            <h3>Web Development</h3>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </div>
        <div>
            <h3>Soft Skills</h3>
            <ul>
                <li>Critical Thinking</li>
                <li>Problem Solving</li>
                <li>Teamwork</li>
            </ul>
        </div>
    </div>
</div>

    <!-- Area of Interests Section -->
    <div id="interests" class="section">
        <div class="section-header">
            <h2>Area of Interests</h2>
        </div>
        <div class="section-content">
            <div>
                <h3>Web Development</h3>
                <p>I am deeply passionate about web development, continuously learning new technologies and trends to build efficient and responsive websites.</p>
            </div>
            <div>
                <h3>Data Analytics</h3>
                <p>Data analytics excites me because it allows me to derive insights from complex datasets and make data-driven decisions. I’m learning how to use various tools and techniques to process data.</p>
            </div>
        </div>
    </div>

    <!-- Technical Competencies Section -->
    <div id="technical-competencies" class="section">
        <div class="section-header">
            <h2>Technical Competencies</h2>
        </div>
        <div class="section-content">
            <div>
                <h3>Operating System</h3>
                <ul>
                    <li>Windows</li>
                </ul>
            </div>
            <div>
                <h3>Languages</h3>
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>Python</li>
                </ul>
            </div>
            <div>
                <h3>Databases</h3>
                <ul>
                    <li>MySQL</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="section">
        <div class="section-header">
            <h2>Contact Me</h2>
        </div>
        <div class="section-content">
            <div class="contact-form">
                <h3>Get In Touch</h3>
                <form>
                    <input type="text" placeholder="Enter Your Name">
                    <input type="email" placeholder="Enter Your Email">
                    <input type="text" placeholder="Enter Your Phone Number">
                    <button type="submit">Submit</button>
                </form>
            </div>
        </div>
    </div>

</body>
</html>
