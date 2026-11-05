# À vérifier — fiabilité des réponses (Manga Master)

Audit de la banque de 7 329 questions. Méthode :

1. contrôles automatiques : réponse vs explication, doublons de questions aux réponses différentes, distracteurs cités dans l’explication ;
2. recoupement d’une cinquantaine de fiches Wikipédia (nombre de tomes, années de début/fin, studios, magazines, prix) ;
3. les erreurs avérées sont corrigées ; les cas douteux sont listés ci-dessous.

**Limite honnête** : les 7 154 questions marquées « probable » n’ont pas toutes été recoupées avec une source externe. Une relecture humaine reste utile, surtout pour les dates et les chiffres.

Le détail est aussi dans `questions-a-verifier.csv` (ouvrable dans Excel/LibreOffice).

# Questions à vérifier

| id | thème | question | statut | problème | suggestion |
|---|---|---|---|---|---|
| c6-013 | cites-dor-albator | Comment s’appelle le vaisseau de Capitaine Flam ? | CORRIGÉ v0.7.1 | La bonne réponse était placée en distracteur : le vaisseau est la Comète. | Réponse = La Comète |
| n4-007 | nana | Dans quel magazine Nana paraît-il ? | CORRIGÉ v0.7.1 | Nana est publié dans Cookie (Shūeisha), pas Cherry. Contredisait b8-010. | Réponse = Cookie |
| fc8-005 | frieren | Quel prix Shogakukan remporte le manga en 2021 ? | CORRIGÉ v0.7.1 | Le Manga Taishō date de 2021 ; le prix Shogakukan est de 2022. | Année = 2022 |
| ds-012 / ds-018 / t2-039 / p8-028 / p8-031 | dr-stone | Combien de tomes compte Dr. Stone ? | À vérifier | Selon la source consultée, 26 tomes (hors tome spécial) ou 27 en comptant le one-shot Reboot Byakuya. | Préciser « hors tome spécial » partout |
| x8-026 | hunter-x-hunter | Combien de tomes compte la série en français (édition Kana) ? | À vérifier | Série toujours en cours : le nombre de tomes VF évolue et dépend de la date. | Reformuler (« au Japon, au moins 38 ») ou retirer |
| sm-013 / sm-018 | sailor-moon | Le manga Sailor Moon compte 12 tomes ? | À vérifier | 12 tomes = édition originale ; 18 tomes pour la shinsōban (édition de luxe). Ambigu. | Préciser « édition originale » |
| sk-012 / sk-018 / k8-019 / k8-026 | sakura-chasseuse-de-cartes | Le manga compte 12 tomes | À vérifier | Confirmer : 12 tomes (série d’origine) ; Clear Card est une autre série. | Garder « série d’origine » |
| k8-012 / k8-035 | sakura-chasseuse-de-cartes | Combien de cartes Clow existent au départ ? | À vérifier | Le décompte diffère entre manga et anime (cartes Sakura incluses ou non). | Préciser « dans le manga » |
| mo8-010 | monster | Quel prix reçoit Monster en 2001 ? | À vérifier | Prix Shogakukan en 1999 et prix Tezuka (excellence) en 2001 : vérifier que le distracteur 1999 n’est pas ambigu. | Préciser « prix d’excellence » |
| ak-008 / ak-026 / k5-016 | akira | Publication en France en 1990 (Glénat) | À vérifier | Certaines sources donnent 1990, d’autres 1991 pour le 1er tome. | Contrôler dans le catalogue Glénat |
| i8-012 | hajime-no-ippo | Combien d’épisodes compte la première série animée ? | À vérifier | Un site donne 76 (spécial inclus). | Préciser « hors spéciaux » |
| d5-034 / dd-019 | doublage-et-diffusion | En quelle année ADN est-il lancé ? | À vérifier | Deux questions identiques donnent deux années différentes. | Vérifier l’année de lancement et harmoniser |
| i5-005 / hb8-007 | habitant-de-linfini | Qu’est-ce qui rend Manji immortel ? | À vérifier | Deux formulations différentes pour la même réponse (kessen-chū). | Harmoniser (« vers sacrés ») |
| va-017 / w5-010 | manga-vs-anime | Pages d’un chapitre hebdomadaire | À vérifier | Valeur indicative, deux réponses différentes. | Garder la fourchette 17–20 seulement |
| g7 / titres-fr-vs-jp / autres | tous thèmes | Dates de sortie, éditeurs, studios, magazines | Non vérifié ligne à ligne | Le reste a été contrôlé uniquement par cohérence interne (réponse/explication/doublons), pas contre une source externe. | Relecture humaine souhaitée |


## Ajout v0.8.0 : 18 thèmes transversaux

Les 18 thèmes transversaux (Esprit shōnen, Méchants et rivalités, Sciences, Isekai, Sport, Yōkai, Magical girls, Cuisine-métiers-école, Pouvoirs, Armes, Tropes, Japon, Mascottes, Jeux vidéo, Horreur, Romance, Histoire du Japon, Musique) sont rédigés par IA et **n’ont pas été recoupés ligne à ligne** avec des sources externes : tous marqués « probable ». Une relecture humaine est la bienvenue, surtout pour les dates, auteurs et studios.

## Mise à jour v0.9.0 — qualité des questions (octobre 2026)

La banque passe de 6 954 à **5 341 questions** : on préfère moins de questions, mais sans répétition ni réponse évidente.

**Ce qui a été fait**
- **Répétitions dans une même série** : environ 1 500 questions posant le même fait sous une autre forme (QCM + vrai/faux + texte à trous + « Qui suis-je ? ») ont été supprimées. On garde la forme la plus riche.
- **Réponse contenue dans la question** (par ex. « Quel esprit habite la forêt de Mon voisin Totoro ? → Totoro ») : une centaine de questions retirées ou réécrites. Les indices « Je m’appelle X » des « Qui suis-je ? » ont été remplacés par de vrais indices.
- **Réponses trop évidentes** : « Naruto » ou « Dragon Ball » servaient d’intrus dans une centaine de questions « lequel n’est pas… ? » : remplacés par des intrus plausibles du même domaine. Les bonnes réponses nettement plus longues que les autres ont été rééquilibrées (une centaine de questions).
- **Vrai/faux à indices** (« toujours », « uniquement », « jamais »…) retirés.

**Vérifications externes faites cette fois** (Wikipédia, presse spécialisée)
| Point | Résultat |
|---|---|
| Lancement d’ADN (Anime Digital Network) | 2013 confirmé (Livres Hebdo). La question qui disait 2014 (d5-034) est supprimée. |
| Éditeur français de Dr. Stone | Glénat (confirmé). |
| Éditeur français de Bleach | Glénat : la question e5-047 le classait à tort comme non-Glénat, elle est supprimée. |
| « Rewrite » (Asian Kung-Fu Generation) | Quatrième opening de Fullmetal Alchemist (2003) : exact. |
| Studio de l’anime Orange | Telecom Animation Film (production TMS Entertainment), 13 épisodes ; manga lancé en 2012 : exact. |
| Sailor Moon : nombre de tomes | Ambigu (12 ou 18 selon l’édition) : question retirée. |
| Pages d’un chapitre hebdomadaire | Valeur non fiable : question retirée. |
| Niveaux de Super Saiyan dans le manga | Formulation ambiguë : question retirée. |

**Reste non recoupé** : les dates, auteurs et studios de la grande majorité des questions n’ont été contrôlés que par cohérence interne, et par ma connaissance générale pour les années de début/fin des séries (toutes relues une à une). Une relecture humaine reste utile.


## Mise à jour v0.10.0 — 13 nouveaux thèmes (novembre 2026)

**+516 questions** (banque : 5 857 questions, 96 thèmes) et un nouveau royaume, « Shōnen : combats et magie ».

| Thème | Questions | Dont recoupées (Wikipédia) |
|---|---|---|
| Seven Deadly Sins | 47 | 42 |
| Record of Ragnarok (Valkyrie Apocalypse) | 42 | 36 |
| Fairy Tail | 43 | 20 |
| Black Clover | 34 | 20 |
| Soul Eater et Fire Force | 43 | 30 |
| Gintama | 34 | 17 |
| Assassination Classroom | 35 | 21 |
| Yu Yu Hakusho | 41 | 26 |
| La vague Jump+ (Chainsaw Man, Spy × Family, Dandadan, Kaiju No. 8, Sakamoto Days) | 51 | 45 |
| Kingdom (Seinen) | 37 | 33 |
| Junji Itō (Seinen, thème sombre) | 43 | 31 |
| Overlord (Isekai) | 35 | 23 |
| Dungeon Meshi (Isekai/fantasy) | 31 | 27 |

**Méthode** : les faits marqués « vérifié » (371 questions) viennent des pages Wikipédia consultées pendant ce travail (dates, magazines, studios, prix, nombre de tomes ou d’épisodes). Les 145 autres sont « probables » : ce sont surtout des faits sur les personnages (équipes, pouvoirs, liens entre personnages) tirés de ma connaissance générale, non recoupés ligne à ligne. Leur liste est dans `nouveaux-themes-v0.10.0-probables.csv`.

**Points de prudence**
- Les séries toujours en cours (Kingdom, Record of Ragnarok) n’ont aucune question sur le nombre de tomes, qui changerait vite.
- Black Clover est terminé (mai 2026) : les questions le traitent comme tel.
- Éditeurs français (Pika, Kazé, Kurokawa…) : non vérifiés sur les pages consultées, sauf Kana pour Yu Yu Hakusho. À recouper avant d’en faire une règle.
- Le titre français « Valkyrie Apocalypse » vient de ta demande ; il n’a pas été recoupé avec un éditeur.
- Les thèmes sont plus petits (31 à 51 questions) que les thèmes historiques (50 à 70) : les séries ont été choisies pour la variété, pas pour la profondeur.

## Mise à jour v0.11.0 — 15 thèmes transversaux (novembre 2026)

**+668 questions** (banque : 6 525 questions, 111 thèmes) et un nouveau royaume, « Archétypes et figures du manga » : des thèmes qui traversent les séries (héros sans pouvoir, cheveux blancs, démons, sportifs, armes à feu, cuisine…).

| Thème | Questions | Dont recoupées |
|---|---|---|
| Héros sans don et héros cabossés | 54 | 29 |
| Orphelins, familles et amitiés | 50 | 13 |
| Cheveux blancs et argentés | 35 | 15 |
| Démons, esprits et compagnons | 51 | 10 |
| Mentors et professeurs | 33 | 7 |
| Rivaux et anti-héros | 48 | 12 |
| Génies et stratèges | 38 | 0 |
| Sportifs et boxeurs | 48 | 22 |
| Équipes, duos et capitaines | 37 | 26 |
| Arts martiaux et épées | 54 | 4 |
| Techniques et éléments | 56 | 5 |
| Armes à feu et pistoleros | 36 | 0 |
| Écoles et lieux | 44 | 6 |
| Mondes extrêmes et voyages dans le temps | 44 | 0 |
| Cuisine et repas | 40 | 6 |

**Méthode** : seules 155 questions sont marquées « vérifié » (dates, magazines, studios, auteurs, nombre de tomes et faits de personnages lus sur les pages Wikipédia consultées). Les 513 autres sont « probables » : faits canoniques de personnages, d’armes et de techniques rédigés de ma connaissance générale, **non recoupés ligne à ligne**. Leur liste est dans `nouveaux-themes-v0.11.0-probables.csv`.

**Points de prudence**
- **Couleurs de cheveux** : les pages Wikipédia consultées ne les indiquent pas. Toutes les questions sur les cheveux sont « probables », y compris celles du thème « Cheveux blancs et argentés ».
- **Faits du monde réel** (judo, karaté, tamahagane, forgerons Masamune et Muramasa, cuisine japonaise : miso, dashi, mochi…) : connaissances générales, non recoupées.
- Les noms français (Tortue Géniale, Sacha, Kaiō du Nord…) suivent l’usage courant ; non vérifiés auprès des éditeurs.
- Armes à feu : les armes de tir à l’élastique ou à l’arc (Usopp) ont été exclues du thème.
- Environ 55 questions trop évidentes (réponse dans l’énoncé, vrai/faux triviaux) ou ambiguës ont été retirées pendant la relecture ; les doublons entre thèmes proches ont été réduits mais pas tous supprimés.
- Les 30 idées de départ ont été regroupées en 15 thèmes : deux idées proches partagent un même thème.
