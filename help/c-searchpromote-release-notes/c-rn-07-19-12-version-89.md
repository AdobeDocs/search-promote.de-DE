---
description: 'null '
seo-description: 'null '
seo-title: Search&amp;Promote 8.9 Versionshinweise (19.07.2012)
solution: Target
title: Search&amp;Promote 8.9 Versionshinweise (19.07.2012)
topic: Release Notes,Site search and merchandising
uuid: 3853c75d-19ed-4e36-9e81-dcbffe5f5b0c
translation-type: tm+mt
source-git-commit: ef818327e1cdaad79ac47575a8dfba1de3dc5c2e

---


# Search&amp;Promote 8.9 Release Notes (07/19/2012){#search-promote-release-notes}

**Neue Funktionen**

* Verbesserungen der Metadatenverwaltung - Dynamische Metadatendefinition von Kunden-Feeds

   Erstellen eines Schemas zur dynamischen Neukonfiguration Ihres Search&amp;Promote-Kontos basierend auf kundenseitigen Metadaten-Definitionen.
* Indizierung von Leistungsverbesserungen - Index Loader

   Index Loader ist eine neue Methode zum direkten Importieren von XML-Inhalten in einen Search&amp;Promote-Index. Hierbei handelt es sich um eine Teilfunktion der Index Connector-Funktion, mit der ein schnelles Importieren unserer Standard-XML-Feed-Dateien möglich ist.

**Korrekturen und Erweiterungen**

* Zusätzlicher Support zur Änderung der Sortierungsoption nach einer Geschäftsregel.
* In the Help system `<search-description>` tag shows the body instead when the meta tag for the description has empty content.
* Erweiterte Möglichkeit zur Nachverfolgung entsprechender Tabellentreffer für Ergebnisse, die anhand von ergebnisbasierten Aktionen hinzugefügt wurden.
* Zusätzlicher Support für die Übermittlung von Abfrageparametern per POST
* Beim Kriechen kann ein finaler mirror_account-Vorgang in manchen Fällen übersprungen werden.
* Adobe Analytics-URLs enthalten keine CGI-Argumente und den Search&amp;Promote-Code, mit dem Adobe Analytics-Nachschlagevorgänge durchführt, um CGI-Argumente ähnlich aus URL-Schlüsseln zu entfernen.
* Umformulierungsregeln sind kurzzeitig von der Benutzeroberfläche verschwunden, nachdem diese live gesetzt wurden.
* Search&amp;Promote-Konten mit &quot;Meinten Sie&quot;-Einstellungen, die für Vorschläge aufgrund niedriger Ergebnisse festgelegt wurden, haben möglicherweise zeitweilige Ergebnisse.
* Die Ausgabe des Rewrite rule-Tests enthielt keine Zeilenumbrüche.
* Die Seiten URL-Regeln durchsuchen und URL-Regeln für Crawl-Liste speichern haben auf die falsche Verlaufsseite verwiesen.
* Beim Anklicken von Bearbeiten auf einigen Bannern wurde nicht die Seite Bearbeiten angezeigt.
* Eine erneute Rangzuordnung des Aktualisierungscodes war in machen Fällen außerordentlich langsam.
* Ein Facettenelement konnte nicht entfernt oder geschoben werden, wenn in dem Facettennamen Groß-/Kleinschreibung verwendet wurde.
