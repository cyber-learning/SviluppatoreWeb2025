CTRL + s per salvare il contenuto del file



Architettura Client - Server
Due programmi di cui uno assume il ruolo di client (cioè si comporta come client) e uno assume il ruolo di server.
Solo il client può avviare la comunicazione. Il server può solo mettersi in ascolto (listen) e NON può effettuare richieste.

Un programma client potrebbe essere:
- il browser (in ambito web)
- app su telefono oppure app su desktop




1) come faccio a trovare la pubblicazione scientifica di Stefano? Il numero di telefono, con quale interno parlare, il nome del libro
2) come dialoghiamo al fine di ottenere la pubblicazione scientifica di Stefano? (regole di comunicazione)
3) come interpreto la pubblicazione scientifica di Stefano? 


WWW:
1) URI (modo astratto) un modo per identificare una pagina HTML all'interno della rete.
    Un caso particolare di URI è l'URL.
    URL uniform resource locator cioè posso identificare una pagina HTML all'interno della rete conoscendo (in anticipo) la sua collocazione nella rete (cioè dove si trova la pagina html nella rete). 
    ad esempio https://it.wikipedia.org/wiki/Ciao
2) protocollo HTTP HyperText Transfer Protocol (un protocollo definisce delle regole di scambio dati - regole di comunicazione)
    Il protocollo HTTP si basa su una architettura client server
    Nel protocollo HTTP il client effettua una "richiesta HTTP", il server riceve la richesta, la elabora ed invia una "risposta HTTP"
3) HTML HyperText Markup Languange un linguaggio di formattazione (markup) per testo + link in modo da presentare i dati all'utente in maniera logica (definendo una struttura)


Con il termine risorsa si intende una pagina HTML, una immagine, un file qualsiasi
L'URL permette di conoscere la collocazione nella rete di una risorsa ad esempio:
- https://it.wikipedia.org:443/wiki/Ciao
- http://localhost:3000/index.html
- http://127.0.0.1:8080/index.html
- http://www.youtube.com:80
- https://www.youtube.com/watch  ?   v=k9ynZnEBtvw & list=RDk9ynZnEBtvw &   start_radio=1
- eric.cartman@gmail.com

Un dominio è praticamente un indirizzo IP
protocollo://username:password@dominio:porta/path?queryString

Il path è il percorso del file

La queryString serve per "filtrare" i risultati di ricerca
key1=value1&key2=value2&key3=value3





Sintassi elemento HTML:
<tagname attribute1="value1" attribute2="value2" attribute3="value3">content</tagname>


Per commentare su windows
alt + shift + a

Heading tag titoli aventi ordine di importanza decrescente:
h1
h2
h3
...
h6

Paragraph
p

Link
a   attributo href  hypertext reference





Il live server simula un web server anni 90 (inizio del WWW)

URL in rete                                              Percorso sul File System
http://127.0.0.1:5500/index.html                ->       C://Users/Alessandra/Desktop/01-Introduzione/index.html
http://127.0.0.1:5500/about-us.html             ->       C://Users/Alessandra/Desktop/01-Introduzione/about-us.html
http://127.0.0.1:5500/chefs/salvatore.html      ->       C://Users/Alessandra/Desktop/01-Introduzione/chefs/salvatore.html

index.html la pagina di partenza di tutti il sito web (l'indice del sito)


# Esercizio - AboutMe
Creare una fantastica pagina web di presentazione personale, stile anni '90,
che punta al vostro account Instagram o TikTok o entrambi usando gli heading, paragraph e links

# Esercizio
Creare un sito formato da più pagine html oltre alla pagina index.html


Riferimenti
https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview
https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status

https://developer.mozilla.org/en-US/docs/Web/HTML
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements

https://www.youtube.com/@NetNinja/playlists