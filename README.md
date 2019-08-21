# Nyhetssidan

## Instruktioner
Märk upp delarna av texten med rätt element för att bygga upp hela HTML-sidan.

### Introduktion - Uppmärkning

Använd elementen

* ```<h1>```, Huvudrubrik
* ```<h2>```, Rubrik
* ```<p>```, Paragraf

```
Trump har gjort det igen!

USAs president senaste tweet, "Det var jag som uppfann hjulet!"

Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
Et recusandae eius aut minus amet fuga exercitationem delectus sint eos aliquid.

Lorem ipsum dolor sit amet consectetur adipisicing elit. 
Nobis consectetur corrupti est voluptatem dolore id laudantium debitis magni 
necessitatibus ad enim exercitationem nihil provident velit similique, 
architecto placeat illum consequuntur? Aliquam voluptatem quod expedita 
minima ipsa assumenda necessitatibus delectus asperiores!

Skriven av Yngve Magnusdottir
```

### Uppdelning av innehåll - Nestning

Efter du är klar med introduktionen, fortsätt med att
lägga till en ny artikel och märk upp den tillsammans med tidigare innehåll.
Lägg även till en ```<header>``` innehållande ```The Garlic News``` som en rubrik,
samt en ```<footer>```innehållande 
```
info@garlicnews.com
+850 555-1337
```

Använd elementen

* ```<header>```, representerar introducerande innehåll
* ```<section>```, en samling av liknande innehåll
* ```<article>```, ett innehållselement som är återanvändbart, tänk en nyhetsartikel, produkt, ett blogginlägg, etc.
* ```<footer>```, brukar innehålla saker som kontaktuppgifter och dylikt

```
Ny måne hittat

"Den smakade som kyckling", säger forskare

Skriven av Olga Svensson

Lorem ipsum dolor sit amet consectetur adipisicing elit. 
Nobis consectetur corrupti est voluptatem dolore id laudantium debitis magni 
necessitatibus ad enim exercitationem nihil provident velit similique, 
architecto placeat illum consequuntur? Aliquam voluptatem quod expedita 
minima ipsa assumenda necessitatibus delectus asperiores!

Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
Et recusandae eius aut minus amet fuga exercitationem delectus sint eos aliquid.
```

### HTML-dokumentet

Lägg till så att dokumentet blir ett komplett HTML-dokument.
Lägg också till ```<!DOCTYPE html>``` längst upp i dokumentet.

Använd elementen

* ```<html>```, Detta är roten till alla HTML-dokument
* ```<head>```, meta-information och saker som inte syns i själv fönstret
    * ```<title>```, Texten som syns på tabben i webbläsaren, ska vara i ```<head>```
    * ```<meta charset="UTF-8">```, anger teckenkodning på dokumentet, ska vara i ```<head>``` 
* ```<body>```, allt innehåll på sidan, ex ```<article>```, ```<h1>``` och ```<p>```
