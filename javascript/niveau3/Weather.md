# Niet weer applicatie

Maak een webapplicatie waar je het weer (temperatuur, regent het?) in je woonplaats kan inzien. Om de juiste weer informatie te hebben, haal je de gegevens op doormiddel van de [weerlive.nl](https://weerlive.nl/delen.php) api.

Je kunt API gegevens op verschillende manieren ophalen. Hieronder staan twee methoden:

## XML HttpRequest Object (old skool)
Met het [XML HttpRequest Object](https://www.w3schools.com/xml/xml_http.asp) kan je via Javascript de gegevens ophalen.

```javascript
var xhr = new XMLHttpRequest();
xhr.open("GET", "[de url]", true);
xhr.onload = function (e) {
  if (xhr.readyState === 4) {
    if (xhr.status === 200) {
      console.log(xhr.responseText);
      var response = JSON.parse(xhr.responseText);
      console.log(response);
    } else {
      console.error(xhr.statusText);
    }
  }
};
xhr.onerror = function (e) {
  console.error(xhr.statusText);
};
xhr.send(null);
```

## Fetch (so fetch)
De tweede methode is met [fetch](https://www.javascripttutorial.net/javascript-fetch-api/). Dit is de moderne manier van gegevens ophalen en is overzichtelijker.
```javascript
fetch([de url])
  .then((response) => 
  {
    return response.json();
  })
  .then((myJson) => 
  {
    console.log(myJson);
  });
```

![Fetch](images/fetch.gif)