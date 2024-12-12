# Het model

Het 5 sterren-model is een hulpmiddel waarbij je per ster de transparantie over een algoritme vergroot. Met elke ster bied je de burger steeds meer de mogelijkheid om zelf te zien en beoordelen of een algoritme op een verantwoorde manier wordt ingezet. Dit begint bij het publiceren van informatie om te laten weten dát en waarvoor er een algoritme wordt gebruikt (**Gepubliceerd**). Vervolgens wordt het algoritme verder beschreven (**Uitgelegd**) en aangetoond dat het grondig is getest (**Gecontroleerd**). Om mensen echt zelf een beeld te kunnen laten vormen van de werking van het algoritme kunnen mensen experimenteren met in- en output (**Testbaar**) of de volledige broncode doorgronden (**Open**). Een uitgebreidere toelichting op deze stappen wordt hieronder gegeven.

![Het 5 sterren-model is gevisualiseerd als 5 oplopende tredes. De tredes zijn: gepubliceerd, uitgelegd, gecontroleerd, testbaar en open.](./img/5sterren-model.svg "Het 5 sterren-model")_****_Afbeelding 1:_** _Het 5 sterren-model bestaat uit de sterren Gepubliceerd, Uitgelegd, Gecontroleerd, Testbaar en Open._

## Toelichting op de 5 sterren

Het is belangrijk om het 5 sterren-model niet als een checklist of een uitputtend overzicht te zien, maar als handvatten om na te denken over welke informatie waardevol is om te delen. Het kan per algoritme verschillen waar dat precies uit bestaat.

### **1** **★** **GEPUBLICEERD**

**“Publiceer (online) wat het algoritme zou moeten doen”**

De eerste ster wordt behaald wanneer er informatie over het algoritme en de toepassing publiek beschikbaar is. Bijvoorbeeld in het Algoritmeregister. Dat betekent dat er een beschrijving is gegeven van de algemene kenmerken van het algoritme, die minimaal bestaat uit:

- Een beschrijving van het doel/de functie van het algoritme;

- Een beschrijving van de rol van het algoritme in relatie tot het proces waarin het gebruikt wordt;

- Een (gemotiveerde en toegelichte) classificatie van de impact van het algoritme.

Met deze informatie ben je transparant over het feit dát er een algoritme wordt gebruikt, waarom en waarvoor het wordt ingezet en hoe impactvol het algoritme is.

Ook is het bij deze stap interessant om na te denken over de vraag of, en zo ja, hoe en wanneer, iemand geïnformeerd moet worden over dit algoritme. Bij een chatbot moet bijvoorbeeld meteen aan gebruikers duidelijk worden gemaakt dat zij te maken hebben met een bot. Daarbij kan ook naar extra informatie worden verwezen in het Algoritmeregister. En als het algoritme wordt gebruikt in een besluitvormingsproces, kan er bijvoorbeeld een link naar deze publicatie worden opgenomen bij het genomen besluit.

### **2** **★** **UITGELEGD**

**“Beschrijf wat er is gedaan om ervoor te zorgen dat het algoritme doet wat het moet doen**

Op dit niveau wordt uitgelegd hoe het algoritme werkt en hoe ervoor is gezorgd dat het goed werkt. Denk hierbij bijvoorbeeld aan de volgende onderdelen:

- Een beschrijving van de werking van het algoritme; bijvoorbeeld door middel van een stroomschema van de input en output gedurende het proces en de daarbij gehanteerde (reken)regels;

- Beschrijving van de data die het algoritme gebruikt, of waarop het is getraind;

- Beschrijving van de nauwkeurigheid van het model en hoe er met bias om wordt gegaan;

- Welke maatregelen er zijn genomen om (maatschappelijke) risico’s te mitigeren;

- Wie of welke partijen verantwoordelijk zijn voor toezicht of onderhoud.

Het eerste punt kan in het algemeen worden uitgelegd, maar wanneer daar sprake van is, is het ook belangrijk om dit op individueel niveau uit te kunnen leggen. Zoals uit het burgerpanel ook bleek, willen mensen graag kunnen begrijpen op basis van welke informatie (input) een beslissing (output) tot stand is gekomen. Je kan bijvoorbeeld op het niveau van individuele burgers een dossier bijhouden van besluiten waarbij een algoritme is toegepast, met daarin een overzicht van welke gegevens zijn gebruikt, tot welke output dat heeft geleid en waarom die output het besluit rechtvaardigt. Zo krijg je als burger de mogelijkheid om het proces te begrijpen en te controleren of de gegevens kloppen.

### **3** **★** **GECONTROLEERD**

**“Deel resultaten die laten zien dat het algoritme doet wat het moet doen”**

Op dit niveau wordt niet alleen beschreven wat er gedaan is om te zorgen dat het algoritme doet wat het moet doen, maar kan dit ook aangetoond worden. Hierbij worden resultaten gedeeld die laten zien dat het algoritme “goed” en “eerlijk” werkt. Dit kan bijvoorbeeld aangetoond worden door het delen van:

- Auditresultaten;

- Monitoringsdata;

- Resultaten van ethische toetsing (bijv. van een eventuele ethische commissie, of een IAMA-traject (Impact Assessment Mensenrechten en Algoritmes);

- Hoe het algoritme getest en gevalideerd is en wat daarvan de resultaten zijn;

- Andere resultaten van de “checks en balances” die onderdeel vormen van de life-cycle.[[19]](#_ftn19)

Onder experts werd dit niveau vaak genoemd als het **minimale** transparantieniveau dat een overheidsalgoritme zou moeten hebben. Ook bij het burgerpanel (oktober 2024) kwam het belang van een (extern) gecontroleerd en gevalideerd algoritme naar voren als essentieel voor vertrouwen van burgers in de overheid.

Soms kan vanwege privacy of veiligheid niet alles van een (interne) audit gedeeld worden. Toch is dat geen excuus om nooit 3 sterren te kunnen behalen - het is geen ‘alles of niets’-transparantie. Resultaten van assessments kunnen geanonimiseerd of samengevat in een publieksversie worden gedeeld. Het belangrijkste is dat je kan laten zien hoe je het algoritme hebt getest, wat je daarin hebt meegenomen, wat de uitkomsten waren en welke eventuele maatregelen of vervolgstappen je aan die uitkomsten hebt gekoppeld. Het aantonen van een gecontroleerde werking helpt bij het opbouwen van extern vertrouwen in de werking en toepassing van een algoritme.

### **4** **★** **TESTBAAR**

**“Maak het mogelijk het algoritme te testen”**

Op dit niveau kunnen belanghebbenden zelf het algoritme gaan testen. Mensen kunnen dan zelf inzien welke output er geleverd wordt bij welke input. Dit kan bijvoorbeeld gerealiseerd worden met:

- Een API waarmee resultaten opgevraagd kunnen worden;

- Een “mock-up” systeem;

- Test-data, eventueel “synthetisch” (niet de daadwerkelijk gevoelige data maar een vergelijkbare neutrale set).[[20]](#_ftn20)

  
Hiermee wordt het algoritme en de werking tastbaar en daarmee ook _test_baar. Dat is een voorwaarde om een open gesprek te kunnen voeren over waarom het algoritme tot bepaalde uitkomsten komt, of deze uitkomsten wenselijk zijn en (dus) of de toepassing van het algoritme in een bepaald proces verantwoord en gerechtvaardigd is.

Het uitvoerig testen van een algoritme vereist technische kennis. Dit niveau is dan ook meer gericht op experts die bijvoorbeeld onderzoek willen doen naar het algoritme, of mogelijke biases. Toch is het ook denkbaar om burgers op een laagdrempelige manier te laten experimenteren met een algoritme. Bijvoorbeeld door het in een eenvoudig systeem, of via een website, mogelijk te maken om zelf te kijken welke uitkomst je krijgt wanneer je bepaalde gegevens invoert. Vergelijkbaar met online tools die alvast een inschatting kunnen geven over of je recht hebt op een toeslag,[[21]](#_ftn21) of hoe kansrijk je VOG-aanvraag is.[[22]](#_ftn22)

### **5** **★** **OPEN**

**“Stel (de ontwikkeling van) het algoritme volledig open”**

Op dit niveau is het algoritme volledig open. De code, data, beheersmaatregelen en ontwerpkeuzes zijn volledig inzichtelijk, uiteraard op een manier die de privacy van betrokkenen niet aantast of voor onveilige situaties zorgt. De maximale openheid is bedoeld om experts of toezichthoudende partijen de mogelijkheid te geven om het algoritme volledig te doorgronden. Concreet kan dit bijvoorbeeld door middel van:

- Het beschikbaar stellen van de broncode in combinatie met contextuele informatie, zoals een “_model card_”;[[23]](#_ftn23)

- Het beschikbaar stellen van (trainings/test)data.

- Bij de ontwikkeling en toepassing van het algoritme nadrukkelijk kiezen voor een open, participatief proces, zodat diverse perspectieven worden meegenomen.

Dit niveau is wellicht niet voor ieder algoritme volledig haalbaar. Daar kunnen veel verschillende redenen voor zijn. Maar zelfs als volledige openheid niet mogelijk is, dan kunnen bepaalde elementen uit dit niveau nog steeds haalbaar zijn en worden gerealiseerd. Des te meer openheid en transparantie rond een algoritme, des te groter de bijdrage aan het beter controleerbaar maken van besluitvormingsprocessen die overheidsorganisaties inzetten. Daarnaast kan het innovatie bevorderen en zelfs tips of verbeteringen van de code opleveren. Dit is ook in lijn met het open source beleid binnen de overheid.[[24]](#_ftn24) Bovendien kwam uit het burgerpanel dat het betrekken van burgers (al dan niet experts) bij de ontwikkeling van algoritmes het vertrouwen vergroot.

## Referenties

[[19]](#_ftnref19) Zoals de [Z-Inspection methode](https://ieeexplore.ieee.org/document/9380498 "https://ieeexplore.ieee.org/document/9380498"), waarmee bij de overheid al wordt [geëxperimenteerd](https://www.rijksorganisatieodi.nl/rijks-ict-gilde/mycelia/pilot-kunstmatige-intelligentie "https://www.rijksorganisatieodi.nl/rijks-ict-gilde/mycelia/pilot-kunstmatige-intelligentie").

[[20]](#_ftnref20) Zie: [https://www.tno.nl/en/technology-science/technologies/synthetic-data-secure-learning-from/](https://www.tno.nl/en/technology-science/technologies/synthetic-data-secure-learning-from/)

[[21]](#_ftnref21) Zie: [https://www.belastingdienst.nl/wps/wcm/connect/nl/toeslagen/content/hulpmiddel-proefberekening-toeslagen](https://www.belastingdienst.nl/wps/wcm/connect/nl/toeslagen/content/hulpmiddel-proefberekening-toeslagen "https://www.belastingdienst.nl/wps/wcm/connect/nl/toeslagen/content/hulpmiddel-proefberekening-toeslagen")

[[22]](#_ftnref22) Zie: [https://vogcheck.justis.nl/](https://vogcheck.justis.nl/ "https://vogcheck.justis.nl/")

[[23]](#_ftnref23) Bedacht door Margaret Mitchell, voorheen ethicus bij Google: [https://arxiv.org/abs/1810.03993](https://arxiv.org/abs/1810.03993 "https://arxiv.org/abs/1810.03993")

[[24]](#_ftnref24) Zie: [https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/open-source/beleid/](https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/open-source/beleid/ "https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/open-source/beleid/")
