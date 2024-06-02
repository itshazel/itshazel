><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hazyverse</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: beige;
            color: black;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            color: black;
            text-align: center;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .grid-item {
            background-color: white;
            border: 1px solid black;
            padding: 20px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Hazyverse</h1>
    <div class="grid-container">
        <!-- Add your Pinterest-like content here -->
        <div class="grid-item">
            <img src="image1.jpg" alt="Image 1">
            <p>Description for Image 1</p>
        </div>
        <div class="grid-item">
            <img src="image2.jpg" alt="Image 2">
            <p>Description for Image 2</p>
        </div>
        <!-- Add more grid items as needed -->
    </div>
</div>

</body>
</html>
