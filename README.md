# Agentes-Power-

Dois agentes especialistas para empresários, prontos para uso no **Claude Code** (e adaptáveis a Claude Projects):

| Agente | Arquivo | Especialidade |
|---|---|---|
| 🧮 **Meu Contador** | `.claude/agents/contador.md` | Contabilidade (CPC/IFRS), tributos, regimes (Simples/Presumido/Real), Reforma Tributária IBS/CBS, reforma do IR, folha, SPED, planejamento tributário, comércio exterior, China e Alemanha |
| ⚖️ **Meu Advogado** | `.claude/agents/advogado.md` | Tributário consultivo e contencioso (CARF, STF/STJ), societário, M&A, contratos nacionais e internacionais, trabalhista, LGPD, compliance, recuperação judicial, PI, sucessão, China e Alemanha/UE |

Os dois trabalham em conjunto: o Contador cuida de números e enquadramento fiscal; o Advogado, de fundamentos jurídicos, estratégia, riscos e minutas.

## Base de conhecimento

Pesquisa extensa em fontes primárias (legislação, Receita Federal, STF/STJ/CARF, BCB, autoridades da China e da Alemanha, UE, OCDE e grandes consultorias):

```
conhecimento/
├── contador/brasil-tributario-contabil.md          # tributos, regimes, reforma, obrigações, CPC, planejamento
├── advogado/brasil-juridico-empresarial.md         # societário, contratos, contencioso, teses, trabalhista, LGPD...
└── internacional/
    ├── tributacao-internacional-comex.md           # tratados, remessas, câmbio, preços de transferência, comex
    ├── china.md                                    # investimento, tributos, contabilidade, contratos, PI, dados
    └── alemanha.md                                 # GmbH, tributos, HGB, trabalho, UE, Mercosul–UE
```

Itens marcados com ⚠️ são pontos que mudam com frequência ou dependem de regulamentação — os agentes são instruídos a **reconfirmar na web** antes de afirmar.

## Como usar (Claude Code)

Abra o Claude Code na pasta do repositório e peça diretamente:

```
Use o agente contador: faturo R$ 3,6 mi/ano com serviços de TI em SP, folha de R$ 900 mil. Qual o melhor regime em 2027?
Use o agente advogado: revise este contrato de fornecimento com uma fábrica na China.
```

Entregáveis (pareceres, minutas, simulações) são salvos em `entregas/`.

## Usar em Claude.ai (Projects)

Crie um Project, cole o conteúdo de `contador.md` ou `advogado.md` (sem o cabeçalho `---`) nas instruções e envie os arquivos de `conhecimento/` como arquivos do projeto.

## Aviso

Os agentes oferecem orientação técnica de alto nível, mas não substituem um contador com CRC ou advogado com OAB para atos formais (assinar balanços, transmitir declarações, peticionar). A legislação muda — confira a vigência das normas para decisões relevantes.
