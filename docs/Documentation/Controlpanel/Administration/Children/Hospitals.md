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

Note: Selvom at offentlig transport og kilometer kontoen er det samme, skal de vælges for at systemet fungere korrekt.

## Kørselskontor (Hospital)

For at oprette et kørselskontor (Hospital) skal du være system administrator.

### Opret kørselskontor (Hospital)

Klik på "Tilføj" for at oprette et hospital

![Opret hospital knapper](/assets/documentation/hospitals_create_actions.png)

Her efter der vil åbne sig en dialog.

![Opret hospital dialog](/assets/documentation/hospitals_create_dialog.png)

AD-gruppenavn skal stemme overens med de AD-gruppenavn, som er lavet i regionens IT-systemer. Her skal du kontakte regionens IT-afdeling for at få de rigtige informationer.

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

For at slette et kørselskontor (Hospital), skal du klikke på et kørselskontor (Hospital) og tryk derefter på "Rediger".

![Slet hospital valgt](/assets/documentation/hospital_selected.png)

Her efter vil der åbne sig en dialog. Tryk på "Slet"

**OBS** For at kunne slette et kørselskontor (Hospital), må der ikke være nogle afdelinger tilknyttet, samt du skal være system administrator.

## Afdelinger

### Opret afdeling

### Rediger afdeling

### Slet afdeling

## Afsnit

### Opret afsnit

### Rediger afsnit

### Slet afsnit

## Skærme

### Opret skærm

### Rediger skærm

### Slet skærm
