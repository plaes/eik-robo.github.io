---
layout: null
---
<html lang="en">
    <head>
        <script src="//code.jquery.com/jquery-1.11.3.min.js"></script>
        <link type="text/css" rel="stylesheet" href="//fonts.googleapis.com/css?family=Quantico"/>
        <meta http-equiv="refresh" content="300">
        <meta charset="utf-8"/>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
        <meta name="viewport" content="width=device-width, user-scalable=no"/>
        <title>Robocalendar</title>    
        <style type="text/css">

        html, body {
            background-color: #234c52;
            margin: 0;
            padding: 0;
        }
        
        iframe {
            border: 0;
            position: absolute;
            width: 100%;
            bottom: 0;
            left: 0;
            height: 80%;
        }
        
        p {
            position: absolute;
            top: 0px;
            right: 0;
            left: 300px;
            display: inline;
            margin: 1em 0;
            font-size: 42px;
            font-family: 'Quantico';
        }


        svg {
            margin: 2em;
        }
        </style>
    </head>
    <body>
        {% include svg/logo2-english.svg %}
        <iframe src="https://www.google.com/calendar/embed?src=YzI4aGJlcWJ0ZzNyaTU5ZWVibTZmcDNidG9AZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&hl=en_EE&mode=agenda"/>
    </body>
</html>
