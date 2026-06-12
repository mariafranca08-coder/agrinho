<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agro Forte - Futuro Sustentável</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#d8f5d0;
}

#inicio{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(#d8f5d0,#b7e4a7);
text-align:center;
padding:20px;
}

#inicio h1{
color:#1b5e20;
font-size:42px;
margin-bottom:20px;
}

#inicio input{
padding:12px;
width:280px;
border-radius:10px;
border:1px solid #999;
margin-bottom:15px;
}

#inicio button{
padding:12px 25px;
background:#2e7d32;
color:white;
border:none;
border-radius:10px;
cursor:pointer;
font-size:18px;
}

#app{
display:none;
max-width:1200px;
margin:auto;
padding:20px;
}

.caixa{
background:white;
padding:20px;
border-radius:15px;
box-shadow:0 3px 10px rgba(0,0,0,0.15);
margin-bottom:20px;
}

.banner img{
width:100%;
height:350px;
object-fit:cover;
border-radius:15px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:15px;
margin-top:20px;
}

.card{
background:#e8f5e9;
padding:20px;
border-radius:15px;
border-left:5px solid #2e7d32;
}

.card h3{
color:#1b5e20;
margin-bottom:10px;
}

.frase{
background:#2e7d32;
color:white;
padding:20px;
text-align:center;
font-size:22px;
font-weight:bold;
border-radius:15px;
margin-top:20px;
}

.menu{
display:flex;
justify-content:center;
gap:10px;
flex-wrap:wrap;
margin-top:20px;
}

.menu button{
padding:12px 20px;
background:#2e7d32;
color:white;
border:none;
border-radius:10px;
cursor:pointer;
}

.secao{
display:none;
margin-top:20px;
}

.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.cardFoto{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 3px 10px rgba(0,0,0,0.15);
}

.cardFoto img{
width:100%;
height:220px;
object-fit:cover;
}

.cardFoto h3{
padding:10px;
color:#1b5e20;
}

.cardFoto p{
padding:0 10px 15px;
line-height:1.6;
}

.pergunta{
background:#f1fff1;
padding:15px;
border-radius:10px;
margin-bottom:15px;
border-left:5px solid green;
}

.tabuleiro{
display:grid;
grid-template-columns:repeat(5,80px);
gap:10px;
justify-content:center;
margin-top:20px;
}

.carta{
width:80px;
height:80px;
background:#4caf50;
display:flex;
justify-content:center;
align-items:center;
font-size:35px;
border-radius:10px;
cursor:pointer;
color:white;
}

</style>
</head>

<body>

<div id="inicio">

<h1>🌱 Agro Forte: Futuro Sustentável 🌱</h1>

<input type="text" id="nome" placeholder="Digite seu nome">

<button onclick="entrar()">Entrar</button>

</div>

<div id="app">

<div class="caixa">

<h2 id="saudacao"></h2>

<br>

<div class="banner">
<img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=1200">
</div>

<br>

<p>
O Agro Forte representa um futuro sustentável baseado no equilíbrio entre produção e meio ambiente.
A agricultura moderna busca produzir alimentos preservando a natureza, economizando água, protegendo o solo
e garantindo qualidade de vida para as futuras gerações.
</p>

<div class="cards">

<div class="card">
<h3>🚜 Tecnologia no Campo</h3>
<p>Máquinas modernas ajudam a aumentar a produtividade agrícola.</p>
</div>

<div class="card">
<h3>💧 Economia de Água</h3>
<p>A irrigação inteligente reduz desperdícios e preserva recursos naturais.</p>
</div>

<div class="card">
<h3>🌳 Preservação Ambiental</h3>
<p>Proteção da fauna, flora e recursos naturais.</p>
</div>

<div class="card">
<h3>🌞 Energia Limpa</h3>
<p>Energia solar contribui para um futuro sustentável.</p>
</div>

</div>

<div class="frase">
🌱 Produzir hoje pensando no amanhã. 🌱
</div>

<div class="menu">
<button onclick="mostrar('fotos')">📷 Fotos</button>
<button onclick="mostrar('quiz')">📝 Quiz</button>
<button onclick="mostrar('memoria')">🧠 Jogo da Memória</button>
</div>

<!-- FOTOS -->

<div id="fotos" class="secao caixa">

<h2>📷 Fotos da Agricultura Sustentável</h2>

<div class="galeria">

<div class="cardFoto">
<img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?w=800">
<h3>🥕 Produção de Hortaliças</h3>
<p>
As hortaliças são fundamentais para a alimentação saudável e para a agricultura.
Cultivos como cenoura, alface e beterraba fornecem nutrientes importantes para a população.
A produção sustentável de hortaliças ajuda a preservar o solo, economizar água e garantir alimentos de qualidade.
</p>
</div>

<div class="cardFoto">
<img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854?w=800">
<h3>🌳 Preservação Ambiental</h3>
<p>
A preservação da natureza é fundamental para o futuro.
As áreas verdes ajudam a proteger rios, animais e o solo.
O equilíbrio entre produção e meio ambiente é essencial.
</p>
</div>

<div class="cardFoto">
<img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=800">
<h3>🌾 Produção Agrícola</h3>
<p>
A agricultura fornece alimentos para milhões de pessoas.
Quando realizada de forma sustentável reduz impactos ambientais.
Produzir e preservar devem caminhar juntos.
</p>
</div>

</div>

</div>

<!-- QUIZ -->

<div id="quiz" class="secao caixa">

<h2>📝 Quiz Agro Sustentável</h2>

<div id="quizPerguntas"></div>

<button onclick="corrigirQuiz()">Finalizar Quiz</button>

<h3 id="resultadoQuiz"></h3>

</div>

<!-- MEMÓRIA -->

<div id="memoria" class="secao caixa">

<h2>🧠 Jogo da Memória</h2>

<div class="tabuleiro" id="tabuleiro"></div>

<h3 id="resultadoMemoria"></h3>

</div>

</div>

<script>

function entrar(){

let nome=document.getElementById("nome").value;

if(nome==""){
alert("Digite seu nome!");
return;
}

document.getElementById("inicio").style.display="none";
document.getElementById("app").style.display="block";

document.getElementById("saudacao").innerHTML=
"Olá, "+nome+"! Seja bem-vindo ao nosso aplicativo.";

}

function mostrar(id){

document.querySelectorAll(".secao").forEach(secao=>{
secao.style.display="none";
});

document.getElementById(id).style.display="block";

}

const perguntas=[

["O que é agricultura sustentável?",["Produção com preservação ambiental","Desmatamento"],0],
["Qual recurso natural deve ser preservado?",["Água","Poluição"],0],
["Qual energia é renovável?",["Solar","Carvão"],0],
["O que ajuda a natureza?",["Reciclagem","Lixo no rio"],0],
["Qual prática protege o solo?",["Plantio consciente","Queimadas"],0],
["O que é compostagem?",["Produção de adubo","Poluição"],0],
["O que reduz impactos ambientais?",["Sustentabilidade","Desperdício"],0],
["O que devemos preservar?",["Fauna e flora","Poluição"],0],
["Qual é o objetivo do agro sustentável?",["Produzir e preservar","Destruir recursos"],0],
["O Agro Forte busca:",["Equilíbrio ambiental","Mais poluição"],0]

];

let html="";

perguntas.forEach((p,i)=>{

html+=`
<div class="pergunta">
<b>${i+1}. ${p[0]}</b><br><br>

<label>
<input type="radio" name="q${i}" value="0">
${p[1][0]}
</label>

<br><br>

<label>
<input type="radio" name="q${i}" value="1">
${p[1][1]}
</label>
</div>
`;

});

document.getElementById("quizPerguntas").innerHTML=html;

function corrigirQuiz(){

let pontos=0;

perguntas.forEach((p,i)=>{

let r=document.querySelector('input[name="q'+i+'"]:checked');

if(r && Number(r.value)==p[2]){
pontos++;
}

});

document.getElementById("resultadoQuiz").innerHTML=
"✅ Você acertou "+pontos+" de 10 perguntas.";

}

let emojis=[
"🌱","🌱",
"🚜","🚜",
"🌾","🌾",
"🌳","🌳",
"☀️","☀️",
"💧","💧",
"🐝","🐝",
"🌻","🌻",
"🥕","🥕",
"🍅","🍅"
];

emojis.sort(()=>Math.random()-0.5);

let primeira=null;
let segunda=null;
let bloqueado=false;
let pares=0;

emojis.forEach(simbolo=>{

let carta=document.createElement("div");

carta.className="carta";
carta.innerHTML="?";

carta.onclick=function(){

if(bloqueado || carta.innerHTML!="?") return;

carta.innerHTML=simbolo;

if(!primeira){
primeira=carta;
return;
}

segunda=carta;

if(primeira.innerHTML===segunda.innerHTML){

pares++;

primeira=null;
segunda=null;

if(pares===10){

document.getElementById("resultadoMemoria").innerHTML=
"🎉 Parabéns! Você completou o jogo da memória!";

}

}else{

bloqueado=true;

setTimeout(()=>{

primeira.innerHTML="?";
segunda.innerHTML="?";

primeira=null;
segunda=null;

bloqueado=false;

},800);

}

};

document.getElementById("tabuleiro").appendChild(carta);

});

</script>

</body>
</html>