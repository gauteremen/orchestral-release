# Orchestral — Mac-nedlastinger

## [Last ned Orchestral (Mac, Apple Silicon)](https://media.githubusercontent.com/media/gauteremen/orchestral-release/main/Orchestral-mac-arm64.dmg)

Samme lenke etter hver release (~130 MB).

## Viktig: macOS blokkerer første åpning

Orchestral er ikke Apple-signert ennå. **Det er ikke en ødelagt fil.**

1. Åpne DMG → dra **Orchestral** til **Programmer**
2. **Høyreklikk** Orchestral i Programmer → **Åpne** → **Åpne**  
   (Ikke vanlig dobbeltklikk første gang.)
3. Hvis det fortsatt feiler:

```bash
xattr -cr /Applications/Orchestral.app
```

DMG-en inneholder også `INSTALL-mac.txt` med disse stegene.
