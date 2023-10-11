# Logistic-Regression
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/beckceline/Logistic-Regression/HEAD)

In diesem Projekt werden wir mit Fake-Daten zu Werbung arbeiten, die aufzeigen, ob ein Nutzer auf eine Werbeanzeige auf einer Webseite einer Firma geklickt hat oder nicht. Wir werden versuchen ein Modell zu erstellen, das anhand von Nutzereigenschaften vorhersagt, ob dieser auf die Werbung klicken wird oder nicht.

Der Datensatz beinhaltet folgende Eigenschaften:

* 'Daily Time Spent on Site': Zeit auf der Webseite in Minuten
* 'Age': Alter in Jahren
* 'Area Income': Durchschnittliches Einkommen der Region des Nutzers
* 'Daily Internet Usage': Durchschnittliche Minutenzahl die der Nutzer täglich im Internet ist
* 'Ad Topic Line': Überschrift der Werbung
* 'City': Stadt des Nutzers
* 'Male': Ob der Nutzer männlich ist (1) oder nicht (0)
* 'Country': Land des Nutzers
* 'Timestamp': Zeit zu der der Nutzer auf die Werbung geklickt oder das Fenster geschlossen hat
* 'Clicked on Ad': Ob der Nutzer gelickt hat (1) oder nicht (0)

### Schritte

1. Importieren der Libraries:
Wir beginnen damit, die erforderlichen Python-Bibliotheken zu importieren. Diese Bibliotheken ermöglichen uns, Daten zu analysieren und Visualisierungen zu erstellen.

2. Daten einlesen:
Wir laden die Datendatei 'advertising.csv' in einen DataFrame und nennen ihn 'ad_data'. Dieser Schritt ermöglicht uns, auf die Daten zuzugreifen und sie weiter zu untersuchen.

3. Datenüberblick:
Wir betrachten die ersten Zeilen des DataFrames und verwenden die Funktionen 'info()' und 'describe()', um grundlegende Informationen über die Daten zu erhalten.

4. Explorative Datensanalyse:
Wir verwenden die Python-Bibliothek Seaborn, um die Daten zu visualisieren. Wir erstellen Histogramme und Jointplots, um Beziehungen zwischen den Merkmalen zu untersuchen.

5. Logistische Regression:
Die Daten werden in Trainings- und Testsets aufgeteilt, um ein logistisches Regressionsmodell zu trainieren. Dieses Modell soll vorhersagen, ob ein Nutzer auf eine Anzeige klicken wird oder nicht, basierend auf den ausgewählten Merkmalen.

6. Vorhersagen und Auswertung:
Nach dem Training des Modells werden Vorhersagen für die Testdaten getroffen. Anschließend wird ein Klassifizierungsreport erstellt, um die Leistung des Modells zu bewerten. Dieser Report enthält Informationen zur Genauigkeit, Präzision, Rückrufrate und F1-Score des Modells.

### Ergebnis

Das trainierte Modell kann erfolgreich vorhersagen, ob ein Nutzer auf eine Werbeanzeige klicken wird oder nicht, basierend auf den gegebenen Merkmalen. Die Ergebnisse werden im Klassifizierungsreport dargestellt, der eine Genauigkeit von etwa 91% aufweist. Dies deutet darauf hin, dass das Modell gute Vorhersagen treffen kann, ob ein Nutzer auf die Anzeige klicken wird oder nicht.
