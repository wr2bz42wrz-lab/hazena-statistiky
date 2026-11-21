HBC Jičín – statistiky (samostatná PWA)
=====================================

Tento balíček je stejná aplikace jako artefakt na claude.ai, ale jako instalovatelná
PWA, která funguje i offline. Data se v ní ukládají do prohlížeče daného zařízení
(localStorage) – nesdílí se s verzí na claude.ai ani mezi zařízeními.
Přenos dat: Tým a sezóny → Stáhnout zálohu (JSON) → na druhém místě Obnovit ze zálohy.

Jak ji zprovoznit (zdarma, cca 5 minut):
1. Nahrajte obsah této složky na libovolný HTTPS hosting, např.
   - GitHub Pages (nový repozitář → nahrát soubory → Settings → Pages), nebo
   - Netlify Drop (app.netlify.com/drop – stačí přetáhnout složku).
2. Otevřete adresu:
   - iPhone/iPad: Safari → Sdílet → Přidat na plochu
   - Mac/Windows (Chrome/Edge): ikona instalace v adresním řádku
3. Po prvním otevření funguje aplikace i bez internetu. Export do PDF potřebuje
   při prvním použití připojení (stahuje se knihovna pro PDF).

Soubory: index.html (celá aplikace), manifest.webmanifest, sw.js (offline režim), ikony.
