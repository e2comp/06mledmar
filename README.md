<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LAB EXERCISES IN E2 COMPUTER - EDMAR JAZARINO (2-INDIA)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .nav-links a {
            margin: 10px;
            text-decoration: none;
            color: white;
            background-color: maroon;
            padding: 10px;
            border-radius: 5px;
        }
        .home {
            background-color: maroon;
            color: white;
            text-align: center;
            padding: 50px;
        }
        .page-content {
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        iframe {
            max-width: 100%;
            height: 400px;
        }
        .image-center {
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
        }
        h2, h3 {
            color: maroon;
        }
        .form-group {
            margin: 20px 0;
        }
        .form-group label {
            font-weight: bold;
        }
        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
    </style>
</head>

<body>
    <!-- Home Page -->
    <div class="home">
        <h1>LAB EXERCISES IN E2 COMPUTER</h1>
        <h2>EDMAR JAZARINO (2-INDIA)</h2>
        <audio controls>
            <source src="videoplayback (6).webm">
            Your browser does not support the audio element.
        </audio>
        <div class="nav-links">
            <a href="#autobiography">Autobiography</a>
            <a href="#article">Article</a>
            <a href="#blog">Blog</a>
            <a href="#form">Form</a>
        </div>
    </div>
    <!-- Autobiography Page -->
    <div id="autobiography" class="page-content container">
        <h2>AUTOBIOGRAPHY</h2>
        <img src="your-image.jpg" alt="Edmar Jazarino" class="image-center">
        <p>I am Edmar N. Jazarino, a 19-year-old from Casiguran, Sorsogon province. I am studying at Sorsogon College of Criminology Inc., a second-year criminology student, born on April 4, 2005. I have a deep passion for law enforcement agencies and am willing to work hard to bring positive change and contribute to this field. My family, especially my father, Eduardo, who works as a fisherman, has always supported me in my educational journey, even though it has been challenging. I remain highly interested in my studies on criminal justice, forensic science, and law enforcement procedures, motivated by my burning desire to fight for justice and help others.</p>
    </div>
    <!-- Article Page -->
    <div id="article" class="page-content container">
        <h2>ARTICLE</h2>
        <iframe src="https://m.youtube.com/watch?v=k6uUXr6Dotk&pp=ygUSV2hhdCBpcyBwbGFnaWFyaXNt" frameborder="0" allowfullscreen></iframe>
        <h3>Plagiarism</h3>
        <p>Plagiarism means taking credit for someone else's words or ideas, either on purpose or accidentally through failure to cite sources.</p>
        <h4>Famous cases of plagiarism:</h4>
        <ul>
            <li><strong>Alex Haley:</strong> The author of "Roots" was accused of plagiarizing parts of "The African" by Harold Courlander. Haley settled the lawsuit, but insisted that "Roots" was his own work.</li>
            <li><strong>Helen Keller:</strong> The author of "The Frost King" was accused of plagiarizing "The Frost Fairies" by Margaret Canby. Keller denied intentionally plagiarizing but admitted she may have been influenced unknowingly.</li>
            <li><strong>Annette Schavan:</strong> The former German Minister of Education and Research was accused of plagiarizing her Ph.D. thesis, using 60 secondary sources without proper citation.</li>
        </ul>
    </div>
    <!-- Blog Page -->
    <div id="blog" class="page-content container">
        <h2>BLOG</h2>
        <iframe src="https://m.youtube.com/watch?v=VJFaO2-zsCU&pp=ygUHbWFsd2FyZQ%3D%3D" frameborder="0" allowfullscreen></iframe>
        <h3>Malware</h3>
        <p>Malware is software designed to disrupt, damage, or gain unauthorized access to computer systems.</p>
        <ul>
            <li><strong>Computer Virus:</strong> A type of malicious software that spreads between computers and damages data and software.</li>
            <li><strong>Spam:</strong> Unsolicited digital communication, often in bulk, sent via email, text messages, phone calls, or social media.</li>
            <li><strong>Antivirus:</strong> Software designed to prevent, detect, and delete viruses from a computer.</li>
        </ul>
    </div>
    <!-- Form Page -->
    <div id="form" class="page-content container">
        <h2>Mobile Legends Feedback Form</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label>Gender:</label>
                <input type="radio" id="male" name="gender" value="Male"> Male
                <input type="radio" id="female" name="gender" value="Female"> Female
            </div>
            <div class="form-group">
                <label>Favorite Mobile Legends Hero:</label>
                <input type="checkbox" id="hero1" name="heroes" value="Lancelot"> Lancelot
                <input type="checkbox" id="hero2" name="heroes" value="Aldous"> Aldous
                <input type="checkbox" id="hero3" name="heroes" value="Layla"> Layla
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <label for="mobile">Preferred Mobile Legends Server:</label>
                <select id="mobile" name="mobile">
                    <option value="Server 1">Server 1</option>
                    <option value="Server 2">Server 2</option>
                    <option value="Server 3">Server 3</option>
                </select>
            </div>
            <div class="form-group">
                <label for="comments">Additional Comments:</label>
                <textarea id="comments" name="comments" rows="4" placeholder="Write your feedback here..."></textarea>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>

</body>

</html>
