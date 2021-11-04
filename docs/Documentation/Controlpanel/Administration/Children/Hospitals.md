---
layout: default
title: Hospitaler
nav_order: 1
parent: Administration
grand_parent: Kontrolpanelet
permalink: dokumentation/kontrolpanelet/administration/hospitaler
---

# Hospitaler

Her vil vi gennemgå hvordan man administrere hospialer, afdelinger, afsnit og skærme.

**OBS** Andre konti er en feature som skal købes. Har din region ikke købt den, vil disse ikke blive vist.

## Konto generelt

For at understøtte forskellige konterings praksis i regionerne, er der udviklet et system som kan det.

Når en betaling tilføjes til en ansøgning, vil systemet automatisk kigge på den mest relevante konto for offentlig eller kilometer.
Den vil kigge på følgende måde

Først vil den se, om det afsnit ansøgningen tilhører har en offentlig/kilometer konto. Hvis afsnittet ikke har den konto, som skal bruges vil den kigge på den afdeling, afsnittet tilhører.
Hvis ikke afdelingen har en relevant konto, vil den kigge på det Kørselskontor (Hospital) som afdelingen tilhører.

AD-gruppenavn skal stemme overens med de AD-gruppenavn, som er lavet i regionens IT-systemer. Her skal du kontakte regionens IT-afdeling for at få de rigtige informationer.

_Note: Selvom at offentlig transport og kilometer kontoen er det samme, skal de vælges for at systemet fungere korrekt._

_Note: Felter som er markeret røde, skal udfyldet. De hvide er optionelle._

## Kørselskontor (Hospital)

For at oprette et kørselskontor (Hospital) skal du være system administrator.

### Opret kørselskontor (Hospital)

Klik på "Tilføj ny" for at oprette et hospital

![Opret hospital knapper](/assets/documentation/hospitals_create_actions.png)

Her efter der vil åbne sig en dialog.

![Opret hospital dialog](/assets/documentation/hospitals_create_dialog.png)

Offentlig Transport og Kilometer konto, er dem som er oprettet under [konti](https://befordring.dash.trifork.com/dokumentation/kontrolpanelet/administration/konti) fanen.
Der kan vælges én offentlig transport eller kilometer konto.

Andre konti kan bruges til at kontere borgeres færge billet, bro billet eller andre udgifter.

**OBS** Vejnavn, husnummer, husbogstav, postnummer og by er en feature som skal tilkøbes.

**OBS** Andre konti er en feature som skal tilkøbes.

### Rediger kørselskontor (Hospital)

For at redigere et kørselskontor (Hospital), skal du klikke på et kørselskontor (Hospital) og tryk derefter på "Rediger".

![Rediger hospital valgt](/assets/documentation/hospital_selected.png)

Her efter vil der åbne sig en dialog boks. Rediger den ønskede værdier, og tryk på "Gem".

### Slet kørselskontor (Hospital)

**DENNE HANDLING KAN IKKE FORTRYDES**

For at slette et kørselskontor (Hospital), skal du klikke på et kørselskontor (Hospital) og tryk derefter på "Rediger".

![Slet hospital valgt](/assets/documentation/hospital_selected.png)

Her efter vil der åbne sig en dialog. Tryk på "Slet"

**OBS** For at kunne slette et kørselskontor (Hospital), må der ikke være nogle afdelinger tilknyttet, samt du skal være system administrator.

## Afdelinger

For at kunne oprette, redigere en afdeling skal du være system administrator eller hospitals administrator.

Vælg et kørselskontor (Hospital).

### Opret afdeling

For at oprette en afdeling tryk på "Tilføj ny" under "Afdelinger for ..."

Her efter vil der åbne sig en dialog.

![Opret afdeling dialog](/assets/documentation/department_create_dialog.png)

For at tilføje den nye afdeling, tryk på "Tilføj".

**OBS** Andre konti er en feature som skal tilkøbes.

### Rediger afdeling

For at redigere en afdeling, klik på den som skal redigeres og klik på "Rediger" under "Afdelinger for ..."

Her efter vil der åbne sig en dialog.

![Rediger afdeling dialog](/assets/documentation/department_edit_dialog.png)

For at tilføje den nye afdeling, tryk på "Tilføj".

**OBS** Andre konti er en feature som skal tilkøbes.

### Slet afdeling

**DENNE HANDLING KAN IKKE FORTRYDES**

For at slette en afdeling, skal du klikke på den afdeling og tryk derefter på "Rediger".

![Slet afdeling dialog](/assets/documentation/department_edit_dialog.png)

Her efter vil der åbne sig en dialog. Tryk på "Slet".

## Afsnit

### Opret afsnit

**OBS** Andre konti er en feature som skal tilkøbes.

### Rediger afsnit

**OBS** Andre konti er en feature som skal tilkøbes.

### Slet afsnit

## Skærme

### Opret skærm

### Rediger skærm

### Slet skærm
