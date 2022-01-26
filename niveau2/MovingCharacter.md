# Bewegende karakter

![Moving Character ui](images/MovingCharacter-ui.png)

Zorg ervoor dat je Psyduck (of iets anders) met de toetsen (omhoog, omlaag, links en rechts) op het toetsenbord kan laten bewegen in een element. Hiervoor maak je in je html een element (div playfield) met daarin Psyduck aan. 

```html
<div id="playfield">
	<div id="psyduck"><img src='images/psyduck'></div>
</div>
```

Positioneer de playfield en psyduck absolute zodat je psyduck makkelijker kan laten bewegen.

```css
#playfield {
	position: absolute;
	width: 500px;
	height: 500px;
}

#psyduck {
	position: absolute;
	width: 50px;
	height: 50px;
}
```

Maak een [addEventListener](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_onkeydown_addeventlistener) aan die bij keydown de Psyduck laat rondbewegen.

## Je maakt gebruikt van
- variabelen [youtube](https://www.youtube.com/watch?v=oTKpXoqZims)
- debuggen & comments [youtube](https://www.youtube.com/watch?v=XUYCOm38SWY)
- DOM en objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- functions [youtube](https://www.youtube.com/watch?v=zC5cvaETdyQ)
- events [youtube](https://www.youtube.com/watch?v=6jYEabxJXxg)
- event keydown [w3schools](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_onkeydown_addeventlistener)