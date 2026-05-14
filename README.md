<!DOCTYPE html>
<html lang="pt-BR">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>🐱 Padaria dos Gatos Terapêuticos 💜</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Pacifico&display=swap" rel="stylesheet">

<style>

/* RESET */
*{
margin:0;
padding:0;
box-sizing:border-box;
}

/* VARIÁVEIS */
:root{
--cor-primaria:#ff8fc7;
--cor-secundaria:#ffb6d9;
--cor-destaque:#ff69b4;
--cor-neutra:#fff0f7;
--texto:#6b2d4f;
}

/* BODY */
html{
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background:linear-gradient(135deg,#fff0f7,#ffe4f1,#ffd6eb);
color:var(--texto);
line-height:1.6;
overflow-x:hidden;
}

/* CONTAINER */
.container{
max-width:1200px;
margin:0 auto;
padding:20px;
}

/* HEADER */
header{
position:relative;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
overflow:hidden;
background:url('https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?auto=format&fit=crop&w=1350&q=80');
background-size:cover;
background-position:center;
}

.overlay{
position:absolute;
inset:0;
background:rgba(255,105,180,0.35);
}

.hero{
position:relative;
z-index:2;
color:white;
padding:20px;
}

.hero h1{
font-family:'Pacifico',cursive;
font-size:4.5rem;
text-shadow:3px 3px 15px rgba(0,0,0,0.5);
animation: brilho 3s infinite alternate;
}

.hero p{
font-size:1.3rem;
margin-top:20px;
}

@keyframes brilho{
from{
text-shadow:0 0 10px rgba(255,255,255,0.5);
}
to{
text-shadow:0 0 25px rgba(255,255,255,1);
}
}

/* BOTÕES */
.btn,
button{
display:inline-block;
margin-top:25px;
padding:15px 35px;
background:var(--cor-secundaria);
color:var(--texto);
border:none;
border-radius:40px;
font-weight:700;
text-decoration:none;
cursor:pointer;
transition:.4s;
box-shadow:0 8px 20px rgba(255,105,180,0.3);
}

.btn:hover,
button:hover{
background:var(--cor-destaque);
color:white;
transform:translateY(-5px) scale(1.05);
box-shadow:0 15px 30px rgba(255,105,180,0.5);
}

/* SECTIONS */
section{
padding:80px 5%;
}

.titulo{
text-align:center;
font-size:2.8rem;
color:var(--cor-destaque);
margin-bottom:50px;
}

/* CARDS */
.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:white;
padding:20px;
border-radius:25px;
text-align:center;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
transition:.4s;
border:2px solid rgba(255,182,217,0.3);
}

.card:hover{
transform:translateY(-10px) scale(1.03);
box-shadow:0 15px 35px rgba(255,105,180,0.3);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
border-radius:20px;
transition:.4s;
}

.card img:hover{
transform:scale(1.05);
}

.card h3{
margin-top:20px;
color:var(--cor-destaque);
}

/* GALERIA */
.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.galeria img{
width:100%;
height:250px;
object-fit:cover;
border-radius:25px;
transition:.4s;
}

.galeria img:hover{
transform:scale(1.05);
}

/* TABELA */
table{
width:100%;
border-collapse:collapse;
background:white;
border-radius:20px;
overflow:hidden;
box-shadow:0 8px 20px rgba(0,0,0,0.1);
}

th,td{
padding:15px;
text-align:center;
}

th{
background:var(--cor-primaria);
color:white;
}

tr:nth-child(even){
background:#fff5fb;
}

/* FORMULÁRIO */
form{
background:white;
padding:40px;
border-radius:30px;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
backdrop-filter:blur(10px);
}

label{
display:block;
margin-top:20px;
font-weight:600;
}

input,
textarea,
select{
width:100%;
padding:15px;
margin-top:10px;
border-radius:15px;
border:2px solid #ffc0e5;
font-family:'Poppins',sans-serif;
transition:.3s;
}

input:focus,
textarea:focus,
select:focus{
border-color:var(--cor-destaque);
outline:none;
box-shadow:0 0 10px rgba(255,105,180,0.3);
}

textarea{
height:130px;
resize:none;
}

/* ÁUDIO */
.video-section{
text-align:center;
}

audio{
width:100%;
max-width:500px;
margin-top:20px;
border-radius:20px;
}

/* FOOTER */
footer{
background:linear-gradient(135deg,#ff8fc7,#ff69b4,#d94f9d);
color:white;
text-align:center;
padding:40px;
margin-top:50px;
}

/* RESPONSIVO */
@media(max-width:768px){

.hero h1{
font-size:2.8rem;
}

.hero p{
font-size:1rem;
}

.titulo{
font-size:2rem;
}

section{
padding:60px 5%;
}

}

</style>
</head>

<body>

<header>

<div class="overlay"></div>

<div class="hero">

<h1>
🐱 Padaria dos Gatos Terapêuticos 💕
</h1>

<p>
O café mais aconchegante da cidade com gatinhos, doces e muito amor.
</p>

<a href="#contato" class="btn">
🐾 Fazer Reserva
</a>

</div>

</header>

<section class="container">

<h2 class="titulo">
⭐ Avaliações dos Clientes
</h2>

<div class="cards">

<div class="card">
<h3>
💖 Ester
</h3>

<p>
“O lugar mais aconchegante do mundo.”
</p>
</div>

<div class="card">
<h3>
☕ Luna
</h3>

<p>
“Os doces são maravilhosos e o ambiente parece um sonho.”
</p>
</div>

<div class="card">
<h3>
🐱 Mochi
</h3>

<p>
“Experiência relaxante perfeita para amantes de gatos.”
</p>
</div>

</div>

</section>

<section class="container">

<h2 class="titulo">
🍰 Nosso Cardápio
</h2>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1519864600265-abb23847ef2c">

<h3>
🎂 Bolo Mochi
</h3>

<p>
Leve e doce como um gatinho.
</p>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085">

<h3>
☕ Latte Art Cat
</h3>

<p>
Com desenho de patinhas.
</p>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93">

<h3>
🧁 Cupcake Pink
</h3>

<p>
Inspirado em cafeterias coreanas.
</p>

</div>

</div>

</section>

<section class="container">

<h2 class="titulo">
📸 Galeria Relaxante
</h2>

<div class="galeria">

<img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba">

<img src="https://images.unsplash.com/photo-1518791841217-8f162f1e1131">

<img src="https://images.unsplash.com/photo-1543852786-1cf6624b9987">

<img src="https://images.unsplash.com/photo-1495360010541-f48722b34f7d">

</div>

</section>

<section class="container">

<h2 class="titulo">
🕒 Horários
</h2>

<table>

<thead>

<tr>
<th>Dia</th>
<th>Abertura</th>
<th>Fechamento</th>
</tr>

</thead>

<tbody>

<tr>
<td>Segunda a Sexta</td>
<td>08:00</td>
<td>19:00</td>
</tr>

<tr>
<td>Sábado e Domingo</td>
<td>09:00</td>
<td>17:00</td>
</tr>

</tbody>

</table>

</section>

<section class="container video-section">

<h2 class="titulo">
🎵 Música Ambiente BTS 💜
</h2>

<audio controls autoplay loop>

<source src="music/bts-save-me.mp3" type="audio/mpeg">

Seu navegador não suporta áudio.

</audio>

</section>

<section class="container" id="contato">

<h2 class="titulo">
💌 Formulário
</h2>

<form>

<label>
Nome:
</label>

<input type="text" placeholder="Digite seu nome">

<label>
E-mail:
</label>

<input type="email" placeholder="Digite seu email">

<label>
Assunto:
</label>

<select>
<option>Reserva</option>
<option>Adoção</option>
<option>Sugestão</option>
</select>

<label>
Mensagem:
</label>

<textarea placeholder="Escreva aqui..."></textarea>

<button type="submit">
Enviar Ronrom 💜
</button>

</form>

</section>

<footer>

<h2>
🐱 Padaria dos Gatos Terapêuticos
</h2>

<p>
Feito com carinho, doces, BTS e gatinhos ☕💜
</p>

</footer>

</body>

</html>
