# Arbeitsblatt: Helligkeit von Sternen – Lösungen
## Teil 1: Scheinbare Sternhelligkeit

### Grundkonzepte

Die **scheinbare Helligkeit** (engl. *apparent magnitude*) ist die Helligkeit, die wir auf der Erde von einem Stern wahrnehmen. Sie hängt ab von:
- Der **Leuchtkraft** $L$ des Sterns (intrinsische Eigenschaft)
- Der **Entfernung** $r$ des Sterns von der Erde

Die scheinbare Helligkeit wird in **Magnituden** (mag) gemessen und folgt einer logarithmischen Skala:

$$m_1 - m_2 = -2{,}5 \cdot \lg\left(\frac{E_1}{E_2}\right)$$

Umgeformt zur Berechnung von Strahlungsleistungsverhältnissen:

$$\frac{E_1}{E_2} = 10^{\frac{m_2-m_1}{2{,}5}} = 2{,}51^{m_2-m_1}$$

**Wichtig**: Kleinere Magnituden bedeuten hellere Sterne! Ein Stern mit $m=1\,\text{mag}$ ist heller als einer mit $m=6\,\text{mag}$.

**Referenzpunkt**: Der Stern Wega hat die Helligkeit $m=0\,\text{mag}$.

---

### Aufgabe 1: Helligkeitsverhältnis zweier Sterne

**Aufgabe**: Zwei Sterne haben die scheinbaren Helligkeiten $m_1 = 6\,\text{mag}$ und $m_2 = 1\,\text{mag}$. Berechnen Sie das Verhältnis ihrer ankommenden Strahlungsleistung pro $\text{m}^2$ auf der Erde.

#### Lösung:

**Gegeben:**
- $m_1 = 6\,\text{mag}$ (dunklerer Stern)
- $m_2 = 1\,\text{mag}$ (hellerer Stern)

**Gesucht:** $\dfrac{E_2}{E_1}$ (Verhältnis der Strahlungsleistung)

**Rechnung:**

$$\frac{E_2}{E_1} = 10^{\frac{m_1-m_2}{2{,}5}}$$

$$\frac{E_2}{E_1} = 10^{\frac{6-1}{2{,}5}} = 10^{\frac{5}{2{,}5}} = 10^2 = 100$$

**Ergebnis:** Der Stern mit $m_2 = 1\,\text{mag}$ ist **100-mal heller** als der Stern mit $m_1 = 6\,\text{mag}$.

Das heißt, die ankommende Strahlungsleistung pro $\text{m}^2$ des helleren Sterns ist 100-mal größer.

---

### Aufgabe 2: Vergleich Sonne – Vollmond

**Aufgabe**: Berechnen Sie, um welchen Faktor sich die Strahlungsleistung pro $\text{m}^2$ von Sonne ($m_\odot = -26{,}7\,\text{mag}$) und Vollmond ($m_{\text{Mond}} = -12{,}7\,\text{mag}$) unterscheiden.

#### Lösung:

**Gegeben:**
- Sonne: $m_\odot = -26{,}7\,\text{mag}$
- Vollmond: $m_{\text{Mond}} = -12{,}7\,\text{mag}$

**Gesucht:** $\dfrac{E_{\odot}}{E_{\text{Mond}}}$

**Rechnung:**

$$\frac{E_\odot}{E_{\text{Mond}}} = 10^{\frac{m_{\text{Mond}} - m_\odot}{2{,}5}}$$

$$\frac{E_\odot}{E_{\text{Mond}}} = 10^{\frac{-12{,}7 - (-26{,}7)}{2{,}5}} = 10^{\frac{14}{2{,}5}} = 10^{5{,}6}$$

$$10^{5{,}6} \approx 398\,107 \approx 4{,}0 \times 10^5$$

**Ergebnis:** Die Sonne ist etwa **400\,000-mal heller** als der Vollmond (genauer: $3{,}98 \times 10^5$ mal).

Dies erklärt, warum wir die Sonne mit blendendem Licht sehen, während der Vollmond nur schwach leuchtet.

---

## Teil 2: Absolute Sternhelligkeit

### Grundkonzept

Die **absolute Helligkeit** $M$ ist die scheinbare Helligkeit, die ein Stern hätte, wenn er sich in einer Standardentfernung von **10 pc** (Parsec) von der Erde befinden würde.

**Konversion**: $1\,\text{pc} = 3{,}26\,\text{Lichtjahre} \approx 3{,}086 \times 10^{16}\,\text{m}$

Die absolute Helligkeit ermöglicht einen direkten Vergleich der **Leuchtkraft** von Sternen, unabhängig von ihrer tatsächlichen Entfernung.

### Entfernungsmodul

Der **Entfernungsmodul** verbindet scheinbare Helligkeit, absolute Helligkeit und Entfernung:

$$m - M = 5 \cdot \lg\left(\frac{r}{10\,\text{pc}}\right)$$

Umformen nach $r$:

$$r = 10\,\text{pc} \cdot 10^{\frac{m-M}{5}}$$

Umformen nach $M$:

$$M = m - 5 \cdot \lg\left(\frac{r}{10\,\text{pc}}\right)$$

---

### Aufgabe 3: Absolute Helligkeit der Sonne

**Aufgabe**: Die scheinbare Helligkeit der Sonne beträgt $m_\odot = -26{,}7\,\text{mag}$. Berechnen Sie daraus ihre absolute Helligkeit.

#### Lösung:

**Gegeben:**
- $m_\odot = -26{,}7\,\text{mag}$ (scheinbare Helligkeit)
- $r_\odot = 1\,\text{AE} = 1{,}496 \times 10^{11}\,\text{m}$

**Konversion der Entfernung zu Parsec:**

$$r_\odot = 1\,\text{AE} = \frac{1{,}496 \times 10^{11}}{3{,}086 \times 10^{16}} = 4{,}848 \times 10^{-6}\,\text{pc}$$

**Gesucht:** $M_\odot$

**Rechnung mit Entfernungsmodul:**

$$M_\odot = m_\odot - 5 \cdot \lg\left(\frac{r_\odot}{10\,\text{pc}}\right)$$

$$M_\odot = -26{,}7 - 5 \cdot \lg\left(\frac{4{,}848 \times 10^{-6}}{10}\right)$$

$$M_\odot = -26{,}7 - 5 \cdot \lg(4{,}848 \times 10^{-7})$$

$$M_\odot = -26{,}7 - 5 \cdot (-6{,}315)$$

$$M_\odot = -26{,}7 + 31{,}575 = 4{,}875\,\text{mag}$$

**Ergebnis:** Die absolute Helligkeit der Sonne ist $M_\odot \approx 4{,}9\,\text{mag}$ (oder genauer: $4{,}83\,\text{mag}$).

**Interpretation:** Bei einer Entfernung von 10 pc würde die Sonne etwa so hell wie ein mittelheller Stern am Nachthimmel erscheinen – keineswegs besonders leuchtend!

---

### Aufgabe 4: Parallaxe und absolute Helligkeit von Spica

**Aufgabe**: Der Stern Spica in der Jungfrau besitzt eine jährliche Parallaxe von $\pi = 0{,}013''$ (Bogensekunden). Seine scheinbare Helligkeit beträgt $m = 0{,}98\,\text{mag}$. Berechnen Sie seine absolute Helligkeit.

#### Lösung:

**Gegeben:**
- Parallaxe: $\pi = 0{,}013''$
- Scheinbare Helligkeit: $m = 0{,}98\,\text{mag}$

**Schritt 1: Entfernung aus Parallaxe berechnen**

Die Parallaxe ist definiert als:

$$r[\text{pc}] = \frac{1}{\pi[\text{Bogensekunden}]}$$

$$r = \frac{1}{0{,}013} = 76{,}92\,\text{pc}$$

**Schritt 2: Absolute Helligkeit berechnen**

$$M = m - 5 \cdot \lg\left(\frac{r}{10\,\text{pc}}\right)$$

$$M = 0{,}98 - 5 \cdot \lg\left(\frac{76{,}92}{10}\right)$$

$$M = 0{,}98 - 5 \cdot \lg(7{,}692)$$

$$M = 0{,}98 - 5 \cdot (0{,}886)$$

$$M = 0{,}98 - 4{,}43 = -3{,}45\,\text{mag}$$

**Ergebnis:** Die absolute Helligkeit von Spica ist $M \approx -3{,}5\,\text{mag}$.

**Interpretation:** Spica ist ein sehr leuchtkräftiger Stern. Trotz der Entfernung von etwa 77 pc ist sie für uns sichtbar, weil sie intrinsisch sehr hell ist (große negative absolute Helligkeit).

---

### Aufgabe 5: Entfernung von Beteigeuze

**Aufgabe**: Der Stern Beteigeuze (Schulterstern des Orion) hat eine absolute Helligkeit von $M = -5{,}7\,\text{mag}$ (bekannt aus dem Spektrum). Seine scheinbare Helligkeit beträgt $m = 0{,}4\,\text{mag}$. Berechnen Sie die Entfernung von Beteigeuze.

#### Lösung:

**Gegeben:**
- Absolute Helligkeit: $M = -5{,}7\,\text{mag}$
- Scheinbare Helligkeit: $m = 0{,}4\,\text{mag}$

**Gesucht:** $r$ in Parsec und Lichtjahren

**Rechnung mit Entfernungsmodul:**

$$m - M = 5 \cdot \lg\left(\frac{r}{10\,\text{pc}}\right)$$

$$0{,}4 - (-5{,}7) = 5 \cdot \lg\left(\frac{r}{10\,\text{pc}}\right)$$

$$6{,}1 = 5 \cdot \lg\left(\frac{r}{10\,\text{pc}}\right)$$

$$\lg\left(\frac{r}{10\,\text{pc}}\right) = \frac{6{,}1}{5} = 1{,}22$$

$$\frac{r}{10\,\text{pc}} = 10^{1{,}22} = 16{,}6$$

$$r = 16{,}6 \times 10\,\text{pc} = 166\,\text{pc}$$

**Konversion zu Lichtjahren:**

$$r = 166 \times 3{,}26\,\text{Lj} \approx 541\,\text{Lj}$$

**Ergebnis:** Beteigeuze ist etwa **166 pc** oder **540 Lichtjahre** entfernt.

**Interpretation:** Beteigeuze ist ein Roter Überriese mit enormer Leuchtkraft. Trotz einer Entfernung von über 500 Lichtjahren ist er mit bloßem Auge sichtbar und gehört zu den hellsten Sternen am Himmel.

---

## Zusammenfassung: Wichtige Formeln

| Konzept | Formel | Anwendung |
|---------|--------|-----------|
| **Helligkeitsverhältnis** | $\dfrac{E_1}{E_2} = 2{,}51^{m_2-m_1}$ | Vergleich von Strahlungsleistungen |
| **Entfernungsmodul** | $m - M = 5 \lg\left(\dfrac{r}{10\,\text{pc}}\right)$ | Zusammenhang Helligkeit-Entfernung |
| **Entfernung aus Helligkeit** | $r = 10\,\text{pc} \cdot 10^{\frac{m-M}{5}}$ | Parallaxe-freie Entfernungsmessung |
| **Parallaxe zu Entfernung** | $r[\text{pc}] = \dfrac{1}{\pi[\text{Bogensekunden}]}$ | Direkte Entfernungsmessung |

---

## Weitere Informationen

Für detaillierte Erklärungen und interaktive Aufgaben siehe:
- **Scheinbare Sternhelligkeit**: https://www.leifiphysik.de/astronomie/fixsterne/grundwissen/scheinbare-sternhelligkeit
- **Absolute Sternhelligkeit**: https://www.leifiphysik.de/astronomie/fixsterne/grundwissen/absolute-sternhelligkeit

**Quelle:** LEIFIphysik – Physik für die Schule