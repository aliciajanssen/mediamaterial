# Hot Items

Maak een webapplicatie waarin een div met id "hotitems" (in je html). In hotitems zitten drie divs met de class "item":

```html
<div id="hotitems">
	<div class="item"></div>
	<div class="item"></div>
	<div class="item"></div>
</div>
```

Deze divs hebben ook een eigen stijl:

```css
#hotitems {
	display: flex;
	justify-content: center;
	width: 100%;
	height: 50px;
}
.item {
	width: 50px;
	height: 50px;
}
```

Zet dit in een css bestand en voeg dat aan de webapplicatie toe.
Je ziet dat er nog geen achtergrondkleur aan is toegevoegd. Je gaat de achtergrondkleur met javascript aanpassen.

Maak een aparte variabele "hotitems" aan waar je dmv document.getElementById of querySelector het hotitems object ophaalt. 

```javascript
let hotitems = document.getElementById("hotitems");
//of
let hotitems = document.querySelector("#hotitems");
```

Nu je van hotitems een object hebt gemaakt, is het makkelijk om de achtergrond aan te passen.

```javascript
let hotitems = document.getElementById("hotitems");
//of
let hotitems = document.querySelector("#hotitems");
hotitems.style.background = "green";
```

Probeer dit ook te doen met de losse items. Hiervoor gebruik je document.getElementsByClassName(). Pas hier ook de achtergrondkleur aan.

## Je maakt gebruikt van
- De DOM en Objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- De DOM uitbreiding [youtube](https://www.youtube.com/watch?v=IrjSvQDvWDc)
- Arrays [youtube](https://www.youtube.com/watch?v=Z-l1IAbq3qg)
- HTML DOM getElementsByClassName() Method [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbyclassname.asp)
- HTML DOM getElementById() Method [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)
- HTML querySelector [w3schools](https://www.w3schools.com/jsref/met_document_queryselector.asp)
- Style background Property [w3schools](https://www.w3schools.com/jsref/prop_style_background.asp)