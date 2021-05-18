# Push It (real good)!

Je gaat je eigen videospeler maken. De video die je zou kunnen gebruiken staat [hier](videos/pushIt.mp4), je kunt natuurlijk ook je eigen video gebruiken!

Ten eerste ga je de video toevoegen aan de webpagina. Dit doe je met het html element "video". Verder moet de video ergens op de webserver (hier in de map video) staan. 

```html
<video width="420" height="300" id="pushIt">
	<source src="video/pushIt.mp4" type="video/mp4">
	Your browser does not support the video tag.
</video>
```

Jij gaat er zelf twee buttons aan toevoegen waarmee de video kan starten en pauzeren. 

```html
<button id="play">Push it!<button\>
<button id="pause">Pause it!<button\>
```

Maak hierna twee addEventListeners voor deze knoppen aan. In deze addEventListeners moet je ervoor zorgen dat de video wordt afgespeeld en stopgezet. Dit kan je doormiddels de [play en pause method](https://www.w3schools.com/tags/av_met_play.asp) doen.

Succes!

## Je maakt gebruikt van
- De DOM en Objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- Variabelen [youtube](https://www.youtube.com/watch?v=HfWaYjRrIM4)
- Events [youtube](https://www.youtube.com/watch?v=6jYEabxJXxg)
- Functions [youtube](https://www.youtube.com/watch?v=zC5cvaETdyQ)
- Javascript HTML DOM EventListener [w3schools](https://www.w3schools.com/js/js_htmldom_eventlistener.asp)
- Play method [w3schools] (https://www.w3schools.com/tags/av_met_play.asp)