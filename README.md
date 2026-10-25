# Hexaciv open data : centres d'examen civique

**Hexaciv n'est pas un site officiel.** Ces données sont compilées par Hexaciv (https://hexaciv.com), un site indépendant de préparation à l'examen civique. Elles ne contiennent aucune question ni réponse d'examen.

Licence : [Licence Ouverte 2.0 (Etalab)](LICENCE). Mention de paternité demandée : « Source : Hexaciv, https://hexaciv.com/centres, mise à jour du 21 octobre 2026 ».

## Fichiers

| Fichier | Contenu |
|---|---|
| `examen-civique-centres-tarifs-sources.csv` | 470 centres d'examen civique en France : adresse, opérateur (FEI, CCI Paris Île-de-France), téléphone, site du centre, liens de réservation CCIP. Le tarif n'est renseigné que lorsque le centre le publie (99 centres) ; une cellule vide signifie « tarif non publié ». |
| `examen-civique-centres-par-departement.csv` | 100 départements : étrangers résidents (Insee RP 2022), nombre de centres FEI et CCIP, étrangers par centre. |

## Sources et dates de lecture

- Liste des centres : France Éducation international (colonne `liste_source`, lue le `liste_lue_le`) et sessions CCI Paris Île-de-France.
- Tarifs : pour chaque ligne qui en a un, `tarif_source_url` (page du centre), `tarif_citation` (extrait exact) et `tarif_lu_le` (date de lecture, 21 octobre 2026).
- Étrangers résidents : Insee, recensement de la population 2022.

Les tarifs et adresses peuvent changer : vérifiez auprès du centre avant de réserver. Aucune garantie de réussite ni de prix.

## Versions en ligne

- Chercheur de centres : https://hexaciv.com/centres
- CSV d'origine : https://hexaciv.com/data/examen-civique-centres-tarifs-sources.csv et https://hexaciv.com/data/examen-civique-centres-par-departement.csv

Contact : hello@hexaciv.com
