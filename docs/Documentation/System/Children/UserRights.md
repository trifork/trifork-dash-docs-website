---
layout: default
title: Brugerrettigheder
nav_order: 1
parent: System
grand_parent: Dokumentation
permalink: dokumentation/system/brugerrettigheder
---

# Bruger rettigheder

Befordring systemet opretholder forskellige adgangsroller opdelt i 3 hovedgrupper:

- Transportkontor = Kørselskontoret (Hospital)
- Hospitalafdeling
- Systemadministratorer

Tabellen nedenfor opsummerer de forskellige adgangsroller for hver gruppe.

| Rolle         | Grupper       | Administrator | Beskrivelse   |
| ------------- | ------------- | ------------- | ------------- |
| Validator | Hospital Afdeling  | Nej | Giver adgang til at oprette nye ansøgninger. <br />Giver **ikke** adgang til administrations submenu. |
| AdminForDepartment | Hospital Afdeling | Ja | Giver adgang til administations submenu. <br />Kan kun aministrere hospitals afdeling. |
| Approver <br />(Payer) | Kørselskontor | Nej | Giver adgang til at godkende modtagede ansøgninger. <br />Giver **ikke** adgagnt til administrations submenu. |
| AdminForHospital | Kørselskontor | Ja | Giver adgang til administrations submenu.<br />Kan administrere afdelinger for hele det givne hospital. |
| SystemAdmin | System Administrator | Ja |  Global system administrator <br />Kan administrere både afdelinger og hospitaler i hele regionen |

Ud over disse 5 adgangsroller definerer frontend en yderligere adgangsrolle kaldet `AnyAdmin`. Denne rolle tildeles automatisk, hvis
brugeren har en af de eksisterende administratorroller. Dette er rent en funktionel rolle, der bestemmer, om det er muligt at interagere med
administration undermenu i kontrolpanelet.
