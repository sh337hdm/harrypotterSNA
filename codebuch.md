# Codebuch
Forschungsfrage: Wie haben sich die Karrieren der Harry Potter Schauspieler seit ihrem Debüt in der Filmreihe entwickelt?

## Inhalt 

edgelistpotter.csv 

nodelistpotter.csv

# EDGE-Attribute

**from**

ID der initiierenden Knoten der Schauspieler, Film, Produktionsfirma, Regisseur, Kooperation, Engagement etc.

**to**

ID der erhaltenden Knoten Schauspieler, Film, Produktionsfirma, Regisseur, Kooperation, Engagement etc.

**relation**

1=Darsteller

2=Produzent

3=Regie

4=Werbepartner

5=Engagement

6=Synchronsprecher

# NODE-Attribute

**id**

IDs aus der Edgelist (from & to Spalte)


**name**

Vor- und Nachname bei Personen, vollständiger Name bei nicht Personen


**type**

1=Person 

2=keine Person 


**age**

Alter des Schauspielers bei Erscheinung des Projekts


**year**

Erscheinungsjahr des Projekts


**sector**

1=Film

2=Serie

3=Werbung

4=Theaterstück

5=Musikvideo

6=Sonstiges

7=Darsteller

8=Regisseur

9=Produktion


**genre**

1=Action

2=Drama

3=Thriller

4=Horror

5=Fantasy

6=Komödie

7=Dokumentation

8=Animation

9=Sonstiges


**country**

Herkunftsland des Beitrags bzw. des Projekts


**production**

Die (größte) Produktionsfirma des Beitrags


**regie**

Vor- und Nachname des Regisseurs



# Codierregeln: 

**1. Abkürzung von Namen in id:**

Beispiel:

moonwalkers -> id: mooonwalkers (Eintragungen mit nur einem Wort, bleiben nur ein Wort) 

sick note -> id: sino (Eintragungen mit zwei oder mehr Wörtern, werden die ersten beiden Buchstaben genutzt) 

The one and only -> id: thonanon

No one left to blame -> id: noonletobl

**2. Genres von imbd** 

Die Genres der Filme werden von imbd genutzt. Nur wenn sich dort keine finden lassen, dürfen auch welche von anderen Plattformen eingetragen werden.

**3. Produktionsstudios** 

Falls mehrere Produktionsstudios beteiligt sind, wird nur das Größte genannt.

**4. Regisseur**

Es wird nur ein Regisseur angegeben. Immer der, der als erstes gelistet wird. 

**5. Keine Sonderzeichen, Umlaute** 

Die Verschwörung - keine Gnade -> die Verschwoerung keine Gnade -> id: divekegn
