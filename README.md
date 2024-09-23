<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siri Cascudo</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <nav>
            <img src="img/bobSereia.jpg" alt="">
            <ul>
                <li> <a href="cardapio.html">Cardapío</a></li>
                <li> <a href="#">Lançamento</a></li>
                <li> <a href="#">Quem Somos</a></li>
                <li> <a href="#">Família</a></li>
                <li> <a href="#">Promoções</a></li>
            </ul>   
        </nav>
    </header>
    <main>
        <div >
            <img class="imgSiriCascudo " src="img/foto de capa siricascudo.png" alt="">
        </div>
        <div>
            <ul class="containerCard">
                <li class="card">
                    <img src="img/bobOferecendoHamburger.jpg" alt="">
                    <p>O melhor Hambúrguer de Siri</p>
                </li>
                <li class="card">
                    <img src="img/comendoSorvete.jfif" alt="">
                    <p>Agora com sorvete do amendobobo</p>
                </li>
                <li class="card">
                    <img src="img/bobcozinhando.jfif" alt="">
                    <p>Temos o melhor cozinheiro da fenda do biquini</p>
                </li>
            </ul>
        </div>
    </main>
    <footer>
        <div class="container-footer">
            <h3>Visite a fenda do biquini</h3>
            <p><a href="">Conheça o Balde de Lixo</a></p>
        </div>
    </footer>

    
</body>
</html>

*{
    margin: 0 auto;
    border: 0;
}

header{
    text-align: center;
    font-size: 32px;
    color: rgb(47, 47, 252);
}

header img{
    width: 100%;
    height: 500px;
}

form{
    margin-top: 100px;
    width: 500px;
    background-color:rgba(253, 236, 3, 0.926);
    border-radius: 40px; 
    padding-top: 40px;
    font-size: 20px;
}

.container{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
}

.container img{
    width: 400px;
    height: 400px;
    padding: 20px 0 0 10px;
}

.formularios{
    display: block;
    width: 400px;
    height: 30px;
}

.container-informaçoes input{
    margin-bottom: 20px;
}

.container-radio{
    display: block;
    align-items: center;
    padding: 20px 0 ;
}

select .formularios{
    margin-bottom: 20px;
}

.input-submit{
   width: 200px;
   height: 50px;
   margin: 40px 0 20px 0;
   background-color: rgb(255, 149, 223);
   border-radius: 40px;
   color: white;
   font-size: 20px;
   font-weight: bold;
   transition: 1s background;
}

.input-submit:hover{
    background-color: rgb(255, 84, 221);
}

footer{
    height: 600px;
    background-color: black;
}
