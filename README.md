# Quasi-Deus.github.io
Image Presets-Using Javascript
<html>
    <head>
        <script type="text/javascript" src= "DLTP JS.js"></script>
        <script type="text/javascript" src="Picture Filter.js"></script>
        <link rel="stylesheet" type="text/css" href="Picture Filter.css">
    </head>
    </script>
    <body>
        <div id=d>
        <canvas id="white"></canvas>
        <p style="text-align: center; padding-left:60px">
            <b>Image</b>
            <input type="file" id="in" multiple= "false"  accept=image/* onchange="upload()";>
        </p>
        <p style="padding-left: 6px;"><b>Filters</b></p>
        <table>
            <tr>
               <td> <input type="button" value="Grayscale" onclick="Gray()"></td>
               <td><input type="button" value="Invert" onclick="invert()"></td>
            </tr>
            <tr>
                <td><input type="button" value="Red Filter" onclick="Red()"></td>
                <td><input type="button" value="Sepia" onclick="sepia()"></td>
            </tr>
            <tr>
                <td><input type="button" value="Blur" onclick="disorder()"></td>
                <td><input type="button" value="Horizontal Flip" onclick="hmirror()"></td>
            </tr>
            <tr>
               <td> <input type="button" value="Rainbow" onclick="rainbow()"></td>
               <td><input type="button" value="Vertical Flip" onclick="vmirror()"></td>
            </tr>
            <tr>
                <td><input type="button" value="Reset" onclick="reset()"></td>
                <td><input type="button" value="Horizontal and Vertical Flip" onclick="absmirror()"></td>
         </tr>
        </table>
        </div>
    </body>
</html>
<!--onclick only uploads the image.
onchange uploads and displays the image.-->
