# Reflexion Noel
Grundaufbau der Pipeline
- Die Pipeline startet automatisch bei einem Push auf den main-Branch. In CI 1 wurde die grundlegende Pipeline eingerichtet. CI 2 ergänzte automatisierte Tests mit Jest sowie das Linting. In CI 3 wurden diese Schritte in drei Jobs aufgeteilt: lint, test und deploy. Die Bereitstellung wird derzeit durch eine einfache Meldung simuliert.
Überlegungen zu den einzelnen Schritten
- Ich fand es sinnvoll, Tests und Linting einzubauen, damit Fehler automatisch erkannt werden. Durch die Aufteilung in mehrere Jobs ist die Pipeline übersichtlicher.
Kritik und Verbesserungsmöglichkeiten
- Wir hätten die Aufgaben teilweise strukturierter angehen können. Gerade bei den ersten Versuchen hatten wir ein paar Fehler, konnten diese aber gemeinsam lösen. Einmal hatten wir ja das yml gepusht obwohl wir noch nichts bearbeitet haben. Ebenfalls hatten wir kleine Probleme mti github, obwohl ich Ron eingeladen habe konnte er erst nicht mitarbeiten.
Vorgehensweise und Zusammenarbeit
- Wir haben die Aufgaben zu zweit an meinem Laptop Schritt für Schritt umgesetzt. Um weitere Github Probleme zu vermeiden
Mein persönlicher Beitrag
- Ich habe zusammen mit Ron die Aufgaben Schritt für Schritt bearbeitet. Wir haben die einzelnen Schritte gemeinsam besprochen und entschieden, wie wir die Pipeline aufbauen. Da wir nur an meinem Laptop gearbeitet haben, habe ich die Änderungen und Tests praktisch umgesetzt, während wir uns dabei gegenseitig unterstützt haben.
Fazit
- Die Aufgaben haben mir ein besseres Verständnis dafür vermittelt, wie eine CI/CD-Pipeline aufgebaut ist und wie GitHub Actions funktioniert. Die Zusammenarbeit mit Ron verlief gut, auch wenn wir aufgrund der Laptop-Situation nicht direkt gemeinsam am Repository arbeiten konnten. Wir konnten die im Zuge unserer Zusammenarbeit aufgetretenen Probleme lösen.


----------------------------------------------------
# Reflexion Ron

Kritik an der zukünftigen Pipeline
- Deployen ist gerade gerade nur eine Meldung aber es gibt noch kein wirkliches Deployment
- Pipline ist noch zu einfach/klein
- Pipeline sollte mehr aufgeteilt werden (am besten in 3 Jobs)
- Das Projekt könnte grösser sein also so wie in einer Grossfirma zb wo ich arbeite bei der AXA.

Vorgehensweise/Rollenverteiung
- Wir haben die Aufgaben auf dem Laptop von Noel gemacht weil wir am anfang github Probleme hatten und auch merge Konflikte einfachkeitshalber vermeiden wollten
- Aufgabe 1
  - Haben wir allen von hand gemacht
  - Beim ref-card projekt vom Unterricht konnten wir nachschauen wie es geht
- Aufgabe 2
  - Mehrheitlich mit KI und wir waren die "Coaches" von KI und haben es am ende überarbeitet 
- Aufgabe 3
  - KI hat das Gerüst für die Jobs gemacht 
  - und wir haben es ergänzt und haben uns erklären lassen wie es funktioniert
      - also zb die Verwendung von actions/checkout um die Dateien aus dem Repository zu holen
      - actions/setup-node um die Node Version zu setzen 

Fazit
- -Ich finde es witzig, dass man während der Prüfung oft einiges lernt. Bei dieser Prüfung lernte ich von der Menge her mindestes so viel wie im Unterricht. Vom Inhalt her lernte ich das wo ich vorher Lücken hatte.
- Verstehe jetzt workflows von der Grundlage her recht gut. Mich würde es noch wunder nehmen, wie es in einem grossen Fullstack Projekt aussehen würde.