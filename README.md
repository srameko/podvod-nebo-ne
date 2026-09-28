# Podvod, nebo ne? – simulátor

Interaktivní trenažér k přednášce pro Sněm pacientských organizací LPR (14. 10. 2026).
Jeden soubor `index.html`, žádný build, žádné externí služby, funguje i offline.

Parametr `?velke=1` zapne větší zobrazení pro projektor.
Rozložení funguje na počítači, tabletu i mobilu (na úzkém displeji jsou volby pod telefonem a nalezená varování se ukazují hned u nich).

## Obsah
- Telefonát „z banky“ (větvený scénář s přepisem hovoru, zvukem a volitelným hlasem)
- Reklama na zázračný lék (deepfake, falešný e-shop, loga médií, „právě objednala“, předplatné v drobném písmu)
- Sbírka na nemocné dítě (A/B srovnání, hlasování v sále)
- Rychlé kolo (10 zpráv a hovorů: podvod, nebo ne? – po odpovědi se v telefonu zvýrazní varovná znamení)

Všechny osoby, firmy, čísla a adresy jsou smyšlené. Nic se neodesílá ani neukládá.
Obsah scénářů je v `index.html` v objektech `CALL`, `FB`, `CH` a `QUIZ_CARDS`.
