# Femi Ofobutu

**Founder · Product Architect & Product Manager** · Lagos, Nigeria · Working remotely

I design and ship products that turn compliance frameworks into automated, audit-ready systems. I have spent ten years in regulated operations across export trade, oil & gas logistics and fintech. Now I build the software that runs compliance.

---

### What I'm building

**[StackWeaver](https://stackweaver.cloud)**: trust infrastructure for regulated fintechs
- Compliance automation covering SOC 2, PCI DSS 4.0, ISO 27001, NDPA 2023 and CBN AML/CFT
- 11 production n8n workflows, including evidence generation, regulatory news triggers and HMAC-verified payment onboarding
- Supabase with tenant-isolated row-level security, plus a self-hosted AI layer (LangGraph, LiteLLM, Qdrant)
- Disposable infrastructure across GCP, Oracle Cloud and Vultr: durable state lives in GitHub, Supabase and Qdrant, and any VM can be rebuilt in under 30 minutes

**[NanoByte](https://nanobyte.biz)**: profit forecasting for affiliate media buyers
- Read-only, least-privilege integrations with ClickBank, Digistore24 and Meta Ads
- API keys encrypted in Supabase Vault, PII stripped on ingestion, row-level security on every account
- P10 to P90 profit ranges with confidence labels, validated by point-in-time backtesting

*Source for both products is private. I'm happy to walk through the architecture on a call.*

---

### Case study: closing a tenant-isolation gap

I audited row-level security on my own platform and found 4 policies that let any signed-in user read every client's data. I replaced them with tenant-scoped policies built on `SECURITY DEFINER` helper functions, then re-tested access for each role.

---

### Toolbox

| Area | Tools |
|---|---|
| Compliance | SOC 2, PCI DSS 4.0, ISO/IEC 27001, NDPA 2023, GDPR, CBN AML/CFT |
| Languages | Python, TypeScript/JavaScript, SQL, Bash |
| Data & auth | Supabase/PostgreSQL, row-level security, Clerk, Keycloak, Vault, OPA |
| Automation & AI | n8n, LangGraph, LiteLLM, Qdrant, Flowise |
| Cloud | Google Cloud, AWS, Oracle Cloud, Cloudflare Workers, Docker |

### Public projects
- [ai-video-renderer](https://github.com/joftfem/ai-video-renderer): an automated content pipeline built on Dockerized n8n, Google Cloud (Functions, Pub/Sub, Secret Manager, Storage) and AI APIs

### Contact
[LinkedIn](https://www.linkedin.com/in/femi-ofobutu) · [stackweaver.cloud](https://stackweaver.cloud)
