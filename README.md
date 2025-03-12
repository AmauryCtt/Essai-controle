# Essai-controle


1. Structure HTML (index.html)
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hôtel</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous">
</head>
<body>

    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#about">About</a>
        <a href="#amenities">Amenities</a>
        <a href="#rooms">Rooms</a>
        <a href="#restaurant">Restaurant</a>
        <a href="#gallery">Gallery</a>
    </nav>

    <section id="accueil">
        <h1>Accueil</h1>
        <p>Bienvenue sur notre site...</p>
    </section>

    <section id="about">
        <h1>About</h1>
        <p>Présentation de l'hôtel...</p>
    </section>

    <section id="amenities">
        <h1>Amenities</h1>
        <p>Les services disponibles...</p>
    </section>

    <section id="rooms">
        <h1>Rooms</h1>
        <p>Nos chambres...</p>
    </section>

    <section id="restaurant">
        <h1>Restaurant</h1>
        <p>Découvrez notre restaurant...</p>
    </section>

    <section id="gallery">
        <h1>Gallery</h1>
        <p>Nos photos...</p>
    </section>

</body>
</html>


2. Style CSS (style.css)
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@200;300;400;500;600;700;800;900&display=swap');

body {
    font-family: 'Roboto Slab', serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth; /* Smooth scrolling */
    background-color: #c1b086;
}

nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: #3f9cc1;
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    margin: 0 15px;
    padding: 10px;
}

nav a:hover {
    background: rgba(255, 255, 255, 0.3);
    border-radius: 5px;
}

section {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
}

#accueil { background: rgba(102, 79, 20, 0.8); }
#about { background: rgba(193, 176, 134, 0.8); }
#amenities { background: rgba(63, 156, 193, 0.8); }
#rooms { background: rgba(173, 217, 129, 0.8); }
#restaurant { background: rgba(255, 99, 71, 0.8); }
#gallery { background: rgba(75, 0, 130, 0.8); }

