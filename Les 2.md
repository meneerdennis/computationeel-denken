# Les 2: Je eerste tekening

### Tekenen in Python

Ons eerste programma ziet er als volgt uit:

import turtle

​

turtle.shape("turtle")

​

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

![](RackMultipart20240201-1-pogx9y_html_8daa1172279d88e2.png)

​

Als je wilt tekenen met turtle, dan moet je dat op de allereerste regel van je programma aangeven. Dit doe je door de regel import turtle op te schrijven. De turtle kijkt altijd in het begin naar rechts.

Met de opdracht turtle.forward(100), gaat de turtle dan 100 stappen vooruit. Zie het plaatje hieronder.

![](RackMultipart20240201-1-pogx9y_html_f54866edb3d5bc3c.png)

​En met de opdracht turtle.backward(100), gaat de turtle 100 stappen achteruit.

**Draaien**

De turtle heeft altijd een bepaalde richting. En als hij beweegt, dan beweegt hij ook die richting op. Je kunt echter de richting veranderen door het commando turtle.right() of turtle.left() in te geven.

![](RackMultipart20240201-1-pogx9y_html_559e2fca79bf2d4f.png)

​

Als je turtle.right(90) ingeeft, dan draait de turtle 90 graden naar rechts. En als je turtle.right(180) ingeeft, dan draait hij zich om.

![](RackMultipart20240201-1-pogx9y_html_c999355b6abc7033.png)

​

### Opdracht 2

Maak de volgende figuren:

![Afbeelding 12](RackMultipart20240201-1-pogx9y_html_b2444bc43de2eb3e.gif) ![Afbeelding 11](RackMultipart20240201-1-pogx9y_html_965f2ec340ef44d3.gif)

​​

![Afbeelding 10](RackMultipart20240201-1-pogx9y_html_fe022865c914478b.gif)

_Tip voor draaien_

_Let er wel op dat de draairichting altijd vanuit de huidige positie van de turtle wordt bepaald. In het onderstaande plaatje kijkt de turtle eerst naar beneden. Als je dan_ turtle.right(90) _uitvoert dan draait de turtle dus 90 graden naar rechts toe!_

![](RackMultipart20240201-1-pogx9y_html_6c2138e00ad1a7b3.png)

Om het draaien duidelijk te maken hieronder nog een programma dat je in Python kan uitvoeren:

import turtle

​

turtle.shape("turtle")

​

turtle.forward(50)

turtle.right(45)

turtle.forward(50)

turtle.right(45)

turtle.forward(50)

turtle.right(90)

turtle.forward(90)

​

### Opdracht 5

Maak voor de figuren hieronder een programma waarbij de turtle dat figuurtje tekent. De afmetingen mag je zelf bepalen.

![](RackMultipart20240201-1-pogx9y_html_fb395624183c389d.png)

![](RackMultipart20240201-1-pogx9y_html_10c08088692051ec.png)

### Opdracht 6

Maak ook vier programma's waarmee je de volgende figuren kan tekenen.

![](RackMultipart20240201-1-pogx9y_html_8ce53d4df1431686.png)

![](RackMultipart20240201-1-pogx9y_html_a4dbd39f0826ebe5.png)

### Opdracht 7

Schrijf een programma waarmee je het onderstaande kan tekenen:

![](RackMultipart20240201-1-pogx9y_html_87fdd373e59bd571.png)

Je kunt het bovenstaande figuurtje tekenen door slechts gebruik te maken van de functie turtle.forward en turtle.right. Zorg ervoor dat je hetzelfde figuurtje maakt, maar dan alleen door uitsluitend gebruik te maken van deze twee functies.

### Opdracht 8 - Mooie vorm

Teken volgende figuur:

![](RackMultipart20240201-1-pogx9y_html_5f29f4c555e46a1d.png)

### Opdracht 9 - Huis

Teken nu een huis met de turtle. Je huis zou er zo uit kunnen zien (de lengte van de zijden mag je zelf bepalen):

![](RackMultipart20240201-1-pogx9y_html_393581c6153b14ab.png)

![](RackMultipart20240201-1-pogx9y_html_5115ae1b395efc8f.png)

# Les 3: Input en datatypes

### **Interactieve programma's met de input functie**

Met de print functie kun je gegevens op het scherm printen. Maar wat als je nou wilt dat de gebruiker iets kan invoeren? Heb je daar ook iets voor? Jazeker! Deinput()-functie.

naam =input("Hoe heet je?")

print("Hallo! Je naam is als volgt: ")

print( **naam** )

Je ziet dat je programma wacht op invoer. Als je iets intypt en eindigt met enter dan gaat het programma verder. Op deze manier kan je dus een programma schrijven dat reageert op de antwoorden van zijn gebruiker!_: Je moet het resultaat van de input()-functie wel eerst in een variabele zetten, zodat dit later gebruikt kan worden._

De regels tekst (strings) worden nu onder elkaar geprint maar je kunt ook string aan elkaar plakken met + (concatenation):

naam =input("Hoe heet je?")

woonplaats =input("Waar woon je?")

print("Hallo "+naam +", je woont in "+woonplaats +".")

### Opgave 3:

Schrijf een programma dat de voornaam van de gebruiker opvraagt met de functie input. Vervolgens wordt de gebruiker gegroet met 'Hallo, [en hier komt de voornaam van de gebruiker]!'.

Hint: denk aan concatenation!

### Opgave 4:

Schrijf een programma dat de gebruiker vraagt om een zelfstandig naamwoord (bv. boom, huis, kast), een bijvoeglijk naamwoord (bv. groot, vies, vervelend) en een infinitief van een werkwoord (bv. lopen, schrijven, eten).

Vul de ingevoerde vervolgens in, in de onderstaande zin en zet het resultaat op het beeld. Vond je ooit een zo ontzettend dat je het voortdurend opnieuw wilde ? Bijvoorbeeld: Vond je ooit een boom zo ontzettend mooi dat je het voortdurend opnieuw wilde knuffelen?

### Opgave 5:

Zoek je verhaal op die je bij lesbrief 1 hebt gemaakt. Maar vraag nu de naam van de hoofdpersoon aan de gebruiker!

**Voorbeeldverhaal:** Hoe heet je? Henk

Henk is een blije jongen. Hij gaat op de fiets naar school. Als Henk op school is gaat hij vrolijk naar de les. Einde!

Code die hier bij hoort:

naam = input("Hoe heet je?") print(naam + " is een blije jongen.") # denk aan de extra spatie! print("Hij gaat op de fiets naar school.") print("Als " + naam + " op school is gaat hij vrolijk naar de les.") print("Einde!")

### Opgave 5

Schrijf een programma dat om drie woorden vraagt en vervolgens die drie woorden in alle zes mogelijke volgordes weer naar het scherm schrijft. Je moet zes keer een print commando geven!

### Van strings naar getallen

Bekijk eens het onderstaande programma:

getal1 =input("Geef een getal")

getal2 =input("Geef nog een getal")

som = getal1 + getal2

print("De som van getal1 en getal2 is")

print(som)

Je zou denken dat je hiermee een optelprogramma hebt gemaakt, maar dat valt vies tegen! Probeer maar eens een paar getallen op te tellen en kijk goed naar het resultaat. Probeer het pogramma uit.

Wat gaat hier nou mis? Als je voor het eerste getal 22 kiest en voor het tweede getal 56, dan is het resultaat 2256. Wat is hier misgegaan?

Python heeft de twee 'getallen' aan elkaar vastgeplakt. Dit doet hij, omdat hij denkt dat je twee strings aan elkaar wilt vastplakken (concatenation!). Net alsof je " **programmeren is**" en " **fun**" aan elkaar wilt vastplakken. Maar wij willen niet dat Python die twee getallen aan elkaar vastplakt, maar dat hij ze bij elkaar optelt! Eigenlijk willen we dat Python de twee getallen ook echt als twee getallen gaat beschouwen. De vraag is: Hoe doen we dat?

De input-functie is hier van belang. Die zegt altijd dat de invoer van de gebruiker als tekst moet worden beschouwd. Wij kunnen expliciet aangeven dat de invoer toch moet worden opgevat als een echt getal. Dit doen we door de functie int() te gebruiken. Dit ziet er als volgt uit:

getal1 =int(input("Geef een getal"))

getal2 =int(input("Geef nog een getal"))

som = getal1 + getal2

print("De som van getal1 en getal2 is")

print(som)

Let vooral op het gebruik van de functie int()! int is een afkorting voor integer. Het is de Engelstalige benaming voor een geheel getal. Je zegt hier eigenlijk: Hetgeen dat de gebruiker invoert met de input functie moet worden opgevat als een getal.

### Opgave 6

Schrijf een programma dat vraagt om vier getallen. Tel de eerste twee getallen bij elkaar op, deel dat dan door het derde getal, en vermenigvuldig het met het vierde getal. Print vervolgens het antwoord op het scherm.

### Opgave 7

Schrijf een programma dat de gebruiker vraagt om vijf getallen en schrijf daarna het gemiddelde van die vijf getallen naar het scherm (niet afronden).

### Opgave 8

Schrijf een programma dat de gebruiker vraagt om het huidige jaartal en om het jaar waarin hij geboren is. Reken uit hoe oud de gebruiker is aan het eind van het huidige jaar (in hele jaren) en schrijf het antwoord naar het scherm.

### Types en type-casting

Inmiddels ben je al bekend met twee soorten informatietypes (datatypes), namelijk strings en int's.Strings zijn een verzameling karakters die als het ware als een zin gebruikt worden door de computer. Een string is een type (soort) informatie waarvan de computer alles tussen de "" als een geheel behandeld. En net zoals dat een string een type informatie is, zijn er ook nog andere types. Een van de belangrijkste hiervan ken je nu ook al. De int wat dus staat voor integer, was een heel getal. Maar wat nou als je met decimale getallen wilt werken (getallen met een komma erin)? Hiervoor bestaat er nog een ander type informatie. Namelijk de float wat een getal is met nog cijfers achter de komma.

In het Engels gebruik je een '.' (punt) in plaats van een '.' (komma). Daarom schrijf je een getal 2,63 bij programma als 2.63

Deze laatste twee datatypes zijn heel erg belangrijk aangezien je er complexe berekeningen mee kan doen. Eerder deze les heb je al meerdere berekeningen gedaan met gehele getallen. Als je daarentegen met decimale getallen wilt werken heb je dus de floats nodig. Een paar voorbeelden van floats zijn:

print(3.5/1.5)

print(2.4\*1.23)

print(13+223.4)

Hierboven zie je dat er verscheidene berekeningen gedaan worden met floats. Als je met de input() functie werkt, wordt het belangrijk om hetzelfde trucje toe te kunnen passen als we eerder met de integers hebben gedaan. Als je namelijk niet expliciet het type informatie geeft aan de input() functie, gaat dit altijd als string behandeld worden. Maar als je het type int aan een float mee geeft krijg je hier een error van. Geef bij het volgende voorbeeld maar een float als input mee en kijk wat er gebeurt!

# In het engels werken mensen met punten i.p.v. komma's.

# Dus 3,4 is dan 3.4.

​

x =int(input("Geef mij een getal"))

y =int(input("Geef mij nog een getal!"))

print(x+y)

Hierboven zie je dat er verscheidene berekeningen gedaan worden met floats. Als je met de input() functie werkt, wordt het belangrijk om hetzelfde trucje toe te kunnen passen als we eerder met de integers hebben gedaan. Als je namelijk niet expliciet het type informatie geeft aan de input() functie, gaat dit altijd als string behandeld worden. Maar als je het type int aan een float mee geeft krijg je hier een error van. Geef bij het volgende voorbeeld maar een float als input mee en kijk wat er gebeurt!

# geef als input bij dit programma maar een float.

# In het engels werken mensen met punten i.p.v. komma's.

# Dus 3,4 is dan 3.4.

​

x =int(input("Geef mij een getal"))

y =int(input("Geef mij nog een getal!"))

print(x+y)

Om dit op te lossen kan je dus simpelweg in plaats van de functie int() de float() functie gebruiken. Als je dit doet, wordt de input behandeld als float en kan je hier dus weer berekeningen mee maken met getallen achter de komma.

# Nu wordt de input als float behandeld en kan de berekening wel op deze manier!

​

x =float(input("Geef mij een getal"))

y =float(input("Geef mij nog een getal!"))

print(x+y)

Het bovenstaande voorbeeld laat dus heel goed het verschil tussen float en int waardes zien. Bij berekeningen moet je hier dus goed op letten hoe je het in gaat voeren en wat voor antwoord je wilt krijgen. Verder kan het natuurlijk ook zo zijn dat je wilt dat een int of float als string behandeld wordt. Dit is namelijk nodig als je een variabele die een int of float bevat wilt printen. Een voorbeeld hiervan is het volgende:

# soms wil je een int of float als string printen zodat het goed leesbaar is

# en je duidelijk kan maken wat wat is.

​

lievelings\_getal =5

mooiste\_float =4.3

​

print("Mijn lievelings getal is "+str(lievelings\_getal))

print("Maar de mooiste float is "+str(mooiste\_float)+"!")

print("Zo zie je dat je eerst een int of float om moet zetten naar string!")

print("Anders krijg je de volgende error:")

print("")

print("als ik mijn lievelings getal zo print krijg je een error: "+ lievelings\_getal)

### Opgave 9

Bedenk wat de types zijn van de volgende tien dingen. Kies uit integer, float of string.

19 "3" 21.234 "Hoela hoepen" 24 \* 21.4 29 / 3 "293.3" 25.1 + 5 2 / 3 \* 9 8 + 30 / 10

Zoals je hierboven kan zien, maakt het erg veel uit hoe je de berekening invoert. Voor de volgende opdracht ga je hier zelf een programma voor schrijven:

### Opdracht 10

Schrijf een programma dat 2 of meer inputs vraagt, maak er een berekening mee en print het antwoord uit. In het programma moeten alle drie de datatypes voorkomen.

Als je even niet meer weet wat voor type iets heeft, bestaat er een functie die je hiervoor kan gebruiken. Als je namelijk type(variabele) gebruikt, zegt de computer wat het type is.

x =8

print(type(x))

print(type("hallo"))

print(type(4.5))

### Rekenen met variabelen

Nu we al die lastige informatie hebben verwerkt gaan we even weer verder met berekeningen met variabelen en deze straks combineren met strings!

We kunnen de variabelen bijvoorbeeld ook weer gebruiken om de turtle, die je hebt leren kennen in Python 0, vooruit te laten bewegen. In plaats van dat je een getal meegeeft aan de forward() functie, kun je bijvoorbeeld ook een variabelenaam meegeven. En ook een berekening met een variabele! Dat ziet er dan zo uit: turtle.forward(d\*10)

### Opgave 1

Wat wordt met de onderstaande code op het scherm geprint? Bedenk het eerst voor jezelf en probeer het daarna uit.

getal1 =10

getal2 =15

getal3 = getal1 + getal2

getal4 = getal1 - getal2

getal1 = getal4 - getal3

getal1 = getal1 -3

print(getal1)

### Opgave 2

Schrijf een programma waarmee je twee variabelen instelt met een beginwaarde. De eerste met waarde 3 en de tweede variabele met waarde 8. De namen van de variabelen mag je zelf weten. Tel de twee getallen bij elkaar op en sla het resultaat op in een nieuwe variabele. Print uiteindelijk het resultaat naar het scherm.

25

ICT Schakelklas 1 Schooljaar 2023-2024