## Rafael Balchuna

**PT-BR:** Analista de Dados, Power BI e Desenvolvedor de Automação (São Paulo/SP · UTC-3 · 100% Remoto BR/LATAM/Global). Trabalho com SQL, Python, Power BI (DAX/PBIP), APIs REST, automação documental e fluxos com IA/MCP. Inglês fluente escrito e falado (90% / percentil 97).

**EN:** Junior Data Analyst, Power BI & Python Automation Developer based in São Paulo, Brazil (UTC-3, aligned with US EST/CST · 100% Remote Worldwide/LATAM). Focused on SQL, Python, Power BI (DAX/PBIP), REST APIs, production document automation, and AI/MCP workflows. Fluent English — written and spoken (90% / 97th percentile).

**Portfólio bilíngue / Bilingual Portfolio (1 clique):** [PT-BR](https://balchuna.github.io/) · [English](https://balchuna.github.io/?lang=en) · **LinkedIn:** [linkedin.com/in/rafael-balchuna](https://www.linkedin.com/in/rafael-balchuna)

---

### Projetos-Âncora / Flagship Projects (1-Click Showcase)

| # | Projeto / Project | Escopo, Arquitetura & Métricas Verificáveis (PT-BR / EN) | Links (1 clique) |
|---|---|---|---|
| **1** | **Brazilian E-Commerce & Macroeconomics BI** | **PT:** 99.441 pedidos reais da Olist (96.478 entregues) cruzados com APIs oficiais do **Banco Central** (IPCA SGS 433, Selic 432, PTAX 1) e **IBGE** (população por UF) em esquema estrela (11 tabelas), Power BI PBIP de 4 páginas (**107 medidas DAX**, 17 títulos dinâmicos `fx`) e painel web bilíngue claro/escuro. GMV real deflacionado de **R$ 15,96 mi** (+135,9% a/a), SLA de **93,23%** e nota média caindo de **4,29 para 2,27** em atrasos, reconciliados 100% entre 6 gabaritos SQL, pandas, TOM/ADOMD e Playwright (**88 testes + CI**).<br>**EN:** Joins 99,441 real Olist orders with official Central Bank (IPCA, Selic, USD PTAX) and IBGE APIs into an 11-table star schema, 4-page Power BI PBIP (**107 DAX measures**), and bilingual web dashboard (**88 automated tests + CI**). | [Painel ao vivo / Live App](https://balchuna.github.io/painel-ecommerce-macro-br/)<br>[Código & PBIP / Repo](https://github.com/Balchuna/painel-ecommerce-macro-br) |
| **2** | **IDEA OHS Document Automation Platform** *(Produção / Private LGPD)* | **PT:** Sistema comercial em produção para construtora (desde 03/2026) que automatiza emissão em lote Word/PPTX→PDF (certificados NR/PEMT, ordens de serviço, fichas de EPI). Evoluiu de v1 web em **PostgreSQL/Supabase** (RLS e triggers) para desktop **Python/PySide6 + SQLite/SQLAlchemy/Alembic** (10 tabelas) + bot **Telegram (Node.js)** via contrato JSON. Validação de RH (12/172 registros bloqueados), auditoria de **145 trabalhadores / 1.417 registros**, hash **SHA-256**, trilha de auditoria e **301 testes pytest** (100 docs/pessoa em 88 emissões concluídas, 1 erro).<br>**EN:** Commercial production platform automating occupational safety documents (Python/PySide6, SQLite/PostgreSQL, Node.js Telegram bot, **145 workers / 1,417 audited records**, **SHA-256**, **301 pytest tests**). Private repo due to employee PII/LGPD; architecture shown publicly without real data. | [Arquitetura (PT)](https://balchuna.github.io/#idea-sst)<br>[Architecture (EN)](https://balchuna.github.io/?lang=en#idea-sst)<br>[Par público BI/SQL](https://github.com/Balchuna/painel-certificacoes-sst) |
| **3** | **Dungeon-Alchemist Prompt Automation — C# HTTP Bridge & MCP Server** *(Privado / EULA)* | **PT:** Automação de software desktop sem API pública via **plugin C#** (ponte HTTP local com **26 comandos**) + biblioteca **Python stdlib (2.800+ linhas)** + executor idempotente com backups, checkpoints, diário de execução e **12 verificações** pós-gravação + **servidor MCP** acionado por agentes de IA.<br>**EN:** Automates desktop software lacking a public API via a **C# plugin** (26 local HTTP commands), pure-Python stdlib engine (**2,800+ LOC**), idempotent checkpointed runner with 12 post-save checks, and an **MCP server** driven by AI agents. | [Vídeo demo (68s)](https://drive.google.com/file/d/1XWy5Qg8_aGuIpLukzWZnooe488D5ud2G/view)<br>[Arquitetura (PT/EN)](https://balchuna.github.io/?lang=en#dungeon-alchemist-mcp) |

---

### Demais Repositórios Públicos / Additional Public Repositories (CI + Automated Tests)

| Repositório / Repository | Resumo (PT-BR / EN) | Testes & Stack |
|---|---|---|
| [Painel de Certificações SST](https://github.com/Balchuna/painel-certificacoes-sst) | **PT:** Power BI PBIP de 4 páginas (modelo estrela, 7 relações, 27 medidas DAX) para exames e treinamentos em obra fictícia de 150 funcionários, validado contra SQLite e pandas no Excel e Power BI Desktop.<br>**EN:** 4-page Power BI OHS dashboard (synthetic 150-worker dataset, 27 DAX measures) cross-checked against SQLite & pandas. | **297 testes** (pytest + CI) · Power BI, DAX, Power Query, SQL, Python |
| [Radar de Vagas de Dados e TI](https://github.com/Balchuna/radar-vagas-dados) · [ao vivo](https://balchuna.github.io/radar-vagas-dados/) | **PT:** Coleta semanal via GitHub Actions nas APIs públicas Greenhouse, Lever e Ashby (31 empresas) com UPSERT idempotente em SQLite e análises em SQL. Coleta de 16/11/2026: **1.478 vagas ativas** e **91 de dados** (Python 78,0%, SQL 76,9%).<br>**EN:** Weekly GitHub Actions ETL scraping 31 public ATS feeds into SQLite with pure SQL analytics & Chart.js dashboard. | **101 testes** (pytest + CI) · Python, SQL, SQLite, GitHub Actions, Chart.js |
| [Estresse no Trabalho por Setor](https://github.com/Balchuna/estresse-trabalho-jss) | **PT:** Pipeline da Job Stress Scale (17 itens, Alves et al., 2004) com descarte de PII na leitura, anonimização k≥5, quadrantes de Karasek (26% alta exigência), alfa de Cronbach (0,80–0,87), Mann-Whitney e relatório HTML.<br>**EN:** People analytics & LGPD pipeline with PII stripping, k≥5 anonymization, Karasek quadrants, Cronbach's alpha, and Mann-Whitney U. | **54 testes** (pytest + CI) · Python, pandas, SciPy, LGPD |
| [Eva Flights](https://github.com/Balchuna/eva-flights) | **PT:** Agregador multiprovedor de passagens aéreas (4 fontes) com normalizadores testados, trava prévia de quota mensal (100 chamadas), timeout de 12s, degradação graciosa e modo demo sem chaves.<br>**EN:** Multi-provider flight aggregator (4 APIs) with normalized contracts, pre-request quota lock (100/mo), 12s timeout fallback, and zero-key demo mode. | **118 testes** (`node:test` + CI) · Node.js, Express, React, REST APIs |

*Transparência de dados / Data transparency:* `painel-ecommerce-macro-br` utiliza dados públicos reais da Olist (CC BY-NC-SA 4.0) e APIs oficiais do BCB/IBGE; `radar-vagas-dados` usa APIs públicas de recrutamento; `painel-certificacoes-sst` e `estresse-trabalho-jss` utilizam dados sintéticos com semente fixa (nenhum dado pessoal real foi publicado).

**Sites em produção / Production Websites:** [Hope Alívios Terapêuticos](https://hopefisioterapia.netlify.app) (cliente real — Next.js 16, TypeScript, Tailwind v4) · [Wilton Alves Jiu-Jitsu](https://portfolio-wilton.netlify.app/) (landing page bilíngue PT/EN).

---

### Disciplina de Engenharia, Stack & Formação / Engineering Discipline, Stack & Education

- **Qualidade verificável / Verifiable quality:** **959 testes automatizados** no total (658 em 5 repositórios públicos com CI no GitHub Actions + 301 no sistema privado da IDEA). Cada repositório público traz `docs/COMO-FUNCIONA.md`, `docs/DECISOES.md` e resumo em inglês no README.
- **Dados & BI:** Power BI (Power Query/M, DAX, Star Schema, PBIP), SQL (PostgreSQL/Supabase, SQLite, SQLAlchemy, Alembic; portabilidade ANSI para SQL Server/T-SQL e MySQL), Excel avançado, Python (pandas, SciPy, PyMuPDF, Chart.js).
- **Engenharia, APIs & Suporte Técnico:** Python, Node.js, Express, TypeScript, React, Next.js, Tailwind CSS, C#, APIs REST/JSON, Telegram Bot API, servidores MCP, pytest, `node:test`, Git, GitHub Actions, troubleshooting de logs/APIs e prática em ambiente sandbox ITSM/CRM (Zendesk, Jira Service Management, HubSpot).
- **IA Aplicada:** desenvolvimento assistido por agentes (Claude Code — cursos da Anthropic concluídos, Codex, OpenCode) com revisão orientada a testes automatizados.
- **Formação / Education:** Administrador de Banco de Dados (Qualificação Profissional — IFRS, em andamento, prev. 01/2027) · Bacharelado em Psicologia (FMU, 06/2026) · Análise de Dados e Power BI (Microsoft Learn / Fundação Bradesco) · Intercâmbio em Portugal (2018–2019).
- **Idiomas / Languages:** Português (nativo) · Inglês (fluente escrito e falado — 90% / percentil 97) · Espanhol (básico).
