<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Confession Page</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #ffd1dc, #fff0f5);
            color: #333;
            text-align: center;
        }
        header {
            background-color: #ff6f91;
            color: white;
            padding: 20px;
            font-size: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        .sentence {
            margin: 50px 20px;
            font-size: 1.8rem;
            color: #ff69b4;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            animation: fadeIn 2s ease-in-out;
        }
        .sentence span {
            display: block;
            margin: 20px 0;
            font-size: 2rem;
        }
        .image {
            max-width: 90%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            margin-bottom: 30px;
        }
        footer {
            background-color: #ff6f91;
            color: white;
            padding: 10px;
            font-size: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>For Someone Special</header>

    <div class="sentence">
        <span>"You are the sunshine that brightens my days."</span>
        <img src="https://example.com/happy-anime-image.jpg" alt="Happy Anime" class="image">

        <span>"I’ve missed our moments together more than words can say."</span>
        <img src="https://example.com/nostalgic-anime-image.jpg" alt="Nostalgic Anime" class="image">

        <span>"Talking to you again has reminded me of how special you are."</span>
        <img src="https://example.com/sentimental-anime-image.jpg" alt="Sentimental Anime" class="image">

        <span>"If you don’t feel the same, I will always respect your feelings."</span>
        <img src="https://example.com/respectful-anime-image.jpg" alt="Respectful Anime" class="image">
    </div>

    <footer>Made with ❤️ for you</footer>
</body>
</html>
