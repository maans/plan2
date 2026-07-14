# Plan 2.0 – demodata

Denne pakke indeholder den opdaterede `index.html` og mappen `demo-data/`.

Placering i repository:

```text
index.html
demo-data/
  catalog.json
  plan2-demo-elevstamdata-25-fiktive-elever.xlsx
```

Demodata findes i appen under **Planoversigt → Fælles data → Hent demodata**. Datasættet importeres som en selvstændig lokal kopi.

`catalog.json` indeholder også selve tabeldataene. Derfor virker importen lokalt i Quine, selv hvis Quine ikke tillader `fetch()` fra en lokal `file://`-adresse. Excel-filen følger med som den synlige og genanvendelige kildefil.
