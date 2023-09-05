# oibsip_l1t2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reethu Bhargavi - Portfolio</title>
    <style>
        body {
            font-family: Times New Roman, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #35424a;
            color: white;
            padding: 0.002px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        h1 {
            color: #35424a;
        }
        h2 {
            color: #35424a;
            border-bottom: 2px solid #007bff;
            padding-bottom: 5px;
        }
        p {
            color: #777;
            line-height: 1.6;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin-bottom: 10px;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        .slideshow-container {
            position: relative;
            max-width: 100%;
            margin: auto;
            overflow: hidden;
        }
        .slide {
            display: none;
            animation-name: fade;
            animation-duration: 1s;
            text-align: left;
            padding: 20px;
            display: flex;
            flex-direction: column; /* Stack content vertically */
            align-items: center; /* Center-align content horizontally */
        }
        @keyframes fade {
            0% {
                opacity: 0.4;
            }
            100% {
                opacity: 1;
            }
        }
        img {
            max-width: 30%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 20px; /* Add margin between image and text */
        }
        .text {
            max-width: 100%; /* Take up full width */
            text-align: center; /* Center-align text within each slide vertically */
        }
    </style>
</head>
<body>
    <header>
        <h1>Reethu Bhargavi</h1>
        <p>PORTIFOLIO</p>
    </header>
    <div class="container">
        <div class="slideshow-container">
            <!-- About Me Slide -->
            <div class="slide">
                <img src="ONEPIECE.jpeg" alt="About Me">
                <div class="text">
                    <h2>About Me</h2>
                    <p>A budding Computer Science Engineering graduate seeking an entry-level position in a dynamic organization, and looking for an opportunity to work in a challenging environment to prove my skills and utilize my knowledge for the growth of the organization resulting in a meaningful contribution towards organizational growth along with personal and professional development.</p>
                </div>
            </div>
            <!-- Hard Skills Slide -->
            <div class="slide">
                <img src="hard.jpeg" alt="Hard Skills">
                <div class="text">
                    <h2>Hard Skills</h2>
                    <p>C, C++, Python</p>
                </div>
            </div>
            <!-- Soft Skills Slide -->
            <div class="slide">
                <img src="soft.jpeg" alt="Soft Skills">
                <div class="text">
                    <h2>Soft Skills</h2>
                    <ul>
                        <li>Adaptability</li>
                        <li>Communication</li>
                        <li>Problem-solving skills</li>
                    </ul>
                </div>
            </div>
            <!-- Education Background Slide -->
            <div class="slide">
                <img src="educa.jpeg" alt="Education Background">
                <div class="text">
                    <h2>Education Background</h2>
                    <p><strong>Under Graduation:</strong> SRM University AP, Computer Science Engineering (2021 - ongoing)</p>
                    <p><strong>Higher Secondary Education:</strong> Vignan Girls Junior College Guntur (2018-2020)</p>
                    <p><strong>Secondary Education:</strong> Katuri Public School (2017-2018)</p>
                </div>
            </div>
            <!-- Contact Information Slide -->
            <div class="slide">
                <img src="cont.jpg" alt="Contact Information">
                <div class="text">
                    <h2>Contact Information</h2>
                    <ul>
                        <li>Email: reethusajjala3125@gmail.com</li>
                        <li>Location: Guntur, AP, India</li>
                        <li>Phone: 9618609295</li>
                        <li><a href="https://www.linkedin.com/in/reethu-bhargavi-sajjala-67216a24b/">LinkedIn Profile</a></li>
                    </ul>
                </div>
            </div>
            <!-- Internships Slide -->
            <div class="slide">
                <img src="intern.jpeg" alt="Internships">
                <div class="text">
                    <h2>Internships</h2>
                    <p><strong>Company:</strong> AICTE (Feb 2023 - ongoing)</p>
                    <p><strong>Tools:</strong> Python IDLE</p>
                    <p><strong>Domain:</strong> Python Programming</p>
                </div>
            </div>
            <!-- Personal Details Slide -->
            <div class="slide">
                <img src="pers.jpg" alt="Personal Details">
                <div class="text">
                    <h2>Personal Details</h2>
                    <p>Date of Birth: 25th October, 2003</p>
                    <p>Languages: English, Telugu, Hindi</p>
                    <p>Hobbies: Reading books, Dancing, Cooking</p>
                </div>
            </div>
            <!-- Add more slides for additional sections if needed -->
        </div>
    </div>

    <script>
        let slideIndex = 0;
        showSlides();

        function showSlides() {
            const slides = document.getElementsByClassName("slide");
            for (let i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }
            slideIndex++;
            if (slideIndex > slides.length) {
                slideIndex = 1;
            }
            slides[slideIndex - 1].style.display = "block";
            setTimeout(showSlides, 1000); // Change slide every 4 seconds
        }
    </script>
</body>
</html>
