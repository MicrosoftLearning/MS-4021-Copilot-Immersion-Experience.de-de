---
demo:
  title: Demo zu Recherche-Agent und Analyse-Agent
---

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demo zu Recherche-Agent und Analyse-Agent

In dieser Demo wird die Verwendung von**Recherche-Agent** und**Analyse-Agent** erläutert – Experten-Agents, die in die Copilot-App integriert sind.  

- **Recherche-Agent** unterstützt Sie bei mehrstufigen Rechercheaufgaben durch die Kombination von Webdaten mit den Dateien und dem Wissen Ihres Unternehmens.  
- **Analyse-Agent** sieht sich als erfahrene wissenschaftliche Fachkraft für Daten, die erweiterte Datenanalyse- und Python-Ausführungen durchführen kann, selbst wenn Sie nicht wissen, wie diese programmiert werden.  

## Demoeinrichtung

Um diese Demos abzuschließen, müssen Sie das[Demo zu Recherche-Agent und Analyse-Agent – Inhaltspaket](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/master/ResourceFiles/Researcher_and_Analyst_Demo_Content_Pack.zip) herunterladen, das alle erforderlichen Dateien und Ressourcen enthält.  

> **TIPP:** Bevor Sie die Demo vorführen, können Sie in Ihrer Demoumgebung eine SharePoint-Website erstellen, um alle Dateien für den einfachen Zugriff zu speichern. Alternativ können Sie die Dateien lokal speichern und in Ihren Prompts mithilfe von**/** auf diese verweisen.  

So greifen Sie auf diese Agents zu:  

- Öffnen Sie die**App Copilot** von[m365.cloud.microsoft](https://m365.cloud.microsoft).  
- Wählen Sie aus dem Navigationsbereich**Recherche-Agent** oder**Analyse-Agent** aus.  

> **Hinweis:** Sie müssen Recherche-Agent und Analyse-Agent auf interne Dateien (SharePoint/OneDrive) verweisen, um gegroundete Einblicke zu erhalten.

---

## Gesprächsthemen

- **Recherche-Agent** verhält sich wie ein hoch bezahlter Berater und kann durch die Kombination interner Dateien, des Wissens von Mitbewerbern und Webquellen strukturierte, gut aufgeführte Ergebnisse erstellen.  
- **Analyse-Agent** ist wie eine wissenschaftliche Fachkraft für Daten und erstellt Modelle, führt Python-Code aus und visualisiert Trends sofort.  
- Beide Agents erläutern ihre Überlegungen transparent, damit Sie die Ergebnisse überprüfen können.  
- Zusammen beschleunigen sie die strategische Arbeit in Form von Marketingplänen, Kundensegmentierung und Finanzprognosen, um Ihnen schnellere und zuverlässige Abläufe zu ermöglichen.  

---

## Demoschritte

### Recherche-Agent: Erstellen eines Marketingplans

> **WICHTIG:** Die Schritte 1–4 sollten zu Beginn des Trainings (wie auf Folie 5 angegeben) ausgeführt werden, damit Recherche-Agent genügend Zeit zum Vervollständigen des ersten Prompts hat.

1. Öffnen Sie im Navigationsbereich**Recherche-Agent**.  

    ![Screenshot: Auswahl von „Recherche-Agent“ im Menü „M365 Copilot“](../Prompts/Media/researcher.png)  

1. Geben Sie den folgenden Prompt ein:

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. Anfügen von Verweisdateien mithilfe von`/` (Verweis auf SharePoint/OneDrive):  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(Optional)***/Contoso - PedalPerks GTM Plan.docx**  

1. Wählen Sie**Übermitteln** aus.  

Recherche-Agent führt Folgendes aus:  

- Kombinieren der Erkenntnisse aus internen Dateien und dem Web  
- Strukturieren eines Marketingplans mit Empfehlungen zu Kanälen und Inhaltsstrategie  
- Zitieren von Quellen, damit Sie ihre Arbeit überprüfen können  

> **Hinweis:** Recherche-Agent zeigt den Pfad seiner Begründungen (die „Gedankenkette“) und kann bei Bedarf weitere Agents aufrufen.  

### Analyse-Agent: Kundensegmentierung und Finanzmodellierung

**Hinweis:** Diese Demo wird nicht für die Ausführungsversion des Inhalts ausgeführt. Wechseln Sie stattdessen zur**Copilot Studio**-Demo.

1. Öffnen Sie im Navigationsbereich**Analyse-Agent**.

    ![Screenshot: Auswahl von Analyst im M365 Copilot-Menü](../Prompts/Media/analyst.png)  

1. Geben Sie den folgenden Prompt ein:

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. Fügen Sie die Datei mithilfe**+** an:  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![Screenshot: Anfügen von Dateien in Analyst](../Prompts/Media/Analyst-Attach-Files.png)  

1. Wählen Sie**Übermitteln** aus.  

Analyse-Agent führt Folgendes aus:  

- Analysieren des Datasets  
- Identifizieren hochwertiger Kundensegmente  
- Bereitstellen von Visualisierungen, um Empfehlungen zu begründen  

### Zusätzliche Szenarios mit Analyse-Agent

Sie können diese zusätzlichen Prompts ausführen, um unterschiedliche Ergebnisse zu erhalten. Jedes folgt demselben Muster:**Prompt → Datei anfügen → Senden → Ergebnisse überprüfen.**

- **Finanzielle Prognosen**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    Datei:**BoulderEV ebike Internal Market Forecast.xlsx**  

- **Vertriebsleistung**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    Datei:**BoulderEV ebike Internal Market Forecast.xlsx**  

- **Kampagnenleistung**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    Datei:**BoulderEV ebike Internal Market Forecast.xlsx**  

## Wichtige Erkenntnisse

- **Recherche-Agent** beschleunigt Strategie und Planung mit qualitativ hochwertiger Recherche.  
- **Analyse-Agent** liefert datengesteuerte Erkenntnisse mit erweiterten Analysen und Visualisierungen.  

Zusammen verkürzen Recherche-Agent und Analyse-Agent den Pfad**von Frage zu Erkenntnissen** und erledigen die Arbeit von Wochen in Minuten.  

[Zurück zum Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
