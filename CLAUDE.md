# Jazzette : consignes de travail

Appli mobile ludique pour apprendre à lire les grilles de jazz, pour adultes débutants.
Critère de simplicité : un enfant de 8 ans qui sait seulement lire la clé de sol doit tout comprendre.
Projet indépendant de Loops (autre dépôt). Fichiers statiques sans build : `index.html`, `app.js`, `style.css`.

## Décisions déjà prises (ne pas redemander)
- Web app mobile-first (390 px), sans backend, progression en `localStorage`. Stack simple, sans dépendance.
- Apprentissage « tables de multiplication » : courtes séries, répétition. Pas d'écoute d'accords : on joue à l'œil.
- Design : fond `#FAFAF7`, texte `#2B2B33`, majeur ☀ `#FFE9A8`, mineur ☾ `#C9D8F5`, bonne réponse `#CDEBD3`, erreur `#F7D0D0`.
  Cartes arrondies à ombre légère, carte « illuminée » = halo doux. Aucune illustration enfantine ni mascotte dans les jeux.
- Pictos (☀ ☾, boutons) toujours en SVG, jamais en symbole texte (emoji sur Android).
- Notation des tonalités partout (cartes, messages, bilan) : `M` = majeur, `m` = mineur, collé au nom : FaM, Fam, Si♭M, Sol♯m. Pas de « majeur » / « mineur » écrits.
- Textes : français, tutoiement, phrases courtes, peu de texte. Jamais « c'est parti », « manche » ni « objectif » à l'écran.
- Chapitre 5 : 5 cycles, 20 paliers, 4 jeux (Trouve l'armure, Trouve la tonalité, Les cousines, Mémo).
  Déroulé : échauffement (dès le cycle 2), tuto (4 tours, sans erreur possible), solo (4 tours, 2 erreurs = palier rejoué).
- Mémoire par famille d'armure (Do ☀ et La ☾ ensemble) : fragile après erreur, solide après 3 réussites du premier coup dont une un autre jour.

## À faire ensuite
Bilan « cercle muet » (fin des cycles 3 et 5), alias Fa♯/Sol♭, chapitres suivants (le II-V-I).

## Règles
- Réponses et textes de l'interface en français.
- Ne jamais committer de clés ni de jetons.
