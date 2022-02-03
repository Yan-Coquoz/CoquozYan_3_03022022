# Oh my Food

Maquettage d'un site de commande de repas en ligne.

## Config SASS :

mettre SASS en global si ce n'est déja fait.
````bash
  npm -g sass 
````
Puis le dans le package.json.
- **Attention** à l'architecture des dossiers **et** au noms des fichiers
````json
"scripts": {
    "sass": "sass --watch ./sass/main.scss:./public/style.css"
  }
````

- Lancement de SASS dans le terminal :
````bash
 npm run sass
````

## Graphique

police : 
- texte: Roboto
- logo et titre : Shrikhand

couleur :
- Primaire : #9356DC
- Secondaire : #FF79DA
- Tertaire : #99E2D0