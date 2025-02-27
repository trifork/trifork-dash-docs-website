---
layout: default
title: Features
nav_order: 1
description: "Alle features i Befordring by Trifork"
permalink: /features
---

# Oversigt over features i Befordring by Trifork

| Feature                                                                   | Region Nordjylland    | Region Midtjylland   | Region Syddanmark        | Region Sjælland    |
| :------------------------------------------------------------------------ | :--------------------:| :------------------: | :----------------------: | :-----------------:|
| [AddVoucherPayment](#addvoucherpayment)                                   | **X**                 |                      |                          |                    |
| AddParentOrGuardianToApplication                                          | **X**                 |                      |                          |                    |
| AlternativeListAndCount                                                   | **X**                 |                      |                          | **X**              |
| [AuditLogs](#auditlogs)                                                   |                       |                      |                          |                    |
| [BookingRange](#bookingrange)                                             | **X**                 |                      |                          |                    |
| ChooseHighestRejseplanPriceByOccurrence                                   |                       |                      |                          |                    |
| CitizenFileUpload                                                         | **X**                 | **X**                |                          |                    |
| [CorrectBookingLocation](#correctbookinglocation)                         |                       |                      |                          |                    |
| DiagnoseCode                                                              | **X**                 |                      |                          |                    |
| EnablePublicTransportType                                                 | **X**                 |                      |                          |                    |
| ErrorHandlingFrontEnd                                                     | **X**                 | **X**                | **X**                    | **X**              |
| ExportWorkflowGraph                                                       |                       |                      |                          |                    |
| [ExtendedPatientGrantTypes](#extendedpatientgranttypes)                   | **X**                 |                      |                          |                    |
| ExternalPdfConverterEnabled                                               |                       |                      |                          |                    |
| [HearingApplications](#hearingapplications)                               | **X**                 |                      |                          |                    |
| [HospitalAddress](#hospitaladdress)                                       |                       |                      | **X**                    |                    |
| [InvalidateApplications](#invalidateapplications)                         | **X**                 | **X**                |                          |                    |
| NonRegional                                                               | **X**                 |                      |                          |                    |
| ParentConsentFeature                                                      |                       |                      |                          |                    |
| [PendingLetters](#pendingletters)                                         |                       |                      |                          |                    |
| [PendingWorkflows](#pendingworkflows)                                     |                       |                      |                          |                    |
| PensionServiceEnabled                                                     |                       |                      |                          | **X**              |
| [PersistSearchField](#persistsearchfield)                                 | **X**                 | **X**                | **X**                    |                    |
| [PublicTransportPricesForFreeChoice](#publictransportpricesforfreechoice) | **X**                 | **X**                | **X**                    | **X**              |
| SampleControl                                                             | **X**                 |                      |                          |                    |
| SectionValidDateInterval                                                  |                       |                      |                          |                    |
| ShowDeceasedStatus                                                        | **X**                 |                      |                          |                    |
| ShowPatientGrants                                                         | **X**                 | **X**                |                          | **X**              |
| [TransportRefundApplicationNote](#transportrefundapplicationnote)         | **X**                 | **X**                |                          |                    |
| TransportRefundApplicationStatesCounterEnabled                            |                       |                      |                          |                    |
| [Visitation (UR, Udenregional)](#visitation-ur-udenregional)              | **X**                 |                      |                          |                    |
| [YearChangeVariables](#yearchangevariables)                               | **X**                 | **X**                | **X**                    | **X**              |

## Beskrivelse af system features

### AddVoucherPayment
Denne feature gør det muligt at kontere ekstra beløb/bilag på en ansøgning.

### AuditLogs
Denne feature slår en revisionslog til i systemet, som logger til en fil på serveren. Den logger hvem der læser, opretter, ændrer og sletter data igennem kontrolpanelet, og logger det til en logfil med et tidspunkt. Dette er ikke slået til i nogle produktionsmiljøer.

### BookingRange
Denne feature giver mulighed for at sætte en slutdato på en booking, så den kun er gyldig i en begrænset periode.

### CorrectBookingLocation
Denne feature bliver brugt til at løse et specifikt behov for bookinger på afdelinger med satelitfunktioner. En booking kan have en alternativ geografisk lokation. Når denne feature er slået til, kan ansøgeren på Borgerløsningen angive et alternativt mødested for en booking. Systemet tjekker om bookingen har en alternativ geografisk lokation og beregner afstand og pris herefter.

### ExtendedPatientGrantTypes
Denne feature slår flere patientbevillingstyper til i systemet.
- Fly
- Hotel
- Betalingstilsagn

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

### PendingLetters
Et brev kan være “Under oprettelse” 
Denne feature visualiserer hvis et brev på en ansøgning, er under oprettelse. Når brevene er oprettede vil de kunne ses under filer, som normalt.

### PendingWorkflows
En ansøgning kan gå i stå i workflowet.
Denne feature er en hjælp til fejlfinding og viser om en ansøgning ligger i kø og afventer kørsel af workflowet.

### PersistSearchField
Når denne feature er slået til, vil værdien man søger på blive stående i søgefeltet efter søgningen er gennemført. Det gør sig gældende for søgefeltet i menuen.

### PublicTransportPricesForFreeChoice
Opslag/beregning af afstand og pris for frit sygehusvalg. Hvis denne feature er slået til, vil systemet også beregne pris og vise afstand til det udpegede nærmeste relevante sygehus.

### TransportRefundApplicationNote
Denne feature giver mulighed for at tilføje en ekstra note til en ansøgning. Ansøgningsnoten vises i ansøgningsoverblikket i Kontrolpanelet og kan ses i alle states.

### Visitation (UR, Udenregional) 
Denne feature dækker over al udenregional funktionalitet. Denne feature kan ikke bare slåes til, da den kræver en del manuel implementering, for at understøtte UR-ansøgninger.
UR-featuren dækker over UR-ansøgningsflow i borgerportalen og UR-sagsbehandling i kontrolpanelet, samt administration af diagnosekoder og visitationer.

### YearChangeVariables
Denne feature slår årsskiftevariabler til i Befordring. Årsskiftevariablerne definerer bla. KM-grænse og minimumsbeløbsgrænse.
