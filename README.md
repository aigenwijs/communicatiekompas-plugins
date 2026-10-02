# Communicatiekompas-plugins

Plugins met skills voor communicatieprofessionals bij de Nederlandse overheid, gebouwd op de
openbare vakkennis van [communicatiekompas.nl](https://www.communicatiekompas.nl) en
[communicatierijk.nl](https://www.communicatierijk.nl). Werkt in **Codex / ChatGPT** en in **Claude Code**.

Dit is een onafhankelijk project van [Aigenwijs](https://aigenwijs.com). Het is geen uitgave van de
Rijksoverheid, de Dienst Publiek en Communicatie of het Communicatiekompas.

## Plugins

### `woordvoering` (versie 0.2.0)

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

## Installeren in de Codex-app (ChatGPT)

Open **Instellingen → Plug-ins → Plug-in-marktplaats toevoegen** en vul in:

| Veld | Waarde |
|---|---|
| Bron | `aigenwijs/communicatiekompas-plugins` (of `git@github.com:aigenwijs/communicatiekompas-plugins.git`) |
| Git-referentie | `main` |
| Sparse-paden | leeg laten, of `plugins/woordvoering` voor alleen die plugin |

Daarna verschijnt de marktplaats **communicatiekompas** met de plugins hierboven; klik op *Installeren*.

Via de Codex-CLI:

```bash
codex plugin marketplace add aigenwijs/communicatiekompas-plugins --ref main
```

## Installeren in Claude Code

```
/plugin marketplace add aigenwijs/communicatiekompas-plugins
/plugin install woordvoering@communicatiekompas
```

## Kosten

De plugins zijn gratis en vrij te gebruiken (CC0). Je hebt wel een werkende Codex-, ChatGPT- of
Claude Code-omgeving nodig; daarvoor gelden de voorwaarden en eventuele abonnementskosten van die aanbieder.

## Bronnen en rechten

De teksten in `bronnen/` zijn kopieën van pagina's van communicatiekompas.nl en communicatierijk.nl,
waarvan de tekst onder een CC0-verklaring is gepubliceerd, plus tekstversies van PDF-publicaties
van die sites die hergebruik met bronvermelding toestaan. Elke kopie vermeldt de bron-URL in de
frontmatter. Twee publicaties met een beperkende rechtenvermelding (*Monitor Ontwikkeling
Mediagebruik 2025* en *Moet dat nou zo?!*) zijn **niet** opgenomen; de skills verwijzen voor die
twee naar de downloadlink op de publicatiepagina.

Alles in deze repository (skills, manifesten, README) is vrijgegeven onder
[CC0 1.0 Universal](LICENSE): doe ermee wat je wilt, zonder bronvermelding of toestemming.
Aigenwijs geeft geen garanties; controleer feiten en cijfers altijd in de aangewezen bron.

## Zelf bouwen

Deze repository wordt gegenereerd uit een werkrepository met `scripts/build_release.py`;
wijzigingen graag als issue melden, niet als pull request op de gegenereerde bestanden.
