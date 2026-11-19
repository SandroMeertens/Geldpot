# Geldpot – Klassenpot

Een simpele spaarpot voor de klas: vul een bedrag in, druk op **Erbij** en zie het geld in de glazen pot vallen.

- **Erbij**: geld in de pot (voor iedereen)
- **🔒 Leerkracht**: met een eigen pincode verschijnen Eruit, ongedaan maken en ⚙️ instellingen; na 10 minuten gaat het slot vanzelf dicht
- **📱 Meedoen**: toont een QR-code en klascode. Leerlingen sturen vanaf hun iPad (`/ipad`) een bedrag dat meteen in de pot op het digibord valt (via de gratis dienst ntfy.sh, alleen bedragen, geen namen). Op de iPad kunnen leerlingen ook de pot bekijken (tabblad "Bekijk de pot")
- **⚙️**: naam van de pot en de klascode; pot op nul zetten
- **Goedkeuren**: bedragen van iPads komen eerst in een wachtrij (📱 n wachten); de leerkracht keurt ze goed of weigert ze (uit te zetten bij ⚙️)
- **Back-up**: bij ⚙️ een back-upbestand maken en terugzetten
- **📋 Alle stortingen** (leerkracht): lijst met datum, tijd en bron (digibord of iPad); losse stortingen weghalen
- **📺 Presentatiestand**: alleen de pot, het totaal en de grafiek; stoppen met de knop of Esc
- **Grafiek**: zo groeide de pot, per dag (of per storting op de eerste dag)
- Op de iPad ververst *Bekijk de pot* zichzelf ongeveer elke 2 minuten
- **App-icoon**: leerlingen kunnen de Geldpot op het beginscherm van hun iPad zetten (Deel → Zet op beginscherm)
- Het bedrag wordt bewaard in de browser van het apparaat waarop je het invult

De QR-code wordt gemaakt met [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) van Kazuhiko Arase (MIT-licentie).
