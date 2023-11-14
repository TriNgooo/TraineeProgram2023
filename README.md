# TraineeProgram2023
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, rgba(12221, 4, 75, 0.8) 10%, rgba(95229, 9333, 40, 1) 100%);
            background-attachment: fixed;
            height: 100vh;
            width: 100vw;
            font-family: 'Roboto', sans-serif;
            color: white;
        }

        #logo {
            width: 200px;
            margin-bottom: 10px;
        }

        #avatar {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            margin-bottom: 30px;
        }

        .left-column {
            width: 400px;
            display: flex;
            flex-direction: column;
            align-items: center;
            border-right: 2px solid rgba(255, 255, 255,800);
            padding-right:20px;
        }

        .right-column {
            width: 460px;
            margin-left: 50px;
        }

        .card {
            background: rgba(0, 0, 0, 0.3);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(200px);
            width: 1000px;
            height: 710px;
            padding: 50px;
            border-radius: 50px;
            display: flex;
            justify-content: space-between;
        }

        h1,
        h2 {
            margin-bottom: 10px;
        }

        p {
            font-size: 17px;
            line-height: 1.7;
        }

        a {
            color: white;
        }

        .section {
            margin-bottom: 0px;
        }

        main {
            height: 100%;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .contacts {
            
            box-shadow: 0 1px 10px rgba(0, 0, 0, 0.9);
            padding: 20px;
            border-radius: 20px;
            margin-top: 20px;
            font-size: 24px;
        }

            .contacts a {
                display: block;
                font: size 20px;
                margin-bottom: 20px;
                text-decoration: none;
                color: white;
            }

            .contacts img {
                width: 30px;
                height: 30px;
                margin-right: 10px;
            }
    </style>
</head>

<body>
    <main>
        <div class="card">
            <!-- Left Column -->
            <div class="left-column">
                <!-- Content for left column goes here --> <img id="logo"                     src="https://lh3.googleusercontent.com/pw/ADCreHdaOMYiUdjIlNAkd_b5__H927yPc0fySkMRdRf1qaRgU26I1UW89DW_9LsfRbU7yvUEOfkbvk1sYWqNZIgNFAf40q51O1fZeMm91sAFycV-reJJcLw=w2400" />
                <img id="avatar" src="https://s1.zerochan.net/Bongo.Cat.600.3353167.jpg" alt="" />
                <div class="highlights">
                    <h1><strong>Ngo Minh Tri</strong></h1>
                    <h2>__________________________</h2>

                    <h2>🎓  <strong> Artificial Intelligence </strong></p>
                    <h2>🏫<strong>University of Information Technology, VNUHCM</strong></p>
                    <h2>📍<strong> Ho Chi Minh City</strong></p>
                </div>
            </div> <!-- Right Column -->
            <div class="right-column">
                <!-- Content for right column goes here -->
                <div class="section">
                    <h1>About Me</h2>
                    <p>My name is Tri Ngo. I'm currently studying at The University of Information Technology (UIT), a member of Vietnam National University and I'm majoring in artificial intelligence</p>
                </div>
                <div class="section">
                    <h1>My Hobbies</h2>
                    <p>I am passionate about engaging in physical activities, particularly football and badminton. Additionally, I find great satisfaction in planting trees and watching movies, as they serve as sources of relaxation and inspiration.</p>
                </div>
                <div class="section">
                    <h1>My Future Goals</h2>
                    <p> RICH 👉👈</p>
                <div class="contacts">
                    <h1>Contact me</h2>
                        <a href="mailto:23521640@gm.uit.edu.vn"><img src="https://cdn-icons-png.flaticon.com/512/6244/6244710.png" alt="">Mail</a>
                        <a href="https://github.com/TriNgooo"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111432.png" alt="">Github</a>
                        <a href="https://www.linkedin.com/in/ng%C3%B4-minh-tr%C3%AD-undefined-960005286/"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384014.png" alt="">Linkedin</a>
                        
        </div>
    </main>
</body>

</html>
