# Starbucks Landing Page

Este es un proyecto que representa una pagina de inicio ficticia para Starbucks. La pagina esta diseña utilizando HTML, Css y JavaScript.

## Contenido del Proyecto

| Fuente usa : | Se utilizo para importar: "viga"y "Popping" |
| ------------ | ------------------------------------------- |

## Estructura HTML:

### Se uso para todas las paginas HTML la misma estructura.

`

<!DOCTYPE html>
<html lang="es" dir="ltr">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Viga&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap" rel="stylesheet">
    <title>Starbucks Landing Page</title>
    <link rel="stylesheet" href="/css/style.css">
    <link rel="icon" href="/img/logo.png" type="image/x-icon">

</head>

<body>
`
    <header>
        <div class="left-side">
            <a href="index.html"><img src="/img/logo.png" alt=""></a>
        </div>
        <div class="right-side">
            <div class="nav-link-wrapper"> <a href="Index.html">Home</a> </div>
            <div class="nav-link-wrapper"> <a href="https://www.starbucks.com.co/menu">Menu</a> </div>
            <div class="nav-link-wrapper"> <a href="https://www.starbucks.com.co/seccion/novedades">Novedades</a> </div>
            <div class="nav-link-wrapper"> <a href="https://www.starbucks.com.co/stores">Contact</a> </div>
        </div>
    </header>

    <div class="container">
    
        <div class="left-side">
            <h1>It's not just Coffee <br>
                It's <span class="green"> Starbucks </span>
            </h1>
            <p>Starbucks, el acogedor refugio para amantes del café, ofrece una experiencia única en un ambiente
                moderno. Con espressos intensos, frappuccinos creativos y bebidas heladas refrescantes, su diverso menú
                conquista. Más que café excepcional, en Starbucks respaldas la sostenibilidad y la comunidad. Sea para
                trabajar, socializar o relajarse, cada visita es especial. Descubre el placer del café en un lugar
                extraordinario.</p>
            <a href="">Learn More</a>
        </div>
        <div class="right-side">
            <img src="/img/img1.png" alt="" class="starbucks">
            <div class="box">
                <a href="https://www.facebook.com/StarbucksColombia/?locale=es_LA"> <img class="facebook"
                        src="/img/facebook.png" alt=""></a>
                <a href="https://twitter.com/Starbucks"> <img src="/img/instagram.png" alt=""></a>
                <a href="https://www.instagram.com/starbuckscol/?hl=es"> <img src="/img/twitter.png" alt=""></a>
            </div>
        </div>`
​    </div>
​    <div class="thumb">
​        <a href="index.html"><img id="bottom" src="/img/thumb1.png" onclick="imgSlider('/img/img1.png');"> </a>
​        <a href="/pages/pink.html"><img src="/img/thumb2.png" onclick="imgSlider('/img/img2.png');"> </a>
​        <a href="/pages/rosa.html"><img src="/img/thumb3.png" onclick="imgSlider('/img/img3.png');"> </a>
​    </div>

    <script src="js/script.js">
    </script>
</body>

</html>`

#### Objetivo:

El objetivo era  recrear el diseño asignado teniendo en cuenta las herramientas para realizar su desarrollo.
