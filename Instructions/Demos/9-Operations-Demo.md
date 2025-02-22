---
demo:
  title: Bedienungs-Demo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Bedienungs-Demo

## Szenario

Sie sind Operations Manager bei Contoso und für die Beschaffung von Lieferanten und die Durchführung von Projekten zuständig. Ihr Ziel ist es, frühere RFPs zu überprüfen, wichtige Auswahlkriterien zu extrahieren und eine neue FFP für eine bevorstehende Initiative zu entwerfen.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demos

### Copilot in Word

Starten wir damit, Copilot in Word einige Fragen zu einem Dokument mit der Bezeichnung „Request for Proposal“ (RFP) zu stellen.

1. Öffnen Sie Word (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).
1
1. Öffnen Sie das folgende Dokument: [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

1. Wählen Sie das Copilot-Symbol im Menüband von Word aus, um den Chat-Bereich zu öffnen.

    ![Screenshot der Registerkarte „Arbeitsmodus".](../Demos/Media/copilot-ribbon-word.png)

1. Wählen Sie im Bereich „Chat“ den Prompt aus oder geben Sie ihn ein:

   ```text
   Summarize this document
   ```

1. Geben Sie dann den folgenden Prompt ein:

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. Bitten Sie Als Nächstes Copilot, eine RFP-Vorlage zu erstellen, indem Sie Folgendes eingeben:

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **HINWEIS:** Es ist nicht erforderlich, den generierten Inhalt zu kopieren, da wir in der folgenden Demo ein bereits erstelltes Vorlagendokument verwenden. Sie können jedoch zeigen, wie Sie die Antwort von Copilot kopieren oder in das Dokument einfügen, falls sie für Ihr Publikum relevant ist.

### Copilot Chat

Nachdem wir nun das RFP-Dokument zusammengefasst und eine RFP-Vorlage erstellt haben, können wir mithilfe von Copilot Chat die Projektanforderungen für eine neue Ausschreibung zusammenfassen.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).  

1. Vergewissern Sie sich, dass **Web-Modus** ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Geben Sie den folgenden Prompt ein:

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **HINWEIS:** Klammern geben an, dass auf ein Dokument verwiesen wird. Verwenden Sie den Link: [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

1. Als nächstes bitten Sie Copilot, die Auswahlkriterien für den Lieferanten zu extrahieren:

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. Bitten Sie Copilot dann, ein RFP basierend auf den Projektrichtlinien zu erstellen:

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **HINWEIS:** Klammern geben an, dass auf ein Dokument verwiesen wird.

1. **Kopieren Sie das generierte RFP** in Ihre Zwischenablage, um es in der nächsten Demo zu verwenden.

1. Optional können Sie Copilot bitten, das erstellte RFP in ein Word-Dokument zu exportieren.

### Copilot in Outlook:

Verwenden Sie schließlich Copilot in Outlook, um eine E-Mail an potenzielle Lieferanten zu verfassen, in der das RFP-Dokument zusammengefasst ist.

1. Öffnen Sie Outlook (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).

1. Wählen Sie **Neue E-Mail**.

1. Wählen Sie im Menüband **Copilot** aus. Wählen Sie aus dem Dropdown-Menü **Entwurf mit Copilot**.

1. In der **„Was soll in dieser E-Mail stehen?“** Prompt-Fenster, tippen Sie:

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **HINWEIS:** Fügen Sie den RFP-Inhalt ein, den Sie aus der vorherigen Demo kopiert haben.

1. Sobald der Entwurf erstellt ist, können Sie mithilfe der Funktion **Anpassen** den Ton, die Länge oder die Stufe der Förmlichkeit ändern.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
