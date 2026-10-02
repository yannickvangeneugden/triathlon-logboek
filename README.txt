TRIATHLON LOGBOEK APP

1. Open de Google Sheet.
2. Extensies > Apps Script.
3. Plak de inhoud van Code.gs en sla op.
4. Deploy > New deployment > Web app.
5. Execute as: Me. Who has access: Anyone.
6. Kopieer de /exec URL.
7. Open index.html via HTTPS-hosting en plak de URL bij Instellingen.

De app schrijft naar tabblad Training Log in de bestaande kolomvolgorde:
Datum, Week, Sport, Trainingstype, Duur, Afstand, HR, Watt, Pace, /100m, Cadans, RPE, Training Load, Z2?, Opmerking.
