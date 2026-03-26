<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <style>
        body {
            background: linear-gradient(135deg, #ff7e5f, #feb47b);
            overflow: hidden;
            position: relative;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .card {
            position: relative;
            width: 250px;
            margin: 15px;
            border: 2px solid #ffffff;
            border-radius: 10px;
            overflow: hidden;
            background: rgba(255, 255, 255, 0.8);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-bottom: 2px solid #feb47b;
        }
        .caption {
            padding: 10px;
            text-align: center;
            font-weight: bold;
            color: #333;
        }
        .circle-bg {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            opacity: 0.5;
        }
        .circle-bg1 { width: 150px; height: 150px; top: 50px; left: 100px; }
        .circle-bg2 { width: 100px; height: 100px; bottom: 30px; right: 100px; }
        .circle-bg3 { width: 200px; height: 200px; top: 200px; left: 0; }
    </style>
</head>
<body>
    <div class="circle-bg circle-bg1"></div>
    <div class="circle-bg circle-bg2"></div>
    <div class="circle-bg circle-bg3"></div>
    <div class="gallery">
        <div class="card">
            <img src="path/to/home_screen.jpg" alt="Gapster Home Screen">
            <div class="caption">Gapster Home Screen</div>
        </div>
        <div class="card">
            <img src="path/to/stories.jpg" alt="Choose from 120+ Stories">
            <div class="caption">Choose from 120+ Stories</div>
        </div>
        <div class="card">
            <img src="path/to/user_profile.jpg" alt="User Profile Pages">
            <div class="caption">User Profile Pages</div>
        </div>
        <div class="card">
            <img src="path/to/leaderboard.jpg" alt="Leaderboard Competitions">
            <div class="caption">Leaderboard Competitions</div>
        </div>
    </div>
</body>
</html>
