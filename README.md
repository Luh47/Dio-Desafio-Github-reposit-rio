# Repositório de Desafio de projeto Git/GitHub da DIO
Dio Desafio de GitHub - Repositório Com meus códigos HTML
## Links Úteis
[Sintaxe básica Markdown](https://www.markdownguide.org/basic-syntax/)

file:///home/luiz/Documentos/Site/index.html

Site Luiz Html

<!DOCTYPE html>
<html lang="pt-br">

<head>
<meta charset="UTF-8" />
<meta id="viewport" name="viewport" content="width=device-width, user-scalable=no">
<title> LUH Silva </title>
<link rel="stylesheet" href="Style.css" />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pushster&display=swap" rel="stylesheet">
</head>

<body>
<!-- olá filho da mãe -->
<header>
<h2>Olá! Como está? Tudo em cima ?
Curta a página, explore ela. É isso aí meu amigo, estude sempre beleza? Não deixe de estudar e se desenvollver, rumo ao progresso!!
</h2>
</header>
</br>
<nav>
<div class="lata">
<a href="/home/luiz/Documentos/Site/index.html">Home</a>
<a href="/home/luiz/Documentos/Site/Teste.html/Formulário.html">Formulário</a>
<a href="/home/luiz/Documentos/Sites.2/index.html">Teste</a>
</div>
</nav> 
</br> </br>

<div><img class="futuro" src="/media/luiz/Linux Edu/índice2.jpeg" alt="Lobão" /></div>
<a class="cinco" href="#filura">Ir para a lista</a>
</br>
<h1 class="um">
<i>A chapeuzinho</i> <em>Blue</em>
</h1>
</br>
<p class="texto"><i>Era uma vez, a chapeuzinho Blue, uma garota extrovertida e inteligente,</i>
</br>crazy por assim dizer, andava sem preocupação pois claramente era crazy.</p>
<p class="texto">
</br> Veio o lobo mal e a matou, fim da história.</p>
<p class="texto">
</br> Boa leitura!!
</br> Brincadeira kakakaka</p>
</br>
<a href="https://www.google.com/">Ir para o site google</a>
</br>

<img class="abaixo" src="/media/luiz/Linux Edu/índice3.png" alt="Logo do google" />
</br>

<a href="https://www.google.com/">Botão clique em mim:
</br>
<input type="checkbox" name="nome" id="nome"/> </br>

<button href="https://www.google.com/">Clique em mim</button></a>
</br>
</br>
<h3 id="filura">Lista de Torta</h3>
<ol>
<li>Frango empanado</li>
<li>Farinha com Fermento</li>
<li>Leite</li>
<li>4 Ovos</li>
<li>Manteiga</li>
<li>Ervilha e milho</li>
<li>Cenoura Ralada</li>
<li>Atum</li>
</ol>

</br>
</br>

<table border= "2" id="bore">
<caption class="num">Minha Tabela Demonstrativa</caption>

<thaed>
<tr bgcolor="#955999">
<th scope="col">Fígaro 1</th>
<th scope="col">Calc 2</th>
<th scope="col"> AJ 3</th>
</tr>
</thaed>

<tbody>
<tr>
<td>Olá Novato</td>
<td>Olá Gafanhoto</td>
<td>Salve uhuu</td>

</tr>

<tr>
<td>Olá Amigo</td>
<td>Salve Aprendiz</td>
<td>Salve uhuu</td>

</tr>

<tr>
<td>Qual a Nova?</td>
<td>Como você está?</td>
<td>Salve uhuu</td>

</tr> 
<tr>
<td>Olá Salve</td>
<td>Olá Konichuá</td>
<td>Salve uhuu</td>

</tr> 

</tbody>
</table>
</div>

<script>
function typeWrite(elemento) {
const textoArray = elemento.innerHTML.split('');
elemento.innerHTML = '';
textoArray.forEach((letra, i) => {
setTimeout(() => elemento.innerHTML += letra, 75 * i)
})
}

const titulo = document.querySelector('h2');
typeWrite(titulo);
</script>
</body>

</br>
</br>

<footer> <a href="/home/luiz/Documentos/Site/Teste.html/Formulário.html">Clique em mim!</a> </br> 
</br>

<div class="video-area">
<iframe width="50%" height="100%" src="/home/luiz/Vídeos/REVELEI A MELHOR ESTRATEGIA PARA GANHAR DINHEIRO NO OTC DA IQ OPTION EM 2022!.mp4"> video </iframe>
</div>

</footer>
</html>
 
 Style CSS
 * {
box-sizing: border-box;
margin: 0px;
padding: 0px;
}
/* olá !! Vai estudar Pô */

body {
font-family: 'Pushster', 'cursive';

}

.lata {
width: 50%;
height: 50%;
margin: auto;
padding: auto;
box-sizing: none;
border: none;
position: absolute;
top: 0px;
}

.lata > a {
height: 30px;
color:#00ff00;
font-size: 57px;
margin: 0 15px;
}

h1 {
color: blue;
font-size: 25px;
border: 5px #55ff
}

.um:hover {
color: red;
border: 7px solid red;
}

.texto {
color: greenyellow;
font-size: 25px;
border: 5px solid #55ff
}

.texto:hover {
color: red;
border: 7px solid red;
}

#filura {
font-size: 30px;
color: aquamarine;
width: 200px
}

#filura:hover {
color: red;
font-size: 33px;
}

body {
background-color: black;
padding: auto;
border: 20px;
margin: 200pt;
padding-right: 5px;
}

p {
font-size: 15px;
color: white;
border: 5px solid #00ff;
}

ol {
font-size: 33px;
color: white;
margin-top: auto;
border: 5px solid #00ff;
padding: 50px;
}

ol:hover {
font-size: 50;
color: blue;
border-radius: 50px;
}

.um {
background-color: white;
border: 5px solid #00ff;
}

div {
font-size: 30px;
color: white;
border: 5px double #00ff00;
}

.futuro {
border: 8px groove blueviolet;
display: flex;
justify-content: center;
align-items: center;
padding: center;
border-radius: 100px;
width: 50px;
height: 50px;
}

.futuro:hover {
width: 100px;
height: 100px;
border-radius: 200px;
}

a {
font-size: 30px;
color: blue;
border: 5px double #00ff00;
padding: 10px;
margin: 5px;
}

.abaixo {
padding: 10px;
margin: 10px;
width: 275px;
height: 150px;
flex-direction: column;
}

.cinco {
width: 30px;
height: 30px;
border: none;
}

#bore {
background: #ccc;
color: blue;
font-size: 30px;
}

tbody > tr:nth-child(2n) {
background-color: rgb(98, 146, 194);
border-bottom: 2px solid #00ff00;
width: 300px;
border: 10px;
}

thead, td:hover {
background-color: red;
}

.num {
font-size: 1.sem;
font-weight: bold;
padding: 10px;
background-color:rgb(6, 199, 233);
}
h2 {
font-size: 50px;
color:rgb(6, 199, 233);
}

a {
font-size: 50px;
color:blueviolet;
display: inline;
border: none;
}

#nove {
height:500px;
width: 500px;
border: 10px solid rgb (10,20,85);
}


.video {
width: 600px;
max-width: 800px;
}

.video-area {
position: relative;
height: 0px;
background-color: #ccc;
padding: 0px 0px 56.20%;
}

.video-area iframe {
position: absolute;
top: 0px;
bottom: 0px;
width: 100%;
height: 100%;
border: 0px;
}
