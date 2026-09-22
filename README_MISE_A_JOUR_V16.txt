OA – Observations en accompagnement – V16
==============================================

Nouveautés V16
- Analyse automatique de la photo dès son import.
- 1 colonne = 1 agent.
- Les abréviations d’agents sont préremplies lorsqu’elles peuvent être reconnues par le navigateur ou reprises d’un tableau déjà renseigné.
- Exemple générique dans les champs : MAR ROB = MARTIN Robert.
- L’écran d’association abréviation / nom complet n’apparaît que si au moins un agent est inconnu.
- Bouton unique « Valider les noms » pour alimenter la base locale des agents.
- Si tous les agents sont déjà connus, ouverture directe de la fenêtre « Quel agent allez-vous coter ? ».
- Le choix de l’agent reste facultatif : « Continuer sans priorités » reste disponible.
- Les warnings rouge / jaune sont appliqués uniquement aux activités de la colonne de l’agent choisi.

Mise à jour GitHub Pages
1. Remplacer index.html par celui de ce package.
2. Remplacer service-worker.js pour forcer le cache V16.
3. manifest.webmanifest et les icônes peuvent être laissés tels quels s’ils sont déjà identiques.
4. Faire Commit changes puis attendre la publication GitHub Pages.
5. Sur le téléphone, relancer l’application et accepter la mise à jour si la popup apparaît.

Les observations et les correspondances d’agents déjà mémorisées dans le stockage local ne sont pas supprimées.
