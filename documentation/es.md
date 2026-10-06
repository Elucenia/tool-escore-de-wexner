<!-- ELUCENIA technical documentation · escore-de-wexner · es · no clinical/professional/rights approval -->

# Puntuación de Wexner (incontinencia fecal)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-de-wexner)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Pérdida de heces sólidas

`solido`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez al mes)
- `2` — A veces (menos de 1 vez por semana, 1 o más al mes)
- `3` — Generalmente (menos de 1 vez al día, 1 o más por semana)
- `4` — Siempre (1 o más veces al día)

### Pérdida de heces líquidas

`liquido`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez al mes)
- `2` — A veces (menos de 1 vez por semana, 1 o más al mes)
- `3` — Generalmente (menos de 1 vez al día, 1 o más por semana)
- `4` — Siempre (1 o más veces al día)

### Pérdida de gases

`gas`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez al mes)
- `2` — A veces (menos de 1 vez por semana, 1 o más al mes)
- `3` — Generalmente (menos de 1 vez al día, 1 o más por semana)
- `4` — Siempre (1 o más veces al día)

### Uso de compresa o protector

`protetor`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez al mes)
- `2` — A veces (menos de 1 vez por semana, 1 o más al mes)
- `3` — Generalmente (menos de 1 vez al día, 1 o más por semana)
- `4` — Siempre (1 o más veces al día)

### Alteración del estilo de vida

`estilo`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez al mes)
- `2` — A veces (menos de 1 vez por semana, 1 o más al mes)
- `3` — Generalmente (menos de 1 vez al día, 1 o más por semana)
- `4` — Siempre (1 o más veces al día)

## Edición del método

Cleveland Clinic/Wexner Jorge 1993: 5 ítems 0–4, total 0–20; incontinencia fecal

## Fórmula documentada

Cada uno de los 5 ítems recibe de 0 a 4 por frecuencia: nunca (0); raramente, menos de 1 vez al mes (1); a veces, menos de 1 vez por semana y 1 o más al mes (2); generalmente, menos de 1 vez al día y 1 o más por semana (3); siempre, 1 o más al día (4).

Total de 0 (continencia perfecta) a 20 (incontinencia completa).

## Límites y población

La gravedad declarada de la incontinencia fecal no define su causa ni su tratamiento. La revisión original destaca la historia clínica, el examen y la evaluación fisiológica antes del tratamiento. La escala y sus frecuencias deben aplicarse según la versión; el total no sustituye la evaluación de la función anorrectal.

## Referencias

- [Jorge JM, Wexner SD. Etiology and management of fecal incontinence. Dis Colon Rectum, 1993.](https://doi.org/10.1007/BF02050307)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Continencia perfecta (0)


### 2

Incontinencia presente: cuanto mayor es la puntuación, mayor es la gravedad (máximo 20)

Utilice la misma puntuación para comparar antes y después del tratamiento.


### 3

Incontinencia presente: cuanto mayor es la puntuación, mayor es la gravedad (máximo 20)

Utilice la misma puntuación para comparar antes y después del tratamiento.

