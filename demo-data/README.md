# Haubro Efterskole – demonstrationsdata

Denne mappe uploades til GitHub ved siden af `index.html` som `demo-data/`.

Plan læser:
- `demo-data/catalog.json`
- separate datasæt i `demo-data/datasets/`
- senere separate elevportrætter i `demo-data/elevbilleder/`

Ingen elevdata, billeder eller øvrige ressourcer er indlejret i appens HTML.
Alle personer og oplysninger er fiktive.

## Dataafledte kontaktgrupper

Plan har ingen hardcodet viden om “Team”, lærerinitialer eller skolens navngivning.
Kolonneoverskrifterne identificerer gruppe- og lærerfelter, og relationerne udledes
af værdier, der optræder sammen i de importerede rækker.

Hvis én lærer kun optræder i én gruppe, kan lærerens initialer entydigt pege på gruppen.
Hvis samme lærer optræder i flere grupper, markeres værdien som tvetydig i stedet for,
at Plan gætter.
