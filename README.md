# Musei Evento - Progetto Interattivo 🏛️

Questo è un progetto web per un evento interattivo nei musei. I partecipanti devono trovare i codici in ogni museo e inserirli per sbloccare le sezioni.

## File inclusi:
- **museo1.html** - Pagina di verifica codice per il Museo 1 (Codice di default: 111)
- **museo2.html** - Pagina di verifica codice per il Museo 2 (Codice di default: 222)
- **museo3.html** - Pagina di verifica codice per il Museo 3 (Codice di default: 333)
- **finale.html** - Pagina finale con le 3 sezioni da sbloccare

## Come personalizzare i codici:

Apri ogni file museo (museo1.html, museo2.html, museo3.html) e trova questa riga:

```javascript
const correctCode = "111"; // Cambia questo numero!
```

Sostituisci con il codice a 3 numeri (da 1 a 9) che vuoi usare.

### Esempio:
```javascript
// Museo 1
const correctCode = "111"; // Codice per il Museo 1

// Museo 2
const correctCode = "222"; // Codice per il Museo 2

// Museo 3
const correctCode = "333"; // Codice per il Museo 3
```

## Come funziona:

1. I partecipanti ricevono un QR code per ogni museo
2. Inquadrando il QR code, vengono portati alla pagina di verifica
3. Trovano un indizio (targa, scritta, etc.) che contiene il codice a 3 numeri
4. Inseriscono il codice e se corretto, la sezione si sblocca
5. Vengono automaticamente portati alla pagina finale
6. Quando tutte e 3 le sezioni sono sbloccate, ricevono il messaggio di completamento

## Tecnologia:

- **localStorage** - Per salvare lo stato degli sblocchi nel browser del partecipante
- **HTML/CSS/JavaScript** - Tutto lato client, nessun server necessario
- **Responsive** - Funziona su mobile, tablet e desktop

## I QR codes devono puntare a:
- Museo 1: `https://narratori-di-mondi.netlify.app/museo1.html`
- Museo 2: `https://narratori-di-mondi.netlify.app/museo2.html`
- Museo 3: `https://narratori-di-mondi.netlify.app/museo3.html`
- Pagina finale: `https://narratori-di-mondi.netlify.app/finale.html`

(Sostituisci il dominio con quello che scegli su Netlify)

---

**Creato per un evento fantastico! Buon divertimento! 🎉**
