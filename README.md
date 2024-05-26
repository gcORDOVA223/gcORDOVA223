- 👋 Hi, I’m @gcORDOVA223
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="cabeçalho">

    <img class= "LogoDoSite" src="hollow-knight-logo.png" alt="Hollow knight">

    <img class="cabeçaDoBixo" src="KnightHead.png" alt="Knight head" >

        
</header>
    <section class="Hollow">
        <div class="hollow_div">
            <h2 class="hollow texto">      O que é Hollow Knight?</h2>
            <p>Hollow Knight é um game de ação e aventura inspirado em clássicos como Metroid e Castlevania, mas principalmente na popular série Dark Souls. O título traz um pequeno cavaleiro em uma jornada para selar uma infecção maléfica capaz de destruir todo o seu mundo. O gameplay é profundo e garante horas de exploração e muitas mortes até conseguir vencer seus oponentes. Nas linhas a seguir, conheça mais sobre a história do jogo independente, seu gameplay, os mapas, dicas para enfrentar chefes (bosses) e o futuro da franquia.</p>
        </div>   
   <img class="hollow-knight-logo"  src="hollow_parece_logo.png" alt="hollow_knight_logo">
   
</section>
<section class="criadores">
    <h2>criadores</h2>
    <img class="Cherry_logo"src="Team_cherry_Logo_Red.png" alt="Team_cherry">

    <div>
    <img src="William Pellen.png" alt="Wiliian pellen">
    <h3 class="seila">William tem projetado e construído jogos por anos, e é cofundador da Team Cherry. Ele adora criar mundos para que as pessoas explorem e descubram seus segredos, tentando recriar uma experiência de aventura e entusiasmo que teve quando jogou Zelda 2.</h3>
    <img src="Ari Gibson.png" alt="Ari Gibson">
    <h3 class="seila">Ari é responsável pelo design do jogo ao lado de William. Ele cria a arte, os ambientes do jogo e anima centenas de bugs.</h3>
    <img src="Jack vine.png" alt="Jack vine">
    <h3 class="seila">Ele era o programador do grupo, mesmo tendo grande habilidade em programação, ele não ajudou a ter a ideia do jogo</h3>
    </div>
</section>
</body>
</html>





css


*{
margin: 0;
padding: 0%;
}

.cabeçalho{
    
    background-color: rgb(14, 14, 14);
    display: flex;
   
}

.LogoDoSite{
    width: 50%;
    
}

.KnightHead{
    width: 5%;    
}

.Hollow{
    color: white;
    font-size: xx-large;
    font-style:initial;
    background-image: linear-gradient(rgb(14, 14, 14) ,rgb(13, 7, 70));
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 70px 0;
}

.hollow_div{
 width: 60%;
     }
.hollow-knight-logo{
    width: 25%;
}


.criadores{
    color: rgb(238, 41, 41);
    font-size: xx-large;
    font-style:initial;
    background-image: linear-gradient(rgb(13, 7, 70) ,rgb(255, 255, 255));
    text-align: center;
    
}

.Cherry_logo{
    width: 25%;
   
}

.seila{
    
    color: rgb(202, 37, 37);
    font-style: unset;

}

.cabeçaDoBixo{
    height: 8%;
    width: 8%;
    align-items: center;
    
}
