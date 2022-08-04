## Allgemeine Hinweise
Bitte **klicken** Sie auf den **verschwommenen Bereich**, 
sodass dieser teilweise scharf dargestellt wird und 
**beantworten Sie die Frage** so gut Sie können.  

* Die **Frage ist immer oben im verschwommenen Bereich** zu 
finden.  
* Die **Antworten** sind **unten** 
* Es ist **immer nur EINE Antwort** richtig.

Wenn Sie **auf den verschwommenen Bereich klicken**, 
wird die **angeklickte Stelle scharf** gestellt.<br>Wenn Sie nun auf eine **andere Stelle klicken**,
 wird die **Erste wieder unscharf** und die **neue Stelle scharf**.  
 Falls das **Bild bei Ihnen nicht lädt**, wechseln Sie bitte auf einen anderen Tab und dann wieder zurück.<br> Wenn Sie noch keinen anderen Tab offen haben, bitte öffnen Sie Einen und wechseln dann auf diesen Tab zurück.  
## Informationen zu DIESER FRAGE
Hier wird nach der Zeile gefragt, die **während des Ausführens des Programms**
die Variable mit dem einzelnen höchsten numerischen Wert hat.  
Wenn es **mehrere Variablen mit dem gleichen Wert** gibt, dann zählt die, 
die **zuerst** in der Ausführung des Programms vorkommt.      
Es werden alle Zahlen betrachtet, als würden sie das **Dezimalsystem** benutzen.  
Strings/Chars/Words/ähnliches sind hier ausgeschlossen. 
  
  Wenn Zahlen in einem String gespeichert werden, zählen diese als Zahlen, nicht als String.  
  
**Arrays** sind eine Liste von Zahlen, und zählen **NUR** dann, wenn nach einem **EINZELNEN Wert** gefragt wird.  
Hier zählen sowohl **einzelne Elemente der Liste** (Nur, wenn es einzeln aufgerufen wird),  
als auch  **Eigenschaften der Liste** (Bsp: Array.length).   
Es wird **IMMER nur nach Integer** Werten gesucht.  
Negative Zahlen sind laut Definition kleiner als positive Zahlen, selbst, wenn der Betrag größer ist.      
Es werden die Variablen **in Laufzeit** betrachtet,
sodass in einer Zeile eine Variable unterschiedliche Werte haben kann,  
zum Beispiel, wenn sie in einer Schleife vorkommt.    


-------------------
*(answer shown after completing the question | Antwort wird nach der Beantwortung der Frage gezeigt)*

------------------------


## Die Antwort
Die richtige Antwort in diesem Fall ist die Zeile 5.  
Hier ist hat 'array.length' den größten Wert im Snippet. Der Wert von 'array.length' ist 5.    

Zwar gibt es auch bei **Zeile 2** die Liste, die bei array[4] == 5 ist, jedoch wird das Element hier nicht einzeln aufgerufen. 

In **Zeile 6** wird das letzte Listenelement im letzten Durchlauf der Zeile aufgerufen, 
jedoch passiert das zeitlich nachdem nach 'array.length' gefragt wird.              

In **Zeile 9** wird das Ergebnis abgefragt, aber dieses ist hier nicht unbedingt von Belang. 
Ausserdem ist es zu diesem Zeitpunkt "-15", was auch kleiner als 5 wäre.  
