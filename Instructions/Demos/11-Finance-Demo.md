---
demo:
  title: Finanzen Demo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Finanzen Demo

**Szenario:**  

Sie sind Finanzanalyst bei Contoso und verantwortlich für die Bewertung der Vertriebsleistung und Marktpositionierung in der EV-Ladeindustrie. Ihr Ziel ist es, Vertriebsdaten zu analysieren, Erkenntnisse zu gewinnen und eine Zusammenfassung für Ihr Team zu erstellen.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Copilot in Excel  

Verwenden Sie Copilot in Excel, um Vertriebsdaten zu analysieren, wichtige Trends zu erkennen und finanzielle Metriken zu berechnen.

1. Starten von Excel & Öffnen der Datei  

1. Öffnen Sie **EV_Charger_Sales_Analysis_v1.xlsx** in Excel (entweder in Ihrem Browser oder in der Desktopanwendung).  

1. Navigieren Sie zur Registerkarte **„Vertrieb nach Produkt“**.  

1. Verwenden Sie Copilot, um die Tabelle zu sortieren, indem Sie die folgende Eingabeaufforderung eingeben:  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - Copilot sortiert die Tabelle und aktualisiert das DataSet.  
    - Wählen Sie nach dem Sortieren **„Anwenden“**.  

1. Eine Spalte 'Gesamt-Umsatzerlös' einfügen  

    Geben Sie im Copilot-Bereich die folgende Eingabeaufforderung ein:  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot erstellt die neue Spalte und wendet die Formel an.  
    - Wählen Sie **„Spalte einfügen“** aus.  

1. Generieren einer Zusammenfassungstabelle des Vertriebs für 2024  

    Geben Sie im Copilot-Bereich die folgende Eingabeaufforderung ein:  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - Copilot generiert eine Zusammenfassungstabelle.  
    - Wählen Sie **„Zu einem neuen Datenblatt hinzufügen“**, um die Tabelle separat zu speichern.  
    - Stellen Sie sicher, dass die Tabelle **nur 2024 Daten** enthält.  
    - Navigieren Sie zurück zur Registerkarte **„Umsatz nach Produkt“** oder wählen Sie **„Zurück zu Daten“** unter der letzten Antwort von Copilot aus.  

1. Identifizieren Sie das meistverkaufte Produkt  

    Geben Sie im Copilot-Bereich die folgende Eingabeaufforderung ein:  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - Copilot analysiert das DataSet und liefert das meistverkaufte Produkt.
    - Navigieren Sie zurück zur Registerkarte **„Umsatz nach Produkt“** oder wählen Sie **„Zurück zu Daten“** unter der letzten Antwort von Copilot aus.  

1. Sortieren von Kunden nach Umsatz

    - Navigieren Sie zum Blatt **„Kunden“** in Excel.

    Geben Sie im Copilot-Bereich die folgende Eingabeaufforderung ein:  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - Copilot sortiert die Kunden nach **Jahresumsatz**.  
    - Wählen Sie nach dem Sortieren **„Anwenden“**.  

1. Berechnung des durchschnittlichen Umsatzes pro Kunde

    Geben Sie den folgenden Prompt ein:  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot errechnet den Durchschnitt und addiert das Ergebnis.  
    - Wählen Sie **„Zeile einfügen“** aus, um den durchschnittlichen Umsatzwert zu speichern.  

1. Suchen der Branche mit dem höchsten Stromverbrauch  

    Geben Sie im Copilot-Bereich die folgende Eingabeaufforderung ein:  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot verarbeitet die Daten und gibt die Branche mit dem höchsten Stromverbrauch an.

1. Speichern Sie das Dokument. Kopieren Sie die freigegebene URL aus dem Dokument (aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus, falls Sie dazu aufgefordert werden).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Nutzen Sie Copilot Chat, um die finanzielle Leistung mit Branchen-Benchmarks und Wettbewerbern zu vergleichen.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).

1. Stellen Sie sicher, dass der Webmodus ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. Bitten Sie Copilot Chat nun, dies mit der Konkurrenz zu vergleichen:

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. Bitten Sie schließlich Copilot, den bisherigen Chatverlauf in ein Word-Dokument zu exportieren:

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. Wählen Sie die verknüpfte Datei aus, die heruntergeladen werden soll, und öffnen Sie dann das Dokument.

1. Wählen Sie **Bearbeitung aktivieren** aus.

1. Die Datei sollte den Titel „**Charging_industry_Financial_Summary.docx**" haben. Kopieren Sie die freigegebene URL aus dem Dokument (aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus, falls Sie dazu aufgefordert werden).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

Verwenden Sie Copilot in Word, um finanzielle Einblicke in eine E-Mail für unser Team zusammenzufassen.

1. Öffnen Sie ein neues Word-Dokument (entweder in Ihrem Browser oder in der Desktopanwendung).

1. Geben Sie in das Prompt-Feld **„Beschreiben Sie, was Sie schreiben möchten“** Folgendes ein:

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **Hinweis:** Fügen Sie die in der vorherigen Aufgabe erstellte Datei Charging_industry_Financial_Summary.docx bei oder fügen Sie den freigegebenen Link direkt in das Prompt ein, um sicherzustellen, dass Copilot Zugriff auf den relevanten Inhalt hat.

1. Überprüfen Sie die Ausgabe von Copilot. Bevor Sie **Beibehalten** wählen, verfeinern Sie die Antwort, indem Sie Copilot fragen:

    ```text
    Shorten this email draft
    ```

1. Weitere optionale Verfeinerungen:

    - Bitten Sie Copilot, Abschnitte umzuformulieren, um einen professionelleren Ton zu erreichen.
    - Erweitern Sie mit zusätzlichen Abschnitten.
    - Machen Sie es weniger formell

1. Nachdem Sie fertig sind, können Sie **Beibehalten** wählen.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
