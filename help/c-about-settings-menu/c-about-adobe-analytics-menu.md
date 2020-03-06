---
description: Verwenden Sie das Adobe Analytics-Menü, um die Authentifizierung von Adobe Analytics-Metriken einzurichten, Adobe Analytics-Metriken einer Report Suite zu verwalten oder SAINT zu verwenden, um Adobe Analytics-Berichte durch Akzeptanz tabellarischer Daten aus externen Quellen zu verbessern.
seo-description: Verwenden Sie das Adobe Analytics-Menü, um die Authentifizierung von Adobe Analytics-Metriken einzurichten, Adobe Analytics-Metriken einer Report Suite zu verwalten oder SAINT zu verwenden, um Adobe Analytics-Berichte durch Akzeptanz tabellarischer Daten aus externen Quellen zu verbessern.
seo-title: Info zum Menü "Adobe Analytics"
solution: Target
subtopic: Adobe Analytics
title: Info zum Menü "Adobe Analytics"
topic: Settings,Site search and merchandising
uuid: 5536edf1-d3a4-47af-a307-6e46f385f738
translation-type: tm+mt
source-git-commit: f21a3f7fe0aeaab517a5ca36da43594873b3e69a

---


# Info zum Menü &quot;Adobe Analytics&quot;{#about-the-adobe-analytics-menu}

Verwenden Sie das Adobe Analytics-Menü, um die Authentifizierung von Adobe Analytics-Metriken einzurichten, Adobe Analytics-Metriken einer Report Suite zu verwalten oder SAINT zu verwenden, um Adobe Analytics-Berichte durch Akzeptanz tabellarischer Daten aus externen Quellen zu verbessern.

## Adobe Analytics-Metriken-Authentifizierung einrichten {#task_8AA93F6273B747F9B4DE9E8DFBCBDC42}

Um Adobe Analytics-Metriken in Ihre Site-Rangfolge für Suche/Merchandising einzubinden, müssen Sie zunächst eine Adobe Analytics Web Services-Anmeldung abrufen. Nachdem Sie die Anmeldeinformationen abgerufen haben, können Sie damit die Adobe Analytics-Authentifizierung bei der Site-Suche/beim Merchandising einrichten.

**So richten Sie die Adobe Analytics-Metriken-Authentifizierung ein**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Authentication]**.
1. Geben Sie auf der [!DNL Setup Adobe Analytics Metrics Authentication] Seite die in den einzelnen Feldern angeforderten Informationen an.

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>Textfeld </p> </th> 
      <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>Adobe Analytics-Firmenname </p> </td> 
      <td colname="col2"> <p>Die gleiche Einstellung für den Unternehmensnamen, mit der Sie sich bei Ihrem Adobe Analytics-Konto anmelden. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Web-Services-Benutzername </p> </td> 
      <td colname="col2"> <p>Der Webdienst-Benutzername, der mit Ihrem Adobe Analytics-Konto verknüpft ist. </p> <p>Sie können diese Informationen in Adobe Analytics abrufen. Klicken Sie in der Menüleiste von Adobe Analytics auf <span class="uicontrol"> Admin <b>&gt;</b> Admin-Konsole </span> <span class="uicontrol"> &gt; <b>Unternehmen&gt;Web-Services</b> </span> <span class="uicontrol"> <b></b> </span> <span class="uicontrol"> <b></b> </span>. Die Informationen finden Sie in der Tabelle "API-Zugriffsinformationen". </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Web-Services - Shared-Secret </p> </td> 
      <td colname="col2"> <p>Der Web-Services-Shared-Secret, der mit Ihrem Adobe Analytics-Konto verknüpft ist. </p> <p>Sie können diese Informationen in Adobe Analytics abrufen. Klicken Sie in der Menüleiste von Adobe Analytics auf <span class="uicontrol"> Admin <b>&gt;</b> Admin-Konsole </span> <span class="uicontrol"> &gt; <b>Unternehmen&gt;Web-Services</b> </span> <span class="uicontrol"> <b></b> </span> <span class="uicontrol"> <b></b> </span>. Die Informationen finden Sie in der Tabelle "API-Zugriffsinformationen". </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. Klicken **[!UICONTROL Save Changes]**.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL History]** , um alle vorgenommenen Änderungen wiederherzustellen.

      Siehe [Verwenden der Option](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)Verlauf.

   * Klicken **[!UICONTROL Live]**.

      Siehe [Live-Einstellungen](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)anzeigen.

   * Klicken **[!UICONTROL Push Live]**.

      Siehe [Pushing-Einstellungen](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4).

## Info zu Adobe Analytics Report Suites {#concept_1A51AEC5D40E459B813E7891D64B1BAE}

Um Adobe Analytics Report Suite-Daten bei der Site-Suche/beim Merchandising zu verwenden, müssen Sie zunächst Kopien der Adobe Analytics-Daten in Ihrem Site-Konto für Suche/Merchandising erstellen.

Sie können neue Adobe Analytics Report Suite-Definitionen erstellen oder Ihre vorhandenen Adobe Analytics Report Suites und zugehörigen Metriken anzeigen oder ändern.

Wenn Sie zum ersten Mal über die Site-Suche/Merchandising auf Adobe Analytics zugreifen, wird eine Liste der verfügbaren Report Suites Ihres Unternehmens heruntergeladen und zwischengespeichert. Wenn kürzlich neue Report Suites hinzugefügt oder vorhandene entfernt wurden, können Sie die Report Suite-Liste aktualisieren, um die Liste der Report Suites erneut herunterzuladen.

## Hinzufügen einer Adobe Analytics Report Suite {#task_6DE17305EA7146DA8C30FF8FDF68A3C0}

Sie können eine Adobe Analytics-Report Suite auswählen, auf der Ihre Site-Suchregel-/Merchandising-Ranking-Regeln basieren sollen.

Die Liste, aus der Sie auswählen können, sollte den Report Suites entsprechen, die in Ihrem Adobe Analytics-Konto verfügbar sind. Die von Ihnen ausgewählte Report Suite bestimmt die Metriken, die in Ihren Site-Such-/Merchandising-Rangregeln zur Verfügung stehen.

Siehe [Info zu Ranking Rules](../c-about-rules-menu/c-about-ranking-rules.md#concept_F555C076759B4E81B925441CFE707397).

Nachdem Sie eine Adobe Analytics Report Suite hinzugefügt haben, können Sie die zugehörigen Metriken bearbeiten.

Siehe [Bearbeiten der Adobe Analytics-Metriken einer Report Suite](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_360904CCBBB140238ADA036C3CC07664).

**So fügen Sie eine Adobe Analytics Report Suite hinzu**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**.
1. Klicken Sie auf der Seite &quot;Adobe Analytics Report Suites&quot;auf **[!UICONTROL Add Report Suite]**.
1. Wählen Sie in der Dropdownliste der neu hinzugefügten Tabellenzeile die gewünschte Report Suite aus.
1. Bearbeiten Sie die Adobe Analytics-Metriken einer Report Suite.

## Bearbeiten der Adobe Analytics-Metriken einer Report Suite {#task_360904CCBBB140238ADA036C3CC07664}

Um Adobe Analytics-Metriken in Ihre Ranking Rules in Site-Suche/Merchandising einzubinden, wählen Sie eine oder mehrere Metriken aus, die mit der gewählten Report Suite verknüpft sind. Anschließend konfigurieren Sie die Optionen, mit denen Metrikdaten über den Adobe Analytics-Webdienst abgerufen werden.

Siehe [Hinzufügen einer Adobe Analytics Report Suite](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_6DE17305EA7146DA8C30FF8FDF68A3C0).

Siehe [Konfigurieren erweiterter Adobe Analytics-Optionen](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_C0FF2D69F59D44D8943A7831ED7FEC19).

**So bearbeiten Sie die Adobe Analytics-Metriken einer Report Suite**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**.
1. Klicken Sie auf der [!DNL Adobe Analytics Report Suites] Seite unter der **[!UICONTROL Actions]** Spalte auf **[!UICONTROL Edit]** die Report Suite, deren Metriken Sie konfigurieren möchten.
1. Stellen Sie auf der [!DNL Edit Adobe Analytics Metrics] Seite die erforderlichen Metriken ein. Metriken ohne Sternchen (*) neben dem Metriknamen sind optional.

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>Option </p> </th> 
      <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>Report Suite </p> </td> 
      <td colname="col2"> <p>Zeigt den Namen der aktuellen Report Suite an, die Sie hinzugefügt haben. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Name der Report Suite-Ansicht </p> </td> 
      <td colname="col2"> <p>Gibt einen Aliasnamen für den Namen der Adobe Analytics Report Suite an. Dieser alternative Name ist nützlich, wenn dieselbe Report Suite in mehr als einer Definition verwendet wird. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Berichttyp auswählen </p> </td> 
      <td colname="col2"> <p>Gibt den Wert für den Berichtstyp an, der mit der ausgewählten Report Suite verwendet werden soll. Der Wert gibt den Schlüssel für jede zurückgegebene Ergebniszeile an. </p> <p>Der Berichtstyp wird auch als Adobe Analytics-Element bezeichnet. </p> <p>Diese Metrik ist erforderlich. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Referenzfeldname </p> </td> 
      <td colname="col2"> <p>Gibt ein Metadatenfeld an, dessen Werte als Nachschlagschlüssel in die Daten der Report Suite verwendet werden. </p> <p>Wenn kein Wert ausgewählt ist ("— Keine —"), stehen die Daten dieser Report Suite nicht zur Verwendung bei Rangberechnungen zur Verfügung ( <span class="uicontrol"> Regeln <b></b> &gt; </span> Rangregeln <span class="uicontrol"><b>&gt; Regeln</b> bearbeiten). </span> <span class="uicontrol"> <b></b> </span> </p> <p>Wenn Sie einen Wert auswählen, werden die Werte dieses Felds verwendet, um auf Site-Suchen/Merchandising-Dokumente mit den Adobe Analytics-Daten dieser Report Suite zu verweisen. Dabei wird der ausgewählte Berichtstyp-Wert verwendet, den Sie zuvor festgelegt haben. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Suchbegriffbericht </p> </td> 
      <td colname="col2"> <p>Ermöglicht Ihnen den Zugriff auf die Erstellung von Geschäftsregeln und die Simulation von Suchbegriffen auf der Seite <b>Adobe Analytics-Datenvorschau</b> . </p> <p>Siehe <a href="../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_735CDCC1D8174B7B9F5B8E0AFA5F0CA0" type="task" format="dita" scope="local">Anzeigen einer Vorschau von Adobe Analytics-Daten</a>. </p> <p>Auf jeder Zeile mit zwei Optionen wird ein Pulldown-Menü angezeigt: Suchbegriff <b></b> simulieren und neue Geschäftsregel <b>erstellen</b>. </p> <p>Beide Optionen verwenden Daten aus dem Berichtstyp als Suchbegriffe. Daher ist diese Funktion nur sinnvoll, wenn der Berichtstyp Suchbegriffe darstellt. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Metriken </p> </td> 
      <td colname="col2"> <p>Identifiziert die Metrikwerte, die Sie herunterladen und in Ihren Site-Such-/Merchandising-Rangregeln verwenden möchten. </p> <p>Die Metriken, die Sie hier konfigurieren, werden als Auswahlmöglichkeiten auf den Seiten <span class="uicontrol"> Regeln <b>&gt;</b> Rangregeln </span> &gt; Regeln <span class="uicontrol"> <b></b> </span> <span class="uicontrol"> <b></b> </span> <span class="uicontrol"> </span>bearbeiten angezeigtMitgliedercenter, wenn der Datentyp der Regel auf Adobe Analytics-Metrik (Nummer) eingestellt ist. Die Auswahl zeigt eine Kombination aus Report Suite-Namen oder Report Suite-Ansichtsnamen (sofern angegeben) und den einzelnen Metriknamen. </p> <p>Diese Metrik ist erforderlich. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Mindestmetrikwert </p> </td> 
      <td colname="col2"> <p>Ermöglicht die Eingabe eines Werts ungleich null, um einen Mindestwert für die Metrik festzulegen. </p> <p>Wenn leer oder Null, werden alle Werte für die Metrik heruntergeladen. Andernfalls wird der Download für diese Metrik beendet, wenn der Mindestmetrikwert übergeben wird. </p> <p>Adobe Analytics-Metriken werden in absteigender Reihenfolge abgerufen. </p> <p>Klicken Sie auf <span class="uicontrol"> + <b></b> </span> , um weitere Metrikdefinitionen hinzuzufügen. Klicken Sie auf <span class="uicontrol"> - <b></b> </span> , um Metrikdefinitionen zu entfernen, die Sie nicht mehr benötigen oder möchten. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Adobe Analytics-Metrik-Aggregationszeitraum (Tage) </p> </td> 
      <td colname="col2"> <p> Steuert die Anzahl der Adobe Analytics-Metriken im Wert von Tagen, die ab dem Datum des Vorgestern abgerufen werden sollen. Es wird nicht versucht, Daten vom aktuellen Tag abzurufen. </p> <p>Die Standardeinstellung ist „7“. </p> <p>Diese Metrik ist erforderlich. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Adobe Analytics Download Refresh Frequency (Days) </p> </td> 
      <td colname="col2"> <p> Legt das Mindestintervall zwischen Downloads von Adobe Analytics-Daten fest, das bei Rangberechnungen verwendet wird. </p> <p>Durch den Index ausgelöste Downloads, die innerhalb des Intervalls für die Downloadaktualisierung auftreten, werden ignoriert. Bei manuellen Downloads wird dieser Wert jedoch ignoriert. </p> <p>Wenn Sie diesen Wert auf den Standardwert 1 setzen, werden Adobe Analytics-Daten innerhalb von 24 Stunden nur einmal heruntergeladen. Alle Suchindizes, die innerhalb des Intervalls für die Aktualisierung des Downloads auftreten, verwenden den zuletzt heruntergeladenen Datensatz. </p> <p>Diese Metrik ist erforderlich. </p> </td> 
      </tr> 
    </tbody> 
    </table>

   See also [About Ranking Rules](../c-about-rules-menu/c-about-ranking-rules.md#concept_F555C076759B4E81B925441CFE707397).
1. Klicken **[!UICONTROL Save Changes]**.

   Sie werden zur [!DNL Adobe Analytics Report Suites] Seite &quot;Stage&quot;zurückgeleitet.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL History]** , um alle vorgenommenen Änderungen wiederherzustellen.

      Siehe [Verwenden der Option](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)Verlauf.

   * Klicken **[!UICONTROL Live]**.

      Siehe [Live-Einstellungen](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)anzeigen.

   * Klicken **[!UICONTROL Push Live]**.

      Siehe [Pushing-Einstellungen](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4).

## Löschen einer Adobe Analytics Report Suite {#task_0ACA172214D14654ABDB139F417B9F7D}

Mit Löschen können Sie eine Report Suite von der [!DNL Adobe Analytics Report Suites] Seite entfernen. Beim Löschen einer Report Suite werden nur die Daten von den Site-Such-/Merchandising-Servern entfernt. Die Daten werden nicht auf Adobe Analytics-Systeme übertragen.

**So löschen Sie eine Adobe Analytics Report Suite**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**.
1. Klicken Sie auf der [!DNL Adobe Analytics Report Suites] Seite unter der **[!UICONTROL Actions]** Spalte auf **[!UICONTROL Delete]** die Report Suite, die Sie entfernen möchten.
1. Klicken Sie auf der [!DNL Adobe Analytics Delete Report Suite] Seite auf **[!UICONTROL Delete]**.

## Vorschau von Adobe Analytics-Daten {#task_735CDCC1D8174B7B9F5B8E0AFA5F0CA0}

Mit der Vorschau können Sie Ihre zuletzt geladenen Adobe Analytics-Metriken anzeigen.

Die Spalte &quot;Zeile&quot;in der Tabelle zeigt die Anzahl für jede Zeile mit den Metrikdaten an und gibt die ursprüngliche Reihenfolge an, in der die Adobe Analytics-Metriken geladen wurden.

Die Spalte &quot;Produkt&quot;zeigt das Adobe Analytics-Element, das mit jeder Zeile von Metrikdaten verknüpft ist. Die Werte in dieser Spalte werden verwendet, um Ihre Site-Such-/Merchandising-Seiten mit den entsprechenden Metrikwerten zu verbinden, wie in Ihren Rangdefinitionen konfiguriert.

Siehe [Info zu Ranking Rules](../c-about-rules-menu/c-about-ranking-rules.md#concept_F555C076759B4E81B925441CFE707397).

Siehe [Konfigurieren der Rangordnung](../c-about-rules-menu/c-about-ranking-rules.md#task_4CEBC13925B047FC95BDC217B48089C5).

Die übrigen Spalten zeigen die Metrikwerte an, die mit jedem Eintrag verknüpft sind.

Wenn die Tabelle leer ist, bedeutet dies, dass Sie noch keine Adobe Analytics-Daten geladen haben. Sie können die [!DNL Adobe Analytics Data Preview] Seite schließen und dann Adobe Analytics-Daten laden.

Siehe [Laden von Adobe Analytics-Daten](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_2F3C55189B0A4049AB2113F2291CC181).
Wenn die Tabelle als Suchbegriffbericht festgelegt wurde, wird in jeder Zeile ein kleines Dreieck angezeigt. Sie können auf die Dropdownliste klicken und die Option **Suchbegriff** simulieren oder Neue Geschäftsregel **erstellen** auswählen. Die gewählte Aktion wird auf den Suchbegriff der Zeile angewendet, die Daten in der zweiten Spalte

**So zeigen Sie eine Vorschau der Adobe Analytics-Daten an**

1. Führen Sie im Produktmenü einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**. Klicken Sie auf der [!DNL Adobe Analytics Report Suites] Seite unter der [!DNL Actions] Spalte auf **[!UICONTROL Preview]** die Report Suite, deren heruntergeladene Daten Sie anzeigen möchten.

   * Klicken **[!UICONTROL Reports]** > **[!UICONTROL Adobe Analytics Terms Reports]**. Klicken Sie auf der [!DNL Adobe Analytics Terms Report] Seite unter der [!DNL Actions] Spalte auf **[!UICONTROL Preview]** die Report Suite, deren heruntergeladene Daten Sie anzeigen möchten.

1. Verwenden Sie auf der [!DNL Adobe Analytics Data Preview] Seite die Navigations- und Anzeigeoptionen am oberen und unteren Rand der Seite, um die Daten anzuzeigen.

   Klicken Sie auf eine Spaltenüberschrift in der Tabelle, um die Daten in auf- oder absteigender Reihenfolge zu sortieren.
1. Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL Download to Desktop]** , um die Tabelle als `.xlt` Datei herunterzuladen und zu speichern.

   * Schließen Sie die Seite, wenn Sie mit der Vorschau der Adobe Analytics-Daten fertig sind, und kehren Sie zur zuvor angezeigten Seite zurück.

## Anzeigen des Protokolls aus dem neuesten Laden der Adobe Analytics-Daten {#task_9C7D6E34BB6C4A40B7CA3EE36ACB0837}

Sie können &quot;Protokoll anzeigen&quot;verwenden, um die Adobe Analytics-Datenprotokolldatei des letzten Downloadprozesses zu überprüfen. Sie können die Protokollansicht auch verwenden, um einen laufenden Download zu überwachen.

Siehe [Laden von Adobe Analytics-Daten](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_2F3C55189B0A4049AB2113F2291CC181).

**So zeigen Sie das Protokoll aus dem neuesten Laden der Adobe Analytics-Daten an**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**.
1. Klicken Sie auf der [!DNL Adobe Analytics Report Suites] Seite auf **[!UICONTROL View Log]**. Protokollseite,
1. Verwenden Sie auf der [!DNL Adobe Analytics Data Log] Seite die Navigations- und Anzeigeoptionen am oberen und unteren Rand der Seite, um die Protokollinformationen anzuzeigen.
1. Wenn Sie fertig sind, schließen Sie die Seite, um zur [!DNL Adobe Analytics Report Suites] Seite zurückzukehren.

## Laden von Adobe Analytics-Daten {#task_2F3C55189B0A4049AB2113F2291CC181}

Sie können die konfigurierten Adobe Analytics Report Suite-Daten in Site-Suche/Merchandising herunterladen.

Die Seite &quot;Datenladevorgang&quot;zeigt den Status Ihres letzten Adobe Analytics-Datenladevorgangs mit den folgenden Informationen an:

<table> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Statusfeld </p> </th> 
   <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Status </p> </td> 
   <td colname="col2"> <p>Gibt den Erfolg oder Misserfolg des letzten Datenladeversuchs an. Oder es zeigt den Status eines bereits ausgeführten Datenladevorgangs an. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ergebnisse </p> </td> 
   <td colname="col2"> <p>Zeigt die Anzahl der Zeilen mit Metrikdaten an, die während des letzten Datenladevorgangs heruntergeladen wurden. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Startzeit </p> </td> 
   <td colname="col2"> <p>Zeigt das Datum und die Uhrzeit an, zu denen der letzte Datenladevorgang gestartet wurde. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Stoppzeit </p> </td> 
   <td colname="col2"> <p>Zeigt das Abschlussdatum und die Uhrzeit des letzten Datenladevorgangs an. Oder es zeigt an, dass der aktuelle Datenladevorgang noch läuft. </p> </td> 
  </tr> 
 </tbody> 
</table>

**So laden Sie Adobe Analytics-Daten**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**.
1. Klicken Sie auf der [!DNL Stage Adobe Analytics Report Suites] Seite auf **[!UICONTROL Load Adobe Analytics Data]**.
1. Führen Sie auf der **[!UICONTROL Adobe Analytics Data Load]** Seite einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL Start Load]** , um den Ladevorgang zu starten.

      Während eines Datenladevorgangs stellt die Zeile **&quot;Fortschritt** &quot;Informationen zum Fortschritt bereit.

   * Klicken Sie auf **[!UICONTROL Stop Load]** , um den Ladevorgang zu beenden.

1. Klicken Sie auf **[!UICONTROL Close]** , um zur [!DNL Stage Adobe Analytics Reports Suite] Seite zurückzukehren.

## Aktualisieren der Report Suite-Liste {#task_EA6215D438CA4185B106657D9712ED34}

Wenn Sie zum ersten Mal über die Benutzeroberfläche für die Site-Suche/Merchandising auf Adobe Analytics zugreifen, wird eine Liste der verfügbaren Adobe Analytics Report Suites Ihres Unternehmens heruntergeladen und zwischengespeichert. Wenn kürzlich neue Report Suites hinzugefügt oder vorhandene gelöscht wurden, können Sie die aktuell angezeigte Liste in Site-Suche/Merchandising mit der Option Report Suite-Liste aktualisieren aktualisieren aktualisieren.

Siehe [Hinzufügen einer Adobe Analytics Report Suite](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_6DE17305EA7146DA8C30FF8FDF68A3C0).

Siehe [Löschen einer Adobe Analytics Report Suite](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_0ACA172214D14654ABDB139F417B9F7D).

**So aktualisieren Sie die Report Suite-Liste**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Metrics]**.
1. Klicken Sie auf der [!DNL Adobe Analytics Report Suites] Seite auf **[!UICONTROL Refresh Report Suite List]**.

## Konfigurieren erweiterter Adobe Analytics-Optionen {#task_C0FF2D69F59D44D8943A7831ED7FEC19}

Sie können Einstellungen steuern, [!DNL Advanced Adobe Analytics Options] die Ihnen helfen sollen, das Verhalten des Adobe Analytics Report Suite-Downloadprozesses genauer einzustellen.

Siehe [Bearbeiten der Adobe Analytics-Metriken einer Report Suite](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_360904CCBBB140238ADA036C3CC07664).

**So konfigurieren Sie erweiterte Adobe Analytics-Optionen**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL Advanced Options]**.
1. Legen Sie auf der [!DNL Advanced Adobe Analytics Options] Seite die folgenden Optionen fest:

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>Option </p> </th> 
      <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>Maximale Zeilen, beliebige Metriken </p> </td> 
      <td colname="col2"> <p>Eine Optimierungseinstellung, die verhindert, dass zu viele Adobe Analytics-Daten heruntergeladen werden. </p> <p>Wenn Sie diese Option auf einen Wert ungleich null setzen, wird der Adobe Analytics-Datenabruf gestoppt, wenn die Gesamtzahl der für jede Metrik abgerufenen Zeilen den angegebenen Wert überschreitet. </p> <p>Der Standardwert ist 0. kein Höchstwert angewendet. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Metrikwiederholtes Abrufen (Zeilen) </p> </td> 
      <td colname="col2"> <p> Steuert die Anzahl der Adobe Analytics-Metrikwerte, die gleichzeitig abgerufen werden. Die Datenzeilen der Metrik werden wiederholt abgerufen, bis alle Daten abgerufen wurden oder bis die maximale Zeilengrenze erreicht ist. </p> <p>Normalerweise müssen Sie diese Einstellung nicht ändern. Es kann jedoch hilfreich sein, die Download-Phase der Metrik eines vollständigen Neuindexes Ihrer Site zu optimieren. </p> <p>Der Standardwert lautet 5000. </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. Klicken **[!UICONTROL Save Changes]**.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL History]** , um alle vorgenommenen Änderungen wiederherzustellen.

      Siehe [Verwenden der Option](../t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)Verlauf.

   * Klicken **[!UICONTROL Live]**.

      Siehe [Live-Einstellungen](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)anzeigen.

   * Klicken **[!UICONTROL Push Live]**.

      Siehe [Pushing-Einstellungen](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4).

## Informationen zu SAINT-Klassifizierungs-Feeds {#concept_C55609DA24914BBC92CD90ED0259199D}

Sie können Adobe Analytics SAINT verwenden, um Ihre Analyseberichte durch die Akzeptanz tabellarischer Daten aus externen Quellen zu verbessern. Beispielsweise können Sie mit der Site-Suche/dem Merchandising die Daten aus ihren eigenen Indizes abrufen und in Adobe Analytics exportieren.

Um die SAINT-Funktion von Adobe Analytics erfolgreich bei der Site-Suche/beim Merchandising zu verwenden, beachten Sie die folgenden Anforderungen:

* Sie benötigen ein Adobe Analytics-Unternehmen und eine Report Suite.

   Siehe [Info zum Adobe Analytics-Menü](../c-about-settings-menu/c-about-adobe-analytics-menu.md#concept_5FD2D13C9D0D40988E6E51480D690411).
* Das Adobe Analytics-Benutzerkonto muss über Berechtigungen zum Ändern der Report Suite verfügen.

   Siehe [Einrichten der Adobe Analytics-Metrikauthentifizierung](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_8AA93F6273B747F9B4DE9E8DFBCBDC42).
* Der Adobe Analytics-Benutzer muss zur Web-API-Gruppe gehören, damit er die Adobe Analytics Web API verwenden kann.
* Der Suchindex muss über Daten verfügen, die Adobe Analytics verwenden kann, z. B. über Daten im richtigen Format.

Bevor Sie einen Feed erstellen, prüfen Sie die folgenden Fragen und Informationen, damit Sie den SAINT-Feed-Assistenten erfolgreich abschließen können:

* Mit welcher Report Suite arbeiten Sie?
* Für welchen Classification-Satz, wie z. B. Produkt, eVar usw., werden Daten bereitgestellt?
* Welche Klassifizierungen gibt es in den Berichten? Die Antwort auf diese Frage wird von der Art der Daten bestimmt, die bei der Site-Suche/beim Merchandising leicht verfügbar sind, und von der Art der Berichte, die Adobe Analytics als gewünscht meldet.
* SAINT akzeptiert die Daten aus der Site-Suche/dem Merchandising als Texttyp. Das Format dieser Daten wirkt sich auf die Präsentation der Adobe Analytics-Berichte aus.

## Erstellen eines Adobe Analytics-SAINT-Feeds {#task_914B5AB821E84627953D8EF9339A7DD0}

Sie können Adobe Analytics SAINT verwenden, um Adobe Analytics-Berichte durch die Akzeptanz tabellarischer Daten aus externen Quellen zu verbessern.

Beispielsweise können Sie mit der Site-Suche/dem Merchandising Daten aus eigenen Indizes abrufen und diese Daten in Adobe Analytics exportieren.

**So erstellen Sie einen Adobe Analytics-SAINT-Feed**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL SAINT Classification Feeds]**.
1. Klicken Sie auf der [!DNL SAINT Classification Feeds] Seite auf **[!UICONTROL Create SAINT Feed]**.
1. Geben Sie im [!DNL Create Feed] Dialogfeld im Textfeld **Feed-Name** den neuen Feed-Namen ein und klicken Sie dann auf **[!UICONTROL Next]**.

   An dieser Stelle wird der Feed gespeichert und der [!DNL SAINT Classification Feed] Seite hinzugefügt. Bei Bedarf können Sie den Feed beenden und später bearbeiten, um den Assistenten abzuschließen.
1. Geben Sie auf der [!DNL Authentication] Seite in den entsprechenden Textfeldern den Firmennamen, den Benutzernamen und das Webgeheimnis von Adobe Analytics ein und klicken Sie auf **[!UICONTROL Next]**.

   Vergewissern Sie sich, dass es berechtigt ist, die Web-API mit Adobe Analytics zu verwenden.
1. Wählen Sie auf der **[!UICONTROL Report Suite]** Seite eine Report Suite und ihren Classification-Datensatz und klicken Sie dann auf **[!UICONTROL Next]**.
1. Ordnen Sie auf der [!DNL Field Maps] Seite Adobe Analytics-Klassifizierungen den Datenfeldern für Site-Suche/Merchandising-Meta zu und klicken Sie auf **[!UICONTROL Next]**.

   Um Adobe Analytics-Klassifizierungen anzupassen, klicken Sie auf **[!UICONTROL Edit]** Adobe Analytics-Klassifizierungen, um sich bei Adobe Analytics anzumelden. Wenn Sie die Änderungen abgeschlossen haben, klicken Sie auf **[!UICONTROL Refresh Classifications]** , um die Auswahl der Klassifizierungen zu aktualisieren.
1. Auf der [!DNL Search Criteria] Seite können Daten aus der Site-Suche/dem Merchandising gefiltert werden, bevor sie an Adobe Analytics SAINT übermittelt werden. Erstellen Sie hier Filterregeln mithilfe der Rule Builder-Oberfläche und klicken Sie auf **[!UICONTROL Next]**.
1. Wählen Sie auf der [!DNL Configure FTP] Seite den FTP-Server aus. Geben Sie die Häufigkeit an, mit der Daten hochgeladen werden sollen, und klicken Sie dann auf **[!UICONTROL Next]**.

   Als bewährtes Verfahren verfügt jeder Feed über ein eigenes FTP-Konto, um einen versehentlichen Datenverlust zu vermeiden. Hier können Sie ein neues Adobe Analytics-FTP-Konto erstellen.
1. Klicken Sie auf der [!DNL Verification] Seite auf **[!UICONTROL Show Data View]** , um die Datenansichtsdarstellung der Ausgabe zu überprüfen. Wenn tatsächlich Feed-Dateien vorhanden sind, werden sie hier aufgelistet und können heruntergeladen werden.
1. Klicken **[!UICONTROL Close]**.

## Bearbeiten eines Adobe Analytics SAINT-Feeds {#task_5BF34D02D0D14359B1CF4B3C1B0ACC84}

Sie können alle Aspekte eines vorhandenen SAINT-Feeds bearbeiten, den Sie erstellt haben.

**So bearbeiten Sie einen Adobe Analytics-SAINT-Feed**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL SAINT Classification Feeds]**.
1. Klicken Sie auf der [!DNL Saint Classification Feeds] Seite unter der **[!UICONTROL Name]** Spalte in der Dropdownliste neben einem Feed auf **[!UICONTROL Edit feed]**.
1. Geben Sie im Dialogfeld SAINT-Feed im Textfeld **Feed-Name** den neuen Feed-Namen ein und klicken Sie dann auf **[!UICONTROL Next]**.

   An dieser Stelle wird der Feed gespeichert und der [!DNL SAINT Classification Feed] Seite hinzugefügt. Bei Bedarf können Sie den Feed beenden und später bearbeiten, um den Assistenten abzuschließen.
1. Geben Sie auf der [!DNL Authentication] Seite in den entsprechenden Textfeldern den Firmennamen, den Benutzernamen und das Webgeheimnis von Adobe Analytics ein und klicken Sie auf **[!UICONTROL Next]**.

   Vergewissern Sie sich, dass es berechtigt ist, die Web-API mit Adobe Analytics zu verwenden.
1. Wählen Sie auf der **[!UICONTROL Report Suite]** Seite eine Report Suite und ihren Classification-Datensatz und klicken Sie dann auf **[!UICONTROL Next]**.
1. Ordnen Sie auf der [!DNL Field Maps] Seite Adobe Analytics-Klassifizierungen den Datenfeldern für Site-Suche/Merchandising-Meta zu und klicken Sie auf **[!UICONTROL Next]**.

   Um Adobe Analytics-Klassifizierungen anzupassen, klicken Sie auf **[!UICONTROL Edit]** Adobe Analytics-Klassifizierungen, um sich bei Adobe Analytics anzumelden. Wenn Sie die Änderungen abgeschlossen haben, klicken Sie auf **[!UICONTROL Refresh Classifications]** , um die Auswahl der Klassifizierungen zu aktualisieren.
1. Auf der [!DNL Search Criteria] Seite können Daten aus der Site-Suche/dem Merchandising gefiltert werden, bevor sie an Adobe Analytics SAINT übermittelt werden. Erstellen Sie hier Filterregeln mithilfe der Rule Builder-Oberfläche und klicken Sie auf **[!UICONTROL Next]**.
1. Wählen Sie auf der [!DNL Configure FTP] Seite den FTP-Server aus. Geben Sie die Häufigkeit an, mit der Daten hochgeladen werden sollen, und klicken Sie dann auf **[!UICONTROL Next]**.

   Als bewährtes Verfahren verfügt jeder Feed über ein eigenes FTP-Konto, um einen versehentlichen Datenverlust zu vermeiden. Hier können Sie ein neues Adobe Analytics-FTP-Konto erstellen.
1. Klicken Sie auf der [!DNL Verification] Seite auf **[!UICONTROL Show Data View]** , um die Datenansichtsdarstellung der Ausgabe zu überprüfen. Wenn tatsächlich Feed-Dateien vorhanden sind, werden sie hier aufgelistet und können heruntergeladen werden.
1. Klicken **[!UICONTROL Close]**.

## Löschen eines Adobe Analytics SAINT-Feeds {#task_5319B1F4CA1A406393CFD7AE97258CEB}

Sie können einen vorhandenen Adobe Analytics SAINT-Feed löschen, den Sie nicht mehr benötigen oder verwenden.

**So löschen Sie einen Adobe Analytics-SAINT-Feed**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL SAINT Classification Feeds]**.
1. Klicken Sie auf der [!DNL Saint Classification Feeds] Seite unter der **[!UICONTROL Name]** Spalte in der Dropdownliste neben dem Feed, den Sie entfernen möchten, auf **[!UICONTROL Delete feed]**.
1. Klicken Sie im Dialogfeld Löschen auf **Ja** , um den Löschvorgang zu überprüfen.

## Anzeigen einer Adobe Analytics SAINT-Feed-Datei {#task_F0C8BADD25E14E5DB30BF31D1F879FDB}

Sie können die [!DNL Verification] Seite eines vorhandenen SAINT-Feeds öffnen, um die Datenansichtsdarstellung der Ausgabe zu überprüfen.

Wenn tatsächlich Feed-Dateien vorhanden sind, werden sie hier aufgeführt und können als Textdatei heruntergeladen werden.

**So zeigen Sie eine Adobe Analytics-SAINT-Feed-Datei an**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL SAINT Classification Feeds]**.
1. Klicken Sie auf der [!DNL Saint Classification Feeds] Seite unter der **[!UICONTROL Name]** Spalte in der Dropdownliste neben einem Feed auf **[!UICONTROL View Feed Files]**.
1. (Optional) Klicken Sie auf , **[!UICONTROL Download File]** um die Feed-Datei als Textdatei zu speichern.
1. Klicken Sie auf **[!UICONTROL Close]** , um zur [!DNL SAINT Classification Feeds] Seite zurückzukehren.

## Testen eines Adobe Analytics SAINT-Feeds {#task_9864D69BE3824FC29C10B36EE4855D25}

Sie können einen vorhandenen Adobe Analytics SAINT-Feed ohne Datei-Upload testen.

Siehe [Generieren und Hochladen eines Adobe Analytics SAINT-Feeds](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_47AED946AA964334A877FDC8D4F6F00A).

Siehe [Anzeigen einer Adobe Analytics SAINT-Feed-Datei](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_F0C8BADD25E14E5DB30BF31D1F879FDB).

**So testen Sie eine Adobe Analytics-SAINT-Feed-Datei**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL SAINT Classification Feeds]**.
1. Klicken Sie auf der [!DNL Saint Classification Feeds] Seite unter der **[!UICONTROL Name]** Spalte in der Dropdownliste neben einem Feed auf **[!UICONTROL Test Feed (No file upload)]**.
1. Klicken Sie nach Abschluss der Verarbeitung des Feeds in der Dropdownliste des Feed-Namens auf **[!UICONTROL View Feed Files]**.
1. Klicken Sie auf der [!DNL Verification] Seite auf **[!UICONTROL Download File]** , um die Feed-Datei herunterzuladen.
1. Klicken Sie auf **[!UICONTROL Close]** , um zur [!DNL SAINT Classification Feeds] Seite zurückzukehren.

## Erstellen und Hochladen eines Adobe Analytics SAINT-Feeds {#task_47AED946AA964334A877FDC8D4F6F00A}

Sie können Feed-Dateien für einen vorhandenen Adobe Analytics-Feed erstellen und hochladen, den Sie erstellt haben.

Siehe [Testen eines Adobe Analytics SAINT-Feeds](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_9864D69BE3824FC29C10B36EE4855D25).

Siehe [Anzeigen einer Adobe Analytics SAINT-Feed-Datei](../c-about-settings-menu/c-about-adobe-analytics-menu.md#task_F0C8BADD25E14E5DB30BF31D1F879FDB).

**So erstellen und laden Sie eine Adobe Analytics SAINT-Feed-Datei hoch**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Settings]** > **[!UICONTROL Adobe Analytics]** > **[!UICONTROL SAINT Classification Feeds]**.
1. Klicken Sie auf der [!DNL Saint Classification Feeds] Seite unter der **[!UICONTROL Name]** Spalte in der Dropdownliste neben einem Feed auf **[!UICONTROL Generate and Upload Feed]**.
1. Klicken Sie nach Abschluss der Verarbeitung des Feeds in der Dropdownliste des Feed-Namens auf **[!UICONTROL View Feed Files]**.
1. Klicken Sie auf der [!DNL Verification] Seite auf **[!UICONTROL Download File]** , um die Feed-Datei herunterzuladen.
1. Klicken Sie auf **[!UICONTROL Close]** , um zur [!DNL SAINT Classification Feeds] Seite zurückzukehren.