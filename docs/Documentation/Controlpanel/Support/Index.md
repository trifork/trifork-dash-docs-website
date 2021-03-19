---
layout: default
title: Support
nav_order: 6
parent: Kontrolpanelet
grand_parent: Dokumentation
permalink: dokumentation/kontrolpanelet/support
---

# Support

Med Support funktionen kan du fremsøge logs fra databasen.

Med denne funktion kan du fremsøge de logs, som systemet laver. Det kan variere fra service til service, hvor meget der logges.
Dette bruges primært til at fejlsøge med.

Når du skal søge i logs, skal du som minimum angive hvor mange logs af gangen du vil se. Jo flere logs, jo længere tid tager det at søge frem.

![Søge parametre](/assets/documentation/support-search-params.png)

Du kan gøre søgningen mere præcis, ved at præcicere din søgning.

Du kan tilføje følgende parametre

- **CPR**: Med denne kommer der kun logs frem, hvor CPR nummeret er knyttet til loggen.
- **Trace Id**: TraceId fremkommer når de røde fejlbokse kommer. TraceId kunne fx se ud `|4f9b61e6-459030d8af136da8.`
- **Application**: Det kunne fx være `ControlPanel.Api`.
- **From Date**: Datoen log søgningen skal starte fra.
- **To Date**: Datoen log søgningen skal slutte.
- **Levels**: Her kan du vælge den level fejlen har.
