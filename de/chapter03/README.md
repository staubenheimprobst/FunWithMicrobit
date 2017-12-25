# Hallo Micro:bit

## Was lernst du in diesem Kaptiel?

* anzeigen eines Text auf deinem BBC Micro:bit
* Schleifen

## Wie du einem Micro:bit hallo sagst

Dein Micro:bit kann sehr viele Dinge, aber du musst Ihm sagen wer Sie erledigen soll.
Das ist wie, als wenn du dir überlegst, was du als nächstes tust und es dann ausführst.

Es ist jetzt Zeit den **MuEditor** zu öffnen und die ersten Zeilen zu schreiben:

```python
# Das ist ein Kommentar
from microbit import display
```

STOP !

Lass uns über die ersten zwei Zeilen nachdenken.
Die erste Zeile startet mit einem # und bedeutet, das es ein Kommentar ist.
Kommentare sind ein Teil des Code in Python, die verwendet werden um eine Information in Python zu hinterlassen.

Die zweite Zeile ist wesentlich wichtiger. Wir sagen Python, das es das Modul _display_ aus microbit laden soll.

Was ist ein Modul?
Module sind eine Ansammlung von Python Code die uns dabei helfen das _display__ zu verwenden.


now we can ask Micro:bit to display our text
jetzt können wir dem Micro:bit sagen, das er unseren Text anzeigen soll.

```python
# Das ist wieder ein Kommentar
from microbit import display

display.show("Hallo PutYourNameHere, Ich bin dein Micro:bit")
```

Was haben wir hier jetzt?

In der ersten und zweiten Zeile steht nichts neues.

Aber was ist mit der dritten Zeile?

Wir verwenden jetzt einen Teil des Code, der in _display_ beschrieben ist, und rufen _show_.

Danach schreiben wir unseren Text.

Lass uns das mit einem anderen Text versuchen:

```python
# This is a AGAIN a COMMENT
from microbit import display

display.show("Helloo Poland!)
```

kopiere diesen Text in dein Mu Editor und flash diesen!

Mmmm.... warum bekommst du ein Fehler?

* Das Ausrufezeichen am Ende des Textes verursacht ein Problem
* Der Test ist zu kurz
* Wir brauchen __"__ am Ende des Textes
* Helloo (es muss Hello heißen) ist grammatikalisch nicht korrekt

## Aber warum nur einmal?

Wir setzen __showed__ in unseren Micro:Bit ... aber er wird nur einmal angezeigt.
Was ist, wenn ich aber den Text immer sehen möchte?

Hier wird das Komnzept der Schleife (__loop__) vorgestellt

Mit einer Schleife sagen wir dem Micro:bit, tu es so lang, bis das Ende erreicht ist.

In Python haben wir verschiedene Schleif, wir starten mit der Benutzung der __while__ Schleife.

While wird so lange ausgeführt, bis die Bedingung whar ist.

```python
from microbit import display

while 1>0:
  display.show("Hello Poland!")
```

Probiere diesen Code.

```python
from microbit import display

while 1<0:
  display.show("Hello Poland!")
```

Wir änderten die Bedingung und Sie wird immer falsch sein!

## Was ist der Unterschied bei beiden Code Beispielen?

## Warum ist display nicht direkt unter while?
