---
demo:
  title: Juristische Demo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Juristische Demo

**Szenario:**  

Sie sind Rechtsberaterin bzw. Rechtsberater bei Contoso und sind dafür verantwortlich zu prüfen, ob die KI-Software des Unternehmens zur Überprüfung von Lebensläufen mit dem EU-KI-Gesetz übereinstimmt. Ihr Ziel ist es, rechtliche Risiken zu recherchieren, eine Zusammenfassung zu verfassen und Empfehlungen an die Geschäftsleitung zu übermitteln.

## Demoeinrichtung

Für diese Demo sind keine Musterdokumente erforderlich.

## Demos

### Copilot Chat

Zunächst werden die EU-Verordnung über künstliche Intelligenz und ihre potenzielle Auswirkungen auf das KI-Einstellungstool von Contoso beleuchtet.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365Copilot.com](https://m365Copilot.com/).

1. Vergewissern Sie sich, dass **Web-Modus** ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Überprüfen Sie die Antwort von Copilot und beachten Sie die relevanten rechtlichen Risiken und Konformitätsanforderungen.

1. Nun werden wir Copilot eine Reihe von Folgefragen stellen, um weitere Informationen zu sammeln:

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. Weisen Sie Copilot nun an, alle bisherigen Informationen zusammenzufassen:

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. Wählen Sie den Hyperlink, den Copilot für das neue Word-Dokument bereitstellt, um es zu öffnen.

1. Nach dem Öffnen wählen Sie **Bearbeitung aktivieren** und schalten dann „AutoSave“ ein. Wählen Sie Ihr OneDrive-Konto aus, wenn Sie dazu aufgefordert werden.

1. Kopieren Sie die freigegebene URL zur Verwendung im nächsten Schritt. (Aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus, wenn Sie dazu aufgefordert werden).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

Jetzt entwerfen wir eine Zusammenfassung der Geschäftsleitung, in der rechtliche Risiken und Empfehlungen für die Führung von Contoso erläutert werden.

1. Öffnen Sie eine neue Instanz von Word, entweder in Ihrem Browser oder in der Desktopanwendung.

1. Geben Sie in das Prompt-Feld **„Beschreiben Sie, was Sie schreiben möchten“** Folgendes ein:

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
    ```

    > **Hinweis:** Hängen Sie das Dokument an oder fügen Sie den freigegebenen Link direkt in das Prompt ein, um sicherzustellen, dass Copilot den entsprechenden Inhalt verknüpfen kann.

1. Überprüfen Sie die Ausgabe von Copilot. Bevor Sie **Beibehalten** wählen, verfeinern Sie die Antwort, indem Sie Copilot fragen:

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. Weitere optionale Optimierungen:

    - Weisen Sie Copilot an, Abschnitte für einen professionelleren Ton umzuformulieren.
    - Fordern Sie eine kürzere, präzisere Version an, wenn die Zusammenfassung zu lang ist.
    - Erweitern Sie mit zusätzlichen Abschnitten.

1. Nach der Überprüfung und Fertigstellung des Dokuments **Kopieren Sie die erstellte Zusammenfassung** in Ihre Zwischenablage, um sie in der nächsten Demo zu verwenden.

### Copilot in Outlook

Abschließend werden wir eine E-Mail an die Contoso-Führung verfassen, in der wir unsere Ergebnisse und die nächsten Schritte zusammenfassen.

1. Öffnen Sie Outlook (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).

1. Wählen Sie **Neue E-Mail**.

1. Wählen Sie im Menüband **Copilot** aus. Wählen Sie aus dem Dropdown-Menü **Entwurf mit Copilot**.

1. In der **„Was soll in dieser E-Mail stehen?“** Prompt-Fenster, tippen Sie:

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **Hinweis:** Fügen Sie den Inhalt der Zusammenfassung ein, den Sie aus der vorherigen Demo kopiert haben.

1. Sobald der Entwurf erstellt ist, können Sie mithilfe der Funktion **Anpassen** den Ton, die Länge oder die Stufe der Förmlichkeit ändern.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
