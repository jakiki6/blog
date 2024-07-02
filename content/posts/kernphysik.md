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

![](/images/pu238.png)

Das Glühen kommt von der Zerfallsenergie. Die Raumsonden Voyager 1 und 2 machen sich das zunutze, indem sie Brocken aus Pu-238 an Bord haben und aus der Wärme elektrischen Strom erzeugen. Es gab auch schon Herzschrittmacher mit dem gleichen Prinzip. Komischerweise fand man heraus, dass es eine schlechte Idee ist, Menschen signifikante Mengen an Plutonium zu implantieren.

# Kernspaltung
Nun kommen wir zu der ersten revolutionären Entdeckung, welche zu dem Bau von Atomreaktoren führte.

Wenn U-235 mit einem Neutron getroffen wird, spaltet es sich zu Ba-144 (Barium 144) und Kr-89 (Krypton 89) und **3** Neutronen auf:

![](/images/u235-kernspaltung.png)

Was ist so besonders daran? Die 3 freigesetzten Neutronen können weitere U-235-Kerne spalten. Und diese noch mehr. Und so weiter. Als erstes wird also 1 Kern gespalten. Dann 3. Dann 9. Dann 27. Dann 81. Dann 243. Dann 729. Dann 2187. Dann 6561. Dann 19683. Dann 59049. Dann 177147. Dann 531441. Dann 1594323.

Nach 19 Schritten haben wir über eine Milliarde Kerne gespalten. Und jede Spaltung setzt 200 MeV (eine Energieeinheit) frei. Das entspricht 22.960.000 kWh pro Kilogramm U-235 oder etwa **4,5% des jährlichen Energieverbrauchs von Deutschland**.

# Atomreaktoren
Das ist alles schön und gut, aber wir haben ein Problem: wir wollen nicht 4,5% des jährlichen Energiebedarfs von Deutschland in ein paar Millisekunden freisetzten (dazu kommen wir später).

Ein Atomreaktor hat eine Eigenschaft namens Reaktivität. Diese gibt an, wie viele Kerne ein gespaltener U-235-Kern spaltet. Idealerweise liegt der Wert bei exakt 1. Wenn er kleiner als 1 ist, geht der Reaktor aus. Wenn er größer als 1 ist, sterben alle:

![](/images/reaktivität.png)
