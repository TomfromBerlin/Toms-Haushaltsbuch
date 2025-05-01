# Toms Haushaltsbuch

# 📊 Haushaltsbuch für LibreOffice Calc

Ein vollständiges Haushaltsbuch für Privathaushalte – ohne Makros, ohne komplizierte Technik, aber mit jeder Menge Features. Entwickelt, um den Überblick über Einnahmen, Ausgaben und Ersparnisse zu behalten – und das ganze Jahr im Blick zu haben.
---
## Inhaltsverzeichnis

- [Zielgruppe](#zielgruppe)
- [Funktionen und Features](#funktionen-und-features)
- [Struktur](#struktur)
- [Hinweise zur Benutzung](#hinweise-zur-benutzung)
- [Screenshots](#screenshots)
- [Bekannte Stolperfallen](#bekannte-stolperfallen)
- [Anpassung & Erweiterung](#anpassung--erweiterung)
- [Lizenz](#lizenz)

---

## 🧑‍💻 Zielgruppe

Dieses Tool richtet sich an:
- Privatpersonen & Haushalte mit **bis zu 80 Transaktionen pro Monat**
- Leute, die **keine Lust auf Apps oder Cloud-Lösungen** haben (Deine Daten gehören nur Dir, auch Deine Einkaufsliste)
- Menschen mit grundlegenden Kenntnissen in Tabellenkalkulation
- Alle, die ihre **Finanzen einfach, visuell und nachvollziehbar** verwalten wollen

---

## ✨ Funktionen und Features

✅ 12 Monatsblätter mit farblicher Markierung von Einnahmen und Ausgaben  
✅ Übersicht (`Summary`) mit automatischer Kategorisierung und Trenddarstellung  
✅ Dynamische Diagramme im Sheet `Diagramme`  
✅ Zusätzliche Berechnungen wie Stundenlohn, Einzelpreis oder Ersparnis in %  
✅ Extra-Sheet für Prozentrechnung (Rabatt-Erkennung)  
✅ Eingabeschutz für Formeln (kein Passwort nötig)  
✅ Smiley-Stimmungsbarometer zur finanziellen Lage (Jahresüberblick)  
✅ Funktioniert vollständig **offline** in LibreOffice Calc  
✅ **Keine Makros**, keine Cloud, keine Drittanbieter-Dienste

---

## 📂 Struktur

- **Einstellungen:** Jahreszahl, Startwerte, Feiertage, Wochenstunden
- **Monate:** `Januar`, `Februar`, ..., `Dezember` – für die Transaktionen
- **Summary:** Jahresüberblick inkl. Diagrammen & Kategorientracking
- **Diagramme:** Visualisierung des Verlaufs von Einnahmen, Ausgaben etc.
- **Prozent:** Tool zur Rabatt-Berechnung

---

## 📌 Hinweise zur Benutzung

- **Formeln nicht überschreiben!** Geschützte Zellen zeigen das durch einen Zellschutz an. Der Schutz kann entfernt werden, ist aber nicht passwortgesichert.
- Kategorien werden über die Spalte `Verwendungszweck` erkannt. Beispiel: Ein Eintrag wie `Gehalt März` zählt zur Kategorie `Gehalt`, wenn diese im Sheet `Summary` festgelegt ist.
- Das aktuelle Datum wird in zukünftigen Monaten bis zum Monatsende automatisch angezeigt, danach bleibt es stehen.
- Für korrekte Anzeige der Smileys brauchst du die Schriftart [`DroidSansMono Nerd Font`](https://www.nerdfonts.com/font-downloads).

---

## 🖼️ Screenshots

| Monatsblatt | Einstellungen | Summary | Diagramme |
|-------------|---------------|---------|-----------|
| ![Monat(Teil 1)](screenshots/monat_a.png) ![Monat(Teil 2)](screenshots/monat_b.png) | ![Einstellungen](screenshots/einstellungen.png) | ![Summary](screenshots/summary.png) | ![Diagramme](screenshots/diagramme.png) |

---

## ⚠️ Bekannte Stolperfallen

| Problem | Erklärung |
|-----------|-----------|
| Kategorien werden nicht erkannt | Stichwort fehlt im Verwendungszweck oder die Schreibweise ist nicht identisch. |
| Smileys sind kryptisch | Nerd Font fehlt. [`DroidSansMono Nerd Font`](https://www.nerdfonts.com/font-downloads) |
| Zellen „meckern“ oder sehen komisch aus | Wurden versehentlich Formeln geändert oder gelöscht? Manche Formeln sind als Matrix-Formeln markiert. Ohne Markierung funktionieren diese Formeln nicht und geben eine Fehlermeldung aus. |
| Neue Monate hinzufügen? | Nicht nötig – alles ist bereits für das ganze Jahr vorbereitet. |
| Zu wenige Zeilen im Monat? | Zeilen können hinzugefügt werden, aber die Formeln müssen ergänzt werden. |
| Die Sheets sind vor Veränderung geschützt? | Die Sheets sind zum Schutz der Formeln geschützt, der Schutz kann jedoch leicht aufgehoben werden. Das Passwort ist leer. |

---

## 🛠️ Anpassung & Erweiterung

Wer mehr Transaktionen oder Spezialfunktionen braucht, sollte sich ein wenig mit LibreOffice Calc auskennen – z. B. Zellbezüge, Zellschutz und bedingte Formatierung. Dann können in dem gewünschten Monat neue Zeilen hinzugefügt werden. Dabei ist zu beachten, dass die Formeln in der ganzen Zeile entsprechend ergänzt werden müssen. Wie gesagt: Grundkenntnisse in LibreCalc sind in dem Fall äußerst hilfreich.

---

## 📜 Lizenz

*Namensnennung - Keine kommerzielle Nutzung - Weitergabe unter gleichen Bedingungen (by-nc-sa)*
[https://creativecommons.org/licenses/by-nc-sa/3.0/de/deed.de](https://creativecommons.org/licenses/by-nc-sa/3.0/de/deed.de)
