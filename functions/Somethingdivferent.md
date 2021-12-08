# Something div-ferent

Maak een webapplicatie met de function "GenerateDIV". Met deze function wordt er een nieuwe div gegenereerd. Hiervoor moet je [createElement](https://www.w3schools.com/jsref/met_document_createelement.asp) function gebruiken. Je zou dit als uitgangspunt kunnen nemen:

```javascript
let field = document.getElementById("field");


function GenerateDIV()
{
	//genereer div
}

let div = GenerateDIV();

//div wordt toegevoegd aan de pagina (div field)
field.appendChild(div);
```

Zorg er nu voor dat je als parameter een kleur voor de div kan meegeven. Wanneer je bijv. de kleur "blue" meegeeft, wordt de div blauw.

```javascript
let field = document.getElementById("field");

//bgColor is parameter
function GenerateDIV(bgColor)
{
	//genereer div
}

let div = GenerateDIV("blue");

//div wordt toegevoegd aan de pagina (div field)
field.appendChild(div);
```

Breid dit uit met andere parameters zoals positie of formaat van de div.

## Je maakt gebruikt van
- Functions [youtube](https://www.youtube.com/watch?v=zC5cvaETdyQ)
- De DOM en Objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- createElement [w3schools](https://www.w3schools.com/jsref/met_document_createelement.asp)
- Javascript Functions [w3schools](https://www.w3schools.com/js/js_functions.asp)