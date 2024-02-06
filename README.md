# BBSoft IFC-Verarbeitung

Diese Skripte verarbeiten eine von BBSoft erzeugte IFC-Datei. Hierbei werden verschiedene Korrekturen vorgenommen:

- Verwendung von gültigen IfcPropertyTypes. Standardmäßig werden alle Datenbankfelder als String ausgegeben.
- Die Textfragmente "(ed.)" und "(ber.)" werden aus den Kanalhaltungen entfernt.
- An die Schachtnamen wird standardmäßig ein ",-" hinzugefügt. Dieses wird entfernt.
- Verschiedene Angaben werden in Meter umgewandelt.

# Massenextraktion

Zusätzlich werden verschiedene Massen extrahiert. Diese Funktionalität ist noch sehr rudimentär.

# Verwendung

Einfach das Programm starten und die entsprechend IFC-Datei auswählen.

# Entwicklung

Das Projekt nutzt den Python Paketmanager [Poetry](https://python-poetry.org/docs/).

```
poetry install
poetry run python ibb_ifc\cli.py
poetry run python ibb_ifc\gui.py
poetry run python build_gui.py

```

(C) 2024 IBB Wörn Ingenieure GmbH
