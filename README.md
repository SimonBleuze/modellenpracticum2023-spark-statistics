# Modellenpracticum 2023 - Onderzoek statistiek van vonkjes in kabelmoffen 

Sander Rieken

### Achtergrond
De meeste storingen in het ondergrondse stroomnet vinden plaats door defecte kabelverbindingstukken (moffen). Om deze storingen te voorkomen gebruikt Alliander "Smart Cable Guard" (SCG). Dit systeem meet partiele ontladingen (vonkjes) in kabels en moffen. Vaak gaan deze vooraf aan een storing, waardoor de mof preventief verwijderd kan worden. Dit levert een grote hoeveelheid data op waar algoritmes en modellen nodig zijn om deze te verwerken.  

### Doel van de opdracht 
Voorafgaand aan een storing meet SCG grote concentraties (clusters) aan ontladingen. Van elke ontlading is de locatie op de kabel (in meter) , en de grootte van de ontlading (in picocoulombs) bekend. Bij Alliander zijn verschillende algoritmes ontwikkeld om deze clusters te analyseren. Er zijn echter nog veel vragen over de statistische verdeling van de ontladingsgroottes. We verwachten dat deze gebruikt kan worden om beter te voorspellen hoe snel de ontladende mof zal storen. 

### Concreet hebben we de volgende vragen: 
* Welke statistische verdeling past goed bij de empirische verdeling van de groottes van de ontladingen?
* Is dit altijd dezelfde verdeling? Hoe goed past de verdeling op de data?
* In de data liggen soms meerdere verdelingen over elkaar. Hoe zijn deze goed te scheiden?
* Hoe verandert de verdeling of de parameters van de verdeling in de tijd in de aanloop naar een storing of een uitdoving van de ontladingen? 

### Praktische zaken 
* Voor deze opdrachten zullen we een github repository ter beschikking stellen met daarin de benodigde data van een aantal circuits, en voorbeeldcode hoe deze te gebruiken.
* We verwachten dat de code in Python wordt aangeleverd.
