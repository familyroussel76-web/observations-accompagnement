OA — Mise à jour V18

Nouveauté principale :
- après analyse de la photo, l'application lit l'abréviation située au-dessus de chaque colonne agent ;
- chaque case « Abréviation lue sur le tableau » est automatiquement préremplie avec l'abréviation détectée ;
- si l'abréviation existe déjà dans la base locale, le nom complet associé est rempli automatiquement ;
- si tous les agents sont connus, l'écran de saisie des noms est sauté et le choix de l'agent à coter s'ouvre directement ;
- si la reconnaissance native du navigateur n'est pas disponible, l'application tente un OCR de secours en ligne. La lecture des couleurs et la cotation restent utilisables hors ligne.

Mise à jour GitHub Pages :
1. Remplacer index.html.
2. Remplacer service-worker.js pour forcer le cache V18.
3. Les icônes et manifest.webmanifest peuvent rester identiques.

Les données enregistrées localement par les versions précédentes sont conservées.
