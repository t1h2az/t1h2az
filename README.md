<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plateforme de Cours de Mathématiques</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .course {
            margin-bottom: 20px;
        }

        .course h2 {
            color: #333;
            margin-bottom: 10px;
        }

        .course p {
            margin-bottom: 10px;
            line-height: 1.6;
        }

        .quiz {
            background-color: #f9f9f9;
            padding: 15px;
            margin-top: 20px;
        }

        .quiz h3 {
            margin-bottom: 10px;
        }

        .quiz form {
            margin-bottom: 20px;
        }

        .quiz label {
            display: block;
            margin-bottom: 5px;
        }

        .quiz input[type="text"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .quiz input[type="submit"] {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .quiz input[type="submit"]:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<header>
    <h1>Plateforme de Cours de Mathématiques</h1>
</header>

<nav>
    <a href="#cours">Cours</a>
    <a href="#quiz">Quiz</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="cours">
        <h2>Cours de Mathématiques</h2>
        <div class="course">
            <h3>Introduction à l'Algèbre</h3>
            <p>Ce cours couvre les bases de l'algèbre, y compris les équations linéaires, les inéquations, et les polynômes.</p>
            <p><a href="#">Commencer le cours</a></p>
        </div>

        <div class="course">
            <h3>Calcul Différentiel</h3>
            <p>Apprenez les concepts fondamentaux du calcul différentiel, comme les dérivées et les applications.</p>
            <p><a href="#">Commencer le cours</a></p>
        </div>

        <div class="course">
            <h3>Géométrie Euclidienne</h3>
            <p>Explorez les principes de base de la géométrie, y compris les angles, les triangles, et les cercles.</p>
            <p><a href="#">Commencer le cours</a></p>
        </div>
    </section>

    <section id="quiz" class="quiz">
        <h3>Quiz de Mathématiques</h3>
        <form action="#" method="post">
            <label for="question1">Quel est le résultat de 5 + 3 ?</label>
            <input type="text" id="question1" name="question1" placeholder="Votre réponse ici">

            <label for="question2">Calculez la dérivée de x².</label>
            <input type="text" id="question2" name="question2" placeholder="Votre réponse ici">

            <input type="submit" value="Soumettre le quiz">
        </form>
    </section>
</div>

</body>
</html>
