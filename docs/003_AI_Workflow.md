# AI-workflow for Reberholt OS

> Workflowet gør samarbejdet mellem produktchefen, ChatGPT, Claude og GitHub tydeligt, kontrollerbart og genbrugeligt.

## Formål

Dette dokument beskriver standardprocessen for opgaver, hvor AI indgår i arbejdet. Processen skal sikre, at:

- opgaven starter med et tydeligt mål
- alle arbejder ud fra den samme godkendte kontekst
- roller og beslutningsrettigheder er klare
- kvalitet og fakta bliver kontrolleret
- det færdige resultat og relevant læring ender i GitHub

Workflowet kan skaleres op eller ned efter opgavens risiko og kompleksitet, men de centrale kontrolpunkter må ikke springes over uden en bevidst beslutning.

## Roller

### Thomas Reberholt — produktchef

Produktchefen:

- fastlægger mål, prioritet og forretningsmæssig retning
- godkender væsentlige antagelser og kompromiser
- afgør konflikter mellem mål, kvalitet, tid og omkostning
- godkender leverancer med større forretningsmæssig betydning
- ejer beslutningen om, hvad der bliver en del af Reberholt OS

### ChatGPT — arkitekt

ChatGPT:

- afklarer opgaven og identificerer manglende information
- finder og strukturerer den relevante kontekst
- nedbryder komplekse opgaver i kontrollerbare leverancer
- designer struktur, krav, arbejdsgang og acceptkriterier
- udfordrer antagelser og synliggør risici
- gennemgår leverancen i forhold til helheden

### Claude — forfatter

Claude:

- producerer og redigerer indhold inden for det godkendte brief
- følger gældende artikel-, brand- og SEO-standarder
- bevarer tone, målgruppe og struktur gennem længere leverancer
- markerer manglende fakta og uklare instruktioner
- afleverer output i det aftalte format

### GitHub — fælles sandhed

GitHub:

- indeholder de godkendte standarder og leverancer
- viser ændringshistorik og ansvar gennem commits
- er udgangspunkt for nye opgaver
- modtager forbedringer, når arbejdet skaber generaliserbar læring

Rollerne er standardroller. Et værktøj kan udføre flere funktioner i en konkret opgave, men rolle, ansvar og godkendelsespunkt skal stadig være tydeligt.

## Grundregel

AI-output er et forslag, indtil det er kontrolleret i forhold til opgavens acceptkriterier og relevante standarder.

Et velformuleret svar er ikke i sig selv dokumentation for, at svaret er korrekt.

## Workflow i syv faser

### Fase 1: Modtag og afklar opgaven

Opgaven begynder med et kort brief. ChatGPT vurderer, om der er nok information til at starte sikkert.

Briefet skal så vidt muligt indeholde:

- **Mål:** Hvad skal opgaven opnå?
- **Projekt:** Hvilket projekt eller hvilken virksomhed vedrører den?
- **Målgruppe:** Hvem skal bruge eller opleve resultatet?
- **Leverance:** Hvad skal konkret afleveres?
- **Kilder:** Hvilke dokumenter, data og systemer er autoritative?
- **Begrænsninger:** Hvad må eller kan ikke ændres?
- **Acceptkriterier:** Hvordan afgør vi, at opgaven er færdig?
- **Ejer:** Hvem godkender resultatet?

Hvis en manglende oplysning kan ændre resultatet væsentligt, skal den afklares. Små, reversible antagelser må foretages, hvis de markeres tydeligt.

### Fase 2: Hent gældende kontekst

Før produktion skal den relevante dokumentation findes i Reberholt OS.

Konteksten bør begrænses til det, som opgaven faktisk kræver. Et normalt kontekstsæt består af:

1. `README.md`
2. `docs/001_Vision.md`
3. `docs/002_Principper.md`
4. den relevante faglige standard
5. projektspecifik dokumentation
6. opgavens godkendte brief og kilder

Hvis en chat eller arbejdsnote indeholder en vigtig regel, som ikke findes i GitHub, skal reglen behandles som en antagelse, indtil den er godkendt og dokumenteret.

### Fase 3: Design løsningen

ChatGPT udarbejder en plan, der passer til opgavens størrelse og risiko.

Planen skal definere:

- delopgaver og rækkefølge
- ansvarlig rolle for hver del
- nødvendige input og handoffs
- kontrolpunkter
- godkendelser
- forventede filer eller andre leverancer

En enkel opgave kan løses direkte. En kompleks opgave bør opdeles, så hver leverance kan vurderes selvstændigt.

### Fase 4: Producér leverancen

Den producerende rolle arbejder inden for briefet og de gældende standarder.

Under produktionen skal AI:

- skelne mellem dokumenterede fakta og antagelser
- bevare sporbarhed til vigtige kilder
- undgå at opfinde manglende forretningsregler
- følge det aftalte format
- stoppe ved beslutninger, som kræver produktchefen
- levere et resultat, der kan gennemgås uden skjult kontekst

Ved indholdsopgaver vil Claude normalt være primær forfatter. Ved struktur, kode, analyse eller dokumentationsarbejde kan ChatGPT være producerende rolle.

### Fase 5: Gennemgå og verificér

Leverancen kontrolleres mod brief, standarder og risiko.

Gennemgangen skal som minimum spørge:

- Løser resultatet det aftalte problem?
- Er alle acceptkriterier opfyldt?
- Er fakta, beregninger og links kontrolleret?
- Er tone, format og målgruppe korrekt?
- Er relevante sikkerheds- og privatlivskrav opfyldt?
- Er væsentlige antagelser synlige?
- Kan en anden person forstå og bruge leverancen?

Den samme AI kan foretage en første egenkontrol, men højrisiko-output skal have en uafhængig kontrol eller menneskelig faglig vurdering.

### Fase 6: Godkend og publicér

Når leverancen er kontrolleret, afgøres det, hvem der skal godkende den.

Produktchefens udtrykkelige godkendelse kræves normalt ved:

- ændring af vision, principper eller fælles standarder
- publicering på vegne af et brand eller en virksomhed
- væsentlige økonomiske, juridiske eller strategiske beslutninger
- ændring af adgang, integrationer eller automatisering med eksterne effekter
- handlinger, som er vanskelige at rulle tilbage

Godkendte ændringer publiceres i GitHub med et commit, der kort beskriver formålet.

### Fase 7: Gem læring

Efter leverancen vurderes det, om arbejdet har skabt viden, som bør genbruges.

Spørg:

- Opstod det samme spørgsmål flere gange?
- Manglede der en regel eller et eksempel?
- Fandt vi en bedre arbejdsgang?
- Bør en projektspecifik løsning blive en fælles standard?
- Afslørede kontrollen en gentagelig fejltype?

Kun generaliserbar og godkendt læring føres tilbage til Reberholt OS. Arbejdsnoter og engangsløsninger skal ikke automatisk blive permanente regler.

## Standardbrief til AI-opgaver

Brug denne skabelon som udgangspunkt:

```markdown
# Opgave

## Mål
[Det konkrete resultat og den ønskede effekt]

## Projekt og målgruppe
[Projekt, brand, bruger eller læser]

## Leverance
[Fil, tekst, analyse, kode, plan eller anden outputtype]

## Autoritative kilder
- [Relevante filer i Reberholt OS]
- [Godkendte eksterne kilder eller data]

## Begrænsninger
- [Det, som ikke må ændres]
- [Juridiske, tekniske, brandmæssige eller tidsmæssige rammer]

## Acceptkriterier
- [Kontrollerbart kriterium 1]
- [Kontrollerbart kriterium 2]
- [Kontrollerbart kriterium 3]

## Roller og godkendelse
- Arkitekt: [navn/værktøj]
- Producent: [navn/værktøj]
- Reviewer: [navn/værktøj]
- Endelig godkender: [navn]
```

## Handoff fra ChatGPT til Claude

Når ChatGPT afleverer en opgave til Claude, skal handoffen være selvstændig og indeholde:

- formål og ønsket effekt
- målgruppe og tone
- disposition eller leverancestruktur
- relevante standarder og kilder
- krav til fakta og kildebrug
- acceptkriterier
- åbne spørgsmål og godkendte antagelser
- præcist outputformat

Claude skal ikke være afhængig af at kunne læse den oprindelige samtale for at løse opgaven korrekt.

## Handoff fra Claude til ChatGPT

Når Claude afleverer et udkast, skal det ledsages af:

- selve leverancen
- en kort liste over anvendte kilder
- markerede antagelser eller manglende information
- eventuelle afvigelser fra briefet
- områder, der kræver særlig kontrol

ChatGPT gennemgår derefter struktur, sammenhæng, acceptkriterier og relation til Reberholt OS.

## Risikoniveauer

### Lav risiko

Eksempler: intern disposition, idéudkast, sproglig forbedring og reversibel dokumentation.

Krav:

- tydeligt mål
- almindelig egenkontrol
- menneskelig godkendelse efter behov

### Mellem risiko

Eksempler: offentligt indhold, SEO-anbefalinger, kodeændringer og automatisering uden følsomme handlinger.

Krav:

- dokumenteret brief og kilder
- eksplicitte acceptkriterier
- målrettet test eller review
- godkendelse før publicering eller aktivering

### Høj risiko

Eksempler: juridiske eller økonomiske beslutninger, persondata, sikkerhed, sundhed, betalinger og automatisering med betydelige eksterne konsekvenser.

Krav:

- navngiven menneskelig ejer
- autoritative og aktuelle kilder
- uafhængig faglig kontrol
- tydelig godkendelse ved handlingstidspunktet
- plan for fejl, stop og eventuel tilbagerulning

AI må ikke være eneste beslutningstager ved høj risiko.

## Kvalitetsport før GitHub

En leverance er klar til GitHub, når:

- [ ] Formål og ejer er tydelige
- [ ] Relevante standarder er fulgt
- [ ] Acceptkriterierne er opfyldt
- [ ] Fakta og tekniske påstande er kontrolleret
- [ ] Antagelser og begrænsninger er synlige
- [ ] Følsomme oplysninger er fjernet
- [ ] Filnavn og placering følger repositoryets struktur
- [ ] Ændringen er lille nok til at kunne gennemgås
- [ ] Commit-beskeden forklarer ændringens formål
- [ ] Relevant læring er vurderet

## Commit-praksis

Commits skal være små og have en kort, handlingsorienteret besked.

Anbefalet format:

```text
type: kort beskrivelse af ændringen
```

Eksempler:

```text
docs: define AI workflow
content: add Madmagasinet article draft
seo: update internal linking standard
fix: correct publishing checklist
```

Én commit bør som hovedregel repræsentere én forståelig ændring.

## Når workflowet skal stoppes

AI eller medarbejderen skal stoppe ved beslutningspunktet, hvis:

- målet eller ejeren ikke kan identificeres
- autoritative kilder modsiger hinanden
- nødvendige data mangler og ikke kan erstattes sikkert
- opgaven kræver adgang eller tilladelse, som ikke er givet
- risikoen er større end den aftalte kontrol
- handlingen vil publicere, sende, betale, slette eller ændre adgang uden nødvendig godkendelse

Et stop er ikke en fiasko. Det er et kontrolpunkt, der beskytter kvalitet og ansvar.

## Anti-mønstre

Følgende arbejdsmåder skal undgås:

- at kopiere en hel chat ind som permanent dokumentation
- at give AI en vag opgave og rette tilfældigt bagefter
- at bruge mange AI-værktøjer uden klare roller
- at behandle AI-selvsikkerhed som bevis
- at publicere før fakta og acceptkriterier er kontrolleret
- at automatisere en proces, som ingen ejer eller forstår
- at oprette en ny standard for hvert enkelt projektproblem
- at gemme vigtig kontekst i private prompts, som teamet ikke kan finde

## Vedligeholdelse

Workflowet revideres, når nye AI-værktøjer, roller eller væsentlige arbejdsgange bliver en del af Reberholt OS.

Revisioner skal bygge på faktisk brug. Hvis et kontrolpunkt konsekvent bliver sprunget over, skal årsagen undersøges: enten er workflowet for tungt, eller også mangler arbejdet den nødvendige disciplin.

---

**Status:** Første version til praktisk afprøvning  
**Ejer:** Thomas Reberholt  
**Næste dokument:** `004_Artikelstandard.md`
