# Principper for Reberholt OS

> Principperne omsætter visionen til faste spilleregler for beslutninger, dokumentation, AI, kvalitet og automatisering.

## Dokumentets rolle

Dette dokument beskriver de principper, som gælder på tværs af Reberholt OS. De skal bruges, når nye standarder, arbejdsgange og projektspecifikke løsninger bliver designet eller ændret.

Principperne fortæller ikke altid præcis, hvordan en opgave skal løses. De fastlægger, hvad en god løsning skal respektere, og hjælper med at vælge mellem flere mulige løsninger.

## Prioritet ved uenighed

Når to instruktioner eller kilder er uenige, gælder denne rækkefølge:

1. Lovgivning, sikkerhed og bindende aftaler
2. En konkret, godkendt beslutning fra produktchefen
3. Gældende dokumentation i Reberholt OS
4. Projektspecifik dokumentation
5. Opgavens aktuelle instruktioner
6. Tidligere chats, prompts og arbejdsnoter

En konflikt må ikke skjules. Hvis den ikke kan løses sikkert ud fra rækkefølgen, skal arbejdet stoppes ved beslutningspunktet og uklarheden forelægges produktchefen.

## 1. GitHub er den fælles sandhed

Godkendte standarder, beslutninger og arbejdsgange skal have et tydeligt hjem i repositoryet.

Det betyder:

- En vigtig regel er ikke færdig, før den er dokumenteret.
- Den gældende version skal kunne findes uden adgang til en bestemt chat.
- Ændringer skal kunne spores gennem commits.
- Chats og AI-output er arbejdsrum, ikke permanente sandhedskilder.

## 2. Mennesket ejer retning og ansvar

AI kan analysere, foreslå og producere, men ansvar kan ikke delegeres til et værktøj.

Det betyder:

- Produktchefen ejer mål, prioritering og væsentlige kompromiser.
- Faglige og forretningsmæssige beslutninger skal have en menneskelig ejer.
- AI skal gøre usikkerhed synlig i stedet for at skjule den bag et sikkert sprog.
- En automatiseret handling skal kunne føres tilbage til en ansvarlig ejer.

## 3. Én regel har ét hjem

Den samme regel må ikke vedligeholdes som flere konkurrerende versioner.

Det betyder:

- Fælles regler placeres i `core/` eller den relevante tværgående dokumentation.
- Projektdokumentation linker til fælles regler i stedet for at kopiere dem.
- Projektspecifikke afvigelser beskrives ved projektet og begrundes.
- Forældet dokumentation fjernes eller markeres tydeligt som historisk.

## 4. Dokumentation skal kunne bruges

Dokumentation skal hjælpe nogen med at træffe en beslutning, udføre en opgave eller kontrollere et resultat.

Et operationelt dokument bør, når det er relevant, definere:

- formål og anvendelsesområde
- ejer og målgruppe
- nødvendige input
- proces eller beslutningsregler
- forventet output
- kvalitetskriterier
- undtagelser og eskalation

Dokumentation uden en konkret bruger eller anvendelse skal ikke oprettes.

## 5. Kvalitet kommer før volumen

Reberholt OS skal gøre det lettere at skabe holdbare leverancer, ikke blot flere leverancer.

Det betyder:

- En færdig, afprøvet standard er bedre end mange halve dokumenter.
- Output vurderes på korrekthed, relevans og anvendelighed før hastighed.
- Skabeloner må ikke erstatte faglig vurdering.
- Masseproduktion må først skaleres, når kvaliteten kan kontrolleres.

## 6. Arbejd i små, kontrollerbare ændringer

Ændringer skal være nemme at forstå, gennemgå, teste og om nødvendigt rulle tilbage.

Det betyder:

- Hver ændring skal have ét tydeligt formål.
- Store initiativer opdeles i leverancer med selvstændig værdi.
- Berørte standarder opdateres sammen med løsningen.
- Kontrol skal stå i rimeligt forhold til ændringens risiko.

## 7. Genbrug kernen, beskyt projektets særpræg

Fælles viden skal genbruges, mens projektspecifik forretning, målgruppe og identitet skal respekteres.

Det betyder:

- En fælles løsning foretrækkes, når behovet reelt er det samme.
- Forskelle mellem projekter må ikke udviskes for at gøre systemet enklere.
- Generalisering sker først, når en metode har værdi i mere end én sammenhæng.
- Læring fra et projekt flyttes kun til kernen efter bevidst vurdering.

## 8. AI skal arbejde med tydelig kontekst

AI-opgaver skal have klare mål, roller og rammer.

En AI-opgave bør som minimum angive:

- hvilket resultat der ønskes
- hvilket projekt og hvilken målgruppe opgaven vedrører
- hvilke dokumenter og data der er autoritative
- hvilke begrænsninger der gælder
- hvordan kvaliteten vurderes
- hvilke beslutninger der kræver menneskelig godkendelse

AI må ikke opfinde manglende forretningsregler. Antagelser skal markeres og valideres, når de kan påvirke resultatet væsentligt.

## 9. Verificér før noget skaleres eller publiceres

Et resultat er ikke færdigt, blot fordi det ser overbevisende ud.

Det betyder:

- Fakta kontrolleres mod relevante og troværdige kilder.
- Kode og automatisering testes i forhold til risikoen.
- Indhold gennemgås mod mål, målgruppe og gældende standard.
- Visuelle leverancer vurderes i deres faktiske anvendelse.
- Fejl og begrænsninger dokumenteres åbent.

## 10. Sikkerhed og privatliv er standard

Beskyttelse af mennesker, virksomheder og systemer skal være en del af designet fra begyndelsen.

Det betyder:

- Adgangskoder, tokens og nøgler må aldrig gemmes i repositoryet.
- Persondata indsamles og deles kun, når det er nødvendigt og lovligt.
- Adgang gives efter mindst mulige privilegium.
- Følsomme ændringer kræver tydelig ejer og kontrol.
- Logning må ikke skabe et nyt lager af unødvendige følsomme oplysninger.

## 11. Automatisér en forstået proces

Automatisering skal forbedre en dokumenteret proces, ikke skjule en uklar proces.

Før en proces automatiseres, skal følgende være kendt:

- formålet med processen
- input og forventet output
- ejer og berørte systemer
- normale beslutningsregler
- kendte fejlscenarier
- kontrolpunkter og mulighed for manuel indgriben
- hvordan automatiseringen stoppes eller rulles tilbage

Højere konsekvens kræver stærkere kontrol og mere menneskelig godkendelse.

## 12. Systemet skal blive enklere af at lære

Ny erfaring skal reducere fremtidig usikkerhed og gentagelse.

Det betyder:

- Gentagne spørgsmål er signaler om manglende eller uklar dokumentation.
- Fejl bruges til at forbedre standarder og kontrolpunkter.
- Dokumenter revideres, når praksis viser, at de ikke virker.
- Forældede processer fjernes, så systemet ikke vokser ukontrolleret.

## Beslutningsmodel

Når en ny løsning vurderes, bruges følgende rækkefølge:

1. **Formål:** Hvilket konkret problem løser vi?
2. **Ejer:** Hvem har ansvar for resultatet?
3. **Kilde:** Hvilken dokumentation og hvilke data er autoritative?
4. **Genbrug:** Findes der allerede en anvendelig standard eller løsning?
5. **Risiko:** Hvad kan gå galt, og hvem bliver påvirket?
6. **Kontrol:** Hvordan verificerer vi resultatet?
7. **Læring:** Hvad skal føres tilbage til Reberholt OS?

Hvis formål eller ejer ikke kan identificeres, bør arbejdet ikke fortsætte som en permanent del af systemet.

## Undtagelser

Et princip kan fraviges, hvis en konkret situation kræver det, men undtagelsen skal:

- have en navngiven ejer
- være bevidst og tidsafgrænset, hvor det er muligt
- beskrive årsagen og den accepterede risiko
- dokumenteres tæt på den berørte løsning
- genvurderes, hvis den gentages

En tilbagevendende undtagelse er et tegn på, at reglen eller systemdesignet bør ændres.

## Vedligeholdelse

Principperne gennemgås, når en større del af Reberholt OS ændres, eller når praksis gentagne gange viser konflikt mellem dokumentet og det daglige arbejde.

Ændringer skal bevare en tydelig forbindelse til visionen i `001_Vision.md`. Nye principper tilføjes kun, hvis de styrer reelle valg og ikke allerede er dækket af en eksisterende regel.

---

**Status:** Første version til praktisk afprøvning  
**Ejer:** Thomas Reberholt  
**Næste dokument:** `003_AI_Workflow.md`
