<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conversor de dollar &#x1F4B8</title>
    <link rel="shortcut icon" href="IMG/icon.ico" type="image/x-icon">
    
    <!--<link rel="stylesheet" href="css/style.css"> -->       
    <style>
        a:link{
            text-decoration: none;
            color: #c5c5d1;
        }
        body{
            background-color: blue;
            margin: 0 auto;
        }
        nav {
            width: 100%;
            background-color: lightblue;
            display: flex;
            margin-top: -45px;
        }
        ul {
            position: fixed;
            margin:auto;
            list-style: none;
            text-decoration: none;
        }
        li {
            display: inline-block;
            padding: 10px;
            transition: background-color 1s;
            text-decoration: none;
        }
        li:hover{
            background-color: black;
        }
        .logo{
            background-color: #0317ff;
            width: 100%;
            height: 60px;
            margin-top: -10px;
            float: inline-end;
            position: relative;
        }
        .joaovitor {
            width: 100%;
            position: relative;
            color:#0400ff;
            margin-top: 34px;
            margin-left: 1%;
            display: flex;
        }
        .back2{
            background-color:black; 
            width: 100%;
            height: 60px;
            margin-top: -70px;
        }
        h1.titulo {
            color: rgb(0, 4, 255);
            margin-top: 15px;
            margin-left: 10px;
        }
        
        /* SESSAO 1*/
        .sessao {
            margin-top: -69px;
            width: 100%;
            display: flex;
        }
        .col-usa{
            width: 300px;
            height: 500px;
            margin-top: 15px;
            margin-left: 20px;
            background-size: 80%;
            background-image: url(IMG/brasileusa.png);
            background-repeat: no-repeat;
        }
        .valor{
            color:rgb(255, 255, 255);
        }
        input{
            width: 80px;
            height: 20px;
            border-radius: 5px;
            margin-top: 15px;
        }
        input.dolar{
            margin-left: 3px;
        }
        .anuncio{
            color: rgb(255, 0, 0);
            color:white;
        }
        .valor-do-dollar{
            margin-left: 15px;
        }
        .doacao{
            margin-left: 15px;
        }
        .sobre-nos{
            margin-left: 15px;
        }
    </style>
</head>

<body>
    <!-- LOGO -->
    <div class="logo"></div>   

    <nav>
        <ul>
            <li><a href="https://joaovitor123.000webhostapp.com">Home</a></li>
            <li><a href="https://www.remessaonline.com.br/cotacao/cotacao-dolar" target="_Blank">Valor do Dolar Americano</a></li>
            <li><a href="https://joaovitor123.000webhostapp.com" target="_Blank">Doação</a></li>
            <li><a href="https://joaovitor123.000webhostapp.com" target="_Blank">Sobre nos</a></li>
        </ul>
    </nav>   

      <!-- TITULO PRINCIPAL -->
    <div class="joaovitor">
        <h1>                 
            João Vitor
        </h1>
    </div>

    <!-- TITULO SECUNDARIO -->
    <div class="back2"></div>
    <!--titulo--> 
    <h1 class="titulo" >
        conversor de dolar pra reais &#x1F4B8
    </h1>  

    <div class="sessao">      
        <!-- IMAGEM -->
        <div class="col-usa">
        </div>

        <div class="col-anucio">

            <div class="texto2"> 
                <p class="valor"
                >insira o valor do dolar aqui em baixo &#x1F447</p>
            </div>
        
            <!-- Campos de insersao -->
            <input type="text">
            <input type="text" class="dolar">
            <div class="anuncio">
                <h4>Assita o anuncio para ver o resultado &#x1F3A5 </h4>
                <h3</h3>
            </div> 
        
        </div>
    </div>
<div class="valor-do-dollar">
    <h1>Valor do dolar</h1>

    <pre>O Dolar Americano muda todo dia.
Por isso atualizamos o site 24h.
    </pre>
</div>

<div class="doacao">
    <h1>Doação</h1>
        <p>
            voce pode nos mandar um pix para me ajudar.
        </p>
</div>

<div class="sobre-nos">
    <h1>Sobre nos</h1>
    <p>eu fiz esse site sozinho, tenho 12 anos e ja sou um programador, tento fazer o melhor para voces &#x2764</p>
</div>
</html>
