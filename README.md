# Inhoud
[Les 1: Print & Variabelen](#Les-1-Print--variabelen)

[Les 2: Je eerste tekening](#Les-2-Je-eerste-tekening)

[Les 3: Input en datatypes ](#Les-3-Input-en-datatypes)



# Computationeel denken: Python

# **Les 1: Print & variabelen**

### De print functie

Met Python is het mogelijk om tekst en getallen op het scherm te tonen. Dat doe je met de functie print(). Deze functie "print" gewoon de informatie die je wilt op het scherm.

    print("Dit komt dus op het scherm terecht.")
    print("We gaan nu een paar sommetjes doen:")
    print(230-21)
    print(78-2+6)
    print(78-2*6)

Zoals je ziet kun je ook berekeningen tussen de haakjes van de print()-functie zetten. Let er wel op dat de voorrangsregels van de wiskunde ook gelden voor programmeertalen: de * en de / gaan dus vóór de + en de -.

Er bestaat iets als een **string**. Een string is een rij van tekens (karakters). Een teken is een letter (zoals ‘a’, ‘B’), nummer (‘0’, ‘2’), symbool (‘#’, ‘^’, ‘}’), enz. en kan gebruikt worden om allerlei soorten informatie in op te slaan. Vaak is dit dus gewoon een stukje tekst wat iemand op het scherm wil printen.

***'string'** betekent in het Engels touw of draad. Het is dus een touw met karakters er aan.*

### Opgave 1:

Schrijf een programma dat met de print() functie “Hello, world” op het scherm zet.

### Opgave 2:

Schrijf een programma dat met de print() functie de volgende boodschap op het scherm zet:

Welkom bij mijn geweldige programma! We gaan allemaal toffe dingen laten zien.

Dit doen we met behulp van de print()-functie. ^_^


### Variabelen

Vaak wil je in je programma tijdelijk gegevens bewaren. Dit doe je met ***variabelen***. **Een variabele kun je zien als een emmer met een label erop**. Je kunt er iets in zetten en je kunt er iets uithalen. Hieronder zie je een stukje code met ernaast een plaatje waarop te zien is wat er gebeurt:

    a = 20
    b = 15
    c = "hallo"

Je kun nu doen:

    print(c)

of:

    print(a+b)


![](afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.003.png)

Je ziet dus dat er nu drie emmers zijn. Elke emmer heeft een naam/label en een inhoud. In het begin zijn alle emmers leeg. Maar na de drie regels van hierboven verandert de zaak: 

- In de emmer met als naam a komt namelijk het getal 20 te staan. 
- In emmer b komt 15 te staan. 
- En in c komt de tekst "hallo" te staan.

We kunnen nu ook een vierde emmer genaamd d in het leven roepen. In die variabele kunnen we het verschil (min) tussen a en b berekenen en bewaren. Dat gaat zo:

![](afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.004.png)

    a = 20
    b = 15
    c = "hallo"
    d = a - b

    # d is 20 - 15 is 5

    print(d)

    # dit zal 5 uitprinten

We halen dus het getal 20 uit emmer a en we halen het getal 15 uit emmer b. Het verschil wordt vervolgens berekend en het antwoord komt in emmer d te staan.

Uiteindelijk zouden we ook de inhoud van de variabelen op het scherm kunnen tonen. Dat doen we natuurlijk met de functie print. Dit gaat zo:

    print(a)
    print(b)
    print(c)
    print(d)	


### Opdracht 3

Schrijf een programma waarbij je de volgende berekeningen doet in Python: 

    8483937 - 523455 
    23.22342 * 34309483 
    218739345 + 3498348

Stop de antwoorden in drie verschillende variabelen. Tel de drie antwoorden bij elkaar op en print het uiteindelijke antwoord.

### Namen van variabelen

De naam van een variabele kan je altijd zelf bepalen. Dus als je berekeningen wilt doen met je favoriete getal, kan je deze in een variabele stoppen met als naam bijvoorbeeld favoriete_getal. Dit is handig omdat je dan makkelijk kan bijhouden wat er in de variabelen zit. Noem je variabelen dus altijd op een logische manier! Kijk maar naar het volgende voorbeeld:

    favoriete_getal = 7
    print(favoriete_getal + 1)
    print(favoriete_getal)
    print(favoriete_getal * 2)
    favoriete_getal = 4 + 5
    print(favoriete_getal)
    print("favoriete_getal")

Zoals je kan zien zijn de eerste drie antwoorden van het programma (dit worden ook wel **outputs** genoemd) gewoon een wiskundesom die de inhoud van onze variabelen gebruikt. Daarna wordt er een verandering gemaakt in de variabele favoriete_getal. Er wordt een andere waarde aan de variabele gegeven, namelijk 4 + 5, dus 9. Je kan na het toewijzen van de waarde van een variabelen deze dus altijd ook nog later veranderen.

Bij de laatste output zien we iets vreemd. Doordat er " " om favoriete_getal stonden, wordt deze gezien als wat? Ja! Een **string**! Het is dus heel erg belangrijk om in je achterhoofd te houden of je iets wilt printen als een **string** of als een **variabele**. Als je de " " namelijk vergeet, gaat het programma zoeken naar een variabele met die naam. En als er dus geen variabele toegewezen is kan je hierdoor een foutmelding (oftewel een *error*) krijgen.

### Strings aan elkaar plakken (concatenation)

Bij de vorige opdrachten heb je steeds een aparte string geprint op het scherm. Nu bestaat er ook iets als string concatenation, waarin je twee strings samen kan voegen. Concatenation is een Engels woord voor “aaneenschakeling”, en in python is dit ontzettend makkelijk: Je plakt twee string aan elkaar vast met een “+” of een “,”! Probeer maar:

    leerling_naam = "Joop"
    print("Hallo, dit is deel een!" , "En dit is deel twee!")
    print("Jouw naam is " + leerling_naam)

    kledingstuk = "broek"
    print("Wat heb je een mooie " + kledingstuk, "aan.")

​

### Opgave 4

Schrijf steeds een programma waarin je de gegeven variabele op de goede plek in de string gebruikt zoals in het voorbeeld.

    naam = Lotte 
    <naam> heeft pannenkoeken gegeten! 
    naam = Kees 

    De kat van <naam> heeft een muis gevangen. 

    naam = Bas 
    tijd = nacht 

    De parkiet van <naam> heeft hem de hele <tijd> wakker gehouden. 



### Opgave 5

Print bij deze opdracht de komende drie woorden in alle volgordes die er maar zijn dus bijvoorbeeld: ‘Niezen Kikkers Blij’ of 'Knikkers Niezen Blij'. Hint, er zijn 6 verschillende volgordes.

    speelgoed = "knikkers" 
    gevoel = "blij" 
    werkwoord = "niezen" 
    print(speelgoed + gevoel + werkwoord) 


### Opdracht 6

Schrijf je eigen kleine verhaaltje.

Gebruik een **variabele** voor de naam van de hoofdpersoon zodat je makkelijk de hoofdpersoon kunt wijzigen. 

**Voorbeeldverhaal**: Henk is een blije jongen. Hij gaat op de fiets naar school. Als Henk op school is gaat hij vrolijk naar de les. Einde!

**Code die hier bij hoort:** 

    naam = "Henk" 
    print(naam + " is een blije jongen.") 
    # denk aan de extra spatie! 

    print("Hij gaat op de fiets naar school.") print("Als " + naam + " op school is gaat hij vrolijk naar de les.") 

    print("Einde!")


### Foutmeldingen (errors)

Een ‘error’ is een foutmelding. Op errors gaan we later dieper in, maar voor nu is het handig om te weten dat je bij bijvoorbeeld de volgende code:


    getel = 4 
    print(getal + 1)

iets kan krijgen als:

    Traceback (most recent call last): File "<stdin>", line 2, in <module>NameError: name 'getal' is not defined

Als je kijkt naar line 2 (regel 2) dan wordt daar een variabele met de naam **getal** gebruikt, terwijl deze dus niet bestaat of geen waarde toegewezen heeft gekregen. Je ziet dat er een spelfout is gemaakt in regel 1. Er staat **getel** in plaats van **getal**. Als je dat verandert verdwijnt de foutmelding.

**Veel voorkomende fouten**

Een error kun je bijvoorbeeld krijgen als:

- je de " " om een string ergens vergeten bent, 
- je variabelenaam verkeerd hebt gespeld
- je variabele nog niet een waarde hebt gegeven

Het kan ook zijn dat je de toewijzing andersom doet, zoals: 4 = x

Dan krijg je een error die eruit ziet als: 

    Traceback (most recent call last):
    In line 1 of the code you submitted: 4 = x ^ SyntaxError: can't assign to literal

Deze foutmelding houdt dan dus in dat je altijd eerst je variabelenaam moet noemen, en dan pas de inhoud ervan moet geven. In de geval verbeter je het dus door er van te maken: 

    x = 4 

In de toekomst gaan we dieper in op errors en hoe je problemen kunt oplossen. Maar het is handig dat je hier alvast wat over hebt gelezen, in het geval dat je straks wat schrijft en opeens een error krijgt. Ze zien er altijd heel ingewikkeld uit, maar als je hier eenmaal handig in wordt valt het best mee! Neem gewoon rustig je tijd, en bekijk wat er staat en neem je code dan nog even door.

### Opgave 8

Run de volgende codes, en los de errors op:

    kosten_lolly = 30
    kosten_appel = 60
    kosten_banaan = 100
    geld_op_zak = 230

    geld_over = geld_op_zak - kosten_appel - kosten_banaan - kosten_lolly

    print geld_over

    katten = 4
    honden = 8
    dolfijnen = 2
    cavias = 3
    chinchillas = 1

    aantal_dieren = katten + honden + dolfijnen + cavias + hamsters + chinchillas
    print(aantal_dieren)

    # Hoe vaak moet nicky heen en weer lopen om drinken voor haarzelf en al haar
    # vriendinnen te halen als zij maar drie flesjes per keer mee kan nemen?

    1 = nicky
    14 = vriendinnen
    nicky + vriendinnen = totaal_hoeveelheid_mensen
    3 = flessen_per_keer
    totaal_hoeveelheid_mensen / flessen_per_keer = hoeveel_keer_lopen
    print(hoeveel_keer_lopen)

    peren = "appels"
    appels = "peren"
    wie_de = "Je moet geen "
    kaatst_kan_hem = " met "
    terug_verwachten = " vergelijken."

    print(wie_de + peren + kaatst_kan_hem + appels + terug_verwachten)


# **Les 2: Je eerste tekening**


### Tekenen in Python
Ons eerste programma ziet er als volgt uit:

    import turtle
    turtle.shape("turtle")     
    turtle.forward(100)
    turtle.right(90)
    turtle.forward(100)
    turtle.right(90)
    turtle.forward(100)
    turtle.right(90)
    turtle.forward(100)
    turtle.right(90)

### Opdracht 1

**Vooruit** met turtle:

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.005.png)

​
Als je wilt tekenen met turtle, dan moet je dat op de allereerste regel van je programma aangeven. Dit doe je door de regel import turtle op te schrijven. De turtle kijkt altijd in het begin naar rechts.

Met de opdracht turtle.forward(100), gaat de turtle dan 100 stappen vooruit. Zie het plaatje hieronder.** 

![](afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.006.png)

​En met de opdracht turtle.backward(100), gaat de turtle 100 stappen achteruit.

**Draaien**

De turtle heeft altijd een bepaalde richting. En als hij beweegt, dan beweegt hij ook die richting op. Je kunt echter de richting veranderen door het commando turtle.right() of turtle.left() in te geven.** 

![](afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.007.png)

​
Als je turtle.right(90) ingeeft, dan draait de turtle 90 graden naar rechts. En als je turtle.right(180) ingeeft, dan draait hij zich om. 

![](afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.008.png)

​
### Opdracht 2

Maak de volgende figuren:

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.009.png)![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.010.png)


![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.011.png)

*Tip voor draaien*

*Let er wel op dat de draairichting altijd vanuit de huidige positie van de turtle wordt bepaald. In het onderstaande plaatje kijkt de turtle eerst naar beneden. Als je dan* turtle.right(90) *uitvoert dan draait de turtle dus 90 graden naar rechts toe!*** 

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.012.png)

Om het draaien duidelijk te maken hieronder nog een programma dat je in Python kan uitvoeren:

    import turtle
    turtle.shape("turtle")
    turtle.forward(50)
    turtle.right(45)
    turtle.forward(50)
    turtle.right(45)
    turtle.forward(50)
    turtle.right(90)
    turtle.forward(90)

**​**
**

### Opdracht 5
Maak voor de figuren hieronder een programma waarbij de turtle dat figuurtje tekent. De afmetingen mag je zelf bepalen.** 

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.013.png)

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.014.png)


### Opdracht 6
Maak ook vier programma's waarmee je de volgende figuren kan tekenen.

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.015.png)


![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.016.png)

### Opdracht 7 

Schrijf een programma waarmee je het onderstaande kan tekenen:

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.017.png)

Je kunt het bovenstaande figuurtje tekenen door slechts gebruik te maken van de functie turtle.forward en turtle.right. Zorg ervoor dat je hetzelfde figuurtje maakt, maar dan alleen door uitsluitend gebruik te maken van deze twee functies.

### Opdracht 8 - Mooie vorm

Teken volgende figuur:

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.018.png)
### Opdracht 9 - Huis 
Teken nu een huis met de turtle. Je huis zou er zo uit kunnen zien (de lengte van de zijden mag je zelf bepalen):** 

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.019.png)

![](/afbeeldingen/Aspose.Words.51dfa2ac-5f97-41fd-bd03-6432528b2b53.020.png)



# **Les 3: Input en datatypes**

### **Interactieve programma's met de input functie**

Met de print functie kun je gegevens op het scherm printen. Maar wat als je nou wilt dat de gebruiker iets kan invoeren? Heb je daar ook iets voor? Jazeker! De input()-functie.

    naam = input("Hoe heet je?")
    print("Hallo! Je naam is als volgt: ")
    print(**naam**)

Je ziet dat je programma wacht op invoer. Als je iets intypt en eindigt met enter dan gaat het programma verder. Op deze manier kan je dus een programma schrijven dat reageert op de antwoorden van zijn gebruiker!*: Je moet het resultaat van de input()-functie wel eerst in een variabele zetten, zodat dit later gebruikt kan worden.*

De regels tekst (strings) worden nu onder elkaar geprint maar je kunt ook string aan elkaar plakken met + (concatenation):

    naam = input("Hoe heet je?")
    woonplaats = input("Waar woon je?")
    print("Hallo " + naam + ", je woont in " + woonplaats + ".")

### Opgave 1:

Schrijf een programma dat de voornaam van de gebruiker opvraagt met de functie input. Vervolgens wordt de gebruiker gegroet met 'Hallo, [en hier komt de voornaam van de gebruiker]!'. 

Hint: denk aan concatenation!

### Opgave 2:

Schrijf een programma dat de gebruiker vraagt om een zelfstandig naamwoord (bv. boom, huis, kast), een bijvoeglijk naamwoord (bv. groot, vies, vervelend) en een infinitief van een werkwoord (bv. lopen, schrijven, eten). 

Vul de ingevoerde vervolgens in, in de onderstaande zin en zet het resultaat op het beeld. Vond je ooit een zo ontzettend dat je het voortdurend opnieuw wilde ? Bijvoorbeeld: Vond je ooit een boom zo ontzettend mooi dat je het voortdurend opnieuw wilde knuffelen?

### Opgave 3:
Zoek je verhaal op die je bij lesbrief 1 hebt gemaakt. Maar vraag nu de naam van de hoofdpersoon aan de gebruiker!

**Voorbeeldverhaal:** Hoe heet je? Henk

Henk is een blije jongen. Hij gaat op de fiets naar school. Als Henk op school is gaat hij vrolijk naar de les. Einde!

Code die hier bij hoort:

    naam = input("Hoe heet je?") 
    print(naam + " is een blije jongen.") 
    # denk aan de extra spatie! print("Hij gaat op de fiets naar school.") 
    print("Als " + naam + " op school is gaat hij vrolijk naar de les.") 
    print("Einde!")
    
### Opgave 4
Schrijf een programma dat om drie woorden vraagt en vervolgens die drie woorden in alle zes mogelijke volgordes weer naar het scherm schrijft. Je moet zes keer een print commando geven!

### Van strings naar getallen
Bekijk eens het onderstaande programma:

    getal1 = input("Geef een getal")
    getal2 = input("Geef nog een getal")
    som = getal1 + getal2
    print("De som van getal1 en getal2 is")
    print(som)

Je zou denken dat je hiermee een optelprogramma hebt gemaakt, maar dat valt vies tegen! Probeer maar eens een paar getallen op te tellen en kijk goed naar het resultaat. Probeer het pogramma uit.

Wat gaat hier nou mis? Als je voor het eerste getal 22 kiest en voor het tweede getal 56, dan is het resultaat 2256. Wat is hier misgegaan? 

Python heeft de twee 'getallen' aan elkaar vastgeplakt. Dit doet hij, omdat hij denkt dat je twee strings aan elkaar wilt vastplakken (concatenation!). Net alsof je "**programmeren is** " en "**fun**" aan elkaar wilt vastplakken. Maar wij willen niet dat Python die twee getallen aan elkaar vastplakt, maar dat hij ze bij elkaar optelt! Eigenlijk willen we dat Python de twee getallen ook echt als twee getallen gaat beschouwen. De vraag is: Hoe doen we dat? 

De input-functie is hier van belang. Die zegt altijd dat de invoer van de gebruiker als tekst moet worden beschouwd. Wij kunnen expliciet aangeven dat de invoer toch moet worden opgevat als een echt getal. Dit doen we door de functie int() te gebruiken. Dit ziet er als volgt uit:

    getal1 = int(input("Geef een getal"))
    getal2 = int(input("Geef nog een getal"))
    som = getal1 + getal2
    print("De som van getal1 en getal2 is")
    print(som)

Let vooral op het gebruik van de functie int()! int is een afkorting voor integer. Het is de Engelstalige benaming voor een geheel getal. Je zegt hier eigenlijk: Hetgeen dat de gebruiker invoert met de input functie moet worden opgevat als een getal.

### Opgave 5
Schrijf een programma dat vraagt om vier getallen. Tel de eerste twee getallen bij elkaar op, deel dat dan door het derde getal, en vermenigvuldig het met het vierde getal. Print vervolgens het antwoord op het scherm.

### Opgave 6
Schrijf een programma dat de gebruiker vraagt om vijf getallen en schrijf daarna het gemiddelde van die vijf getallen naar het scherm (niet afronden).
### Opgave 7

Schrijf een programma dat de gebruiker vraagt om het huidige jaartal en om het jaar waarin hij geboren is. Reken uit hoe oud de gebruiker is aan het eind van het huidige jaar (in hele jaren) en schrijf het antwoord naar het scherm.

### Types en type-casting
Inmiddels ben je al bekend met twee soorten informatietypes (datatypes), namelijk strings en int’s. Strings zijn een verzameling karakters die als het ware als een zin gebruikt worden door de computer. Een string is een type (soort) informatie waarvan de computer alles tussen de “” als een geheel behandeld. En net zoals dat een string een type informatie is, zijn er ook nog andere types. Een van de belangrijkste hiervan ken je nu ook al. De int wat dus staat voor integer, was een heel getal. Maar wat nou als je met decimale getallen wilt werken (getallen met een komma erin)? Hiervoor bestaat er nog een ander type informatie. Namelijk de float wat een getal is met nog cijfers achter de komma.

In het Engels gebruik je een '.' (punt) in plaats van een '.' (komma). Daarom schrijf je een getal 2,63 bij programma als 2.63

Deze laatste twee datatypes zijn heel erg belangrijk aangezien je er complexe berekeningen mee kan doen. Eerder deze les heb je al meerdere berekeningen gedaan met gehele getallen. Als je daarentegen met decimale getallen wilt werken heb je dus de floats nodig. Een paar voorbeelden van floats zijn:

    print(3.5 / 1.5)
    print(2.4 * 1.23)
    print(13 + 223.4)

Hierboven zie je dat er verscheidene berekeningen gedaan worden met floats. Als je met de input() functie werkt, wordt het belangrijk om hetzelfde trucje toe te kunnen passen als we eerder met de integers hebben gedaan. Als je namelijk niet expliciet het type informatie geeft aan de input() functie, gaat dit altijd als string behandeld worden. Maar als je het type int aan een float mee geeft krijg je hier een error van. Geef bij het volgende voorbeeld maar een float als input mee en kijk wat er gebeurt!

In het engels werken mensen met punten i.p.v. komma's.

Dus 3,4 is dan 3.4.

    x = int(input("Geef mij een getal"))
    y = int(input("Geef mij nog een getal!"))
    print (x+y)

Hierboven zie je dat er verscheidene berekeningen gedaan worden met floats. Als je met de input() functie werkt, wordt het belangrijk om hetzelfde trucje toe te kunnen passen als we eerder met de integers hebben gedaan. Als je namelijk niet expliciet het type informatie geeft aan de input() functie, gaat dit altijd als string behandeld worden. Maar als je het type int aan een float mee geeft krijg je hier een error van. Geef bij het volgende voorbeeld maar een float als input mee en kijk wat er gebeurt!

geef als input bij dit programma maar een float. 

In het engels werken mensen met punten i.p.v. komma's.

3us 3,4 is dan 3.4.

    x = int(input("Geef mij een getal"))
    y = int(input("Geef mij nog een getal!"))
    print(x+y)

Om dit op te lossen kan je dus simpelweg in plaats van de functie int() de float() functie gebruiken. Als je dit doet, wordt de input behandeld als float en kan je hier dus weer berekeningen mee maken met getallen achter de komma.

# Nu wordt de input als float behandeld en kan de berekening wel op deze manier!

    x = float(input("Geef mij een getal"))
    y = float(input("Geef mij nog een getal!"))
    print(x+y)

Het bovenstaande voorbeeld laat dus heel goed het verschil tussen float en int waardes zien. Bij berekeningen moet je hier dus goed op letten hoe je het in gaat voeren en wat voor antwoord je wilt krijgen. Verder kan het natuurlijk ook zo zijn dat je wilt dat een int of float als string behandeld wordt. Dit is namelijk nodig als je een variabele die een int of float bevat wilt printen. Een voorbeeld hiervan is het volgende:

soms wil je een int of float als string printen zodat het goed leesbaar is

en je duidelijk kan maken wat wat is.

    ​lievelings_getal = 5
    mooiste_float = 4.3
    print("Mijn lievelings getal is " + str(lievelings_getal))
    print("Maar de mooiste float is " + str(mooiste_float) + "!")
    print("Zo zie je dat je eerst een int of float om moet zetten naar string!")
    print("Anders krijg je de volgende error:")
    print("")
    print("als ik mijn lievelings getal zo print krijg je een error: " + lievelings_getal)

### Opgave 8
Bedenk wat de types zijn van de volgende tien dingen. Kies uit integer, float of string.

19 “3” 21.234 “Hoela hoepen” 24 * 21.4 29 / 3 “293.3” 25.1 + 5 2 / 3 * 9 8 + 30 / 10

Zoals je hierboven kan zien, maakt het erg veel uit hoe je de berekening invoert. Voor de volgende opdracht ga je hier zelf een programma voor schrijven:

### Opdracht 9
Schrijf een programma dat 2 of meer inputs vraagt, maak er een berekening mee en print het antwoord uit. In het programma moeten alle drie de datatypes voorkomen.

Als je even niet meer weet wat voor type iets heeft, bestaat er een functie die je hiervoor kan gebruiken. Als je namelijk type(variabele) gebruikt, zegt de computer wat het type is.

    x = 8
    print(type(x))
    print(type("hallo"))
    print(type(4.5))
