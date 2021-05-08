# Niet weer applicatie

Maak een webapplicatie waar je het weer (temperatuur, regent het?) in je woonplaats kan inzien. Om de juiste weer informatie te hebben, haal je de gegevens op doormiddel van de [weerlive.nl](https://weerlive.nl/delen.php) api.
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

