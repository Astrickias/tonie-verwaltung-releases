# 🎧 Tonie Verwaltung

**Eine private Android-App, mit der unsere Familie ihre Tonie-Sammlung verwaltet.**
Hier liegen nur die fertigen Installationsdateien (APK) und die automatischen Updates.

> ⚠️ **Privates Hobbyprojekt – kein offizielles Produkt.**
> Diese App ist nicht von der tonies GmbH und hat mit ihr nichts zu tun. Bitte lies den
> [Hinweis & Haftungsausschluss](#%EF%B8%8F-hinweis--haftungsausschluss) unten, bevor du sie installierst.

---

## ✨ Was die App kann

**Sammlung**
- Alle Tonies auf einen Blick – mit Status (im Regal, beim Kind, verschwunden, Wunschliste), Kategorie, Serie, Laufzeit, Alter, Aufbewahrungsort, Kaufpreis und eigenem Foto
- **Katalog mit rund 700 deutschen Tonie-Figuren** – suchen, antippen, fertig
- **Eigene Namen:** Ihr nennt einen Tonie „Anna“? Kein Problem – die App merkt sich trotzdem, welcher echte Tonie das ist
- **Serien-Fortschritt:** Welche Folgen einer Serie fehlen noch?
- Suche, Filter, Statistiken und eine Übersicht als Startseite

**Erkennen & Einkaufen**
- 📷 **Tonie scannen:** Figur fotografieren – die App erkennt sie und zeigt, ob ihr sie schon habt
- ⚡ **Flohmarkt Blitz-Check:** Am Stand kurz fotografieren oder ein paar Buchstaben tippen – riesengroß steht da, ob ihr zuschlagen solltet
- 💙 **Wunschliste teilen:** Ein Link für Oma, Opa & Co. – wer etwas schenkt, reserviert es, damit nichts doppelt kommt

**Familie**
- 👨‍👩‍👧 **Familien-Sync:** Mehrere Handys teilen sich dieselbe Sammlung (per Familien-Code)
- Optional: **Kinder & Ausleihe** – wer hat welchen Tonie gerade, Lieblings-Tonies, Verlauf und Erinnerungen
- 🎲 **„Was hören wir heute?“** – die App würfelt einen Tonie aus, passend zur gewünschten Länge

**Sonstiges**
- 📱 Läuft auf Handy, **Tablet (z. B. Samsung Galaxy Tab), Samsung DeX und Googlebook** – inkl. Rechtsklick-Menü und Tastenkürzel (ab Version 1.0)
- Dunkler Modus, kurze Einführung beim ersten Start, Schnellzugriffe vom App-Symbol
- Backup & Wiederherstellen, Export als Tabelle (Excel / Google Sheets)
- **Automatische Updates** direkt in der App
- Expertenmodus: Tonies per NFC ans Handy halten

## 📥 Installation

1. Unter **[Releases](../../releases/latest)** die neueste Datei `tonie-verwaltung-vX.Y.Z.apk` herunterladen
   (die Datei `katalog.json` ist kein App-Update, sondern nur der Tonie-Katalog).
2. Die APK öffnen. Android fragt einmalig, ob der Browser bzw. Dateimanager Apps installieren darf → erlauben.
3. Fertig. Neue Versionen meldet die App von selbst und installiert sie auf Wunsch.

Voraussetzung: Android 7.0 oder neuer. Die App ist nicht im Google Play Store.

## 🔒 Datenschutz in Kürze

- Eure Sammlung liegt **auf eurem Gerät**. Nur wenn ihr den Familien-Sync oder das Teilen der Wunschliste
  einschaltet, wird sie in einer Google-Firebase-Datenbank gespeichert, damit eure anderen Geräte sie sehen.
- Beim **Tonie-Scan** wird nur das (verkleinerte) Foto zur Erkennung an Google (Gemini) geschickt – nichts aus eurer Sammlung.
- Keine Werbung, kein Tracking, keine Analyse-Tools.
- In der App sind keine fremden persönlichen Daten enthalten – jeder startet mit einem leeren Haushalt.

---

## ⚖️ Hinweis & Haftungsausschluss

- **Rein privates, nicht-kommerzielles Projekt.** Die App wurde für den Eigengebrauch in unserer Familie
  entwickelt und ist hier nur öffentlich, damit die Updates funktionieren. Es gibt **keinen Support**, keine
  Garantie auf Weiterentwicklung und keinen Anspruch auf Fehlerbehebung.
- **Benutzung auf eigene Gefahr.** Die App wird so bereitgestellt, wie sie ist – ohne jede Gewährleistung.
  Für Schäden, Datenverlust, Fehlfunktionen oder sonstige Folgen der Installation oder Nutzung wird – soweit
  gesetzlich zulässig – **keine Haftung** übernommen. Macht regelmäßig ein Backup (in der App unter „Export & Backup“).
- **Keine Verbindung zu tonies.** Diese App steht in **keiner Verbindung zur tonies GmbH** und wird von ihr weder
  unterstützt noch geprüft oder empfohlen. Sie greift weder auf die Toniebox noch auf die Tonie-Cloud oder ein
  Tonie-Konto zu und verändert keine Figuren.
- **Marken.** „Tonies“, „Toniebox“, „Tonie“ und die zugehörigen Figuren, Namen und Logos sind Marken bzw. Eigentum
  der tonies GmbH bzw. der jeweiligen Rechteinhaber. Sie werden hier nur verwendet, um zu beschreiben, wofür die
  App gedacht ist.
- **Katalogdaten und Bilder** stammen aus der frei verfügbaren Community-Datenbank
  [tonies-json](https://github.com/toniebox-reverse-engineering/tonies-json) (TeddyCloud-Projekt). Für ihre
  Richtigkeit und Vollständigkeit gibt es keine Gewähr; Produktbilder gehören ihren jeweiligen Rechteinhabern.
- **Die Bilderkennung** (Google Gemini) kann sich irren. Bitte vor dem Kauf auf dem Flohmarkt lieber noch einmal
  selbst hinschauen.
- Die Nutzung der eingebundenen Google-Dienste (Firebase, Gemini) unterliegt den Bedingungen von Google.

Bei Rechte-Fragen oder Problemen bitte ein [Issue](../../issues) eröffnen – wir kümmern uns dann darum.
