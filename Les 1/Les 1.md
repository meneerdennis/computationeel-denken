![](RackMultipart20240201-1-pogx9y_html_3f8ae9d1fb467d52.gif) ![Shape1](RackMultipart20240201-1-pogx9y_html_7dd93edd99011b94.gif)

ICT

Mr. Dennis

**I**

# HOOFDSTUK 4

# Computationeel denken: Python

# Les 1: Print & variabelen

### De print functie

Met Python is het mogelijk om tekst en getallen op het scherm te tonen. Dat doe je met de functie print(). Deze functie "print" gewoon de informatie die je wilt op het scherm.

print("Dit komt dus op het scherm terecht.")

print("We gaan nu een paar sommetjes doen:")

print(230-21)

print(78-2+6)

print(78-2\*6)

Zoals je ziet kun je ook berekeningen tussen de haakjes van de print()-functie zetten. Let er wel op dat de voorrangsregels van de wiskunde ook gelden voor programmeertalen: de \* en de / gaan dus vóór de + en de -.

Er bestaat iets als een **string**. Een string is een rij van tekens (karakters). Een teken is een letter (zoals 'a', 'B'), nummer ('0', '2'), symbool ('#', '^', '}'), enz. en kan gebruikt worden om allerlei soorten informatie in op te slaan. Vaak is dit dus gewoon een stukje tekst wat iemand op het scherm wil printen.

_ **'string'** betekent in het Engels touw of draad. Het is dus een touw met karakters er aan._

### Opgave 1:

Schrijf een programma dat met de print()functie "Hello, world" op het scherm zet.

### Opgave 2:

Schrijf een programma dat met deprint() functie de volgende boodschap op het scherm zet:

Welkom bij mijn geweldige programma! We gaan allemaal toffe dingen laten zien.

Dit doen we met behulp van de print()-functie. ^\_^

### Variabelen

Vaak wil je in je programma tijdelijk gegevens bewaren. Dit doe je met _ **variabelen** _. **Een variabele kun je zien als een emmer met een label erop**. Je kunt er iets in zetten en je kunt er iets uithalen. Hieronder zie je een stukje code met ernaast een plaatje waarop te zien is wat er gebeurt:

a =20

b =15

c ="hallo"

​

Je kun nu doen:

print(c)

​

of:

print(a+b)

![](RackMultipart20240201-1-pogx9y_html_7128f96a18f3db9f.png)

Je ziet dus dat er nu drie emmers zijn. Elke emmer heeft een naam/label en een inhoud. In het begin zijn alle emmers leeg. Maar na de drie regels van hierboven verandert de zaak:

- In de emmer met als naam a komt namelijk het getal 20 te staan.
- In emmer b komt 15 te staan.
- En in c komt de tekst "hallo" te staan.

We kunnen nu ook een vierde emmer genaamd d in het leven roepen. In die variabele kunnen we het verschil (min) tussen a en b berekenen en bewaren. Dat gaat zo:

![](RackMultipart20240201-1-pogx9y_html_a9e3bb064ee834b.png)

a =20

b =15

c ="hallo"

​

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

23.22342 \* 34309483

218739345 + 3498348

Stop de antwoorden in drie verschillende variabelen. Tel de drie antwoorden bij elkaar op en print het uiteindelijke antwoord.

### Namen van variabelen

De naam van een variabele kan je altijd zelf bepalen. Dus als je berekeningen wilt doen met je favoriete getal, kan je deze in een variabele stoppen met als naam bijvoorbeeld favoriete\_getal. Dit is handig omdat je dan makkelijk kan bijhouden wat er in de variabelen zit. Noem je variabelen dus altijd op een logische manier! Kijk maar naar het volgende voorbeeld:

favoriete\_getal =7

print (favoriete\_getal +1)

print (favoriete\_getal)

print (favoriete\_getal \*2)

favoriete\_getal =4+5

print (favoriete\_getal)

print ("favoriete\_getal")

Zoals je kan zien zijn de eerste drie antwoorden van het programma (dit worden ook wel **outputs** genoemd) gewoon een wiskundesom die de inhoud van onze variabelen gebruikt. Daarna wordt er een verandering gemaakt in de variabele favoriete\_getal. Er wordt een andere waarde aan de variabele gegeven, namelijk 4 + 5, dus 9. Je kan na het toewijzen van de waarde van een variabelen deze dus altijd ook nog later veranderen.

Bij de laatste output zien we iets vreemd. Doordat er " " om favoriete\_getalstonden, wordt deze gezien als wat? Ja! Een **string**! Het is dus heel erg belangrijk om in je achterhoofd te houden of je iets wilt printen als een **string** of als een **variabele**. Als je de " " namelijk vergeet, gaat het programma zoeken naar een variabele met die naam. En als er dus geen variabele toegewezen is kan je hierdoor een foutmelding (oftewel een _error_) krijgen.

### Strings aan elkaar plakken (concatenation)

Bij de vorige opdrachten heb je steeds een aparte string geprint op het scherm. Nu bestaat er ook iets als string concatenation, waarin je twee strings samen kan voegen. Concatenation is een Engels woord voor "aaneenschakeling", en in python is dit ontzettend makkelijk: Je plakt twee string aan elkaar vast met een "+" of een ","! Probeer maar:

leerling\_naam ="Joop"

print ("Hallo, dit is deel een!" , "En dit is deel twee!")

print ("Jouw naam is "+ leerling\_naam)

​

kledingstuk ="broek"

print("Wat heb je een mooie "+ kledingstuk, "aan.")

​

### Opgave 4

Schrijf steeds een programma waarin je de gegeven variabele op de goede plek in de string gebruikt zoals in het voorbeeld.

naam = Lotte

\<naam\> heeft pannenkoeken gegeten!

naam = Kees

De kat van \<naam\> heeft een muis gevangen.

naam = Bas

tijd = nacht

De parkiet van \<naam\> heeft hem de hele \<tijd\> wakker gehouden.

### Opgave 5

Print bij deze opdracht de komende drie woorden in alle volgordes die er maar zijn dus bijvoorbeeld: 'Niezen Kikkers Blij' of 'Knikkers Niezen Blij'. Hint, er zijn 6 verschillende volgordes.

speelgoed = "knikkers"

gevoel = "blij"

werkwoord = "niezen"

print(speelgoed + gevoel + werkwoord)

# Ga Verder

### Opdracht 6

Schrijf je eigen kleine verhaaltje.

Gebruik een **variabele** voor de naam van de hoofdpersoon zodat je makkelijk de hoofdpersoon kunt wijzigen.

**Voorbeeldverhaal** : Henk is een blije jongen. Hij gaat op de fiets naar school. Als Henk op school is gaat hij vrolijk naar de les. Einde!

**Code die hier bij hoort:**

naam = "Henk"

print(naam + " is een blije jongen.")

# denk aan de extra spatie!

print("Hij gaat op de fiets naar school.") print("Als " + naam + " op school is gaat hij vrolijk naar de les.")

print("Einde!")

### Foutmeldingen (errors)

Een 'error' is een foutmelding. Op errors gaan we later dieper in, maar voor nu is het handig om te weten dat je bij bijvoorbeeld de volgende code:

getel = 4

print (getal + 1)

iets kan krijgen als:

Traceback (most recent call last): File "\<stdin\>", line 2, in \<module\>NameError: name 'getal' is not defined

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

kosten\_lolly =30

kosten\_appel =60

kosten\_banaan =100

​

geld\_op\_zak =230

​

geld\_over = geld\_op\_zak - kosten\_appel - kosten\_banaan - kosten\_lolly

​

print geld\_over

katten =4

honden =8

dolfijnen =2

cavias =3

chinchillas =1

​

aantal\_dieren = katten + honden + dolfijnen + cavias + hamsters + chinchillas

​

print(aantal\_dieren)

# Hoe vaak moet nicky heen en weer lopen om drinken voor haarzelf en al haar

# vriendinnen te halen als zij maar drie flesjes per keer mee kan nemen?

​

1= nicky

14= vriendinnen

nicky + vriendinnen = totaal\_hoeveelheid\_mensen

​

3= flessen\_per\_keer

​

totaal\_hoeveelheid\_mensen / flessen\_per\_keer = hoeveel\_keer\_lopen

​

print(hoeveel\_keer\_lopen)

peren ="appels"

appels ="peren"

wie\_de ="Je moet geen "

kaatst\_kan\_hem =" met "

terug\_verwachten =" vergelijken."

​

print (wie\_de + peren + kaatst\_kan\_hem + appels terug\_verwachten)

​

​

