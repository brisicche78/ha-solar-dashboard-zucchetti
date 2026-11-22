# HA Solar Dashboard – Personalizzazione Zucchetti

Repository personale per raccogliere le immagini personalizzate della card
[ha-solar-dashboard](https://github.com/404GamerNotFound/ha-solar-dashboard),
adattate all'impianto di casa.

## Obiettivo

Mantenere lo stile e la prospettiva delle immagini originali, con queste
modifiche permanenti:

- pannelli fotovoltaici solo sul tetto della casa principale;
- capannino laterale senza pannelli fotovoltaici;
- box auto vuoto, senza auto né colonnina;
- palo elettrico in cemento armato sullo sfondo a destra;
- nessuna linea blu di collegamento verso il palo, per il momento.

Le varianti meteo e giorno/notte dovranno mantenere la stessa struttura della
casa, cambiando soltanto illuminazione, cielo e condizioni atmosferiche.

## Struttura

```text
immagini/
└── casa/
    ├── giorno/
    ├── notte/
    ├── nuvoloso/
    ├── pioggia/
    ├── temporale/
    ├── neve/
    └── altre-varianti/
```

I nomi definitivi dei file saranno allineati a quelli effettivamente richiesti
dalla card, dopo aver verificato il codice sorgente.

## Nota

Questo repository contiene soltanto le personalizzazioni. Il progetto
originale resta separato e non viene modificato.
