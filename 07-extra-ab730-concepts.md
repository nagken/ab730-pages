# AB-730 Extra Concepts

> Subtle distinctions and nuances that show up in exam wording.

## Microsoft Copilot families - confusion matrix

| Name | Surface | Grounding | License |
|---|---|---|---|
| **Microsoft Copilot** (free) | copilot.microsoft.com / web / Edge / Windows | Public web (Bing) | Free |
| **Microsoft Copilot Pro** | Same | Public web + Office apps (consumer) | Subscription |
| **Microsoft 365 Copilot** | Word / Excel / PPT / Outlook / Teams (work) | Microsoft Graph (your tenant) | Per-user M365 license |
| **Microsoft Copilot for Sales / Service / Finance** | Specific Dynamics 365 surfaces | CRM/ERP data | Per-product |
| **Copilot Studio** | Custom chatbots | Connectors + topics | Standalone or M365 Copilot |
| **GitHub Copilot** | IDE / GitHub.com | Code | Per-user |

## Grounding clarified

- **Public web grounding** - Copilot uses Bing search to find current info.
- **Tenant grounding** - Copilot uses Microsoft Graph to find your work files, emails, chats.
- **Custom data grounding** - Copilot Studio + connectors to bring custom data sources.

## License vs feature

- M365 Copilot license enables Copilot inside Word, Excel, PPT, Outlook, Teams.
- Free Microsoft Copilot does **NOT** integrate inside Office apps for business.
- Microsoft Copilot Pro **does** integrate into consumer Office (M365 Personal/Family) but NOT business tenants.

## Plugins / extensions

- Copilot Studio agents can be **published** as Copilot extensions.
- Microsoft 365 Copilot can call extensions (Graph connectors, Power Platform, Copilot Studio).
- Plugins **expand grounding** beyond the default Microsoft Graph.

## Image generation

- Microsoft Copilot creates images via DALL-E 3.
- Free users have a daily token allowance ("boosts").
- Generated images carry Content Credentials metadata (provenance).

## Voice and agent modes

- **Copilot Voice** - speak to Copilot in supported clients.
- **Copilot Agents** - persistent task-oriented Copilots.

## When NOT to use Copilot

- High-stakes legal / medical / financial decisions without expert review.
- Anything requiring 100% factual accuracy without verification.
- Generating final output verbatim with no human review.
- Pasting regulated data into web (free) Copilot.

---

[Master Index](00-MASTER-INDEX.md)
