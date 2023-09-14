<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page1</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    <nav>
        <a href="#">Home</a>
        <a href="index.html">Event</a>
    </nav>
    <div class="media-container">
        <div class="media">
            <img src="1.jpg" title="jett" alt="Picture" id="image1">
            <button onclick="changeImage('image1')">Change</button>
        </div>
        <div class="media">
            <img src="1.jpg" title="sage" alt="Picture" id="image2">
            <button onclick="changeImage('image2')">Change</button>
        </div>
        <div class="media">
            <img src="1.jpg" title="reyna" alt="Picture" id="image3">
            <button onclick="changeImage('image3')">Change</button>
        </div>
    </div>

    <div class="media-container">
        <div class="media">
            <video controls="wall.jpg" id="video1" autoplay muted>
                <source src="videocha1.mp4" type="video/mp4">
            </video>
            <button onclick="changeVideo('video1')">Change</button>
        </div>
        <div class="media">
            <video controls="wall.jpg" id="video2" autoplay muted>
                <source src="videocha1.mp4" type="video/mp4">
            </video>
            <button onclick="changeVideo('video2')">Change</button>
        </div>
        <div class="media">
            <video controls="wall.jpg" id="video3" autoplay muted>
                <source src="videocha1.mp4" type="video/mp4">
            </video>
            <button onclick="changeVideo('video3')">Change</button>
        </div>
    </div>

    <script>
        function changeImage(imageId) {
            var image = document.getElementById(imageId);
            image.src = "2.jpg"; 
        }

        function changeVideo(videoId) {
            var video = document.getElementById(videoId);
            video.src = "videocha2.mp4"; 
        }
    </script>
</body>
</html>
