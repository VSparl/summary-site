# Demographie - Teil 2
Vielen Dank an _Jarquantavious_ für die Zusammenfassung!

## Demografische Kennzahlen
### Mathematische Grössen

- **Geburtenrate**: Lebendgeborene pro 1000 Personen pro Jahr
    - $r = \frac{G}{B} \cdot 1000$

- **Sterberate**: Todesfälle pro 1000 Personen pro Jahr
    - $r = \frac{T}{B} \cdot 1000$

- **Fertilitätsrate**: Durchschnittliche Anzahl Kinder, die eine Frau in ihrem reproduktiven Alter (meist 15–49) gebärt.
    - Das **Ersatzniveau** liegt bei etwa **2.1 Kindern** pro Frau (erhält die Bevölkerungszahl ohne Migration).

- **Lebenserwartung**: Erwartete durchschnittliche Lebensjahre **bei Geburt**
    - stark empfindlich gegenüber Gesundheitsversorgung und Kindersterblichkeit

- **Natürliches Bevölkerungswachstum**: Beschreibt die Zu- bzw. Abnahme einer Bevölkerung innerhalb eines bestimmten Zeitraumes.
    - $r = \frac{(E - A)}{B} \cdot 1000$

- **Migrationsrate**: Saldo Einwanderung minus Auswanderung pro 1000 Personen pro Jahr.
    - $r = \frac{(E - A)}{B} \cdot 1000$

- **Bevölkerungsdichte**: Einwohner pro Flächeneinheit (z. B. Einwohner/km²)
    - sagt etwas über Siedlungsdruck, Infrastrukturbedarf und ökologische Belastung

### Indikatoren

- **BNE per capita**
	- **B**rutto**n**ational**e**inkommen
	- Das Einkommen aller Bürger pro Einwohner vor Steuern
	- Lässt Ungleichheit, Lebenszufriedenheit, Umweltbelastung aus
    - $r = \frac{E}{B}$

- **HDI (Human Development Index)**
	- Besteht aus drei Dimensionen:
        - Leben und Gesundheit
        - Schulung
        - Finanzielle Stärke
    - Es wird das geometrische Mittel von Lebenserwartung, erwartete Bildungsjahren und durchschnittliche Bildungszeit, BNE Index berechnet.
	- HDI liegt zwischen 0 und 1:
		- **Sehr hoch** ($\geq 0.800$)
		- **Hoch** ($0.700 - 0.799$)
		- **Mittel** ($0.550-0.699$)
		- **Tief** ($\lt 0.550$)
	- Lässt Ungleichheit, Umweltbelastung, Lebenszufriedenheit aus

- **GINI-Koeffizient**
	- Die Lorenzkurve zeigt die Einkommensverteilung einer Bevölkerung
	- Der Gini-Koeffizient zeigt den Anteil der Fläche der Ungleichheit an
    - Messung der Abweichung von einer perfekten Gleichheit
		- Wenn der Koeffizient = 1 &rightarrow; Totale Ungleichheit
		- Wenn der Koeffizient = 0 &rightarrow; Totale Gleichheit

- **BIP (per capita)**
	- Das **B**rutto**i**nlands**p**rodukt gibt den Gesamtwert aller Waren und Dienstleistungen einer Bevölkerung an
    - Wird oft **pro Person** _(= per capita)_ angegeben
	- Lässt Ungleichheit, Lebenszufriedenheit, Umweltbelastung aus

- **SPI (Social progress index)**
	- Grundbedürfnisse: Ernährung, Gesundheit, Sicherheit, Unterkunft
	- Wohlbefinden: BIldung, Umwelt, Lebensqualität, Zugang zu Information
	- Chancen: Rechte, Gleichberechtigung, Bildung

## Bevölkerungsprognosen
### Modelle

**Lineares** Modell:

- $B(t)$ = Anz. Menschen zur Zeit $t$
- $B(0)$ = Anz. Menschen im Ausgangsjahr
- $d$ = Absoluter Bevölkerungszuwachs pro Jahr
- $t$ = Zeit in Jahren
- Anwendung: Wenn Zuwachs konstant in absoluten Zahlen angenommen wird

$$B(t) = B(0) + (t \cdot d)$$

$$d = \frac{1}{t}(B(t) - B(0))$$

$$\text{Verdoppelungszeit } t = \frac{B_0}{d}$$

**Exponentielles** Modell:

- $B(t)$ = Anz. Menschen zur Zeit $t$
- $B(0)$ = Anz. Menschen im Ausgangsjahr
- $r$ = Wachstumsrate pro Jahr **als Dezimalzahl** _(nicht Prozent)_
- $t$ = Zeit in Jahren
- Wichtig: Exponentielles Modell führt langfristig zu deutlich höheren Zahlen; in der Praxis werden Wachstumsraten jedoch meist variabel (Geburten sinken/steigen).

$$B(t) = B(0) \cdot (1 + r)^t$$

$$r = \sqrt[t]{\frac{B(t)}{B(0)}}-1$$

$$\text{Verdoppelungszeit } t = \frac{\log_{10} (2)}{\log_{10}(1+r)}$$

Faustregel zur **Verdoppelungszeit**:

- $r$ = Wachstumsrate **in Prozent**

$$t = \frac{70}{r}$$

## Malthus' Hypothese und Kritik

Der Malthusianismus ist eine **Theorie**, nach der das Bevölkerungswachstum gemäß dem malthusianischen Wachstumsmodell **potenziell exponentiell** verläuft, während das Wachstum der **Nahrungsmittelversorgung** oder anderer Ressourcen **linear** ist, was letztendlich zu einer Verringerung des Lebensstandards bis hin zu einem **Bevölkerungsrückgang** führt. Dieses Ereignis, das als **malthusianische Katastrophe** bezeichnet wird, wird vorhergesagt, wenn das Bevölkerungswachstum die landwirtschaftliche Produktion übersteigt und dadurch Hungersnöte oder Kriege verursacht. Dieser Theorie zufolge nehmen **Armut und Ungleichheit** zu, wenn die Preise für Vermögenswerte und knappe Rohstoffe aufgrund des harten Wettbewerbs um diese schwindenden Ressourcen steigen. Diese zunehmende Armut führt schließlich zu einem **Bevölkerungsrückgang** durch sinkende Geburtenraten. Wenn die Vermögenspreise weiter steigen, kommt es zu sozialen Unruhen, die wahrscheinlich einen großen Krieg, eine Revolution oder eine Hungersnot auslösen würden.

### Kritik

- **Unterschätzung des technischen Fortschritts**
    - Malthus konnte nicht vorhersehen, wie stark die **Landwirtschaft, Industrie und Technik** die Nahrungsmittelproduktion steigern würden _(z. B. durch Düngemittel, Maschinen, Transport)_
    - Ergebnis: Die Produktion konnte **viel schneller** wachsen als linear.

- **Vernachlässigung sozialer und politischer Faktoren**
    - Malthus betrachtete das Problem **nur biologisch** (Bevölkerung vs. Nahrung), ignorierte aber **Ungleichverteilung, Armutspolitik, Bildung und Handel**.
    - Kritiker sagten: **Hunger entsteht nicht durch Mangel**, sondern durch **ungleiche Verteilung**.

- **Falsche Annahme über das Bevölkerungswachstum**
    - In der Realität wächst die Bevölkerung **nicht unbegrenzt exponentiell**.
    - Mit **steigendem Wohlstand, Bildung und Verhütung** sinken Geburtenraten – das nennt man **demografischer Übergang**.

## Nachhaltigkeit und SDGs
### Nachhaltigkeit (Brundtland)

- **Definition (Brundtland-Kommission 1987)**
	- _"Nachhaltige Entwicklung ist eine Entwicklung, die die Bedürfnisse der Gegenwart befriedigt, ohne zu riskieren, dass zukünftige Generationen ihre eigenen Bedürfnisse nicht befriedigen können."_
	- Ein **Gleichgewicht** zwischen wirtschaftlichem Wachstum, sozialer Gerechtigkeit und Umweltschutz schaffen.

- **Nachhaltigkeitsdreieck**
	- **Ökologie**: Schutz von Ressourcen, Ökosystemen und Klima
	- **Ökonomie**: Wirtschaftliche Stabilität und Effizienz, aber ohne Übernutzung von Ressourcen.
	- **Sozial**: Gerechtigkeit, Bildung, Gesundheit, Lebensqualität

### SDGs
- Sustainable Development Goals
- **Ziele**, die die UN erreichen möchte, die mit dem Nachhaltigkeitsdreieck verbunden sind:
	1. Keine Armut
	2. Kein Hunger
	3. Gesundheit
	4. Bildung
	5. Geschlechtsgleichstellung
	6. Sauberes Wasser und Sanitäreinrichtungen
	7. Bezahlbare und saubere Energie
	8. Wirtschaftswachstum durch ethische Arbeit
	9. Industrie, Innovation und Infrastruktur
	10. Weniger Ungleichheiten
	11. Nachhaltige Städte und Gemeinden
	12. Nachhaltiger Konsum und Produktion
	13. Klimaschutz
	14. Leben unter Wasser
	15. Leben an Land
	16. Frieden, Gerechtigkeit, starke Institutionen
	17. Partnerschaft und Kooperation
- Soziales: 1-6, 10, 16
- Wirtschaft: 7-9, 12
- Ökologie: 13-15
- Kooperation: 17

## Historische Entwicklung der Weltbevölkerung

Die Weltbevölkerung wuchs über Jahrtausende nur langsam, da hohe Geburten- und Sterberaten sich ungefähr ausglichen. Mit der **Agrarrevolution** stieg die Ernährungssicherheit leicht, doch erst die **Industrielle Revolution** brachte durch technische und medizinische Fortschritte einen deutlichen Bevölkerungsanstieg. Im **20. Jahrhundert** senkten Hygiene, Impfungen und bessere Lebensbedingungen die Sterblichkeit stark, während die Geburtenraten zunächst hoch blieben – die Bevölkerung explodierte. Dieses Muster beschreibt der **demographische Übergang**: von hohen zu niedrigen Geburten- und Sterberaten, mit einer Wachstumsphase dazwischen.

> Dieser Teil wurde von oder mit KI geschrieben

## Ländervergleiche, Urbanisierung und Migration

Hier geht es um den Vergleich von Ländern anhand von **Bevölkerungsdaten und Entwicklungsindikatoren** wie HDI, TFR, Lebenserwartung oder BIP. Dabei zeigen sich Unterschiede in Lebensstandard, Struktur und Dynamik der Bevölkerung. **Urbanisierung** beschreibt das starke Wachstum von Städten und die damit verbundenen Chancen (Arbeitsplätze, Infrastruktur) und Probleme (Überbevölkerung, Slums, Umweltbelastung). **Migration** erklärt Wanderungsbewegungen zwischen und innerhalb von Ländern: durch **Push-Faktoren** wie Armut oder Konflikte und **Pull-Faktoren** wie Arbeit oder Sicherheit. Diese Prozesse prägen Bevölkerungsverteilung, Wirtschaft und Kultur weltweit.

> Dieser Teil wurde von oder mit KI geschrieben
