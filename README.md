## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Introduction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #161313;
            color: #eceaea;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: rgb(14, 12, 51);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            text-align: center;
        }
        h1 {
            color: #0bdb5b;
            margin-bottom: 20px;
            height: 30px;
        }
        p {
            line-height: 1.6;
        }
        .skills {
            margin-top: 20px;

        }
        .skills span {
            background-color: #0073e6;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            margin: 5px;
            display: inline-block;
        }
        .contact {
            margin-top: 20px;
        }
        .contact a {
            color: #6a6af1;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 id="intro-title"></h1>
        <p>I am a web developer with a passion for creating modern and functional websites.</p>
        <div class="skills">
            <h2>MY Skills</h2>
            <span>HTML</span>
            <span>CSS</span>
            <span>photoshop</span>
            <span>My SQL</span>
            <span>Python</span>
            <span>Django</span>
        </div>
        <div class="contact">
            <h2>Contact Me</h2>
            <a href="https://github.com/MO-ZAREI84" target="_blank">GitHub</a>
            <a href="zareisanim@example.com">Email</a>
        </div>
    </div>

    <script>
        const title = "Hello! I'm Mostafa Zarei 👋";
        let i = 0;

        function typeWriter() {
            if (i < title.length) {
                document.getElementById("intro-title").innerHTML += title.charAt(i);
                i++;
                setTimeout(typeWriter, 100);
            }
        }

        window.onload = typeWriter;
    </script>
</body>
</html>
