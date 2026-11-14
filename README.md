## Rafael Balchuna

**Analista de Dados Júnior** · SQL · Python · Power BI · integração de APIs

Formado em Psicologia (FMU, 2026), em transição para Análise de Dados e cursando Administrador de Banco de Dados no IFRS. Desde 2026, automatizo a emissão de documentos de Segurança e Saúde do Trabalho para uma empresa de construção: banco relacional, importação de planilhas com validação e geração de documentos em lote.

Gosto de perguntas que se respondem com dados limpos e contas que dá para conferir.

*Junior data analyst from São Paulo, Brazil. Each project below has an English summary in its README.*

### Projetos

| Projeto | O que responde | Ferramentas |
|---|---|---|
| [**Radar de Vagas de Dados e TI**](https://github.com/Balchuna/radar-vagas-dados) · [página](https://balchuna.github.io/radar-vagas-dados/) | Quais skills as vagas de dados pedem, e o que muda nas vagas para quem está começando? Coleta semanal nas APIs públicas de recrutamento de 31 empresas, com UPSERT idempotente e todas as análises num arquivo SQL. | Python, SQL, SQLite, GitHub Actions, Chart.js |
| [**Painel de Certificações SST**](https://github.com/Balchuna/painel-certificacoes-sst) | Numa obra de cerca de 150 funcionários, quem está irregular hoje e o que vence em 30, 60 e 90 dias? Um gabarito em SQL diz qual número cada visual tem de mostrar, e os testes conferem o painel no próprio Power BI Desktop. | Power BI, DAX, Power Query, SQL, Python |
| [**Estresse no Trabalho por Setor**](https://github.com/Balchuna/estresse-trabalho-jss) | Onde estão os grupos de maior risco psicossocial, pela Job Stress Scale? Limpeza, anonimização, pontuação, quadrantes de Karasek, alfa de Cronbach e comparação entre unidades. | Python, pandas, SciPy, Jupyter |
| [**Eva Flights**](https://github.com/Balchuna/eva-flights) | Integra fontes gratuitas de preços de passagens numa busca só, com a idade de cada preço, controle de quota por fonte e falha de uma fonte que não derruba a busca. | Node.js, Express, React, APIs REST |

Os dados dos projetos de SST e de estresse são **sintéticos**, gerados com semente fixa. Nenhum dado pessoal real é publicado.

### Como os projetos são feitos

- **Números conferíveis:** cada resultado no README aponta para o comando ou a consulta que o gera.
- **Testes e CI:** todos têm testes automatizados (pytest ou `node:test`) rodando no GitHub Actions.
- **Decisões escritas:** `docs/COMO-FUNCIONA.md` explica o projeto sem jargão, e, nos três projetos de dados, `docs/DECISOES.md` registra cada escolha com o motivo.
- **Coleta responsável:** termos de uso e `robots.txt` conferidos antes de usar uma fonte, com limite de requisições.

### Ferramentas

**Dados:** SQL (SQLite e PostgreSQL), Python (pandas, requests, SciPy), Power BI (DAX e Power Query), Excel
**Engenharia:** Git e GitHub Actions, pytest, Node.js, React, APIs REST, SQLAlchemy e Alembic
**Idiomas:** português nativo, inglês fluente
