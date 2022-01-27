# Aan de oppervlakte

Maak een webapplicatie met de function "BerekenOppRechthoek". Deze function heeft twee parameters: lengte en breedte. Wanneer deze function wordt aangeroepen wordt de oppervlakte van een rechthoek berekend en terug gestuurd.

In javascript kan je dit op twee manieren doen, met alleen **function** of  met een **const-variabele en function**.

## Function
```javascript
function BerekenOppRechthoek(lengte, breedte)
{
	//berekening oppervlakte
	return oppervlakte
}

let oppervlakte = BerekenOppRechthoek(3, 4); //hier komt 12 uit
```

Function wordt nog veel gebruikt en zie je nog veel op voorbeelden online staan. Maar er wordt steeds meer plaats gemaakt voor de const-variabele en function.

## Const + Function
```javascript
const BerekenOppRechthoek = function(lengte, breedte) {
	//berekening oppervlakte
	return oppervlakte
}

let oppervlakte = BerekenOppRechthoek(3, 4); //hier komt 12 uit
```

Je ziet dat er weinig verschil tussen de eerste en tweede optie is. Het verschil zit het in waar je de function kan aanroepen. Bij de eerste mogelijkheid kan je function overal in jouw script aanroepen, maar bij de tweede er alleen onder. Voor meer informatie bekijk deze [video](https://www.youtube.com/watch?v=lleIeTMaFRo).

Maak nog een function waarmee de **oppervlakte van een cirkel** berekend kan worden. Doe dit op beiden manieren. 
Voor de wiskundige onder ons: om de oppervlakte berekening van een cirkel bestaat deze berekening: 
straal * staal * pie. Hiervoor kan je de javascript PI [Math.Pi](https://www.w3schools.com/jsref/jsref_pi.asp) property gebruiken. Je hebt bij deze functie 1 parameter nodig: straal.

## Je maakt gebruikt van
- Functions [youtube](https://www.youtube.com/watch?v=lleIeTMaFRo)
- Net Ninja - Modern Javascript - Functions [youtube](https://www.youtube.com/watch?v=xUI5Tsl2JpY)
- Javascript PI [w3schools](https://www.w3schools.com/jsref/jsref_pi.asp)
- Javacript functions [w3schools](https://www.w3schools.com/js/js_functions.asp)
- Oppervlakte berekenen [rekenen-oefenen](https://www.rekenen-oefenen.nl/instruction/rekenen/meten-en-meetkunde/meten/meten/de-oppervlakte-berekenen/de-oppervlakte-berekenen-1)
- Oppervlakte berekenen cirkel [rekenen-oefenen](https://www.rekenen-oefenen.nl/instruction/rekenen/meten-en-meetkunde/meten/meten/de-oppervlakte-berekenen/de-oppervlakte-van-een-cirkel-berekenen)

## Eventuele uitbreidingen:
- Maak een visuele weergave van de rechthoek en cirkel. Wanneer de berekening wordt gemaakt, wordt ook de rechthoek of cirkel met oppervlakte weergegeven.
- Wanneer de oppervlakte groter is dan 10 dan laat een melding zien
- Bereken meerdere oppervlaktes tegerlijkertijd en laat het totaal zien.
- Genereer een random rechthoek of cirkel (zie opdracht [RandomNumber](RandomNumber))