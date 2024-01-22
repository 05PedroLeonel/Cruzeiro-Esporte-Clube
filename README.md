<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Cruzeiro Esporte Clube</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Oxygen:wght@300;400&display=swap" rel="stylesheet" />
    <link rel="stylesheet" href="index.css">
</head>

<body>
    <main>
        <section class="hero">
            <video class="hero__background" autoplay muted loop>
                <source src="/Meu projeto/video/2024-01-21 17-34-36 (video-converter.com).mp4" type="video/mp4" />
            </video>
            <div class="hero__foreground">
                <h1 class="hero__title">Cruzeiro Esporte Clube.</h1>
                <p class="hero__text">
                    Discover more about the biggest in Minas Gerais
                </p>
            </div>
        </section>
        <section class="section">
            <h2 class="section__title">Brazilian Cups</h2>
            <img class="section__img" src="/Meu projeto/img/Dpyd5rsW0AI5zb9.jpg" alt="" width="500" height="5000"/>
            <p class="section__text">
                Cruzeiro is the biggest champion of the tournament, with 6 titles and had its last title in 2017, and Grêmio is in second place, with 5 cups.
            </p>
        </section>
        <section class="section">
            <h2 class="section__title">Brazilian championship</h2>
            <img class="section__img-inline" src="/Meu projeto/img/cruzeiro_campeao_brasileiro_gustavoandrade-1-.jpg" alt="" />
            <div class="section__text-inline">
                <p>
                    At national level, Cruzeiro won the Brazilian Football Championship four times (1966 / 2003 / 2013 and 2014) Turning four-time champions.
                </p>
                <p>
                    Champions of running points in the history of the Brasileirão
The team that scored the most in the history of running points was Cruzeiro, which scored 100 points in 2003, but with 46 games played (2.17 points per game), as there were 24 clubs in the first division.
                </p>
            </div>
        </section>
        <section class="section">
            <h2 class="section__title">Libertadores</h2>
            <img class="section__img" src="/Meu projeto/img/Libertadores-jpeg.avif" alt=""  />
            <p class="section__text">
                At international level, Cruzeiro won the Copa Libertadores da América twice (1976 / 1997) becoming two-time champions, they won the Supercopa American Libertadores twice (1991 / 1992) becoming two-time champions
            </p>
        </section>
        <section class="section">
            <h2 class="section__title">Cruzeiro Esporte Club titles</h2>
            <div class="gallery">
                <span class="gallery__img-wrapper">
                    <img class="gallery__img" src="/Meu projeto/img/cruzeiro-levantou-trofeu-do-campeonato-mineiro-sub-20-nesta-quinta-feira_1_57151.webp" alt="" />
                </span>
                <span class="gallery__img-wrapper">
                    <img class="gallery__img" src="/Meu projeto/img/cruzeiro_campeao_brasileiro_gustavoandrade-1-.jpg" alt="" />
                </span>
                <span class="gallery__img-wrapper">
                    <img class="gallery__img" src="/Meu projeto/img/Dpyd5rsW0AI5zb9.jpg" alt="" />
                </span>
                <span class="gallery__img-wrapper">
                    <img class="gallery__img" src="/Meu projeto/img/Libertadores-jpeg.avif" alt="" />
                </span>
            </div>
            <p class="section__text">
                This is a list of titles won by Cruzeiro Esporte Clube in different sports. In Football, Cruzeiro has 20 official titles at international, national and regional levels.
            </p>
        </section>
        <section class="section">
            <h2 class="section__title">Curiosities about Cruzeiro Esporte club</h2>
            <img class="section__img-inline" src="/Meu projeto/img/temp_xpZF23H.png" alt="" />
            <div class="section__text-inline">
                <p>
                    It was an Italian colony in Belo Horizonte (MG) that founded the association. The time was born with the support of the Italian consul Lorenzo Nicolai, who visited the capital of Minas Gerais. Until 1925, only players with Italian ancestry were accepted into the team.
                </p>
                <p>
                    The club was founded on January 2, 1921 from the Italian community in Belo Horizonte, Minas Gerais, as Società Sportiva Palestra Italia. His shield was green and red with gold details, paying homage to Italy.
                </p>
            </div>
        </section>
    </main>
    <footer class="footer">
        Made with
        <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="#f64348" stroke="#f64348" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path>
        </svg>
        <a href="https://www.linkedin.com/in/pedro-leonel-7a9a90291/">@PedroLeonel</a>
    </footer>
</body>

</html>



* {
    box-sizing: border-box;
    font-family: "Oxygen", system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    margin: 0;
    padding: 0;
}

:root {
    --color-background: #030207;
    --color-white: #fff;
    --color-blue: #1474b4;
}

body {
    background-color: var(--color-background);
    color: var(--color-white);
}

a {
    color: var(--color-blue);
}

.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.1), var(--color-background));
    position: relative;
    min-height: 100vh;
}

.hero__background {
    object-fit: cover;
    position: absolute;
    top: 0;
    height: 100vh;
    width: 100%;
    z-index: -10;
}

.hero__foreground {
    color: var(--color-white);
    padding-top: 40vh;
    text-align: center;
}

.hero__title {
    font-size: 5rem;
    font-weight: 300;
}

.hero__text {
    margin-top: 2rem;
    letter-spacing: 0.5rem;
    text-transform: uppercase;
}




.section {
    overflow: hidden;
    padding: 0 8rem;
    text-align: center;
}

.section__title {
    font-size: 3rem;
    font-weight: 300;
    margin: 4rem auto;
}

.section__img,
.section__img-inline {
    border-radius: .75rem;
    /* eixo x, eixo y, blur, expansão/recuo, cor */
    box-shadow: 0 1rem 2rem -0.5rem rgba(20, 116, 180, 0.25);
    object-fit: cover;
    object-position: top;
    position: relative;
    max-height: 75rem;
    width: 80%;
}

.section__text,
.section__text-inline {
    font-size: 1.25rem;
    line-height: 1.75;
    margin: 4rem auto;
}

.section__img-inline {
    border-top-left-radius: 4rem;
    border-bottom-right-radius: 4rem;
    float: left;
    margin-right: 4rem;
    margin-bottom: 2rem;
    height: 30rem;
    width: 30rem;
}

.section__text-inline {
    margin-top: 6rem;
    text-align: left;
}

.section__text-inline > p {
    margin-top: 1.5rem;
}

#hangouts img {
    object-position: center;
}

.gallery__img {
    border-radius: .75rem;
    height: 16rem;
    width: 16rem;
    object-fit: cover;
    transform: rotate(-2deg); /* deg = degrees */
}

.gallery__img-wrapper {
    display: inline-block;
    position: relative;
}

.gallery__img-wrapper + .gallery__img-wrapper {
    margin-left: 3rem;
    margin-top: 3rem;
}

.gallery__img-wrapper:nth-child(even) > .gallery__img {
    top: 1rem;
    transform: rotate(2deg);
}

.gallery__img-wrapper::after {
    content: "";
    background-color: rgb(228, 26, 26);
    border-radius: 999px;
    display: block;
    height: 1.25rem;
    width: 1.25rem;
    position: absolute;
    top: 0.25rem;
    right: 1rem;
}

.gallery__img-wrapper:nth-child(even)::after {
    left: 1rem;
}

footer {
    margin-top: 4rem;
    padding: 2rem;
    text-align: center;
}
