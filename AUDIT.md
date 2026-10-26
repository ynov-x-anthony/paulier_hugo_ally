# AUDIT.md : à compléter

Pour chaque ligne, retrouve le problème correspondant dans `src/App.tsx` / `src/App.css`
et remplis les 3 colonnes. Il y a **6 problèmes volontaires** dans ce starter.

| # | Problème trouvé (où, quoi) | Principe WCAG (P / O / U / R) | Pourquoi c'est bloquant, et pour qui |
|---|------------------------------|-------------------------------|----------------------------------------|
| 1 | Les images sont absents et n'ont pas d'attribbut "alt" | Perceptible | Ce qui pénalise tout le monde en cas de manque d'image|
| 2 | Le Statut "annulé"/"publié" est porté uniquement par la couleur du point| Perceptible | Pour les personnes avec des problèmes de vue, cela est bloquant pour différencier les catégories |
| 3 | Bandeau .carousel qui s'affiche sans aucun moyen de le fermer/mettre en pause | Opérable  | Pour tout les utilisateurs : tout contenu qui apparaît doit pouvoir être maîtrisé par celui-ci |
| 4 | Tout en bas aveac les Trois liens avec le même texte "cliquez ici"| Compréhensible |  Le texte d'un lien doit avoir un sens hors contexte, c'est-à-dire que beaucoup d'utilisateurs de lecteur d'écran naviguent par liste de liens|
| 5 | Le bouton "see-more" qui utilise une balise div au lieu d'une balise bouton| Opérable | Inatteignable au clavier, et annoncé comme texte brut par un lecteur d'écran, pas comme un contrôle, ce qui casse la navigation |
| 6 | La balise h3 qui est fausse | Robuste | La hiérarchie de titres sert à naviguer rapidement une page ; un saut de balise casse cette navigation |

> Rappel : P = Perceptible, O = Opérable, U = Utilisable (Compréhensible), R = Robuste.
