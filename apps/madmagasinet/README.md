# Madmagasinet

> Projektspecifik ramme for indhold, SEO, GEO og AI-understøttet arbejde på Madmagasinet.dk.

Denne mappe er første praktiske afprøvning af Reberholt OS. Den samler kun regler og beslutninger, som er særlige for Madmagasinet. Tværgående principper og standarder vedligeholdes fortsat i repositoryets `docs/`-mappe.

## Projektidentitet

| Felt | Værdi |
| --- | --- |
| **Projekt** | Madmagasinet |
| **Website** | [madmagasinet.dk](https://www.madmagasinet.dk/) |
| **Ejer** | Thomas Reberholt |
| **Status** | Pilotprojekt i Reberholt OS |
| **Primært sprog** | Dansk |
| **Offentlig beskrivelse** | Online madmagasin med opskrifter, anmeldelser, artikler, tips, trends samt gear og gadgets |

Projektbeskrivelsen er kontrolleret mod Madmagasinets offentlige [om-side](https://www.madmagasinet.dk/om-madmagasinet) den 19. juli 2026. Interne mål, systemadgange og kommercielle oplysninger skal dokumenteres særskilt, når de er godkendt; de må ikke udledes af offentligt indhold.

## Formål

Madmagasinet skal bruge Reberholt OS til at:

- skabe mere ensartet og troværdigt redaktionelt indhold
- forbedre eksisterende indhold før unødvendig nyproduktion
- gøre artikler lettere at finde, forstå, citere og vedligeholde
- dokumentere beslutninger og kontroller tæt på projektet
- afprøve fælles standarder i et rigtigt publiceringsflow

## Gældende fælles dokumenter

Arbejdet følger altid de senest godkendte versioner af:

1. [`README.md`](../../README.md) — repositoryets arbejdsmodel
2. [`docs/001_Vision.md`](../../docs/001_Vision.md) — retning og succeskriterier
3. [`docs/002_Principper.md`](../../docs/002_Principper.md) — tværgående principper
4. [`docs/003_AI_Workflow.md`](../../docs/003_AI_Workflow.md) — AI, kontrol og ansvar
5. [`docs/004_Artikelstandard.md`](../../docs/004_Artikelstandard.md) — redaktionel kvalitet
6. [`docs/005_SEO_GEO.md`](../../docs/005_SEO_GEO.md) — søgning, citérbarhed og måling

Ved konflikt gælder den mest specifikke godkendte regel. En projektspecifik afvigelse skal stå i denne mappe, have en begrundelse, en ejer og en dato for revurdering.

## Indholdstyper

Den første projektmodel omfatter:

- opskrifter
- anmeldelser af restauranter, produkter og oplevelser
- redaktionelle artikler og guides
- tips og trends
- gear og gadgets
- tema- og sæsonindhold

Nye indholdstyper tilføjes først, når de har et konkret formål, en ansvarlig og et defineret kvalitetsniveau.

## Projektspecifikke redaktionelle krav

### Opskrifter

En opskrift skal som minimum have:

- tydelig titel og kort introduktion
- antal portioner eller anden entydig mængde
- ingredienser med brugbare mål
- trinvis fremgangsmåde i logisk rækkefølge
- relevante tider, temperaturer og nødvendigt udstyr
- kendte allergener eller sikkerhedsforhold, når de er relevante
- originale erfaringer, variationer eller serveringsforslag, når de findes

Opskriften skal være praktisk gennemførlig. AI må ikke opfinde afprøvning, smagsoplevelser eller resultater.

### Anmeldelser

En anmeldelse skal:

- have en navngiven afsender
- gøre vurderingsgrundlaget tydeligt
- oplyse dato eller relevant periode for oplevelsen
- skelne mellem observerbare forhold og skribentens vurdering
- oplyse væsentlige kommercielle relationer, invitationer eller modtagne produkter
- bruge Madmagasinets godkendte karakterskala konsekvent, hvis der gives karakter

### Sundhed, ernæring og fødevaresikkerhed

Indhold med sundheds-, ernærings- eller fødevaresikkerhedspåstande kræver skærpet kontrol:

- brug aktuelle og autoritative kilder
- angiv kilde og kontroltidspunkt ved væsentlige påstande
- adskil generel information fra individuel rådgivning
- undgå diagnose, behandling eller løfter om helbredseffekt
- få menneskelig faglig kontrol, når fejlinformation kan skade læseren

### Kommercielt indhold

Annoncer, sponsoreret indhold, affiliate-links, produktprøver og andre væsentlige relationer skal mærkes tydeligt efter gældende regler og Madmagasinets godkendte praksis. Redaktionelle vurderinger må ikke fremstilles som uafhængige, hvis en relation kan påvirke læserens opfattelse.

## SEO og GEO for Madmagasinet

Hver prioriteret side skal:

- løse et tydeligt læserbehov frem for blot at ramme et søgeord
- have en entydig hovedvinkel og undgå unødigt overlap med eksisterende sider
- vise erfaring, afsender, dato og kilder, hvor det styrker tilliden
- give det centrale svar tidligt og uddybe det i en logisk struktur
- bruge relevante interne links med beskrivende ankertekst
- anvende strukturerede data, når de matcher det synlige indhold
- have billeder med dokumenteret brugsret, meningsfuldt filnavn og relevant alternativ tekst
- kunne opdateres, konsolideres eller afpubliceres på baggrund af dokumenteret værdi

Opskrifts- og anmeldelsesmarkup må kun bruges, når siden opfylder platformens aktuelle krav og de markerede oplysninger er synlige for læseren.

## Arbejdsgang for pilotopgaven

Den første opgave skal være en kontrolleret forbedring af én eksisterende side, ikke en masseproduktion.

1. Vælg en side med et tydeligt læser- eller forretningsbehov.
2. Registrér nuværende URL, indholdstype, ejer og kendte resultater.
3. Kortlæg søgeintention, eksisterende overlap, kilder og nødvendige kontroller.
4. Definér acceptkriterier før redigering.
5. Udarbejd ændringen efter artikel-, AI- og SEO/GEO-standarderne.
6. Gennemfør faktakontrol, redaktionel kontrol og teknisk kontrol.
7. Få nødvendig menneskelig godkendelse før publicering.
8. Registrér publiceringsdato og måleplan.
9. Evaluer resultat og læring på en aftalt dato.
10. Flyt kun generel læring til fælles standarder efter bevidst godkendelse.

## Definition of Done

En Madmagasinet-opgave er først færdig, når:

- [ ] mål, målgruppe, sideejer og acceptkriterier er dokumenteret
- [ ] relevante fælles standarder er fulgt
- [ ] fakta, citater, billeder og rettigheder er kontrolleret
- [ ] kommercielle relationer er oplyst korrekt
- [ ] sundheds- og sikkerhedspåstande har passende kilder og kontrol
- [ ] titel, introduktion, struktur, metadata og interne links er gennemgået
- [ ] eventuelle strukturerede data matcher det synlige indhold
- [ ] AI-bidrag er menneskeligt vurderet efter opgavens risiko
- [ ] forhåndsvisning eller publiceret side er teknisk kontrolleret
- [ ] måling, evalueringsdato og ansvarlig er registreret
- [ ] følsomme oplysninger og adgangsdata er udeladt fra repositoryet

## Mappestruktur

Strukturen udvides kun, når et konkret dokument kræver det:

```text
apps/madmagasinet/
├── README.md             # Projektets godkendte ramme
├── decisions/            # Varige projektspecifikke beslutninger
├── content/              # Briefs og godkendt arbejdsdokumentation
└── audits/               # Afgrænsede SEO-, indholds- og kvalitetsaudits
```

Mapper uden godkendt indhold oprettes ikke. Kladder, eksporter, persondata, adgangsoplysninger og rå analyser hører kun hjemme her, hvis repositoryet er et godkendt og sikkert opbevaringssted for materialet.

## Åbne beslutninger

Før pilotopgaven kan publiceres, skal følgende fastlægges:

- projektets vigtigste forretningsmål og primære konverteringer
- prioriterede målgrupper og indholdsområder
- ansvarlig redaktør og godkendelsesflow
- godkendte kilder for ernæring, sundhed og fødevaresikkerhed
- praksis for sponsoreret indhold, affiliate-links og produktprøver
- måleværktøjer, baseline og evalueringsperiode
- den endelige målemetode og de numeriske succeskriterier for Pandasia-piloten

Uklarhederne er bevidste kontrolpunkter. De må ikke udfyldes med AI-antagelser.

---

**Status:** Første projektspecifikke struktur i brug

**Ejer:** Thomas Reberholt

**Næste trin:** Udfyld baseline og kommerciel afklaring i [`content/001_Pandasia_pilotbrief.md`](content/001_Pandasia_pilotbrief.md).
