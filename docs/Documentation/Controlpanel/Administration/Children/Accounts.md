---
layout: default
title: Konti
nav_order: 13
parent: Administration
grand_parent: Kontrolpanelet
permalink: dokumentation/kontrolpanelet/administration/konti
---

# Konti

_Dele af denne feature er et tilkøb_

Formålet med denne funktion er at vedligeholde en kontoplan i Befordring. Når der sker en udbetaling på en ansøgning knyttes udbetalingen til et kontonummer. Der skal som minimum være angivet kontonumre for KM-udbetalinger og Offentlig takst-udbetalinger. Med den nye konteringsfunktion er der mulighed for at tilføje flere konti, fx. konto til kontering af ansøgers udgift til Hotel eller færge og lignende.

I det følgende vil vi gennemgå, hvordan konti administreres.

## Opret en konto

Gå til menuen Konti

Tryk på "Tilføj ny"

![Tilføj ny konto](/assets/documentation/accounts_create_actions.png)

Herefter åbner dialogen til oprettelse af en ny konto.

![Tilføj ny konto dialog](/assets/documentation/accounts_create_dialog.png)

Indtast et passende navn til kontoen, et Kort navn samt kontonummeret. Tryk herefter på "Tilføj".

**OBS** der er ingen validiering på om kontoen findes i ØkonomiSystemet.

## Rediger en konto

Vælg den konto, der skal redigeres.

![Rediger konto valgt](/assets/documentation/accounts_selected.png)

Tryk herefter på "Rediger", hvorefter Rediger Konto-dialogen åbnes.

![Rediger konto valgt actions](/assets/documentation/accounts_edit_actions.png)

Rediger de ønskede værdier og tryk på "Gem".

**OBS** Der er ingen validiering på om kontoen findes i ØkonomiSystemet.

**OBS** Hvis der er anøsgninger som ligger under "Godkendt", som bruger den konto som redigeres, vil den benytte sig af den opdaterede værdi!

## Slet en konto

For at slette en konto, skal du vælge den konto, der skal slettes.

![Slet konto valgt](/assets/documentation/accounts_selected.png)

Tryk herefter på "Rediger", hvorefter Rediger Konto-dialogen åbnes.

Tryk på "Slet".

**OBS** Når en konto har været brugt til mindst én udbetaling, er det ikke muligt at slette den mere.

## Tilknyt konto til Hospitalsenhed

Når du har oprettet en konto i kontoplanen, skal kontoen knyttes til en Hospitalsenhed. 

Det er muligt at tilknytte konti på tre niveauer i Hospitalshierarkiet: Hospital, Afdeling eller Afsnit. Konti nedarves. Det vil sige, at du kan nøjes med at tilknytte en konto på Hospitals-niveauet, hvis alle underliggende enheder i hierarkiet afregner til økonomisystemet på de samme konti.

For at tilknytte en konto til en enhed i Hospitalshierarkiet skal du gøre følgende:
1. Gå til menuen Hospitaler
2. Udpeg den Hospitalsenhed, som kontoen skal knyttes til
3. Vælg Rediger
4. Scroll ned til felterne Offentlig transport konto og Km konto
5. Klik på søgefeltet til højre i feltet: Fremsøg og vælg en konto fra listen. Du skal som minimum angive en konto for offentlig transport og Km
6. Hvis du har tilkøbt mulgheden for at kontere ekstra bilag på en ansøgning kan du også vælge at oprette og udpege Andre konti
7. Afslut på knappen Gem

