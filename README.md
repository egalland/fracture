# Fracture — L’atelier des petits éclats

Un atelier créatif en laine pour transformer vos images en 2D et 3D.

**[Ouvrir l’atelier](https://egalland.github.io/fracture/)** · [Le code](https://github.com/egalland/fracture)

## Jouer avec une image

Cliquez sur **Importer une image** au-dessus du tableau, puis choisissez une expérience : fractures irrégulières, rubans, relief sculpté, big bang, accordéon, portail, ondes ou constellation. Ajustez le relief, l’ouverture, le nombre de découpes et la rotation. Filou, la pelote animée, vous accompagne avec ses expressions et ses conseils.

- Import PNG, JPEG, WebP, AVIF et GIF fixe, jusqu’à 25 Mo.
- Textures conservées sur les fragments ; relief construit à partir de la luminosité.
- Comparaison à l’original, nouvelle découpe aléatoire et reconstruction.
- Souris, clavier, rotation, zoom et gestes tactiles prévus.
- Export PNG/JPEG, définition jusqu’à ×3 et transparence en PNG.
- Images traitées sur votre appareil, sans envoi à un serveur.

Les images très grandes sont adaptées à 4096 pixels sur leur plus grand côté. Trois.js utilise WebGL quand disponible ; un rendu Canvas compatible prend le relais sinon. WebGL et les gestes mobiles n’ont pas été validés sur appareil physique. Les réglages et l’image importée ne sont pas conservés après rechargement.

## Lancer en local

Servez la racine avec un serveur HTTP, par exemple `python -m http.server 8000`, puis ouvrez `http://localhost:8000`. Aucun build n’est nécessaire.

Three.js r170 est fourni dans `vendor/`, avec sa licence MIT. Les images de laine ont été générées pour ce projet. Les polices utilisent Google Fonts avec des polices de secours.

## Raccourcis

Espace : pause · R : rotation · B : big bang · C : recoudre · 2/3 : vue · flèches : tourner · +/− : zoom · E : exporter.

## Historique

Trois versions de réalisation ont été réimportées dans leur ordre d’origine : atelier initial, refonte en laine et nouvelles transformations, puis import visible au-dessus du tableau. Les commits de publication sont attribués à egalland ; leurs dates correspondent à la publication GitHub.
