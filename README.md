# CarMatch

Aide à la décision pour choisir sa prochaine voiture en France : quels modèles regarder, en quelle motorisation (électrique, hybride rechargeable, hybride, essence), et s'il vaut mieux **acheter**, **louer en LLD** ou passer par une **voiture de fonction**.

L'application tient compte de votre usage (kilométrage, longs trajets, recharge à domicile), de votre conduite, de vos priorités et de votre situation fiscale, avec les règles françaises 2026 :

- prime « coup de pouce » CEE (qui remplace le bonus écologique depuis juillet 2025) ;
- malus CO2 et malus au poids ;
- avantage en nature des voitures de fonction, avec l'abattement de 70 % pour les électriques éco-scorées.

## Fonctionnalités

- **Configuration guidée** en 6 étapes (trajets, conduite, priorités, véhicule, finances, voiture de fonction), une question à la fois, avec le meilleur match affiché en direct.

- **Ma voiture** : top 3 à regarder, motorisation conseillée, formule la plus avantageuse et coût mensuel réel. Ce coût inclut énergie, entretien, malus, prime, intérêts, et déduit la revente.
- **Classement** filtrable d'une cinquantaine de modèles distribués en France, toutes origines et toutes silhouettes.
- **Financement** : achat, LLD et voiture de fonction côte à côte pour le modèle de votre choix.
- **Comparateur** jusqu'à 3 véhicules, avec un radar et un tableau détaillé.
- **Garage éditable** : ajouter, modifier ou exclure des véhicules, importer ou exporter en JSON.
- **Réglages** : toutes les hypothèses fiscales et de coûts sont modifiables.
- **Profils multiples** et préréglages types.
- **Thème** clair ou sombre, six couleurs d'accent.
- **IA intégrée** (« Décrivez votre besoin », « Avis de l'IA ») lorsque l'application est ouverte comme artifact dans Claude.

## Utilisation

Tout tient dans un seul fichier, `index.html`, sans dépendance ni étape de build.

- **En local** : ouvrez `index.html` dans un navigateur.
- **En ligne** : activez GitHub Pages sur la branche `main` (Settings → Pages).

Hors de Claude, les fonctions IA sont masquées automatiquement. Vos profils et réglages sont alors enregistrés dans le navigateur, via `localStorage`.

## Limites

- Les fiches véhicules sont indicatives (fin 2026, version représentative) : vérifiez la finition exacte en concession.
- Le barème du malus CO2 est reconstitué entre les points officiels publiés.
- Assurance, carte grise, pneus et frais de restitution LLD ne sont pas inclus.
- CarMatch est un simulateur de comparaison, pas un conseil financier ou fiscal personnalisé.
