# Manga Master (pilote 0.1.0)

Quiz entre amis en direct sur les mangas et animes : un Sensei ouvre un dojo (code à 4 caractères + QR code), jusqu'à 30 nakamas rejoignent depuis leur téléphone. Mêmes mécaniques que Lore Master (Chacun sa voie / Duel de clans / Tous contre le Sensei, Mêlée, 9 formats de questions).

Pilote : 3 thèmes × 30 questions (One Piece, Dragon Ball, Studio Ghibli).

- `python3 build.py` : génère `dist/` (à publier tel quel sur GitHub Pages)
- `node test/bank_test.js`, `node test/content_test.js` : contrôle de la banque
- `src/manga_master.sql` : à exécuter une fois dans le SQL Editor de Supabase (tables `mm_*`)
- `quiz/*.json` : questions (schéma `quiz-bestiaire/1`), `conf: "probable"` = rédigé avec source, à auditer
Outil libre CC BY-NC 4.0, non affilié aux éditeurs ni aux studios.
