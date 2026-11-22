## Rafael Balchuna

Analista de Dados e Desenvolvedor de Automação em São Paulo. Trabalho com SQL, Python, Power BI, APIs REST e Web (Node.js, React, Next.js, TypeScript).

**Portfólio unificado (PT/EN):** [balchuna.github.io](https://balchuna.github.io/) · **LinkedIn:** [linkedin.com/in/rafael-balchuna](https://www.linkedin.com/in/rafael-balchuna)

Sou formado em Psicologia pela FMU (2026), concluí Análise de Dados e Power BI (Microsoft Learn / Fundação Bradesco) e os cursos da Anthropic sobre Claude Code, e curso Administrador de Banco de Dados no IFRS. Desde março de 2026 desenvolvo e mantenho o sistema de automação documental e banco de dados de Segurança e Saúde do Trabalho de uma construtora (Python/PySide6, SQLite/PostgreSQL, bot Telegram em Node.js e 301 testes automatizados).

*Junior Data Analyst & Python Automation Developer based in São Paulo, Brazil (UTC-3). Full bilingual portfolio at [balchuna.github.io](https://balchuna.github.io/) — every public repository below includes an English summary in its README.*

---

### Projetos públicos (código, testes automatizados e CI)

| Projeto | Do que se trata | Testes & Stack |
|---|---|---|
| [Radar de Vagas de Dados e TI](https://github.com/Balchuna/radar-vagas-dados) · [painel ao vivo](https://balchuna.github.io/radar-vagas-dados/) | Coleta semanal automática via GitHub Actions nas APIs públicas (Greenhouse, Lever, Ashby; 31 empresas) com UPSERT idempotente em SQLite e análises em SQL. Coleta agendada de 16/11/2026: **1.478 vagas ativas** e **91 de dados** (Python 78,0%, SQL 76,9%). | **101 testes** (pytest + CI) · Python, SQL, SQLite, Chart.js |
| [Painel de Certificações SST](https://github.com/Balchuna/painel-certificacoes-sst) | Painel Power BI de 4 páginas (modelo estrela, 7 relações, 27 medidas DAX) para controle de exames e treinamentos de SST em obra fictícia de 150 funcionários. Todos os números são validados contra gabarito em SQL (SQLite) e pandas, abrindo Excel e Power BI Desktop nos testes. | **297 testes** (pytest + CI) · Power BI, DAX, Power Query, SQL, Python |
| [Estresse no Trabalho por Setor](https://github.com/Balchuna/estresse-trabalho-jss) | Pipeline analítico da Job Stress Scale (17 itens, Alves et al., 2004) com descarte de PII na leitura, anonimização k≥5 por setor, quadrantes de Karasek, alfa de Cronbach (0,80–0,87), Mann-Whitney e relatório HTML. | **54 testes** (pytest + CI) · Python, pandas, SciPy, LGPD |
| [Eva Flights](https://github.com/Balchuna/eva-flights) | Buscador multiprovedor de passagens aéreas que integra 4 fontes com normalizadores testados, trava prévia de quota mensal (100 chamadas), timeout de 12s, degradação graciosa e modo demo sem chaves. | **118 testes** (`node:test` + CI) · Node.js, Express, React, Vite |

Os dados dos projetos de SST e de estresse são sintéticos, gerados com semente fixa. Nenhum dado pessoal real foi publicado.

### Outras entregas reais & protótipos

- **Automação SST — IDEA Sistemas Construtivos (cliente real, código privado LGPD):** emissão em lote Word/PPTX→PDF, SQLite/SQLAlchemy/Alembic (10 tabelas), validação de RH (12/172 bloqueados), bot Telegram (Node.js) e **301 testes pytest**. Em uma instalação: 100 documentos por pessoa em 88 emissões concluídas (1 erro).
- **Dungeon-Alchemist por Prompt (privado por EULA):** plugin C# (ponte HTTP local com 26 comandos) + biblioteca Python pura + servidor MCP — [vídeo de demonstração (68s)](https://drive.google.com/file/d/1XWy5Qg8_aGuIpLukzWZnooe488D5ud2G/view).
- **Sites em produção:** [Hope Alívios Terapêuticos](https://hopefisioterapia.netlify.app) (cliente real — Next.js 16, TypeScript, Tailwind v4) · [Wilton Alves Jiu-Jitsu](https://portfolio-wilton.netlify.app/) (landing page bilíngue PT/EN).

### Como trabalho nos projetos

Os números dos READMEs saem de comandos e consultas verificáveis. Ao todo são **871 testes automatizados** somando os repositórios públicos (570) e o sistema privado (301), todos os projetos públicos rodam CI no GitHub Actions, e cada repositório traz `docs/COMO-FUNCIONA.md` e `docs/DECISOES.md`.

### Ferramentas

- **Dados & BI:** SQL (SQLite, PostgreSQL/Supabase, SQLAlchemy, Alembic), Power BI (Power Query, DAX, PBIP), Excel avançado, Python (pandas, SciPy, PyMuPDF, Chart.js).
- **Engenharia, APIs & Web:** Python, Node.js, Express, TypeScript, React, Next.js, Tailwind CSS, C#, APIs REST, Telegram Bot API, servidores MCP, pytest, `node:test`, Git, GitHub Actions.
- **IA Aplicada:** desenvolvimento assistido por agentes (Claude Code — cursos da Anthropic concluídos, Codex, OpenCode) com revisão rigorosa por testes automatizados, subagentes e skills.

Português (nativo) · Inglês (fluente — 90% / percentil 97).
