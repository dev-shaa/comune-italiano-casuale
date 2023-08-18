# Comune italiano casuale
Un semplice script bash per stampare a schermo un comune italiano casuale.

I dati dei comuni sono forniti dall'ISTAT e sono reperibili a questo indirizzo: https://www.istat.it/it/archivio/6789.

## Esempio d'uso
```
$ comune
Carlantino (FG)
```

## Opzioni
È possibile specificare diverse opzioni. La sintassi per utilizzare questi comandi è la seguente:
```
comune [OPZIONI]
```

Di seguito vengono riportate le opzioni utilizzabili:
- `n NUM` specifica quanti comuni vengono stampati a schermo
- `l` usa il formato lungo
- `f` forza il download del file dei comuni, anche se già presente
- `h` mostra questo aiuto ed esce
