# Machetă 3D — Pompă de căldură CO₂ transcritică

Macheta interactivă a unei pompe de căldură cu CO₂ (R744) în regim transcritic,
pentru încălzire (calorifere 55/45 °C) și apă caldă menajeră (60 °C).

**Pagina live:** https://mmt15.github.io/pdc--co2/

## Ce conține

109 componente și 37 de conducte, verificate automat: nicio conductă nu atinge
alta, fiecare capăt intră într-un racord real și fiecare armătură stă pe un
tronson drept, în ordinea de curgere.

- **circuitul de CO₂** — compresor, separator de ulei cu retur în carter, două
  gas coolere în serie, vană de reglaj a înaltei presiuni, receiver cu bypass
  de gaz flash, filtru deshidratator, vizor, vană de expansiune electronică,
  evaporator și separator de lichid pe aspirație
- **siguranța pe CO₂** — supape pe înaltă presiune, pe receiver și pe joasă
  presiune, fiecare cu țeavă de evacuare spre exterior
- **circuitul de apă sursă** (5/0 °C) și cel de **încălzire** (55/45 °C), cu
  rezervor tampon, vas de expansiune, supapă de siguranță și golire
- **apă caldă menajeră** — 2 × 300 l în serie, încălzite direct de CO₂ prin
  HX-302, cu grup de siguranță complet pe apa rece
- **automatizare** — tablou electric, convertizor de frecvență pentru compresor,
  sondă de temperatură exterioară, instrumentație și interblocări după P&ID
- **listă de linii generată din model** — lungimi reale pe axa curbelor, număr
  de coturi, armăturile de pe fiecare tronson și totaluri pe diametru

## Utilizare

- **Orbit / Liber (WASD)** — două moduri de cameră
- click pe orice componentă → fișa ei tehnică, cota de montaj și racordurile
- **straturi pe categorii** — echipamente, conducte, armături, senzori, cu
  subcategorii și combinații gata făcute, de exemplu „CO₂ + senzori T°”
- **scenarii** — regim nominal, extrasezon 45/35, pornire, standby, val de
  dușuri cu prioritate ACM, lipsă de debit, presiune mare pe CO₂
- plan de secțiune, pentru a vedea rack-ul din spate

## Atenție

Cotele componentelor folosesc dimensiuni de gabarit aproximative. Lungimile de
țeavă sunt exacte **pentru acest aranjament**, dar verifică fiecare cotă față de
fișele reale ale echipamentelor comandate înainte de execuție.

Rămân de stabilit: varianta circuitului de sursă (puț → puț, puț → canalizare
sau buclă intermediară cu antigel), puterea schimbătorului HX-302, debitul
pompei P-ACM și dimensionarea finală a compresorului.
