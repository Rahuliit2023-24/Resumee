<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        .section {
            margin-bottom: 20px;
        }
        .education, .skills, .hobbies, .achievements {
            display: flex;
            justify-content: space-between;
        }
        .marks {
            width: 50%;
        }
        .skills-list, .hobbies-list, .achievements-list {
            list-style-type: none;
            padding: 0;
        }
        .skills-list li, .hobbies-list li, .achievements-list li {
            background: #e7f3fe;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .about-me {
            background: #e7f3fe;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Rahul singh</h1>
    <p>Email: 262804rahulsingh@gmail.com | Phone: +918726920973 | Location: India (kheri) uttar pradesh </p>

    <div class="section about-me">
        <h2>About me</h2>
        <p>Me rahul singh persuing BSC cs from iit patna  currently i am learning pthon, JavaScript, css , html , SQL and many more  skills  
        i persued class 10th from T.P.R.S senior secondry school up kheri ,and 
        12th from Cambridge senior secondry school khurbura uttrakhand dehradun </p>
    </div>

    <div class="section education">
        <div class="marks">
            <h2>Education</h2>
            <p><strong>10th Class:</strong> 77.6%</p>
            <p><strong>12th Class:</strong> 67%</p>
        </div>
       

    <div class="section skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <li>HTML & CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>Problem Solving</li>
            <li>Team Collaboration</li>
            <li>SQL</li>
        </ul>
    </div>

 <div class="section achievements">
    <h2>Achievements</h2>
    <table>
        <tr>
            <th>Achievement</th>
        </tr>
        <tr>
            <td>winner of kabaddi in tahasil</td>
        </tr>
        <tr>
            <td>winner of long jump in school level</td>
        </tr>
        <tr>
            <td>best sketching award at school level</td>
        </tr>
    </table>
</div>

 <div class="section hobbies">
        <h2>Hobbies</h2>
        <ul class="hobbies-list">
            <li></li>
            <li>Cycling</li>
            <li>Traveling</li>
            <li>weight traning</li>
            <li>scatching</li>
            <li>Photography</li>
            <li>Playing games </li>
        </ul>
    </div>
</div>

</body>
</html>
