<!-- ELUCENIA technical documentation · escore-de-wexner · fr · no clinical/professional/rights approval -->

# Score de Wexner (incontinence fécale)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escore-de-wexner)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Fuites de selles solides

`solido`

- `0` — Jamais
- `1` — Rarement (moins de 1 fois par mois)
- `2` — Parfois (moins de 1 fois par semaine, 1 fois ou plus par mois)
- `3` — Habituellement (moins de 1 fois par jour, 1 fois ou plus par semaine)
- `4` — Toujours (1 fois par jour ou plus)

### Fuites de selles liquides

`liquido`

- `0` — Jamais
- `1` — Rarement (moins de 1 fois par mois)
- `2` — Parfois (moins de 1 fois par semaine, 1 fois ou plus par mois)
- `3` — Habituellement (moins de 1 fois par jour, 1 fois ou plus par semaine)
- `4` — Toujours (1 fois par jour ou plus)

### Fuites de gaz

`gas`

- `0` — Jamais
- `1` — Rarement (moins de 1 fois par mois)
- `2` — Parfois (moins de 1 fois par semaine, 1 fois ou plus par mois)
- `3` — Habituellement (moins de 1 fois par jour, 1 fois ou plus par semaine)
- `4` — Toujours (1 fois par jour ou plus)

### Utilisation d’une protection ou d’un protège-slip

`protetor`

- `0` — Jamais
- `1` — Rarement (moins de 1 fois par mois)
- `2` — Parfois (moins de 1 fois par semaine, 1 fois ou plus par mois)
- `3` — Habituellement (moins de 1 fois par jour, 1 fois ou plus par semaine)
- `4` — Toujours (1 fois par jour ou plus)

### Modification du mode de vie

`estilo`

- `0` — Jamais
- `1` — Rarement (moins de 1 fois par mois)
- `2` — Parfois (moins de 1 fois par semaine, 1 fois ou plus par mois)
- `3` — Habituellement (moins de 1 fois par jour, 1 fois ou plus par semaine)
- `4` — Toujours (1 fois par jour ou plus)

## Édition de la méthode

Cleveland Clinic/Wexner Jorge 1993 : 5 items 0–4, total 0–20 ; incontinence fécale

## Formule documentée

Chacun des 5 items reçoit 0 à 4 selon la fréquence : jamais (0) ; rarement, moins de 1 fois par mois (1) ; parfois, moins de 1 fois par semaine et 1 ou plus par mois (2) ; habituellement, moins de 1 fois par jour et 1 ou plus par semaine (3) ; toujours, 1 fois ou plus par jour (4).

Total de 0 (continence parfaite) à 20 (incontinence complète).

## Limites et population

La sévérité déclarée de l’incontinence fécale ne définit pas sa cause ou son traitement. La revue originale souligne l’anamnèse, l’examen et l’évaluation physiologique avant traitement. L’échelle et ses fréquences doivent être appliquées selon la version ; le total ne remplace pas l’évaluation de la fonction anorectale.

## Références

- [Jorge JM, Wexner SD. Etiology and management of fecal incontinence. Dis Colon Rectum, 1993.](https://doi.org/10.1007/BF02050307)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Continence parfaite (0)


### 2

Incontinence présente : plus le score est élevé, plus la gravité est importante (maximum 20)

Utilisez le même score pour comparer avant et après le traitement.


### 3

Incontinence présente : plus le score est élevé, plus la gravité est importante (maximum 20)

Utilisez le même score pour comparer avant et après le traitement.

