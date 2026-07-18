# Plan 2.0 · Guides v76

Denne version retter selve leverings- og aktiveringsfejlen:

- Guide-rendereren ligger nu som den sidste kode i `index.html`.
- Ingen senere widgetregistrering kan overskrive den.
- Den aktive tavle genrenderes automatisk, når den nye renderer installeres.
- Guidepakkerne hentes med cache-busting (`?v=76`).
- Den aktive guide viser `v76` nederst, så det kan verificeres på skærmen.
- Der er ikke lavet nye billeder eller skitser.

Efter upload til GitHub skal den allerede åbne Plan-fane genindlæses én gang,
fordi JavaScript i en åben browserfane ikke kan udskiftes af en filupload.
