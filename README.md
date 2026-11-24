# Hexaciv open data : examen civique (questions d'entraînement, centres)

**Hexaciv n'est pas un site officiel.** Ces données sont compilées par Hexaciv (https://hexaciv.com), un site indépendant de préparation à l'examen civique. Les questions de ce dépôt sont des questions d'entraînement écrites par Hexaciv ; ce ne sont pas les questions de l'examen.

Licence : [Licence Ouverte 2.0 (Etalab)](LICENCE). Mention de paternité demandée : « Source : Hexaciv, https://hexaciv.com » avec la date du fichier (24 novembre 2026 pour les questions, 21 octobre 2026 pour les centres).

## Fichiers

| Fichier | Contenu |
|---|---|
| `examen-civique-questions-entrainement-fr-en-ar.csv` | 114 questions d'entraînement à l'examen civique (80 questions de connaissance, 34 mises en situation), chacune en français, anglais et arabe : 342 lignes, une par question et par langue. Colonnes : question, 4 choix, numéro et texte de la bonne réponse, explication, thème, parcours (CSP : carte de séjour pluriannuelle, CR : carte de résident, NAT : naturalisation), intitulé de la question sur la liste publiée par le ministère de l'Intérieur (questions de connaissance), titre et lien de la fiche du ministère qui justifie la réponse. |
| `examen-civique-centres-tarifs-sources.csv` | 470 centres d'examen civique en France : adresse, opérateur (FEI, CCI Paris Île-de-France), téléphone, site du centre, liens de réservation CCIP. Le tarif n'est renseigné que lorsque le centre le publie (99 centres) ; une cellule vide signifie « tarif non publié ». |
| `examen-civique-centres-par-departement.csv` | 100 départements : étrangers résidents (Insee RP 2022), nombre de centres FEI et CCIP, étrangers par centre. |

## Questions d'entraînement : ce qu'elles sont

- Les questions de connaissance sont écrites par Hexaciv à partir de la liste officielle des questions de connaissance publiée par le ministère de l'Intérieur ; les mises en situation sont écrites par Hexaciv sur le modèle de l'examen. La formulation et les choix sont ceux d'Hexaciv.
- Les lignes en anglais et en arabe sont des traductions non officielles (colonne `statut_texte`).
- Les explications sont rédigées avec l'IA à partir de la fiche officielle citée dans la colonne `fiche_url` (colonne `mention_ia`).
- Ce sont les questions du test blanc gratuit d'Hexaciv, déjà en accès libre sur https://hexaciv.com/test-civique-gratuit. Extraction du 24 novembre 2026 (colonne `extrait_le`).
- Signaler une erreur : hello@hexaciv.com, avec l'identifiant de la question (colonne `id`).

## Sources et dates de lecture (centres)

- Liste des centres : France Éducation international (colonne `liste_source`, lue le `liste_lue_le`) et sessions CCI Paris Île-de-France.
- Tarifs : pour chaque ligne qui en a un, `tarif_source_url` (page du centre), `tarif_citation` (extrait exact) et `tarif_lu_le` (date de lecture, 21 octobre 2026).
- Étrangers résidents : Insee, recensement de la population 2022.

Les tarifs et adresses peuvent changer : vérifiez auprès du centre avant de réserver. Aucune garantie de réussite ni de prix.

## Versions en ligne

- Test blanc gratuit (questions) : https://hexaciv.com/test-civique-gratuit
- Chercheur de centres : https://hexaciv.com/centres
- CSV d'origine : https://hexaciv.com/data/examen-civique-centres-tarifs-sources.csv et https://hexaciv.com/data/examen-civique-centres-par-departement.csv

Contact : hello@hexaciv.com
