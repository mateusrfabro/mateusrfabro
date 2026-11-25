# Mateus Fabro — Engenheiro de Dados & Analytics

**Construo o pipeline e o produto em volta dele — Python · SQL · TypeScript · agentes de IA**

🟢 **Em busca de vaga** — Em busca de vaga de engenharia de dados, analytics engineering ou desenvolvimento de produto — PJ ou CLT, remoto. Converso também sobre projeto de escopo fechado. O jeito mais rápido é o e-mail.

- Site (projetos, números medidos e lições de casos reais): https://mateusfabro.vercel.app
- Currículo: [PT](https://mateusfabro.vercel.app/curriculo/mateus-fabro-pt.pdf) · [EN](https://mateusfabro.vercel.app/curriculo/mateus-fabro-en.pdf)
- LinkedIn: https://www.linkedin.com/in/mateusrfabro
- E-mail: mateusrfabro@hotmail.com

## O que eu faço

- Engenheiro de dados e analytics com experiência em iGaming e crédito. Construo pipelines ETL em Python e SQL orquestrados com Prefect, modelo a camada gold e entrego painéis em Power BI. Migrei a camada de consumo de um data lake de 3,07 bilhões de registros para lakehouse (S3 Tables/Iceberg) e reduzi uma consulta crítica de 240 s para 21 s. Atuei na Super Nova Gaming / MultiBet de out/2025 até o encerramento da empresa, em nov/2026.

## Projetos

| Projeto | O que é | Status | Código |
|---|---|---|---|
| **Avisa Edital** | Alertas de convocação, nomeação e edital de concurso para médicos no Paraná e em São Paulo, no WhatsApp ou no Telegram, filtrados por especialidade e região. | No ar desde agosto de 2026; operação diária desde outubro | `avisa-edital` (privado) |
| **Pingado** | Sistema de cafeteria: balcão em três toques, comanda, fiado, estoque e resultado do mês. | Em produção desde setembro de 2026; mensalidade ativa, duas lojas | `cafesaas` (privado) |
| **Nous Clinical** | Gestão de clínicas: agenda, prontuário, exames, financeiro e retorno de pacientes. | Última versão do produto em 06/10/2026; depois só manutenção do repositório | [nous-clinical](https://github.com/mateusrfabro/nous-clinical) |
| **Aggron** | Compra cooperativa para hamburguerias: pedidos somados em rodadas e fornecedores disputando o lote. | MVP completo; parado desde 28/05/2026 (depois só manutenção do repositório) | [poolcompras](https://github.com/mateusrfabro/poolcompras) |
| **DumpAI** | A IA escolhe as 10 melhores de 30 fotos para um photo dump de Instagram. | No ar; faturamento baixo | [dumpai](https://github.com/mateusrfabro/dumpai) |
| **Secretária de WhatsApp** | Recepcionista de WhatsApp com agenda real para profissionais autônomos. | Piloto parado (autorização do Google) | `secretaria-ia` (privado) |
| **SaaS de crédito (sob NDA)** | Gestão de crédito multi-tenant: painel da equipe e portal do cliente como PWA. | Piloto no ar desde outubro de 2026 | `credito-saas` (privado) |
| **Portais de conteúdo com dados oficiais** | Cinco portais estáticos de finanças e direitos, com indicadores que se atualizam sozinhos a partir de fontes oficiais. | No ar desde outubro de 2026; monetização em avaliação | `guiadocredito`, `radardoinvestidor`, `central-do-trabalhador`, `usmoneybrasil`, `mydollarpilot` (privados) |
| **diario-mateus-fabro** | Site profissional e currículo gerados de um JSON só, para pessoas e agentes de IA: HTML, PDF, JSON Resume, llms.txt e servidor MCP | — | [diario-mateus-fabro](https://github.com/mateusrfabro/diario-mateus-fabro) |
| **lab-ia** | Laboratório local de IA: Ollama + PyTorch numa RTX 4060 — agente com ferramentas, QLoRA, ML tabular | — | [lab-ia](https://github.com/mateusrfabro/lab-ia) |

Trabalho anterior: Super Nova Gaming / MultiBet (Grupo PGX), out/2025 – nov/2026 — repositórios privados (dados da empresa).

## Engenharia de agentes

- Montei 25 agentes Claude Code (10 de dados + 15 gerais) e 5 skills próprias (tenant, multimoeda, memória, PRD e páginas), com gate obrigatório (extração → boas práticas → auditoria → entrega) e hooks que bloqueiam git destrutivo e commit sem teste.
- Mantenho memória em três camadas (projeto → global → export): 125 lições registradas, cada uma com origem, motivo e forma de aplicar, e um script que prova que o índice não esqueceu nenhuma.
- API da Anthropic em produção em dois produtos (IA multimodal no DumpAI; chatbot clínico no Nous Clinical), agente LangChain/n8n na secretária de WhatsApp e laboratório local (Ollama + PyTorch numa RTX 4060) para saber o que roda sem API.

## Como trabalho

- **Memória em camadas.** Cada projeto tem um índice de memória com o que é armadilha viva. O que vale para outro projeto sobe para uma memória global: lição com origem, motivo e forma de aplicar.
- **Um gate fecha a promoção.** Promover uma lição é escrevê-la no disco, no índice legível e no índice de máquina. Esse passo falhou duas vezes sem sintoma; hoje um script confere os três e tem um modo que prova que ele sabe ficar vermelho.
- **Mutação como hábito.** 66 dos 717 commits meus no Avisa Edital registram teste de mutação: o defeito é reintroduzido e o teste tem de reprovar antes de o conserto valer.
- **Agentes com papel, não com autonomia.** 25 agentes especializados (10 do squad de dados e 15 gerais: qualidade, segurança, testes, UX, revisão de conteúdo, growth) trabalham em paralelo. O que os revisores acham é reproduzido antes de virar mudança.
- **Onde paramos.** Todo projeto tem um arquivo de retomada que a próxima sessão lê primeiro: estado, decisões de quem é dono do negócio e pendências, com data.

_README gerado de `conteudo/dados.json` em 2026-11-05 pelo repositório [diario-mateus-fabro](https://github.com/mateusrfabro/diario-mateus-fabro)._
