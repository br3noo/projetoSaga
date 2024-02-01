# projetoSaga
Esse repositório tem como objetivo guardar o código usado na criação de um site 
HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <link rel="shortcut icon" href="img/Black_And_White_Modern_Vintage_Retro_Brand_Logo-removebg-preview.ico" type="image/x-icon">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
    <link rel="stylesheet" href="css/estilo.css" type="text/css">
</head>
<body>
    
    <div id="interface">
        <div id="cabecalho">
        <img src="img/Design_sem_nome-removebg-preview.png" id="imagem">
    <nav id="menu">
        <ul>
            <li class="titulo"><a href="somos.html">Quem somos</a></li>
            <li class="titulo"><a href="fazemos.html">O que fazemos</a></li>
            <li class="titulo"><a href="meios.html">Nossos meios de coleta de dados</a></li>
            <li class="titulo"><a href="formulario.html">Responder formulário</a></li>
        </ul>
    </nav>
</div>
    <div id="texto">
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Commodi molestiae quod quas culpa autem non aspernatur doloribus ratione! Impedit, eos assumenda quia necessitatibus sint vitae eum maxime laudantium officia. Corporis.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut eius maxime laboriosam esse error sunt quae blanditiis veritatis possimus, quam nemo enim velit consequatur nesciunt ipsam saepe pariatur tempora. Fugiat.</p>
    
    <div class="box">
        <form action="" id="ajuste">
            <fieldset>
                <legend><b><i>Preencha esse formulário e nos ajude a melhorar a situação da comunidade!</i></b></legend>
                <hr>
                <br>
                <div class="inputBox">
                    <input type="text" name="estado" id="estado" class="inputUser" required>
                    <label for="estado" class="labelnput">Estado</label>
                </div>
                <br><br>
                <div class="inputBox">
                    <input type="text" name="cidade" id="cidade" class="inputUser" required>
                    <label for="cidade" class="labelnput">Cidade</label>
                </div>
                <br><br>
                <div class="inputBox">
                    <label for="residencia">Quantas pessoas habitam na residência?</label>
                    <select name="residencia" id="residencia" class="inputUser" required>
                        <option value=""></option>
                        <option value="1_pessoa">1 pessoa</option>
                        <option value="2_pessoas">2 pessoas</option>
                        <option value="3_pessoas">3 pessoas</option>
                        <option value="4_ou_mais">4 ou mais pessoas</option>
                    </select>
                </div>
                <br><br>
                <div class="inputBox">
                    <label for="escolaridade">Nível de escolaridade:</label>
                    <select name="escolaridade" id="escolaridade" class="inputUser" required>
                        <option value=""></option>
                        <option value="1">Ensino fundamental imcompleto</option>
                        <option value="2">Ensino fundamental completo</option>
                        <option value="3">Ensino médio imcompleto</option>
                        <option value="4">Ensino médio completo</option>
                        <option value="5">Ensino superior imcompleto</option>
                        <option value="6">Ensino superior completo</option>
                    </select>
                </div>
                <br><br>
                <div class="inputBox">
                    <label for="renda">Renda per capita:</label>
                    <select name="renda" id="renda" class="inputUser" required>
                        <option value=""></option>
                        <option value="salario1">Até R$1.000,00</option>
                        <option value="salario2">De R$1.001,00 até R$2.000,00</option>
                        <option value="salario3">De R$2.001,00 até R$3.000,00</option>
                        <option value="salario4">De R$3.001,00 até R$4.000,00</option>
                        <option value="salario5">De R$4.001,00 até R$5.000,00</option>
                        <option value="salario6">De R$5.001,00 até R$10.000,00</option>
                        <option value="salario7">Acima de R$10.001,00</option>
                    </select>
                </div>
                <br><br>
                <div class="inputBox">
                    <label for="datanascimento">Data de nascimento:</label>
                    <input type="date" id="datanascimento" name="datanascimento" class="inputUser" required>
                </div>
                <br><br>
                <div class="inputBox">
                    <label for="moradia">Tipo de moradia</label>
                    <select name="moradia" id="moradia" class="inputUser" required>
                        <option value=""></option>
                        <option value="casa">Casa</option>
                        <option value="condominio">Condomínio</option>
                        <option value="apartamento">Apartamento</option>
                    </select>
                </div>
                <br><br>
                <div class="inputBox">
                    <label for="estadocivil">Estado civil:</label>
                    <select name="estadocivil" id="estadocivil" class="inputUser" required>
                        <option value=""></option>
                        <option value="solteiro">Solteiro(a)</option>
                        <option value="casado">Casado(a)</option>
                        <option value="divorciado">Divorciado(a)</option>
                        <option value="viuvo">Viúvo(a)</option>
                    </select>
                </div>
                <br><br><!--Colocar para as labels do tupo input aparecem apenas se a bolinhas sim forem clicadas-->
                <div class="inputBox" aria-required="true">
                    <label>Tem filhos?</label>
                    <br>
                    <input type="radio" name="filhos" id="filhosim" class="inputUser">
                    <label for="filhosim">Sim</label>
                    <input type="radio" name="filhos" id="filhonao" class="inputUser">
                    <label for="filhonao">Não</label>
                    <br>
                    <label for="quantidadefilhos">Se sim, quantos filhos(as)?</label>
                    <input type="text" name="quantidadefilhos" id="quantidadefilhos" class="inputUser">
                </div>
                <br>
                <div class="inputBox" aria-required="true">
                    <label>Qual seu sexo?</label>
                    <br>
                    <label for="masculino">
                        <input type="radio" id="masculino" name="genero" class="inputUser">
                        Masculino 
                    </label>
                    <label for="feminino">
                        <input type="radio" id="feminino" name="genero" class="inputUser">
                        Feminino
                    </label>
                    <label for="outro">
                        <input type="radio" id="outro" name="genero" class="inputUser">
                        Outro
                    </label>
                    <label for="naodizer">
                        <input type="radio" id="naodizer" name="genero" class="inputUser">
                        Prefiro não dizer 
                    </label>
                </div>
                <br><br><br>
                <div class="inputBox" aria-required="true">
                    <label>Você tem acesso a uma escola?</label>
                    <br>
                    <input type="radio" name="escola" id="escolasim" class="inputUser">
                    <label for="escola">Sim</label>
                    <input type="radio" name="escola" id="escolanao" class="inputUser">
                    <label for="escola">Não</label>
                </div>
                <label for="distanciaescola">Se sim, qual a distância da moradia até a escola?</label>
                <input type="text" id="distanciaescola" name="distanciaescola" class="inputUser">
                <br><br><br>
                <div class="inputBox" aria-required="true">
                    <label>Você tem acesso a internet?</label>
                    <br>
                    <input type="radio" name="acessointernet" id="internetsim" class="inputUser">
                    <label for="internetsim">Sim</label>
                    <input type="radio" name="acessointernet" id="internetnao" class="inputUser">
                    <label for="internetnao">Não</label>
                </div>
                    <label for="distanciaescola">Se sim, como é o acesso a internet?</label>
                <input type="text" id="distanciaescola" name="distanciaescola" class="inputUser">
                <br><br><br>
                <div class="inputBox" aria-required="true">
                    <label>Tem acesso a água potável?</label>
                    <br>
                    <input type="radio" name="agua" id="aguasim" class="inputUser">
                    <label for="aguasim">Sim</label>
                    <input type="radio" name="agua" id="aguanao" class="inputUser">
                    <label for="aguanao">Não</label>
                </div>
                <label for="acessoagua">Se sim, como é o acesso a água potável?</label>
                <input type="text" name="acessoagua" id="acessoagua" class="inputUser">
                <br><br><br>
                <div class="inputBox" aria-required="true">
                    <label>Tem acesso a esgoto?</label>
                    <br>
                    <input type="radio" name="esgoto" id="esgotosim" class="inputUser">
                    <label for="esgotosim">Sim</label>
                    <input type="radio" name="esgoto" id="esgotonao" class="inputUser">
                    <label for="esgotonao">Não</label>
                </div>
                <label for="acessoesgoto">Se sim, como é o acesso ao esgoto?</label>
                <input type="text" name="acessoesgoto" id="acessoesgoto" class="inputUser">
                <br><br><br><!--Colocar para as labels do tupo input aparecem apenas se a bolinhas sim forem clicadas-->
                <div class="inputBox" aria-required="true">
                    <label for="religiao">Quais suas principais crenças religiosas?</label>
                    <input type="text" name="religiao" id="religiao" class="inputUser">
                    <br><br><br>
                    <label for="lazer">Quais suas principais formas de lazer?</label>
                    <input type="text" name="lazer" id="lazer" class="inputUser">
                    <br><br><br>
                    <label for="cultura">Quais suas principais atividades culturais?</label>
                    <input type="text" name="cultura" id="cultura" class="inputUser">
                </div>
            </fieldset>
            <input type="submit" name="submit" id="submit">
            <p>FUNDEP &copy;</p>
        </form>
    </div>
</div>
</div>
<footer id="rodape">
    <p>Nossos meio de contato:</p>
    <p>Gmail</p> 
    <p>Telefone</p> 
    <hr>
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

#cabecalho{
    border-bottom: 1px #606060 solid;
    height: 50px;
}
