# Jazzette

Appli mobile ludique pour apprendre à lire les grilles de jazz (adultes débutants).
Prototype actuel : **chapitre 5, « Les tonalités »**.

Web app sans build ni backend. En local :

```
python3 -m http.server 8123
```

puis http://localhost:8123 (vue téléphone, 390 px). Progression sauvegardée dans `localStorage`
(clé `jazzette-ch5-v1`). Menu debug : icône à droite de l'en-tête.

Réglages à tester en tête de `app.js` : `SOLID_WINS`, `MEMO_MAX_MISS`.
Pas encore fait : Bilan « cercle muet », alias Sol♭.
