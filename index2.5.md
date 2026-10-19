# Assignment 2.5 — HTML Foundations Mini-Project

## Objective
To create a complete personal introduction webpage using HTML only, with a proper document structure and all required sections.

## Complete HTML Code

Save the following code in a file named `index.html`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Introduction - Shubham Yadav</title>
</head>
<body>
    <header>
        <h1>My Personal Introduction Webpage</h1>
        <p>Welcome to my personal webpage!</p>
    </header>

    <main>
        <section id="about-me">
            <h2>About Me</h2>
            <p>My name is Shubham Yadav. I am pursuing a B.Tech in Computer Science and Engineering at Invertis University. I am interested in programming, computers, and web development. I enjoy learning new technologies and improving my technical skills.</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <ul>
                <li>B.Tech in Computer Science and Engineering — Invertis University (Currently Pursuing)</li>
                <li>Class 12 — Lord Academy Secondary School (Completed)</li>
            </ul>
        </section>

        <section id="technical-skills">
            <h2>Technical Skills</h2>
            <ul>
                <li>HTML Basics</li>
                <li>Computer Fundamentals</li>
                <li>Basic Programming Concepts</li>
                <li>Visual Studio Code</li>
                <li>Git and GitHub Basics</li>
                <li>Learning JavaScript</li>
            </ul>
        </section>

        <section id="hobbies">
            <h2>Hobbies</h2>
            <ul>
                <li>Learning new technologies</li>
                <li>Exploring computers and software</li>
                <li>Playing games</li>
                <li>Listening to music</li>
                <li>Working on creative projects</li>
            </ul>
        </section>

        <section id="contact-information">
            <h2>Contact Information</h2>
            <p><strong>Name:</strong> Shubham Yadav</p>
            <p><strong>Location:</strong> Deoria, Uttar Pradesh, India</p>
            <p><strong>Email:</strong> Add your email address here</p>
            <p><strong>GitHub:</strong> Add your GitHub profile URL here</p>
        </section>
    </main>

    <footer>
        <p>Thank you for visiting my webpage!</p>
        <p>&copy; 2026 Shubham Yadav. All rights reserved.</p>
    </footer>
</body>
</html>
```

## Steps to Run the Webpage
1. Create a project folder named `Assignment-2.5`.
2. Create a file named `index.html` inside the folder.
3. Paste the HTML code into the file and save it.
4. Open `index.html` in a web browser to view the webpage.

## Git and GitHub Submission
1. Create a public GitHub repository named `Assignment-2.5`.
2. Open the terminal in the project folder.
3. Run the following commands:

```bash
git init
git add index.html
git commit -m "Complete HTML Foundations Mini-Project"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/Assignment-2.5.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username. If Git is already initialized or a remote already exists, do not repeat those setup commands unnecessarily.

## Result
A complete personal introduction webpage was created using HTML only. It includes a page title, heading, About Me, Education, Technical Skills, Hobbies, Contact Information, and footer.

## Submission
- HTML file: `index.html`
- GitHub repository: `https://github.com/YOUR-USERNAME/Assignment-2.5`
- Screenshot of the webpage, if required by the instructor.

Note: Replace the placeholder email and GitHub profile with your actual details before submission.