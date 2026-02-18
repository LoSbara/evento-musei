# Font Tox Typewriter

Questo progetto utilizza il font **Tox Typewriter** scaricato da dafont.com.

## Installazione

1. Scarica il font da: https://www.dafont.com/tox-typewriter.font
2. Una volta scaricato, estrai il file `.ttf` dal ZIP
3. Rinomina il file come **`ToxTypewriter.ttf`** (se non è già così)
4. Posiziona il file in questa cartella: `/musei-evento/fonts/`

## Struttura finale

```
musei-evento/
├── fonts/
│   └── ToxTypewriter.ttf  ← Metti il file qui
├── index.html
├── unlock.html
├── museo1.html
├── museo2.html
├── museo3.html
├── finale.html
└── README.md
```

Una volta che il file è in posizione, il font verrà automaticamente caricato da tutti i file HTML tramite `@font-face`.

## Risoluzione dei problemi

Se il font non appare:
- Verifica che il file si chiami esattamente **`ToxTypewriter.ttf`** 
- Verifica che sia nella cartella `/fonts/`
- Cancella la cache del browser e ricarica la pagina
- Apri la console nel browser (F12) per verificare se ci sono errori di caricamento del file
