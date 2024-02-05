# projetoSaga
Esse repositório tem como objetivo guardar o código usado na criação de um site 
HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <link rel="shortcut icon" href="img/Black_And_White_Modern_Vintage_Retro_Brand_Logo-removebg-preview.ico" type="image/x-icon">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FUNDEP</title>
    <link rel="stylesheet" href="css/estilo.css" type="text/css">
</head>
<body>
    
    <div id="interface">
        <div id="cabecalho">
        <img src="img/Design_sem_nome-removebg-preview.png" id="imagem">
    <nav id="menu">
        <ul>
            <li class="titulo"><a href="fazemos.html">O que fazemos</a></li>
            <li class="titulo"><a href="meios.html">Nossos meios de coleta de dados</a></li>
            <li class="titulo"><a href="form.html">Responder formulário</a></li>
        </ul>
    </nav>
</div>
    <div id="texto">
    <h1>Quem somos</h1>
    <p>A FUNDEP é uma vertente da Petrobras com foco em captar a gerenciar dados da população, visando melhorar a situação dos moradores e fazer com que eles possam alcançar um novo estilo de vida.</p>

    <h1>O Que Fazemos</h1>
    <p>Com as nossas tecnologias, coletamos dados das pessoas ao nosso redor, fazendo análises focando na melhora da sitaução de vida delas e no que a comunidade a qual elas pertencem precisa.</p>

    <h1>Tecnologia Utilizada</h1>
    <h2>Site</h2>
    <p>A criação do site foi feita para que as pessoas pudesem saber mais sobre nós, fazendo com que a desconfiança diminuisse. Ele também hospeda o formulário necessário para a coleta de dados, diminuindo o número de acessos desnecessários que uma pessoa precisaria fazer para acessar nosso formulário.</p>
    
    <h2>Formulário</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui minima velit, sed hic magnam, iste quod, autem iusto numquam esse nihil error possimus. Eos pariatur ab quo, necessitatibus incidunt perferendis!</p>

    </div>
     
    <hr>
<footer id="rodape">
    <p>Nossos meio de contato:</p>
    <p>Gmail</p> 
    <p>Telefone</p> 
    
    <p>FUNDEP &COPY;</p> 
</footer>
</body>
</html>


CSS
@charset "UTF-8";

body{
    font-family: Arial, Helvetica, sans-serif;
    width: 100%;
    height: 100%;
    display: block;
    justify-content: center;
    align-items: center;
    background: white;
}

#interface{
     width: 1350px;
     margin: 50px auto 50px auto; 
     padding: 10px;
}

.box{
    background-color: white;
    padding: 0.5px;
    border-radius: 10px;
    width: 60%;
    box-shadow: 0px 0px 5px 5px rgba(0, 0, 0, .212);
    position: center;
}

fieldset{
    border: 0px solid black;
}
legend{
    text-align: center;
    padding: 10px;
}
.inputBox{
    position: relative;
}
.inputUser{
    background: none;
    border: none;
    border-bottom: 1px solid black;
    outline: none;
    color: black;
    font-size: 15px;
    letter-spacing: 2px;
}
.labelnput{
    position: absolute;
    top: 0%;
    left: 0%;
    pointer-events: none;
    transition: .5s;
}
.inputUser:focus ~ .labelnput,
.inputUser:valid ~ .labelnput{
    top: -20px;
    color: black;
}
#submit{
    background-color: lightcyan;
    width: 100%;
}

.titulo{
    font-size: 14px;
}

.titulo2{
    font-size: 17px;
    font-style: italic;
}
p{
    text-align: justify;
}
#menu{
    display: block;
}

#menu ul{
    list-style: none;
    text-transform: uppercase;
    position: absolute;
    top: 20px;
    left: 880px;
}
#menu li{
    display: inline-block;
    background-color: none;
    padding: 8px;
    margin: 4px;
    transition: background-color 1s;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

#menu li:hover{
    background-color: #606060;
}

#menu a{
    color: black;
    text-decoration: none;
}

#menu a:hover{
    color: white;
    text-decoration: underline;
}

#imagem{
    position: absolute;
    height: 100px;
    left: 300px;
    top: 7px;
    margin-bottom: 500px;
}

#texto{
    margin-top: 50px;
}

#botao{
    background-color: none;
    padding: 8px;
    margin: 4px;
    transition: background-color 1s;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    border-radius: none 5px;
    display: block;
    text-transform: uppercase;
    border: none;
}

#botao:hover{
    background-color: #606060;
}

#botao a{
    color: black;
    text-decoration: none;
}

#botao a:hover{
    color: white;
    text-decoration: underline;
}

#rodape{
    margin: 10px;
}
#cabecalho{
    border-bottom: 1px #606060 solid;
    height: 50px;
}
