# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #9873c5;
            color: #3030a1;
        }

        header {
            background: #22033c;
            color: rgb(26, 1, 1);
            text-align: center;
            padding: 30px;
        }

        header h1 {
            font-size: 36px;
        }

        header p {
            margin-top: 10px;
            font-size: 18px;
        }

        nav {
            background: #34495e;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-size: 18px;
        }

        nav a:hover {
            color: yellow;
        }

        section {
            width: 80%;
            margin: 30px auto;
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 0 10px gray;
        }

        h2 {
            color: #2c3e50;
            margin-bottom: 15px;
        }

        ul {
            margin-left: 20px;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }

        img {
            width: 150px;
            border-radius: 50%;
            display: block;
            margin: 20px auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>Portfolio</h1>
        <p>Web Developer | Student | Designer</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <img src="c:\Users\acer\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\EFC4A5C763B8ECA19F4271424744DC337DE519F4\transfers\2026-20\WhatsApp Image 2026-05-14 at 11.25.43 AM.jpeg" alt="Profile Photo">
        <p>Hello! I am a student interested in web development. I enjoy creating websites using HTML, CSS, and JavaScript.</p>
        <p>Name: Kamalesh</p>
        <p>Age: 19</p>
        <p>Education: B.Tech Artificial Intelligence and Data Science</p>
        <p>Hobbies: Coding, Traveling, Cooking</p>
        <p>passed out year: 2029</p>
        <p>Exprience : Fresher</p>
        <p>DOB: 2007-07-31</p>
        <p>Address: 123 Main Street, City, Country</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>Student Registration Form</li>
            <li>Restaurant Feedback Form</li>
            <li>Online Course Enrollment Form</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: kamaleshe3172007.com</p>
        <p>Phone: +91 9176431086</p>
    </section>

    <footer>
        <p>© 2026 My Portfolio | All Rights Reserved</p>
    </footer>

</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2026-05-13 235138.png>)
![alt text](<Screenshot 2026-05-13 235116.png>)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
