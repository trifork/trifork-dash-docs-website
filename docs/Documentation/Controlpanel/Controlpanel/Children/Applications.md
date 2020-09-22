---
layout: default
title: Ansøgninger
nav_order: 1
parent: Kontrolpanel
grand_parent: Kontrolpanelet
permalink: dokumentation/kontrolpanelet/kontrolpanel/ansoegninger
last_modified_date: '2020-09-22'
---

# Ansøgninger

## Oversigt

- "Modtaget" kan vi se en samlet liste over alle ansøgninger som afventer en behandling.
- "Behandlet" er stadiet efter afdelingen har sendt ansøgningen ind til kørselskontoret.
- "Godkendt" er stadiet efter de er godkendt og inden de er betalt.

![Ansøgningsliste](/assets/documentation/application-detail-select.png)

## Ansøgnings detalje

Den gule markering er patientinformationer som indeholder alder, adresse, tekst, beskeder og historik.
Den røde markering indeholder information om selve ansøgningen og de pågældende bookinger. I visse situationer kan der være flere bookinger på en ansøgning.

![Ansøgningsliste](/assets/documentation/application-detail-view.png)

Man kan naturligvis ændre svarene på ansøgningen hvis patienten har udfyldt disse forkert. Nogle svar vil være markeret med rødt fordi de afventer afdelingen.
Hvis man har brug for at se navnet på den sagsbehandler, der har skrevet en note i Patient tekst eller i Beskeder, kan man se dette ved at køre musen hen over AD-brugerstemplingen, som er vist.

### Beskeder

Beskeder tilhører en enkel ansøgning, og følger med ansøgningen. Dette kan fx bruges til at formidle information videre til en anden sagsbehandler.

### Ansøgningsrelaterede filer

Til venstre kan der tilføjes filer til yderligere dokumentation for ansøgningen. Dette gøres ved at klikke på tegnet "Plus" ud for "Ansøgningsrelateret filer"

Det første vi skal gøre, er at vælge ”Vælg filer”, herefter kan de ønskede filer markeres til upload. Når filerne i listen ser korrekt ud, vælger man knappen ”Upload”. Alternativt ”Annuller” for at fortryde. Krydset vil fjerne den pågældende fil

### Historik

Det er altid muligt at se historikken på en ansøgning. Dette gøres ved at klikke på + ved "Historik".

## Behandlet

Den midterste sektion viser information om selve bookingen i forhold til ansøgningen. Hvis ønsket kan oplysningerne ændres og gemmes på knappen ”Gem oplysninger”.

![Godkendt ansøgning](/assets/documentation/application-detail-booking-details.png)

Alle spørgsmål kan man “cykle” igennem ved at benytte TAB-knappen på tastaturet. Man kan bevæge sig tilbage med SHIFT+TAB-knapperne. Når et bestemt spørgsmål er markeret, kan man vælge forskellige svar med piletasterne.
Befordring henter informationer omkring kørslen og beregner priser i henhold til offentlig transport og kørsel med km-godtgørelse for kørsel i egen bil.

Ansøgningen kan flyttes fra stadiet ”Behandlet” til "Godkendt” på en meget simpel måde. Der skal blot indtastes et godkendt beløb og herefter klikke på knappen "Gem betaling og godkend".
Ønsker man at afvise ansøgningen eller sende den tilbage til afdelingen, benyttes henholdsvis knappen "Afvis" eller "Tilbage til Modtaget". Begge knapper kræver en begrundelse.

I stedet for at indtaste godtgørelsesbeløb, kan man nøjes med at klikke på et af de to beløb, som løsningen viser ovenfor. Gør man det, vil det beløb, man klikker på, automatisk blive overført til feltet ”indtast beløb”.

![Godkendt ansøgning](/assets/documentation/application-detail-payment.png)

## Godkendt

I nederste er der et ”Informationskort” som viser beløbet der blev godkendt i stadiet "Behandlet"

![Godkendt ansøgning](/assets/documentation/application-detail-payment-detail.png)

Når en ansøgning er gået fra stadiet "Behandlet" til "Godkendt", kan vi stadig se alle svarene men ikke længere ændre dem. Dette indikeres med den grå baggrund på alle felterne

![Godkendt ansøgning](/assets/documentation/application-detail-approved.png)

Hvis alt er korrekt, vil den automatisk sende ansøgningerne til betaling om natten. Nøjagtig som tidligere stadie kan ansøgningen også her afvises eller sendes tilbage til forrige stadie.

## Afvist

Hvis en ansøgning skal afvises, skal dette begrundes. En afvisning kan ikke gennemføres uden begrundelse.

![Godkendt ansøgning](/assets/documentation/application-detail-reject.png)

Når en sag er afvist, kan sagen findes, ved at foretage en [søgning](/dokumentation/kontrolpanelet#søgning) på patientens CPR-nr

Afvist stadiet er meget simpelt. Vi kan, på samme måde som "Godkendt", ikke ændre i nogle svar (alle felter er markeret grå).
Det er dog muligt at sende sagen tilbage til behandling igen. Gør man det, skal dette begrundes.

På ansøgningen kan man se, hvilket afslagsbrev, der vil blive sendt til patienten. (nederst til venstre, hvor det også er muligt at slette brevet, ved at trykke på skraldespanden.)
