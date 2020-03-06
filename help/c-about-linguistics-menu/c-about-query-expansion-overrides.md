---
description: Sie können die Erweiterung der Suchabfrageergebnisse überschreiben.
seo-description: Sie können die Erweiterung der Suchabfrageergebnisse überschreiben.
seo-title: Außerkraftsetzungen der Abfrageerweiterung
solution: Target
title: Außerkraftsetzungen der Abfrageerweiterung
topic: Linguistics,Site search and merchandising
uuid: dfe18004-b8fd-4889-b01c-72a3b0c82b9c
translation-type: tm+mt
source-git-commit: ef818327e1cdaad79ac47575a8dfba1de3dc5c2e

---


# Außerkraftsetzungen der Abfrageerweiterung{#about-query-expansion-overrides}

Sie können die Erweiterung der Suchabfrageergebnisse überschreiben.

## Außerkraftsetzung der Abfrageerweiterung {#concept_6895B469B0E044299E93361BFA06B554}

Wenn Sie eine Außerkraftsetzung der Abfrageerweiterung konfigurieren, erstellen Sie einen Regelsatz. Jede Regel besagt im Wesentlichen: &quot;Zum Zeitpunkt der Suche nicht `<this>` in `<that>` die Regel eingehen&quot;, wobei `<this>` es sich um ein einfaches Textwort oder eine einfache Wortgruppe und `<that>` um ein Textwort, eine Wortgruppe oder eine Klassifizierung handelt.

>[!NOTE]
>
>Diese Funktion ist in Search&amp;Promote nicht standardmäßig aktiviert. Wenden Sie sich an den technischen Support, um die Funktion für Ihre Verwendung zu aktivieren. Nachdem die Funktion zum Überschreiben der Abfrageerweiterung aktiviert wurde, müssen Sie sie in der Benutzeroberfläche aktivieren.

**Funktionsweise einer Abfrageerweiterung**

Wenn auf der Seite &quot;Abfrageerweiterung außer Kraft setzen&quot;ein Wert für &quot;Text und Begriff&quot;angegeben ist, wirkt der Code auf die jeweilige Paarung. Wenn ein Klassifizierungstyp als Begriff angegeben wird, z. B. Wörterbücher oder alternative Word-Formulare, wird der Wert &quot;Nicht erweitern&quot;nicht in ein mit der angegebenen Klassifizierung erstelltes Formular umgewandelt.

Angenommen, Sie haben die folgende Definition:

`Do Not Expand = "dog"`

`Type = Text`

`Term = "dogs"`

Eine Suchabfrage nach &quot;Hund&quot;, die sich erweitert, um &quot;Hunde&quot; und &quot;Hunde&quot; durch alternative Word-Formulare einzuschließen, enthält nicht &quot;Hunde&quot;.

Wenn die Definition jedoch wie folgt lautet:

`Do Not Expand = "dog"`

`Type = Alternate Word Forms`

Die Abfrage enthält weder &quot;Hunde&quot;noch &quot;Hunde&quot;(die verfügbaren alternativen Word-Formulare für &quot;Hund&quot;).

Sie können mehrere Begriffe, mehrere Klassifizierungen oder beides angeben. Wenn Sie jedoch &quot;Alle&quot;als Typ auswählen, wird eine Liste mit mehreren Begriffen auf einen einzigen &quot;Alle&quot;reduziert.

Wenn Text- und Classification-Einträge in einer Regel gemischt werden, werden sie in der Benutzeroberfläche neu angeordnet, um zunächst die Textwerte anzuzeigen. Dies bedeutet jedoch nicht, dass die Reihenfolge der Auswertung zum Zeitpunkt der Suche beeinträchtigt wird.

Textbegriffe werden validiert, um aussagekräftige Verweise zu entfernen. Das heißt, der Begriff wird mit dem Wert &quot;Nicht erweitern&quot;verglichen und der Begriff wird entfernt, wenn eine Übereinstimmung vorliegt. Außerdem werden doppelte Begriffswerte, entweder Text oder Klassifizierung, entfernt.

Wenn Sie eine neue Regel hinzufügen, deren Wert &quot;Nicht erweitern&quot;einer früheren Definition entspricht, werden die Begriffe der neuen Definition dem Original hinzugefügt.

## Konfigurieren von Außerkraftsetzungen der Abfrageerweiterung {#task_A087354A509D4997BA275186C224160E}

Definieren und Hinzufügen einer Außerkraftsetzung der Abfrageerweiterung in Search&amp;Promote.

<!-- 

t_configuring_query_expansion_overrides.xml

 -->

>[!NOTE]
Diese Funktion ist in Search&amp;Promote nicht standardmäßig aktiviert. Wenden Sie sich an den technischen Support, um die Funktion für Ihre Verwendung zu aktivieren. Nachdem die Funktion zum Überschreiben der Abfrageerweiterung aktiviert wurde, müssen Sie sie in der Benutzeroberfläche aktivieren. Die ersten Schritte unten beschreiben, wie das zu bewerkstelligen ist.

**So konfigurieren Sie Außerkraftsetzungen der Abfrageerweiterung**

1. Klicken Sie in Search&amp;Promote auf **Einstellungen** > **Benutzer** > Rollen **anzeigen**.
1. Klicken Sie auf der Seite &quot;Rollen anzeigen&quot;in der Spalte &quot;Aktionen&quot;der Tabelle rechts neben der Rolle, der Sie Zugriff auf Abfrageerweiterungsüberschreibungen gewähren möchten, im Menü &quot;Linguistik&quot;auf &quot; **Bearbeiten** &quot;.
1. Erweitern Sie auf der Seite &quot;Rolle bearbeiten&quot;die Struktur Linguistik.
1. Markieren Sie **Abfrageerweiterungsüberschreibungen** und klicken Sie dann auf Änderungen **speichern**.
1. Klicken Sie auf **Linguistik** > **Abfrageerweiterungsüberschreibungen**.
1. Klicken Sie auf Außerkraftsetzung **der Abfrageerweiterung** hinzufügen.
1. Legen Sie auf der Seite &quot;Abfrageerweiterung außer Kraft setzen&quot;die gewünschten Optionen fest.

   <!-- 
   
   r_query_expansion_override_definitions.xml
   
   -->

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>Option </p> </th> 
      <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>Nicht erweitern </p> </td> 
      <td colname="col2"> <p>Gibt das Wort oder die Wortgruppe an, das bzw. die Sie nicht erweitern möchten. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Typ  </p> </td> 
      <td colname="col2"> <p>Wählen Sie " <b>Text</b> "aus, um die Paarung eines bestimmten Wortes oder einer bestimmten Wortgruppe festzulegen. Sie können auch eine Klassifizierung auswählen, um anzugeben, dass das Wort oder die Wortgruppe "Nicht erweitern"nicht mithilfe der ausgewählten Klassifizierung konvertiert wird. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Begriff </p> </td> 
      <td colname="col2"> <p>Nur verfügbar, wenn Sie <b>Text</b> als Typ ausgewählt haben. Gibt das Wort oder die Wortgruppe an, die/die von der Sucherweiterung ausgeschlossen werden soll. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Aktion </p> </td> 
      <td colname="col2"> <p> Klicken Sie auf <b>+</b> oder <b>-</b> , um der Definition Begriffe hinzuzufügen bzw. zu löschen. </p> </td> 
      </tr> 
    </tbody> 
    </table>

1. Wenn Sie fertig sind, klicken Sie auf **Hinzufügen**.

   Auf der Seite &quot;Definitionen für Abfrageerweiterung außer Kraft setzen&quot;können Sie die hinzugefügten Definitionen bearbeiten oder löschen.
1. Um die Ergebnisse Ihrer Ergänzungen in der Vorschau anzuzeigen, klicken Sie im blauen Feld auf den Link zum **Erstellen des Staged Site-Index** , um den Stage-Website-Index schnell neu zu erstellen.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **Live**.

      Siehe [Live-Einstellungen anzeigen](../c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)

   * Klicken Sie auf **Live**&#x200B;übertragen.

      Siehe [Pushing-Einstellungen live](../c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4)
