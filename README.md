# prop
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Gissy mi mujer</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color:blueviolet;
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('Ya eres mi mujer de nuevo jeje');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";
            

        }
    </script>
</head>
<body>
    <center>
        <br>
        <br>
        <br>
        <br>
        <br>
    <h1>Quieres ser mi mujer de nuevo?</h1>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="SI" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="NO" />
    <br>
    <br>
    <br>
    <img src="https://images.genius.com/babf22a596133c7057f5a895808caf45.720x720x1.jpg" width="200">
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <h2>Si le logras dar que no, te regalo algo</h2>
    </center> 
</body>
</html>
