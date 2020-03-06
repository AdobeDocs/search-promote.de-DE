---
description: 'null '
seo-description: 'null '
seo-title: Search&amp;Promote 15.1.1 Versionshinweise (15.01.2015)
solution: Target
title: Search&amp;Promote 15.1.1 Versionshinweise (15.01.2015)
topic: Release Notes,Site search and merchandising
uuid: 070f9c46-426f-4ca1-80c7-8ca53d40a402
translation-type: tm+mt
source-git-commit: ef818327e1cdaad79ac47575a8dfba1de3dc5c2e

---


# Search&amp;Promote 15.1.1 Release Notes (01/15/2015){#search-promote-release-notes}

## Neue Funktion {#section_2A10EF6B40FC4F2CB2381FFA9FFA64BD}

* Bisher wurden in Regeln für die geführte Suche immer linguistische Funktionen wie Wortstämme, Synonyme usw. auf die Keywords angewendet. Nun können Sie diese Erweiterung deaktivieren, damit nur das Keyword wie eingegeben verwendet wird.

   Wenn Sie Auslöserbedingungen auf eine Geschäftsregel anwenden möchten, wählen Sie in der [!DNL Advanced Rule Builder]folgenden Liste **[!UICONTROL If any/all of the following conditions are met]** in der ersten Dropdown-Liste die Option **[!UICONTROL keyword]** und wählen Sie dann den neuen Operator **[!UICONTROL equal exact]** in der zweiten Dropdownliste aus.

   See [About Business Rules](../c-about-rules-menu/c-about-business-rules.md#concept_2A93D76216754D3D8412CDEA00BD26BD).

## Fixes and enhancements {#section_22D1AFC99F394D569898828A0D3C419D}

* [!DNL Visual Rule Builder] und [!DNL Advanced Rule Builder] verkürzt den Feldwert des MDI (Merchandising Document ID) nicht mehr.
* Die RBTA-bezogenen Indizierungsfehler wurden nun behoben.
* Beim Bearbeiten einer vorhandenen Geschäftsregel mit dem Status &quot;genehmigt&quot;wird jetzt der Status &quot;genehmigt&quot;widerrufen. You must use [!DNL Advanced Rule Builder] to recheck the option **[!UICONTROL Approved]**, and then save the rule as usual. If you do not reapprove an edited rule, the rule&#39;s status is automatically set to WIP (Work In Progress) on the [!DNL Business Rules] page.
* A new **[!UICONTROL Advanced Search]** option is now available on the [!DNL Business Rules] page for improved filtering of rules.
* Neue **[!UICONTROL contains word]** Bedingung zu Regelauslösern in [!DNL Query Cleaning], [!DNL Pre-Search Rules], [!DNL Post Search Rules]und [!DNL Business Rules], damit Sie Wortumbrüche einfach angeben können.
* Verbesserungen, die an Geschäftsregelhinweisen vorgenommen wurden, z. B. wenn Sie eine Regel anzeigen, können Sie jetzt den Notizverlauf für diese Regel abrufen. Notizen sind jetzt auch angemeldet **[!UICONTROL Reports]** > **[!UICONTROL Change Log]**.
* Queries with nonzero `sp_i` values are no longer run through the [!DNL Adobe Analytics] redirector.

   Siehe Zeile 15 in der Tabelle unter CGI-Parameter für die [Backend-Suche](../c-appendices/c-cgiparameters.md#reference_582E85C3886740C98FE88CA9DF7918E8).
