---
layout: default
title: Features
nav_order: 1
description: "Alle features i Befordring by Trifork"
permalink: /features
---

# Oversigt over features i Befordring by Trifork

| Feature | Region Nordjylland | Region Midtjylland | Region Syddanmark | Region Sjælland |
| :-----: | :-----------------: | :-----------------: | :---------------: | :-------------: |
| [AddVoucherPayment](#addvoucherpayment)                                                           | **X**                 |                      |                          |                    |
| [AddParentOrGuardianToApplication](#addparentorguardiantoapplication)                             | **X**                 |                      |                          |                    |
| [AlternativeListAndCount](#alternativelistandcount)                                               | **X**                 |                      |                          | **X**              |
| [AuditLogs](#auditlogs)                                                                           |                       |                      |                          |                    |
| [BookingRange](#bookingrange)                                                                     | **X**                 |                      |                          |                    |
| [ChooseHighestRejseplanPriceByOccurrence](#choosehighestrejseplanpricebyoccurrence)               |                       | **X**                | **X**                    | **X**              |
| [CitizenFileUpload](#citizenfileupload)                                                           | **X**                 | **X**                |                          |                    |
| [CorrectBookingLocation](#correctbookinglocation)                                                 |                       |                      |                          |                    |
| [DiagnoseCode](#diagnosecode)                                                                     | **X**                 |                      |                          |                    |
| [EnablePublicTransportType](#enablepublictransporttype)                                           | **X**                 |                      |                          |                    |
| [ErrorHandlingFrontEnd](#errorhandlingfrontend)                                                   | **X**                 | **X**                | **X**                    | **X**              |
| [ExportWorkflowGraph](#exportworkflowgraph)                                                       |                       |                      |                          |                    |
| [ExtendedPatientGrantTypes](#extendedpatientgranttypes)                                           | **X**                 |                      |                          |                    |
| [ExternalPdfConverterEnabled](#externalpdfconverterenabled)                                       |                       |                      |                          |                    |
| [HearingApplications](#hearingapplications)                                                       | **X**                 |                      |                          |                    |
| [HospitalAddress](#hospitaladdress)                                                               |                       |                      | **X**                    |                    |
| [InvalidateApplications](#invalidateapplications)                                                 | **X**                 | **X**                |                          |                    |
| [NonRegional](#nonregional)                                                                       | **X**                 |                      |                          |                    |
| [ParentConsentFeature](#parentconsentfeature)                                                     |                       |                      |                          |                    |
| [PendingLetters](#pendingletters)                                                                 |                       |                      |                          |                    |
| [PendingWorkflows](#pendingworkflows)                                                             |                       |                      |                          |                    |
| [PensionServiceEnabled](#pensionserviceenabled)                                                   |                       |                      |                          | **X**              |
| [PersistSearchField](#persistsearchfield)                                                         | **X**                 | **X**                | **X**                    |                    |
| [PublicTransportPricesForFreeChoice](#publictransportpricesforfreechoice)                         | **X**                 | **X**                | **X**                    | **X**              |
| [SampleControl](#samplecontrol)                                                                   | **X**                 |                      |                          |                    |
| [SectionValidDateInterval](#sectionvaliddateinterval)                                             |                       |                      |                          |                    |
| [ShowDeceasedStatus](#showdeceasedstatus)                                                         | **X**                 |                      |                          |                    |
| [ShowPatientGrants](#showpatientgrants)                                                           | **X**                 | **X**                |                          | **X**              |
| [TransportRefundApplicationNote](#transportrefundapplicationnote)                                 | **X**                 | **X**                |                          |                    |
| [TransportRefundApplicationStatesCounterEnabled](#transportrefundapplicationstatescounterenabled) | **X**                 | **X**                |                          | **X**              |
| [Visitation (UR, Udenregional)](#visitation-ur-udenregional)                                      | **X**                 |                      |                          |                    |
| [YearChangeVariables](#yearchangevariables)                                                       | **X**                 | **X**                | **X**                    | **X**              |

## Beskrivelse af system features

### AddVoucherPayment
Denne feature gør det muligt at kontere ekstra beløb/bilag på en ansøgning.

### AddParentOrGuardianToApplication
Denne feature giver mulighed for forælder eller værge at oprette ansøgning på vegne af en anden person.

### AlternativeListAndCount
En alternativ måde at hente listen over ansøgninger, samt antallet af ansøgninger til visning i front end.

### AuditLogs
Denne feature slår en revisionslog til i systemet, som logger til en fil på serveren. Den logger hvem der læser, opretter, ændrer og sletter data igennem kontrolpanelet, og logger det til en logfil med et tidspunkt. Dette er ikke slået til i nogle produktionsmiljøer.

### BookingRange
Denne feature giver mulighed for at sætte en slutdato på en booking, så den kun er gyldig i en begrænset periode.

### ChooseHighestRejseplanPriceByOccurrence
Denne feature bestemmer hvorvidt der, i forbindelse med beregning af priser  

### CitizenFileUpload
Denne feature tillader brugere af uploade filer via borgerløsningen.

### CorrectBookingLocation
Denne feature bliver brugt til at løse et specifikt behov for bookinger på afdelinger med satelitfunktioner. En booking kan have en alternativ geografisk lokation. Når denne feature er slået til, kan ansøgeren på Borgerløsningen angive et alternativt mødested for en booking. Systemet tjekker om bookingen har en alternativ geografisk lokation og beregner afstand og pris herefter.

### DiagnoseCode
Katalog over diagnosekoder der bruges i forbindelse med visitationer/UR

### EnablePublicTransportType
Denne feature tillader brugeren at vælge hvorvidt de har taget offentlig transport begge veje eller blot en af vejene.

### ErrorHandlingFrontEnd
Denne feature bestemmer hvordan vi håndterer fejl ved oprettelse af ansøgninger i borgerløsningen.

### ExportWorkflowGraph
Denne feature giver mulighed for at få vist et visuelt overblik over et workflow.

### ExtendedPatientGrantTypes
Denne feature slår flere patientbevillingstyper til i systemet.
- Fly
- Hotel
- Betalingstilsagn

### ExternalPdfConverterEnabled
Denne feature gør brug af en service til konvertering af filer af typen .docx til .pdf, som alternativ til Spire biblioteket, som nu kun understøttes på Windows systemer. Featuren tillader dermed konvertering af .docx til .pdf på f.eks. Linux servere.

### HearingApplications
Denne feature stiller tre ekstra states til rådighed i Kontrolpanelet på både IR- og UR-ansøgninger
- Agterskrivelse tilskud
- Agterskrivelse afslag
- Indsigelse

Med denne feature har man mulighed for at sende en ansøgning til enten "Agterskrivelse tilskud" eller "Agterskrivelse afslag". Ansøgningen ligger i denne state i en konfigurerbar periode. Hvis patienten ikke gør indsigelse behandles ansøgningen automatisk efter den konfigurede periode til hhv. "Afvis" eller "Godkend" afhængig af agterskrivelse status (godkend eller afslag). Hvis patienten gør indsigelse kan ansøgningen sendes tilbage til "Behandles", "Afvises" eller "Behandles på papir".

### HospitalAddress
Denne feature slår adresse flettefelter til i Breve for Hospital-niveauet.

### InvalidateApplications
Denne feature indfører en ny state, “Ugyldig”, og gør det muligt at ugyldiggøre en ansøgning fra status "Modtaget" eller "Behandles".

### NonRegional
Denne feature giver mulighed for at tilgå UR-relaterede sider.

### ParentConsentFeature
Denne feature tilføjer en samtykkeerklæring for om informationer om ansøgninger må videresendes til forælder/værge, når man ansøger på vegne af en person under 15 år.

### PendingLetters
Et brev kan være “Under oprettelse” 
Denne feature visualiserer hvis et brev på en ansøgning, er under oprettelse. Når brevene er oprettede vil de kunne ses under filer, som normalt.

### PendingWorkflows
En ansøgning kan gå i stå i workflowet.
Denne feature er en hjælp til fejlfinding og viser om en ansøgning ligger i kø og afventer kørsel af workflowet.

### PensionServiceEnabled
Denne feature slår integration mod Kombit/Pensionsinfo til. Alternativt tages der udgangspunkt i ansøgerens alder.

### PersistSearchField
Når denne feature er slået til, vil værdien man søger på blive stående i søgefeltet efter søgningen er gennemført. Det gør sig gældende for søgefeltet i menuen.

### PublicTransportPricesForFreeChoice
Opslag/beregning af afstand og pris for frit sygehusvalg. Hvis denne feature er slået til, vil systemet også beregne pris og vise afstand til det udpegede nærmeste relevante sygehus.

### SampleControl
Denne feature giver mulighed for at tilgå ansøgninger med stikprøvestatus.

### SectionValidDateInterval
Denne feature bliver pt. ikke brugt, men bliver brugt til at sætte en gyldighedsperiode for en SOR-kode.

### ShowDeceasedStatus
Denne feature giver mulighed for at vise at en borger er død, dog ikke hvornår personen er død.

### ShowPatientGrants
Denne feature giver mulighed for at håndtere ansøgeres patientbevillinger.

### TransportRefundApplicationNote
Denne feature giver mulighed for at tilføje en ekstra note til en ansøgning. Ansøgningsnoten vises i ansøgningsoverblikket i Kontrolpanelet og kan ses i alle states.

### TransportRefundApplicationStatesCounterEnabled
Denne feature slår overblikket over antal af ansøgninger i hver status til.

### Visitation (UR, Udenregional) 
Denne feature dækker over al udenregional funktionalitet. Denne feature kan ikke bare slåes til, da den kræver en del manuel implementering, for at understøtte UR-ansøgninger.
UR-featuren dækker over UR-ansøgningsflow i borgerportalen og UR-sagsbehandling i kontrolpanelet, samt administration af diagnosekoder og visitationer.

### YearChangeVariables
Denne feature slår årsskiftevariabler til i Befordring. Årsskiftevariablerne definerer bla. KM-grænse og minimumsbeløbsgrænse.
