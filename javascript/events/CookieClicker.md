# Cookie clicker - That's another cookie!

Om de events onder de knie te krijgen kan je een blitse cookie clicker maken. Kort gezegd is een Cookie clicker een spelletje waarmee je punten kan verdienen door op cookies te klikken.

Om goed te beginnen zet je eerst een cookie(div: cookie) op de webpagina. Dit zet je in het html bestand. Hoe de cookie eruit komt zien, mag je zelf bepalen: css-en, smakelijke cookie images, positie enz..

Verder moet je een divje aanmaken waar je punten (score) laat weergeven.

```html
<div id="score"></div>

<div id="cookie"></div>
```

## Opdracht 1 - Click event
Om de Cookie Clicker te laten werken moet je eerst een click-event voor de cookie maken. Aan deze click-event wordt de function addScore gekoppeld. Er moet immers iets gebeuren wanneer er op een van die cookies wordt geklikt. Dit kan je doen met een [addEventListener](https://www.w3schools.com/jsref/met_document_addeventlistener.asp). 

Maak het eerst zo dat wanneer je op de cookie clickt er een Alert met "ik heb erop geklikt" tevoorschijn komt.

```javascript
let cookieElement = document.getElementById("cookie");
cookieElement.addEventListener("click", addScore);

function addScore()
{
	//hier komt een alert
}

```

## Opdracht 2 - Score updaten
Wanneer dit is gelukt is het tijd voor de volgende stap. Je moet een extra variabele toevoegen, namelijk de variabele voor de score. Je geeft de variabele de waarde 0. Deze variabele staat buiten de addScore function.

```javascript
let score = 0;
```

Nu moet je zorgen dat wanneer er op de cookie wordt geklikt de waarde van score wordt opgehoogd met 1 punt. Laat ipv "ik heb erop geklikt" de waarde in de Alert zien.

## Opdracht 3 - Score weergeven
De laatste stap om ipv het in de Alert te laten waargeven, het op de pagina te laten zien. Hiervoor kan je de [innerHTML property](https://www.w3schools.com/jsref/prop_html_innerhtml.asp) gebruiken.

```javascript
let scoreElement = document.getElementById("score");
scoreElement.innerHTML = ....
```

## Opdracht 4 - Key event
Maak een cheat in de Cookie Clicker. Wanneer de speler op de enter toets drukt komen er 100 punten erbij. Hiervoor gebruik je ook weer een addEventListener, maar maak je gebruik van een keydown ipv een click event. Daarnaast moet je kijken welke toets je indrukt, hiervoor moet je gebruik maken van een event.key.

```javascript
window.addEventListener("keydown", addCheat);

// de function heeft de parameter event! Daarmee kan je zien welke toets er wordt ingedrukt.
function addCheat(event)
{
	if (event.key == "Enter")
	{
		//
	}
}

```

## Eventuele uitbreidingen
De cookie clicker kan je makkelijk uitbreiden met van alles. Denk aan:
- meer cookies
- meer type events
- een tijdslimiet
- geluidjes erbij
- wanneer er ook een cookie wordt geklikt, verandert de positie
- ...

## Je maakt gebruikt van
- De DOM en Objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- Variabelen [youtube](https://www.youtube.com/watch?v=A6YVhg9GgPE)
- Events [youtube](https://www.youtube.com/watch?v=6jYEabxJXxg)
- Functions [youtube](https://www.youtube.com/watch?v=lleIeTMaFRo)
- Scoping [youtube](https://www.youtube.com/watch?v=CD1prUUhisI)
- KeyboardEvent.key [developer mozilla](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/key)
- Keydown event [developer mozilla](https://developer.mozilla.org/en-US/docs/Web/API/Document/keydown_event)
- Javascript HTML DOM EventListener [w3schools](https://www.w3schools.com/js/js_htmldom_eventlistener.asp)