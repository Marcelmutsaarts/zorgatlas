# Zorgatlas

Leeromgeving voor de bachelor verpleegkunde. Proof of concept.

- `index.html`: de campus. Elf leeromgevingen op een plattegrond, verdeeld over vier leerlijnen (klinisch handelen, communicatie en relatie, organisatie en kwaliteit, professionaliteit en onderzoek).
- `nachtdienst.html`: **Nachtdienst**, een 3D-verpleegafdeling met zes patiënten.

## Nachtdienst

Je bent de verpleegkundige van 23:00 tot 03:00. Je leest de overdracht en kiest per patiënt wat je doet: observeren, vitale parameters meten, glycemie prikken, naar het toilet begeleiden, de arts bellen, enzovoort. Elke handeling kost tijd, en je kunt maar op één plek tegelijk zijn.

- **Fatima** (pyelonefritis) glijdt stil weg in een sepsis. Ze belt niet.
- **Luc** (diabetes, insuline, half gegeten) raakt in een hypoglykemie die de EWS nauwelijks laat zien.
- **Jan** (COPD) wordt benauwd en angstig. Meer zuurstof leidt tot CO₂-stapeling.
- **Maria** (heupprothese) belt voor het toilet. Wacht je te lang, dan valt ze.
- **Anna** vraagt om pijnstilling, **Kevin** heeft neurocontroles om 01:00 en 03:00.

Leerelementen:

1. **Leermodus**: na elke meting bereken je zelf de early warning score (NEWS2) en kies je de vervolgactie.
2. **SBAR**: je belt de arts door per stap de beste zin te kiezen. Hoe beter je verhaal, hoe sneller de arts komt.
3. **Dienstrapport**: de werkelijke EWS van elke patiënt naast jouw metingen, de uitkomst per patiënt en scores voor vroegsignalering, prioriteren, communicatie en klinisch redeneren.
4. **Reflectie** volgens Korthagen, vertrekkend uit het logboek van de eigen dienst.
5. Zeven uitlegonderwerpen (uitleg, in deze dienst, rekenen, denkvraag) en zeven opdrachten volgens RTTI.

Het is een leermodel. Klinische verlopen, tijden en drempels zijn vereenvoudigd. Laat de inhoud nakijken door een vakdocent verpleegkunde en stem af op de protocollen van de eigen stageziekenhuizen.

## Techniek

Statische HTML zonder build-stap. 3D met three.js r147 via jsDelivr. Geen cookies, geen accounts, niets opgeslagen.
