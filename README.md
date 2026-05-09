# Brazil + AI Data Toolkit API
<img width="1254" height="1254" alt="logo_API" src="https://github.com/user-attachments/assets/035f377e-0ff0-4a2b-ad56-5fba801d44e0" />


Turn websites into AI-ready Markdown, screenshots and structured public data for RAG, agents, automation and security workflows.

## Features

- Webpage to Markdown extraction
- Website screenshots
- Brazilian CNPJ lookup
- Brazilian CEP lookup
- IP intelligence
- Subdomain discovery

## Built for

- AI agents
- RAG pipelines
- automation workflows
- enrichment systems
- security workflows

---

# Example — Markdown Extraction

```bash
curl -X POST \
  https://brazil-ai-data-toolkit1.p.rapidapi.com/v1/extract/markdown \
  -H "X-RapidAPI-Key: YOUR_API_KEY" \
  -H "X-RapidAPI-Host: brazil-ai-data-toolkit1.p.rapidapi.com" \
  -H "Content-Type: application/json" \
  -d '{
    "url": "https://en.wikipedia.org/wiki/Brazil",
    "max_bytes": 750000,
    "refresh": false
  }'
```

## Example Response

```json
{
  "cache_hit": false,
  "result": {
    "url": "https://en.wikipedia.org/wiki/Brazil",
    "title": "Brazil",
    "markdown": "# Brazil\n\nBrazil is the largest country in South America..."
  }
}
```

---

# Use Cases

## AI & RAG

Convert public webpages into clean Markdown ready for:
- LLM ingestion
- retrieval pipelines
- AI agents
- embeddings

## Automation

Use screenshots and structured data in:
- n8n
- Zapier
- internal workflows
- monitoring systems

## Security

Discover subdomains and inspect public IPs for:
- reconnaissance
- enrichment
- monitoring
- lightweight security workflows

---

# Available on RapidAPI

Access the API through RapidAPI with:
- free tier
- usage quotas
- API key management 
- marketplace billing

## RapidAPI

[View on RapidAPI](https://rapidapi.com/cleberf323/api/brazil-ai-data-toolkit1)
