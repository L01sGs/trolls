<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>::: MEU BLOG DE HOMESTUCK ::: NOVO LAYOUT 2009 !!!1!</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

    <style>
        /* Configurações Globais e Fundo Sólido */
        body {
            margin: 0;
            padding: 0;
            background-color: #0c0c0f; 
            font-family: 'Press Start 2P', cursive;
            color: #ffffff;
            font-size: 11px;
            line-height: 1.8;
        }

        /* --- 1. CABEÇALHO DO BLOG --- */
        .blog-header {
            display: block;
            text-align: center;
            padding: 30px 20px;
            background-color: #000000; 
            border-bottom: 6px double #00ff00;
        }

        .logo-top {
            max-width: 100px;
            height: auto;
            margin: 0 auto 10px auto;
            display: block;
        }

        .blog-title {
            color: #00ff00;
            font-size: 26px;
            margin: 10px 0;
            text-shadow: 4px 4px #000000;
            letter-spacing: -2px;
        }

        .logo-bottom {
            max-width: 350px;
            width: 100%;
            height: auto;
            margin: 10px auto 0 auto;
            display: block;
        }

        /* --- 2. LAYOUT EM DUAS COLUNAS --- */
        .main-layout {
            max-width: 1000px;
            margin: 30px auto;
            display: flex;
            gap: 20px;
            padding: 0 15px;
        }

        .content-area {
            flex: 2;
        }

        .sidebar-area {
            flex: 1;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        /* Caixas de Conteúdo */
        .post-container, .widget-container {
            background-color: rgba(10, 10, 15, 0.95);
            border: 3px solid #00ff00;
            box-shadow: 6px 6px 0px #000000;
            padding: 20px;
            margin-bottom: 25px;
        }

        .post-title, .widget-title {
            background-color: #efefef;
            padding: 8px;
            border: 2px solid #000;
            margin-top: 0;
            margin-bottom: 20px;
            font-size: 11px;
            color: #000;
            text-align: left;
        }

        /* --- 3. ESTILOS DE TEXTO E SEÇÕES --- */
        .post-content p {
            margin-bottom: 15px;
            word-wrap: break-word;
        }

        .char-card {
            background-color: rgba(255, 255, 255, 0.05);
            border: 1px dashed #555;
            padding: 12px;
            margin: 15px 0;
        }

        /* Estilo da nova seção Lado a Lado para os Trolls */
        .trolls-flex-container {
            display: flex;
            gap: 15px;
            align-items: flex-start;
        }

        .trolls-text-column {
            flex: 1.2;
        }

        .trolls-image-column {
            flex: 0.8;
            background-color: #111;
            border: 2px dashed #00ff00;
            padding: 10px;
            text-align: center;
        }

        .trolls-huge-img {
            width: 100%;
            height: auto;
            image-rendering: pixelated;
        }

        /* Cores dos Quirks dos Trolls */
        .tc-karkat { color: #ff0000; }
        .tc-aradia { color: #a10000; }
        .tc-tavros { color: #a15000; }
        .tc-sollux { color: #a1a100; }
        .tc-nepeta { color: #416600; }
        .tc-kanaya { color: #008141; }
        .tc-terezi { color: #008282; }
        .tc-vriska { color: #005682; }
        .tc-equius { color: #000056; }
        .tc-gamzee { color: #2b0057; }
        .tc-eridan { color: #6a0dad; }
        .tc-feferi { color: #ff007f; }

        .highlight-blue { color: #00d2ff; }
        .highlight-pink { color: #ff00ff; }
        .highlight-red { color: #ff0000; }
        .highlight-green { color: #4ac925; }

        /* --- 4. MIDIAS E LINKS --- */
        .image-box {
            background-color: #111;
            border: 2px solid #ff0000;
            padding: 15px;
            margin: 20px auto;
            display: inline-block;
            text-align: center;
        }

        .karkat-img {
            max-width: 180px;
            height: auto;
            image-rendering: pixelated;
        }

        .official-link {
            display: block;
            color: #000000;
            background-color: #ffff00;
            padding: 12px;
            text-decoration: none;
            border: 2px solid #ffffff;
            box-shadow: 4px 4px 0px #000000;
            text-align: center;
            margin: 20px 0;
            font-size: 10px;
        }

        .official-link:hover {
            background-color: #00ff00;
        }

        /* --- 5. INTERAÇÕES --- */
        .btn-interact {
            display: block;
            width: 100%;
            background-color: #222;
            color: #00ff00;
            border: 2px solid #00ff00;
            padding: 10px;
            font-family: 'Press Start 2P', cursive;
            font-size: 9px;
            cursor: pointer;
            margin-bottom: 10px;
            box-shadow: 3px 3px 0px #000;
            text-align: center;
        }

        .btn-interact:hover {
            background-color: #00ff00;
            color: #000;
        }

        .status-gif {
            color: #ff3333;
            font-size: 9px;
            text-align: center;
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <header class="blog-header">
        <img class="logo-top" src="https://static.wikia.nocookie.net/mspaintadventures/images/2/2d/Sburb_Logo.svg" alt="Sburb Logo">
        <h1 class="blog-title">HOMESTUCK BLOG</h1>
        <img class="logo-bottom" src="https://static.wikia.nocookie.net/mspaintadventures/images/a/a7/Homestuck_logo.png" alt="Homestuck Logo">
    </header>

    <div class="main-layout">
       
        <main class="content-area">
           
            <article class="post-container">
                <h2 class="post-title">POSTED: 24/10/2009 ==&gt; INFOS GERAIS!!!</h2>
                <div class="post-content">
                    <p>MEU DEUS DO CEU!!!! vc nao ta entendendo!!!!! 8D 8D</p>
                    <p>tipo... vc PRECISA conhecer essa webcomic q ta todo mundo comentando na internet!!!! o nome eh HOMESTUCK e eh do msm cara q fez Jailbreak e Problem Sleuth (o andrew hussie, vulgo mestre supremo kkkk)!!!!</p>
                    <p>eh basicamente a historia de um mlk de 13 anos chamado <span class="highlight-blue">John Egbert</span> (ele curte uns filmes mt ruins de terror e magica kk bem nerd) q ta trancado no quarto esperando um jogo de computador mt foda e misterioso sair em versao Beta... o nome do jogo eh <strong>Sburb</strong>!!!!</p>
                    <p>so q qnd ele e os amigos dele da internet (a <span class="highlight-pink">Rose</span>, o <span class="highlight-red">Dave</span> e a <span class="highlight-green">Jade</span>) comecam a jogar... o jogo simplesmente INTERAGE COM A REALIDADE!!!! O_O tipo... eles conseguem mover os moveis do quarto uns dos outros usando o mouse do PC!!! mto bizarro dorgas mano kkkkkk</p>
                   
                    <a href="https://www.homestuck.com" target="_blank" class="official-link">
                        ==&gt; CLIQUE AKI PRO SITE OFICIAL DA COMIC !!!!
                    </a>
                </div>
            </article>

            <article class="post-container">
                <h2 class="post-title">POSTED: 28/10/2009 ==&gt; OS TROLLS CHEGARAM!!!!</h2>
                <div class="post-content">
                    <p>NOOOOSSA kra vc nao ta entendendo o nivel da loucura q virou essa parada dps q os TROLLS apareceram!!!! 8D KKKKKKK</p>
                    <p>Eles sao uns alienigenas cinzas de um planeta chamado Alternia, tem chifres de doce, sangue de cores diferentes e ficam trollando os kids pelo Pesterchum!!! Saca so os mais marcantes:</p>
                   
                    <div class="char-card">
                        <span class="highlight-red">KARKAT VANTAS (carcanguejo kk):</span>
                        <p>MEEEU DEUS o bicho eh uma maquina de xingamento!!!! xD ele digita TUDO EM CAPS LOCK E PARECE Q TA SEMPRE GRITANDO COM VOCE!!! ele eh o lider e o sangue dele eh mutante mas ele esconde d todo mundo pra nao morrer... mt tsundere ele!!!! O_O</p>
                       
                        <div class="image-box">
                            <img class="karkat-img" src="https://static.wikia.nocookie.net/mspaintadventures/images/1/17/Karkat_Vantas.png" alt="Karkat">
                        </div>
                    </div>

                    <div class="char-card">
                        <span class="highlight-purple">ERIDAN AMPORA:</span>
                        <p>mano kkkkk o eridan eh mt patetico namoral!!! ele eh da realeza dos trolls (um seadweller) entao ele se acha SUPERIOR A TODO MUNDO. usa uma capa roxa estilosa e usa um quirk onde DUPLICA AS LETRAS "W" E "V" (tipo "wwhat are vyou doing")!!!</p>
                    </div>
                </div>
            </article>

            <article class="post-container">
                <h2 class="post-title">POSTED: 30/10/2009 ==&gt; EXPLICAÇAO DE TODOS OS 12 TROLLS!!!1!</h2>
                <div class="post-content">
                    <p>Mano do ceu, resolvi fazer um guia definitivo d todos os trolls pq eh mt gnt e os cara tem uns "quirks" (tipo mania de digitar esquisito na internet kkk) mt bizarro x_x Fica vendo a listinha q montei pra vcs decorarem!!</p>
                    
                    <div class="trolls-flex-container">
                        
                        <div class="trolls-text-column">
                            <p><span class="tc-aradia">ARADIA:</span> a minina fantasma x_x ela comessa a historia morta dpois vira robo dpois vira fada wtf kkkk ela digita trocando as letra o pelo numero 0 e num tem sentimentos d inicio :/</p>
                            
                            <p><span class="tc-tavros">TAVROS:</span> o garoto dos chifrao de touro q usa cadeira de rodas pq a vriska derrubou ele d um cliff :-( ele eh super timido, ama Pupa Pan e digita INVERTENDO AS MAIUSCULA (tIPO aSSIM mANO,)</p>
                            
                            <p><span class="tc-sollux">SOLLUX:</span> u mestre dus conputador!! eli tem 4 oio (dois azul e dois vermei) e fala cum mo sotaqe de lingua presa kkk digita trocando as letra por "2" e "to" tipo ii2 2o cool B-)</p>
                            
                            <p><span class="tc-karkat">KARKAT:</span> u lider mais nervozo de todos!!!1! ele ODEIA tudo e grita cum tdu mundo nu pesterchum escrevendo TUDO EM CAPS LOCK >:O (sangue vermelho mutante secreto alert!!)</p>
                            
                            <p><span class="tc-nepeta">NEPETA:</span> a otaku dus gatinhu :33 ela mora numa caverna fazendo roleplay na internet e shippando os amigo td!! ela comessa as frase cum :33 e fas trocadilhu de gato purr-feito kkk mt fofa</p>
                            
                            <p><span class="tc-kanaya">KANAYA:</span> a troll mas elegante, ela curte moda, cortar as coisas cum motosserra e eh tipo um vampiro (rainbow drinker o_o) ela DIGITA COMEÇANDO TODA PALAVRA COM MAIUSCULA ASSIM!!</p>
                            
                            <p><span class="tc-terezi">TEREZI:</span> a mina cega q consegue VER AS CORES PELO CHEIRO E GOSTO :P mto dorgas mano!!! ela eh loca por justiça, usa ólinho vermelho e digita cum numeros tipo 43551M (1337 speak total standard) XD</p>
                            
                            <p><span class="tc-vriska">VRISKA:</span> a spider-girl ultra perigosa e crueeel :::;) ela tem mo sorte e usa dados magicos. fodeu a vida de metade dus trolls kkk ela troca o "e" ou "oito" pelo numero 8 e bota 8 óio no emoticon :::;)</p>
                            
                            <p><span class="tc-equius">EQUIUS:</span> u cara fortão esquisito e encanado cum castas de sangue!! ele quebra tudo pq tem força d+ e fica suando mto o_o" eli digita usando D-&gt; pras setas e trocando a palavra "nay" ou "percent" por %</p>
                            
                            <p><span class="tc-gamzee">GAMZEE:</span> u troll palhaço mto chapado de torta de Sopor Slime kkkk :o) ele fala super de boa "miracles bro" e digita AlTeRnAnDo MaIuScUlA e MiNuScUlA mO tRaMpOfO dE lEr kkkkk</p>
                            
                            <p><span class="tc-eridan">ERIDAN:</span> u princepe dos mar patetico d+ q odeia os troll de terra e qer matar todo mundo cum uma arma de laser x_x ele usa cachecol e duplica as letra w e v (wwhat are vyou doing) :/</p>
                            
                            <p><span class="tc-feferi">FEFERI:</span> a princesa peixe ultra empolgada! )( ela eh herdeira do trono de alternia mas eh super de boa e quer cuidar d todo mundo. ela digita usando ) ( pros h maiusculo e -* pros emoticons de coroa</p>
                        </div>
                        
                        <div class="trolls-image-column">
                            <p style="color:#00ff00; font-size:9px; margin-bottom:5px;">[ FOTO DELES SEM CHIFRE NO REDDIT KKK ]</p>
                            <img class="trolls-huge-img" src="https://preview.redd.it/trolls-without-horns-v0-i2gju0kufsj01.png?width=640&crop=smart&auto=webp&s=f72a2e92b3ffaaec10338982c64d8e9cb3b9f7d5" alt="Todos os Trolls de Homestuck">
                            <p style="font-size:8px; color:#888; margin-top:5px;">Olha o naipe dos bixo sem os chifre de doce mto estranho mano kkkkkk mds</p>
                        </div>

                    </div>
                </div>
            </article>

        </main>

        <aside class="sidebar-area">
           
            <div class="widget-container">
                <h3 class="widget-title">INTERAÇÕES DOS FÃS</h3>
                <button class="btn-interact" onclick="alert('Vc curtiu esse post! XD')">[ CURTIR POST ]</button>
                <button class="btn-interact" onclick="alert('Função de comentários abrirá no MSN kkkk brinks')">[ COMENTAR ]</button>
                <button class="btn-interact" onclick="alert('Adicionado aos favoritos do seu Internet Explorer!')">[ FAVORITAR ]</button>
            </div>

            <div class="widget-container">
                <h3 class="widget-title">MY STATUS</h3>
                <p>Ouvindo: Midnight Crew MIDI Track</p>
                <p>Navegador: Firefox 3.5</p>
                <div class="status-gif">
                    [ NET DISCADA: ONLINE ] <br>
                    !!!1!1!!1!!
                </div>
            </div>

        </aside>

    </div>

</body>
</html>
