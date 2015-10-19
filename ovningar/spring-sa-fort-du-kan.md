# Spring så fort du kan

Detta spelet har ett enkelt mål; Ta dig över mållinjen först

Grundläggande delar
* Flytta figur med en tangent
* Rita en mållinje
* Ropa JAAA när figuren kommer i mål
* Återställ spelare
* Byt klädsel på figur

Flerspelarläge
* Flera figurer samtidigt
* Stanna båda figurerna när en har kommit i mål
* Räkna poäng för varje spelare
* Starta-nytt-spel-knapp

Avancerat
* Löpningen måste ske med varannat ben

## Grundläggande delar
### Flytta figur
För att figuren ska komma till mållinjen, så ska en tangent tryckas ner.  
Varje gång kommer figuren ett steg närmare mållinjen.

![Gå framåt](/images/blocks/spring-sa-fort-du-kan/ga-framat.png)

### Rita en mållinje
Figuren måste ha en målinje att springa över.  
Denna kan vi rita dit själva på bakgrunden.

![Rita en mållinje](/images/blocks/spring-sa-fort-du-kan/rita-en-mallinje.png)

### Ropa JAAA när figuren kommer över mållinjen
För att veta om figuren har kommit över mållinjen, så behöver vi på något sätt
säga "Om figurens `x-position` är högre än mållinjens `x-position`, så säger
jag JAAA".

Denna övning använder block från flera kategorier.  
Skriv gärna ut [detta dokument](https://docs.google.com/document/d/1TWWXtoiNGTc23qed5cwHx88KNNQPpuAAADPB_Syy8uw/edit?usp=sharing) och lämna ut det till eleverna, så de kan se alla kategorierna på en gång.  

Detta gör vi med ett "om"-block.  
![Om-block](/images/blocks/spring-sa-fort-du-kan/om-block.png)

I detta lägger vi in en "Större än"-operator som innehåller...  
![Större än](/images/blocks/spring-sa-fort-du-kan/storre-an.png)

.."x-positionen" på vår figur  
![x-position](/images/blocks/spring-sa-fort-du-kan/x-lage.png)

.. och x-positionen på mållinjen, som du hittar på detta sätt  
![xposition på
mållinje](/images/blocks/spring-sa-fort-du-kan/hitta-x-position-pa-mallinje.png)

Slutresultatet ser ut så här  
![Har sprungit över
mållinjen](/images/blocks/spring-sa-fort-du-kan/har-sprungit-over-mallinjen.png)

### Nollställ spelet
När figuren har kommit över mållinjen, så är spelet slut.   
För att börja ett nytt spel behöver figuren flyttas tillbaka till
startpositionen.

![Flytta tillbaka till
start](/images/blocks/spring-sa-fort-du-kan/nollstall-spelet.png)

### Få figuren att springa
För att få lite mer rörelse i spelet, så ska vi få figuren att se ut som den
springer.

Detta gör vi genom att "byta klädsel" på den. I grund och botten handlar det om
att växla mellan olika bilder för att skapa en illusion om att det rör sig.  
Precis som i tecknad film.

Se till att det finns två klädslar för figuren.  
![Klädslar till figuren](/images/blocks/spring-sa-fort-du-kan/valj-kladsel.png)


Lägg sedan in blocket "Nästa klädsel"  
![Nästa klädsel](/images/blocks/spring-sa-fort-du-kan/nasta-kladsel.png)

## Tvåspelarläge

* Ändra startposition för båda figurerna
* Båda ska ha en "återställ startposition"
* Ändra tangent så de inte använder samma
* sluta springa när någon går i mål => Variabel "Gått i mål"
  * ![Sluta
    spring](/images/blocks/spring-sa-fort-du-kan/har-gatt-i-mal-sluta-spring.png)
