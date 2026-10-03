todo

wikipedia dinge ersetzen - alle

erklären was alpha-power ist - sophie

Abbildungen für Alpha nochmal ändern, sodass überschriften weg sind (+ bei beiden abbildungen soll das biosemi an die rechte Stelle (s1, s2, s3)) - sophie

-80 bis 200 ms verzerrt die Werte für durchschnittlichen P1 wert fürs OpenBCI weil das schneller ins negative abfällt --> eig etwas besser - katharina

-alle mal die arbeit durchlesen um alle begriffe eklären zu können im kolloquim

fragen an h:

abbildungen im text kleiner machen und dann in den anhagng packen --> dementsprechend auch ergänzende auswretung für alphapower

seitenabstand nach unten von seitenzahl aus oder von text aus gemessen

können wir im abkürzungsverzeichnis auch schon erklärungen machen oder sollen wir da auf das glossar verweisen

statistische Tests: am Ende entscheiden, ob noch gemacht werden. Falls nein, in Methodik 3.4.3 (Absatz "Latenzvariabilität") "beziehungsweise statistisch verglichen" streichen, weil in 4.3 steht, dass auf Tests verzichtet wurde. Falls ja, 4.3 anpassen - alle


---------------------------------------------
SOPHIE - MORGEN (04.10.)
---------------------------------------------
METHODIK ERGÄNZEN
- 3.4.3 P1: Filtergrenzen des ERP-Zweigs angeben (in 3.4.1 steht nur "eigene Filtergrenzen", keine Werte)
- 3.4.3 P1: Epochenlänge in Zahlen (z.B. -200 bis 800 ms) und Basislinie -200 bis 0 ms
- 3.4.3 P1: welche Elektroden genau = "okzipito-parietale Region" (bei beiden Systemen dieselben?)
- 3.4.3 P1: Überschrift "Manuelle Epochierung" -> passt nicht, gemeint ist Epochenauswahl/Artefaktbereinigung
- 3.4.3 P1: Anzahl verworfener Epochen + entfernter ICA-Komponenten je System/Bedingung angeben
- 3.4.3 P1: SNR-Definition aus 4.3 hierher (Verhältnis mittlere P1-Amplitude / Standardabweichung Basislinie)
- 3.4.3 P1: Absatz "Latenzvariabilität" passt nur zur Spitzenwert-Methode; ihr nutzt den Mittelwert -> kürzen
- 3.4.4 Alpha: Rangfolge + Spearman-Rangkorrelation (Grenze rho >= 0,5, Cohen 1988)
- 3.4.4 Alpha: 2-s-Analyse (Abschnitte, Alpha-Power je Abschnitt, Schwelle in der Mitte zwischen EO- und
  EC-Mittel, 2-fache Kreuzvalidierung, balancierte Trefferquote, Zufallsgrenze ca. 62 % nach Müller-Putz 2008)
- Entscheidung Zeitfenster P1 (siehe Kritik unten)

KRITIK ERP-AUSWERTUNG (für Methodik bzw. Diskussion)
- Zeitfenster 80-200 ms ist zu breit: P1-Peak liegt bei 100-130 ms, N1-Peak bei ca. 170 ms (eigene Tabelle 2.2)
  -> die N1 fällt ins Fenster und drückt den Mittelwert, bei OpenBCI stärker (fällt schneller ins Negative,
  Katharinas Punkt). Besser aus der Theorie begründetes engeres Fenster (z.B. 80-130 ms) und neu rechnen.
- Durchschnittsreferenz über 16 (OpenBCI) bzw. 32 Kanäle (BioSemi) an verschiedenen Positionen ->
  Amplituden sind dadurch nicht direkt vergleichbar (Diskussion)
- unterschiedliche Abtastraten 125 vs. 512 Hz (Diskussion; ggf. erwähnen, ob angeglichen)
- SNR hängt von der Anzahl gemittelter Epochen ab -> Epochenzahl je System angeben, sonst ist der
  SNR-Vergleich unfair
- manuelle Epochenauswahl ist subjektiv (wer, nach welchen Regeln, gleich für beide Systeme?)
- Theorie (2.4.5) sagt auch kürzere Latenz bei großem Kontrast voraus, Latenz wird aber nicht
  ausgewertet -> in Diskussion als Grenze nennen
- Kriterium Hypothese 4 "im Mittel größer": zusätzlich angeben, bei wie vielen der 6 Personen groß > klein
- Reihenfolge immer s1 -> s2 -> s3 (Müdigkeit, Reaktionszeit 4.2) -> Diskussion

ERGEBNISSE 4.1-4.3 (eigene Teile)
- SNR-Einzelwerte je System angeben (Hypothese 5: SNR > 1 bei beiden)
- Epochenzahlen je System/Bedingung
- ggf. neues Zeitfenster -> Tabelle 4.1 neu

SONST
- Autorenschaft 2.6 mit Katharina klären (Seitenzahlen!)
- Diskussion: Aufteilung in der Gruppe festlegen
