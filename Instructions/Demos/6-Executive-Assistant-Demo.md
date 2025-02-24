---
demo:
  title: Executive Assistant Demo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Executive Assistant Demo

**Szenario:**

Sie wurden damit beauftragt, das Protokoll der letzten Ergebnis-Calls für Ihre Führungskraft zusammenzufassen. Diese Aufgabe umfasst die Gewinnung der wichtigsten Erkenntnisse, die Erstellung einer Zusammenfassung und die Vorbereitung auf ein Folgetreffen.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demoschritte

### Copilot in Word

Wir beginnen mit der Durchsicht des Transkripts der letzten Telefonkonferenz zum Quartalsbericht und fassen die wichtigsten Punkte für Ihre Führungskraft zusammen.

1. Wählen Sie die Datei **Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx** aus und öffnen Sie sie in Word (entweder in Ihrem Browser oder in Ihrer Desktopanwendung).

    > **Hinweis:** Vielleicht möchten Sie schnell durch das Dokument scrollen, um zu zeigen, wie umfangreich es ist und dass es keine einfache Aufgabe ist, es zusammenzufassen.

1. Wählen Sie das Symbol Copilot im Menüband:

    ![Symbol Copilot in Word](../Demos/Media/Copilot-in-word-ribbon.png)

1. Der Copilot-Bereich sollte sich öffnen. Geben Sie die folgende Eingabeaufforderung an der Stelle ein, an der **Fragen zu diesem Dokument** steht:

    ```text
    Summarize the key points from the Microsoft FY24 Second Quarter Earnings Conference Call.
    ```

1. Stellen Sie sich vor, Ihre Führungskraft möchte wissen, was Satya Nadella während des Calls konkret besprochen hat. Verwenden Sie den folgenden Prompt:

    ```text
    Provide a brief summary of Satya Nadella's remarks during the earnings call.
    ```

   - Zeigen Sie, wie Copilot für jeden Aufzählungspunkt Verweise enthält, die eine schnelle Navigation zu bestimmten Abschnitten ermöglichen.  
   - Klicken Sie auf einen Verweis, um zu demonstrieren, wie Copilot Sie sofort zu den relevanten Inhalten des Dokuments führt.

1. Um einen detaillierten Bericht zu erstellen, fragen Sie Copilot:

    ```text
    Analyze the Microsoft FY24 Second Quarter Earnings Conference Call document to provide a comprehensive report that includes:
    - A summary of the key points from each speaker
    - Identification of the top three growth areas and their contributing factors.
    - A detailed breakdown of the financial performance, including revenue, operating income, and earnings per share.
    - Trends in AI adoption and its influence on Microsoft's business strategy.
    - A comparison of this quarter's performance with the same quarter last year, highlighting significant changes.
    - Key strategic initiatives and future outlook as discussed in the call.
    ```

    > **Tipp:** Erwähnen Sie, dass es sich um eine komplexe Eingabeaufforderung handelt und Copilot einige Zeit brauchen kann, um die Antwort zu erstellen.

1. Sobald Copilot die Analyse abgeschlossen hat, wählen Sie das Symbol **Kopieren**, um die Ergebnisse für den nächsten Schritt zu speichern.

    ![Ergebnisse kopieren.](../Demos/Media/Copilot-in-word-copy-results.png)


### Copilot Chat

Der von Word bereitgestellte Bericht ist ein guter Ausgangspunkt, aber jetzt möchten wir Copilot Chat nutzen, um eine Zusammenfassung für die Fürungskraft zu erstellen.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).

1. Stellen Sie sicher, dass **Webmodus** ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Fügen Sie die Antwort von Copilot in Word in Copilot Chat mit der folgenden Eingabeaufforderung ein:

    ```text
    Based on the following information, provide an executive summary on the following information:

    [paste the Word output here]
    ```

    > **Hinweis:** Bereinigen Sie den kopierten Inhalt um jeglichen überflüssigen Text, um die Übersichtlichkeit zu gewährleisten.

1. Verfeinern Sie die Zusammenfassung in ein prägnantes Format:

    ```text
    Summarize this executive summary into a more concise format by focusing on the most critical insights and metrics for each speaker. Use a structured format with headings and bullet points to improve readability. Export to a Word document.
    ```

   - Wenn Copilot das Dokument nicht exportiert, formulieren Sie die Anforderung neu: „Speichere Sie diese Zusammenfassung als Word-Dokument“.

1. Wenn die Zusammenfassung für die Führungskraft fertig ist, fragen Sie Copilot:

    ```text
    Based on the summarized executive summary, generate 5-7 concise and impactful talking points my manager can use in their next leadership call. Focus on key achievements, growth areas, and strategic priorities.
    ```

### Copilot in Outlook:

In dieser Demo verwenden wir Copilot in Outlook, um eine Besprechung mit der Führungskraft einzurichten, um sie über alles zu informieren, was während der Telefonkonferenz zum Ergebnis des zweiten Quartals passiert ist.

1. Öffnen Sie einen Browser, und navigieren Sie zu [outlook.office.com](https://outlook.office.com.com/).

1. Wählen Sie im Outlook-Menüband das Copilot-Symbol, um den Copilot-Bereich zu öffnen.

1. Verwenden Sie die folgende Eingabeaufforderung, um eine Synchronisierung zu planen:

    ```text
    I need to schedule a 30-minute meeting with [/Pick a colleague] tomorrow afternoon to discuss the Second Quarter Earnings Conference Call. Can you suggest a time that works? If they are unavailable, provide an alternative.
    ```

1. Der Kopilot sollte eine Uhrzeit und ein Datum für die Besprechung vorschlagen. Die Eingabeaufforderung zeigt ein Kalenderelement an, das gesendet oder bearbeitet werden kann. Wählen Sie **Bearbeiten** aus.

1. Wechseln Sie zum Terminplanungs-Assistenten, um zu zeigen, dass die von Copilot vorgeschlagene Zeit für die Projektmanagerin bzw. den Projektmanager passt. Sie sollten beide Zeit haben.

1. Wechseln Sie zurück zur Registerkarte Ereignis und wählen Sie dann **Entwurf mit Copilot** im Ereignistext.

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    I’m meeting with my boss to discuss key updates and strategic initiatives they missed from the Second Quarter Earnings Conference Call. Create an agenda to discuss financial performance, AI and technology integration, strategic acquisitions, productivity updates, and future outlook.
    ```

1. Bevor Sie **Beibehalten** wählen, können Sie Copilot bitten, die Agenda zu verlängern, zu verkürzen oder den Ton zu ändern.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
