---
demo:
  title: Erstellen eines Agents mit Copilot Studio
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

---

# Erstellen und Veröffentlichen eines Agents mithilfe von Copilot Chat

In dieser Demo wird beschrieben, wie Sie mithilfe von Copilot Studio einen virtuellen Assistant über Copilot Chat erstellen und in Microsoft 365 Copilot veröffentlichen.

## Demoeinrichtung

Für diese Demos müssen Sie die folgenden Dateien herunterladen:

- [**Delivery Drone Press Release.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Press_Release.docx)
- [**Delivery Drone Troubleshooting.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Troubleshooting.docx)
- [**Delivery Drone SOP.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_SOP.docx)
- [**Upselling Opportunities.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Upselling_Opportunities.docx)
- [**Delivery Drone FAQ.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_FAQ.docx)

> **TIPP:** Bevor Sie die Demo vorführen, können Sie in Ihrer Demoumgebung eine SharePoint-Website erstellen, um alle Dateien für den einfachen Zugriff zu speichern. Alternativ können Sie die Dateien lokal speichern und in Ihren Prompts mithilfe von **/** auf diese verweisen.

## Gesprächsthemen

In Copilot Studio können benutzerdefinierte Copilots erstellt werden, die auf bestimmte Projekte, Abteilungen oder Wissensdatenbanken zugeschnitten sind. Es ist möglich, ihnen eine Persönlichkeit zu verleihen, ihre Grenzen festzulegen und ihnen bestimmte Dokumente zur Verfügung zu stellen, damit diese qualitativ hochwertige, gegroundete Antworten geben können.

In dieser Demo wird ein virtueller Assistant für das ReleCloud-Drohnenlieferungsprojekt erstellt. Der Assistent weiß alles aus den hochgeladenen Inhalten und hilft bei der Beantwortung von Fragen des Teams. Das für zu einer Zeitersparnis und einer Verbesserung der Produktivität.

## Demoschritte

### Schritt 1: Navigieren zu Copilot Studio

1. Wechseln Sie zu [https://m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat), und wählen Sie auf der rechten Schiene **Agent erstellen** aus.

    ![Screenshot: Link zum Erstellen eines Agents](../Prompts/media/create-agent.png)

1. Melden Sie sich mit Ihren Anmeldeinformationen an.

### Schritt 2: Definieren des Agents

1. Fügen Sie die folgende Beschreibung hinzu, wenn Sie dazu aufgefordert werden:

    ```text
    You're a virtual project manager assistant for our drone delivery project. You know everything about the project from the documents we've shared with you, and are happy to help team members get the information they need.
    ```

   ![Screenshot: Feature „Beschreiben“](../Prompts/Media/create-agent-through-describe.png)

1. So benennen Sie den Assistenten:

    ```text
    Drone Delivery Assistant
    ```

1. Wenn Sie zur Bestätigung gefragt werden:

    ```text
    Yes, thank you
    ```

1. Wenn Sie gefragt werden, was vermieden oder hervorgehoben werden sollte:

    ```text
    Please be clear and concise and avoid long answers. Where possible, refer primarily to the knowledge shared with you. If you don't know the answer, refer them to the drone delivery project manager.
    ```

1. Wenn Sie zum Tonfall gefragt werden:

    ```text
    Friendly and professional
    ```

> **WICHTIG:**  Je nach Umgebung werden Sie möglicherweise nicht zur Angabe aller Optionen aufgefordert. Wenn Sie nicht dazu aufgefordert werden, können Sie diese Informationen in Copilot Studio auf der Registerkarte **Konfigurieren** hinzufügen.

### Schritt 3: Konfigurieren des Agents

1. Klicken Sie auf **Konfigurieren**, um den Agent-Editor zu öffnen.
1. Lesen Sie den Abschnitt **Anweisungen**, und aktualisieren Sie ihn bei Bedarf:

    ```text
    Your name is Drone Delivery Project Manager Assistant. You serve as a virtual project manager for the ReleCloud drone delivery project, with comprehensive knowledge from shared documents. Be clear and concise, avoiding long answers. If the answer is unknown, refer to the drone delivery project manager.
    ```

1. Scrollen Sie nach unten zum Abschnitt **Wissen**, und klicken Sie auf die Textblase **Nach Name suchen oder URL eingeben**. Wählen Sie **Dateien** aus, und fügen Sie der Wissensdatenbank des Agents die folgenden Dokumente hinzu:

    - **Delivery Drone Press Release.docx**
    - **Delivery Drone Troubleshooting.docx**
    - **Delivery Drone SOP.docx**
    - **Upselling Opportunities.docx**
    - **Delivery Drone FAQ.docx**

        ![Screenshot: Wissensquellen](../Prompts/Media/knowledge-sources.png)

### Schritt 4: Testen des Agents

Probieren Sie, im rechten Bereich „Testen“ einige der folgenden Fragen zu stellen:

- `Tell me about the ReleCloud Delivery Drone.`
- `How do I fix the drone error code D-101?`
- `What are the upsell opportunities for ReleCloud?`
- `What’s the duration of Phase 1 of the delivery drone project?`

> **WICHTIG:**   Es kann einige Zeit dauern, bis der Agent die Dokumente verarbeitet und genaue Antworten liefert. Wenn Sie eine Fehlermeldung erhalten, warten Sie einige Minuten, und versuchen Sie es noch einmal.

> **TIPP:** Sie können zudem über Microsoft Teams testen, sobald der Agent live ist.

### Schritt 5: Veröffentlichen und Freigeben

1. Klicken Sie auf **Erstellen**, um den Agent zu veröffentlichen.
1. Wählen Sie **Freigabeeinstellungen ändern** und dann **Jeder Benutzer in Ihrer Organisation** aus.
1. Kopieren Sie den Freigabelink, und fügen Sie ihn für den erleichterten Zugriff in einen Teams-Chat ein.

Sobald der Agent live ist, können Sie im Teams-Chat oder über @mentions mit ihm interagieren.

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
