# Sales Automation 1 Final

## Overview

The finalized version of the Sales Automation 1 workflow. It reads companies from a Google Sheet or form, uses an AI agent with Tavily to find domains, enriches organizations through Apollo, searches for people matching ICP criteria, and outputs qualified leads. This version includes form-based input and refined people search from ICP filtering.

## How It Works

```
Manual/Form Trigger -> Google Sheets (read companies) -> AI Agent (find domain) -> Apollo People Search from ICP -> Limit -> Clean data -> Output
```

## Integrations

- **Google Sheets** - Company data source
- **OpenAI** - Domain research
- **Tavily** - Web search
- **Apollo** - Organization enrichment and people search

## Setup

1. Import `Sales_Automation_1_final.json` into your n8n instance.
2. Configure all credentials.
3. Execute manually or via form.
