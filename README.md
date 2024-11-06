<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #ffffff;
            margin: 0;
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        h1 {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .section-title {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .icon-bar a {
            display: inline-block;
            padding: 8px 16px;
            margin-right: 5px;
            color: #ffffff;
            background-color: #333333;
            border-radius: 5px;
            text-decoration: none;
        }
        .icon-bar a:hover {
            opacity: 0.8;
        }
        .languages, .front-end, .back-end, .database {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }
        .badge {
            padding: 8px 16px;
            background-color: #444;
            border-radius: 5px;
            font-weight: bold;
        }
        .react { background-color: #61dafb; }
        .material-ui { background-color: #0081cb; }
        .html5 { background-color: #e34c26; }
        .css3 { background-color: #264de4; }
        .bootstrap { background-color: #563d7c; }
        .node { background-color: #68a063; }
        .express { background-color: #333; }
        .mysql { background-color: #4479a1; }
        .mongodb { background-color: #4caf50; }
        .links a {
            display: inline-block;
            padding: 10px;
            margin: 5px;
            border-radius: 5px;
            color: white;
            text-align: center;
            text-decoration: none;
            font-weight: bold;
        }
        .codeforces { background-color: #f35b04; }
        .leetcode { background-color: #f89f1b; }
        .lightoj { background-color: #8e44ad; }
        .stopstalk { background-color: #5dade2; }
        .linkedin { background-color: #0072b1; }
        .github { background-color: #333333; }
        .gmail { background-color: #d14836; }
    </style>
</head>
<body>

    <h1>Hi there! I'm Nafis Fuad Pranta <span>👋</span></h1>
    <p>🌱 I'm currently studying Computer Science and Engineering at Chittagong University of Engineering and Technology.</p>
    <p>🍃 I'm currently learning about backend engineering. Interested in .NET and Springboot.</p>
    <p>💬 Ask me about Anything!</p>
    <p>📫 How to reach me: <a href="mailto:u1804053@student.cuet.ac.bd" style="color: #42a5f5;">u1804053@student.cuet.ac.bd</a></p>

    <div class="section">
        <h2 class="section-title">Connect with me:</h2>
        <a href="#" class="icon-bar"><i class="fab fa-linkedin"></i> LinkedIn</a>
    </div>

    <div class="section">
        <h2 class="section-title">⚒️ Skills</h2>

        <h3>Languages</h3>
        <div class="languages">
            <span class="badge" style="background-color: #00599C;">C</span>
            <span class="badge" style="background-color: #00599C;">C++</span>
            <span class="badge" style="background-color: #f0db4f;">JavaScript</span>
            <span class="badge" style="background-color: #3776AB;">Python</span>
        </div>

        <h3>Front-End Development</h3>
        <div class="front-end">
            <span class="badge react">React</span>
            <span class="badge material-ui">Material UI</span>
            <span class="badge html5">HTML5</span>
            <span class="badge css3">CSS3</span>
            <span class="badge bootstrap">Bootstrap</span>
        </div>

        <h3>Back-End Development</h3>
        <div class="back-end">
            <span class="badge node">Node.js</span>
            <span class="badge express">Express.js</span>
        </div>

        <h3>Database</h3>
        <div class="database">
            <span class="badge mysql">MySQL</span>
            <span class="badge mongodb">MongoDB</span>
        </div>
    </div>

    <div class="section">
        <h2 class="section-title">🔗 Links</h2>
        <div class="links">
            <a href="#" class="codeforces">Codeforces</a>
            <a href="#" class="leetcode">LeetCode</a>
            <a href="#" class="lightoj">LightOJ</a>
            <a href="#" class="stopstalk">StopStalk</a>
            <a href="#" class="linkedin">LinkedIn</a>
            <a href="#" class="github">GitHub</a>
            <a href="mailto:someone@example.com" class="gmail">Gmail</a>
        </div>
    </div>

</body>
</html>
