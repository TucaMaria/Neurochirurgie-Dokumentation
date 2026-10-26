# Neurochirurgie – Dokumentation
Version 0.24 · 26.10.2026 · Aufbauphase

Diese Bibliothek unterstützt die sprachliche Erstellung ärztlicher Dokumentation. Sie enthält konsolidierte Nutzerbausteine und vom Nutzer beschriebene Hausabläufe. Offene Varianten stehen in 06_REGISTER/OFFENE_KLAERUNGEN.md. Die Texte sind keine extern geprüften Leitlinien. Alle Dokumente sind ärztlich zu prüfen.

## Einrichtung
1. Krankenhausprofil in 00_GRUNDLAGEN/KLINIKPROFIL.md ergänzen.
2. Eigene Prompts und anonymisierte Muster unter 07_EINGANG ablegen.
3. Regeln konsolidieren; Muster nach Dokumenttyp, Pathologie und Eingriff zuordnen.
4. Referenzindex pflegen und Freigabestatus jeder Vorlage festhalten.
5. Für die Nutzung in einem ChatGPT-Projekt den Master-Prompt als Projektanweisung hinterlegen und benötigte Referenzen bereitstellen. Diese Ordner erzeugen kein ChatGPT-Projekt und keine automatisch installierten Skills.

## Arbeitsablauf
Pro Fall einen eigenen Chat verwenden. Dokumenttyp, Pathologie/Eingriff und Falldaten angeben. Passende Referenzen gezielt lesen lassen. Entwurf und offene Fragen getrennt prüfen. Neue Regeln zentral aktualisieren.

Reale Falldaten nur in einer vom Krankenhaus freigegebenen Umgebung verarbeiten. Diese Startbibliothek enthält keine Patientendaten. Fallvorlagen nicht als ausgefüllte Patientenarchive in dieser gemeinsamen Referenzbibliothek speichern.

## Wichtigste Änderung in v0.24
Entlassbriefe synthetisieren OP-Berichte (normalerweise 1–2 ergebnisorientierte Sätze), interpretieren Radiologiebefunde neurochirurgisch knapp und verdichten Visiten zu einem logischen klinischen Verlauf. Ausführlichkeit bedeutet Relevanz und klinische Vollständigkeit, nicht detailreiche Quellenwiedergabe. Verbindliche Regeln in 00_MASTER_PROMPT.md und 01_ENTLASSBRIEFE/HAUPTPROMPT.md; Prüfregeln in 05_QUALITAETSKONTROLLE.md.
