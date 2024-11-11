# aluraflix
<html lang="pt-BR">

<head>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>Aluraflix</title>
</head>

<body>
    <header>ALURAFLIX</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/watch?v=k_F-b8tLvng"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

    <section class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <a href="https://https://www.youtube.com/watch?v=k_F-b8tLvng">
                <img src="https://https://www.youtube.com/watch?v=k_F-b8tLvng" />
            </a>
            <a href="https://https://www.youtube.com/watch?v=k_F-b8tLvng">
                <img src="https://https://www.youtube.com/watch?v=k_F-b8tLvng" />
            </a>
            <a href="https://https://www.youtube.com/watch?v=k_F-b8tLvng">
                <img src="https://https://www.youtube.com/watch?v=k_F-b8tLvng" />
            </a>
            <a href="https:/https://www.youtube.com/watch?v=k_F-b8tLvng">
                <img src="https://https://www.youtube.com/watch?v=k_F-b8tLvng" />
            </a>
            <a href="https://https://www.youtube.com/watch?v=k_F-b8tLvng">
                <img src="https://https://www.youtube.com/watch?v=k_F-b8tLvng" />
            </a>
        </div>
    </section>

</body>

</html>
body {
    color: white;
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
    border-bottom: solid 2px rgb(42, 122, 228);
    padding: 20px;
    font-size: 32px;
    color: rgb(42, 122, 228);
}

.chamada {
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}

h1 {
    font-size: 40px;
}

p {
    font-size: 20px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}

.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}

.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}

.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}

.categoria h2 {
    color: rgb(42, 122, 228);
}
