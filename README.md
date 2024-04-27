<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>#1 - Pixel Art Generator | AsmrProg</title>
</head>

<body>

    <div class="wrapper">
        <div class="options">
            <div class="opt-wrapper">
                <div class="slider">
                    <label for="width-range">Grid Width</label>
                    <input type="range" id="width-range" min="1" max="35">
                    <span id="width-value">00</span>
                </div>
                <div class="slider">
                    <label for="height-range">Grid Height</label>
                    <input type="range" id="height-range" min="1" max="35">
                    <span id="height-value">00</span>
                </div>
            </div>

            <div class="opt-wrapper">
                <button id="submit-grid">Create Grid</button>
                <button id="clear-grid">Clear Grid</button>
                <input type="color" id="color-input">
                <button id="erase-btn">Erase</button>
                <button id="paint-btn">Paint</button>
            </div>

        </div>
        <div class="container"></div>
    </div>




    <script src="index.js"></script>
</body>

</html>
