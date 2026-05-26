# Systemutvikling, fra start til slutt

## 1. Planlegge

- Kartlegge behov og ønsker
- Forene "den beste løsningen" med virkeligheten
- Definere MVP
- Ett sted å tracke status (GitHub? Devops?)
- Formulere overordnet kravspesifikasjon
- Formulere detaljerte spesifikasjoner av ulike views eller subsystemer (ved behov)
- Hva innebærer leveransen?
  - Tilpasset hyllevare eller egenutviklet?
  - Et produkt vi kan bruke?
  - Kildekode? Som UDA kan forvalte?
  - UX og UU (hvilket kvalitetsnivå trenger vi)
  - Dataeierskap (eier vi våre egne data, hvem har tilgang)
  - Portabilitet (mhp både innhold og selve tjenesten)
- Finne egnet teknologi
  - UI: Web? Inni Teams? Tykk klient?
  - Rammeverk: Power Platform? Pro code?
  - Datalagring: SharePoint? Filer? Database?
  - Hosting: Self-hosted? GC? AWS? Azure?
  - Relevant teknologi - viktig for å finne folk
- Personvern, ROS, DPIA
  - Forvaltning av persondata (GDPR)
- Forvaltning - når programvaren eksisterer, hvem skal
  - Drifte
  - Rette feil
  - Viderutvikle
  - Bekoste løpende utgifter
- Vilkår for bruk
  - Hvem kan bruke tjenesten
  - API-er
  - Lisens/open source
    - Husk at lukket kildekode må begrunnes
- Hva er estimert levetid?

## 2. Utvikle
- Prioritere oppgaver
- Oppfølging av utviklere
- Tisplan for milepæler, MVP, v1.0 og evt. senere versjoner
- Dersom eksterne utivklere: Dagbøter ved manglende respons eller leveranse?

## 3. Teste 
- Automatiserte tester av tilgang
- Mennesker tester mot en evt. kravspesifikasjon
- Penetrasjonstest

## 4. Rulle ut
- Levere MVP, deretter bygge ut én og én feature
- Dersom eksterne utviklere, følge opp vs. kravspesifikasjon

## 5. Drift 
- Skalering etter behov
- Systemovervåking
- Hendelseshåndtering
- Kontinuerlig utvikling
  - Fikse bugs
  - Nye features
  - --> Tilbake til punkt 2
- Dersom eksterne aktører: Dagbøter ved nedetid eller annen svikt?

## 6. Avvikle
- Avhengigheter, melde fra
- Data: Skal alt slettes? Arkiveres? Overføres?
- Hvordan slette?

