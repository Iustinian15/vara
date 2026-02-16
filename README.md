<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sporturi de Vară</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            background: #f2f8ff;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #ff9800, #ff5722);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        section {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        h2 {
            color: #ff5722;
            margin-top: 40px;
        }

        .sport {
            background: white;
            border-radius: 15px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 10px 20px rgba(0,0,0,0.08);
        }

        .img-box {
            text-align: center;
            margin: 25px 0;
        }

        .img-box img {
            width: 100%;
            max-width: 400px;
            border-radius: 15px;
        }

        .img-box p {
            font-size: 0.9em;
            color: #666;
            margin-top: 8px;
        }

        ul {
            padding-left: 20px;
            line-height: 1.8;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
            margin-top: 40px;
        }

        /* Mobile tweaks */
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>🏖️ Sporturi de Vară</h1>
    <p>Mișcare, distracție și sănătate!</p>
</header>

<section>
    <h2>Ce sunt sporturile de vară?</h2>
    <p>
        Sporturile de vară sunt activități fizice practicate în special în anotimpul cald.
        Ele contribuie la menținerea sănătății și ne ajută să ne petrecem timpul liber
        într-un mod activ și plăcut.
    </p>

    <div class="img-box">
        <img src="https://www.iqool.ro/wp-content/uploads/2015/06/79.jpg" alt="Sporturi de vară">
        <p>Activități sportive practicate în sezonul cald.</p>
    </div>
</section>

<section>
    <h2>⚽ Fotbal</h2>
    <div class="sport">
        <p>
            Fotbalul este cel mai popular sport din lume. Se joacă în echipă și dezvoltă
            spiritul de cooperare, rezistența fizică și coordonarea.
        </p>
    </div>

    <div class="img-box">
        <img src="https://fitnet.ro/data_files/articles/images/2983/articles-de-ce-sa-joci-fotbal-8-motive-pe-care-trebuie-sa-le-stie-orice-persoana-fit_2983.jpg?cache=" alt="Fotbal">
        <p>Fotbalul este practicat de milioane de oameni în întreaga lume.</p>
    </div>
</section>

<section>
    <h2>🏊 Înot</h2>
    <div class="sport">
        <p>
            Înotul este ideal vara deoarece răcorește organismul și lucrează toți mușchii corpului.
            Este unul dintre cele mai sănătoase sporturi.
        </p>
    </div>

    <div class="img-box">
        <img src="https://inot-sport.ro/wp-content/uploads/2021/01/cursuri-inot-copii-grup-750x391.jpg.webp" alt="Inot">
        <p>Înotul este perfect pentru zilele călduroase.</p>
    </div>
</section>

<section>
    <h2>🎾 Tenis</h2>
    <div class="sport">
        <p>
            Tenisul dezvoltă viteza de reacție, concentrarea și coordonarea ochi-mână.
            Se poate juca atât individual, cât și în echipă.
        </p>
    </div>

    <div class="img-box">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Tennis_Racket_and_Balls.jpg/960px-Tennis_Racket_and_Balls.jpg" alt="Tenis">
        <p>Tenisul este un sport elegant și dinamic.</p>
    </div>
</section>

<section>
    <h2>Beneficiile sportului</h2>
    <ul>
        <li>Îmbunătățește sănătatea</li>
        <li>Crește energia</li>
        <li>Reduce stresul</li>
        <li>Ajută la socializare</li>
    </ul>
</section>

<footer>
    <p>Proiect realizat de elev • 2026</p>
</footer>

</body>
</html>
