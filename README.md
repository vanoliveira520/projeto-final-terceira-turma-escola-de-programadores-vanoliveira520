<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">

    <title>Lucio Prado Cimentos</title>
</head>
<body id="body">
    <header> 
            
        
           
    </div>

   
    </div>
    </header>

    <section class="logo">
        <h1 class="nome">Lucio Prado Cimentos</h1>

    </section>

    <section class="menu">
    <nav id="menu">
        <ul>
            <li><a href="#materialDeConstrucao">Materiais de Construção</a></li>
            <li><a href="#terraplanagem">Terraplanagem</a></li>
            <li><a href="#poco">Poço Semi-Artesiano</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

</section>

        <section class="container" id="materialDeConstrucao">
     
                <img class="imagem" src="img/material de construção.jpeg">
                <h2 class="h2"><b>Materiais de Construção Basicos. </b>Reformar ou construir uma casa não é uma tarefa simples, exige tempo, dinheiro e esforço, sem contar da necessidade de um bom planejamento de obras e uma lista completa dos materiais de construção.

                    Aqui você encontra os principais materiais que você vai precisar na sua obra, oferecendo orientações práticas e dicas muito úteis para estar bem preparado para iniciar e concluir o seu projeto de uma construção simples com sucesso. </h2>
              
    </section>
    <section class="container" id="terraplanagem"
    <div>
        <img class="imagem" src="img/tratorTerraplenagem.jpg">

        <h2 class="h2">A terraplanagem, ou terraplenagem, é uma etapa crucial em qualquer projeto de construção. 
            Basicamente, ela é o processo de preparar o terreno para a construção, garantindo que o solo seja nivelado e estável, 
            limitando assim, problemas futuros como erosão e inundações.</h2>
        </div>
</section>
 
<section class="container" id="poco"
<div>
    <img class="imagem" src="img/poço.jpg" alt="Poço semi artesiano já acabado e jorrando água">
    
    <h2 class="h2">O poço semi artesiano é uma opção de captação de água que possui muitas vantagens a serem consideradas.</h2>
</div>
</section>
    <footer> 

        
        <div class="rodape" style="display: flex; flex-direction: column; gap: 20px;" id="contato">
            <img src="img/baixados.png" alt="Logo Lucio Prado Cimentos">
            <div style="display: flex; gap: 15px;">
                <a href="https://www.facebook.com/profile.php?id=100090065694822"><img src="img/facebook.png" alt="Facebook"></a>
                <a href="https://www.instagram.com/luciopradocimentos/?hl=pt-br"><img src="img/instagram.png" alt="Instagram"></a>
                <a href="https://wa.me/5511932095512"><img src="img/whatsapp.png" alt="WhatsApp"></a>
            
            </div>
        </div>
        
     
    </footer>
        
     
                 
  
<body>        
                   
  <script>
        var menu = document.getElementById("opcoesMenu");

        var body = document.getElementById("body");
    
        function chamaMenu(){
            if(menu.style.display == "none"){
                menu.style.display = "block";
            } else {
                menu.style.display = "none";
            }
        }
        
        function trocarTema(){
            if (body.style.backgroundColor == "white"){
                body.style.backgroundColor = "grey";
            } else{
                body.style.backgroundColor = "white";
            }
        }
    </script>
</body>

</html>
