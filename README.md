# Practica4
Practica 4: Hipervínculos en HTML

index.html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis redes sociales</title>
    <style>
        body {
            background-color: rgb(241, 252, 180);
        }
        table {
            text-align: center;
            margin: 0 auto;
        }
        .footer {
            background-color: rgb(95, 89, 89); 
            color: black; 
            padding: 15px;
            text-align: center;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td><img src="https://www.grid.cl/blog/wp-content/uploads/2019/03/estrategia-de-marketing-digital-en-redes-sociales-como-empezar.png" /></td>
        </tr>
        <tr>
            <td>
                <table width="80%">
                    <!--tabla 2-->
                    <tr>
                        <th>FACEBOOK</th>
                        <th>TWITTER</th>
                        <th>INSTAGRAM</th>
                    </tr>
                    <tr>
                        <td><img src="imagenes/facebook.png" width="60px" height="60px" /></td>
                        <td><img src="imagenes/twitter.png" width="60px" height="60px" /></td>
                        <td><img src="imagenes/instagram.png" width="60px" height="60px" /></td>
                    </tr>
                    <tr>
                        <td><a href="mifacebook.html">Leer más</a></td>
                        <td><a href="mitwitter.html" target="_blank">Leer más</a></td>
                        <td><a href="miinstagram.html">Leer más</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://www.facebook.com/">Ir al sitio oficial</a></td>
                        <td><a href="https://twitter.com/" target="_blank">Ir al sitio oficial</a></td>
                        <td><a href="https://www.instagram.com/">Ir al sitio oficial</a></td>
                    </tr>
                </table>
                
            </td>
        </tr>
        <tr>
            <td class="footer">
                <p>
                    <b>Universidad Autónoma de Chiapas</b><br> Programación de aplicaciones web
                </p>
                <p>
                    <b>Alumno:</b> Irene Lopez Santiz
                </p>
            </td>
        </tr>
    </table>
</body>
</html>





mifacebook.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Las mejores redes sociales</title>
<style>
h1 { color:red}
p { color:blue}
</style>
</head>
<body>
    <h1>Facebook</h1>
   <p>Continuar...</p>
   <a href="index.html" >Regresar al menú</p>
</body>
</html>





mitwitter.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Las mejores redes sociales</title>
<style>
h1 { color:red}
p { color:blue}
</style>
</head>
<body>
    <h1>Twitter</h1>
   <p>Continuar...</p>
   <a href="index.html" >Regresar al menú</p>
</body>
</html>





miinstagram.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Las mejores redes sociales</title>
<style>
h1 { color:red}
p { color:blue}
</style>
</head>
<body>
    <h1>Instagram</h1>
   <p>Continuar...</p>
   <a href="index.html" >Regresar al menú</p>
</body>
</html>