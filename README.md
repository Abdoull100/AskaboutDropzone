<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ask About Dropzone</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <div class="logo">DZ</div>
        <h1>Ask About Dropzone</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="skills.html">My Skills</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <section class="home">
            <p>Hi there! I'm glad you're here. This is my personal space where you can explore everything about me such as my Biography, skills and hubby. Feel free to browse around and checkout my works.</p>
            <p class="signature">Thank you<br>© Abdoull Dropzone</p>
        </section>
    </main>
    <footer>
        <p>© Dropzone 2025</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me - Dropzone</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <div class="logo">DZ</div>
        <h1>Ask About Dropzone</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="skills.html">My Skills</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <section class="about">
            <img src="assets/images/profile.jpg" alt="Profile Photo" class="profile-img">
            <div class="info-columns">
                <p><strong>Name:</strong> Abdullahi Adam Sulaiman</p>
                <p><strong>Gender:</strong> Male</p>
                <p><strong>DOB:</strong> 23 August, 2006</p>
                <p><strong>Religion:</strong> Islam</p>
                <p><strong>Continent:</strong> Africa</p>
                <p><strong>Country:</strong> Nigeria</p>
                <p><strong>Region:</strong> Northern Nigeria</p>
                <p><strong>State:</strong> Kano State</p>
                <p><strong>University:</strong> Northwest University Kano</p>
                <p><strong>Faculty:</strong> Faculty of Computing</p>
                <p><strong>Department:</strong> Software Engineering</p>
            </div>
        </section>
    </main>
    <footer>
        <p>© Dropzone 2025</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Skills - Dropzone</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <div class="logo">DZ</div>
        <h1>Ask About Dropzone</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="skills.html">My Skills</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <section class="skills">
            <h2>My Skills</h2>
            <ul>
                <li>Graphic Design</li>
                <li>Html and CSS</li>
                <li>Action Games</li>
            </ul>
            <h2>Hobbies</h2>
            <ul>
                <li>Game</li>
                <li>Football</li>
                <li>Eating</li>
                <li>Sleeping</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>© Dropzone 2025</p>
    </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Dropzone</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <div class="logo">DZ</div>
        <h1>Ask About Dropzone</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Me</a>
            <a href="skills.html">My Skills</a>
            <a href="contact.html">Contact Us</a>
        </nav>
    </header>
    <main>
        <section class="contact">
            <p>📞 Phone: +234 9165 324848</p>
            <p>📧 Email: abdullahiadamsulaiman500@gmail.com</p>
            <p>📍 Address: No. 7b Kofar Famfo, Dukawuya Quarters, Kano State Nigeria</p>
            <iframe src="https://maps.google.com/maps?q=No.%207b%20Kofar%20Famfo,%20Dukawuya%20Quarters,%20Kano%20State,%20Nigeria&t=&z=15&ie=UTF8&iwloc=&output=embed" width="100%" height="300" style="border:0;"></iframe>
        </section>
    </main>
    <footer>
        <p>© Dropzone 2025</p>
    </footer>
</body>
</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: 'Segoe UI', sans-serif;
    background: white;
    color: #111;
}
header {
    background-color: darkblue;
    color: white;
    padding: 1rem;
    text-align: center;
}
.logo {
    position: absolute;
    top: 10px;
    left: 20px;
    font-weight: bold;
    font-size: 1.2rem;
}
nav {
    margin-top: 0.5rem;
}
nav a {
    margin: 0 10px;
    color: #fff;
    text-decoration: none;
}
footer {
    background-color: #e0f0ff;
    padding: 10px;
    text-align: center;
    font-size: 0.9rem;
}
.home, .about, .skills, .contact {
    padding: 2rem;
}
.home p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
}
.signature {
    font-family: 'Brush Script MT', cursive;
    font-size: 1.4rem;
}
.profile-img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    margin-bottom: 1rem;
}
.info-columns {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    font-size: 1rem;
}
.skills ul, .skills h2 {
    margin: 1rem 0;
}
.skills ul {
    list-style-type: square;
    padding-left: 20px;
}
.contact p {
    margin: 0.5rem 0;
}

/* Responsive */
@media (max-width: 768px) {
    .info-columns {
        flex-direction: column;
    }
    header, .home, .about, .skills, .contact {
        padding: 1rem;
    }
    .profile-img {
        width: 100%;
        height: auto;
    }
}
