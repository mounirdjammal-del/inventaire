# Application Inventaire Immobilisations

Application web d'inventaire des immobilisations, optimisee pour tablette.

## Acces
**URL :** https://VOTRE-USERNAME.github.io/inventaire/

## Deploiement GitHub Pages

1. Creez un depot GitHub nomme `inventaire` (Public)
2. Uploadez `index.html` et `README.md`
3. Settings -> Pages -> Branch main / root -> Save
4. Attendez 2 minutes -> URL disponible

## Configuration Google Cloud

Dans APIs & Services -> Identifiants -> Client ID OAuth :

Origines JS autorisees : https://VOTRE-USERNAME.github.io

URIs de redirection : https://VOTRE-USERNAME.github.io/inventaire/

## Feuilles Google Sheets utilisees

- Inventaire : base de donnees principale (lecture)
- Updates : mises a jour etat articles (ecriture temps reel)
- NouveauxArticles : articles ajoutes
- NouveauxEmplacements : emplacements crees
