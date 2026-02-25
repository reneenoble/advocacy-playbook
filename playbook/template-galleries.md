# Template Galleries

Get your product into a gallery where developers are already browsing for templates. When someone wants to try a technology, they find a template and deploy it immediately — removing friction from the "getting started" experience.

## Overview

| Attribute | Details |
|-----------|---------|
| **Impact Level** | Medium-High |
| **Lead Time** | 2-4 weeks |
| **Effort Required** | Medium |
| **Best For** | Practical adoption, getting started quickly |

## Key Galleries

### Awesome AZD (Azure Developer CLI)
- **Gallery**: [azure.github.io/awesome-azd](https://azure.github.io/awesome-azd/)
- **GitHub**: [github.com/Azure/awesome-azd](https://github.com/Azure/awesome-azd)
- Full-stack templates with code + infrastructure
- Developers deploy with `azd init --template <name>` and `azd up`

### Awesome Copilot
- **GitHub**: [github.com/github/awesome-copilot](https://github.com/github/awesome-copilot)
- Copilot agents, prompts, skills, and configurations
- Cookbook examples and reusable agent skills

Check if your product area has its own template/sample gallery too.

## How to Add a Template

1. **Review the gallery** — understand the format and requirements
2. **Create your template** — follow the gallery's structure (e.g. include `azure.yaml` for AZD)
3. **Test thoroughly** — ensure it works reliably on a fresh environment
4. **Submit a PR** — follow the contribution guidelines
5. **Maintain** — keep your template updated (broken templates damage credibility)

## Tips

- Focus on getting users to a working state quickly
- Include a clear README with instructions
- Test on fresh environments — don't assume anything is pre-installed
- Pin all dependency versions
- Support Codespaces/DevContainers so users can start without local setup

## Organising Your Samples

A few common patterns (discussed in the advocacy team meeting):

| Pattern | How it works | Good for |
|---------|-------------|----------|
| **Folder-based** | One repo with each sample in a subfolder | Manageable number of samples, unified ownership |
| **Branch-based** | One repo with each sample on a different branch | Less common, some projects use it |
| **Awesome-style** | One repo linking to other repos, auto-generates a browsable site | Large numbers of samples, distributed ownership |

## Works Well With

- **For Beginners Courses** — templates as starting points for lessons
- **Workshops** — use gallery templates as workshop foundations
- **Blogs** — write posts explaining your gallery template
- **Videos** — record walkthroughs of deploying your template

## Real Examples

| Template/Gallery | What It Shows |
|------------------|---------------|
| [azure-search-openai-demo](https://github.com/Azure-Samples/azure-search-openai-demo) | 7.6k stars — the reference RAG app. Full AZD template with Codespaces, Bicep infra, and thorough docs |
| [python-openai-demos](https://github.com/Azure-Samples/python-openai-demos) | 317 stars — short, focused OpenAI SDK examples for Azure OpenAI and GitHub Models |
| [python-ai-agent-frameworks-demos](https://github.com/Azure-Samples/python-ai-agent-frameworks-demos) | 290 stars — multi-framework agent examples with AZD support |
| [python-mcp-demos](https://github.com/Azure-Samples/python-mcp-demos) | FastMCP with stdio/HTTP transports and Azure Container Apps deployment |
| [Awesome Copilot](https://github.com/github/awesome-copilot) | 22k stars — community-driven agents, prompts, skills, and cookbook recipes for GitHub Copilot |
| [openai-chat-app-quickstart](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Minimal chat app quickstart — good example of a focused, deploy-fast template |

## Links

- [Awesome AZD Gallery](https://azure.github.io/awesome-azd/)
- [Awesome Copilot Repository](https://github.com/github/awesome-copilot)
- [Azure Developer CLI Templates Docs](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates)

---

[← Back to Playbook](./README.md)
