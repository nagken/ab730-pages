# AB-730 Architectures

> Conceptual architectures relevant to a business user.

## 1. Microsoft Copilot (free, web)

```mermaid
flowchart LR
    User[User]
    User --> WebUI[copilot.microsoft.com]
    WebUI --> AI[GPT model]
    WebUI --> Bing[Bing web search]
    Bing --> AI
    AI --> Resp[Response]
    Resp --> User
```

## 2. Microsoft 365 Copilot (tenant-grounded)

```mermaid
flowchart TB
    User[User in Word / Outlook / Teams]
    User --> M365[M365 Copilot]
    M365 --> Graph[Microsoft Graph -<br/>user emails, files, chats]
    M365 --> LLM[Foundation model]
    Graph --> LLM
    LLM --> Out[Grounded response<br/>with citations]
    Out --> User
    Purview[Purview sensitivity labels]
    Purview --> Out
```

## 3. Copilot Studio (custom agent)

```mermaid
flowchart LR
    Maker[Maker / IT pro]
    Maker --> Studio[Copilot Studio]
    Studio --> Topics[Topics + flows]
    Studio --> KB[Knowledge sources -<br/>SharePoint, web, docs]
    Studio --> Conn[Connectors -<br/>1500+ data sources]
    Studio --> Agent[Custom Copilot agent]
    Agent --> Users[Business users]
```

## 4. Sensitivity label flow

```mermaid
flowchart LR
    File[Confidential file in SharePoint]
    File --> Label[Sensitivity: Confidential]
    User[User asks Copilot] --> M365[M365 Copilot]
    M365 --> File
    M365 --> Out[Output]
    Label --> Out
    Out -->|inherits Confidential label| User
```

## 5. M365 Copilot Chat surfaces

```mermaid
flowchart TB
    Chat[Microsoft 365 Copilot Chat]
    Chat --> Web[copilot.cloud.microsoft]
    Chat --> Teams[Teams app]
    Chat --> Outlook[Outlook chat panel]
    Chat --> Edge[Edge sidebar]
```

---

[Master Index](00-MASTER-INDEX.md)
