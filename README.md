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

Carte flottante noir bleuté, GIF animé de Luffy en fond avec voile sombre, bordure corail, glitch bref, pseudo du nouveau follower et petit son de bienvenue. Durée par défaut : 5 secondes. Les follows successifs s’affichent l’un après l’autre.

L’alerte réelle est installée dans StreamElements, overlay « Akiraffou — Alertes ». Ajouter son URL StreamElements à une source Navigateur OBS en 1920 × 1080. L’aperçu GitHub Pages est une démonstration en boucle : il ne reçoit pas les follows Twitch. Durée et son sont réglables dans StreamElements.
## Alertes sub et resub

Aperçu : https://lraffou.github.io/akiraffou-overlays/sub-preview.html

Animation de Luffy fournie pour les subs, en fond sur toute la carte avec un voile sombre. Nouveau sub : pseudo et remerciement. Resub : nombre de mois. Sub offert : remerciement au donateur ; les dons groupés sont regroupés dans une seule alerte.

Les follows et subs partagent la même source StreamElements « Akiraffou — Alertes » et une file commune. Garder la même URL OBS en 1920 × 1080. Les boutons de test sont dans les réglages Alertes du widget. Les aperçus GitHub Pages sont des démonstrations.
## Alerte raid

Aperçu : https://lraffou.github.io/akiraffou-overlays/raid-preview.html

GIF animé de Luffy fourni pour les raids, en fond sur toute la carte. Pseudo du raideur et nombre de personnes accueillies. Même source StreamElements « Akiraffou — Alertes » : conserver la même URL OBS en 1920 × 1080. Bouton « Tester un raid » dans les réglages Alertes du widget.
## Alerte tip

Aperçu : https://lraffou.github.io/akiraffou-overlays/tip-preview.html

GIF animé de Nami en fond sur toute la carte. Pseudo et montant du don, avec la devise du compte StreamElements (EUR par défaut). Même source « Akiraffou — Alertes » : garder la même URL OBS. Bouton « Tester un tip » dans les réglages Alertes du widget.
## Liens OBS après le renommage

Ce dépôt s’appelait auparavant `akiraffou-webcam`. Utiliser désormais les nouvelles URL ci-dessus dans les sources Navigateur OBS.
