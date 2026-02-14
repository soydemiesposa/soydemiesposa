!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Para Arely 💕</title>

<style>
body {
    margin: 0;
    font-family: 'Courier New', cursive;
    background: linear-gradient(180deg, #ff9ecf, #ffe6f2);
    text-align: center;
    color: #fff;
    overflow-x: hidden;
}

h1 {
    font-size: 40px;
    margin-top: 30px;
    text-shadow: 2px 2px 5px #ff4da6;
}

.carta {
    background: rgba(255,255,255,0.9);
    color: #ff4d88;
    padding: 25px;
    margin: 20px auto;
    border-radius: 20px;
    max-width: 750px;
    box-shadow: 0 0 20px rgba(0,0,0,0.2);
}

h2 {
    color: #ff1a75;
}

img {
    width: 220px;
    border-radius: 20px;
    margin: 10px;
    box-shadow: 0 0 15px rgba(0,0,0,0.3);
}

ul {
    text-align: left;
    max-width: 600px;
    margin: auto;
}

li {
    margin: 8px 0;
}

/* Corazones flotando */
.corazon {
    position: fixed;
    top: -10px;
    font-size: 20px;
    animation: caer 6s linear infinite;
}

@keyframes caer {
    0% {transform: translateY(-10px);}
    100% {transform: translateY(100vh);}
}
</style>
</head>

<body>

<h1>Para Arely 💗</h1>

<!-- Música -->
<audio autoplay loop>
    <source src="musica.mp3" type="audio/mpeg">
</audio>

<div class="carta">
    <h2>Feliz primer mes y San Valentin 💕</h2>
    <p>
    Mi niña hermosa Arely 💗

Hoy es 14 de febrero, el día del amor, y aunque estemos lejos, quiero que sientas mi cariño como si te estuviera abrazando fuerte. Tal vez estamos pequeños y solo tenemos 14 años bueno yo 14 y tu 13, pero lo que siento por ti es algo tan bonito y sincero que no lo puedo esconder.

Desde que llegaste a mi vida, todo se volvió más lindo. Antes mis días eran normales, pero ahora tienen color, tienen emoción, tienen esa sensación bonita de saber que en algún momento del día voy a hablar contigo. Me gusta despertar y pensar en ti, me gusta revisar el celular esperando un mensaje tuyo, y me gusta dormir sabiendo que existes y que estás en mi vida.

Tú eres como ese rayito de sol que aparece cuando todo está gris. Con solo un “hola” tuyo, mi corazón se pone feliz. Con solo saber que estás ahí, siento que todo vale la pena. A veces sonrío sin razón, y es porque me acuerdo de ti. A veces me quedo viendo tu nombre en la pantalla, y siento algo tan bonito que no sé cómo explicarlo.

Aunque la distancia nos separe, siento que mi corazón siempre está contigo. Me gusta imaginar el día en que pueda verte, hablar contigo cara a cara, reírnos juntos y tal vez darte un abrazo largo, de esos que no se quieren soltar. Pero mientras ese día llega, cada mensaje tuyo es como un pequeño abrazo que me llega directo al corazón.

Eres esa persona especial que me hace sentir cosas nuevas, que me hace querer ser mejor, que me hace ilusionarme con cosas simples, como hablar contigo, escucharte o hacerte sonreír. Me gustas por todo lo que eres, por tu forma de ser, por tu dulzura, por tu manera de hablar y por todo lo bonito que transmites.

Tal vez somos jóvenes, pero lo que siento por ti es puro y real. No es un juego, no es algo sin importancia. Es ese sentimiento dulce que me hace latir el corazón más rápido cuando veo tu nombre, ese que me hace pensar en ti a cada rato, ese que me hace decir con toda sinceridad que te amo a mi manera, con un corazón joven pero lleno de cariño para ti.

Este 14 de febrero quiero recordarte lo especial que eres para mí. Quiero que sepas que te amo muchísimo, que eres una parte muy importante de mis días y que cada momento contigo, aunque sea a distancia, significa mucho para mí.

Feliz 14 de febrero, mi niña preciosa.
Te amo con todo mi corazoncito de 14 años 💖
    </p>
</div>

<h2>Nuestras fotos 📸</h2>
<img src="foto1.jpg">
<img src="foto2.jpg">
<img src="foto3.jpg">
<!-- Corazones flotando -->
<script>
function crearCorazon() {
    const corazon = document.createElement("div");
    corazon.classList.add("corazon");
    corazon.innerHTML = "💖";
    corazon.style.left = Math.random() * 100 + "vw";
    corazon.style.animationDuration = (Math.random() * 3 + 3) + "s";
    document.body.appendChild(corazon);

    setTimeout(() => {
        corazon.remove();
    }, 6000);
}

setInterval(crearCorazon, 500);
</script>

</body>
</html>
