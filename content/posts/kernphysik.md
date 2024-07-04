+++
title = 'Kernphysik'
date = 2024-07-02T22:48:06+02:00
draft = true
+++

# Atome
Wahrscheinlich hast du im Chemie- oder Physikunterricht schonmal von Atomen gehört. Atome werden in der Schule meistens als die kleinsten Bauteile von Materie angesehen. Aber auch Atome lassen sich weiter zerlegen. Ein Atom besteht aus einem Atomkern und einer Elektronenhülle. Der Atomkern enthält Protonen, welche positiv geladen sind, und Neutronen, welche neutral sind. Die Elektronenhülle enthält Elektronen, welche negativ geladen sind. Damit ein Atom neutral ist, enthält die Elektronenhülle ein Elektron für jedes Proton im Kern. Neutronen kann man dabei ignorieren, weil sie ja schon neutral sind. Die Eigenschaften eines Atoms, also z.B. welches Element es ist, wird durch die Anzahl der Protonen bestimmt. Wasserstoff hat ein Proton im Kern. Kohlenstoff hat 6 und Uran hat 92. 

# Isotope
So weit, so gut. Aber was machen die Neutronen? Neutronen haben keinen direkten Einfluss auf die Eigenschaften eines Atoms. Wasserstoff gibt es zum Beispiel in 3 Varianten:

![https://commons.wikimedia.org/wiki/File:Hydrogen_Deuterium_Tritium_Nuclei_Schmatic-de.svg](/images/isotope_wasserstoff.png)

Diese Varianten nennt man Isotope. Deuterium ist ein Isotop von Wasserstoff, welches sich chemisch kaum von Protonium (das "normale" Wasserstoff) unterscheided. Es ist halt einfach nur schwerer, weil es ein extra Neutron im Kern hat. Tritium ist noch schwerer und ist zudem radioaktiv (später dazu mehr). Da beide Isotope häufig verwendet werden, hat Deuterium das Symbol D und Tritium das Symbol T.

Isotope stellt man normalerweise wie folgt da: nach unten kommt die Anzahl der Protonen, nach oben die Anzahl der Protonen und Neutronen und danach das chemische Symbol für das Element.

So können wir ableiten, dass Deuterium ein Isotop von Wasserstoff ist, welches ein Proton und ein Neutron besitzt.

Da die Protonenzahl ja durch das Element schon angegeben ist (Wasserstoff hat *immer* ein Proton), gibt man häufig nur die obere Zahl an.

Die wichtigsten Isotope für den restlichen Text werden die folgenden Sein: U-235, U-238, Pu-238, Pu-239, Bi-209 und Po-210. U steht für Uran, Pu für Plutonium, Bi für Bismuth und Po für Polonium.

# Radioaktivität

Ein weiterer wichtiger Baustein ist die Radioaktivität.

Prinzipiell gibt es nur 2 Arten von Radioaktivität, die uns interessieren:
- es kann einen Heliumkern auswerfen, also ein Atomkern mit 2 Protonen und 2 Neutronen
- es kann ein Elektron auswerfen und dabei ein Neutron zu einem Proton abändern
- es kann ein Photon, also ein Lichtteilchen auswerfen

Die erste Zerfallsart nennt man sehr kreativ auch Alphazerfall. Der Heliumkern wird dann auch Alphateilchen genannt. Wenn ein Atomkern ein Alphateilchen auswirft, verliert es 2 Protonen und rutscht im Periodensystem der Elemente 2 Plätze zurück. Zudem verliert es 4 "Masseneinheiten". Wenn also Po-210 zerfällt, wirft es 2 Protonen und 2 Neutronen aus und wird zu Pb-206, also Blei:

![](/images/pse-polonium.png)

Die zweite Zerfallsart nennt man noch kreativer auch Betazerfall. Im inneren des Atomkerns verwandelt sich ein Neutron spontan in ein Proton und Elektron, welche genau wie das Neutron zusammen neutral sind. Das Elektron wird aus dem Kern ausgeworfen und das Element rückt im Periodensystem einen Platz nach vorne, behält aber die gleiche Masse. Wenn also Tritium zerfällt, verwandelt sich eins der beiden Neutronen zu einem Proton und ein Elektron wird ausgeworfen, wodruch der Atomkern zu einem Helium-3 Kern wird (2 Protonen und ein Neutron).

Es gibt auch noch den Beta-Plus-Zerfall, bei dem ein Proton im Kern zu einem Neutron wird und dabei ein Antimaterie-Elektron auswirft. Kalium-40 macht das zum Beispiel, wodurch du Antimaterie ausstrahlst. Cool, oder?

Bei der Radioaktivität gibt es aber noch einen weiteren wichtigen Aspekt: die Halbwertszeit. Die Halbwertszeit ist die Zeit, die eine Menge von Atomkernen eines Isotops braucht, damit die Hälfte der Atomkerne zerfällt. Tritium hat z.B. eine Halbwertszeit von 12,33 Jahren. Also sind nach 12,33 Jahren nur noch die Hälfte der Tritium-Kerne da. Die andere Hälfte ist in der Zeit zu Helium-3 zerfallen. Nach weiteren 12,33 Jahren ist nur noch ein Viertel der Anfangsmenge da. Nach weiteren 12,33 Jahren nur noch ein Achtel usw. Te-128 (Tellur 128) ist das Isotop mit der längsten bekannten Halbwertszeit mit schlappen 7.700.000.000.000.000.000.000.000 Jahren.

Es ist noch wichtig zu erwähnen, dass bei jedem Zerfall Energie freigesetzt wird. Das ist der Grund, warum Atommüll gekühlt werden muss, weil er sich sonst selbst schmilzt. Das kann man aber auch ausnutzen, indem man Pu-238 verwendet. Dieses Isotop hat eine Halbwertszeit von 87,7 Jahren und strahlt enorme Mengen an Wärmeenergie aus:

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="/images/pu238.png" alt="Pu-238 am glühen" height="300"/>
    <img src="https://imgs.xkcd.com/comics/plutonium.png" alt="relevant xkcd" height="300" />
</div>

Das Glühen kommt von der Zerfallsenergie. Die Raumsonden Voyager 1 und 2 machen sich das zunutze, indem sie Brocken aus Pu-238 an Bord haben und aus der Wärme elektrischen Strom erzeugen. Es gab auch schon Herzschrittmacher mit dem gleichen Prinzip. Komischerweise fand man heraus, dass es eine schlechte Idee ist, Menschen signifikante Mengen an Plutonium zu implantieren.

# Kernspaltung
Nun kommen wir zu der ersten revolutionären Entdeckung, welche zu dem Bau von Atomreaktoren führte.

Wenn U-235 mit einem Neutron getroffen wird, spaltet es sich zu Ba-144 (Barium 144) und Kr-89 (Krypton 89) und **3** Neutronen auf:

![](/images/u235-kernspaltung.png)

Was ist so besonders daran? Die 3 freigesetzten Neutronen können weitere U-235-Kerne spalten. Und diese noch mehr. Und so weiter. Als erstes wird also 1 Kern gespalten. Dann 3. Dann 9. Dann 27. Dann 81. Dann 243. Dann 729. Dann 2187. Dann 6561. Dann 19683. Dann 59049. Dann 177147. Dann 531441. Dann 1594323.

Nach 19 Schritten haben wir über eine Milliarde Kerne gespalten. Und jede Spaltung setzt 200 MeV (eine Energieeinheit) frei. Das entspricht 22.960.000 kWh pro Kilogramm U-235 oder etwa **4,5% des jährlichen Energieverbrauchs von Deutschland**.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://imgs.xkcd.com/comics/log_scale.png" style="max-width: fit-content; margin-left: auto; margin-right: auto;" />
</div>

# Atomreaktoren
Das ist alles schön und gut, aber wir haben ein Problem: wir wollen nicht 4,5% des jährlichen Energiebedarfs von Deutschland in ein paar Millisekunden freisetzten (dazu kommen wir später).

Ein Atomreaktor hat eine Eigenschaft namens Reaktivität. Diese gibt an, wie viele Kerne ein gespaltener U-235-Kern spaltet. Idealerweise liegt der Wert bei exakt 1. Wenn er kleiner als 1 ist, geht der Reaktor aus. Wenn er größer als 1 ist, sterben alle:

![](/images/reaktivität.png)

Atomreaktoren sind vom Aufbau her sehr einfach: es gibt einen Behälter, in dem Stäbe aus U-238 und U-235 sind, zwischen die man Bremsstäbe schieben kann und die von einem Moderator umhüllt sind. Bremsstäbe sind meistens aus Bor, welches Neutronen gut absorbiert, damit man die Kettenreaktion kontrollieren kann, indem man überschüssige Neutronen abfängt. Der Moderator ist meistens entweder Wasser, schweres Wasser (Wie normales Wasser, nur, dass die 2 Wasserstoffatome in H2O durch Deuterium ersetzt wurden) oder Graphit (eine Form von Kohlenstoff). Dieser bremst die entstehenden Neutronen ab, da diese sonst viel zu schnell sind und somit keine realistische Chance haben, andere U-235-Kerne zu treffen. Die freigesetzte Energie wird genutzt, um Wasser zu erhitzen, welches in Turbinen dann zu Strom umgewandelt wird. Statt U-235 kann man auch Pu-239 oder U-233 als Brennstoff nutzen, wozu wir später noch kommen.

Die Bremsstäber werden dynamisch ein- oder ausgefahren, damit die Reaktivität bei ~1 bleibt. In einer Notfallsituation können alle Bremsstäbe gleichzeitig eingefahren werden, obwohl das eher einem Einschießen ähnelt, um den Reaktor sofort zu stoppen.

## Chernobyl

Sehr wahrscheinlich hast du schonmal von dem Unglück in Chernobyl gehört. "Chernobyl" war die Explosion des vierten Reaktorblocks des Kernkraftwerks Chernobyl in der ukrainischen Stadt Prypjat am 26. April 1986 um 1:23 Uhr und 44 Sekunden.

Nur was lief schief? Ein paar Dinge.

Für einen Test wurde der Reaktor zuvor auf eine niedrigere Leistung gefahren, indem mehr Bremsstäbe eingefahren wurden. Das ist ein fataler Fehler bei Atomreaktoren, da sich dadurch das Isotop I-135 (Iod 135) ansammelt, da es nicht mehr durch die überschüssigen Neutronen "verbrannt", also abgebaut, wird. Aber was ist das Problem mit I-135? Es zerfällt mit einer Halbwertszeit von 19 Sekunden zu Xe-135 (Xenon 135). Xe-135 ist der stärkste Neutronenabsorbator, den wir kennen, und "frisst" die Neutronen aus der Spaltung praktisch auf, wodurch der Reaktor eine niedrigere Reaktivität hat. Deswegen schaltet man Reaktoren erst 3 Tage nach der Abschaltung wieder an, da bis dahin das Xe-135 vollständing zerfallen ist. Aufgrund des Drucks, den Test endlich durchzuführen und gleichzeitig genug Strom zu liefern, wurde dies nicht getan.

Genau das passierte auch in Chernobyl. Man kam auf die geniale Idee, die Bremsstäbe einfach mehr rauszuziehen, damit die Leistung wieder steigt. Ein fataler Fehler. Das Xe-135 wird von den Neutronen "verbrannt" und ist ab einer bestimmten Zeit abgebaut, wodurch der Reaktor wieder normal läuft. Durch das Rausziehen der Bremsstäbe ist jetzt aber die Leistung sehr viel höher als sie sein sollte.

Diesen Fehler bemerkte man dann um 1:23 Uhr und 40 Sekunden.

Die Lösung? AZ-5. AZ-5 war ein Knopf im Kontrollraum, welcher sofort alle Bremsstäbe in den Kern schieben sollte.

Es gab nur ein Problem: Chernobyls Reaktor nutzte Graphit als Moderator. Die Spitzen der aus Bor bestehenden Bremsstäbe waren aus Graphit. Das Einfahren der Bremsstäbe steigerte also die Reaktivität. Das wäre normalerweise kein Problem, da man normalerweise Wasser als Moderator nutzt, welcher sofort verdampft und somit die Reaktion stoppt, da der Moderator weg ist. Graphit verdampft aber nicht. Wenige Millisekunden vor der Explosion war die Leistung des Reaktors über 100 mal so hoch wie die vorgesehende Maximalleistung.

Der Reaktorkern in Block 4 wurde zu einer kleinen Atombombe (man erinnere sich an die vorherige Grafik über Reaktivität). Durch die enorme Hitze reagierte das Kühlwasser mit dem Graphit und dem Zirconium (ein Metall, welches in den Bremsstäben als Stabilisation verwendet wird, da es Neutronen ungehindert durchlässt), wodurch sich Wasserstoff bildete. Dieses explodierte wenige Sekunden später und zerstörte das Dach, wodurch der Großteil des Reaktorinhalts ausgeworfen wurde.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/IAEA_02790015_%285613115146%29.jpg/800px-IAEA_02790015_%285613115146%29.jpg" height="700"/>
</div>

Man geht davon aus, dass mehr als 100.000 Menschen an den Folgen des Zwischenfalls starben. Die Zone um Chernobyl ist bis heute unbewohnbar. Russische Soldaten sind auch schon gestorben, weil sie in der Nähe von Chernobyl Schützengräben gebuddelt haben und den Staub dabei eingeatmet haben.

Und man hätte es so einfach verhindern können:
- keinen Betrieb bei niedriger Leistung
- keine Bremsstäbe mit Graphit
- kein Graphit als Moderator

## Fukushima
Der Vorfall in Fukushima ist sehr einfach zu erklären: durch fehlende Kühlung schmolzen die Brennstäbe durch die Zerfallshitze der Spaltprodukte. Dadurch entstand durch die Reaktion von Zirconium mit Wasser wieder Wasserstoff, welcher detonierte.

Auch das hätte man sehr einfach verhindern können:
- Reaktor nicht **direkt am Meer bauen**
- Notstromaggregate nicht in den Keller stellen
- Kern notkühlen, was auch ohne Strom gehen sollte
- Kern "lüften", um Wasserstoff loszuwerden

Der Betreiber wusste von den Mängeln, entschied sich aber aus Kostengründen, nichts zu tun.

# Brennstoffproduktion
Das ist ja alles schön und gut. Aber wie stellt man den Brennstoff eigentlich her?

Natürliches Uran enthält nur 0,7% U-235 und 99,3% U-238, welches unspaltbar ist. Man muss mindestens 3% U-235 haben, um es in Reaktoren zu verwenden, und mindestens 90%, um es in Atombomben zu verwenden.

## Isotopseparierung
Aber wie macht man das? Uran ist chemisch gesehen Uran. Es gibt nur einen minimalen Unterschied: ein U-238-Kern ist 1,28% schwerer als ein U-235-Kern.

Wenn man also Atomkerne nach ihrer Masse trennen könnte, könnte man U-235 anreichern. Dazu gibt es prinzipiell 2 Wege.

### Diffusionsmethode
U-238 ist etwas träger als U-235. Wenn man also Uran gasförmig macht, indem man es mit Fluor zu Uranhexafluorid umwandelt, kann man es in eine Kammer mit kleinen Membranen leiten. Das Gas, welches durch die Membranen dringt, enthält minimal mehr U-235 als U-238.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d7/Gaseous_Diffusion_%2844021367082%29_%28cropped%29.jpg?20190316135514" height="300" />
</div>

Diese Methode ist sehr ineffizient, da das Uran in jedem Schritt um sage und schreibe 0,43% angereichert wird. Wenn man diesen Prozess 12 mal durchläuft, hat man reaktorfähiges Uran. Für waffenfähiges Uran sind es dann schon 150 mal.

Deswegen hat man ein neues Verfahren entwickelt:

## Zentrifugen
Wenn man das Urangas in eine Zentrifuge gibt und diese schnell dreht, sammelt sich das schwerere U-238 an den Rändern und das leichtere U-235 in der Mitte. Damit kann man einen Seperationsfaktor von bis zu 20% erreichen. Das ist sehr viel mehr als die 0,43% der Diffusionsmethode und ist auch sehr viel effizienter.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d8/HEUraniumC.jpg/1024px-HEUraniumC.jpg" height="300" />
</div>

# Brüter
Vorhin meinte ich, dass man auch Pu-239 als Brennstoff nutzen kann. Dieses kommt aber in der Natur nicht vor. Was macht man also?

Wenn U-238 von einem Neutron getroffen wird, wird es zu U-239.

U-239 zerfällt mit einer Halbwertszeit von 23 Minuten zu Np-239 (Neptunium 239).

Np-239 zerfällt mit einer Halbwertszeit von 2,3 Tagen zu Pu-239.

Man kann also mit überschüssigen Neutronen aus einem Atomreaktor Pu-239 "brüten". Zudem enthält Atommüll Pu-239, da ein Großteil der Brennstäbe aus U-238 bestehen. Um waffenfähiges Pu-239 zu produzieren, lässt man einen Reaktor 3 Monate laufen und bereitet dann den anfallenden Müll chemisch auf, um das Plutonium zu extrahieren.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0f/Plutonium_ring.jpg/800px-Plutonium_ring.jpg" height="300" />
</div>

# Atomwaffen
Nun kommen wir zu dem interessanten Teil dieses Beitrags: Atomwaffen.

Atomwaffen oder auch Atombomben haben ein sehr einfaches Funktionsprinzip: Chernobyl nachstellen.

Wenn man bewusste die Reaktivität auf das Maximum erhöht, setzt man die gesammte Spaltenergie in kurzer Zeit frei.

Da sowohl Uran als auch Plutonium natürlich kleine Mengen an Neutronen ausstrahlen, gibt es eine sogenannte Kritische Masse, ab der ein Haufen des Isotops spontan eine Reaktivität von über 1 erreicht und explodiert.

Bei U-235 liegt diese bei 56kg oder eine Kugel mit einem Durchmesser von 17,32cm. Bei Pu-239 liegt sie bei 11kg oder einer Kugel mit einem Durchmesser von 10,2cm.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Partially-reflected-plutonium-sphere.jpeg" height="400" />
</div>

Prinzipiell gibt es 2 Wege, diese Kritische Masse gezieht zu erreichen, ohne sich dabei in die Luft zu jagen.

## Gun
Der erste Weg ist sehr intuitiv: man trennt die Kugel in 2 Hälften, welche beide nicht kritisch sind, und setzt sie zusammen, wenn man eine Detonation will.

In der Bombe, die auf Hiroshima geworfen wurde, wurde genau das getan. An einem Ende war ein Projektil aus U-235, welches in ein Ziel am anderen Ende geschossen wurde, welches auch aus U-235 bestand:

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Gun-type_fission_weapon_en-labels_thin_lines.svg/670px-Gun-type_fission_weapon_en-labels_thin_lines.svg.png" height="300" />
</div>

Dieses Design hat ein paar Probleme:
- wenn man die Bombe ausversehen fallen lässt, detoniert sie
- man braucht **sehr viel** teueres U-235
- man kann kein Pu-239 verwenden

Pu-239 reagiert "zu schnell" auf eine Kritische Masse und detoniert, bevor das Projektil das Ziel trifft. Dadurch zerstört sich die Bombe selbst, bevor sie überhaupt die Chance hat, irgendwas zu tun.

## Implosion
Es gibt noch einen zweiten Weg, welcher mittlerweile das Standard ist: Implosionslinsen.

Wenn man eine nicht-kritische Menge an Pu-239 genug komprimiert, wird sie trotzdem kritisch.

Wenn man also eine Kugel aus Plutonium mit Sprengstoff umhüllt und diesen Millisekundengenau detoniert, kann man eine Druckwelle erzeugen, die den Kern genug komprimiert.

Zudem enthält die Kugel im Kern eine kleine Menge an Po-210 und Beryllium, welche zusammen Neutronen produzieren, um der Reaktion einen Schub zu geben.

Dieses Design benötigt weniger Material und wurde in der Bombe von Nagasaki verwendet.

Zudem wird der Kern mit U-238 umhüllt, da dieses sehr träge ist und somit der Reaktion mehr Zeit bietet, bis sich der Kern durch den Druck zerstört. Das kann die freigesetzte Energie signifikant erhöhen.

<div style="max-width: fit-content; margin-left: auto; margin-right: auto;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Implosion_Nuclear_weapon.svg/661px-Implosion_Nuclear_weapon.svg.png" height="300" />
</div>
