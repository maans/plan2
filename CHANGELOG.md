# Plan 2.0 · Guides v78

## Rettelser

- Guides skifter nu direkte til præsentationstilstand, når guidesessionen indlæses.
- Præsentation aktiveres ikke længere kun fra widgettens `mount`.
- **Slet guiden** bruger nu en direkte slettearbejdsgang:
  1. Plan finder det aktuelle forløb.
  2. Plan skifter til et andet forløb eller opretter et tomt forløb.
  3. Alle guidens sessioner, tavler, widgets og lokale datasæt slettes.
- Sletningen afhænger ikke længere af Lager og oprydnings beskyttelse mod sletning af det aktive forløb.
- Guidens footer viser `v78`, så den aktive kode kan kontrolleres.
