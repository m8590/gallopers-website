<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallopers Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: url('https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDJ8fGRhcmt8ZW58MHx8fHwxNjE5MTU2NzU4&ixlib=rb-1.2.1&q=80&w=1080') no-repeat center center fixed;
            background-size: cover;
            margin: 0;
            padding: 0;
            color: #fff;
        }

        .header {
            text-align: center;
            padding: 50px 20px;
            background-color: rgba(0, 0, 0, 0.5);
        }

        .header img {
            max-width: 150px;
            border-radius: 50%;
        }

        .header h2 {
            font-size: 24px;
            margin-top: 20px;
        }

        h1 {
            text-align: center;
            margin-top: 40px;
            font-size: 36px;
            text-transform: uppercase;
        }

        .main-nav ul {
            list-style-type: none;
            text-align: center;
            padding: 0;
        }

        .main-nav ul li {
            display: inline-block;
            margin: 0 15px;
        }

        .main-nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            padding: 10px 20px;
            border: 2px solid #fff;
            border-radius: 25px;
            transition: all 0.3s;
        }

        .main-nav ul li a:hover {
            background-color: #fff;
            color: #000;
        }

        .admission-form {
            background-color: rgba(0, 0, 0, 0.7);
            max-width: 600px;
            margin: 50px auto;
            padding: 30px;
            border-radius: 10px;
        }

        .admission-form fieldset {
            border: none;
        }

        .admission-form legend {
            font-size: 28px;
            margin-bottom: 20px;
            text-align: center;
        }

        .admission-form label {
            display: block;
            margin: 10px 0 5px;
        }

        .admission-form input,
        .admission-form select,
        .admission-form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }

        .admission-form input,
        .admission-form select {
            background-color: #f1f1f1;
        }

        .admission-form button {
            background-color: #ff5722;
            color: #fff;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .admission-form button:hover {
            background-color: #e64a19;
        }

        .information, footer {
            max-width: 800px;
            margin: 50px auto;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 30px;
            border-radius: 10px;
        }

        footer textarea {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 20px;
            resize: none;
        }

        footer img {
            max-width: 100%;
            border-radius: 10px;
        }

        marquee {
            margin-top: 30px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="https://i.pinimg.com/originals/19/9f/d2/199fd29184c6cff24e3445f849af463e.gif" alt="computer">
        <h2>Welcome to the most practical school in Ketu North Municipality. Here, we give you the means to become what you never imagined to be.</h2>
    </div>

    <h1>Welcome to Gallopers Website</h1>

    <nav class="main-nav">
        <ul>
            <li><a id="home" href="#">Home</a></li>
            <li><a id="admission" href="#">Admission</a></li>
            <li><a id="contact-us" href="#">Contact Us</a></li>
            <li><a id="about-us" href="#">About Us</a></li>
        </ul>
    </nav>

    <section class="admission-form">
        <form id="admission-form">
            <fieldset>
                <legend>Admission Form</legend>
                
                <label for="name">Enter Your Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="number">Enter Your Number:</label>
                <input type="number" id="number" name="number" required>
                
                <label for="email">Enter Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="courses">Select Your Course:</label>
                <select id="courses" name="courses">
                    <option>Programming</option>
                    <option>Graphic Design</option>
                    <option>Social Media Education</option>
                    <option>Website Design</option>
                    <option>Mentorship</option>
                    <option>Video Editing</option>
                </select>
                
                <button type="submit">Register</button>
            </fieldset>
        </form>
    </section>

    <section class="information">
        <h2>About Gallopers Training and Innovation Center</h2>
        <p>We offer a variety of courses such as programming and many more. We know no bounds.</p>

        <h3>Requirements</h3>
        <ul>
            <li>Ability to read, speak, and write good English</li>
            <li>Must be on time to class</li>
            <li>Respect for the school authority</li>
            <li>Typing skills</li>
        </ul>

        <h4>Programming Languages We Offer</h4>
        <nav>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Java</li>
                <li>Python</li>
                <li>C++</li>
                <li>C</li>
                <li>PHP</li>
            </ul>
        </nav>
    </section>

    <footer>
        <textarea placeholder="Leave a comment"></textarea>
        <img id="background-image" src="https://scontent-fra3-1.xx.fbcdn.net/v/t39.30808-6/357433194_938818513974815_1920438294375316227_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=833d8c&_nc_eui2=AeGYCIzpKoKR_4IjQjjd37Qfx46U79joQ7_HjpTv2OhDvxl870VA0E7NrYCHnoNRaskhdtzn7jDHhPAn6prk5xiZ&_nc_ohc=JhTFSTjld-MQ7kNvgGM-SFI&_nc_ht=scontent-fra3-1.xx&oh=00_AYBnFDxNlcYt9OMSvBzlAwHmcCBXAOu-_G4FUXE2FpS18A&oe=66C40CE1" alt="Gallopers Training Center">
    </footer>
    <marquee direction="left">Gallopers Network</marquee>
    <marquee direction="right">We know no bounds.!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!</marquee>
   <marquee direction="center"><h5>Our aim is to help upcoming youth to come into the digital world</h5></marquee>
</body>
</html>
