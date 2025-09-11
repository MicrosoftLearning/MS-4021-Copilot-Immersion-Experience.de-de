---
demo:
  title: HR-Demo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# HR-Demo

**Szenario:**  

Rationalisierung des Einstellungsprozesses für ein Team von UX-Designern durch die Erstellung einer maßgeschneiderten Stellenbeschreibung, die Vorauswahl von Kandidaten auf der Grundlage ihrer Lebensläufe und die Ausarbeitung einer Einstellungsstrategie zur Ausrichtung des Teams

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demos

### Copilot in Word

Starten wir damit, Copilot in Word zu bitten, eine Stellenbeschreibung zu erstellen.

1. Öffnen Sie Word (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).

1. Geben Sie in das Prompt-Feld **„Beschreiben Sie, was Sie schreiben möchten“** Folgendes ein:

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **HINWEIS:** Fügen Sie die Datei Design_Team_Responsibilities.docx an, oder fügen Sie den freigegebenen Link direkt in das Prompt ein, um sicherzustellen, dass Copilot Zugriff auf die relevanten Inhalte hat.

1. Nach der Überprüfung und Fertigstellung der Stellenbeschreibung speichern Sie das Dokument als **GDI_Job_Description.docx** und kopieren die freigegebene URL zur Verwendung im nächsten Schritt. (Aktivieren Sie AutoSave und wählen Sie Ihr OneDrive-Konto aus, wenn Sie dazu aufgefordert werden).

    ![Link teilen.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Anschließend vergleichen wir mithilfe von Copilot Chat die empfangenen Lebensläufe mit der Stellenbeschreibung und ermitteln die besten Kandidaten.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).

1. Stellen Sie sicher, dass der Arbeitsmodus ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/work-mode.png)

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **Hinweis:** Fügen Sie die Lebensläufe an oder laden Sie sie in das Prompt-Fenster hoch. Alternativ dazu können Sie die einzelnen Dateien mithilfe der freigegebenen Links oder Dateinamen in Ihrem OneDrive verknüpfen.

1. Optional können Sie Copilot Chat auffordern, seine Antwort in ein Word-Dokument zu exportieren, um diese Funktion hervorzuheben.

### Copilot in Outlook

Verwenden Sie schließlich Copilot in Outlook, um eine E-Mail an das Einstellungsteam zu verfassen, in der die besten Kandidaten genannt werden.

1. Öffnen Sie Outlook (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).

1. Wählen Sie **Neue E-Mail**.

1. Wählen Sie im Menüband **Copilot** aus. Wählen Sie aus dem Dropdown-Menü **Entwurf mit Copilot**.

1. In der **„Was soll in dieser E-Mail stehen?“** Prompt-Fenster, geben Sie Folgendes ein:

    ```text
    Please draft an email to the hiring team to share that Nestor Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
