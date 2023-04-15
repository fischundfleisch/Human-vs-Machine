# Human-vs-Machine

Das ist ein SPS-Programm, das teilweise auch SCL enthält. Menschliche Zeiten werden gemessen, sortiert und in ein Highscore board eingetragen. Dazu wird der Insert Sort 
verwendet. Anschließend wird auf einem HMI die Platzierung sowie die Top Platzierungen ausgegeben.

Max:
Unbedingt den "Startwert" deiner ganzen Ints im Array in der Tabelle anklicken und 32000 reinschreiben. In jeden einzelnen Platz. Das Array machst du von 0..4 zu 0..29, damit du 30 Plätze füllen kannst. Und jeder davon braucht als Startwert 32000. Ist der Startwert nämlich 0, dann ist die vom Spieler erreichte Zeit immer größer als alles, was im Array gespeichert ist. Damit wird dir nie eine andere Zeit hinein geschrieben.
