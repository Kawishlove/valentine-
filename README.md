<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will you be my Valentine?</title>
    <style>
        body {
            background-color: #ffe6f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .box {
            background-color: #ff99cc;
            padding: 50px;
            border-radius: 20px;
            box-shadow: 0px 0px 20px #ff6699;
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            font-size: 18px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
        #yes { background-color: #ff4d94; color: white; }
        #no { background-color: #ffb3d1; color: white; }
    </style>
</head>
<body>
    <div class="box">
        <h1>Will you be my Valentine? ❤️</h1>
        <button id="yes">Yes ❤️</button>
        <button id="no">No 💔</button>
    </div>

    <script>
        document.getElementById('yes').onclick = () => alert('Yay! I love you 💖');
        document.getElementById('no').onclick = () => alert('Oh no 😢');
    </script>
</body>
</html>
