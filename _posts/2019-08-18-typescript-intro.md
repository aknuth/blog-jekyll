---
layout: post
title:  "Typescript Einführung"
author: aknuth
categories: [ Typescript, tutorial ]
image: assets/images/prog1.jpg
featured: true
hidden: false
---

Letztens stand ich vor der Herausforderung, das mein jüngster Sohn mich gebeten hatte, mit ihm das Programmieren zu beginnen ...
Als freiberuflicher Entwickler ist man ja ständig am experimentieren, sucht nach optimalen Lösungen und steckt auch viel Freizeit in die Weiterbildung 😇
Das bekommen Kinder (vermutlich insbesondere Söhne) natürlich mit und versuchen oftmals den Eltern nach zu eifern.

Auf der Suche nach geeigneter Literatur bin ich auf das Buch "Hello World - Programmieren für Kids und andere Anfänger" gestoßen. Das gefiel mir didaktisch sowie inhaltlich wirklich gut - leider verwendet der Author Python als Programmiersprache. Nicht das ich Python als eine ungeeignete oder schlechte Programmiersprache empfinde - nur leider bin ich (wohl auch beruflich bedingt) inzwischen ein großer Fan des JavaScript Ökosystems geworden und insbesondere hat mich Typescript als Sprache so angefixt, das ich auch gerne mit meinem Sohn diesen Weg gehen wollte ...

Natürlich kommt jetzt direkt die Frage auf: Warum entwickelt ihr nicht direkt in Javascript ? Das ist für Anfänger einfacher 

Jetzt ist Typescript unglücklicherweise keine Sprache für die es eine Laufzeitumgebung gibt, sondern der geschrieben Code muss erst nach Javascript "transpiliert" werden. Dieser Vorgang soll natürlich für den Anwender möglich im Verborgenen ablaufen, so das der nicht von den erzeugten Javascript mitbekommt.

Damit ergab sich die Aufgabe: Wie setze ich eine Entwicklungsumgebung auf, in der mein Sohn Typescript Programme erstellen kann und diese sowohl zum Laufen bekommt als auch bei Bedarf debuggen kann .... Puuuhhh, gar keine so einfache Aufgabe 😬

Ich beschreibe in diesem Blog Artikel meine Vorgehensweise von der ich denke, das sie einigermaßer konfortabel zu handhaben ist. Über Verbesserungsvorschläge freu ich mich jederzeit - diese bitte bei Bedarf unten im Disqus Bereich eintragen.
 
1. Wahl des Editors
Das Thema war sehr schnell erledigt. Die Wahl fällt auf Visual Studio Code - dieser Editor steht kostenlos zur Verfügung, unterstützt grundsätzlich Typescript Compiling sowie Autocompletion.

A major clue to everything that truly happened was the scene that played next under the credits - hospital staff failed to bring a patient back to life with a defibrillator after a car accident. Chest compressions failed and there was no pulse. A second major clue was provided by hospital orderly Travis (Stephen Graham): <span class="spoiler">Everybody dies. No mystery there. But why and how everyone dies. Now, there's a mystery worth solving. Probably the biggest mystery there is.</span>

#### So how do we do spoilers?

```html
<span class="spoiler">My hidden paragraph here.</span>
```
