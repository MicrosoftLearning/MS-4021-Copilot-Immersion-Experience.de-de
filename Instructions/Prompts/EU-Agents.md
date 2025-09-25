---
task:
  title: "Immersionserfahrung\_– Agents (Geschäftliche Benutzende)"
---

## Immersionserfahrung – Agents (Geschäftliche Benutzende)

Hier erfahren Sie, wie Microsoft 365 Copilot und Copilot Studio Sie dabei können, alltägliche Herausforderungen bei der Produktivität zu bewältigen, indem Sie einen einfachen **abrufbasierten Agent** entwerfen. In dieser optimierten Übung erfahren Sie, wie Sie ein häufig auftretendes Problem identifizieren. Zudem untersuchen Sie, wie KI dabei helfen kann, und erstellen anschließend einen einfachen Agent zum Testen.  

Sie werden drei Aufgaben erfüllen:

- Identifizieren eines Problempunkts bei der Produktivität  
- Hier erfahren Sie, wie KI das Abrufen und Organisieren unterstützen kann.  
- Erstellen und Testen eines einfachen Agents in **Copilot Studio**  

> **HINWEIS:** Es werden Beispielprompts bereitgestellt, die Sie bei den ersten Schritten unterstützen. Diese können Sie an Ihre Anforderungen anpassen.  
>
> Wenn Sie beim Generieren oder Optimieren von Prompts Unterstützung möchten, probieren Sie den <a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank">Prompt-Coach-Agent</a>aus, der Prompts vorschlagen, verbessern und auswerten kann, damit Sie mit Copilot bessere Ergebnisse erzielen.

### Aufgabe 1: Identifizieren einer Herausforderung bei der Produktivität  

Stellen Sie sich ein häufig auftretendes Problem in Ihrer täglichen Arbeit vor, durch das Sie verlangsamt werden oder das Auffinden oder Organisieren von Informationen erschwert wird. Sie können allein darüber nachdenken oder **Copilot Chat** als Partner verwenden, um Ideen zu generieren und häufig auftretende Probleme zu identifizieren.

Beispiele:

- Suchen der neuesten Version eines Dokuments  
- Sammeln von Updates aus mehreren E-Mails oder Chats  
- Erfassen von Details aus früheren Projekten oder Besprechungen  

**Schritte**:  

- Öffnen Sie eine neue Browserregisterkarte, und navigieren Sie zu [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat). 

- Stellen Sie sicher, dass in **Copilot Chat** die Registerkarte **Arbeitsmodus** ausgewählt ist.  

   ![Screenshot: Registerkarte „Arbeitsmodus“ in Copilot Chat](../Prompts/Media/work-mode.png)  

    **Beispielprompt:**

    ```text
    Summarize the top challenges I face in my daily work, based on recent emails, chats, and documents. Show results in a simple list with: 
    
    - Title (short label for the issue) 
    - Description (1–2 sentences) 
    ```  

### Aufgabe 2: Erkunden von Ideen zu KI-Lösungen mit Recherche-Agent  

Verwenden Sie **Recherche-Agent**, um herauszufinden, wie Copilot oder Agents bei der gewählten Herausforderung helfen könnten.

**Schritte**:  

- Erweitern Sie im Menü „Copilot Chat“ die Option **Agents** (falls erforderlich), und wählen Sie **Recherche-Agent** aus.  

   ![Screenshot: Auswahl von „Recherche-Agent“ im Menü „M365 Copilot“](../Prompts/Media/researcher.png)  

- Probieren Sie einen Prompt wie den folgenden aus:  

   ```text
   Explore possible AI solutions to help with [insert productivity issue]. Focus on retrieval-based approaches using Microsoft Copilot or Copilot Studio agents. Summarize two or three ways an agent could help me find, organize, or summarize information more efficiently.
   ```  

    > **TIPP:** Konzentrieren Sie sich auf praktische, alltägliche Anwendungsfälle wie das schnelle Anzeigen eines Dokuments oder das Abrufen von Updates aus mehreren Quellen.
  
    > **HINWEIS:** Recherche-Agent kann je nach Anfrage 5 bis 10 Minuten (oder mehr) beanspruchen. Die Antworten sind sehr detailliert. Während die Recherche läuft, können Sie denselben Prompt in Copilot Chat ausprobieren. Durch den Vergleich der beiden Ergebnisse können Sie gut erkennen, wie die beiden Tools die Aufgabe angehen.

### Aufgabe 3: Erstellen und Testen des Agents  

Erstellen Sie nun in **Copilot Studio Lite** einen einfachen Abruf-Agent, der sich Ihrer Herausforderung widmet.  

**Schritte**:  

1. Wählen Sie im Menü **Copilot Chat** die Option **Agent erstellen** aus.

   ![Screenshot: Link zum Erstellen eines Agents](../Prompts/Media/create-agent.png)  

1. Entwerfen Sie auf der Registerkarte **Beschreiben** die Rolle Ihres Agents. Zum Beispiel:  

   ```text
   You’re a virtual assistant that helps me with [key task]. Be concise and always reference my recent files or resources when possible.
   ```  

   ![Screenshot: Beschreibung des Agents mit ausgefülltem Beispielprompt](../Prompts/Media/create-agent-through-describe.png)  

1. Wählen Sie die Registerkarte **Konfigurieren** aus, und fügen Sie eine Wissensquelle hinzu (z. B. **Meine E-Mails** oder **Meine Teams-Chats und -Besprechungen**).

    ![Screenshot: Abschnitt „Wissensquellen“ im Agent-Generator](../Prompts/Media/knowledge-sources.png)

1. Testen Sie mithilfe des Bereichs **Testen** Ihren Agent, und optimieren Sie ihn nach Bedarf.  
1. Wählen Sie **Erstellen** aus, um Ihren Agent zu veröffentlichen und mit der Verwendung zu beginnen.  

> **TIPP:** Selbst ein sehr einfacher Agent, der Ihnen hilft, aktuelle Projektdateien zu finden, kann die Leistungsfähigkeit des Abrufens bei Ihrer täglichen Arbeit veranschaulichen.
