<!-- ELUCENIA technical documentation · escore-de-wexner · pt-BR · no clinical/professional/rights approval -->

# Escore de Wexner (incontinência fecal)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escore-de-wexner)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Perda de fezes sólidas

`solido`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez por mês)
- `2` — Às vezes (menos de 1 vez por semana, 1 ou mais por mês)
- `3` — Geralmente (menos de 1 vez por dia, 1 ou mais por semana)
- `4` — Sempre (1 ou mais vezes por dia)

### Perda de fezes líquidas

`liquido`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez por mês)
- `2` — Às vezes (menos de 1 vez por semana, 1 ou mais por mês)
- `3` — Geralmente (menos de 1 vez por dia, 1 ou mais por semana)
- `4` — Sempre (1 ou mais vezes por dia)

### Perda de gases

`gas`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez por mês)
- `2` — Às vezes (menos de 1 vez por semana, 1 ou mais por mês)
- `3` — Geralmente (menos de 1 vez por dia, 1 ou mais por semana)
- `4` — Sempre (1 ou mais vezes por dia)

### Uso de absorvente ou protetor

`protetor`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez por mês)
- `2` — Às vezes (menos de 1 vez por semana, 1 ou mais por mês)
- `3` — Geralmente (menos de 1 vez por dia, 1 ou mais por semana)
- `4` — Sempre (1 ou mais vezes por dia)

### Alteração do estilo de vida

`estilo`

- `0` — Nunca
- `1` — Raramente (menos de 1 vez por mês)
- `2` — Às vezes (menos de 1 vez por semana, 1 ou mais por mês)
- `3` — Geralmente (menos de 1 vez por dia, 1 ou mais por semana)
- `4` — Sempre (1 ou mais vezes por dia)

## Edição do método

Cleveland Clinic/Wexner Jorge 1993:5 itens 0–4, total 0–20; incontinência fecal

## Fórmula documentada

Cada um dos 5 itens recebe de 0 a 4 pela frequência: nunca (0); raramente, menos de 1 vez por mês (1); às vezes, menos de 1 vez por semana e 1 ou mais por mês (2); geralmente, menos de 1 vez por dia e 1 ou mais por semana (3); sempre, 1 ou mais vezes por dia (4).

Total de 0 (continência perfeita) a 20 (incontinência completa).

## Limites e população

A gravidade relatada de incontinência fecal não define sua causa ou tratamento. A revisão original destaca história, exame e avaliação fisiológica pré-tratamento. A escala e suas frequências devem ser aplicadas conforme a versão; o total não substitui avaliação da função anorretal.

## Referências

- [Jorge JM, Wexner SD. Etiology and management of fecal incontinence. Dis Colon Rectum, 1993.](https://doi.org/10.1007/BF02050307)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Continência perfeita (0)


### 2

Incontinência presente: quanto maior o escore, maior a gravidade (máximo 20)

Use o mesmo escore para comparar antes e depois do tratamento.


### 3

Incontinência presente: quanto maior o escore, maior a gravidade (máximo 20)

Use o mesmo escore para comparar antes e depois do tratamento.

