# Systemutvikling, fra start til slutt

## Livssyklus

### 1. Planlegge

- Kartlegge behov og ønsker
- Forene "den beste løsningen" med virkeligheten
- Definere MVP
- Formulere overordnet kravspesifikasjon
- Formulere detaljerte spesifikasjoner av ulike views eller subsystemer (ved behov)
- Hva innebærer leveransen?
  - Et produkt vi kan bruke?
  - Kildekode? Som UDA kan forvalte?
  - UX og UU (hvilket kvalitetsnivå trenger vi)
- Finne egnet teknologi
  - UI: Web? Inni Teams? Tykk klient?
  - Rammeverk: Power Platform? Pro code?
  - Datalagring: SharePoint? Filer? Database?
  - Hosting: Self-hosted? GC? AWS? MS?
  - Relevant teknologi - viktig for å finne folk
- Forvaltning - når programvaren eksisterer, hvem skal
  - Rette feil
  - Drifte
  - Viderutvikle
  - Bekoste løpende utgifter
  - Hva er estimert levetid?
- Vilkår for bruk
  - Hvem kan bruke tjenesten
  - API-er
  - Lisens/open source
- Personvern, ROS, DPIA
  - Forvaltning av persondata (GDPR)


### 2. Utvikle
- System for å tracke status på oppgaver (github? devops?)
- Oppfølging av utviklere
- Tisplan for milepæler, MVP og v1.0
- Dersom eksterne utivklere: Dagbøter ved manglende respons eller leveranse?

### 3. Teste programvare 
- Automatiserte tester av tilgang
- Mennesker tester mot en evt. kravspesifikasjon
- Penetrasjonstest

### 4. Rulle ut programvare
- Levere MVP, deretter bygge ut én og én feature
- Dersom ekstern utvikler, følge opp vs. kravspesifikasjon

### 5. Drift 
- Skalering
- Systemovervåkning
- Hendelseshåndtering 
- Kontinuerlig utvikling (tilbake til punkt 2)
- Dersom eksterne aktører: Dagbøter ved nedetid eller annen svikt?

### 6. Avvikle programvare
- Avhengigheter, melde i fra
- Data, skal alt slettes? Arkiveres? Overføres?
- Hvordan slette?

