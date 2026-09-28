## Hi, I'm Ravi Kumar

**Senior Full Stack Software Engineer** — Ruby · Grape APIs · Ruby on Rails · React · Multi-tenant SaaS

Mohali, Punjab, India · 8 years building with Ruby · **Open to new roles — available to join immediately**

[LinkedIn](https://www.linkedin.com/in/ravi-kumar-b7504612a) · [GitLab](https://gitlab.com/ravikumar.developerbabu) · [Email](mailto:rvk_singh@outlook.com)

---

### About me

I build multi-tenant SaaS platforms and distributed Ruby services — both Ruby on Rails applications and standalone Grape/Rack APIs. Most recently I worked on a business-management platform commercialised in 15+ countries, where I designed and shipped a production OAuth 2.0 authorization server that lets ChatGPT, Claude, Slack and Microsoft Teams connect to the platform over the Model Context Protocol (MCP).

What I care about most: strict tenant isolation, fast PostgreSQL, background jobs that are safe to retry, and APIs that never break their consumers.

### Highlights

- **OAuth 2.0 + MCP** — authorization server (RFC 6749, PKCE, RFC 8414/9728) connecting external AI assistants to the platform; found and closed a cross-service impersonation vulnerability by making every service re-validate the bearer token itself.
- **Multi-tenant PostgreSQL** — horizontal sharding and ActsAsTenant scoping with strict isolation across 6 microservices; p95 query latency held under a 300 ms New Relic SLO.
- **AI service layer** — shared LLM layer (RubyLLM, AWS Bedrock, Anthropic Claude, OpenAI) adopted platform-wide, including streaming XLSX-to-CSV for document-aware chat.
- **Integrations** — 39+ third-party connectors across 13 domains: Stripe, PayPal, Razorpay, Adyen, Xero, QuickBooks, Salesforce, HubSpot, ConnectWise, Autotask, Halo PSA.
- **Background pipelines** — Sidekiq and Sidekiq-Cron with per-tenant shard context, idempotent jobs and a replay-safe PayPal payout pipeline.
- **Security** — raised the platform security rating to 95/100 (OWASP Top 10): Warden, JWT, 2FA, Rack::Attack and one declarative RBAC macro across all services.
- **Team lead** — led Maropost's ConnectorApp and shipped a Commerce API V1 → V2 migration with full backward compatibility.

### Featured project

**[salary_management](https://github.com/RvSinghDeveloperbabu/salary_management)** — compensation analytics for a 10,000-employee, multi-country organisation. Rails 8.1 API + React 19/TypeScript, fully Dockerised, 491 RSpec examples with 99% backend coverage, append-only effective-dated salary history, integer-only money handling, and written ADRs for every major decision.

### Tech stack

| Area | Tools |
|---|---|
| Languages & frameworks | Ruby, Grape, Rack, Rake, Ruby on Rails, Sinatra, JavaScript (ES6+), TypeScript, React.js, Vue.js, HTML/ERB, HAML |
| Databases & search | PostgreSQL (sharding, indexing, query tuning), ActiveRecord, ActsAsTenant, Redis, Elasticsearch, MySQL, MongoDB |
| APIs & messaging | REST, GraphQL, Swagger/OpenAPI, Webhooks, Sidekiq, Sidekiq-Cron |
| Cloud & containers | AWS (EKS, EC2, S3, Bedrock), Docker, Docker Compose, Kubernetes, GCP, DigitalOcean, Heroku |
| Security & auth | OAuth 2.0 (PKCE, RFC 8414/9728), JWT, Warden, Rack::Attack, 2FA, OWASP Top 10 |
| AI & agents | Model Context Protocol (MCP), RubyLLM, AWS Bedrock, Anthropic Claude API, OpenAI API |
| Quality & observability | RSpec, RuboCop, SonarQube, Bundler Audit, GitLab CI/CD, GitHub Actions, New Relic APM, Sentry |

### Experience

| Period | Role |
|---|---|
| Jul 2023 – Jun 2026 | Senior Software Engineer — PosiWise / CloudOlive (remote, Belgium) |
| Nov 2020 – Jul 2023 | Senior Ruby on Rails Developer / Team Lead — Maropost |
| Jul 2018 – Sep 2020 | Ruby on Rails Developer — CodeGarageTech |

Most of my professional work lives in private company repositories and on [GitLab](https://gitlab.com/ravikumar.developerbabu). Happy to walk through architecture and code in an interview.
