# ejercicio_seudo
Ejercicio0_1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="06_seudoclases.css">
    <style>
    *{
    margin: 0;
    padding: 0;
}
.boton{
    padding: 12px;
    margin-top: 15px;
}
.boton::before{
    
    content: "Pasa por encima";
}
.boton:hover{
    color: white;
   background-color: green;
}
.boton::after{
    content: "!Hecho";
}</style>
    <title>Seudo Clases</title>
</head>
<body>
    
    <button class="boton"></button>
   
</body>
</html>
