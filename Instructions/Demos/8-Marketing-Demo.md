---
demo:
  title: Marketingdemo
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Marketingdemo

**Szenario:**  

Sie sind im Marketing eines Getränkeunternehmens tätig und haben das Ziel, Markttrends zu analysieren, eine Marketinganalyse zu erstellen und eine neue Social-Media-Kampagne zu entwickeln.

## Demoeinrichtung

Die Beispieldokumente sind im MS-4021 GitHub Repository [hier](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) zu finden:

Die für diese Demo benötigten spezifischen Dateien sind:

- [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Promotion_Plan_for_Chai_Tea_in_Latin_America.docx)

- [Mystic_Spice_Premium_Chai_Tea_product_description.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Mystic_Spice_Premium_Chai_Tea_product_description.docx)

- [Contoso_Chai_Tea_market_trends.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_market_trends.docx)

- [Contoso_Chai_Tea_social_marketing_trends.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_social_marketing_trends.xlsx)

> **HINWEIS:** Es kann bis zu 10 Minuten dauern, bis diese Dateien nach dem Herunterladen mit Ihrem OneDrive synchronisiert werden. Um Verzögerungen während der Demo zu vermeiden, stellen Sie sicher, dass diese Dateien rechtzeitig heruntergeladen werden und in Ihrem OneDrive verfügbar sind. Wenn die Dateien nicht verfügbar sind, öffnen Sie die Dokumente und kopieren Sie die Links zu den freigegebenen Dateien, um sie in der Demo zu verwenden.

## Demos

### Copilot in Word

Verwenden Sie Copilot in Word, um einen detaillierten Marktanalysebericht zu erstellen und kreative Ideen für Marketingkampagnen zu entwickeln, die auf den lateinamerikanischen Markt zugeschnitten sind.

1. Öffnen Sie Word (entweder in Ihrem Browser oder in Ihrer Desktop-Anwendung).

1. Geben Sie im Promptfeld **Was soll Copilot entwerfen?** Folgendes ein:

    ```text
    Create a Market Analysis report for Mystic Spice Premium Chai Tea using the attached files. Include the product description, market trend analysis, and a promotion plan for Latin America.

    [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx], [Mystic_Spice_Premium_Chai_Tea_product_description.docx], [Contoso_Chai_Tea_market_trends.docx]
    ```

    > **HINWEIS:** Klammern geben an, dass auf ein Dokument verwiesen wird. Wenn Sie auf ein Dokument verweisen, können Sie den freigegebenen Link direkt einfügen oder auf den Dateinamen verweisen, wenn dieser in Ihrem OneDrive verfügbar ist.

1. Lassen Sie Copilot einen neuen Abschnitt erstellen, um Ideen für Social-Media-Kampagnen hinzuzufügen:

    Geben Sie den folgenden Prompt ein:

    ```text
    Draft a new section for social media campaigns to promote Mystic Spice Premium Chai Tea. Include a brief description of 2-3 campaign ideas, each with a unique focus. For each campaign, provide a tagline that reflects its theme and resonates with our target audience of young professionals and tea enthusiasts.
    ```

1. Wählen Sie im Fenster „Copilot“ die Option „Beibehalten“ aus, um das Dokument von einem Copilot-Entwurf in ein tatsächliches Word-Dokument zu ändern. Speichern Sie dieses neue Dokument anschließend als **LATAM_Market_Analysis.docx**.

### Copilot Chat

Nutzen Sie Copilot Chat, um die Effektivität von vorgeschlagenen Social-Media-Kampagnen zu bewerten und Strategien für die kulturelle Relevanz auf dem LATAM-Markt zu präzisieren.

1. Öffnen Sie einen Browser, und navigieren Sie zu [M365copilot.com](https://m365copilot.com/).

1. Stellen Sie sicher, dass Webmodus ausgewählt ist.

    ![Screenshot der Registerkarte Webmodus.](../Prompts/Media/web-mode.png)

1. Geben Sie im Eingabeaufforderungsfenster Folgendes ein:

    ```text
    Review the social media campaigns outlined in the Market Analysis Report for Mystic Spice Premium Chai Tea.docx. Evaluate which campaign might resonate best with the LATAM market based on cultural relevance, target audience preferences, and alignment with regional trends. Provide reasons for your choice and suggest any adjustments to improve its impact.
    ```

    > **HINWEIS:** Übermitteln Sie die Aufforderung noch nicht. Wechseln Sie zum nächsten Schritt, um die Datei hochzuladen.

1. Wählen Sie **Inhalt hinzufügen** und laden Sie die **LATAM_Market_Analysis.docx** hoch, die Sie in der vorherigen Demo auf Ihrem OneDrive gespeichert haben. Dann senden Sie den Prompt.

    ![Fügen Sie den Copilot-Chat hinzu.](../Demos/Media/add-content-copilot-chat.png)

1. Der Copilot sollte empfehlen, sich auf eine der Kampagnen zu konzentrieren und Vorschläge für Verbesserungen bereitzustellen. Im nächsten Prompt soll Copilot einen Werbeslogan für diese neue Idee vorschlagen:

    ```text
    Generate a catchy marketing slogan for the [Campaign name - e.g., 'Morning Motivation'] campaign that highlights its unique value proposition and resonates with the LATAM market. Ensure the slogan reflects a vibrant and culturally relevant tone that appeals to young professionals.
    ```

1. Optional können Sie Copilot mit dem letzten Prompt auffordern, ein neues Video für die Kampagne zu erstellen:

    Wählen Sie im Copilot-Chat auf der rechten Seite den **Visual Creator Agent**:

    ![video creator agent.](../Demos/Media/video-creator.png)

    Geben Sie dann den folgenden Prompt ein:

    ```text
    Create a captivating social media video for Mystic Spice Chai Tea that highlights its unique flavor and vibrant appeal. The video should feature eye-catching visuals, with colors, and themes that resonate with young professionals and tea enthusiasts.
    ```

### Copilot in Excel

1. Vergewissern Sie sich, dass Sie [Contoso_Chai_Tea_market_trends_2023.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Contoso_Chai_Tea_market_trends_2023.xlsx) heruntergeladen haben, und öffnen Sie das Dokument in Excel (im Web oder in der Desktop-Anwendung).

1. wählen Sie **Copilot** im Excel-Menüband und dann **App-Fähigkeiten** aus, um den Copilot-Bereich zu öffnen.

1. Geben Sie den folgenden Prompt in Excel ein:

    ```text
    On average, how many sales do we get per social media campaign view?
    ```

1. Als Nächstes bitten Sie Copilot, den Umsatz mit dem Engagement in den sozialen Medien zu vergleichen:

    ```text
    Can you show a correlation between social media engagement and sales?
    ```

1. Geben Sie als nächstes den folgenden Prompt ein:

    ```text
    How many social media campaign views did we have from September to December?
    ```

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
