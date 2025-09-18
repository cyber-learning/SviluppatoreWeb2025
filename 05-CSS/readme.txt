responsabilità dell'HTML è fornire una struttura logica alla pagina

CSS         cascade         style sheet
responsabilità del CSS fornire uno stile (rendere belli visivamente) agli elementi HTML

Possiamo applicare il CSS (sugli elementi HTML) in 3 modi diversi:
- inline    attributo HTML style
- embedded  elemento HTML style
- file esterno


windows:
alt gr + 124
alt gr + shift + +
alt gr + shift + è


    shift + alt gr + è

mac:
option + shift + è


Le parentesi graffe definiscono un blocco di dichiarazioni
selector {
    property1: value1;  
    property2: value2;
    property3: value3;
}

Selettori CSS utili per selezionare gli elementi HTML su cui vogliamo applicare le dichiarazioni CSS
(in ordine di specificità dal meno specifico (dal meno importante) al più specifico (al più importante)):
1) * universal selector permette di selezionare tutti gli elementi HTML della pagina
2) tag selector permette di selezionare tutti gli elementi HTML della pagina avente quel determinato tag
3) .nomeDellaClasse class selector
4) #id id selector permette di selezionare SOLO un elemento HTML
5) attributo HTML style 


value per il colore:
- named color   red, green, aqua
- tramite funzione CSS rgb() che richiede 3 valori da 0 a 255 oppure la funzione rgba() con il quarto valore per il canale alpha da 0.0 a 1.0
- tramite 3 coppie di valori esadecimali #rrggbb da 00 a FF (per il canale alpha basta aggiungere una quarta coppia)


Riferimenti
https://blog.marketing-espresso.com/colori-marketing/
https://m3.material.io/
https://colorhunt.co/
https://www.canva.com/colors/color-wheel/


Font:
- serif
- sans-serif
- cursive
- monospace

font-weight specifica lo spessore del carattere ed assume come valori:
- 100   lighter
- 300   
- 400   normal (spessore di default dei paragrafi)
- 700   bold
- 900   bolder


text-decoration i valori interessanti sono:
- none
- underline
- line-through (gli sconti)

text-transform i valori interessanti sono:
- uppercase
- lowercase
- capitalize solo la prima lettera in maiuscolo






# Esercizio
Prendendo ispirazione da un blog di ricette già esistente (ad esempio Giallo Zafferano):
- utilizzare due font (presi da Google Fonts - uno per tutti gli elementi ed uno per gli headings tag)
- applicare dei colori (sia sul il testo sia sul background dell'elemento)
- prestando particolare attenzione alla specificità dei selettori!