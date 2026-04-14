Steg 1:
"Nav" är till för navigationen längst upp.
"Main" är huvudinnehållet.
"Header" är till för heron.
"Section" är den del korten är i.
"Footer" är den del som är längst ner.

Steg 2:
Nav:
Jag gjorde två klasser, en som heter "logo" och en "nav-list".
På nav gjorde jag så att det allt ska vara i mitten fast att det är ett mellanrum mellan loggan och navigeringslänkarna (justify-content: space-between).

På nav-list, nav a, och logo ändrade jag utseendet på headern.


Hero:
Jag gjorde en klass, "cta-button", och ändrade utseendet på den och allt annat i heron.

Section:
Allt i mitten, flex-wrap, list-style. Jag gjorde så att korten ska vara lika stora med flex: 1;. Jag gjorde så att gap ska vara 3% av fönstret oavsett hur stort det är med vw.

Footer:
Allt i mitten.

------
Gjorde att nav och kort-listan har samma bredd så det ser snyggt ut med width: 70vw; (70% av fönstret)

Media query:
Nav får flex-direction column och lite mer margin längst upp. Cards-list column. Cta-button bredare.