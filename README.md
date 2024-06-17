my-website/
├── index.html
├── styles.css
└── scripts.js
<!DOCTYPE html>
<html lang="N.S.D.A.P">
<head>
    <meta charset="UTF-8">
    <meta name="nacional socialista" content="width=device-width, initial-scale=1.0">
    <title>bienvenido compatriota</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">Sobre Nosotros</a>nosotros somos una comunidad que sigue fiel mente las ideales de adolf Hitler</li>
                <li><a href="#gallery">Galería</a>por ahora no tenemos información aqui</li>
                <li><a href="#contact">Contacto</a>te puedes comunicar con nosotros con este correo hghcjgdfhhfdhf@gmail.com</li>
            </ul>
        </nav>
    </header>
    <section id="hogar" class="section">
        <h1>compatriota bienvenido disfrutá la información real que te ofrecemos</h1>
        <p>Esta es una página web desarrollada con HTML, CSS y JavaScript.</p>
    </section>
    <section id="about" class="section">
        <h2>Sobre Nosotros</h2>nosotros somos una comunidad fielmente a adolf Hitler, queremos liberar el mundo de las mentiras que los judíos han inventado 
        <p>Somos un partido que revive el partido de Adolf Hitler fielmente.</p>
    </section>
    <section id="gallery" class="section">
        <h2>Galería</h2>
        <div class="gallery">
            <img src="https://nacional socialismo .com/150" alt="Imagen 1">
            body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.section {
    padding: 20px;
    text-align: center;
}

.section:nth-child(even) {
    background-color: #ddd;
}

.gallery {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.gallery img {
    margin: 10px;
    width: 150px;
    height: 150px;
    object-fit: cover;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin: 5px 0;
}

form input, form textarea {
    margin: 5px 0;
    padding: 10px;
    width: 80%;
    max-width: 500px;
}

form button {
    padding: 10px 20px;
    background-color: #007BFF;
    color: white;
    border: none;
    cursor: pointer;
    margin-top: 10px;
}

form button:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
document.addEventListener('DOMContentLoaded', () => {
    const form = document.getElementById('contactForm');
    
    form.addEventListener('submit', (e) => {
        e.preventDefault();
        
        const name = document.getElementById('name').value;
        const email = document.getElementById('email').value;
        const message = document.getElementById('message').value;
        
        console.log('Nombre:', name);
        console.log('Email:', email);
        console.log('Mensaje:', message);
        
        alert('Formulario enviado. ¡Gracias por contactarnos!');
        
        form.reset();
    });
});
