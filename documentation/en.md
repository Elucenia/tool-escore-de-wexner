<!-- ELUCENIA technical documentation · escore-de-wexner · en · no clinical/professional/rights approval -->

# Wexner score (fecal incontinence)

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-de-wexner)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Solid stool leakage

`solido`

- `0` — Never
- `1` — Rarely (less than once a month)
- `2` — Sometimes (less than once a week, once or more a month)
- `3` — Usually (less than once a day, once or more a week)
- `4` — Always (1 or more times per day)

### Liquid stool leakage

`liquido`

- `0` — Never
- `1` — Rarely (less than once a month)
- `2` — Sometimes (less than once a week, once or more a month)
- `3` — Usually (less than once a day, once or more a week)
- `4` — Always (1 or more times per day)

### Gas leakage

`gas`

- `0` — Never
- `1` — Rarely (less than once a month)
- `2` — Sometimes (less than once a week, once or more a month)
- `3` — Usually (less than once a day, once or more a week)
- `4` — Always (1 or more times per day)

### Use of pad or liner

`protetor`

- `0` — Never
- `1` — Rarely (less than once a month)
- `2` — Sometimes (less than once a week, once or more a month)
- `3` — Usually (less than once a day, once or more a week)
- `4` — Always (1 or more times per day)

### Lifestyle alteration

`estilo`

- `0` — Never
- `1` — Rarely (less than once a month)
- `2` — Sometimes (less than once a week, once or more a month)
- `3` — Usually (less than once a day, once or more a week)
- `4` — Always (1 or more times per day)

## Method edition

Cleveland Clinic/Wexner Jorge 1993: 5 items 0–4, total 0–20; fecal incontinence

## Documented formula

Each of the 5 items receives 0 to 4 by frequency: never (0); rarely, less than 1 time per month (1); sometimes, less than 1 time per week and 1 or more per month (2); usually, less than 1 time per day and 1 or more per week (3); always, 1 or more times per day (4).

Total from 0 (perfect continence) to 20 (complete incontinence).

## Limits and population

Reported fecal incontinence severity does not define its cause or treatment. The original review emphasizes history, examination and pretreatment physiological assessment. The scale and its frequencies must be applied according to the version; the total does not replace assessment of anorectal function.

## References

- [Jorge JM, Wexner SD. Etiology and management of fecal incontinence. Dis Colon Rectum, 1993.](https://doi.org/10.1007/BF02050307)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Perfect continence (0)


### 2

Incontinence present: the higher the score, the greater the severity (maximum 20)

Use the same score to compare before and after treatment.


### 3

Incontinence present: the higher the score, the greater the severity (maximum 20)

Use the same score to compare before and after treatment.

