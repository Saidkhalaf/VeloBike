# Status 
### Waar staan we globaal?
- We zijn klaar met het maken van dimensies tabellen en waren bezig met het verbinden van de dimensies met het feit tabel
- De dimtabellen werden gemaakt in spark-warehouse folder
- De verbinding luktte voor 3 dimensies "DimCustomer,DimSlot, DimDate" maar voor de DimWeer nog niet!

### Wat loopt goed en minder goed ?
* Het maken van dimensies was goed gegaan 
* We hadden het moeilijk om DimWeer te maken en verbinden met de fact tabel wegens het lezen van JSON file en Zo soort ding hebben we nog nooit gezien!
* 

### Hoe verloop de samenwerking 
* De samenwerking was goed gegaan in het algemeen. We hebben goed met elkaar kunnen communiceren en elkaar helpen. 

### Progress per deel
* 65% 

### Vragen 
* Hoe kunnen we de JSON file van de DimWeer lezen?
* Hoe kunnen we de data halen van een JSON file?
* Moeten we incremantal maken voor de Fact tabel Als de Customer tabel?
****************************
# Na het eerste gesprek "07/10/2024"
### Feedback 
* Het maken van een refelctie.md file. 
* Taal aanpassen van de weer.csv file "Taal moet in een taal zijn Zowel Engels of Nederlands"
* Verwerk de namen van Spark-wearhouse folders om de dimensies tabels en fact tabel duidelijker te maken.
* SCD start en end maken voor de customer dimensie. 
* Incremental maken voor dimCustomer.
* De Incremantal moet ook geladen worden in het feit tabel.
* monotonically_increasing_id() toepassen ipv uuid() in dimCustomer
* De fact tabel moet alleen maar meetwaarden, sleutel en FK'S die verwijzen naar dimensies 

# Vragen Week 5 15/10/2024
* Hoe kan ik de start_time van rit halen in de weer Api responses dus "in the json files"
* Hoe kan ik met de dimweer en de Api responses van weer behandelen om alle twee te verbinden met het feit tabel, Of de bedoeling vaan een van hen !
* Moet ik de duration van ritten een apart query maken of gewoon vermelden in de select statemnet van het feit tabel.
* Hoe de afstand berekenen van een rit ! 
* Hoeveel procent moet klaar zijn tegen volgend week van de hele project ?
* Hoeveel procent moet klaar zijn tegen volgend week van de hele project ?

# V2 Status 
### Waar staan we globaal?
- S2 opdracht 1 is af en S1 moet nog de analyse vragen doen.
- We hebben de feedback na de eerste evaluatie aangepast op onze code.
- NoSql installatie is klaar en ElasticSearch Velo Forum met tekst functionaliteit is ook klaar.

### Wat loopt goed en minder goed ?
* Bij S1 hadden we het moeilijk om match te maken tussen de weathertime en de ridestarttime en we hebben veel tijd verloren voor niks om dit deelje aan te passen.
* Het werken met weather api was niet zo goed gelopen, misschien want we hebben geen enkele voorbeeld gekregen tijdens de lessen.
* Bij S2 was alles goed gelopen en hij is bijna klaar met zijn deeltje.

### Hoe verloop de samenwerking 
* De samenwerking was goed gegaan in het algemeen. We hebben goed met elkaar kunnen communiceren en elkaar helpen. 

### Progress per deel
* 90% bij Spark 
* 30% bij NoSql

### Vragen 
* Als alles wordt afgemaakt behalve een klein stukje van een opdracht, dan kunnen we een kans hebben om te slagen! Want we hebben nog veel te doen met andere vakken.

****************************
# Na het tweede gesprek "22/10/2024"
### Feedback
* startlockid != zipcode dus deze aanpassen
* in feit mag geen UNKNOWN want deze is string
* koppeling gebeurt in de csv file... logica moet in fact job staan.

# V3 Status 
### Waar staan we globaal?
- Alles af.

### Wat loopt goed en minder goed ?
* Alles was goed gegaan.

### Hoe verloop de samenwerking 
* De samenwerking was goed gegaan in het algemeen. We hebben goed met elkaar kunnen communiceren en elkaar helpen. 

### Progress per deel
* 100% bij Spark.

