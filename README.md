Sternzeichen
Dieses Repo dient zur Sammlung unserer Dateien für das Projekt Sternzeichen


--- Folgen Sie diesen Schritten, um die Sternzeichen-Bestimmungsanwendung zu verwenden und Ihre eigenen personalisierten Bilder mit Ihrem Namen, Geburtsdatum und Sternzeichen zu erstellen. ---

*** Sternzeichen Bestimmung GUI - Gebrauchsanweisung ***

Starten der Anwendung:

Führen Sie den Code aus, indem Sie ihn in Visual Code öffnen und ausführen. Die GUI-Anwendung wird gestartet.

Eingabe von Benutzerinformationen:

Geben Sie Ihren Namen in das Textfeld "Name" ein.
Geben Sie Ihr Geburtsdatum mit den Dropdown-Menüs für Tag, Monat und Jahr ein.
Auswahl eines Bildes:

Klicken Sie auf die Schaltfläche "Bild auswählen", um ein Bild von Ihrem Computer auszuwählen.
Wählen Sie das gewünschte Bild aus dem Dateiauswahldialog aus und bestätigen Sie die Auswahl.
Anzeige der Ergebnisse:

Nachdem Sie Ihren Namen, Ihr Geburtsdatum und ein Bild ausgewählt haben, klicken Sie auf die Schaltfläche "Ergebnisse anzeigen".
Das Programm berechnet Ihr Sternzeichen basierend auf dem eingegebenen Geburtsdatum und kombiniert es mit dem ausgewählten Bild.

Speichern des kombinierten Bildes:
Klicken Sie auf "Speichern", um das Bild unter einem von Ihnen gewählten Dateinamen und Speicherort zu speichern.
Wählen Sie das gewünschte Dateiformat aus (Standardmäßig PNG).

Es wird das kombinierte Bild angezeigt, das Ihr Bild mit Ihrem Namen, Ihrem Geburtsdatum und Ihrem Sternzeichen überlagert.

Beenden der Anwendung:

Schließen Sie das GUI-Fenster, um die Anwendung zu beenden.




Funktion get_zodiac_sign(day, month)
Diese Funktion berechnet das Sternzeichen basierend auf dem Geburtsdatum.

Monatsnamen-Wörterbuch
Das Wörterbuch month_names ordnet jedem Monat seine deutsche Bezeichnung zu.

Sternzeichen-Berechnung
Je nach Kombination von Tag und Monat wird das passende Sternzeichen zurückgegeben.

Ungültiges Datum
Falls ein ungültiges Datum eingegeben wird, wird eine Fehlermeldung ausgegeben und None zurückgegeben.

Bildauswahl-Funktion select_image()
Diese Funktion öffnet einen Dateiauswahldialog, um ein Bild zu laden und anzuzeigen.

Funktion zum Anpassen und Zuschneiden von Bildern resize_and_crop_to_800x800(image_array)
Diese Funktion passt die Größe eines Bildes an und schneidet es auf 800x800 Pixel zu.

Hauptfunktion zum Anzeigen der Ergebnisse show_results()
Diese Funktion sammelt die Eingabedaten, verarbeitet das Bild, berechnet das Sternzeichen und sendet eine E-Mail.

GUI-Setup
Die GUI wird mit tkinter erstellt, um die Benutzereingaben zu sammeln und die Ergebnisse anzuzeigen.

