---
demo:
  title: IT-Demo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# IT-Demo

**Szenario:**  

Als IT-Infrastrukturmanager planen Sie, ein neues Netzwerksicherheitsprodukt in Ihrem Unternehmensnetz zu installieren.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demos

### Copilot Chat

Starten wir damit, Copilot zu bitten, einen Projektdurchführungsplan zu erstellen.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).

1. Stellen Sie sicher, dass der Webmodus ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **Hinweis:** Rollenbasierte Prompts helfen Copilot, die Verantwortlichkeiten und den Kontext des Benutzenden zu verstehen, was die Relevanz und Spezifität der Ausgabe verbessert.

1. Jetzt verfeinern wir den Projektplan, indem wir Copilot auffordern, dem Projektplan neue Abschnitte hinzuzufügen:

    Geben Sie den folgenden Prompt ein:

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. Schließlich lassen Sie Copilot den vorgeschlagenen Projektplan in ein Word-Dokument ausgeben:

    Geben Sie den folgenden Prompt ein:

    ```text
    Please export the project plan to a Word document.
    ```

1. Speichern Sie das generierte Word-Dokument als **Project_Implementation_Plan.docx**. Kopieren Sie die freigegebene URL aus dem Dokument (aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus, falls Sie dazu aufgefordert werden).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

Wir werden Copilot nun bitten, diese Strategien zu erläutern und Vorschläge zu ihrer Umsetzung zu erarbeiten.

1. Öffnen Sie Word (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).

1. Geben Sie in das Prompt-Feld **Beschreiben Sie, was Sie schreiben möchten** Folgendes ein:

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **HINWEIS:** Klammern geben an, dass auf ein Dokument verwiesen wird.
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = Verwenden Sie den Link, den Sie in der vorherigen Demo kopiert haben.
    > Wenn Sie auf ein Dokument verweisen, können Sie den Link direkt einfügen oder auf den Dateinamen verweisen, wenn es in Ihrem OneDrive verfügbar ist.

1. Wählen Sie **Beibehalten** oder, wenn es die Zeit erlaubt, demonstrieren Sie, wie Sie das Dokument mit Copilot optimieren können.

1. Sobald Sie das Dokument fertiggestellt haben, speichern Sie es als **Contoso_Project_Plan.docx** und kopieren Sie die freigegebene URL (aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus, wenn Sie dazu aufgefordert werden).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in PowerPoint

Wir werden nun Copilot verwenden, um eine PowerPoint-Präsentation zu erstellen, die auf dem neuen Vorschlag zur Implementierung des Contoso CipherGuard-Produkts basiert.

1. Starten Sie Microsoft PowerPoint über Ihren Browser [PowerPoint.new](https://PowerPoint.new) oder verwenden Sie die Desktop-Anwendung.

1. Öffnen Sie eine neue leere Präsentation.

1. Wählen Sie im Bereich Copilot den Prompt „Präsentation aus Datei erstellen“.

1. Fügen Sie den gemeinsamen Link für das Dokument **Contoso_Project_Plan.docx** ein und wählen Sie **Senden**.

    Die vollständige Eingabeaufforderung sollte wie folgt aussehen:

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot beginnt mit der Erstellung von Folien auf der Grundlage des Projektplans und stellt eine Gliederung zusammen mit Funktionen wie Sprechernotizen, Abbildungen, Folienlayouts und einer Vertraulichkeitsbezeichnung bereit.

    > **HINWEIS:** Das Generieren von Folien kann je nach Komplexität und Anzahl von Folien bis zu zwei Minuten dauern.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
