# Willekeurige afbeelding

Maak een webpagina die elke keer wanneer je de pagina opnieuw inlaadt een willekeurige afbeelding laat zien.
Deze afbeeldingen komen uit het mapje "images" op je eigen server. De afbeeldingen mag je zelf uitkiezen en in het mapje zetten.

Voorbeeld mappenstructuur:
- css (folder)
	- style.css
- js (folder)
	- main.js
- images (folder)
	- schoenen.jpg
	- kabouter.png
	- frikandel.jpg
- index.html

```javascript
//voorbeeld van array
var images = [  
 "schoenen.jpg",  
 "kabouter.png",  
 "frikandel.jpg"  
];
```

Om een willekeurige afbeelding te kiezen heb je een [random functie](../functions/RandomNumber.md) nodig.

## Je maakt gebruikt van
- De DOM en Objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- Arrays [youtube](https://www.youtube.com/watch?v=Z-l1IAbq3qg)
- Javascript Arrays [w3schools](https://www.w3schools.com/js/js_arrays.asp)
- Create img elements in javascript [softauthor](https://softauthor.com/javascript-working-with-images/#:~:text=Create%20Image%20Element%20in%20JavaScript,URL%20to%20its%20src%20attribute.&text=Finally%2C%20add%20the%20image%20element,it%20to%20the%20body%20element.)