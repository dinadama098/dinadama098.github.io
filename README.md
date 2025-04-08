/* style.css - Style façon Netflix */
body.dark-theme {
  background-color: #141414;
  color: #fff;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

h1, h2 {
  color: #fff;
  text-align: center;
}

.film-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 20px;
  justify-items: center;
}

.film {
  background-color: #222;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.5);
  text-align: center;
  transition: transform 0.3s ease;
}

.film:hover {
  transform: scale(1.05);
}

.film img {
  max-width: 100%;
  border-radius: 8px;
}

.view-more {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #e50914;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
  transition: background 0.3s;
}

.view-more:hover {
  background-color: #f40612;
}

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FilmXpress</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="dark-theme">
  <h1>Bienvenue sur FilmXpress</h1>
  <h2>Achetez vos films favoris instantanément</h2>

  <div class="film-list">
    <div class="film">
      <img src="le-destin-du-roi.jpg" alt="Le Destin du Roi" />
      <h3>Le Destin du Roi</h3>
      <a class="view-more" href="film1.html">Voir plus</a>
    </div>

    <div class="film">
      <img src="amour-interdit.jpg" alt="Amour Interdit" />
      <h3>Amour Interdit</h3>
      <a class="view-more" href="film2.html">Voir plus</a>
    </div>
  </div>
</body>
</html>
