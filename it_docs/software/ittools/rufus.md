# Rufus

## Wat doet Rufus

[Rufus](https://rufus.ie/) is een programma dat helpt bij het formatteren en aanmaken van opstartbare USB-flash-drives, zoals USB-sticks, USB-hd's etc...

Wij gebruiken Rufus voor het maken van onze Boot USB's voor de Image Tool

## Hoe maak je een USB met Rufus

<style>
  .rufus { width:auto ; height: 500px; float: right; margin left: 30px; margin-bottom: 30px; }
</style>
<img src="/images/rufus.png" alt="Rufus applicatie" class="rufus">
Wanneer je rufus opstart krijgen we het volgende scherm te zien.

Voordat het USB apparaat dat we klaarmaken geselecteerd kan worden moeten we in geavanceerde eigenschappen "USB-harde schijven weergeven" aanvinken. Dan selecteren we de USB in kwestie.
Hierna kan je via de knop "SELECTEREN" hit ISO bestand van de boot kiezen.

Voordat we de installatie hiervan starten zetten we de instelling voor Partitie-indeling op de optie "MBR" dit hebben we nodig om de USB nog in meerdere partitie's te splitsen.
Ken het Volumelabel "Boot" toe en klik op "Starten"

Wanneer de USB geinstalleerd is openen we schijfbeheer. Voor de stappen die we hierin doen heb je een admin user nodig.

We selecteren de USB met een rechtermuis klik en kiezen "Volume Verkleinen". geef zeker nog wat extra vrije ruimte aan het orginele stuck.
Hierna geven we een rechterklik aan de nu niet toegeweze ruimte die is vrijgekomen en selecteren "Nieuw eenvoudig volume".

Ken hieraan de helft van het vrije volume toe en geef het label "Images" en bestandsysteem "exFAT"
Hierna maken we van de overige opslag een tweede "Nieuw eenvoudig volume" met het label "Bestanden" en bestandsysteem "exFAT" 