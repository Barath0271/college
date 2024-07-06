COLLEGE WEBSITE
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website</title>
    <style>
        /* Basic CSS for styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color:rgb(160, 160, 107);
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color:blueviolet;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color:black;
            text-decoration: none;
            margin: 0 10px;
            cursor: pointer;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background-color:white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo" alt="" style="width: 100%; max-width: 1000px;">
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#courses">Courses</a>
        <a href="#admissions">Admissions</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to our college website. Learn, explore, and succeed with us!</p>
            <img src="clg images.jpg" alt="College Image" style="width: 100%; max-width: 600px;">
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p><ol><li>General Admission Statement
                Join us at SRM UNIVERSITY college and embark on a journey of academic excellence and personal growth."</li><br>
                <li>Welcoming Prospective Students:
                "We invite passionate and driven individuals to join our diverse community at saveetha engineering college."</li><br>
                <li>Highlighting Opportunities:
                "Discover endless opportunities for learning and innovation when you choose to study at saveetha engineering college."</li><br>
                <li>Emphasizing Community and Support:
                "At [College Name], we foster a supportive community where every student's journey is valued and supported."</li><br>
                <li>Promoting Diversity and Inclusivity:
                "Embrace diversity and inclusivity as you become a part of our vibrant campus community at saveetha engineering college."</li><br>
                <li>Encouraging Personal and Professional Development:
                "Start your journey towards a successful career with our comprehensive programs designed to nurture your talents and skills."</li><br>
                <li>Highlighting Accreditation and Quality Education:
                "Benefit from our accredited programs and industry-relevant curriculum that ensures a high-quality education at saveetha engineering college."</li><br>
                <li>Inviting Application:
                "Apply now and join the ranks of future leaders and innovators at [College Name]. Your journey to success begins here."</li><br></ol></p>
        </section>
        <section id="courses">
            <h2>Courses</h2>
            <ul>
                <li>Computer Science</li>
                <img src="cs lab" alt="">
                <li>Information Technology</li>
                <img src="it lab" alt="">
                <li>Mechanical</li>
                <img src="mech lab" alt="">
                <li>IOT</li>
                <img src="iot" alt="">
                
            </ul>
        </section>
        <section id="admissions">
            <h2>Admissions</h2>
            <p>Explore our admission process and apply to join our diverse community.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Reach out to us for any queries or feedback.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Our College. All rights reserved.</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
```
### Output :
![Screenshot (35)](https://github.com/Barath0271/college/assets/135820464/2a337c9a-49a6-4827-aabe-eaecce2707c3)
![Screenshot (36)](https://github.com/Barath0271/college/assets/135820464/ccf1624c-0102-432a-ab81-ebf2f0b99a43)
![Screenshot (37)](https://github.com/Barath0271/college/assets/135820464/e66cb19f-d5fc-49ee-8ed0-4de92bbe1895)
![Screenshot (38)](https://github.com/Barath0271/college/assets/135820464/1af351da-f499-4650-a75d-a2fac37af81f)
