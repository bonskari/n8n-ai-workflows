# n8n AI Workflow Templates -- Powered by Ollama (100% Local, 100% Free AI)

> **Production-ready n8n automation workflows that use local AI via Ollama. No API keys. No cloud costs. No data leaves your machine.**

[![n8n](https://img.shields.io/badge/n8n-workflow_automation-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)
[![Ollama](https://img.shields.io/badge/Ollama-local_AI-000000?style=for-the-badge)](https://ollama.ai)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](#license)
[![Get Full Pack](https://img.shields.io/badge/Get_Full_Pack_(11_Workflows)-$39-667eea?style=for-the-badge)](https://bonskari.github.io/n8n-ai-workflows/)

---

## 3 Free Sample Workflows

Try before you buy. Each workflow is a real, complete, production-ready template -- not a stripped-down demo.

| # | Workflow | What It Does | Nodes | Trigger |
|---|----------|-------------|-------|---------|
| 1 | [AI Blog Writer Pipeline](samples/ai-blog-writer.json) | Enter a topic, get a polished 1500-word blog post. Uses a 4-stage AI pipeline: Research, Outline, Draft, Edit. | 7 | Manual |
| 2 | [AI Social Media Content Generator](samples/ai-social-content-generator.json) | One topic becomes ready-to-post content for Twitter, LinkedIn, Reddit, and Instagram -- with AI quality review. | 6 | Manual |
| 3 | [AI Data Extractor](samples/ai-data-extractor.json) | Send unstructured text via webhook, get clean structured JSON back. Includes AI-powered verification of extracted data. | 6 | Webhook |

### Quick Download Links

- **[ai-blog-writer.json](https://github.com/bonskari/n8n-ai-workflows/raw/main/samples/ai-blog-writer.json)** -- 4-stage blog content pipeline
- **[ai-social-content-generator.json](https://github.com/bonskari/n8n-ai-workflows/raw/main/samples/ai-social-content-generator.json)** -- Multi-platform social content
- **[ai-data-extractor.json](https://github.com/bonskari/n8n-ai-workflows/raw/main/samples/ai-data-extractor.json)** -- Unstructured text to structured JSON

---

## How to Import into n8n

```
1. Download any .json file from the samples/ folder above
2. Open n8n -> Workflows -> Import from File
3. Select the downloaded JSON file
4. Make sure Ollama is running locally:
     ollama pull llama3:8b
     ollama serve
5. Click "Execute Workflow" -- done!
```

All workflows connect to Ollama at `http://localhost:11434` by default. No API keys or credentials needed.

---

## The Full Pack: 11 Production Workflows ($39)

Like the free samples? The complete pack includes **11 workflows** covering content, sales, and productivity automation -- all powered by local AI.

### Content & Marketing (4 workflows)
- **AI Blog Writer Pipeline** -- 4-stage content pipeline *(free sample included)*
- **AI Social Media Content Generator** -- One topic to 4 platforms *(free sample included)*
- **AI YouTube-to-Newsletter Pipeline** -- YouTube URL to email newsletter in 60 seconds
- **AI Multi-Platform Content Repurposer** -- One post to 6 platform-optimized versions

### Sales & Business (4 workflows)
- **AI Lead Scoring & Enrichment** -- Webhook-triggered scoring (1-100), auto-route hot leads
- **AI Competitor Intelligence Monitor** -- Weekly autopilot competitive analysis
- **AI Email Auto-Responder** -- Classify emails, filter spam, draft replies every 5 minutes
- **AI Support Ticket Router** -- Classify, prioritize, auto-reply, and escalate

### Productivity (3 workflows)
- **AI Data Extractor** -- Unstructured text to clean JSON with verification *(free sample included)*
- **AI Document Summarizer** -- Webhook API for document summaries + Q&A pairs
- **AI Meeting Notes Summarizer** -- Transcripts to structured summaries + action items

### [Get the Full Pack -- $39 ->](https://bonskari.github.io/n8n-ai-workflows/)

One-time purchase. Instant download. Lifetime updates.

---

## Why Self-Hosted AI?

| | Cloud AI (OpenAI, etc.) | Self-Hosted (Ollama) |
|---|---|---|
| **Monthly cost** | $20--200+ | **$0** |
| **Data privacy** | Sent to third-party servers | **Stays on your machine** |
| **Rate limits** | Yes | **None** |
| **Works offline** | No | **Yes** |
| **GDPR compliant** | Complicated | **By default** |
| **Vendor lock-in** | Yes | **No** |

---

## Requirements

- [n8n](https://n8n.io) self-hosted (v1.0+)
- [Ollama](https://ollama.ai) running on `localhost:11434`
- Any Ollama model -- `llama3:8b` recommended (works with any model)
- 8GB+ RAM recommended

### Quick Setup

```bash
# Install Ollama (macOS/Linux)
curl -fsSL https://ollama.ai/install.sh | sh

# Pull the recommended model
ollama pull llama3:8b

# Start Ollama (if not already running)
ollama serve
```

---

## Screenshots

> Screenshots of each workflow running in n8n coming soon. Star this repo to get notified!

<!--
TODO: Add screenshots
![Blog Writer Workflow](screenshots/blog-writer.png)
![Social Content Generator](screenshots/social-content.png)
![Data Extractor](screenshots/data-extractor.png)
-->

---

## FAQ

**Q: Do these work with OpenAI / Claude / other cloud APIs?**
A: The workflows are built for Ollama, but you can swap the HTTP Request nodes for n8n's native OpenAI/Anthropic nodes with minimal changes.

**Q: What n8n version do I need?**
A: v1.0 or later. All workflows use standard nodes available in the free self-hosted version.

**Q: Can I use a different Ollama model?**
A: Yes. Change `llama3:8b` in the workflow to any model you have pulled (e.g., `mistral`, `codellama`, `phi3`).

**Q: What do I get in the full pack vs. the free samples?**
A: The free samples are 3 complete workflows. The full pack adds 8 more workflows covering email automation, lead scoring, competitor monitoring, meeting notes, document summarization, content repurposing, YouTube-to-newsletter, and support ticket routing.

---

## Tutorials & Guides

Step-by-step guides for building AI automation workflows with n8n + Ollama:

- [Getting Started with Self-Hosted AI Workflows](https://bonskari.github.io/n8n-ai-workflows/blog/self-hosted-ai-workflows-n8n-ollama.html)
- [Complete n8n + Ollama Tutorial](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-ollama-tutorial-local-ai-automation.html)
- [AI Email Auto-Responder](https://bonskari.github.io/n8n-ai-workflows/blog/automate-email-responses-n8n-ollama.html)
- [AI Lead Scoring Pipeline](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-ai-lead-scoring-ollama-workflow.html)
- [Private RAG Knowledge Base](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-rag-knowledge-base-ollama-private.html)
- [AI Customer Support Automation](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-customer-support-automation-ollama.html)
- [AI Invoice Data Extraction](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-invoice-data-extraction-ollama.html)
- [AI Code Review Automation](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-ai-code-review-ollama.html)
- [AI Content Moderation](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-ai-content-moderation-ollama.html)
- [AI Product Descriptions for E-Commerce](https://bonskari.github.io/n8n-ai-workflows/blog/n8n-ai-product-descriptions-ollama-ecommerce.html)

[View all tutorials ->](https://bonskari.github.io/n8n-ai-workflows/)

---

## Star History

If this repo helped you, give it a star! It helps others discover these workflows.

[![Star this repo](https://img.shields.io/github/stars/bonskari/n8n-ai-workflows?style=social)](https://github.com/bonskari/n8n-ai-workflows)

---

## Support

Questions or issues? [Open an issue](https://github.com/bonskari/n8n-ai-workflows/issues) or email admin@unstableentity.com

---

## License

The free sample workflows in this repository are released under the [MIT License](LICENSE). The full paid pack is licensed per-user.

---

### [Get the Full Pack (11 Workflows) -- $39 ->](https://bonskari.github.io/n8n-ai-workflows/)
