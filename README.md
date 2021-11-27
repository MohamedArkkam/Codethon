
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <title>Draw Something
        </title>
        <body>
            <canvas id="c" width="400" height="300">
                <canvas id="c" width="400" height="300"
                style="border: 1px solid #C3C3C3;">
                </canvas>
                <body onload="drawOnCanvas();"></body>
        </body>
        <script>
            function drawOnCanvas() {
                var c = document.getElementById("c");
                var ctx = c.getContext("2d");
// set fill color to green
ctx.fillStyle = "#00ff00";
// draw filled rectangle
ctx.fillRect(50, 50, 200, 150);
// trace first diagonal
ctx.moveTo(50, 50);
ctx.lineTo(250, 200);
// draw second diagonal
ctx.moveTo(250, 50);
ctx.lineTo(50, 200);
// draw diagonals in red
ctx.strokeStyle = "#ff0000";
ctx.stroke();
}
        </script>
    </head>
</html>


