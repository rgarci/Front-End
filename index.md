<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <title>Front-End design</title>
</head>
<body>
    <header>
        <nav class="navbar">
            <figure class="logo">
                <a href="index.html">
                <img src="images\logos\cover.png" alt="logo-img">
                </a>
            </figure>
            <ul class="nav-options">
                <li class="nav-option"><a href="index.html">Home</a></li>
                <li class="nav-option"><a href="servicios.html">servicios</a></li>
                <li class="nav-option"><a href="index.html#aboutus">about us</a></li>
                <li class="nav-option"><a href="contacto.html">contacto</a></li>
                <li class="nav-option"><a href="#">subscribe</a></li>
            </ul>
            <figure class="burger">
                <a href=""><img src="images\burger.png" alt="burger-menu"></a>
            </figure>
        </nav>
        <section class="banner">
            <figure class="ban-logo">
                <img  alt="TORCHWOOD">
            </figure>
        </section>
    </header>
    <section class="aboutus" id="aboutus">
        <p class="au-title">about us</p>
        <p class="au-content">Aventuras a través del tiempo y el espacio de la mano del personaje más entrañable de la última media década. Te encuentras en el sitio oficial de fanáticos de Doctor Who. Aquí encontrarás todas las novedades que envuelven el misterioso universo de The Doctor (y los universos paralelos también). Suscríbete para ser parte de la comunidad más grande desde Gallifrey hasta Raxacoricofallapatorius.</p>
        <p class="au-subtitle">the team</p>
        <section class="team">
            <article class="card-member">
                <figure class="cm-image">
                    <img src="images\tony.jpg" alt="Antonio Barrera">
                </figure>
                <p class="cm-name">Antonio Barrera</p>
            </article>
            <article class="card-member">
                <figure class="cm-image">
                    <img src="images\Eli.jpg" alt="Eliezer Couoh">
                </figure>                
                <p class="cm-name">Eliezer Couoh</p>
            </article>
            <article class="card-member">
                <figure class="cm-image">
                    <img src="images\rosi.jpg" alt="Rosaura Garcilazo">
                </figure>
                <p class="cm-name">Rosaura Garcilazo</p>
            </article>
        </section>
    </section>
    <section class="quizz">
        <p class="quizz-title">descubre qué doctor eres con este quizz</p>
        <div class="quizz-opts">
            <a href="" class="gotoservice">contestar quizz</a>
            <a href="servicios.html#quizz" class="gotoservices">ver todos los quizzes</a>
        </div>
        
    </section>
    <br>
    <section class="articles">
        <div class="art-info">
            <p class="art-title">todo acerca de jodie whittaker</p>
            <p class="article-desc">El camino a ser #13 y descubrir su doctor interior</p>
            <a href="" class="gotoservice">leer artículo</a>
            <a href="servicios.html#articles" class="gotoservices">ver todos los artículos</a>
        </div>
    </section>
    <section class="news">
        <article class="new">
            <figure class="new-img">
                <img src="images\teamtardis.jpg" alt="new-img">
            </figure>
            <p class="new-content">TEAM TARDIS. David Tennant en entrevista junto a los personajes más icónicos del doctor no. 10! </p>
        </article>
        <article class="new">
            <figure class="new-img">
                <img src="images\dotd.jpg" alt="new-img">
            </figure>
            <p class="new-content">The day of the doctor es tendencia después de cumplir 7 años este mes. Únete a la celebración con #TDOTD</p>
        </article>
        <article class="new">
            <figure class="new-img">
                <img src="images\river.jpg" alt="new-img">
            </figure>
            <p class="new-content">“In terms of television, I think i’ve only kissed him twice” ¿Alex Kingston nos da a entender que ha besado a Matt Smith fuera de cámara?</p>
        </article>
        <article class="new">
            <figure class="new-img">
                <img src="images\jo.jpg" alt="new-img">
            </figure>
            <p class="new-content">Jo Martin tras balbalinas en el set de Doctor Who, no creerás lo que tiene que contar al respecto...</p>
        </article>
    </section>
    <section class="election">
        <p class="el-title">vota por tu favorito</p>
        <p class="el-desc">Haremos un especial de “Sabías que?” del ganador</p>
        <section class="contestans">
            <div class="contestan">
                <article class="cont-name" title="VOTA AHORA"><a href="">daleks</a></article>
                <div class="percentage">
                    <div class="cont-bar opt1"></div>
                    <p class="cont-percent">64%</p>
                </div>
                
            </div>

            <div class="contestan">
                <article class="cont-name" title="VOTA AHORA"><a href="">cybermen</a></article>
                <div class="percentage">
                    <div class="cont-bar opt2"></div>
                    <p class="cont-percent">36%</p>
                </div>

            </div>
            
        </section>
        <p class="time-left">Quedan 36 hrs 24 min 18 s</p>
    </section>
    <section class="store">
        <p class="store-title">tienda en línea</p>
        <article class="store-content">
            <figure class="store-img">
            <img src="images\toys.jpg" alt="store-img">
            </figure>
            <div class="store-card">
                Miles de artículos temáticos de Doctor Who te esperan en nuestra tienda en línea, entra para ver las promociones
                <a href="servicios.html#shop" class="gotoservices">ver más >></a>
            </div>
        </article>
    </section>
    <br>
    <footer class="footer">
        <p class="footer-desc">© 2020 TORCHWOOD CORP.</p>
    </footer>
</body>
</html>