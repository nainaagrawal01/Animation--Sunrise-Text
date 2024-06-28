# Animation--Sunrise-Text
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8"> <!-- Added quotes around utf-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#333641">
    <title>Animation</title>
    <style type="text/css">
        @import url("https://fonts.googleapis.com/css?family=Source+Sans+Pro");

        :root,
        body {
            color: #fff;
            height: 100vh; /* Changed to 100vh for full viewport height */
            overflow: hidden;
            background: black;
            margin: 0; /* Added to remove default margin */
        }

        body {
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0; /* Added to remove default margin */
        }

        div {
            background: 50% 100% / 50% 50% no-repeat radial-gradient(ellipse at bottom, #fff, transparent, transparent);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-size: 10vw;
            font-family: "Source Sans Pro", sans-serif;
            animation: reveal 3000ms ease-in-out forwards 200ms, glow 2500ms linear infinite 2000ms;
        }

        @keyframes reveal {
            80% {
                letter-spacing: 8px;
            }
            100% {
                background-size: 300% 300%;
            }
        }

        @keyframes glow {
            40% {
                text-shadow: 0 0 8px #fff;
            }
        }
    </style>
</head>

<body>
   
    <div>
        HACKATHON
    </div>
</body>

</html>

</html>
