<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wheels on Rent</title>
    <style>
        body {
            background-color: black;
            color: gold;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 50px;
            font-weight: bold;
        }
        .categories {
            margin-top: 20px;
            font-size: 24px;
        }
        .categories div {
            margin: 10px 0;
        }
        .whatsapp-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: gold;
            color: black;
            padding: 15px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
        }
        .animation {
            width: 100%;
            height: 300px;
            background: url('https://www.hdcarwallpapers.com/thumbs/bmw_m4_headlights_4k-t2.jpg') no-repeat center;
            background-size: cover;
            animation: fadeIn 3s ease-in-out;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>Wheels on Rent</h1>
    <div class="animation"></div>
    <div class="categories">
        <div>🚗 Self Drive</div>
        <div>🚖 With Driver</div>
        <div>🎩 Wedding Car</div>
        <div>🚌 Traveller</div>
    </div>
    <a href="https://wa.me/91XXXXXXXXXX" class="whatsapp-button" target="_blank">📲 Book on WhatsApp</a>
</body>
</html>
