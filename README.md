# La Terre et les animaux

Jeu de sciences en quiz : 10 bonnes réponses le plus vite possible, thèmes « La Terre » et « Les animaux », une explication après chaque question, 20 badges tous les 10 bonnes réponses.

## Tranches d'âge
Chaque question est classée dans une tranche : 3-6, 6-9, 9-12 ou 12-16 ans (170 questions). Le joueur choisit une ou plusieurs tranches avant de lancer une partie ; la tranche proposée par défaut se déduit du niveau scolaire de l'enfant (CM1 → 9-12 ans). La tranche choisie est mémorisée dans la progression et notée dans le détail de chaque partie.

## Fichiers
- `index.html` : le jeu (branché à la salle de jeux via `SalleJeu`, identifiant `sciences-terre-animaux`)
- `questions.js` : banque de questions `[id, question, [bonne réponse, fausses…], explication, tranche]` (la bonne réponse est en premier, le jeu mélange les choix)
- `fonts/` : polices Fredoka et Nunito auto-hébergées (licence OFL)
- `fond.jpg`, `favicon*`, `apple-touch-icon.png` : images
- `audio/musique.mp3` (facultatif) : musique de fond, le bouton n'apparaît que si le fichier existe
- `voix-plume/` : phrases de Plume (à venir)

Progression enregistrée dans la salle de jeux.
