# Podvod, nebo ne? – simulátor

Interaktivní trenažér k přednášce pro Sněm pacientských organizací LPR (14. 10. 2026).
Jeden soubor `index.html`, žádný build, žádné externí služby, funguje i offline.

## Nasazení na GitHub Pages
1. Vytvořte repozitář a nahrajte `index.html`, `.nojekyll` a `README.md`.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
3. Adresa: `https://<uživatel>.github.io/<repozitář>/` (pro sál stačí QR kód).

Parametr `?velke=1` zapne větší zobrazení pro projektor.

## Obsah
- Telefonát „z banky“ (větvený scénář s titulky, zvukem a volitelným hlasem)
- Reklama na zázračný lék (deepfake, falešný obchod, předplatné v drobném písmu)
- Sbírka na nemocné dítě (A/B srovnání, hlasování v sále)
- Rychlé kolo (8 zpráv: podvod, nebo ne?)

Všechny osoby, firmy, čísla a adresy jsou smyšlené. Nic se neodesílá ani neukládá.
Obsah scénářů je v `index.html` v objektech `CALL`, `FB`, `CH` a `QUIZ_CARDS`.
