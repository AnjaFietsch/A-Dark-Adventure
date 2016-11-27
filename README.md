##### Anmerkung
Ich habe an dem Projekt "A Dark Adventure" alleine gearbeitet, obwohl wir zu zweit an einem Projet arbeiten sollten. Ich hatte davor mit Thao Mi zusammengearbeitet. Wir haben uns gemeinsam mit den Funktionen von App Lab und der Block-Programiersprache auseinadergesetzt und schon zusammen den Grundstein für das Spiel "Drinking Game" gelegt. Leider sind im Verlauf der Entwicklungen Unstimmigkeiten aufgetreten, weshalb wir uns entschlossen hatten getrennte Wege zu gehen. Ich war darauf nicht unvorbereitet, denn ich hatte mir schon ein Konzept für ein anderse Spiel ausgedacht.


# A Dark Adventure
Ein kleines Spiel mit eigenen Zeichnungen.

[1. Vertrautmachen mit App Lab](#1)     
[2. Kriterien für das Erstellen einer App ](#2)  
[3. Erstellen von A Dark Adventure](#3)  
[4. Reflektion](#4)

##<a name="1"></a>Vertrautmachen mit App Lab
In den ersten Stunden habe ich mich mit der Internetseite [App Lab](https://code.org/educate/applab) vertraut gemacht. Ich habe mir die Videos angeschaut und die Aufgaben gemacht, wie man hier sehen kann. ![Kurs 1](https://code.org/v2/hoc/certificate/ewogICJuYW1lIjogIkFuamEiLAogICJjb3Vyc2UiOiAiY291cnNlMSIsCiAgImNvdXJzZV90aXRsZSI6ICJLdXJzIDEiCn0=.jpg)
In den nächsten Kurseh habe ich die Aufgebn  bearbeitet, bis ich die Funktion verstanden hatte.   
Die Videos waren sehr hilfreich, zum Verstehn von App Lab und dass sie alle auf Englsich waren, hat mir auch sehr viel Spaß beim zu schauen gemacht.

##<a name="2"></a> Kriterien für das Erstellen einer App 

Zunächst fange ich an, indem ich den Begriff "App" erkläre.  
Eine App, oder auch Application Software, ist nicht notwendig für ein System, weshalb es eher als eine Erweiterung, mit denen der Nutzer sein Gerät beliebig erweitern kann, verstanden wird. Es ist ein kleines Computerprogramm, mit denen verschiedenste Zusatzaufgaben bearbeitet werden können. Zum Beispiel kann man mit ihnen die Wartezeit verürzen, indem man eine Sieleapp spiel, oder sie zählen die Schritte, die man täglich läuft, um sich zu erinnern, nicht nur rumzusitzen. 
Eine App kann auf IOS oder Android geladen werden, nur gibt es da auch wieder unterschiede, die bei den Programmiersparachen anfangen. Für IOS braucht man die Programmiersprache Objectiv-C oder Swift und für Android setzt man Java ein.   

Im nächsten Schritt habe ich mir Gedanken gemacht, was man braucht und worauf man achten sollte, wenn man eine App erstelln möchte. Im Internet habe ich gute Kriterien gefunden, die ich umzusetzen versucht habe.  

1. Welchen Zweck erfüllt die App?  
  Soll sie zur Unterhaltung dienen, oder dem Nutzer anderweitig behilflich sein, wie zum Beispiel bei der Wegfindung, oder ist sie eine   App zu einer Internetseite.  
  - In meinem Fall habe ich mich für eine Spieleapp entschieden. Ihr Zweck ist es Spaß zu machen und zu Unterhalten. Ich habe mir auch gedacht, dass es ein guter Einsieg für meine erste App wäre.
  
2. Welche Zielgruppe soll angesprochen werden?
  Die Zielgruppe bestimmt wie das Desing, die Nutzersprache und am Ende das ganze Erscheinungsbild der App ausfällt.  
  - Es gibt verschiedene Millieus, mit denen mn sich vorher auseinander gesetzt haben muss, um seine richtige Zielgruppe zu ermitteln. ich habe mir dabei die Grafik von Sinus-Milieus zu nutze gemacht. ![Sinus-Milieus](http://www.sinus-institut.de/fileadmin/user_data/sinus-institut/Bilder/sinus-mileus-2015/2016-02-08_Website-Abbildungen_Die_Sinus-Milieus_in_Deutschland_2016.png)  Es wird die Mittlere Mittelschicht, die Traditionellen aber auch die Modernisierung, die Bürgerliche Mitte ansprechen. Die Zielgruppe soll im Alter von 15-30 Jahren liegen und spricht auch Menschen älterer Generationen an, weil sie Spiel gespiel hatten, indenen es noch keien menschenähnlichen Animationen gab. In den älteren Spielen wurden meist Geschichten Erzählt, die man durch verschiedene Möglichkeiten beeinflussen konnte. Dazu später mehr.
  
3. Für Welches Betriebssystem soll die App verwendet werden?
  Das Betreibssystem ist naheliegend mit der Zielgruppe und dem Budget, dass man bereitgestellt hat. Bei einer hohen Zielgruppe für ein   Betriebssyste, ist die Wahrscheinlichkeit höher, das die App geladen wird.
  - Das Betriebssystem ist schwer auszusuchen, aber da ich mich mehr mit IOS auskenne, würde ich sagen, das man es auf Apple-Geräten spielen kann.
  
4. Wie soll das Desing ausfallen?
  Das Aussehend der App darf nicht von anderen Seiten oder Apps kopiert werden, aber man kann sich verschiedene Desings anschauen und sich von ihnen inspirieren lassen.
  - Für die Idee und das Desing sind mir viel Beispile Eingefallen. Zum einen hat mich das Video von App Lab "How to make a choose your own adventure Game" dazu inspiriert ein Adventure Game zu machen, weil man dabei sehr viel eigene Fantasie einbringen und eine Art kleine interaktive Geschichte erstellen kann. Ich habe mir auch das Spiel ["A Dark Room"](http://adarkroom.doublespeakgames.com/mobileWarning.html) aus dem Apple Store geladen, um mr die Strucktur nochmal anzuschen. In diesem Fall ist noch sehr viel mehr dazugekommen, als in einem reinen Text-Adventure. Hier wird gezählt, wie viel Einwohner in der Stadt sind, die man sich aufbaut und man kann viele Sachen aus dem Inventar sammeln und verkaufen oder etwas daraus bauen. 
  
##<a name="3"></a> Erstellen von A Dark Adventure

Für den Anfang von A Dark Adventure habe ich mir eine Mind Map erstellt, mit der ich die einzelnen Wege vernetzt habe. 
![Lösungswege für A Dark Adventure](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_0862%5B1%5D.PNG) Ich habe mir viel Mühe dabei gegeben, viele spannende Elemente und unerwartete Wendungen reinzubekommen. Auf App Lab habe ich die Screens zuerst schwarz gemacht, dann habe ich mir eine Geschichte dazu ausgedacht und schließlich kann man in zwei verschiedene Richtungen gehen, die ich durch Buttons programiert habe. Jeder Button führt zu einem bestimmten Screen, der dem Nutzer wieder zwei verschiedene Möglichkeiten zum fortfahren gibt.

Ich habe außerdem zu ein paar Screens ein Bild gezeichnet. Dafür habe ich mir eine Vorlage aus dem Internet gesucht und diese auf meine Ansprüche umgewandelt. Für die Bilder habe ich das Programm [Krita](https://krita.org/en/) benutzt und auf einem Tablet gezeichnet. Für den ersten Screen mit Bild habe ich ein Lagerfeuer gewählt, weil es die Stimmung, dass man alleine im Wald am Feuer sitzt unterstützen soll. Man soll denken, dass man sich in dem Augenblick vor dem Lagerfeur befindet. ![Lagerfeuer](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/Feuer.jpeg)
Für die Schuhe habe ich das Bild von ein paar Herrenschuhen gespiegelt und diese dann gezeichnet.
![Herrenschuhe](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/JRCL5694%5B1%5D.jpg?raw=true)

Begonnen habe ich mit leichten Bleistiftlinien, um die Umrisse darzustellen. Als nächstes bin ich auf einer neuen Folie die Bleistiftzeichnungen nachgefahren, um schonmal die Outlines fertig zu haben. Nun muss man die Fraben einfügen. Dabei probiert man ein bisschen aus, welche Farben zu den Schuhen passen könnten. Ich habe mich für Rot, Blau und ein leichtes Grün entschieden. Zum Schluss muss alles nur noch schattiert werden , damit die Schuhe auch plastisch aussehen. ![Schuh, Schattenfolie](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_2213%5B1%5D.JPG?raw=true)
Hier kann man gut sehen, was ich mit "Ebene" meine. Es gibt die Funktion neue Ebenen einzufügen und mit anderen verschmelzen zu lassen. Die Ebenen können auch einzeln an- und ausgeschaltet werden, wenn man sich nicht sicher ist, ob eine Änderung gut war, oder nicht, anstatt sie neu hinzumalen und wieder wegzuradieren, denn auf den Ebenen ist alles, was sich nicht auf ihnen befindet fest und kann nich verändert werden. Herrausgekommen ist dann das hier: ![Schuh, selbst gezeichnet](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_2214%5B1%5D.JPG?raw=true)

Damit man aber nicht einen weißen Kasten in den Screens hat, muss man natürlich auch den Hintergrund schraz einfärben, aber damit sich die Stellen der Schuhe nicht auch mit dunkler färben, muss man den Platz für die Schuhe weiß lassen. Die Farben überlagern sich nämlich von Folie zu Folie immer mehr. ![Schuh, weißer Platz](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_2216%5B1%5D.JPG?raw=true)

Das Gleiche habe ich auch mit den anderen Bildern gemacht.

![Nachricht](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/Nachricht.jpeg?raw=true)
Um die verwitterte Textur des Papriers zu kreieren, habe ich verschiedene Braun und Gelbtöne mit verschieden großen Pinseln benutzt. Manche machen sehr kleine, feine Punkte und andere sind da etwas grober. Man darf nur nicht übertreiben, denn sonst sieht das Blatt eher angemalt, als verwitert aus.

![Fuß](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_2206%5B1%5D.PNG?raw=true)

![Fuß, selber gemalt](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_2219%5B1%5D.JPG?raw=true)
Den Fuß habe ich zuerst ohne Verletzungen gemalt, damit ich die Schattierungen besser abstimmen konnte. Den Blutverlauf habe ich dannach auf einer neuen Ebene gezeichnet.

![Schwert](https://s-media-cache-ak0.pinimg.com/236x/f6/ea/59/f6ea5975fc5f2f22f9900418a8f9e9a4.jpg)

![Schild](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/IMG_2223%5B1%5D.PNG?raw=true)

![Schwert und Schild](https://github.com/AnjaFietsch/A-Dark-Adventure/blob/master/Schwet%20und%20Schild%20Game.jpeg?raw=true)

Schwert und Schild habe ich beides nacheinander gezeichnet und abgespeichert, damit ich die beiden Sachen auch noch nicht angelehnt von einander habe. Davon habe ich eine Kopie gemacht, in der ich die linke Seite vom Schild ein wenig verkürtzt und dunkler gefärbt habe. Bei dem Schwert bin ich genauso vorgegangen. Beim letzten Schritt bin ich aber nicht mit der Perspektive zufrieden. Es sollte so aussehen, als ob Schwert und Schild aneinander und an der Wand lehen und der Schatten ist in diesem Falle weiß und nicht schwarz. Zum einen, damit man die Umrisse deutlicher sieht und die Bilder dadurch ein wenig leuchten, was für den anderen Bildern auch zutrifft.

Die Bilder sollen ein wenig mehr Farbe in das Dark Adventure bringen und damit man sich fragt: Habe ich schon alle Bilder gefunden? Das wäre noch ein Grund, es nocheinmal zu spielen.

##<a name="4"></a>Reflektion

Ich komme nun zum Abschluss meines Projektes und möchte noch hinzufügen, dass es mir wirklich sehr viel Spaß gemacht hat, an dem Mini-Adventure zu arbeiten. Ich habe viel über das Programmieren an sich gelernt und es hat auch sehr viel Freude gemacht di Bilder dafür zu gestalten. Für die Schuhe hatte ich ca. 4 Stunden gebrauch, weil ich noch ein paar neuere Pinsel verwendet habe. Für die anderen Bilder hatte ich ca. zwei Stunden pro Bild benötigt. Ich habe, meiner Meinung nach die Schlagwörter in Bilder verwandelt, die einen besonderen Einfluss auf die Geschichte ausüben. Damit bin ich sehr zufrieden. Sehr gefällt mir das Muster vom Schwert, das ich auch in das Schild mit eingearbeitet habe.
Ein paar negative Punket muss ich aber auch noch erwähnen, und zwar, dass sich App lab nicht so richtig gut eignet, für Text-Adventure, weil man ein sehr kleinens Teld zum, schreiben hat. Das heißt dann wenn man einen fehler gemacht hat, muss man in diesem kleinen fenster mühevoll danach suchen, obweohl man ihn im Vorschauscreen links schon entdeckt hat. Für mich wäre App Lab also eine Programierplattform, um Apps zu programmieren, die mit eher weniger Text auskommen würden.

Ich hätte ab
