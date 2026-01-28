<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Josel Wynda Marie</title>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@0,400;1,400&family=Montserrat:wght@200;300&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: 'Montserrat', sans-serif;
            overflow-x: hidden;
        }

        /* Subtle grain effect to mimic the band's album art style */
        body::before {
            content: "";
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background: url('https://www.transparenttextures.com/patterns/stardust.png');
            opacity: 0.1;
            pointer-events: none;
        }

        .container {
            text-align: center;
            max-width: 700px;
            padding: 20px;
            animation: fadeIn 4s ease-in;
        }

        h1 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 200;
            letter-spacing: 8px;
            text-transform: uppercase;
            font-size: 1.2rem;
            margin-bottom: 60px;
            color: #ccc;
        }

        .confession {
            font-family: 'Crimson Text', serif;
            font-style: italic;
            font-size: 1.8rem;
            line-height: 1.8;
            color: #fff;
            margin-bottom: 40px;
        }

        .sub-text {
            font-weight: 200;
            letter-spacing: 3px;
            font-size: 0.8rem;
            color: #666;
            margin-top: 50px;
            text-transform: uppercase;
        }

        .divider {
            width: 40px;
            height: 1px;
            background: #444;
            margin: 40px auto;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Ambient pulse */
        .glow {
            box-shadow: 0 0 20px rgba(255,255,255,0.05);
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Josel Wynda Marie Cuya</h1>
    
    <div class="confession">
        "I love you exactly the way you are.<br>
        Every detail, every habit, every quiet moment.<br>
        I appreciate everything you do, and everything you are."
    </div>

    <div class="divider"></div>

    <div class="sub-text">
        Always.
    </div>
</div>

</body>
</html>
