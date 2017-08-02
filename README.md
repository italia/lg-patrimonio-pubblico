# Linee guida per la valorizzazione del patrimonio informativo pubblico - anno 2017

Questo documento rappresenta l'aggiornamento annuale, previsto dall'articolo 52 comma 7 del Codice dell'Amministrazione Digitale e da un'azione del piano triennale, delle linee guida per la valorizzazione del patrimonio informativo pubblico.

Il documento sarà in costante aggiornamento anche a seguito dei lavori che si svolgeranno nella seconda metà del 2017.

Le linee guida sono ora navigabili [online](http://lg-patrimonio-pubblico.readthedocs.io/it/latest/) e collegate anche a guide tecniche disponibili online (incluse le [linee guida per i cataloghi dati](https://linee-guida-cataloghi-dati-profilo-dcat-ap-it.readthedocs.io/it/latest/), le [schede descrittive delle basi dati di interesse nazionale](http://pianotri-schede-bdin.readthedocs.io/en/latest/) e l'[elenco delle basi dati chiave](http://elenco-basi-di-dati-chiave.readthedocs.io/it/latest/)).

### Requisiti

- [Sphinx](http://www.sphinx-doc.org/en/stable/)

### Build
Dopo aver apportato le dovute modifiche in [`src/`](./src) esegui

```
sphinx-build -b html src docs
```

oppure

```
make html
```
