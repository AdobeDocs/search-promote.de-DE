---
description: Bei jeder Änderung Ihrer Website können Sie ein Skript oder Programm ausführen, das anfordert, dass der Suchroboter einen Index mit Remote Control ausführt.
solution: Target
title: Info zur Remote-Steuerung für die Indizierung
topic-legacy: Index,Site search and merchandising
uuid: 20e230c6-5c1a-4bf4-bff3-b8236d14ab21
exl-id: 1a7689f9-1e3f-48c8-a5f1-abe0efdb7768
translation-type: tm+mt
source-git-commit: 7559f5f7437d46e3510d4659772308666425ec96
workflow-type: tm+mt
source-wordcount: '1037'
ht-degree: 1%

---

# Info zur Remote-Steuerung für die Indizierung{#about-remote-control-for-indexing}

Bei jeder Änderung Ihrer Website können Sie ein Skript oder Programm ausführen, das anfordert, dass der Suchroboter einen Index mit Remote Control ausführt.

## Verwenden der Fernsteuerung für die Indizierung von {#concept_C79B322190E84106A434E5C6D4A4118F}

Die Indexanfrage für die Remote-Steuerung stammt in der Regel von einem Skript oder einem Programm, das sich auf Ihrem Server befindet.

Der Roboter führt dieselben Indexierungsschritte aus, als ob er manuell über das Menü [!DNL Index] gestartet wurde. Um eine Remote-Steuerungsanforderung zu senden, konfigurieren Sie die erforderlichen Kennwort- und Antwortzeichenfolgen.

## So erstellen Sie eine Remote-Steuerungsanforderung {#section_42FAB2BAB25A4E24BEA69566C6D1C70F}

Verwenden Sie zum Anfordern einer Remote-Steuerung die folgenden Formatbeispiele, die auf der Position Ihres Rechenzentrums basieren:

<table> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Position des Rechenzentrums </p> </th> 
   <th colname="col2" class="entry"> <p>Beispiel </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>London </p> </td> 
   <td colname="col2"> <p> <code> https://center.lon5.atomz.com/search/cgiindex.tk? <b>sp_a=sp99999999&amp;sp_password=xxxxxx&amp;sp_operation=op</b> </code> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nordamerika </p> </td> 
   <td colname="col2"> <p> <code> https://center.atomz.com/search/cgiindex.tk? <b>sp_a=sp99999999&amp;sp_password=xxxxxx&amp;sp_operation=op</b> </code> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Singapur </p> </td> 
   <td colname="col2"> <p> <code> https://center.sin2.atomz.com/search/cgiindex.tk? <b>sp_a=sp99999999&amp;sp_password=xxxxxx&amp;sp_operation=op</b> </code> </p> </td> 
  </tr> 
 </tbody> 
</table>

oder

<table> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> <p>Zeichenfolge und Wert </p> </th> 
   <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
  </tr> 
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> sp_a= sp999999999  </span> </p> </td> 
   <td colname="col2"> <p> Ihre Kontonummer. </p> <p>Sie finden Ihre Kontonummer unter <span class="uicontrol"> <b>Einstellungen</b> </span> &gt; <span class="uicontrol"> <b>Kontooptionen</b> </span> &gt; <span class="uicontrol"> <b>Kontoeinstellungen</b> </span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> sp_lines= N  </span> </p> </td> 
   <td colname="col2"> <p>Ermöglicht die Überprüfung des Status eines laufenden Index-Crawls. </p> <p> <span class="codeph">  N  </span> ist entweder eine positive Ganzzahl oder  <span class="codeph"> alles  </span>. Wenn es sich um einen numerischen Wert handelt, werden die letzten <span class="codeph"> N </span>-Zeilen der entsprechenden Indexprotokolldatei in die JSON-Antwort aufgenommen. </p> <p>Wenn der Wert <span class="codeph"> alle </span> lautet, wird die gesamte Datei zurückgegeben. </p> <p>Wenn der Wert <span class="codeph"> 0 </span> ist, werden keine Protokollinformationen zurückgegeben. Dieser Wert ist der Standardwert für eine laufende Indexstatus-Abfrage. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> sp_operation= op  </span> </p> </td> 
   <td colname="col2"> <p>Hier können Sie einen der folgenden Indizierungsvorgänge angeben, die Sie ausführen möchten: </p> <p> 
     <ul id="ul_6CA190AC41694BC293FC7C6BABA629FE"> 
      <li id="li_EFC76E31D47E473F9A56B2EBA8A97CA1"> <span class="codeph"> full_index  </span> <p>Der Suchroboter führt einen vollständigen Index Ihrer Website aus. </p> </li> 
      <li id="li_A9ACE21718804A21B3DA7B84AB6729D3"> <span class="codeph"> incremental_index  </span> <p>Der Suchroboter führt einen inkrementellen Index mit der Konfiguration aus, die unter <span class="uicontrol"> <b>Index</b> </span> &gt; <span class="uicontrol"> <b>Inkrementeller Index</b> </span> &gt; <span class="uicontrol"> <b>Konfiguration</b></span> eingestellt ist. </p> </li> 
      <li id="li_722FE409AE454AD48ACE95C4CDC7A00B"> <span class="codeph"> vertical_index  </span> <p>Der Suchroboter führt ein vertikales Update mit der unter <span class="uicontrol"> <b>Index</b> </span> &gt; <span class="uicontrol"> <b>Vertikales Update</b> </span> &gt; <span class="uicontrol"> <b>Konfiguration</b></span> festgelegten Konfiguration aus. </p> <p>Siehe <a href="../c-about-index-menu/c-about-vertical-updates.md#concept_E65A70C9C2E04804BF24FBE1B3CAD899" format="dita" scope="local"> Vertikale Aktualisierung</a>. </p> </li> 
      <li id="li_A40B513CE17043A4925CE3D4DE0B48A4"> <span class="codeph"> script_index  </span> <p>Der Suchroboter führt einen inkrementellen Index mit der Textdatei aus, die unter <span class="uicontrol"> <b>Index</b> </span> &gt; <span class="uicontrol"> <b>Skriptgesteuerter Index</b> </span> &gt; <span class="uicontrol"> <b>Konfiguration</b></span> angegeben ist. </p> </li> 
      <li id="li_A0BC7F1373B14393997BAB7690FD3EF7"> <span class="codeph"> full_staged_index  </span> <p>Der Suchroboter führt einen vollständigen Stufenindex Ihrer Website aus. </p> </li> 
      <li id="li_47753E358457443A95B384A278FACA83"> <span class="codeph"> incremental_staged_index  </span> <p>Der Suchroboter führt einen inkrementellen Index mit der Konfiguration aus, die unter <span class="uicontrol"> <b>Index</b> </span> &gt; <span class="uicontrol"> <b>Inkrementeller Index</b> </span> &gt; <span class="uicontrol"> <b>Konfiguration</b></span> eingestellt ist. </p> </li> 
      <li id="li_C8B5F8F1208E438ABEFDF9129A6B14A3"> <span class="codeph"> vertical_staged_index  </span> <p>Der Suchroboter führt eine Aktualisierung mit vertikaler Stage aus, indem er die Konfiguration verwendet, die unter <span class="uicontrol"> <b> </span> &gt; <span class="uicontrol"> <b>Vertikale Aktualisierung</b> </span> &gt; <span class="uicontrol"> <b>Konfiguration</b></span> eingestellt ist.</b> </span></p> </li> 
     </ul> </p> <p>Hinweis:  Um vertikale Updates zu verwenden, müssen Sie diese eventuell in Ihrem Konto von Ihrem Kundenbetreuer oder vom Adobe Support aktivieren lassen. </p> <p>Siehe <a href="../c-about-index-menu/c-about-vertical-updates.md#concept_E65A70C9C2E04804BF24FBE1B3CAD899" format="dita" scope="local"> Vertikale Aktualisierung </a>. </p> <p>Sie können <span class="codeph"> _saved </span> an einen der oben stehenden <span class="codeph"> sp_operation </span>-Werte anhängen, damit der Suchroboter versucht, gespeicherte Inhalte zu verwenden. Sie können beispielsweise Folgendes angeben: </p> <p> <code class="syntax html"> sp_operation=full_index_saved </code> </p> <p>oder </p> <p> <code class="syntax html"> sp_operation=full_staged_index_saved </code> </p> <p>Oder Sie können <span class="codeph"> _status </span> an einen der oben stehenden <span class="codeph"> sp_operation </span>-Werte anhängen, um einen Statusbericht für den aktuellen oder letzten Vorgang anzufordern. Sie können beispielsweise Folgendes angeben: </p> <p> <code class="syntax html"> sp_operation=full_index_status </code> </p> <p>oder </p> <p> <code class="syntax html"> sp_operation=full_staged_index_status </code> </p> <p>und die Ergebnisse werden als JSON-Objekt zurückgegeben. Fügen Sie <span class="codeph"> sp_lines=N </span> ein, um N Zeilen der zugehörigen Protokolldatei einzuschließen. Wenn N negativ ist, werden die letzten N Zeilen eingeschlossen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> sp_operation= pushlive  </span> </p> </td> 
   <td colname="col2"> <p> Ermöglicht die remote Live-Übertragung eines gestaffelten Indexes. </p> <p>Jeder Versuch, <span class="codeph"> _saved </span> an den Push-Live-Vorgang anzuhängen, wird ignoriert. </p> <p>Wenn Sie den Vorgang <span class="codeph"> push live </span> ausführen, wird eine Zeichenfolge der Antwort "OK", "Priorität"oder "Fehler"an den Server zurückgegeben. Sie geben diese Antwortzeichenfolgen auf der Seite <span class="wintitle"> Remote Control </span> an. </p> <p>Siehe <a href="../c-about-index-menu/c-about-remote-control-for-indexing.md#task_57C296258404448DA7A5ADC9B7232391" format="dita" scope="local"> Konfigurieren der Remote-Steuerung für die Indizierung</a>. </p> <p>Wenn Sie einen Live-Push durchführen, ohne einen gestaffelten Index zu haben, passiert nichts und die OK-Antwortzeichenfolge wird zurückgegeben. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> <span class="codeph"> sp_password= xxxxxx  </span> </p> </td> 
   <td colname="col2"> <p>Das Kennwort der Fernbedienung. </p> </td> 
  </tr> 
 </tbody> 
</table>

Die Suche gibt Daten in Form einer richtigen HTTP-Antwort zurück. Die vollständige Antwort besteht aus einem HTTP-Status, HTTP-Antwort-Kopfzeilen, einer leeren Zeile und der Antwort-Zeichenfolge.

Angenommen, Sie führen die folgende Remote-Steuerungsanforderung aus:

```
https://center.atomz.com/search/cgiindex.tk?sp_a=sp99999999&sp_password=my-password&sp_operation=full_index
```

Die Antwort des Servers lautet wie folgt:

```
Status: 200 OK 
Content-type: text/plain 
OK
```

Angenommen, Sie führen die folgende Statusanforderung für die Remote-Steuerung aus:

```
https://center.atomz.com/search/cgiindex.tk?sp_a=sp99999999&sp_password=my-password&sp_operation=full_index_status
```

Die Antwort des Servers könnte wie folgt aussehen:

```
Status: 200 OK 
Content-type: application/json; charset=utf-8 
{ 
    "current_time": "2017-08-27T10:58:58-0700", 
    "start_time": "2017-07-25T16:40:07-0800", 
    "end_time": "2017-07-25T16:40:20-0800", 
    "elapsed_seconds": 13, 
    "elapsed_seconds_fmt": "13s", 
    "state": "finished", 
    "docs_indexed": 3, 
    "depth": 0, 
    "errors": 0, 
    "status": 1, 
    "message": "ok" 
}
```

Um die ersten zehn Zeilen der Protokollliste abzurufen, die mit diesem Indexvorgang verknüpft sind, wird die folgende Abfrage verwendet:

```
https://center.atomz.com/search/cgiindex.tk?sp_a=sp99999999&sp_password=my-password&sp_operation=full_index_status&sp_lines=10
```

Die Antwort des Servers:

```
Status: 200 OK 
Content-type: application/json; charset=utf-8 
{ 
    "current_time": "2017-08-27T10:59:30-0700", 
    "start_time": "2017-07-25T16:40:07-0800", 
    "end_time": "2017-07-25T16:40:20-0800", 
    "elapsed_seconds": 13, 
    "elapsed_seconds_fmt": "13s", 
    "state": "finished", 
    "docs_indexed": 3, 
    "depth": 0, 
    "errors": 0, 
    "offset": 672, 
    "lines": [ 
        "07/25 16:40:07 PST   ======== Starting manual crawl of account sp99999999. ========", 
        "07/25 16:40:08 PST   Loading existing data", 
        "07/25 16:40:08 PST   Downloading entrypoint https://www.atomz.com/", 
        "07/25 16:40:08 PST   Robots.txt exclude mask: https://www.atomz.com/snap", 
        "07/25 16:40:08 PST   Exclude mask: regexp ^https://www.atomz.com/$", 
        "07/25 16:40:08 PST   Include mask: https://www.atomz.com/", 
        "07/25 16:40:08 PST   Downloading https://www.atomz.com/style.css", 
        "07/25 16:40:09 PST   Ignoring https://www.atomz.com/style.css, document type 'text/css'.", 
        "07/25 16:40:09 PST   Downloading https://www.atomz.com/privacy.html", 
        "07/25 16:40:09 PST   Downloading https://www.atomz.com/terms.html" 
    ], 
    "status": 1, 
    "message": "ok" 
}
```

Beachten Sie den Wert `offset`. Dieser Wert gibt die Datei-Offset-Position in der Protokolldatei an, an der das Lesen abgebrochen wurde. Um die Zeilen *next* zehn in der Datei zu lesen, würden Sie in diesem Beispiel `&sp_offset=672` in die an den Server gesendete Anforderung einschließen.

Mithilfe von `sp_offset` können Sie effektiv durch eine Protokolldatei blättern.

Um die Zeile *last* mit zehn Zeilen des Protokolls zusammen mit dem Status abzurufen, geben Sie die Zahl als negative Zahl an. Geben Sie beispielsweise `sp_lines=` wie folgt mit dem Wert `-10` an:

```
https://center.atomz.com/search/cgiindex.tk?sp_a=sp99999999&sp_password=my-password&sp_operation=full_index_status&sp_lines=-10
```

Die Antwort des Servers:

```
Status: 200 OK 
Content-type: application/json; charset=utf-8 
{ 
    "current_time": "2017-08-27T11:01:14-0700", 
    "start_time": "2017-07-25T16:40:07-0800", 
    "end_time": "2017-07-25T16:40:20-0800", 
    "elapsed_seconds": 13, 
    "elapsed_seconds_fmt": "13s", 
    "state": "finished", 
    "docs_indexed": 3, 
    "depth": 0, 
    "errors": 0, 
    "lines": [ 
        "07/25 16:40:20 PST   End Time: 07/25/2017 16:40:20 PST", 
        "07/25 16:40:20 PST   Elapsed Time: 13 seconds", 
        "07/25 16:40:20 PST   Pages Crawled: 3 pages", 
        "07/25 16:40:20 PST   Pages Indexed: 3 pages", 
        "07/25 16:40:20 PST   Words/Bytes Indexed: 2373 words/ 20618 bytes", 
        "07/25 16:40:20 PST   Errors: 0", 
        "07/25 16:40:20 PST   *** Index Summary ***", 
        "07/25 16:40:20 PST   Total Pages: 3", 
        "07/25 16:40:20 PST   --------------------------------------------------------------------", 
        "07/25 16:40:20 PST   ======== Finish manual crawl of account sp99999999: Done. ========" 
    ], 
    "status": 1, 
    "message": "ok" 
}
```

Beachten Sie, dass hier kein `offset`-Wert zurückgegeben wird, da dieser Vorgang am Ende der Datei abgeschlossen ist und keine Zeilen mehr gelesen werden können.

## Konfigurieren der Remote-Steuerung für die Indexierung von {#task_57C296258404448DA7A5ADC9B7232391}

Bei jeder Änderung Ihrer Website können Sie mithilfe von Remote Control ein Skript oder Programm von Ihrem Server ausführen und vom Suchroboter einen Index ausführen lassen.

**So konfigurieren Sie die Remote-Steuerung für die Indizierung**

1. Klicken Sie im Produktmenü auf **[!UICONTROL Index]** > **[!UICONTROL Remote Control]**.
1. Stellen Sie auf der Seite [!DNL Remote Control] jede Konfigurationsfeldoption ein, damit eine Indexanfrage von Ihrem Server automatisch gesendet werden kann, um Ihre Website zu indizieren.

   <table> 
    <thead> 
    <tr> 
    <th colname="col1" class="entry"> <p>Option </p> </th> 
    <th colname="col2" class="entry"> <p>Beschreibung </p> </th> 
    </tr> 
    </thead>
    <tbody> 
    <tr> 
    <td colname="col1"> <p>Remote Control-Kennwort </p> </td> 
    <td colname="col2"> <p>Geben Sie das Kennwort für die Remote-Steuerung an. </p> <p> Bei Kennwörtern muss die Groß-/Kleinschreibung beachtet werden, sie müssen mindestens sechs Zeichen lang sein und mindestens einen Buchstaben enthalten. Es wird empfohlen, mindestens eine Zahl einzufügen. </p> <p>Verwenden Sie nicht Ihr Anmeldekennwort für die Site-Suche/Merchandising-Anmeldung. </p> <p>Ihr Kennwort wird bei jeder Remote Control-Anforderung verwendet. </p> </td> 
    </tr> 
    <tr> 
    <td colname="col1"> <p>OK-Antwortzeichenfolge </p> </td> 
    <td colname="col2"> <p>Ermöglicht die Angabe einer OK-Antwort-Textzeichenfolge, wenn der angeforderte Indexvorgang erfolgreich beginnt. In solchen Fällen gibt der Suchroboter Ihre OK-Antwort-Zeichenfolge an den Server zurück. </p> </td> 
    </tr> 
    <tr> 
    <td colname="col1"> <p>Priority Response String </p> </td> 
    <td colname="col2"> <p>Wenn während der Remote-Anforderung ein weiterer Indexierungsvorgang ausgeführt wird, kann der Suchroboter den angeforderten Index nicht ausführen. In solchen Fällen wird die Zeichenfolge für die Antwort "Priorität"an den Server zurückgegeben. </p> </td> 
    </tr> 
    <tr> 
    <td colname="col1"> <p>Fehler-Antwortzeichenfolge </p> </td> 
    <td colname="col2"> <p>Ermöglicht die Eingabe einer Fehlerantwort-Textzeichenfolge Wenn Ihr Kennwort falsch ist oder ein anderer Fehler auftritt. In solchen Fällen gibt der Suchroboter Ihre Fehlerantwort-Zeichenfolge zurück an den Server. </p> </td> 
    </tr> 
    </tbody> 
    </table>

1. Klicken **[!UICONTROL Save Changes]**.
