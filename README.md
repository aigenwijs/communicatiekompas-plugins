# Communicatiekompas-plugins

Plugins met skills voor communicatieprofessionals bij de Nederlandse overheid, gebouwd op de
openbare vakkennis van [communicatiekompas.nl](https://www.communicatiekompas.nl) en
[communicatierijk.nl](https://www.communicatierijk.nl). Werkt in **Codex / ChatGPT** en in **Claude Code**.

Dit is een onafhankelijk project van [Aigenwijs](https://aigenwijs.com). Het is geen uitgave van de
Rijksoverheid, de Dienst Publiek en Communicatie of het Communicatiekompas.

## Plugins

### Woordvoering bij de Rijksoverheid (`woordvoering`, versie 0.2.2)

Woordvoering zoals de Rijksoverheid het afspreekt: dilemmalogica, kernboodschap (kijk-want-dus), uitgangspunten overheidscommunicatie en persreacties, gebaseerd op communicatiekompas.nl en communicatierijk.nl.

Skills:

- `bewindspersoon-in-de-media`: Bewindspersoon in de media
- `crisiscommunicatie`: Crisiscommunicatie
- `dilemmalogica-toepassen`: Dilemmalogica toepassen
- `mediabereik-en-media-analyse`: Mediabereik en media-analyse
- `persregels-checken`: Persregels checken
- `persvraag-beantwoorden`: Persvraag beantwoorden
- `reageren-op-kritiek-en-frames`: Reageren op kritiek en frames

Elke skill bevat een leestabel die verwijst naar de meegeleverde bronteksten in `bronnen/`.
De agent leest die teksten bij gebruik; de skill geeft werkwijze, output en veelgemaakte fouten.

### Communicatieadvies bij de Rijksoverheid (`communicatieadvies`, versie 0.1.1)

Communicatieadvies zoals de Rijksoverheid het afspreekt (Factor C): intake en debriefing, omgevingsanalyse, publieksonderzoek, communicatiestrategie, kernboodschap, communicatieplan, evaluatie en verantwoording, en de adviesrol in een politiek-bestuurlijke omgeving, gebaseerd op communicatiekompas.nl en communicatierijk.nl.

Skills:

- `communicatieadvies-geven`: Communicatieadvies geven
- `communicatieplan-schrijven`: Communicatieplan schrijven
- `communicatiestrategie-bepalen`: Communicatiestrategie bepalen
- `evaluatie-en-verantwoording`: Evaluatie en verantwoording
- `intake-en-debriefing`: Intake en debriefing
- `kernboodschap-ontwikkelen`: Kernboodschap ontwikkelen
- `omgevingsanalyse-maken`: Omgevingsanalyse maken
- `publieksonderzoek-opzetten`: Publieksonderzoek opzetten

Elke skill bevat een leestabel die verwijst naar de meegeleverde bronteksten in `bronnen/`.
De agent leest die teksten bij gebruik; de skill geeft werkwijze, output en veelgemaakte fouten.

### Schrijven bij de Rijksoverheid (`schrijven-rijksoverheid`, versie 0.2.0)

Schrijven zoals de Rijksoverheid het afspreekt (Taalkompas): tekst opzetten en structureren, begrijpelijke taal op B1, burgerbrief, Kamerbrief, beslisnota, inclusief schrijven, eenvoudige taal op A2 en teksten testen bij lezers, gebaseerd op communicatierijk.nl en communicatiekompas.nl.

Skills:

- `a2-eenvoudig-schrijven`: Eenvoudig schrijven op A2
- `b1-begrijpelijk-schrijven`: Begrijpelijk schrijven op B1
- `beslisnota-schrijven`: Beslisnota schrijven
- `burgerbrief-schrijven`: Burgerbrief schrijven
- `inclusief-schrijven`: Inclusief schrijven
- `kamerbrief-schrijven`: Kamerbrief schrijven
- `tekst-opzetten-en-structureren`: Tekst opzetten en structureren
- `tekst-testen-en-controleren`: Tekst testen en controleren

Elke skill bevat een leestabel die verwijst naar de meegeleverde bronteksten in `bronnen/`.
De agent leest die teksten bij gebruik; de skill geeft werkwijze, output en veelgemaakte fouten.

### Factor C-hulpmiddelen bij de Rijksoverheid (`factorc-hulpmiddelen`, versie 0.1.0)

De hulpmiddelen van Factor C, de werkwijze voor communicatie van de Rijksoverheid, als losse skills: per tool van communicatiekompas.nl/hulpmiddelen (intake, debriefing, SWOT, actoren-inventarisatie, omgevingsscan, belangen- en vertrouwenmatrix, macht- en invloedanalyse, ringen van invloed, beweegredenen-matrix, persona, klantreis, communicatiestrategie, framing, CASI, communicatieplan, kijk-want-dus, message box, message house, kritiek-repliek, dilemmalogica, teksten, middelenkeuze, briefing, evenementen, communicatiekalender, media-analyse) een eigen skill, plus een skill die per fase het passende hulpmiddel kiest.

Skills:

- `actoren-inventariseren`: Actoren-inventarisatie
- `belangen-en-vertrouwenmatrix-invullen`: Belangen- en vertrouwenmatrix
- `beweegredenen-matrix-invullen`: Beweegredenen-matrix
- `briefing-communicatiemiddel-schrijven`: Briefing communicatiemiddelen
- `casi-toepassen`: CASI
- `communicatiekalender-maken`: Communicatiekalender
- `communicatieplan-opbouwen`: Bouwstenen van een communicatieplan
- `communicatiestrategie-uitwerken`: Communicatiestrategie
- `debriefing-maken`: Debriefing
- `dilemmalogica-doorlopen`: Dilemmalogica
- `evenement-organiseren`: Evenementen en congressen
- `factor-c-hulpmiddel-kiezen`: Factor C-hulpmiddel kiezen
- `framing-toepassen`: Framing
- `intake-voeren`: Intake (checklist)
- `interdisciplinair-werken`: Interdisciplinair werken
- `kijk-want-dus-formuleren`: Kijk-want-dus
- `klantreis-maken`: Klantreis
- `kritiek-repliek-maken`: Kritiek-repliek
- `macht-en-invloedanalyse-maken`: Macht- en invloedanalyse
- `media-analyse-uitvoeren`: Media-analyse en omgevingsonderzoek
- `message-box-invullen`: Message box
- `message-house-bouwen`: Message house
- `middelenkeuze-maken`: Middelenkeuze
- `netwerkanalyse-sociogram-maken`: Netwerkanalyse of sociogram
- `omgevingsscan-maken`: Omgevingsscan
- `persona-maken`: Persona's
- `projectorganisatie-inrichten`: Inrichten projectorganisatie
- `ringen-van-invloed-tekenen`: Ringen van invloed
- `swot-analyse-maken`: SWOT-analyse
- `teksten-schrijven`: Teksten schrijven

Elke skill bevat een leestabel die verwijst naar de meegeleverde bronteksten in `bronnen/`.
De agent leest die teksten bij gebruik; de skill geeft werkwijze, output en veelgemaakte fouten.

In Claude Code meldt deze plugin bij de start van elke sessie (SessionStart-hook) welke
hulpmiddelen er zijn, zodat de assistent ze uit zichzelf kan aanbieden. De hook voert alleen
een `echo` uit en verstuurt niets.

## Installeren in de Codex-app (ChatGPT)

Open **Instellingen → Plug-ins → Plug-in-marktplaats toevoegen** en vul in:

| Veld | Waarde |
|---|---|
| Bron | `aigenwijs/communicatiekompas-plugins` (of `git@github.com:aigenwijs/communicatiekompas-plugins.git`) |
| Git-referentie | `main` |
| Sparse-paden | leeg laten, of `plugins/<naam>` (bijvoorbeeld `plugins/woordvoering`) voor alleen die plugin |

Daarna verschijnt de marktplaats **communicatiekompas** met de plugins hierboven; klik op *Installeren*.

Via de Codex-CLI:

```bash
codex plugin marketplace add aigenwijs/communicatiekompas-plugins --ref main
```

## Installeren in Claude Code

```
/plugin marketplace add aigenwijs/communicatiekompas-plugins
/plugin install woordvoering@communicatiekompas
/plugin install communicatieadvies@communicatiekompas
/plugin install schrijven-rijksoverheid@communicatiekompas
/plugin install factorc-hulpmiddelen@communicatiekompas
```

## Kosten

De plugins zijn gratis en vrij te gebruiken (CC0). Je hebt wel een werkende Codex-, ChatGPT- of
Claude Code-omgeving nodig; daarvoor gelden de voorwaarden en eventuele abonnementskosten van die aanbieder.

## Bronnen en rechten

De teksten in `bronnen/` zijn kopieën van pagina's van communicatiekompas.nl en communicatierijk.nl,
waarvan de tekst onder een CC0-verklaring is gepubliceerd, plus tekstversies van PDF-publicaties
van die sites die hergebruik met bronvermelding toestaan. Elke kopie vermeldt de bron-URL in de
frontmatter. Vier publicaties met een beperkende rechtenvermelding (*Monitor Ontwikkeling
Mediagebruik 2025*, *Moet dat nou zo?!*, *Leidraad Communicatieonderzoek 2017* en *Blijf bevragen*)
zijn **niet** opgenomen; de meegeleverde paginateksten noemen ze wel, met de bron-URL in de frontmatter.

De plugin `factorc-hulpmiddelen` bevat naast de tekstversies ook de originele PDF's (blanco
invulformulieren en CASI-publicaties). **Uitzondering op CC0:** de *Handleiding CASI*
(`plugins/factorc-hulpmiddelen/bronnen/communicatierijk/documenten/handleiding-casi/`) valt niet onder CC0.
Volgens het colofon mogen delen ervan met vermelding van auteur en bron worden gebruikt voor
niet-commerciële doeleinden; voor ander gebruik is toestemming nodig van de Dienst Publiek en
Communicatie (Ministerie van Algemene Zaken). Zie `bronnen/OVERZICHT.md` in die plugin.

Alles in deze repository (skills, manifesten, README) is, met uitzondering van de hierboven genoemde
Handleiding CASI, vrijgegeven onder
[CC0 1.0 Universal](LICENSE): doe ermee wat je wilt, zonder bronvermelding of toestemming.
Aigenwijs geeft geen garanties; controleer feiten en cijfers altijd in de aangewezen bron.

## Zelf bouwen

Deze repository wordt gegenereerd uit een werkrepository met `scripts/build_release.py`;
wijzigingen graag als issue melden, niet als pull request op de gegenereerde bestanden.
