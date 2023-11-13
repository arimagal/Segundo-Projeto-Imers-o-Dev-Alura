# Segundo-Projeto-Imers-o-Dev-Alura
Segundo projeto do Dia da Imersao Alura - Convertendo Anos Luz em KM

HTML
<div class="container">
  <h1 class="page-title">
    Anos Luz em Quilometros
  </h1>
  <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/logo-imersao-aluraflix.svg" class="page-logo" alt="">
</div>
<a href="https://alura.com.br/" target="_blank">
  <img src="https://www.alura.com.br/assets/img/home/alura-logo.svg" alt="" class="alura-logo">
  <img src="https://www.starpng.com/public/uploads/preview/meteor-png-4-11583843264zr7cwzv8jk.png">
</a>

CSS
body {
  font-family: "Roboto Mono", monospace;
  text-align: center;
  background-image: url("https://i.pinimg.com/originals/e8/6f/1a/e86f1afbaceb48180b6b4d650f61e2b2.jpg");
  background-color: #ffffff;
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
  height: 100vh;
}

.container {
  text-align: center;
  padding: 20px;
}

.page-title {
  color: #ffffff;
  margin: 0 0 5px;
}

.page-subtitle {
  color: #ffffff;
  margin-top: 5px;
}

.page-logo {
  width: 200px;
}

.alura-logo {
  width: 40px;
  position: absolute;
  top: 10px;
  right: 10px;
}

body > img {
  margin: 0 10px;
}

img {
  max-height: 250px;
}

JS
var valorEmAnosLuz = 2;
var quilometrosDeAnosLuz = 9460730472580.8;

var valorEmAnosLuz = Number(prompt("Digite o valor em Bitcoin:"));

var valorEmQuilometros = valorEmAnosLuz * quilometrosDeAnosLuz;
valorEmQuilometros = valorEmQuilometros;
alert("Resultado de AnosLuz em Quilometros " + valorEmQuilometros + " KM ");
