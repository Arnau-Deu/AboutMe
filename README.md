<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Arnau's Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fdf6e3;
            color: #333;
            padding: 20px;
        }

        h1, h2 {
            font-family: 'Georgia', serif;
            color: #2c3e50;
            text-align: center;
        }

        .card {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .card-text {
            flex: 1;
            text-align: left;
            margin-right: 20px;
        }

        .card img {
            max-width: 150px;
            border-radius: 10px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin: 5px 0;
        }

        a {
            color: #2980b9;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .spotify-button {
            display: inline-block;
            background-color: #1DB954;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 25px;
            font-size: 16px;
            font-family: Arial, sans-serif;
            vertical-align: middle;
            margin-top: 10px;
        }

        .spotify-button img {
            width: 50px;
            border-radius: 50%;
            margin-right: 10px;
            vertical-align: middle;
        }
    </style>
</head>
<body>

    <h1>~ 𝓦𝓮𝓵𝓬𝓸𝓶𝓮 𝓽𝓸 𝓶𝔂 𝓟𝓻𝓸𝓯𝓲𝓵𝓮 ~</h1>

    <!-- About Me -->
    <div class="card">
        <div class="card-text">
            <h2>~ About Me ~</h2>
            <ul>
                <li><b>Name:</b> Arnau</li>
                <li><b>Hobbies:</b> reading manga, watching anime, playing LoL and WoW, agriculture, listening to Spotify</li>
            </ul>
            <!-- Spotify Button -->
            <a class="spotify-button" href="https://open.spotify.com/user/e471w7efesrioeuur5v4nwbrq" target="_blank">
                <img src="https://i.pinimg.com/736x/a7/49/0d/a7490d99bb1f5d7674d2f82058e5ad6f.jpg" alt="Spotify Profile">
                Listen on Spotify 🎧
            </a>
        </div>
        <img src="https://64.media.tumblr.com/e1f1c97123ae217eb731500e502e0083/tumblr_n9dxcikmIU1qc9zfzo7_r1_250.gif" alt="About Me GIF">
    </div>

    <!-- Knowledge -->
    <div class="card">
        <div class="card-text">
            <h2>~ Knowledge ~</h2>
            <p>I am currently studying <b>1st year of Web Application Development (DAW)</b> at IES El Caminàs, and I am interested in everything related to web development and applications.</p>
        </div>
        <img src="https://i.pinimg.com/originals/8d/4b/77/8d4b77c44b7a68c0fd609411e2c0ec3c.gif" alt="Knowledge GIF">
    </div>

</body>
</html>
