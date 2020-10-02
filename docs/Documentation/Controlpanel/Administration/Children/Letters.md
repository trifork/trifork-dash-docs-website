---
layout: default
title: Breve
nav_order: 2
parent: Administration
grand_parent: Kontrolpanelet
permalink: dokumentation/kontrolpanelet/administration/breve
last_modified_date: '2020-09-22'
---

# Breve

Brevene bruges til at sende ud til borgerne ved afslag, tilsagn eller ved en regulering.
Brevene skal være i formatet `.docx`(Word fil).

Ved upload af et brev foretages der en validering af nøgleordene i brevet og de definerede nøgleord i brevskabelonen. Vær opmærksom på, at du overskriver et eksisterende brev i brevskabelonen, når der uploades et nyt.


## Brevtyper

Når du skal definere et nyt brev, skal du starte med at vælge brevtype. Brevtypen har betydning for hvilke flettefelter, der er understøttet samt hvor systemet kan stille brevet til rådighed.
* Vælg brevtypen Betalt, når du vil definere et Tilsagnsbrev
* Vælg brevtypen Afslag, når du vil definere et Afslagsbrev
* Vælg brevtypen Korrektion, når du vil definere et efterreguleringsbrev.

## Nøgleord

Systemet kan dynamisk indsætte forskellige flettefelter, baseret på nøgleord.
For at indsætte det nyt nøgleord, skal du trykke på det grønne "plus".
Vælg Nøgleordstype og definer nøgleordet.

Det væsentligste her (dette gælder også når man opretter nye breve) at man får oprettet de rigtige nøgleord – de nøgleord, som er valgt som merge-felter i DOCX-filen (Word filen). Hvis ikke disse passer sammen, vil brevet ikke blive sendt.
