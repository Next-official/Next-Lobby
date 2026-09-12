# Next Lobby

Questo progetto è, diciamocelo chiaramente, del tutto superfluo e non strettamente necessario. Tuttavia, l'ho realizzato semplicemente perché adoro lo stile degli **albori del Web**: quell'estetica anni '90 fatta di bordi tridimensionali grigi, tipografia in stile *Windows 95*, contatori di visite e testi in scorrimento. È stato un divertente esercizio di stile retro declinato in chiave moderna.

---

## Dettagli Tecnici

La struttura della pagina è contenuta in un unico file standalone, privo di dipendenze esterne o framework, per garantire massima leggerezza ed esecuzione immediata.

* **HTML5**: Struttura semantica pulita e priva di commenti generati.



* **CSS3**:
**Layout Responsive**: Utilizzo di CSS Grid con `repeat(auto-fit, minmax(...))` combinato con `clamp()` per la gestione fluida dei font e dei margini su qualsiasi risoluzione schermo.
**Rilievo 3D Web 1.0**: Implementazione di bordi tridimensionali stile Bevel/Emboss ottenuti tramite la combinazione di `border-top/left` chiari e `border-right/bottom` scuri, integrati con l'effetto `transform: translate()` e inversione dei bordi sullo stato `:active` dei pulsanti.



* **JavaScript (ES6)**:
**Contatore Visitatori Locale**: Funzione custom per il tracciamento delle visite tramite la Web Storage API (`localStorage`).
**DOM Manipulation**: Generazione dinamica dei singoli elementi cifra del contatore con formattazione a pad fisso (6 cifre).
