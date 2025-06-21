# Inventator
Zusammenfassung: Was ist "Smart Inventar Organizer Pro" ( Inventator)?

Smart Inventar Organizer Pro ist eine hochentwickelte, browserbasierte Anwendung zur Verwaltung von Haushaltsinventar. Sie geht weit über einfache Listen hinaus und bietet eine Fülle von Funktionen, die sie zu einem leistungsstarken Organisationswerkzeug machen. Die App ist als "Single-Page-Application" konzipiert, die vollständig auf dem Gerät des Nutzers (im Browser) läuft und ihre Daten lokal speichert. Dies gewährleistet maximale Privatsphäre.

Die Kernphilosophie der App ist eine hierarchische Organisation, die der realen Welt nachempfunden ist:
Raum → Möbelstück → Behälter (Kiste, Schublade) → Gegenstand

Zu den herausragenden Merkmalen gehören eine fortschrittliche Sprachsteuerung, ein visueller Grundriss-Editor, detaillierte Gegenstands-Eigenschaften mit Foto-Upload und eine lokale Netzwerk-Synchronisation zwischen Geräten.
Hauptnavigation und Benutzeroberfläche (UI)

Die App verfügt über eine klare, moderne und responsive Benutzeroberfläche, die sich an verschiedene Bildschirmgrößen anpasst (Mobile-First-Design).

    Theme-Umschalter (🌓): Ein Knopf oben rechts ermöglicht den Wechsel zwischen einem hellen und einem dunklen Design (Light/Dark Mode).

    Dashboard-Statistiken: Oben werden prominent die wichtigsten Kennzahlen angezeigt:

        Gegenstände: Gesamtzahl aller erfassten Items.

        Räume: Gesamtzahl der angelegten Räume.

        Container: Gesamtzahl aller Möbel und Behälter.

    Tab-Navigation: Die Hauptfunktionen sind in sechs übersichtliche Tabs unterteilt:

        🔍 Suche

        📦 Inventar

        ➕ Hinzufügen

        🏠 Grundriss

        🎤 Sprache

        ⚙️ Settings

Detaillierte Beschreibung der Funktionen nach Tabs
1. 🎤 Sprache & 🔍 Suche (Kombinierter Start-Tab)

Dieser Tab ist das Kontrollzentrum für die Interaktion mit dem Inventar.

    Sprachsteuerung:

        Mikrofon-Button: Ein großer, zentraler Knopf startet die aktive Spracherkennung. Der Zustand des Knopfes ändert sich visuell:

            Blau (Standard): Bereit.

            Rot (Pulsierend): Hört aktiv zu (listening).

            Orange: Verarbeitet die Eingabe (processing).

            Grün: Gibt eine Antwort per Sprache aus (speaking).

        Wake Word ("Hey Organizer"): Wenn in den Einstellungen aktiviert, lauscht die App kontinuierlich auf das Aktivierungswort "Hey Organizer". Sagt man dies, wird die aktive Zuhörfunktion automatisch gestartet, ohne dass ein Knopf gedrückt werden muss.

        Intelligente Befehlsverarbeitung: Die App kann natürliche Sprache verstehen, um Gegenstände zu finden (z.B. "Wo ist mein Hammer?") oder nach Eigenschaften zu filtern (z.B. "Zeige mir alles, was fast leer ist").

        Sprachausgabe (Text-to-Speech): Suchergebnisse und Statusmeldungen werden nicht nur angezeigt, sondern auch per Computerstimme vorgelesen.

        Mikrofon-Auswahl: Nutzer mit mehreren Mikrofonen können ihr bevorzugtes Eingabegerät auswählen, um die Erkennungsqualität zu optimieren.

    Erweiterte Suche:

        Text-Suchfeld: Ein einfaches Feld, um nach Name, ID oder Eigenschaften eines Gegenstands zu suchen.

        Kategorie-Filter: Es werden automatisch Knöpfe für alle im Inventar verwendeten Kategorien generiert, um die Anzeige mit einem Klick zu filtern.

        Schnellfilter: Vordefinierte Filter für häufige Abfragen:

            🔴 Fast leer: Filtert Gegenstände mit einem "Füllstand" unter 20%.

            🟢 Voll: Filtert Gegenstände mit einem "Füllstand" über 80%.

            ⚠️ Schlecht: Filtert Gegenstände mit einem "Zustand" unter 30%.

            🔋 Schwach: Filtert Gegenstände mit einer "Batterie" unter 25%.

        Filter löschen: Ein Knopf, um alle aktiven Filter zurückzusetzen und das gesamte Inventar wieder anzuzeigen.

2. ➕ Hinzufügen (Neuen Gegenstand erfassen)

Dieser Bereich dient der detaillierten Erfassung neuer Gegenstände.

    Foto-Upload: Man kann ein Foto des Gegenstands hochladen. Es wird eine Vorschau angezeigt. Das Foto wird direkt in den lokalen Daten gespeichert.

    Hierarchische Eingabe:

        Gegenstand (Pflichtfeld): Name des Items (z.B. "Akkuschrauber").

        Raum (Pflichtfeld): Der Raum, in dem sich das Item befindet (z.B. "Werkstatt").

        Möbel (optional): Ein Möbelstück im Raum (z.B. "Werkbank").

        Container (optional): Ein Behälter im Möbelstück (z.B. "Obere Schublade").

    Kategorie-Auswahl (🏷️): Eine visuelle Auswahl an vordefinierten Kategorien (z.B. 📱 Elektronik, 🔧 Werkzeug, 🎣 Angeln). Diese sind in den Einstellungen anpassbar.

    Eigenschaften (📊): Eine der Kernfunktionen. Man kann jedem Gegenstand numerische Eigenschaften (0-100) zuweisen, die über Schieberegler eingestellt werden.

        Standard-Eigenschaften: "Füllstand", "Zustand", "Batterie", etc.

        Benutzerdefinierte Eigenschaften: Über einen Knopf (➕ Eigene Eigenschaft hinzufügen) können dynamisch neue Eigenschaften für alle zukünftigen Items hinzugefügt werden (z.B. "Verschleiß", "Wichtigkeit").

    Aktionen:

        Hinzufügen: Speichert den Gegenstand mit all seinen Details im Inventar.

        Leeren: Setzt das gesamte Formular zurück.

3. 📦 Inventar (Die hierarchische Übersicht)

Hier wird das gesamte Inventar in einer Baumstruktur visualisiert.

    Strukturierte Ansicht: Die Ansicht folgt der Hierarchie: Raum > Möbel > Container > Gegenstand.

    Auf-/Zuklappen: Jeder Knoten (z.B. ein Raum) kann einzeln aufgeklappt werden, um seinen Inhalt zu sehen. Ein Button (Alle öffnen/schließen) erlaubt das globale Umschalten.

    Detaillierte Item-Anzeige: Jeder Gegenstand wird mit folgenden Informationen angezeigt:

        Vorschaubild: Wenn ein Foto hinzugefügt wurde.

        Name: Der Name des Gegenstands.

        ID (optional): Eine einzigartige, automatisch generierte ID (z.B. ITM-1001), die in den Einstellungen ein- und ausgeblendet werden kann.

        Kategorie-Badge: Ein farbiges Label, das die zugewiesene Kategorie anzeigt.

        Eigenschaften-Anzeige: Die zugewiesenen Eigenschaften werden mit farbigen Fortschrittsbalken und Prozentwerten dargestellt. Die Farbe des Balkens signalisiert den Zustand (z.B. Rot für niedrig, Grün für hoch).

    Item-Detail-Ansicht: Ein Klick auf einen Gegenstand öffnet ein Modal (Pop-up-Fenster) mit einer Großansicht des Fotos und allen Details. In diesem Fenster können die Eigenschaften des Gegenstands nachträglich bearbeitet werden.

    Daten-Export: Ein Knopf, um das gesamte Inventar als JSON-Datei zu exportieren (Backup).

4. 🏠 Grundriss (Visueller Editor)

Eine einzigartige Funktion zur visuellen Planung und Verortung von Gegenständen.

    Canvas-Editor: Eine leere Zeichenfläche, auf der man den Grundriss eines Raumes skizzieren kann.

    Raum-Auswahl: Man wählt aus, welchen Raum man bearbeiten möchte. Der gezeichnete Grundriss wird für diesen Raum gespeichert.

    Werkzeuge:

        ✏️ Zeichnen: Ermöglicht das freihändige Zeichnen von Wänden und Möbeln.

        📦 Gegenstand: Ermöglicht das Platzieren von "Pins" auf der Karte. Man wird nach dem Namen des Gegenstands gefragt, der an dieser Stelle platziert werden soll.

        🗑️ Löschen: Leert die gesamte Zeichenfläche für den ausgewählten Raum.

    Speicherung: Die Zeichnung wird als Bild gespeichert und ist an den jeweiligen Raum gebunden. Beim nächsten Aufruf des Raumes wird der Grundriss wieder geladen.

5. ⚙️ Settings (Einstellungen)

Dieser Tab ermöglicht eine weitreichende Konfiguration der App.

    Audio-Einstellungen:

        Kontinuierliches Zuhören: Aktiviert/deaktiviert die Wake-Word-Funktion.

        Sprechgeschwindigkeit/Lautstärke: Regler zur Anpassung der Sprachausgabe.

    Netzwerk-Synchronisation:

        Funktionsweise: Nutzt eine browser-interne Technologie (BroadcastChannel), um Daten im lokalen Netzwerk zwischen Geräten auszutauschen (z.B. zwischen einem Laptop und einem Handy im selben WLAN). Es findet keine Synchronisation über das Internet oder eine Cloud statt.

        Server starten: Ein Gerät agiert als "Server", um für andere sichtbar zu sein.

        Geräte suchen: Ein Gerät kann das lokale Netzwerk nach anderen Geräten mit aktiver App durchsuchen.

        Datenübertragung: Wenn eine Verbindung hergestellt wird, können die Inventardaten von einem Gerät auf das andere übertragen werden (nach Bestätigung durch den Nutzer), um beide auf dem gleichen Stand zu halten.

    Eigenschaften verwalten:

        Kategorien bearbeiten: Ein Textfeld, in dem die Liste der verfügbaren Kategorien angepasst werden kann (eine pro Zeile).

        Eigenschaften bearbeiten: Ein Textfeld zur Anpassung der Standard-Schieberegler für Gegenstände.

    App-Einstellungen:

        IDs anzeigen: Schaltet die Anzeige der einzigartigen IDs im Inventar ein/aus.

        Auto-Save/Auto-Export: Konfiguriert, ob die App automatisch speichert und beim Schließen eine Backup-Datei anlegt.

        Sprache: Auswahl der Sprache für die Spracherkennung und -ausgabe.

        Alle Daten löschen: Ein gefährlicher Knopf, der nach Bestätigung das gesamte Inventar und alle Einstellungen unwiderruflich löscht.

Zusätzliche Technische Details und Funktionen

    Lokale Speicherung: Alle Daten (Inventar, Einstellungen, Grundrisse) werden im localStorage des Browsers gespeichert. Das bedeutet, die Daten verlassen das Gerät nicht, es sei denn, man nutzt die Sync- oder Export-Funktion.

    ID-System: Jeder Raum, jedes Möbelstück, jeder Behälter und jeder Gegenstand erhält eine einzigartige, fortlaufende ID. Dies hilft, die Daten intern konsistent zu halten.

    Benachrichtigungssystem: Wichtige Aktionen (z.B. "Gegenstand gespeichert", "Fehler") werden durch kurz eingeblendete Benachrichtigungen am oberen Bildschirmrand signalisiert.

    JSON Import/Export: Die App bietet die Möglichkeit, das gesamte Inventar als .json-Datei zu sichern und eine solche Datei wieder zu importieren. Dies ist ideal für Backups oder den Umzug auf einen neuen Computer.

    Barrierefreiheit: Der Code enthält Vorkehrungen für prefers-reduced-motion, um Animationen für Nutzer zu deaktivieren, die dies wünschen.
