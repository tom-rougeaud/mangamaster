# Manga Master (pilote 0.1.0)

Quiz entre amis en direct sur les mangas et animes : un Sensei ouvre un dojo (code à 4 caractères + QR code), jusqu'à 30 apprenti(e)s rejoignent depuis leur téléphone. Mêmes mécaniques que Lore Master (Esprit Shōnen / Duel de clans / Tous contre le Sensei, Mêlée, 9 formats de questions).

Pilote : 3 thèmes × 30 questions (One Piece, Dragon Ball, Studio Ghibli).

- `python3 build.py` : génère `dist/` (à publier tel quel sur GitHub Pages)
- `node test/bank_test.js`, `node test/content_test.js` : contrôle de la banque
- `src/manga_master.sql` : à exécuter une fois dans le SQL Editor de Supabase (tables `mm_*`)
- `quiz/*.json` : questions (schéma `quiz-bestiaire/1`), `conf: "probable"` = rédigé avec source, à auditer
Outil libre CC BY-NC 4.0, non affilié aux éditeurs ni aux studios.

## Mise à jour v0.11.0

- Nouveau royaume « Archétypes et figures du manga » : 15 thèmes transversaux (héros sans don, cheveux blancs, démons et compagnons, mentors, rivaux, génies, sportifs, équipes, arts martiaux et épées, techniques et éléments, armes à feu, écoles et lieux, mondes extrêmes et temps, cuisine et repas).
- Banque : 111 thèmes, 6 525 questions (+668, dont 155 « vérifié » et 513 « probable »).
- Rien à changer côté Supabase (tables `mm_*` inchangées).
- Liste des questions non recoupées : `a-verifier/nouveaux-themes-v0.11.0-probables.csv` (dépôt GitHub Pages).

## Mise à jour v0.11.0

- Nouveau royaume « Archétypes et figures du manga » : 15 thèmes transversaux (héros sans don, cheveux blancs, démons et compagnons, mentors, rivaux, génies, sportifs, équipes, arts martiaux et épées, techniques et éléments, armes à feu, écoles et lieux, mondes extrêmes et temps, cuisine et repas).
- Banque : 111 thèmes, 6 525 questions (+668, dont 155 « vérifié » et 513 « probable »).
- Rien à changer côté Supabase (tables `mm_*` inchangées).
- Liste des questions non recoupées : `a-verifier/nouveaux-themes-v0.11.0-probables.csv` (dépôt GitHub Pages).

## Mise à jour v0.11.1

Recoupement Wikipédia des 15 thèmes « Archétypes et figures du manga » : 308 questions vérifiées sur 667, plusieurs réponses corrigées. Voir `a-verifier/README.md`. Rien à modifier dans Supabase.

## Mise à jour v0.11.2

Deuxième tour de recoupement à deux sources : 344 questions vérifiées sur 649 dans les 15 thèmes transversaux, plusieurs réponses corrigées, 18 questions faibles retirées. Voir `a-verifier/README.md`. Rien à modifier dans Supabase.

## Mise à jour v0.11.3

Nouvelle règle de tirage : dans une même partie (solo, duel, boss, remplacement d’une question), le moteur n’aligne plus deux questions « jumelles » : même bonne réponse (QCM, intrus, texte à trous, qui suis-je), réponse d’une question présente dans l’énoncé d’une autre, ou énoncés partageant trois mots-clés ou plus. Si le thème choisi est trop petit pour tenir la règle, la partie est complétée plutôt que raccourcie (cas observé seulement avec 30 questions tirées dans un thème de moins de 60). Plus un thème compte de questions, mieux la règle tient. Rien à modifier dans Supabase.
