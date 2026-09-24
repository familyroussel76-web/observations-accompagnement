OA — Mise à jour V17

Correction principale :
- détection automatique du nombre de colonnes/agents dans la photo ;
- les fines lignes de séparation du tableau ne découpent plus artificiellement la zone colorée ;
- le cas observé « 12 colonnes détectées alors qu'il y en a 4 » est corrigé.

Mise à jour GitHub Pages :
1. Remplacer index.html par celui de cette archive.
2. Remplacer service-worker.js afin de forcer le nouveau cache V17.
3. manifest.webmanifest et les icônes sont inchangés, mais sont inclus dans l'archive complète.
4. Commit changes sur GitHub.
5. Ouvrir l'application et accepter/recharger la mise à jour si elle est proposée.

Les données locales existantes (observations, base agents, réglages) ne sont pas supprimées.
