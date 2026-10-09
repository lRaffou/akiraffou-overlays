# Akiraffou — overlays OBS

Dépôt public des overlays prêts à utiliser dans OBS : cadre webcam animé et écrans de début, de pause et de fin, dans le style corail et noir bleuté de la chaîne.

Les maquettes et captures de référence sont conservées séparément dans le dépôt privé `akiraffou-stream-style`.

## Cadre webcam

URL : https://lraffou.github.io/akiraffou-overlays/

Dans OBS : source Navigateur, largeur 500, hauteur 280. Placer au-dessus de la caméra et désactiver l’ancien cadre. Le centre reste transparent. Contour animé et glitch discret.

## Écran de début

URL : https://lraffou.github.io/akiraffou-overlays/start.html

Source Navigateur OBS : 1920 × 1080. Fond plein écran noir bleuté, titres corail, animation d’attente et glitch discret. L’overlay réseaux horizontal existant est intégré en bas à gauche. Ne pas ajouter une deuxième copie des réseaux sur cette scène. Aucun compte à rebours automatique.

## Écran de pause

URL : https://lraffou.github.io/akiraffou-overlays/pause.html

Source Navigateur OBS : 1920 × 1080. Écran « Je reviens », avec les mêmes animations et le glitch discret que l’écran de début. L’overlay réseaux horizontal existant est intégré en bas à gauche. Aucun compte à rebours automatique.
## Écran de fin

URL : https://lraffou.github.io/akiraffou-overlays/end.html

Source Navigateur OBS : 1920 × 1080. Écran « Merci à tous », avec les mêmes animations et le glitch discret que les autres scènes. L’overlay réseaux horizontal existant est intégré en bas à gauche. Aucun son ni compte à rebours automatique.
## Alerte follow

Aperçu : https://lraffou.github.io/akiraffou-overlays/follow-preview.html

Carte flottante noir bleuté, bordure corail, glitch bref, pseudo du nouveau follower et petit son de bienvenue. Durée par défaut : 5 secondes. Les follows successifs s’affichent l’un après l’autre.

L’alerte réelle est installée dans StreamElements, overlay « Akiraffou — Alerte follow ». Ajouter son URL StreamElements à une source Navigateur OBS en 1920 × 1080. L’aperçu GitHub Pages est une démonstration en boucle : il ne reçoit pas les follows Twitch. Durée et son sont réglables dans StreamElements.
## Liens OBS après le renommage

Ce dépôt s’appelait auparavant `akiraffou-webcam`. Utiliser désormais les nouvelles URL ci-dessus dans les sources Navigateur OBS.
