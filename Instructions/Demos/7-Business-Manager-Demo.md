---
demo:
  title: Demo für die geschäftsleitende Person
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demo für die geschäftsleitende Person

**Szenario:**

Analysieren Sie die Vertriebsleistung und das Kundenfeedback, um ein Produktproblem anzugehen, und arbeiten Sie dann mit Ihrem Team zusammen, um Verbesserungen zu planen.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demoschritte

### Copilot in Excel

1. Starten Sie Excel (entweder in Ihrem Browser oder in der Desktop-Anwendung) und öffnen Sie die Datei **EV_Charger_Sales_Analysis_v1.xlsx**.

1. **Navigieren Sie zur Registerkarte „Vertrieb nach Produkt“** in der Excel-Datei.

1. Verwenden Sie Copilot, um Ihren monatlichen Umsatzerlös zu berechnen:  

   Finden Sie zunächst heraus, welche Kategorie Ihres Unternehmens die meisten Einnahmen erzielt. Dieses Blatt enthält Umsatzdaten aus drei Jahren mit Tausenden von Zeilen, die den Umsatz nach Produkt nach Monat anzeigen. Obwohl es sich um eine Routineaufgabe handelt, kann diese Datenmenge unübersichtlich sein. Sie können Copilot bitten, den monatlichen Umsatzerlös nach Produkt schnell zu berechnen.

   Verwenden Sie den folgenden Prompt:

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - Copilot weiß, wie dies funktioniert und welche Daten über Registerkarten hinweg referenziert werden sollen.
    - Copilot erstellt einen Plan für die Ausführung dieser Zahlen, führt diesen Plan aus, zeigt seine Arbeit an und fordert Sie auf, Fragen zu stellen oder die erreichte Lösung zu wiederholen.
    - Wählen Sie **+Spalte einfügen** und navigieren Sie dann zurück zur Registerkarte **Umsatz nach Produkt**.

1. Verwenden Sie Copilot, um den Umsatzerlös zu analysieren, indem Sie die folgende Eingabeaufforderung im Bereich „Copilot“ eingeben:

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot überprüft die Zahlen und erstellt ein Balkendiagramm, das Sie Ihrer Arbeitsmappe hinzufügen können.
    - Wählen Sie **+Zu einem neuen Blatt hinzufügen** und navigieren Sie dann zurück zur Registerkarte **Umsatz nach Produkt**.

1. Verwenden Sie jetzt Copilot, um Produkte mit geringem Umsatz hervorzuheben, indem Sie diese Eingabeaufforderung eingeben:

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot wendet bedingte Formatierung an und hilft Ihnen, Produkte zu identifizieren, die nicht Ihren Anforderungen entsprechen.

1. **Navigieren Sie zur Registerkarte „Rezensionen“**, um Kundenfeedback zu analysieren.

1. Bitten Sie Copilot, die wichtigsten Bedenken zusammenzufassen, indem Sie die folgende Eingabeaufforderung eingeben:

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot analysiert das Feedback und zeigt die drei wichtigsten Kundenbedenken auf. Es sieht so aus, als sei die Ladegeschwindigkeit ein neu auftretendes Problem.

1. Als Nächstes heben Sie Rezensionen hervor, die die Ladegeschwindigkeit erwähnen, indem Sie diese Eingabeaufforderung eingeben:

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot hebt alle relevanten Bewertungen im DataSet hervor.

### Copilot Chat

Nachdem wir nun die langsame Ladegeschwindigkeit als Hauptproblem identifiziert haben, können Sie den **Copilot Chat** nutzen, um das Problem weiter zu untersuchen und mögliche Lösungen zu finden.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).  

1. Vergewissern Sie sich, dass **Web-Modus** ausgewählt ist.  

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Um das Problem zu untersuchen, geben Sie die folgende Eingabeaufforderung ein:
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - Überprüfen Sie die Zusammenfassung von Copilot und fragen Sie bei Bedarf nach zusätzlichem Kontext oder aktuellen Trends.  

1. Optional können Sie die Ausgabe verfeinern:
   - Fragen Sie Copilot nach aktuellen Trends oder Technologien, die die Effizienz von EV-Ladegeräten betreffen:

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - Anfordern von Erkenntnissen von Wettbewerbern:

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. Bitten Sie den Kopiloten, fünf strategische Fragen an den Projektleiter für EV-Ladegeräte zu stellen:

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Copilot in Outlook:

In dieser Demo verwenden wir Copilot in Outlook, um ein Treffen mit dem Projektleiter für die Produktlinie der Ladegeräte für Elektrofahrzeuge zu vereinbaren und mögliche Lösungen zu besprechen.

1. Öffnen Sie einen Browser, und navigieren Sie zu [outlook.office.com](https://outlook.office.com.com/).

1. Wählen Sie im Outlook-Menüband das Copilot-Symbol, um den Copilot-Bereich zu öffnen.

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Der Kopilot sollte eine Uhrzeit und ein Datum für die Besprechung vorschlagen. Die Eingabeaufforderung zeigt ein Kalenderelement an, das gesendet oder bearbeitet werden kann, wählen Sie **Bearbeiten**.

1. Wechseln Sie zum Terminplanungs-Assistenten, um zu zeigen, dass die von Copilot vorgeschlagene Zeit für die Projektmanagerin bzw. den Projektmanager passt. Sie sollten beide Zeit haben.

1. Wechseln Sie zurück zur Registerkarte Ereignis und wählen Sie dann **Entwurf mit Copilot** im Ereignistext.

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. Bevor Sie **Beibehalten** wählen, können Sie den Copiloten bitten, den Text länger oder kürzer zu machen oder den Tonfall der Agenda zu ändern.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
