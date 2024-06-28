# Bristfällig manual till GraphFromGoogleMaps 

För att du ska kunna tillverka andra grafer utifrån bilder för användning i labb 1.

## Installation

Packa upp zip-filen i en lämplig mapp. Starta programmet med
    
    java -jar GraphFromGoogleMaps.jar

## Öppna projektet

    File > Open project ...
Filen `sunsdvall.grp` är vad som ligger till grund för indatat i labb1. 

## Redigera noder

Du kan manuellt redigera befintliga noder i 

    Adjacency list > Show...

## Lägga till noder

För att skapa en ny nod använder du musen.  

- Klicka först på en tom punkt
på kartan. En blå linje visar rutten som beräknas. Den blå linjen är 
ett resultat av ett extremt sofistikerat AI. 
- Klicka därefter på en befintlig nod du vill ansluta till.
- Ange namnet på den nya noden i dropdownlistan. Namnet kan vara samma som andra noder. I labben finns det flera noder döpt storgatan.
- Ange namnet på den nya kanten under Name. Kantnamn bör vara unika.
- Kontrollera rimligheten hos den beräknade längden. Justera eller avbryt vid behov.
- En kant är vanligtvis dubbelriktad. Dvs i den exporterade kantlistan finns två inlagor. A -> B och B -> A.

*Om den blå linjen uppför sig illa kan man hålla ner [Skift]. Det avaktiverar AIn tillfälligt.*

*Det är ofta olämpligt att göra långa kanter. Om resultatet blir konstigt, gör kanten kortare.*

## Ta bort noder

Det finns inget sätt att ta bort noder. Spara ofta. Börja om om det går helt snett.

## Kalibrera bilden

Man vill ju att den exporterade grafen innehållet ett vettigt mått på vikterna. Välj

    Map -> Calibrate

- Dra upp en linje (visas som en rektangel) mellan två punkter du kan använda som längdreferens. 
- Skriv in de verkliga positionerna för de två punkter du angivit.



