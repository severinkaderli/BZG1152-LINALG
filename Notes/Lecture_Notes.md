# Modulinformationen

**Modul:** BZG1152-LINALG  
**Dozent:** Lorenz Frey

## Modulunterlagen

Alle Unterlagen zum Modul sind auf Moodle zu finden:  
https://moodle.bfh.ch/course/view.php?id=16730

**Zugriffscode:** LinAlg_2018

## Hauptthemen

* Komplexe Zahlen
* Matrizen
* Lineare Gleichungssysteme
* Analytische Geometrie
* Vektorräume
* Lineare Abbildungen
* Matlab

# Komplexe Zahlen

Komplexe Zahlen sind eine Gruppe von Zahlen, die nach den Reelen Zahlen kommen. Komplexe Zahlen bestehen dabei aus zwei Teilen. Einem Realteil und einem Imaginärteil. Im Imaginärteil wird auch noch die Imaginäre Einheit $i$ oder $j$ eingeführt. Häufig wird die Variable $z$ gebraucht um eine Komplexe Zahl darzustellen.

Für die Imaginäre Einheit ist folgende Eigenschaft definiert:

$$j^{2} = -1$$

## Algebraische Form

Die Erste Form der komplexen Zahlen ist die Algebraische Form. Sie besteht aus dem Realteil $Re(z)$ und dem Imaginärteil $Im(z)$.

Diese Form nennt man auch Kartesische Form, da man sie  ganz einfach in der Gauss'schen Zahlenebene darstellen kann.

$$z := x + j * y$$

### Beispiele 

$$z_{1} = 2 + 3j$$

$$z_{2} = -7.1 + 5j$$
 
$$z_{3} = -1.1 - 3.4j$$
 
$$z_{4} = 2.3$$   

$$z_{5} = -3.3j$$ 

## Konjugiert Komplexe Zahl
Eine Konjugiert komplexe Zahl entsteht, wenn man das Vorzeichen vom Imaginärteil wechselt.

$$z = x + y * j$$

$$z^* := x - y * j$$

## Betrag
$$|z| := \sqrt{x^{2} + y^{2}}$$

## Polarform
Die Polarform ist eine alternative Schreibform für die komplexen Zahlen. Dafür wird der Betrag $r$ und der Hauptwert des Argumentes $\phi$ benötigt.

$$z = x + y * j = r * (\cos(\phi) + j * \sin(\phi))$$

### Umrechnungsbeispiel
Die Umrechnung von der Kartesischen zur Polarform ist eigentlich recht einfach. Den Betrag $r$ kann man ganz einfach berechnen:

$$r = \sqrt{x^{2} + y^{2}}$$

Das Argument $\phi$ wird je nach Winkel anders berechnet. Folgende Übersicht sollte dabei helfen den korrekturen Wert zu berechnen:
$$
\phi =
\begin{cases}
\pi & \text{für }  x<0, y = 0\\
-arccos(\frac{x}{r}) & \text{für } y < 0\\
arccos(\frac{x}{r}) & \text{sonst}\\
\end{cases}

$$

Um von der Polarform wieder zurück zur Kartesischen-Form zu kommen kann man einfach das $x$ und $y$ mit Trigonometrie berechnen:

$$x = r * \cos(\phi)$$

$$y = r * \sin(\phi)$$

## Exponentialform
Die Exponentialform ist sehr ähnlich wie die Polarform. Man muss genau wie für die Polarform den Betrag $r$ und das Argument $\phi$ berechnet haben.

$$z = r * e^{j * \phi}$$

## Addition und Substraktion mit komplexen Zahlen
Die Addition und Subtraktion mit komplexen Zahlen funktioniert nur in der kartesischen Form und ist ganz einfach. Man addiert bzw. substrahiert einfach jeweils den Realteil und Imaginärteil miteinander.

$$z_{1} + z_{2} := (x_{1} + x_{2} + j * (y_{1} + y_{2})$$

$$z_{1} - z_{2} := (x_{1} - x_{2} + j * (y_{1} - y_{2})$$

## Multiplikation mit komplexen Zahlen
Die Multiplikation kann man in allen Formen durchführen, man muss jedoch jeweils anders vorgehen. In der kartesischen Form kann man ganz einfach die zwei Zahlen algebraisch multiplizieren:

$$z_{1} * z_{2} := (x_{1} * x_{2} - y_{1} * y_{2}) + j * (x_{1} * y_{2} + x_{2} * y_{1})$$

In der Exponentialform kann man ganz einfach die beiden Beträge zusammen multiplizieren und die Argumente addieren:

$$z_{1} * z_{2} := r_{1} * r_{2} * e^{j * (\phi_{1} - \phi_{2})}$$

## Potenzieren mit komplexen Zahlen
$$z^{n} = r^{n} * e^{j * n * \phi}$$

## Division mit komplexen Zahlen
Die Division kann man auch in allen Formen durchführen, wobei es in der Exponentialform viel einfacher ist.

$$\frac{z_{1}}{z_{2}} = \frac{z_{1} * z_{2}^*}{|z_{2}|^{2}}$$

In der Exponentialform geht man ähnlich wie bei der Multiplikation vor. Man dividiert die Beträge miteinander und substrahiert dann die Argumente voneinander.

$$\frac{z_{1}}{z_{2}} = \frac{r_{1}}{r_{2}} * e^{j * (\phi_{1} - \phi_{2})}$$


# Matrizen

# Lineare Gleichungssysteme

# Vektoren

# Vektorräume

$\vec{a}\begin{pmatrix}1 \end{pmatrix}$
