# Filter

Je hebt een uitgebreide dvd collectie van de Disney films. Om een beetje overzicht te creëren maak je hier een webapplicatie voor. In deze webapplicatie kunnen de films gefilterd worden op decennium.

![Filter ui](images/Filter-ui.png)

Maak van de films een unordered list en geef de films een decennium-class mee.

```html
<ul id="films">
	<li class="d30">Sneeuwwitje</li>
	<li class="d40">Pinokkio</li>
	<li class="d40">Fantasia</li>
	...
</ul>
```

De buttons waarmee je filtert kan je dezelfde naam meegeven als bij de decennium-class. Maak voor elke button een addEventListener aan. 

```html
<button id="d30">jaren 30</button>
<button id="d40">jaren 40</button>
...
```

```javascript
button30.addEventListener("click", filterMovies);
```

## Je maakt gebruikt van
- variabelen [youtube](https://www.youtube.com/watch?v=oTKpXoqZims)
- debuggen & comments [youtube](https://www.youtube.com/watch?v=XUYCOm38SWY)
- DOM en objecten [youtube](https://www.youtube.com/watch?v=k81rBKqwDhU)
- functions [youtube](https://www.youtube.com/watch?v=zC5cvaETdyQ)
- events [youtube](https://www.youtube.com/watch?v=6jYEabxJXxg)

## Eventuele uitbreidingen
- voeg nog meer filters toe
- ipv tekst gebruik plaatjes van de film