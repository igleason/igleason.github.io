# igleason.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Charity Water Mockup</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Proxima+Nova:wght@400;700&display=swap');

        body {
            font-family: 'Proxima Nova', sans-serif;
            background-color: #8BD1CB;
            color: #fff;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            padding: 20px;
            position: relative;
        }
        .logo {
            position: absolute;
            top: 10px;
            left: 10px;
        }
        .logo img {
            width: 120px; /* Increased size */
            height: auto;
        }
        .header {
            font-size: 2em;
            font-weight: bold;
            color: #FFC907;
        }
        .subheader {
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        .section {
            display: flex;
            justify-content: space-around;
            margin-bottom: 20px;
        }
        .section div {
            text-align: center;
        }
        .section img {
            width: 200px;
            height: auto;
            border-radius: 10px;
            display: block;
            margin: 0 auto;
        }
        .section p {
            width: 200px;
            font-size: 0.9em;
            color: #fff;
        }
        .button {
            background-color: #FFC907;
            color: #000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="img/cw_logo-2.png" alt="Logo">
        </div>
        <div class="header">Real Change Starts with Spare Change</div>
        <div class="subheader">Turn your everyday coins into clean water for someone in need. It’s simple, powerful, and starts with you.</div>
        <div class="section">
            <div>
                <img src="img/girls2.png" alt="Locally led water projects">
                <p>Locally led - and community owned water projects that you can be involved in. This means rehabilitating old water systems, building new ones, or completing sanitation and hygiene training.</p>
            </div>
            <div>
                <img src="img/girlwater1.png" alt="Personal mission">
                <p>Giving to charity: water means being apart of a personal mission that involves us all.</p>
            </div>
            <div>
                <img src="img/dudewater.png" alt="Monthly donations">
                <p>Monthly gaps in funding can be supported by The Spring; Monthly donations funding restoration of water facilities and more.</p>
            </div>
        </div>
        <button class="button">TAP IN: MAKE A CHANGE</button>
    </div>
</body>
</html>
