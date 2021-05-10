# Wie is de ouder van?

De [DOM](https://www.w3schools.com/whatis/whatis_htmldom.asp) bestaat uit een heel stamboom van ouders (parents) en kinderen (children). 
Laat zien hoe dit werkt op een webpagina. Maak hiervoor een aantal divs in je html aan:

```html
<div id="kees-marie">
	<div id="daan"></div>
	<div id="kevin"></div>
	<div id="anouk"></div>
</div>

<div id="henk-truus">
	<div id="jorian"></div>
	<div id="geert"></div>
	<div id="noah"></div>
</div>

<div id="jos-annie">
	<div id="jasper"></div>
	<div id="celeste"></div>
	<div id="luc"></div>
</div>

<div id="kinderen-kees-marie"></div>
<div id="ouders-jorian"></div>
```

Haal met de [children](https://www.w3schools.com/jsref/prop_element_children.asp) Property de kinderen (Daan, Kevin en Anouk) van Kees en Marie op. Laat deze zien in de kinderen-kees-marie div.

Haal de ouders van Jorian op met de [parent](https://www.w3schools.com/jsref/prop_node_parentelement.asp) property. Laat de ouders zien in de ouders-jorian div.

Haal met de [children](https://www.w3schools.com/jsref/prop_element_children.asp) Property de kinderen (Jasper, Celeste en Luc) van Jos en Annie op. Voeg de tekst "ik ben een kind" aan elk div-kind toe.

## Je maakt gebruikt van
- De DOM en Objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- Arrays [youtube](https://www.youtube.com/watch?v=Z-l1IAbq3qg)
- HTML DOM getElementById() Method [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp))
- HTML DOM parentElement [w3schools](https://www.w3schools.com/jsref/prop_node_parentelement.asp)
- HTML DOM children Property [w3schools](https://www.w3schools.com/jsref/prop_element_children.asp)
- HTML DOM innerHTML [w3schools](https://www.w3schools.com/jsref/prop_html_innerhtml.asp)