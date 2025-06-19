# Mozilla-Splash-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Funky Mozilla Splash Page</title>
    <style>
        body {
            background: linear-gradient(135deg, #ff6ec4, #7873f5);
            color: white;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            padding: 30px;
        }
        h1 {
            font-size: 3rem;
            animation: spin 5s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg);}
            100% { transform: rotate(360deg);}
        }
        img {
            border: 5px dashed yellow;
            border-radius: 20px;
            margin: 20px;
            width: 300px;
            height: auto;
        }
        video {
            border: 5px solid white;
            border-radius: 15px;
            width: 500px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Welcome to the Funky World of Mozilla!</h1>
    <p>Mozilla is open-source, fast, and absolutely funky!</p>

    <!-- <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Mozilla_Firefox_Logo_2013.svg" alt="Mozilla Firefox Logo"> -->

    

    <p>Watch this cool video about Mozilla Firefox:</p>
    <video controls>
        <source src="https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <p>Visit <a href="https://www.mozilla.org" target="_blank" style="color: yellow;">Mozilla Official Site</a></p>
</body>
</html>
