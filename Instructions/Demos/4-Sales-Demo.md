---
demo:
  title: Demo für den Vertrieb
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demo für den Vertrieb

**Szenario:**  

Sie arbeiten im Vertrieb eines Unternehmens für EV-Ladegeräte und entwickeln einen strategischen Plan für das kommende Jahr.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [Charger_sales_report_2022-2024.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Charger_sales_report_2022-2024.xlsx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demos

### Copilot Chat

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).

1. Stellen Sie sicher, dass Webmodus ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Beginnen wir damit, Copilot zu bitten, eine Schlüsselmetrik zu untersuchen. Geben Sie in das Eingabeaufforderungs-Feld **Copilot Chat** ein:

    ```text
    What is the ratio of EV cars to EV chargers by region in the US for the past 3 years? Please show it in a table organized by region.
    ```

    ![Screenshot, der die Eingabeaufforderung Copilot Chat EV-Ladegerät zeigt.](../Demos/Media/copilot-chat-ev-charger-prompt.png)

1. Vergleichen wir nun die nationalen Trends mit der Vertriebsleistung Ihres Unternehmens. Sie laden das bereitgestellte DataSet hoch und bitten Copilot, die Daten zu visualisieren:

    Geben Sie im Eingabeaufforderungsfeld Folgendes ein:

    ```text
    I need to know the quarterly trends for each of our sales regions. Create a quarterly revenue line graph for the past 2 years based on:
    ```

    > **HINWEIS:** Übermitteln Sie die Aufforderung noch nicht. Wechseln Sie zum nächsten Schritt, um die Datei hochzuladen.

1. Wählen Sie **Inhalt hinzufügen** und laden Sie [**Charger_sales_report_2022-2024.xlsx**](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Resourcefiles/Charger_sales_report_2022-2024.xlsx) hoch. Dann senden Sie den Prompt.

    ![Fügen Sie den Copilot-Chat hinzu.](../Demos/Media/add-content-copilot-chat.png)

1. Gehen wir noch einen Schritt weiter und fragen Copilot nach Empfehlungen, die in ein Word-Dokument exportiert werden:

    Geben Sie im Eingabeaufforderungsfeld Folgendes ein:

    ```text
    Based on the trend, suggest two ways I can increase EV charger sales in the Mountain and Midwest regions. Export the recommendations to a Word Document.
    ```

1. Wählen Sie den Hyperlink, den Copilot für das neue Word-Dokument bereitstellt, um es zu öffnen.

1. Nach dem Öffnen wählen Sie **Bearbeitung aktivieren** und schalten dann „AutoSave“ ein. Wählen Sie Ihr OneDrive-Konto aus, wenn Sie dazu aufgefordert werden.

### Copilot in Word

Wir werden Copilot nun bitten, diese Strategien zu erläutern und Vorschläge zu ihrer Umsetzung zu erarbeiten.

1. Das generierte Word-Dokument aus der vorherigen Demo sollte bereits geöffnet sein, falls nicht, öffnen Sie es jetzt (entweder in Ihrem Browser oder in Ihrer Desktopanwendung).

1. Wählen Sie eine beliebige Stelle im Text des Dokuments aus und wählen Sie das Symbol Copilot.

    Geben Sie die folgende Eingabeaufforderung ein:

    ```text
    Draft a detailed proposal on how we could implement each of the strategies outlined in this document. Ensure the plan is actionable and includes resource requirements, timelines, and key stakeholders.
    ```

1. Wählen Sie **Beibehalten** oder, wenn es die Zeit erlaubt, demonstrieren Sie, wie Sie das Dokument mit Copilot optimieren können.

1. Wenn Sie fertig sind, speichern Sie das Dokument als **EV Sales Proposal.docx** und kopieren Sie die gemeinsame URL, die im nächsten Schritt verwendet werden soll (aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

    > **Tipp für die Kursleitung:** Verwenden Sie diesen Schritt, um zu veranschaulichen, wie Copilot auf vorherigen Ausgaben aufbaut und Ideen in einen zusammenhängenden Vorschlag verfeinern.

### Copilot in PowerPoint

1. Starten Sie Microsoft PowerPoint über Ihren Browser [PowerPoint.new](https://PowerPoint.new) oder verwenden Sie die Desktop-Anwendung.

1. Öffnen Sie eine neue leere Präsentation.

1. Wählen Sie im Bereich Copilot den Prompt „Präsentation aus Datei erstellen“.

1. Fügen Sie den Link **EV Sales Proposal.docx** nach „Eine Präsentation erstellen von“ ein und wählen Sie **Senden**.

    Die vollständige Eingabeaufforderung sollte wie folgt aussehen:

    ```text
    Create a presentation from [Link to EV Sales Proposal.docx].
    ```

1. Copilot beginnt mit der Erstellung von Folien auf der Grundlage des EV-Verkaufsvorschlags und bietet eine Gliederung sowie Funktionen wie Sprechernotizen, Bilder, Folienlayouts und die Vertraulichkeitsangabe „Allgemein“.

    > **HINWEIS:** Das Generieren von Folien kann je nach Komplexität und Anzahl von Folien bis zu zwei Minuten dauern.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
