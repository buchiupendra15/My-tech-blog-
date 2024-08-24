<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Tech Blog</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
            color: #eaeaea;
        }
        header {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 20px 0;
            text-align: center;
            border-bottom: 4px solid #1abc9c;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            overflow: hidden;
        }
        .main-content {
            float: left;
            width: 70%;
            background: #1e1e1e;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            border-radius: 8px;
            margin-right: 20px;
        }
        .sidebar {
            float: right;
            width: 25%;
            background: #1e1e1e;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            border-radius: 8px;
        }
        .sidebar h3 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            color: #ecf0f1;
            margin-bottom: 15px;
        }
        .slider {
            position: relative;
            overflow: hidden;
            width: 100%;
            height: 200px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            margin-bottom: 20px;
        }
        .slides {
            display: flex;
            transition: transform 0.5s ease-in-out;
            width: 100%;
        }
        .slide {
            min-width: 100%;
            box-sizing: border-box;
            padding: 20px;
        }
        .slide img {
            width: 100%;
            border-radius: 8px;
        }
        .slide p {
            text-align: center;
            color: #ecf0f1;
        }
        .navigation {
            position: absolute;
            top: 50%;
            width: 100%;
            display: flex;
            justify-content: space-between;
            transform: translateY(-50%);
        }
        .navigation button {
            background: #3498db;
            border: none;
            color: #fff;
            padding: 10px;
            border-radius: 50%;
            cursor: pointer;
        }
        .navigation button:hover {
            background: #2980b9;
        }
        footer {
            clear: both;
            background: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 15px 0;
            position: relative;
            bottom: 0;
            width: 100%;
            border-top: 4px solid #1abc9c;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .tags a {
            background: #3498db;
            color: #fff;
            padding: 5px 10px;
            margin-right: 5px;
            border-radius: 5px;
            text-decoration: none;
        }
        .tags a:hover {
            background: #2980b9;
        }
        .recent-posts {
            margin-top: 40px;
        }
        .recent-posts h3 {
            color: #ecf0f1;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .recent-posts ul {
            list-style: none;
            padding: 0;
        }
        .recent-posts ul li {
            margin-bottom: 10px;
        }
        .recent-posts ul li a {
            color: #3498db;
            text-decoration: none;
        }
        .recent-posts ul li a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Tech Blog</h1>
        </div>
    </header>

    <div class="container">
        <div class="main-content">
            <!-- Slider Section -->
            <div class="slider">
                <div class="slides">
                    <div class="slide">
                        <img src="profile1.jpg" alt="Profile Image 1">
                        <p>Hi, I'm Buchi Venkata Naga Upendra, a web developer with a passion for creating intuitive and visually engaging websites. I have expertise in both front-end and back-end technologies, and I love exploring new trends in web development.</p>
                    </div>
                    <div class="slide">
                        <img src="profile2.jpg" alt="Profile Image 2">
                        <p>With knowledge and other kinds of experience in the industry, I focus on crafting user-centered designs and robust web applications. I enjoy sharing knowledge and insights through my blog to help others in the tech community.</p>
                    </div>
                </div>
                <div class="navigation">
                    <button onclick="prevSlide()">&#10094;</button>
                    <button onclick="nextSlide()">&#10095;</button>
                </div>
            </div>

            <!-- Blog Post Section -->
            <div class="post">
                <h2>Understanding Web Development: A Comprehensive Guide</h2>
                <p><strong>By Buchi Venkata Naga Upendra</strong> | August 17, 2024</p>
                <p>Web development is a dynamic and essential field focused on building and maintaining websites and web applications. It involves various disciplines, each contributing to the creation of a functional and visually appealing digital presence.</p>
                <p><strong>Front-End Development:</strong> This area focuses on the client side of web development, where developers use languages like HTML, CSS, and JavaScript to build the layout, design, and interactive elements of a website. Modern front-end frameworks like React, Vue, and Angular further enhance these capabilities.</p>
                <p><strong>Back-End Development:</strong> Here, developers work on the server side, dealing with databases, server logic, and application integration. Technologies like Node.js, Ruby on Rails, and Django are commonly used to handle data processing and server-side scripting.</p>
                <p><strong>Full-Stack Development:</strong> Full-stack developers are proficient in both front-end and back-end technologies. They can build and maintain both the user-facing aspects and server-side functionalities, offering a holistic approach to web development.</p>
                <p>The field is continuously evolving, with emerging trends like serverless architecture, progressive web apps (PWAs), and API-first development shaping the future. Staying updated with these advancements is crucial for creating innovative and effective web solutions.</p>
                <div class="tags">
                    <a href="#">Web Development</a>
                    <a href="#">Front-End</a>
                    <a href="#">Back-End</a>
                    <a href="#">Full-Stack</a>
                </div>
            </div>

            <!-- Additional Blog Post Section -->
            <div class="post">
                <h2>Exploring Modern Front-End Technologies</h2>
                <p><strong>By Buchi Venkata Naga Upendra</strong> | August 16, 2024</p>
                <p>Modern front-end development has seen significant advancements with the rise of powerful frameworks and tools. This post delves into the latest technologies like React, Vue, and Angular, and their impact on creating dynamic and responsive user interfaces.</p>
                <p>React, developed by Facebook, is known for its component-based architecture and virtual DOM, making it highly efficient for building complex applications. Vue offers a more approachable and flexible framework with its easy integration and progressive features. Angular, maintained by Google, provides a robust platform with a comprehensive set of tools for building large-scale applications.</p>
                <p>Understanding these technologies and their ecosystems can help developers choose the right tool for their projects and enhance their skill set in the ever-evolving landscape of web development.</p>
            </div>

            <!-- Recent Posts Section -->
            <div class="recent-posts">
                <h3>Recent Posts</h3>
                <ul>
                    <li><a href="#">Understanding Web Development: A Comprehensive Guide</a></li>
                    <li><a href="#">Exploring Modern Front-End Technologies</a></li>
                    <li><a href="#">How to Build a Responsive Design</a></li>
                </ul>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 My Tech Blog. All Rights Reserved.</p>
    </footer>

    <script>
        let currentSlide = 0;

        function showSlide(index) {
            const slides = document.querySelector('.slides');
            const totalSlides = document.querySelectorAll('.slide').length;
            if (index >= totalSlides) { currentSlide = 0; }
            if (index < 0) { currentSlide = totalSlides - 1; }
            slides.style.transform = `translateX(${-currentSlide * 100}%)`;
        }

        function nextSlide() {
            currentSlide++;
            showSlide(currentSlide);
        }

        function prevSlide() {
            currentSlide--;
            showSlide(currentSlide);
        }

        // Initialize the slider
        showSlide(currentSlide);
    </script>
</body>
</html>
