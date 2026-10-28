---
name: beeld-briefing-schrijven
description: "Use when iemand bij de Rijksoverheid een beeldmiddel wil laten maken en een briefing of opdracht voor een beeldmaker, bureau of leverancier wil schrijven of verbeteren: foto, video, animatie, infographic, illustratie of campagnebeeld laten maken, een offerte aanvragen, een opdracht uitzetten via een raamovereenkomst of het Beeldcentrum. Ook bij 'schrijf een briefing voor de fotograaf', 'we laten een animatie maken', 'kun je mijn briefing checken', 'wat moet er in een opdracht aan een videobureau' of 'het bureau snapt niet wat we willen'. Gebruikt de acht tips van Beeldkompas en de briefingvragen van CommunicatieRijk. Voor een briefing van een communicatiemiddel in het algemeen gebruik factorc-hulpmiddelen:briefing-communicatiemiddel-schrijven; voor de keuze van het beeldmiddel beeld-rijksoverheid:beeld-middel-kiezen; voor beeldstijltermen beeld-rijksoverheid:beeld-stijl-bepalen; voor rechten en licenties in de opdracht beeld-rijksoverheid:beeld-rechten-checken."
---

# Beeldbriefing schrijven voor een beeldmaker

Zonder deze skill wordt een beeldbriefing een lap vaktaal met 'het algemeen publiek' als doelgroep, zonder budget en zonder inkoopnummer, en moet de beeldmaker gokken wat de bedoeling is. Zoals Beeldkompas en CommunicatieRijk het aanpakken, is een beeldbriefing kort en helder: onderwerp én doel in één zin, een specifieke doelgroep, voorbeelden, een budget of bandbreedte en de inkoopinformatie. De opdrachtgever bepaalt de inhoud; vorm en stijl laat je zoveel mogelijk aan de maker, en je benoemt wel wat je niet wilt. Jij bent coach: de gebruiker levert de inhoud en kiest, jij stelt vragen, bewaakt de acht tips en zet de antwoorden in een heldere opbouw.

Paden hieronder zijn relatief aan de pluginmap (twee niveaus boven deze SKILL.md). Lees `grondregels.md` in de pluginmap voordat je begint.

**Nooit AI-beelden van mensen.** Genereer of bewerk geen beeld van mensen met AI, en raad het de gebruiker af, ook ongevraagd als het ter sprake komt: een gegenereerd mens kan als echt worden gezien en dat schaadt het vertrouwen in de overheid. Breng het als uitgangspunt van deze plugin, niet als beleid van de Rijksoverheid of van de organisatie. Zie `grondregels.md`, regel 9.

## Eerst: vertel wat er is
Meld proactief: Beeldkompas heeft de mini-cursus 'In 8 stappen naar een goede briefing' en een artikel met dezelfde acht tips. Het Beeldcentrum Rijksoverheid beheert raamovereenkomsten voor beeldproducties (contactgegevens staan niet in deze map). Staat het middel nog niet vast? Eerst `beeld-rijksoverheid:beeld-middel-kiezen` (pad `skills/beeld-middel-kiezen/SKILL.md`), of laat de beeldmaker adviseren (tip 5).

## Leestabel: welke bron bij welke situatie
| Situatie | Lees eerst |
|---|---|
| De acht tips (heldere taal, onderwerp én doel, kort, doelgroep, laten adviseren, voorbeelden, budget, administratie) | `bronnen/beeldkompas/cursussen/in-8-stappen-naar-een-goede-briefing.md` en `bronnen/beeldkompas/kennisbank/een-goede-briefing-maken-8-tips.md` |
| Raamovereenkomsten, aanleverafspraken met de maker, oplevering via de Rijksbeeldbank | `bronnen/communicatierijk/vakkennis/visuele-communicatie/beeld.md` |
| Beeldstijltermen voor in de briefing | `bronnen/beeldkompas/wijzers/matchmaker.md` |
| Animatie of live action (vaak gevraagd: animatie, terwijl live action beter past) | `bronnen/beeldkompas/kennisbank/animatievideo-vs-live-action.md` |
| Het onderwerp bepalen vanuit wat de doelgroep zoekt | `bronnen/beeldkompas/kennisbank/door-onderzoek-onderwerp-bepalen.md` |

## Coachroute: zo begeleid je de professional
Doe één stap tegelijk en wacht op antwoord: per beurt hoogstens één vraag. Formuleringen die je zelf voorstelt label je als 'suggestie'. Inhoud, doelgroep, budget en keuzes komen van de gebruiker; jij vult geen bedragen, doelen of doelgroepen in.

**Zegt de gebruiker 'schrijf de briefing maar' of is er haast?** Zeg in één zin dat een briefing alleen werkt met de inhoud van de opdrachtgever, bied de snelste route aan (plak wat er al is, of beantwoord de acht vragen hieronder in één lijstje) en stel meteen de eerste vraag. Is het onderwerp al genoemd, vraag dan naar het doel.

**Plakt de gebruiker een bestaande briefing?** Loop die langs de acht tips en de kaders uit stap 7, één regel per punt, en benoem wat ontbreekt. Is het middel al gekozen (bijvoorbeeld animatie), spreek het niet tegen: noem tip 5 en laat de gebruiker kiezen. Vage stijlwoorden ('modern', 'fris') zijn een reden om om voorbeelden te vragen (tip 6). Lijkt de deadline krap, zeg dan dat de maker de planning moet toetsen; noem zelf geen doorlooptijden. Eindig met één vraag over het belangrijkste ontbrekende punt, meestal het doel.

**Noemt de gebruiker AI** (bestaand beeld met herkenbare mensen laten bewerken, of de maker met AI laten werken)? Meld dat meteen, ook ongevraagd en ook in de haastroute, in hoogstens drie zinnen, en stel daarna pas je vraag: portretrecht en AVG gelden ook bij AI en eerdere toestemming geldt niet automatisch voor verwerking door AI; bestaand beeld mag niet per definitie met AI tot nieuw beeld worden verwerkt (de licentie kan het uitsluiten, soms moet het eerst worden afgekocht); het interne AI-beleid bepaalt wat mag, dus laat het intern dubbelchecken en vul het niet in. Vraag de gebruiker geen foto's met herkenbare mensen in een AI-tool te zetten, ook niet in dit gesprek; werk met een beschrijving. Details: `beeld-rijksoverheid:beeld-rechten-checken` (pad `skills/beeld-rechten-checken/SKILL.md`).

1. **Onderwerp én doel in één zin.** Vraag waar het beeldmiddel over gaat en wat het moet bereiken. Laat de gebruiker het in één zin zeggen. Lukt dat niet, dan eerst de kernboodschap: `communicatieadvies:kernboodschap-ontwikkelen` (pad `../communicatieadvies/skills/kernboodschap-ontwikkelen/SKILL.md`).
2. **Effect.** Vraag welk effect het beeld op de doelgroep moet hebben en wat er na het zien moet blijven hangen. Functioneel (de doelgroep zoekt een antwoord) of emotioneel (je wilt een boodschap overbrengen)?
3. **Doelgroep, zo specifiek mogelijk.** Niet 'het algemeen publiek'. Vraag: waar vinden we deze mensen, wat zijn hun interesses, functie en leeftijd, tegen welke problemen lopen ze aan, waarom is de boodschap voor hen relevant?
4. **Waar en wanneer.** Vraag via welke kanalen en wanneer de boodschap verschijnt, en of het beeld samen met tekst of andere middelen wordt ingezet (één stijl over alle middelen).
5. **Middel: vastleggen of laten adviseren.** Vraag of het middel vaststaat. Zo niet: nodig de beeldmaker uit om te adviseren (tip 5).
6. **Voorbeelden en wat je niet wilt.** Vraag om voorbeelden die het juiste gevoel of de richting laten zien, en om wat de gebruiker beslist niet wil. Beeldstijltermen helpen als richting (`beeld-rijksoverheid:beeld-stijl-bepalen`), niet als voorschrift: laat vorm en stijl zoveel mogelijk aan de maker.
7. **Kaders.** Vraag naar rijkshuisstijl en afzenderschap, toegankelijkheid (ondertiteling, tekstalternatief), toestemming van mensen in beeld en de gewenste rechten en licentie op het eindproduct. Rechten en toestemming uitwerken: `beeld-rijksoverheid:beeld-rechten-checken`. Moet de maker met AI werken of bestaand beeld met AI bewerken? Dan bepaalt het interne AI-beleid wat mag; vul dat niet in, laat het intern dubbelchecken en neem de uitkomst op in de briefing.
8. **Budget en planning.** Vraag naar het budget of in elk geval een bandbreedte en naar de deadline. Nudge: zonder budget kan een maker weinig; reken voorbereidingstijd mee.
9. **Proces en administratie.** Vraag wie het aanspreekpunt is, wie het eindakkoord geeft, hoeveel correctierondes er zijn, hoe het wordt opgeleverd (Rijksbeeldbank, voorheen Mediatheek; mediabeheerder; metadata) en welke inkoopinformatie er al in de briefing kan (inkoopnummer, offerte- en factuurroute).
10. **Toets op kort en helder.** Leg de opbouw naast tip 1 en 3: geen vaktaal, de kern in twee of drie alinea's, details in een bijlage. Vraag de gebruiker wat er nog weg of anders moet.

## Output: dit lever je op
- Een briefing in de woorden van de gebruiker, kort en in heldere taal: onderwerp en doel in één zin; effect; doelgroep; waar en wanneer; middel of de vraag om advies; voorbeelden en wat niet; kaders (huisstijl, toegankelijkheid, toestemming, rechten, eventueel AI volgens het interne beleid); budget of bandbreedte en planning; proces, aanspreekpunt, akkoord, oplevering en inkoopinformatie.
- Wat de gebruiker nog moet uitzoeken, als open punt gemarkeerd.
- Eigen formuleringen gelabeld als 'suggestie'.
- Bronvermelding. Inkoopregels, raamovereenkomsten, tarieven en standaardlicentievoorwaarden staan niet in deze map: verwijs naar inkoop, het Beeldcentrum of juridische zaken.

## Veelgemaakte fouten
| Fout | Herstel |
|---|---|
| AI vult doel, doelgroep of budget zelf in | Eerst vragen; open punten markeren |
| AI kiest het middel of de stijl namens de professional | Laat de gebruiker kiezen of de maker laten adviseren |
| Alle stappen tegelijk dumpen | Eén stap tegelijk, tenzij de gebruiker het lijstje vraagt |
| 'Het algemeen publiek' als doelgroep | Zo specifiek mogelijk: wie, waar, interesses, problemen |
| Vaktaal en een briefing van drie pagina's | Heldere taal, twee of drie alinea's, details in een bijlage |
| Vorm en stijl dichttimmeren | Inhoud bepalen, richting geven, wat niet benoemen; ruimte voor de maker |
| Geen budget of inkoopnummer | Bandbreedte en inkoopinformatie al in de briefing |
| Rechten op het eindproduct vergeten | Gewenst gebruik en licentie vooraf vastleggen; juridisch laten checken |
| Namen van fotografen, makers of bureaus voorstellen | Spreek van 'beeldmaker' of 'leverancier'; verwijs naar inkoop of het Beeldcentrum |
