# Booking Net Calculator 💶

Calcola rapidamente il **netto** a partire dal lordo di una prenotazione su Booking.com, considerando:

- **Commissione Booking**: 15% del lordo
- **Costo transazione**: 1,5% del lordo
- **IVA (22%)** calcolata su *(commissione + costo transazione)*
- **Cedolare secca**: 21% del lordo

Il risultato mostra il **netto**, il dettaglio di tutte le voci di costo e l’incidenza percentuale sul lordo.

---

## 🚀 Demo Online
🔗 **[Apri la calcolatrice](https://booking-calculator.carlocappai.me)**

---


## ⚙️ Funzionalità
- Interfaccia responsive in **Bulma CSS**
- Input lordo e personalizzazione di:
    - Costo transazione
    - Cedolare secca
- Calcolo in tempo reale
- Progress bar che mostra l’incidenza dei costi
- Riepilogo “sticky” in basso per avere lordo/costi/netto sempre a vista

---

## 🛠 Tecnologie usate
- **HTML5** + **JavaScript** vanilla
- **[Bulma CSS](https://bulma.io/)** per il design system
- **GitHub Pages** per il deploy

---

## 📦 Installazione locale
Clona il repository e apri `index.html` nel browser:

```bash
git clone git@github.com:capaio/booking-net-calculator.git
cd booking-net-calculator
open index.html  # MacOS
# oppure
xdg-open index.html  # Linux
