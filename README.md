# Jev · 11 niveaux de démos live

Une page HTML autonome pour découvrir Jev (`~typesafe/jev-latest`), un modèle qui ne rédige pas : on lui envoie un état et des questions, il rend des choix et des probabilités que le code utilise directement. Onze niveaux, du simple oui/non à l'agent qui décide seul quand l'appeler, et en bonus un Crossy Road en Three.js que Jev joue en direct.

## Démarrer

1. Télécharge `jev-eleves.html` et ouvre-le dans ton navigateur (double-clic). Pas d'installation, pas de serveur.
2. Crée une clé sur [openrouter.ai/keys](https://openrouter.ai/keys) et colle-la dans le champ « Ta clé OpenRouter » du panneau de gauche (bouton « ☰ Niveaux » sur mobile).
3. Choisis un niveau et clique sur « Appeler Jev ».

## Ta clé et ton budget

- La clé reste en mémoire dans la page, n'est jamais enregistrée sur le disque, et n'est envoyée qu'à `openrouter.ai`. Elle disparaît quand tu fermes ou recharges la page : il faut la recoller à chaque ouverture. C'est voulu, parce qu'un fichier HTML ouvert en double-clic partage son stockage avec tous les autres fichiers HTML locaux, et un fichier piégé pourrait la lire.
- Chaque appel est facturé sur ton compte OpenRouter, avec le coût affiché sous la réponse. Un appel coûte une fraction de centime : mesuré, 38 décisions de jeu pour 0,0016 $.

## Les niveaux

| # | Niveau |
| --- | --- |
| 01 | Le if intelligent |
| 02 | Le choix multiple |
| 03 | Le score composite |
| 04 | Le portier par la confiance |
| 05 | Le routage de modèles et d'agents |
| 06 | Les garde-fous dans l'agent |
| 07 | Le compactage automatique |
| 08 | Les lectures à bas prix |
| 09 | Les fichiers à l'échelle |
| 10 | L'agent qui décide quand appeler Jev |
| 11 | Bonus · Jev joue au jeu |

Au niveau 11, tu peux jouer toi-même aux flèches ou lancer « Jev joue » : le trafic ne s'arrête jamais, Jev décide en environ 300 ms, et le jeu ne laisse passer que les coups dont la survie est prouvée. Objectif : la ligne 100.

## Hors ligne

La page fonctionne sans connexion (three.js et la police sont intégrés) : tu peux lire les niveaux et jouer au clavier. Seuls les appels à Jev demandent internet.

## Licence

Code sous licence MIT, voir `LICENSE`. Les composants tiers (three.js, la police Press Start 2P, le code d'origine du jeu) gardent leur propre licence, détaillée dans `THIRD_PARTY_NOTICES`.
