# ⚡ Gradient Boosting Lab

**ML Learning Lab · Projekt 5 · Supervised Learning**

Interaktive, deutschsprachige Lernanwendung zum **Gradient Boosting für Regression**. Läuft vollständig im Browser und benötigt keine Bibliotheken, Installation, Server oder API-Schlüssel.

## Lernziele

- Unterschied **Random Forest vs. Gradient Boosting** verstehen
- Den **Startwert** (Mittelwert) nachvollziehen
- Verstehen, wie jeder neue Baum **Residuen** korrigiert
- Einfluss von **Lernrate**, **Baumtiefe**, **Boosting-Schritten** und **Rauschen** untersuchen
- **Trainings-MSE und Test-MSE** vergleichen
- Overfitting im Lernlabor entdecken
- **Eigene Vorhersagen** und die Beiträge der einzelnen Bäume prüfen
- Hell-/Dunkelmodus, responsive Bedienung, **kein Quiz**

## Start

`index.html` lokal im Browser öffnen oder mit GitHub Pages veröffentlichen.

## GitHub Pages aktivieren

Im Repository unter **Settings → Pages** die Option **Deploy from a branch** auswählen. Dann Branch **main**, Ordner **/ (root)** und **Save**.

Die spätere Projektadresse lautet bei einem Repository `UISY/gradient-boosting-visualizer`:

`https://uisy.github.io/gradient-boosting-visualizer/`

## Didaktischer Hinweis

Diese Demo implementiert **Gradient Boosting Regression mit MSE** selbst in JavaScript: ein konstanter Startwert, anschließend kleine Regressionsbäume, die nacheinander Residuen lernen. Die Trainingsdaten werden zufällig in 75 % Training und 25 % Test aufgeteilt. Der Testdatensatz wird **nicht** zum Fitten verwendet. Für den allgemeinen Gradient-Boosting-Algorithmus hängen Pseudo-Residuen von der Verlustfunktion ab; hier ist MSE gewählt, damit die Fehlerkorrektur besonders anschaulich ist.
