<!DOCTYPE html>
<html>
<head>
    <style>
        h1 {
            margin-top: 200px; /* puedes ajustar el número */
        }
        body {
            background-color: #000;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
        }

        .espacial {
            font-size: 18px;
            font-weight: bold;
            color: #fff;
            text-shadow: 0 0 10px #00f, 0 0 20px #0ff, 0 0 30px #0ff, 0 0 40px #0ff, 0 0 70px #0ff, 0 0 80px #0ff;
            animation: brillar 3s infinite alternate ease-in-out;
        }

        @keyframes brillar {
            from {
                text-shadow: 0 0 10px #00f, 0 0 20px #0ff, 0 0 30px #0ff, 0 0 40px #0ff, 0 0 70px #0ff, 0 0 80px #0ff;
                color: #fff;
            }

            to {
                text-shadow: 0 0 20px #0ff, 0 0 40px #0ff, 0 0 60px #0ff, 0 0 80px #0ff, 0 0 100px #0ff;
                color: #aaf;
            }
        }

        .arcoiris {
            font-size: 18px;
            font-weight: bold;
            background: linear-gradient(90deg, red, orange, yellow, green, blue, indigo, violet);
            background-size: 400%;
            -webkit-background-clip: text;
            color: transparent;
            animation: mover 5s linear infinite;
        }

        @keyframes mover {
            0% {
                background-position: 0%;
            }

            100% {
                background-position: 100%;
            }
        }

        h1 {
            color: #ff66ff;
            font-size: 45px;
            font-family: cursive;
            text-shadow: 2px 2px 4px gray;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-align: center;
        }

        h2 {
            color: #ccffe6;
            font-size: 25px;
            font-family: cursive;
            text-shadow: 2px 2px 4px gray;
            text-align: center;
        }

        p {
            color: #ffffcc;
            font-size: 18px;
            font-family: cursive;
            line-height: 1.6;
            text-align: justify;
            margin: 10px 40px;
        }

        .firma {
            color: #ff99ff;
            font-style: italic;
            text-align: right;
            margin-right: 60px;
        }
    </style>
</head>
<body>


    <h1>Para la mujer más hermosa del fokin mundo</h1>

    <p style="text-align: center;">
        Perdón, amor... llegué una semana tarde bueno, seis días.
        Solo quería hacerte una cartita a mi manera, y la verdad no sabía cómo.
        Si la escribía a mano, dudo que pudieras entenderla.
    </p>

    <h2>Espero que te guste 💖</h2>
    <audio id="musica" loop>
        <source src="audio/Cometas.mp3" type="audio/mpeg">
        Tu navegador no soporta audio HTML5.
    </audio>
    <button onclick="document.getElementById('musica').play()">🎵 Reproducir música</button>
    <p>
        Hola, mi amor.
        Ayer cumplimos un mes de novios un mes precioso, lleno de baches que supimos superar juntos.
        Quiero darte las gracias por todo, porque aunque digas que no me das nada “material”, me lo das todo.
        pues yo soy feliz cada día, cada segundo a tu lado — y eso no tiene precio.
        Me hiciste el hombre más feliz del mundo cuando me dijiste “sí”.
        <br>Gracias por elegirme entre todas las personas del mundo.Y amarme como nadie lo ha hecho. </p>
    <p style="color:#ff4d4d; font-family:cursive; text-align:center;">Te amo ❤️</p>

    <p>
        Solo con ver tu <span class="arcoiris">sonrisa</span> y tus <span class="arcoiris">ojos</span> puedo vivir en paz.
        Pues tu eres mi tranquilidad.
        Ahora mi corazón lleva tu nombre, y cada día que pasa te amo más.
        Me quiero casar contigo y tener varios hijos, y ojalá algún día leamos nuestras cartas en familia,
        recordando estos momentos tan Bonitos 💫
    </p>

    <p class="espacial">Te amo hasta el infinito y más allá, en esta vida y en mil más 🚀</p>

    <p class="firma">— De Matu, para mi amada Jowi 💜</p>

    <img src="imagenes/IMG_0071.jpg" alt="Trulli" width="400" height="250" style="border-radius: 10px; box-shadow: 0 0 20px #0ff; margin-top: 20px;">
    


</body>
</html>
