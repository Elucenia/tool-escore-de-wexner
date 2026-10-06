<!-- ELUCENIA technical documentation · escore-de-wexner · it · no clinical/professional/rights approval -->

# Punteggio di Wexner (incontinenza fecale)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-de-wexner)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Perdita di feci solide

`solido`

- `0` — Mai
- `1` — Raramente (meno di 1 volta al mese)
- `2` — A volte (meno di 1 volta a settimana, 1 o più al mese)
- `3` — Generalmente (meno di 1 volta al giorno, 1 o più a settimana)
- `4` — Sempre (1 o più volte al giorno)

### Perdita di feci liquide

`liquido`

- `0` — Mai
- `1` — Raramente (meno di 1 volta al mese)
- `2` — A volte (meno di 1 volta a settimana, 1 o più al mese)
- `3` — Generalmente (meno di 1 volta al giorno, 1 o più a settimana)
- `4` — Sempre (1 o più volte al giorno)

### Perdita di gas

`gas`

- `0` — Mai
- `1` — Raramente (meno di 1 volta al mese)
- `2` — A volte (meno di 1 volta a settimana, 1 o più al mese)
- `3` — Generalmente (meno di 1 volta al giorno, 1 o più a settimana)
- `4` — Sempre (1 o più volte al giorno)

### Uso di assorbente o proteggislip

`protetor`

- `0` — Mai
- `1` — Raramente (meno di 1 volta al mese)
- `2` — A volte (meno di 1 volta a settimana, 1 o più al mese)
- `3` — Generalmente (meno di 1 volta al giorno, 1 o più a settimana)
- `4` — Sempre (1 o più volte al giorno)

### Alterazione dello stile di vita

`estilo`

- `0` — Mai
- `1` — Raramente (meno di 1 volta al mese)
- `2` — A volte (meno di 1 volta a settimana, 1 o più al mese)
- `3` — Generalmente (meno di 1 volta al giorno, 1 o più a settimana)
- `4` — Sempre (1 o più volte al giorno)

## Edizione del metodo

Cleveland Clinic/Wexner Jorge 1993: 5 item 0–4, totale 0–20; incontinenza fecale

## Formula documentata

Ciascuno dei 5 item riceve da 0 a 4 per frequenza: mai (0); raramente, meno di 1 volta al mese (1); talvolta, meno di 1 volta a settimana e 1 o più al mese (2); solitamente, meno di 1 volta al giorno e 1 o più a settimana (3); sempre, 1 o più volte al giorno (4).

Totale da 0 (continenza perfetta) a 20 (incontinenza completa).

## Limiti e popolazione

La gravità riferita dell’incontinenza fecale non ne definisce la causa o il trattamento. La revisione originale sottolinea anamnesi, esame e valutazione fisiologica prima del trattamento. La scala e le sue frequenze devono essere applicate secondo la versione; il totale non sostituisce la valutazione della funzione anorettale.

## Riferimenti

- [Jorge JM, Wexner SD. Etiology and management of fecal incontinence. Dis Colon Rectum, 1993.](https://doi.org/10.1007/BF02050307)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Continenza perfetta (0)


### 2

Incontinenza presente: più alto è il punteggio, maggiore è la gravità (massimo 20)

Usare lo stesso punteggio per confrontare prima e dopo il trattamento.


### 3

Incontinenza presente: più alto è il punteggio, maggiore è la gravità (massimo 20)

Usare lo stesso punteggio per confrontare prima e dopo il trattamento.

