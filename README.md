React Advanced Project
Overzicht
Dit project is gebouwd met de volgende tools:

Talen en frameworks: React.js, JavaScript, Chakra UI, JSON
Functionaliteit: CRUD-methodologie


Installatie-instructies
Eerste installatie:
Open je terminal en voer de volgende commando's uit: 
npm install
npm run dev

JSON-server starten:
Open een tweede terminal en voer het volgende commando uit om de virtuele server te starten:
json-server events.json

Let op: Zorg ervoor dat je bestand events.json niet in je "starter"-folder staat, maar bijvoorbeeld op je bureaublad of een andere locatie. Anders kun je te maken krijgen met een loop.

Veelvoorkomende problemen oplossen
JSON-server installeren
Als de server niet start, controleer dan of json-server correct is geïnstalleerd. Installeer het eventueel opnieuw met:
npm install -g json-server

Controleer daarna de installatie door het versienummer op te vragen:
json-server --version

Problemen met PowerShell oplossen
Als je problemen ondervindt bij het uitvoeren van json-server, probeer dan de volgende stappen:

Open PowerShell als beheerder (rechtsklik en kies "Als administrator uitvoeren").
Voer dit commando uit om de uitvoeringspolicy aan te passen:
Set-ExecutionPolicy RemoteSigned

Bevestig met "Y" en druk op Enter.
Controleer of de policy correct is ingesteld:
Get-ExecutionPolicy

Dit zou "RemoteSigned" moeten teruggeven.
Probeer vervolgens opnieuw de json-server te starten:
json-server --version

Screenshots
Hier zijn enkele screenshots van de applicatie in actie:

Homepagina:

![React1](https://github.com/aelyakoubi/React-Advanced-Project/assets/115151631/3f360556-d80b-4ed9-a47c-7a0016f8b28a)
Server succesvol gestart:

UI Voorbeeld:

![React2](https://github.com/aelyakoubi/React-Advanced-Project/assets/115151631/486e52e1-849f-4d38-adf7-f0824aa334c5)

```Thanks and credits to WincAcademy in Amsterdam, The Netherlands!```
