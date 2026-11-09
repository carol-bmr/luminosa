# Luminosa Gioielli — Sito e-commerce vetrina

Sito web per **Luminosa Gioielli**, piccola attività artigianale di Cristina,
che crea collane e bracciali a mano all'uncinetto con filato per gioielli,
cristalli e pietre dure.

🔗 **Sito online:** https://carol-bmr.github.io/luminosa/

---

## Di cosa si tratta

Ho progettato e realizzato questo sito per aiutare mia mamma a vendere le sue
creazioni artigianali online e a presentarle nei mercatini. L'obiettivo era
un sito **professionale, gratuito e facile da aggiornare** per chi non ha
competenze tecniche.

## Caratteristiche

- **Catalogo dinamico** con 35 collane e 43 bracciali, filtrabili per categoria
- **Scheda prodotto a comparsa** (lightbox) con foto ingrandita, descrizione,
  lavorazione, lunghezza e significato delle pietre
- **Carrello** con calcolo automatico del totale e della spedizione fissa
- **Promo automatica**: ogni 3 collane, 1 bracciale in omaggio (calcolato dal carrello)
- **Configuratore "Crea la tua collana"**: il cliente compone il gioiello
  su misura (lunghezza, punto, pietre, colori) e invia la richiesta
- **Checkout** verso WhatsApp con riepilogo ordine precompilato e campi di spedizione
- **Sezioni editoriali**: storia dell'artigiana, lavorazione, punti dell'uncinetto, mercatini
- **Tema chiaro coerente** ispirato ai colori del marchio (crema, marrone, oro)
- **Responsive** (ottimizzato per telefono) e **accessibile**

## Come è fatto

- **HTML, CSS e JavaScript puri**, senza framework né dipendenze esterne
- Pagina singola autonoma (`index.html`) + cartella `img/`
- Immagini ottimizzate per il web e caricamento differito (`lazy loading`)
- Catalogo gestito come struttura dati in JavaScript, facile da modificare
- Pubblicato gratuitamente con **GitHub Pages**

## Struttura

```
index.html              → il sito
img/                    → tutte le immagini
  collane/              → foto delle collane (nome file = nome gioiello)
  braccialetti/         → foto dei bracciali
  mamma.jpg, ...        → foto dell'artigiana e delle lavorazioni
  locandina1.jpg, ...   → locandine dei mercatini
CATALOGO.txt            → elenco leggibile di tutti i prodotti
LEGGIMI.txt             → istruzioni per aggiornare il sito
```

## Come aggiornare

Nessun codice da toccare per le modifiche comuni: basta **sostituire un file
immagine** con uno dallo stesso nome. Per nomi, prezzi e descrizioni c'è una
tabella commentata in `index.html`. Istruzioni complete in `LEGGIMI.txt`.

---

*Progetto realizzato da [Carol Pagano](https://github.com/carol-bmr) —
sito artigianale costruito da zero con HTML, CSS e JavaScript.*
