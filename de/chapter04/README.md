# Animmationen

## Was wir in diesem Kapitel lernen?

* Anzeigen von Text auf deinem BBC Micro:bit
* Anzeigen von Bildern auf deinem BBC Micro:bit
* Kombinieren von Bildern und Text

## Anzeien von Bildern

Anzeigen von Text ist okay ... aber was ist mit Bilder?!

Lass uns starten mit etwas witzigem. :)

```python
from microbit import *

display.show(Image.HAPPY)
```

Hast du den Code auf deinen Micro:bit gespielt?

Es zeigt sich uns ein klügliches Bild!

Ein Liste der Bilder, die du verwenden kannst:

```python
Image.HEART
Image.HEART_SMALL
Image.HAPPY
Image.SMILE
Image.SAD
Image.CONFUSED
Image.ANGRY
Image.ASLEEP
Image.SURPRISED
Image.ROLLERSKATE
Image.DUCK
Image.HOUSE
Image.TORTOISE
Image.BUTTERFLY
Image.STICKFIGURE
Image.GHOST
Image.SWORD
Image.GIRAFFE
Image.SKULL
Image.UMBRELLA
Image.SNAKE
```

__Nimm dir 5 Minuten und spiele mit den Bildern.__

Versuche das und nimm mal mehr als ein Bild!

```python
from microbit import *

display.show(Image.HAPPY)
display.show(Image.HOUSE)
```

Lass uns über das Ergebnis reden. :)

# Showing 2 images

Wir sehen nicht das erste Bild ....Micro:bit führt das zweite Bild so schnell aus, das wir das erste nicht sehen.

Lass uns dem Micro:bit sagen...er soll schlafen (sleep).

Das spezielle Kommando heißt sleep(seconds*1000) versetzt dein Micro:bit zu einer bestimmten Zeit in Schlafmodus.

Fügen Sie deiese Kommando sleep(seconds*1000) hinzu und ersetzen Sie _seconds_ mit einer Zahl die der Micro:bit schlafen soll.

```python
from microbit import *

display.show(Image.HAPPY)
sleep(10*1000)
display.show(Image.HOUSE)
```

Flash den Code und beschreibe das Resultat.

# Bau dein Bild!

Der Micro:bit kennte viele Bilder. Aber lass uns ein eigenes Bild bauen.

So funktioniert das.

```python
from microbit import *

new_image = Image(
             "11111:"
             "19991:"
             "19991:"
             "19991:"
             "11111")
display.show(new_image)
```
Wir haben ein neues Bild erzeugt!

Aber was sagen die Nummer aus?

Wir haben fünf Zeilen und fünf Nummern in jeder Zeile ...

Das sind unsere LED's!

Jeder Nummer repräsentiert eine LED auf unserem Micro:Bit, von Links oben.

Aber wir haben 0, 1 und 9.

Kannst du sagen, was sich verändert wenn du die Zahlen zwischen 0, 1 oder 9 veränderst?

Hinweis: du kannst Nummern zwischen 0 und 9 verwenden.

Experimentiere!
