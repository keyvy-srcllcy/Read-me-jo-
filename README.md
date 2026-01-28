I love you, Jo.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Josel Wynda Marie</title>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Pro:ital,wght@1,200;1,300&family=Montserrat:wght@100;200&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #050505;
            --text-main: #ffffff;
            --text-dim: #777;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: 'Montserrat', sans-serif;
            overflow: hidden;
        }

        /* Subtle film grain overlay */
        body::after {
            content: "";
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background: url('https://www.transparenttextures.com/patterns/stardust.png');
            opacity: 0.15;
            pointer-events: none;
        }

        .container {
            text-align: center;
            max-width: 800px;
            padding: 40px;
            z-index: 1;
        }

        .header {
            font-size: 0.7rem;
            letter-spacing: 10px;
            text-transform: uppercase;
            color: var(--text-dim);
            margin-bottom: 80px;
            animation: fadeIn 5s ease-in;
        }

        .poetry {
            font-family: 'Crimson Pro', serif;
            font-style: italic;
            font-weight: 200;
            font-size: 1.6rem;
            line-height: 2.2;
            letter-spacing: 1px;
            animation: slideUp 4s ease-out;
        }

        .nurse-dedication {
            margin-top: 60px;
            font-size: 0.85rem;
            letter-spacing: 4px;
            color: #aaa;
            font-weight: 200;
            text-transform: uppercase;
        }

        .name-footer {
            margin-top: 100px;
            font-size: 0.6rem;
            letter-spacing: 12px;
            color: var(--text-dim);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Floating smoke-like blur effect */
        .ambient-glow {
            position: absolute;
            width: 300px;
            height: 300px;
            background: rgba(255, 255, 255, 0.03);
            filter: blur(80px);
            border-radius: 50%;
            z-index: -1;
            animation: drift 15s infinite alternate;
        }

        @keyframes drift {
            from { transform: translate(-10%, -10%); }
            to { transform: translate(10%, 10%); }
        }
    </style>
</head>
<body>

<div class="ambient-glow"></div>

<div class="container">
    <div class="header">To Josel Wynda Marie Cuya</div>
    
    <div class="poetry">
        In the quiet hours of the night,<br>
        I find myself tracing the thought of you.<br>
        I love you exactly as you exist—<br>
        without edit, without change, without end.<br>
        <br>
        There is a gentle power in your hands,<br>
        the same hands that are now destined to heal.<br>
        I appreciate the light you carry<br>
        and the heart you give so freely.
    </div>

    <div class="nurse-dedication">
        Congratulations on your nursing journey.
    </div>

    <div class="name-footer">
        I am so proud of you.
    </div>
</div>

</body>
</html>
