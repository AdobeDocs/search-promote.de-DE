---
description: Sie können verschiedene Bereiche von "Autom. ausfüllen"konfigurieren, um die Erstellung des für die automatische Vervollständigung aktivierten Suchformulars und der Datei "autocomplete_data.js"zu steuern, die als Teil des für die automatische Vervollständigung aktivierten Suchformulars enthalten ist.
seo-description: Sie können verschiedene Bereiche von "Autom. ausfüllen"konfigurieren, um die Erstellung des für die automatische Vervollständigung aktivierten Suchformulars und der Datei "autocomplete_data.js"zu steuern, die als Teil des für die automatische Vervollständigung aktivierten Suchformulars enthalten ist.
seo-title: Info zur automatischen Vervollständigung
solution: Target
subtopic: Auto-Complete
title: Info zur automatischen Vervollständigung
topic: Design,Site search and merchandising
uuid: 3dfdd14d-2044-4f01-a5bc-fcb2eb0d5068
translation-type: tm+mt
source-git-commit: 439100ab96f4b597c55b1c1ae38a5778c208e896

---


# Info zur automatischen Vervollständigung{#about-auto-complete}

Sie können verschiedene Bereiche von &quot;Autom. ausfüllen&quot;konfigurieren, um die Erstellung des für die automatische Vervollständigung aktivierten Suchformulars und der Datei &quot;autocomplete_data.js&quot;zu steuern, die als Teil des für die automatische Vervollständigung aktivierten Suchformulars enthalten ist.

## Info zur automatischen Vervollständigung {#concept_093A9CD754864BA79B456FE4BEB64578}

Die Datei [!DNL autocomplete_data.js] wird jedes Mal neu generiert und im Netzwerk für Suchinhalte veröffentlicht, wenn Änderungen vorgenommen wurden, die auf der Seite &quot;Auto-Complete-Einrichtung&quot;gespeichert wurden.

## Konfigurieren der automatischen Vervollständigung {#task_F491F2BFC4D24A61BBDC48B9059C11BB}

Sie können die Optionen konfigurieren und einrichten, mit denen die Erstellung des Suchformulars und der Datei mit aktivierter automatischer Vervollständigung gesteuert wird.

<!-- 

t_configuring_auto-complete.xml

 -->

Nachdem Sie die automatische Vervollständigung konfiguriert haben, können Sie die resultierende HTML-Quelle zur Überprüfung anzeigen. Die HTML-Quelle ist das, was Sie kopieren und in die Seiten Ihrer Website einfügen.

Siehe [Anzeigen einer Vorschau des Suchformulars, wie es auf Ihrer...](c-about-auto-complete.md#task_437B35EFA5424603A08AF8E79E6B4714).

Siehe [Konfigurieren der Liste](c-about-auto-complete.md#task_1F8E0F346263443383F8CFD2C7AB35D4)mit automatischem Ausfüllen.

Siehe [Konfigurieren der automatischen Vervollständigung von CSS](c-about-auto-complete.md#task_EECE35DEB6C94F4A8A5B42B4DED76D96).

**So konfigurieren Sie die automatische Vervollständigung**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Design]** > **[!UICONTROL Auto-Complete]** > **[!UICONTROL Auto-Complete Setup]**.
1. Legen Sie auf der [!DNL Auto-Complete Setup] Seite die gewünschten Optionen fest.

   Siehe auch [Vorschau des Suchformulars, wie es auf Ihrer...](c-about-auto-complete.md#task_437B35EFA5424603A08AF8E79E6B4714).

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>Option </p> </th> 
      <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>Maximale Empfehlungen </p> </td> 
      <td colname="col2"> <p>Gibt die maximale Anzahl von Elementen an, die in der Liste der Vorschläge zur automatischen Vervollständigung angezeigt werden sollen. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Mindesteingabezeichen </p> </td> 
      <td colname="col2"> <p>Gibt die Anzahl der Zeichen an, die ein Kunde in das Suchformular für die automatische Vervollständigung eingeben muss, bevor Vorschläge angezeigt werden. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Maximale Cacheeinträge </p> </td> 
      <td colname="col2"> <p>Gibt die maximale Anzahl der zuvor angeforderten Vorschläge zur automatischen Vervollständigung an, die im Browser des Kunden zwischengespeichert werden sollen. Im Allgemeinen sollten Sie diese Einstellung auf den Standardwert 1000 setzen. </p> <p>Sie können die Browserzwischenspeicherung zwar vollständig deaktivieren, indem Sie diese Option auf 0 setzen, jedoch wird dies nicht empfohlen. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Name des Formulars </p> </td> 
      <td colname="col2"> <p>Gibt das Attribut "name"des "form"-Tags des für die automatische Vervollständigung aktivierten Suchformulars an. Beispiel: </p> <p> <span class="filepath"> &lt;form name="SiteSearch" method="get" action="https://sp1004337c.guided.t1.atomz.com" target="_blank"&gt; </span> </p> <p>wobei <span class="filepath"> SiteSearch </span> das Namensattribut des form-Tags ist. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Div-Tag-ID </p> </td> 
      <td colname="col2"> <p>Gibt das ID-Attribut des "div"-Tags des für die automatische Vervollständigung aktivierten Suchformulars an. Beispiel: </p> <p> <span class="filepath"> &lt;div id="autocomplete"&gt; </span> </p> <p>wobei <span class="filepath"> autocomplete </span> das Attribut des div-Tags ist. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Eingabe-Tag-ID </p> </td> 
      <td colname="col2"> <p>Gibt das ID-Attribut des Tags "input"des automatisch ausgefüllten Suchformulars an. Beispiel: </p> <p> <span class="filepath"> &lt;input type="text" id="q" name="q" /&gt; </span> </p> <p>wobei <span class="filepath"> q </span> das id-Attribut des input-Tags ist. </p> </td> 
      </tr> 
      <tr>
      <td colname="col1"> <p>Schatten anzeigen </p> </td>
      <td colname="col2"> <p>Fügt der Liste der Vorschläge für die automatische Vervollständigung einen kosmetischen Schlagschatten hinzu. </p> </td>
      </tr>
      <tr>
      <td colname="col1"> <p>Übereinstimmung nur am Anfang der Wortgruppe </p> </td>
      <td colname="col2"> <p>Nur Ergebnisse vorschlagen, die mit dem Anfang des Eingabetextes übereinstimmen . </p> </td>
      </tr>
      <tr>
      <td colname="col1"> <p>UTF-8-Zeichensatz unterstützen </p> </td>
      <td colname="col2"> <p>Korrigiert Nicht-ASCII-Zeichen in Begriffen. </p> </td>
      </tr>
    </tbody> 
   </table>

1. Klicken **[!UICONTROL Save Changes]**.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL History]** , um alle vorgenommenen Änderungen wiederherzustellen.

      Siehe [Verwenden der Option](t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)Verlauf.

   * Klicken **[!UICONTROL Live]**.

      Siehe [Live-Einstellungen](c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)anzeigen.

   * Klicken **[!UICONTROL Push Live]**.

      Siehe [Pushing-Einstellungen](c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4).

## Konfigurieren der Liste für die automatische Vervollständigung von Wörtern {#task_1F8E0F346263443383F8CFD2C7AB35D4}

Konfigurieren Sie die Liste der Wörter und Ausdrücke, die ein automatisches Ausfüllen dem Kunden als Vorschläge angezeigt wird.

<!-- 

t_configuring_auto-complete_word_list.xml

 -->

Siehe [Konfigurieren des automatischen Ausfüllens](c-about-auto-complete.md#task_F491F2BFC4D24A61BBDC48B9059C11BB).

Siehe [Konfigurieren der automatischen Vervollständigung von CSS](c-about-auto-complete.md#task_EECE35DEB6C94F4A8A5B42B4DED76D96).

**So konfigurieren Sie die Liste der automatisch auszufüllenden Wörter**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Design]** > **[!UICONTROL Auto-Complete]** > **[!UICONTROL Auto-Complete Word List]**.
1. Legen Sie auf der [!DNL Auto-Complete Word List] Seite die gewünschten Optionen fest.

   Siehe [Anzeigen einer Vorschau des Suchformulars, wie es auf Ihrer...](c-about-auto-complete.md#task_437B35EFA5424603A08AF8E79E6B4714).

   <table> 
    <thead> 
      <tr> 
      <th colname="col1" class="entry"> <p>Option </p> </th> 
      <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
      </tr> 
    </thead>
    <tbody> 
      <tr> 
      <td colname="col1"> <p>Zeitraum für gängige Suchen </p> </td> 
      <td colname="col2"> <p> Steuert den Zeitraum für die Aufnahme von Wörtern und Wortgruppen aus den jüngsten Suchvorgängen des Kunden. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p> Maximale Suchanzahl </p> </td> 
      <td colname="col2"> <p>Steuert die maximale Anzahl von gesuchten Wörtern und Ausdrücken, die in die Liste der automatisch ausgefüllten Wörter aufgenommen werden sollen. Die wichtigsten Wörter und Ausdrücke, die auch am beliebtesten sind, sind eingeschlossen. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Feldname </p> </td> 
      <td colname="col2"> <p>Jeder Feldname definiert den Namen eines Felds, für das indizierte Werte aufgenommen werden sollen. Verwenden Sie + und -, um Feldnamen hinzuzufügen oder zu entfernen. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Maximum Value Count </p> </td> 
      <td colname="col2"> <p>Definiert die maximale Anzahl von Feldwerten, die für den ausgewählten Feldnamen zulässig sind. Die obersten Werte, die auch am häufigsten referenziert werden, werden einbezogen. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Fügen Sie diese Wörter und Ausdrücke hinzu </p> </td> 
      <td colname="col2"> <p> Die Liste mit den Wörtern und Ausdrücken, die in diesem Bereich aufgeführt sind, wird automatisch ausgefüllt. </p> <p> Klicken Sie auf <span class="uicontrol"> Bearbeiten, </span> um die Liste anzuzeigen oder der Liste Wörter und Wortgruppen hinzuzufügen. Wenn Sie fertig sind, klicken Sie auf <span class="uicontrol"> Änderungen speichern </span>. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Entfernen Sie diese Wörter und Ausdrücke </p> </td> 
      <td colname="col2"> <p> Einträge in diesem Bereich werden nicht in der Liste der automatisch ausgefüllten Wörter angezeigt. </p> <p> Klicken Sie auf <span class="uicontrol"> Bearbeiten, </span> um die Liste anzuzeigen oder der Liste Wörter und Wortgruppen hinzuzufügen. Wenn Sie fertig sind, klicken Sie auf <span class="uicontrol"> Änderungen speichern </span>. </p> <p> Reguläre Ausdrücke sind in dieser Liste zulässig. Um einen regulären Ausdruck in dieser Liste anzugeben, starten Sie die Zeile mit 
        <userinput>
          regexp 
        </userinput> gefolgt von einem Leerzeichen, gefolgt vom regulären Ausdruck. Alle Zeilen in der Wortliste, die mit dem regulären Ausdruck übereinstimmen, werden entfernt. </p> <p> <b>Wichtig</b>: Sie sollten reguläre Ausdrücke nur dann verwenden, wenn Sie zuvor mit ihnen in anderen Anwendungen gearbeitet haben. </p> <p>Siehe <a href="c-appendices/r-regular-expressions.md#reference_B5BA7D61D82E4109A01D2A2D964E3A6A" type="reference" format="dita" scope="local"> Reguläre Ausdrücke </a>. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Groß-/Kleinschreibung ignorieren </p> </td> 
      <td colname="col2"> <p>Doppelte Einträge in der Liste der automatisch ausgefüllten Wörter, die sich nur in alphabetischer Groß-/Kleinschreibung unterscheiden, werden entfernt. Alle Einträge in der Wortliste werden in Kleinbuchstaben umgewandelt. </p> <p>Wenn die Vorschläge zum automatischen Ausfüllen als "erster Buchstabe mit Großbuchstaben"oder "Großbuchstaben"angezeigt werden sollen, fügen Sie die 
        <userinput>
          text-transform : kapitalisieren; 
        </userinput> oder 
        <userinput>
          text-transform : Großbuchstabe; 
        </userinput> CSS-Texteigenschaften auf den CSS-Inhalt automatisch ausfüllen, unter "/* Stile für Ergebniselement */". </p> <p>Siehe <a href="c-about-auto-complete.md#task_EECE35DEB6C94F4A8A5B42B4DED76D96" type="task" format="dita" scope="local"> Konfigurieren der automatischen Vervollständigung von CSS </a>. </p> </td> 
      </tr> 
      <tr> 
      <td colname="col1"> <p>Aktualisierung auf Neuindex </p> </td> 
      <td colname="col2"> <p>Die Wörterliste für die automatische Vervollständigung wird nach jeder erfolgreichen Kontoneuindizierung automatisch neu generiert. </p> </td> 
      </tr> 
    </tbody> 
   </table>

1. Klicken **[!UICONTROL Save Changes]**.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL History]** , um alle vorgenommenen Änderungen wiederherzustellen.
   * Klicken Sie **[!UICONTROL Preview Word List]** auf , um alle von Ihnen vorgenommenen Änderungen zu speichern, und öffnen Sie dann die [!DNL Auto-Complete Word List Preview] Seite, auf der Sie die Liste der Vorschläge zur automatischen Vervollständigung überprüfen können. Verwenden Sie die Navigationsoptionen am oberen Rand der Seite, um die angezeigte Liste zu überprüfen und zu verfeinern. Wenn Sie fertig sind, klicken Sie auf **[!UICONTROL Close]** , um zur [!DNL Auto-Complete Word List] Seite zurückzukehren.

      Siehe [Verwenden der Option](t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)Verlauf.

   * Klicken **[!UICONTROL Live]**.

      Siehe [Live-Einstellungen](c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)anzeigen.

   * Klicken **[!UICONTROL Push Live]**.

      Siehe [Pushing-Einstellungen](c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4).

## Konfigurieren der automatischen Vervollständigung von CSS {#task_EECE35DEB6C94F4A8A5B42B4DED76D96}

Verwenden Sie die automatische Vervollständigung von CSS, um das zu verwendende Cascading Stylesheet zu konfigurieren.

<!-- 

t_configuring_auto-complete_css.xml

 -->

Automatisches Ausfüllen von CSS steuert den Inhalt von [!DNL autocomplete_styles.css], der als Teil des für die automatische Vervollständigung aktivierten Suchformulars enthalten ist. Das hier angegebene CSS steuert die visuelle Darstellung der Liste mit Empfehlungen für die automatische Vervollständigung. Ein Beispiel für mögliche visuelle Darstellungskonzepte finden Sie hier:

[https://developer.yahoo.com/yui/examples/autocomplete/ac_skinning.html](https://developer.yahoo.com/yui/examples/autocomplete/ac_skinning.html).

[Konfigurieren der Liste](c-about-auto-complete.md#task_1F8E0F346263443383F8CFD2C7AB35D4)für die automatische Vervollständigung von Wörtern.

[Konfigurieren der automatischen Vervollständigung](c-about-auto-complete.md#task_F491F2BFC4D24A61BBDC48B9059C11BB).

Wenn Sie mit der Konfiguration von CSS zum automatischen Ausfüllen fertig sind, können Sie eine Vorschau des Suchformulars anzeigen, um zu sehen, ob die von Ihnen angegebene CSS in Erscheinungsbild und Layout akzeptabel ist.

Siehe [Anzeigen einer Vorschau des Suchformulars, wie es auf Ihrer...](c-about-auto-complete.md#task_437B35EFA5424603A08AF8E79E6B4714).

**Wichtig**: Um Ihre benutzerdefinierte CSS für die automatische Vervollständigung anzuwenden, müssen Sie die Kommentar-Tags aus der zweiten Zeile entfernen, die im HTML-Code angezeigt wird. Dann verschieben Sie die gleiche Zeile in den Kopfabschnitt der Seite, die das Suchformular enthält.

Siehe [Kopieren des HTML-Codes des Suchformulars in die...](c-about-auto-complete.md#task_A3A01EA800F24C0AA33902387E0362C7).

**So konfigurieren Sie die automatisch vervollständigte CSS**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Design]** > **[!UICONTROL Auto-Complete]** > **[!UICONTROL Auto-Complete CSS]**.
1. Geben Sie im [!DNL Auto-Complete CSS] Textfeld die Kaskadenstilblattinformationen ein, die Sie mit der Liste für die automatische Vervollständigung verknüpfen möchten.
1. Klicken **[!UICONTROL Save Changes]**.
1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Klicken Sie auf **[!UICONTROL History]** , um alle vorgenommenen Änderungen wiederherzustellen.

      Siehe [Verwenden der Option](t-using-the-history-option.md#task_70DD3F87A67242BBBD2CB27156F43002)Verlauf.

   * Klicken **[!UICONTROL Live]**.

      Siehe [Live-Einstellungen](c-about-staging.md#task_401A0EBDB5DB4D4CA933CBA7BECDC10F)anzeigen.

   * Klicken **[!UICONTROL Push Live]**.

      Siehe [Pushing-Einstellungen](c-about-staging.md#task_44306783B4C0408AAA58B471DAF2D9A4).

## Anzeigen einer Vorschau des Suchformulars, wie es auf Ihrer Website angezeigt wird {#task_437B35EFA5424603A08AF8E79E6B4714}

Je nach Konfiguration der CSS zum automatischen Ausfüllen und automatischen Ausfüllen können Sie eine Vorschau des Suchformulars anzeigen, wenn Sie den HTML-Code zu Ihrer Website hinzufügen möchten.

<!-- 

t_previewing_the_search_form_as_it_would_appear_on_your_website.xml

 -->

Siehe [Konfigurieren des automatischen Ausfüllens](c-about-auto-complete.md#task_F491F2BFC4D24A61BBDC48B9059C11BB).

Siehe [Konfigurieren der automatischen Vervollständigung von CSS](c-about-auto-complete.md#task_EECE35DEB6C94F4A8A5B42B4DED76D96).

Siehe [Kopieren des HTML-Codes des Suchformulars in die...](c-about-auto-complete.md#task_A3A01EA800F24C0AA33902387E0362C7).

Siehe [Verwenden von Sammlungen in Suchformularen](c-appendices/c-searchforms.md#reference_5A079AEEEFB84457892EF0870D0605C3).

Siehe [Verwenden von Frames mit Formularen](c-appendices/c-searchforms.md#reference_82CDDDA1E37042E4849EBF7EA05407C5).

Siehe [Beispiel für ein erweitertes Suchformular](c-appendices/c-searchforms.md#reference_82E1051918744EBA88A01E9E6AE42C4A).

Siehe HTML-Code [für erweiterte Suchformulare](c-appendices/c-searchforms.md#reference_9AAD4A46B68D4D48865508982CB86DB9).

Siehe [Erweiterter Vorlagencode](c-appendices/c-searchforms.md#reference_D762C22E754E462DBEECD88D2C3FA579)für Suchformulare.

**So zeigen Sie eine Vorschau des Suchformulars an, wie es auf Ihrer Website angezeigt wird**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Design]** > **[!UICONTROL Auto-Complete]** > **[!UICONTROL Search Form]**.
1. (Optional) Klicken Sie auf **[!UICONTROL HTML code]** , um den HTML-Code anzuzeigen, den Sie kopieren und in die Seiten Ihrer Website einfügen.

## Kopieren des HTML-Codes des Suchformulars in die Seiten Ihrer Website {#task_A3A01EA800F24C0AA33902387E0362C7}

Je nach Konfiguration der CSS zum automatischen Ausfüllen und automatischen Ausfüllen können Sie eine Vorschau des Suchformulars anzeigen, wenn Sie den HTML-Code zu Ihrer Website hinzufügen möchten.

<!-- 

t_copying_the_html_code_of_the_search_form_into_the_pages_of_your_website.xml

 -->

Siehe [Konfigurieren des automatischen Ausfüllens](c-about-auto-complete.md#task_F491F2BFC4D24A61BBDC48B9059C11BB).

Siehe [Konfigurieren der automatischen Vervollständigung von CSS](c-about-auto-complete.md#task_EECE35DEB6C94F4A8A5B42B4DED76D96).

Siehe [Kopieren des HTML-Codes des Suchformulars in die...](c-about-auto-complete.md#task_A3A01EA800F24C0AA33902387E0362C7).

Siehe [Verwenden von Sammlungen in Suchformularen](c-appendices/c-searchforms.md#reference_5A079AEEEFB84457892EF0870D0605C3).

Siehe [Verwenden von Frames mit Formularen](c-appendices/c-searchforms.md#reference_82CDDDA1E37042E4849EBF7EA05407C5).

Siehe [Beispiel für ein erweitertes Suchformular](c-appendices/c-searchforms.md#reference_82E1051918744EBA88A01E9E6AE42C4A).

Siehe HTML-Code [für erweiterte Suchformulare](c-appendices/c-searchforms.md#reference_9AAD4A46B68D4D48865508982CB86DB9).

Siehe [Erweiterter Vorlagencode](c-appendices/c-searchforms.md#reference_D762C22E754E462DBEECD88D2C3FA579)für Suchformulare.

**So kopieren Sie den HTML-Code des Suchformulars in die Seiten Ihrer Website**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Design]** > **[!UICONTROL Auto-Complete]** > **[!UICONTROL Form Source]**.

   >[!NOTE]
   >
   >Ändern Sie den `form name=` Wert in der Formularquelle nicht.

1. (Optional) Führen Sie einen der folgenden Schritte aus:

   * Wenn Sie die automatische Vervollständigung des CSS konfiguriert haben und die Stile auf das Suchformular angewendet werden sollen, entfernen Sie die Kommentar-Tags aus der zweiten Zeile, die im HTML-Code angezeigt wird. Verschieben Sie dann dieselbe Zeile in den Kopfabschnitt der Seite, die das Suchformular enthält.
   * Um eine maximale Leistung zu erzielen, verschieben Sie die Tags, die unten im HTML-Code aufgeführt sind, und platzieren Sie sie am unteren Rand des Textabschnitts jeder Seite, die das Suchformular enthält.

1. Kopieren Sie den Code und fügen Sie ihn auf den Webseiten Ihrer Website ein, auf denen das Suchformular angezeigt werden soll.