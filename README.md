<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Agro Aventura</title>

<style>
body{
    font-family:Arial;
    background:#dff7df;
    text-align:center;
}

.caixa{
    width:500px;
    margin:50px auto;
    background:white;
    padding:20px;
    border-radius:20px;
    box-shadow:0 0 10px gray;
}

input{
    padding:10px;
    width:200px;
}

button{
    padding:10px 20px;
    background:green;
    color:white;
    border:none;
    border-radius:10px;
}
</style>

</head>
<body>

<div class="caixa">
    <h1>🌱 Agro Aventura 🌱</h1>

    <h2 id="pergunta">
        Qual máquina é usada para colher grãos?
    </h2>

    <input id="resposta" type="text">

    <br><br>

    <button onclick="verificar()">
        Responder
    </button>

    <h3 id="pontos">⭐ Pontos: 0</h3>
</div>

<script>

let pontos = 0;

function verificar(){

let resposta =
document.getElementById("resposta")
.value.toLowerCase();

if(resposta=="colheitadeira"){
    pontos++;
    alert("Parabéns! Você acertou!");
}else{
    alert("Resposta incorreta!");
}

document.getElementById("pontos")
.innerHTML = "⭐ Pontos: " + pontos;

}

</script>

</body>
</html>
