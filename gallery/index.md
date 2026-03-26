<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <style>
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .gallery-item {
            margin: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            overflow: hidden;
            width: 200px;
            text-align: center;
        }
        .gallery-item img {
            width: 100%;
        }
        .caption {
            padding: 5px;
            font-size: 14px;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div class="gallery-item">
            <img src="img1.png" alt="Image 1">
            <div class="caption">Caption for Image 1</div>
        </div>
        <div class="gallery-item">
            <img src="img2.png" alt="Image 2">
            <div class="caption">Caption for Image 2</div>
        </div>
        <div class="gallery-item">
            <img src="img3.png" alt="Image 3">
            <div class="caption">Caption for Image 3</div>
        </div>
        <div class="gallery-item">
            <img src="img4.png" alt="Image 4">
            <div class="caption">Caption for Image 4</div>
        </div>
    </div>
</body>
</html>