# À vérifier — fiabilité des réponses (Manga Master v0.7.1)

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
