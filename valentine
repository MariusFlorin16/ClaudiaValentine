<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Valentine 💘</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: 'Arial', sans-serif;
        }

        .container {
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 40px;
        }

        .buttons {
            position: relative;
            width: 300px;
            height: 150px;
            margin: auto;
        }

        button {
            font-size: 1.2rem;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            position: absolute;
        }

        #yes {
            left: 20px;
            background-color: #4CAF50;
            color: white;
        }

        #no {
            right: 20px;
            background-color: #f44336;
            color: white;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Do you wanna be my Valentine? 💖</h1>
    <div class="buttons">
        <button id="yes">Yes</button>
        <button id="no">No</button>
    </div>
</div>

<script>
    const noBtn = document.getElementById('no');
    const container = document.querySelector('.buttons');

    function moveButton() {
        const containerRect = container.getBoundingClientRect();
        const btnRect = noBtn.getBoundingClientRect();

        const maxX = containerRect.width - btnRect.width;
        const maxY = containerRect.height - btnRect.height;

        const randomX = Math.random() * maxX;
        const randomY = Math.random() * maxY;

        noBtn.style.left = randomX + 'px';
        noBtn.style.top = randomY + 'px';
    }

    // Pentru mouse
    noBtn.addEventListener('mouseover', moveButton);

    // Pentru touch (telefon)
    noBtn.addEventListener('touchstart', moveButton);

    document.getElementById('yes').addEventListener('click', () => {
        alert("Yaaay! 💘 Happy Valentine’s Day!");
    });
</script>

</body>
</html>
