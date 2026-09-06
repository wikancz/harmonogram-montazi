# Harmonogram montáží – stažení

**Ke stažení: [wikancz.github.io/harmonogram-montazi](https://wikancz.github.io/harmonogram-montazi/)**

Tento repozitář obsahuje **jen hotový instalátor** aplikace Harmonogram montáží, návod
a stránku, ze které se dá stáhnout. Zdrojový kód je v soukromém repozitáři a nezveřejňuje se.

Soubory sem kopíruje workflow „Publish downloads“ ze zdrojového repozitáře, které se po
zveřejnění vydání spouští ručně. Název instalátoru je záměrně bez čísla verze, aby odkaz
`releases/latest/download/Harmonogram-Setup.exe` na stránce platil navždy. Verzi ukazuje
stránka podle vydání.

| Soubor                   | Co to je                                  |
| ------------------------ | ----------------------------------------- |
| `Harmonogram-Setup.exe`  | Windows – instalátor (bez práv správce)   |
| `navod.html`             | návod pro obsluhu k aktuální verzi        |

Instalátor **není digitálně podepsaný**, takže Windows při prvním spuštění varuje. Postup,
jak varování odklikat, je na stránce i v návodu.

## Ikony

`favicon.png` (96 px) a `apple-touch-icon.png` (180 px) jsou zmenšeniny ikony aplikace
(`src-tauri/icons/icon.png` ve zdrojovém repozitáři):

```bash
sips -Z 96 src-tauri/icons/icon.png --out favicon.png
sips -Z 180 src-tauri/icons/icon.png --out apple-touch-icon.png
```

Licence: MIT.
