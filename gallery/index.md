<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <style>
        body {
            background: linear-gradient(90deg, rgba(255, 182, 193, 1) 0%, rgba(255, 105, 180, 1) 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .gallery {
            display: table;
            width: 80%;
            border-collapse: collapse;
        }
        .gallery-card {
            display: table-cell;
            padding: 10px;
            text-align: center;
            position: relative;
        }
        .circle {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            overflow: hidden;
            position: relative;
            margin: 0 auto;
        }
        .circle img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top: 0;
            left: 0;
        }
        caption {
            font-weight: bold;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div class="gallery-card">
            <div class="circle">
                <img src="image1.jpg" alt="Gallery Image 1">
            </div>
            <caption>Image 1 caption</caption>
        </div>
        <div class="gallery-card">
            <div class="circle">
                <img src="image2.jpg" alt="Gallery Image 2">
            </div>
            <caption>Image 2 caption</caption>
        </div>
        <div class="gallery-card">
            <div class="circle">
                <img src="image3.jpg" alt="Gallery Image 3">
            </div>
            <caption>Image 3 caption</caption>
        </div>
        <div class="gallery-card">
            <div class="circle">
                <img src="image4.jpg" alt="Gallery Image 4">
            </div>
            <caption>Image 4 caption</caption>
        </div>
    </div>
</body>
</html>
