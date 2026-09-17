# Alin Rizea

**AI engineer who ships on Python and Django.** Six years in production, six systems built end to end as the only engineer: specification, architecture, MVP, launch, hardening and day-to-day operation on AWS.

Two rules in everything I build with language models: the model never holds transactional state (a deterministic state machine does), and privacy is designed in from the first commit.

## Live systems

| System | What it is | Stack |
|---|---|---|
| [FormAI](https://dbm-ai.com/ai-form/) · [demo](https://demo.dbm-ai.com/) | Two embedded assistants for commercial websites, installed by one script tag. A2 helps complete forms without ever sending personal data to a model; Sonia is a shopping conversation with an AI search bar that replaces the site's own. | Django, OpenAI API, Shadow DOM, WooCommerce, multi-tenant, AWS |
| [Sprijin360](https://sprijin360.ro) | Community platform for families and therapy specialists. Two-agent conversational onboarding, ten parallel writer agents, a grading loop that rewrites its own prompts with a human in command. | Django, LangGraph, pgvector, Redis, AWS |
| [i-Migrator](https://i-migrator.com) | Immigration case management where lawyers assemble the visa journey themselves: flow builder, JSON-driven screening decision tree, stage-aware permission system. Built for Berd Ltd. | Django, MySQL, Stripe, AWS |
| [LocalInfo](https://localinfo.club) | Guest concierge with a live provider auction. Correctness kept in the data, side effects in an idempotent sweep, fraud control distributed across four parties. Runs in 2 GB. | Django, django-q, gunicorn-gevent, AWS |
| Biblioteca Ligiei | Offline-first audiobook and ebook PWA. Presigned chapter delivery, IndexedDB playback, an LLM translation harness with back-translation validation. | Django, S3, service worker, IndexedDB |
| Multi-tenant dropshipping platform | Supplier and dropshipper as separate tenants, static Astro storefronts deployable to any cheap host. MVP with two pilot clients, for SMY Associates Ltd. | Django, PostgreSQL, Astro |

## Code

- **Public:** [django-error-monitor](https://github.com/elisrizea/django-error-monitor), in-database error capture, grouping and email alerts for Django. Extracted from production, 33 tests, 0BSD.
- **Private:** the systems above are client and company codebases. I can walk you through any of them on a call, including the AI development harness I build with (TDD skills, prompt auditing and tuning suite, agent simulators).
- The older repositories on this profile are 2023 course exercises and are kept for the record only.

## Stack

**AI:** Anthropic Claude, OpenAI API, open-weight models (Qwen, Llama, GLM) via Ollama, LM Studio, AWS Bedrock and Cerebras, LangGraph, LangChain, CrewAI, MCP, RAG on pgvector and ChromaDB
**Backend:** Python, Django, Django REST Framework, HTMX, Celery, django-q2, PostgreSQL, MySQL, Redis, modular monoliths with an enforced dependency graph, deterministic state machines
**Delivery:** Docker, nginx, Caddy, gunicorn, AWS (EC2, RDS, S3, SES, Bedrock), Terraform, Ansible, Jenkins
**Payments and privacy:** Stripe and Stripe Connect, Worldpay, PCI-compliant self-hosted card capture, GDPR, client-side tokenisation of PII and PHI
**Frontend and mobile:** JavaScript, Alpine.js, Astro, progressive web apps, Shadow DOM, Flutter

## Contact

alin.rizea@gmail.com · [LinkedIn](https://www.linkedin.com/in/alin-rizea-b10368104/) · [dbm-ai.com](https://dbm-ai.com) · UK-based, available for contract work through DBM AI Ltd or permanent roles.
