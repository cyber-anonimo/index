# index
<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula Teorica</title>    
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
<fieldset>
    <legend>Calculadora IMC</legend>
    <fieldset class="fieldset">
        <legend>Peso</legend>
        <input type="text" name="inputPeso" placeholder="Ex: 70 em Kg" id="peso" onkeydown="validaTamanhoInput()"> <span class="span-erro" id="erroInputPeso">Número Maximo 3 caracteres </span>
    </fieldset>
    
    <fieldset class="fieldset">
        <legend>Altura</legend>
        <input type="text" name="inputPeso" placeholder="Ex: 1.75 em cm" id="altura" >
    </fieldset>

    <button id="btn" onclick="calcular()" class="botao-margem botao-cor">Calcular</button> <span id="resultadoTexto"></span> <span id="resultado"></span>

    <img id="imgResultado" src="" >

    <!-- <button onclick="mensagem()">mensagem</button> -->

</fieldset>    


<script src="app.js"></script>
</body>
</html>
