<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
    </body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
    </head>
    <body>
    </body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
    </body>
</html>
:root {
    --cor-de-fundo: #EBECEE;
}

body {
    background-color: var(--cor-de-fundo);
}
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <h1>AluraBooks</h1>
    </body>
</html>
:root {
    --cor-de-fundo: #EBECEE;
}

body {
    background-color: var(--cor-de-fundo);
}

h1 {
    background-color: white;
}
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
            <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header class="cabeçalho">
                <span class="cabeçalho__menu-hamburguer"></span>
                <img src="img/Logo.svg" alt="Logo da AluraBooks">
            </header>
    </body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AluraBooks</title>
            <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header class="cabeçalho">
                <span class="cabeçalho__menu-hamburguer"></span>
                <img src="img/Logo.svg" alt="Logo da AluraBooks">
                <a href="#"><img src="img/Favoritos.svg"></a>
                <a href="#"><img src="img/Compras.svg"></a>
                <a href="#"><img src="img/Usuario.svg"></a>
            </header>
    </body>
</html>
<!-- código omitido -->

</label>
<ul class="lista-menu">
  <li class="lista-menu_titulo">Categorias</li>
  <li class="lista-menu_item">
    <a href="#" class="lista-menu_link">Programação</a>
  </li>
  <li class="lista-menu_item">
    <a href="#" class="lista-menu_link">Front-end</a>
  </li>
  <li class="lista-menu_item">
    <a href="#" class="lista-menu_link">Infraestrutura</a>
  </li>
  <li class="lista-menu_item">
    <a href="#" class="lista-menu_link">Business</a>
  </li>
  <li class="lista-menu_item">
    <a href="#" class="lista-menu_link">Design & UX</a>
  </li>
</ul>

<!-- código omitido -->
/* código omitido */

.lista-menu {
    display: none;
    position: absolute;
    top: 100%;
    width: 60vw;
}

/* código omitido */
//Código omitido

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AluraBooks</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">

</head>

//Código omitido
//Código omitido

:root {
    --cor-de-fundo: #EBECEE;
    --branco: #FFFFFF;
    --laranja: #EB9B00;
    --azul-degrade: linear-gradient(97.54deg, #002F52 35.49%, #326589 165.37%);
    --fonte-principal: "Poppins";|
}

//Código omitido
//Código omitido

body {
    background-color: var(--cor-de-fundo);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}
<!-- código omitido -->

<section class="banner">
    <h2 class="banner__titulo">Já sabe por onde começar?</h2>
    <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!<p>
</section>
<!-- código omitido -->

<section class="banner">
    <h2 class="banner__titulo">Já sabe por onde começar?</h2>
    <p class="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!<p>
    <input type="search" class="banner_pesquisa" placeholder="Qual será sua próxima leitura?">
</section>

<!-- código omitido -->
/* código omitido */

.banner__pesquisa {
    background-color: transparent;
    border: 1px solid var(--branco);
    color: var(--branco);
    border-radius: 24px;
}
/* código omitido */

.banner__pesquisa {
    background-color: transparent;
    border: 1px solid var(--branco);
    color: var(--branco);
    border-radius: 24px;
    padding: 1em;
    width: 100%;
}
/* código omitido */

.banner__pesquisa::placeholder {
    font-family: var(--fonte-principal);
    font-size: 14px;
    font-weight: 400;
}
/* código omitido */

.banner__pesquisa::placeholder {
    font-family: var(--fonte-principal);
    font-size: 14px;
    font-weight: 400;
    text-align: center;
    color: var(--branco);
}
/* código omitido */

.banner__pesquisa::placeholder {
    font-family: var(--fonte-principal);
    font-size: 14px;
    font-weight: 400;
    text-align: center;
    color: var(--branco);
    background: url("../img/Lupa.svg");
}
/* código omitido */

.banner__pesquisa::placeholder {
    font-family: var(--fonte-principal);
    font-size: 14px;
    font-weight: 400;
    text-align: center;
    color: var(--branco);
    background: url("../img/Lupa.svg") no-repeat;
}
/* código omitido */

.banner__pesquisa::placeholder {
    font-family: var(--fonte-principal);
    font-size: 14px;
    font-weight: 400;
    text-align: center;
    color: var(--branco);
    background: url("../img/Lupa.svg") no-repeat;
    background-position: 1em;
}
//Código omitido

<section class="carrossel"> I
    <h2 class="carrossel titulo">Novos lançamentos</h2>
/section>
//Código omitido

@import url("styles/carrossel.css")

//Código omitido
.carrossel_titulo {
color: var(--laranja);
background-color: var(--branco);
text-align: center;
text-transform: uppercase;
//Código omitido

font-size: 18px;
font-weight: 700;
padding: 1em 0 0.5em 0
//Código omitido

<linf rel="stylesheet" href="https://unpk.com/swiper@8/swiper-bundle.min.css">

//Código omitido
//Código omitido

<script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script>

//Código omitido
<!-- Slider main container -->
<div class="swiper">
  <!-- Additional required wrapper -->
  <div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide">Slide 1</div>
    <div class="swiper-slide">Slide 2</div>
    <div class="swiper-slide">Slide 3</div>
    ...
  </div>
  <!-- If we need pagination -->
  <div class="swiper-pagination"></div>

  <!-- If we need navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>

  <!-- If we need scrollbar -->
  <div class="swiper-scrollbar"></div>
</div>
//Código omitido

<div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide"><img src="img/Apachekafka.svg" alt="Livro sobre apache kafka e spring boot da alura books"></div>
    <div class="swiper-slide"><img src="img/Liderança.svg" alt="Livro sobre liderança em design design da alura books"></div>
    <div class="swiper-slide"><img src="img/Javascript.svg" alt="Livro sobre javascript assertivo da alura books"></div>
    <div class="swiper-slide"><img src="Guia Front-end.svg" alt="Livro Guia front end"></div>
    <div class="swiper-slide"><img src="Portugol.svg" alt="Livro sobre portugol"></div>
    <div class="swiper-slide"><img src="Acessibilidade.svg" alt="livro sobre acessibilidade"></di>
</div>
const swiper = new Swiper('.swiper', {
  speed: 400,
  spaceBetween: 100,
});
<script>
    const swiper = new Swiper('.swiper', {
        spaceBetween: 10,
    });
</script>
const swiper = new Swiper('.swiper', {
  // Default parameters
  slidesPerView: 1,
  spaceBetween: 10,

  // código omitido

})
<script>
    const swiper = new Swiper('.swiper', {
        spaceBetween: 10,
        slidesPerView: 3,
    });
</script>
.swiper-slide img {
    width: 100%;
}<div class="swiper-slide"><img src="img/Guia Front-end.svg" alt="Livro Guia front end"></div>
<div class="swiper-slide"><img src="img/Portugol.svg" alt="Livro sobre portugol"></div>
<div class="swiper-slide"><img src="img/Acessibilidade.svg" alt="livro sobre acessibilidade"></div>.swiper-button-prev,
.swiper-button-next {
    display: none;
}
<!-- If we need pagination -->
<div class="swiper-pagination"></div>const swiper = new Swiper('.swiper', {
  pagination: {
    el: '.swiper-pagination',
    type: 'bullets',
  },
});<script>
    const swiper = new Swiper('.swiper', {
        spaceBetween: 10,
        slidesPerView: 3,
        pagination: {
            el: '.swiper-pagination',
            type: 'bullets',
        },
    });
</script>
.swiper-pagination {
    position: initial;
}.swiper-pagination {
    position: initial;
    margin: .5em 0;
}<!-- If we need scrollbar -->
<div class="swiper-scrollbar"></div>
<section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
     <section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
     <section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
        <li class="tópicos__item">
              <a href="#" class="tópicos__link"></a>
        </li>
    </ul>
 </section>
 <section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Android</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Marketing Digital</a>
        </li>
    </ul>
 </section><section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Android</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Marketing Digital</a>
        </li>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Agile</a>
        </li>
    </ul>
 </section><section class="tópicos">
   <h2> class="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <ul class="tópicos__lista">
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Android</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Marketing Digital</a>
        </li>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Agile</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Startups</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">HTML e CSS</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">OO</a>
        </li>
        <li class="tópicos__item">
              <a href="#" class="tópicos__link">Java</a>
        </li>
    </ul>
 </section>
 .tópicos {
    background: var(--azul-degrade);
}.tópicos {
    background: var(--azul-degrade);
     text-align: center;
}.tópicos {
    background: var(--azul-degrade);
     text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}
.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
}.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
}
.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.tópicos__link {
   color: var(--branco);
    padding: 1em;
    background-color: var(--laranja);

}.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

.tópicos__link {
   color: var(--branco);
    padding: 1em;
    background-color: var(--laranja);

}
.tópicos {
    background: var(--azul-degrade);
    text-align: center;
     padding: 1em 0;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

.tópicos__link {
   color: var(--branco);
    padding: 1em;
    background-color: var(--laranja);
    text-decoration: none;

}.tópicos {
    background: var(--azul-degrade);
   text-align: center;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

.tópicos__link {
   color: var(--branco);
    padding: 1em;
    background-color: var(--laranja);
    text-decoration: none;
    font-size: 14px;
    font-weight: 700;

}.tópicos {
    background: var(--azul-degrade);
    text-align: center;
     padding: 1em 0;
}

.tópicos__titulo {
   color: var(--branco);
}

.tópicos__lista {
   display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

.tópicos__link {
   color: var(--branco);
    padding: 1em;
    background-color: var(--laranja);
    text-decoration: none;
    font-size: 14px;
    font-weight: 700;

}
.tópicos {
    background: var(--azul-degrade);
    text-align: center;
   padding: 1em 0;
}

.tópicos__titulo {
   color: var(--branco);
    font-weight: 300;
    margin-bottom: 1em;
}

.tópicos__lista {
   display: flex;
   flex-wrap: wrap;
   justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

.tópicos__link {
   color: var(--branco);
  padding: 1em;
  background-color: var(--laranja);
  text-decoration: none;
  font-size: 14px;
  font-weight: 700;

}
.tópicos {
    background: var(--azul-degrade);
    text-align: center;
   padding: 1em 0;
}

.tópicos__titulo {
   color: var(--branco);
    font-weight: 300;
    margin-bottom: 1em;
}

.tópicos__lista {
   display: flex;
   flex-wrap: wrap;
   justify-content: center;
}

.tópicos__item {
   margin: 2em 0.5em;
}

<section class="contato">
    <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
    <p class="contato__texto">Atualizações de e-books, novos livros, promoções e outros.</p>
    <input type="email" placeholder="Cadastre seu e-mail" class="contato__email">
</section>

}@import url("styles/contato.css");.contato {
    background-color: var(--branco);
    padding: 1em;
}
}.contato__titulo {
    background: var(--azul-degrade);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}
.contato__titulo,
.contato__texto {
    background: var(--azul-degrade);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}.contato__titulo {
    font-size: 18px;
    font-weight: 500;
}

.contato__texto {
    font-weight: 300;
    margin: 1em 0;
}.contato__email {
    padding: 1em;
    border: 1px solid var(--azul);
    border-radius: 24px;
    width: 90%;
}
