# Reberholt OS

> Et fælles operativsystem for Reberholts virksomheder, digitale produkter og AI-drevne arbejdsgange.

Reberholt OS samler den viden, de principper og de standarder, som ligger bag Reberholts websites, indhold, design, SEO, automatisering og tekniske drift. Formålet er at gøre arbejdet ensartet, genbrugeligt og nemt at videreudvikle på tværs af mennesker, projekter og AI-værktøjer.

Dette repository er projektets fælles referencepunkt. Når instruktioner, prompts eller tidligere samtaler er uenige med indholdet her, er den senest godkendte version i GitHub gældende.

## Hvorfor Reberholt OS findes

Reberholt OS skal gøre det muligt at:

- omsætte idéer til driftssikre løsninger med en tydelig proces
- genbruge viden og standarder på tværs af virksomheder og websites
- give AI-værktøjer en fælles kontekst og klare kvalitetskrav
- dokumentere beslutninger, så vigtig viden ikke kun findes i chats eller hos én person
- skalere indhold, SEO, design og automatisering uden at miste kvalitet eller retning

## Sådan fordeles rollerne

| Rolle | Ansvar |
| --- | --- |
| **GitHub** | Er den fælles sandhed og opbevarer godkendte standarder, beslutninger og systemer. |
| **ChatGPT** | Arbejder som arkitekt: skaber struktur, udfordrer antagelser og holder overblik over helheden. |
| **Claude** | Arbejder som forfatter: producerer og redigerer indhold inden for de vedtagne rammer. |
| **Thomas Reberholt** | Er produktchef: fastlægger retning, prioriterer arbejdet og godkender væsentlige beslutninger. |

Rollerne beskriver den primære arbejdsdeling. Et værktøj må gerne løse flere typer opgaver, men det skal altid følge de gældende standarder i dette repository.

## Hvad systemet omfatter

Reberholt OS er ikke kun et publiceringssystem. Det er den fælles ramme for:

- AI og prompts
- websites og digitale produkter
- redaktionelt indhold
- SEO og generativ søgning
- design og brands
- arbejdsgange og kvalitetssikring
- automatisering og n8n
- servere, drift og dokumentation
- Reberholts virksomheder og projekter

## Arbejdsprincipper

1. **Repositoryet kommer først.** En vigtig beslutning er ikke færdig, før den er dokumenteret det rigtige sted.
2. **Én tydelig kilde pr. regel.** Vi undgår parallelle dokumenter med forskellige versioner af den samme sandhed.
3. **Mennesket ejer retningen.** AI kan foreslå, analysere og producere, men væsentlige produkt- og forretningsbeslutninger godkendes af produktchefen.
4. **Kvalitet før volumen.** En gennemarbejdet standard er mere værd end mange ufærdige filer.
5. **Små, kontrollerbare ændringer.** Arbejde opdeles, så det kan gennemgås, testes og rulles tilbage.
6. **Genbrug før nyopfindelse.** Fælles metoder placeres i kernen; projektspecifikke undtagelser placeres ved projektet.
7. **Sikkerhed og privatliv er standard.** Hemmeligheder, persondata og adgangsoplysninger må aldrig gemmes direkte i repositoryet.

## Sådan bruges Reberholt OS

Før en ny opgave påbegyndes:

1. Læs denne README og de dokumenter, som er relevante for opgaven.
2. Afklar hvilket projekt og hvilket forretningsmål opgaven understøtter.
3. Find den gældende standard i `core/` eller `docs/`.
4. Beskriv den ønskede ændring og de kriterier, der afgør, om den er færdig.
5. Udfør arbejdet i en lille, afgrænset ændring.
6. Kontrollér resultatet og opdatér dokumentationen, hvis en regel eller beslutning er ændret.

AI-værktøjer skal starte med repositoryets dokumentation og må ikke behandle tidligere chats som en mere autoritativ kilde. Hvis dokumentationen mangler eller er modstridende, skal uklarheden beskrives i stedet for at blive skjult bag en antagelse.

## Planlagt struktur

Strukturen udvides først, når der er konkret indhold til den:

```text
reberholt-os/
├── README.md
├── docs/                 # Vision, principper og tværgående dokumentation
├── core/                 # Fælles standarder for AI, SEO, design og workflow
└── apps/                 # Projektspecifik viden og løsninger
    ├── madmagasinet/
    ├── tex-tryk/
    ├── refleksvesten/
    └── akvaponik/
```

De første planlagte dokumenter er:

```text
docs/
├── 001_Vision.md
├── 002_Principper.md
├── 003_AI_Workflow.md
├── 004_Artikelstandard.md
└── 005_SEO_GEO.md
```

Mapperne og dokumenterne oprettes gradvist. Tom struktur skaber ikke værdi; hvert nyt dokument skal løse et konkret behov og have en tydelig ejer.

## Beslutninger og ændringer

En ændring bør kunne besvare fire spørgsmål:

- Hvilket problem løser den?
- Hvilke projekter eller arbejdsgange påvirker den?
- Hvordan er resultatet kontrolleret?
- Kræver den opdatering af en eksisterende standard?

Større ændringer gennemgås og godkendes før de bliver en del af hovedgrenen. Følsomme oplysninger placeres i godkendte secret- eller adgangssystemer, aldrig i commits, issues eller dokumentationsfiler.

## Roadmap

- [x] Etablér Reberholt OS som fælles koncept
- [x] Definér repositoryets formål og arbejdsmodel
- [x] Godkend vision og principper
- [x] Dokumentér AI-workflowet
- [x] Definér artikelstandarden
- [x] Definér SEO- og GEO-standarden
- [x] Etablér den første projektspecifikke app-struktur
- [ ] Gennemfør den første målbare Madmagasinet-pilot

## Status

Reberholt OS er i praktisk afprøvning. Fundamentet og de første fælles standarder er etableret; næste milepæl er at forbedre én eksisterende Madmagasinet-side fra brief til målt resultat.

---

**Ejer:** Thomas Reberholt  
**Repository:** Reberholt OS  
**Primært sprog:** Dansk
