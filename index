<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Machine</title>
    <style>
        table {
            border-collapse: collapse;
        }
        td {
            border: 1px solid black;
            width: 100px;
            height: 100px;
            text-align: center;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td><img src="image1.png" alt=" 1"></td>
            <td><img src="image2.png" alt="Image 2"></td>
            <td><img src="image3.png" alt="Image 3"></td>
        </tr>
        <tr>
            <td><img src="image4.png" alt="Image 4"></td>
            <td><img src="image5.png" alt="Image 5"></td>
            <td><img src="image6.png" alt="Image 6"></td>
        </tr>
        <tr>
            <td><img src="image7.png" alt="Image 7"></td>
            <td><img src="image8.png" alt="Image 8"></td>
            <td><img src="image9.png" alt="Image 9"></td>
        </tr>
    </table>
    <button onclick="randomizeImages()">Spin</button>

    <script>
        function randomizeImages() {
            const images = document.querySelectorAll('img');
            images.forEach(image => {
                const randomNum = Math.floor(Math.random() * 9) + 1;
                image.src = `image${randomNum}.png`;
            });
        }
    </script>
</body>
</html>
