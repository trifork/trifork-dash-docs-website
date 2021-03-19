---
layout: default
title: Statuser
nav_order: 4
parent: Kontrolpanel
grand_parent: Kontrolpanelet
permalink: dokumentation/kontrolpanelet/kontrolpanel/statuser
---

# Statuser

I Befordring kan en ansøgnings sag befinde sig på et række stadier. I Befordring kalder vi dette stadie for ”Status”. NÅR MAN LOGGER PÅ LØSNINGEN, VIL KUN DE STATUSSER, HVOR DER ER SAGER (OG DE STATUSSER MAN HAR ADGANG TIL) VÆRE SYNLIGE. Der er følgende statusmuligheder i Befordring

![Ansøgnings states](/assets/documentation/application-state-flow.png)

**Afventer FlexDanmark:** Her ligger ansøgninger, hvor der mangler besvarelse af ”benyttet liggende eller sidende befordring” og hvor ansøgningen er under 4 dage gammel. (Dette fordi vi afventer data fra FlexDanmark.

**Modtaget:** Alle ansøgninger, som er modtaget, men hvor der mangler udfyldelse af et eller flere felter under de bookinger, som er blevet tilknyttet ansøgningen, ligger her.

**Behandlet:** Dette er en status, der fortæller at alle informationer er tilstede og ansøgningen er klar til at blive godkendt eller afvist.

**Godkendt:** Her ligger sager, som er blevet godkendt og hvor beløbet er påført, men betalingen endnu ikke er eksekveret.

**Betalt:** Når der er dannet en udbetalingsfil (sendt informationer til økonomisystemet), skifter ansøgningen status til ”Betalt”.

**Afvist:** Her ligger alle sager, som er blevet afvist (af en medarbejder eller af workflow), men hvor der endnu ikke er blevet generet et brev.

**Afvist færdige:** Afviste sager, hvor brevet er genereret og sendt, flyttes til denne status.

**Eksterne:** Der er tale om ansøgninger, som er blevet behandlet, men hvor personen ikke har adresse i regionen.

**Eksterne færdige:** Her ligger U-Reg ansøgninger, som erblevet mailet fra andre regioner.

**Papir:** Her ligger sager, der er markeret ”Behandlet på Papir” af en medarbejder på kørselskontoret.NB: Hvis en sag, på grund af en fejl, eller fordi der opstår en situation, hvor workflowet ikke kan få fat i data, eller beregne, vil en sag automatisk blive overført til status ”Behandlet (skal godkendes). Dette fordi det er her, sagsbehandleren har mulighed for dels at få et overblik over, hvorfor ansøgningen er stoppet, dels for at sagsbehandleren derved manuelt kan udføre de manglende handlinger, og derefter sende ansøgningen videre i systemet.
