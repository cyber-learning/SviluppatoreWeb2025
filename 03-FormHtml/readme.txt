elemento form un contenitore utile per raccogliere (più) dati dell'utente
l'attributo action della form specifica il path di destinazione dei dati raccolti all'interno della form

l'attributo enctype specifica l'encoding type cioè la formattazione dei dati inviati al server.
Di defautl enctype assume come valore application/x-www-form-urlencoded

block level elements:
form

inline level elements:
input   (self closing tag)
label
select

Gli elementi di input possono essere di tipo:
- text
- number
- email
- password
- checkbox
- radio



query string (il name altro non è che la key) nel formato application/x-www-form-urlencoded
name1=value1&name2=value2&name3=value3
firstname=Eric&lastname=Cartman

un altro formato che vedremo più avanti è application/json
{"firstname":"Eric","lastname":"Cartman"}


Nel protocollo https, la query string deve essere utilizzata SOLO per trasferire dati NON sensibili.
La query string viene utilizzata per filtrare i risultati di ricerca.

GET /ricette.html
GET /ricette.html?categoria=primiPiatti

GET /explore?place=mare



# Riferimenti:
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/input
https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=it#images





# Esercizio - Blog di Ricette
Prendendo ispirazione da un blog di ricette già esistente (ad esempio Giallo Zafferano),
strutturare la pagina index.html utilizzando tutto ciò che abbiamo visto in HTML ed in particolare:
- tag semantici
- headings tag (sia article sia section devono presentare un heading tag)

Per le immagini utilizzare picsum.photos modificando opportunamente l'URL dell'immagine:
    https://picsum.photos/400/300

Creare una navbar che contiene un link interno per registrarsi come chef (pagina di iscrizione per gli chef).

Questa pagina deve presentare una form che richieda le seguenti informazioni:
    nome e cognome
    età
    email
    password
    chef stellato?
    accetti termini e condizioni?

