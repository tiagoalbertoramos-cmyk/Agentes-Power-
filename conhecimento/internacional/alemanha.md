# Alemanha — Guia de Direito Empresarial, Tributação e Contabilidade para Empresários Brasileiros

> **Base de conhecimento para os agentes Contador e Advogado.**
> Data de referência: **22/11/2026**. Jurisdição: República Federal da Alemanha (*Bundesrepublik Deutschland*) e normas da União Europeia com efeito no país.
> Convenção: **⚠️ verificar vigência** = dado não confirmado em fonte primária, sujeito a alteração legislativa recente ou com divergência entre fontes. Valores em euro (€). "§" = parágrafo/artigo da lei alemã citada.
> Este material é técnico-informativo; não substitui parecer de *Steuerberater* (consultor tributário habilitado) ou *Rechtsanwalt* (advogado) alemão.

---

## Sumário

1. [Formas societárias e constituição](#1-formas-societárias-e-constituição)
2. [Tributação empresarial](#2-tributação-empresarial)
3. [IVA — Umsatzsteuer](#3-iva--umsatzsteuer)
4. [Contabilidade, demonstrações e obrigações acessórias](#4-contabilidade-demonstrações-e-obrigações-acessórias)
5. [Relação tributária Brasil–Alemanha](#5-relação-tributária-brasilalemanha)
6. [Direito do trabalho, previdência e imigração](#6-direito-do-trabalho-previdência-e-imigração)
7. [Contratos e solução de disputas](#7-contratos-e-solução-de-disputas)
8. [UE e compliance](#8-ue-e-compliance)
9. [Acordo Mercosul–União Europeia](#9-acordo-mercosulunião-europeia)
10. [Checklists práticos](#10-checklists-práticos)
11. [Tabela-resumo de alíquotas e prazos](#11-tabela-resumo-de-alíquotas-e-prazos)
12. [Glossário alemão–português](#12-glossário-alemãoportuguês)
13. [Mapa de incertezas (⚠️)](#13-mapa-de-incertezas-)

---

## 1. Formas societárias e constituição

### 1.1 Visão geral das formas jurídicas (*Rechtsformen*)

| Forma | Base legal | Capital mínimo | Responsabilidade dos sócios | Uso típico para brasileiros |
|---|---|---|---|---|
| **GmbH** (*Gesellschaft mit beschränkter Haftung* — sociedade de responsabilidade limitada) | GmbHG | €25.000 (*Stammkapital*, §5 GmbHG); integralização mínima de **metade** (€12.500) antes do registro (§7(2) GmbHG), cada quota ≥ 25% integralizada | Limitada ao capital | **Padrão** para subsidiária operacional |
| **UG (haftungsbeschränkt)** (*Unternehmergesellschaft* — "mini-GmbH") | §5a GmbHG | €1 (sem limite inferior prático); capital **integralizado à vista**, sem aporte em bens (*Sacheinlage* vedada) | Limitada | Start-ups, estruturas de baixo custo; deve reter **25% do lucro líquido anual** em reserva legal (*gesetzliche Rücklage*) até atingir €25.000 e converter-se em GmbH |
| **AG** (*Aktiengesellschaft* — sociedade anônima) | AktG | €50.000 (*Grundkapital*, §7 AktG); integralização mínima de 25% do valor nominal + ágio integral (§36a AktG) | Limitada | Grandes grupos, IPO; governança dual (*Vorstand* — diretoria; *Aufsichtsrat* — conselho fiscal/supervisão obrigatório) |
| **SE** (*Societas Europaea*) | Reg. (CE) 2157/2001 + SEAG | €120.000 | Limitada | Grupos pan-europeus |
| **KG** (*Kommanditgesellschaft* — comandita simples) | §§161 ss. HGB | Sem mínimo | *Komplementär* (sócio comanditado): ilimitada; *Kommanditist* (comanditário): até a *Haftsumme* registrada | Estruturas familiares / fundos |
| **GmbH & Co. KG** | HGB + GmbHG | GmbH como comanditada (€25.000) + KG | Na prática limitada | Muito popular: transparência fiscal da KG para IR, com responsabilidade limitada via GmbH; *Gewerbesteuer* incide sobre a KG |
| **OHG** (*offene Handelsgesellschaft* — sociedade em nome coletivo) | §§105 ss. HGB | Sem mínimo | Ilimitada e solidária | Raramente recomendada |
| **GbR** (*Gesellschaft bürgerlichen Rechts* — sociedade civil) | §§705 ss. BGB (reformados pela MoPeG, em vigor desde **01/01/2024**) | Sem mínimo | Ilimitada | Joint ventures simples; agora pode registrar-se no *Gesellschaftsregister* como **eGbR** (obrigatório para adquirir imóveis/quotas) |
| **Einzelunternehmen / e.K.** (*eingetragener Kaufmann*) | HGB | Sem mínimo | Ilimitada (pessoa física) | Empresário individual |
| **Zweigniederlassung** (filial registrada) | §§13–13h HGB (filial de sociedade estrangeira: §13d e ss.) | Não tem capital próprio | Responsabilidade é da matriz brasileira | Operação comercial sem nova pessoa jurídica |
| **Repräsentanz** (escritório de representação) | Sem regime legal específico; GewO | — | Matriz | Apenas atividades preparatórias/auxiliares (marketing, contato); não pode concluir contratos |

**Pontos críticos:**
- **Zweigniederlassung × GmbH:** a filial não limita a responsabilidade da matriz brasileira; é um *Betriebsstätte* (estabelecimento permanente, §12 AO) sujeito a KSt (contribuinte não residente com renda doméstica, §2 nº 1 KStG c/c §49 EStG) e GewSt. Registro obrigatório no *Handelsregister* se a matriz for sociedade comercial (§13d HGB), com apresentação de documentos societários traduzidos e apostilados. Lucro da filial remetido à matriz **não sofre retenção** na fonte alemã (diferente de dividendos de GmbH), o que pode ser vantajoso na ausência de tratado (ver Seção 5).
- **Repräsentanz:** risco de configurar estabelecimento permanente (*Betriebsstätte*, §12 AO) ou representante permanente (*ständiger Vertreter*, §13 AO) se houver poder de fechar contratos — **sem tratado com o Brasil**, aplicam-se só os conceitos domésticos (mais amplos que o art. 5 do Modelo OCDE). Exige *Gewerbeanmeldung* (registro de atividade) na prefeitura.
- **GmbH & Co. KG**: transparência fiscal para KSt/ESt (cada sócio tributa sua parte), mas a KG é contribuinte da GewSt. Com sócio brasileiro, a participação na KG gera estabelecimento permanente do sócio na Alemanha. A opção pela tributação como corporação (*Optionsmodell*, §1a KStG, desde 2022) é possível.

### 1.2 Processo de constituição de uma GmbH

| Etapa | Descrição | Base legal | Prazo/custo indicativo |
|---|---|---|---|
| 1. Contrato social (*Gesellschaftsvertrag* / *Satzung*) | Escritura **notarial obrigatória** (*notarielle Beurkundung*). Possível usar o *Musterprotokoll* (modelo simplificado) para até 3 sócios e 1 diretor | §2 GmbHG | Custos notariais conforme GNotKG; com *Musterprotokoll* e capital €25.000, ordem de €300–€900 ⚠️ verificar |
| 2. Nomeação do *Geschäftsführer* | Gerente/administrador; pode ser estrangeiro e não residente | §6 GmbHG | Na escritura ou ata |
| 3. Abertura de conta bancária e integralização | ≥ €12.500 (e ≥ 25% de cada quota) depositados em conta da *GmbH in Gründung* | §7(2) GmbHG | Bancos alemães exigem KYC (GwG) rigoroso; frequentemente o maior gargalo para não residentes |
| 4. Requerimento de registro no *Handelsregister* | Notário envia eletronicamente (formato XJustiz) ao *Amtsgericht* (tribunal de registro) | §§7, 8 GmbHG; §12 HGB | 1–4 semanas; taxas judiciais ~€150–€300 |
| 5. Inscrição no *Transparenzregister* (registro de beneficiários finais) | Desde a reforma de 2021 (TraFinG Gw) é "registro completo" (*Vollregister*): toda pessoa jurídica deve inscrever o *wirtschaftlich Berechtigter* (beneficiário final, >25% capital/votos ou controle) | §§18–20 GwG | Imediatamente após a constituição; multas por omissão |
| 6. *Gewerbeanmeldung* | Registro da atividade empresarial na prefeitura (*Gewerbeamt*) | §14 GewO | ~€20–€60; antes de iniciar atividade |
| 7. Registro fiscal | *Fragebogen zur steuerlichen Erfassung* (questionário de inscrição fiscal), via ELSTER, dentro de **1 mês** do início da atividade; recebe *Steuernummer* e, se requerido, **USt-IdNr** (número de IVA intra-UE, emitido pelo BZSt) | §138 AO; §27a UStG | 2–6 semanas |
| 8. Outros | Câmara de comércio (*IHK*) — filiação compulsória e contribuição; *Berufsgenossenschaft* (seguro de acidentes do trabalho) se houver empregados; *Betriebsnummer* na Bundesagentur für Arbeit | IHKG; SGB VII | — |

**Constituição online (DiRUG):** desde **01/08/2022** (*Gesetz zur Umsetzung der Digitalisierungsrichtlinie* — DiRUG, transpondo a Diretiva (UE) 2019/1151) é possível constituir GmbH/UG integralmente por **videoconferência notarial** (sistema da *Bundesnotarkammer*), com identificação eletrônica (eID). Desde **01/08/2023** (DiREG) estendido a constituições com aporte em bens (*Sachgründung*) e a mais atos registrais. ⚠️ Na prática, brasileiros sem documento de identidade eletrônico compatível com eIDAS/ eID alemão frequentemente **não conseguem** usar o procedimento; alternativa: escritura em consulado alemão no Brasil ou em notário brasileiro com apostila — *atenção:* a equivalência de escritura estrangeira para constituição de GmbH é controvertida; o caminho seguro é notário alemão (presencial ou por procuração notarial apostilada).

**Wirtschafts-Identifikationsnummer (W-IdNr):** número único federal para empresas, implementado gradualmente pelo BZSt desde **novembro/2024** (§139c AO); ⚠️ cronograma de uso obrigatório a verificar.

### 1.3 Geschäftsführer (administrador) e responsabilidade

- Representação: §35 GmbHG; poderes ilimitados perante terceiros (§37(2) GmbHG).
- **Dever de diligência:** "diligência de um empresário ordenado" (*Sorgfalt eines ordentlichen Geschäftsmannes*, §43(1) GmbHG); responsabilidade solidária perante a sociedade (§43(2)). *Business Judgment Rule* (§93(1) frase 2 AktG, aplicada analogicamente à GmbH).
- **Responsabilidade tributária pessoal:** §§34, 69 AO — o administrador responde por tributos não recolhidos por culpa grave (ex.: retenções de IR sobre salários — *Lohnsteuer*, IVA).
- **Contribuições previdenciárias:** não recolher a parte do empregado é crime (§266a StGB).
- **Inabilitação:** condenações por crimes de insolvência, fraude etc. impedem o exercício (§6(2) GmbHG).
- **Residência:** não há exigência de residência nem de nacionalidade da UE; porém, para cidadão não-UE trabalhar fisicamente na Alemanha como GF é preciso título de residência adequado (ver 6.8).
- **Previdência do GF-sócio:** GF com participação ≥ 50% (ou minoria de bloqueio) normalmente **não** é segurado obrigatório (*sozialversicherungsfrei*); casos-limite → *Statusfeststellungsverfahren* (§7a SGB IV).

### 1.4 Insolvência (InsO) e reestruturação (StaRUG)

| Tema | Regra | Base legal |
|---|---|---|
| Motivos de insolvência | *Zahlungsunfähigkeit* (insolvência de caixa); *Überschuldung* (passivo a descoberto com prognóstico negativo de continuidade em **12 meses**); *drohende Zahlungsunfähigkeit* (insolvência iminente — prognóstico de **24 meses**, só faculta o pedido) | §§17, 18, 19 InsO |
| **Dever de requerer** (*Insolvenzantragspflicht*) | Sem culpa, sem demora, no máximo **3 semanas** após a *Zahlungsunfähigkeit* e **6 semanas** após a *Überschuldung* | §15a(1) InsO (redação SanInsFoG, desde 01/01/2021) |
| Sanção | Crime de *Insolvenzverschleppung* (atraso no pedido): até 3 anos de prisão (dolo) | §15a(4) InsO |
| Pagamentos após insolvência | GF responde pessoalmente por pagamentos feitos após o surgimento do motivo de insolvência, salvo os compatíveis com a diligência | §15b InsO (substituiu §64 GmbHG) |
| *Eigenverwaltung* | Autogestão sob supervisão de *Sachwalter* | §§270 ss. InsO |
| **StaRUG** | *Unternehmensstabilisierungs- und -restrukturierungsgesetz*: reestruturação pré-insolvencial (transposição da Diretiva (UE) 2019/1023), em vigor desde **01/01/2021**. Plano de reestruturação com *cram-down* entre classes de credores, aplicável em caso de **insolvência iminente**; dever do GF de monitorar riscos de crise (§1 StaRUG) | StaRUG |
| Juízo | *Insolvenzgericht* no *Amtsgericht* | §2 InsO |

**Para o Advogado:** a GmbH controlada por grupo brasileiro com *Patronatserklärung* (carta de conforto) ou *Rangrücktritt* (subordinação de empréstimos de sócio — §39(2) InsO) pode evitar a *Überschuldung*. Empréstimos de sócios são subordinados na insolvência (§39(1) nº 5 InsO) e pagamentos ao sócio no ano anterior ao pedido são anuláveis (§135 InsO).

**Fontes (Seção 1):**
- https://www.gesetze-im-internet.de/gmbhg/
- https://www.gesetze-im-internet.de/aktg/
- https://www.gesetze-im-internet.de/hgb/
- https://www.gesetze-im-internet.de/inso/
- https://www.gesetze-im-internet.de/starug/
- https://www.gesetze-im-internet.de/gwg_2017/
- https://www.gtai.de/en/invest/business-location-germany/business-setup-in-germany
- https://www.handelsregister.de
- https://www.transparenzregister.de
- https://www.bzst.de

---

## 2. Tributação empresarial

### 2.1 Imposto de renda da pessoa jurídica (*Körperschaftsteuer* — KSt)

- **Alíquota:** **15%** (§23(1) KStG), até o período de apuração (*Veranlagungszeitraum* — VZ) **2027**.
- **Solidaritätszuschlag** (adicional de solidariedade — "Soli"): **5,5% sobre o KSt** devido (§4 SolZG) → 0,825% do lucro. Total KSt + Soli = **15,825%**. O Soli para pessoas jurídicas permanece integral (o Tribunal Constitucional Federal — BVerfG — julgou constitucional em **26/03/2025**, 2 BvR 1505/20).
- **Contribuintes:** sociedades com sede (*Sitz*) ou administração efetiva (*Ort der Geschäftsleitung*) na Alemanha — tributação em bases mundiais (§1 KStG); não residentes apenas sobre rendas domésticas (§2 KStG c/c §49 EStG).

**Reforma 2025 — *Gesetz für ein steuerliches Investitionssofortprogramm zur Stärkung des Wirtschaftsstandorts Deutschland* ("Investitionsbooster"):** publicada no **BGBl. 2025 I Nr. 161 de 18/07/2025**, em vigor desde 19/07/2025:

| Medida | Conteúdo | Vigência |
|---|---|---|
| Redução do KSt | 15% → **14% (2028), 13% (2029), 12% (2030), 11% (2031), 10% (2032 em diante)** — redução de 1 p.p. por ano | VZ 2028–2032 (§23(1) KStG nova redação) |
| Depreciação degressiva (*degressive AfA*) | Bens móveis do ativo imobilizado adquiridos/produzidos entre **01/07/2025 e 31/12/2027**: até **3× a taxa linear, máximo 30% ao ano** sobre o saldo residual | §7(2) EStG |
| Veículos elétricos | Depreciação especial: **75% no ano de aquisição**, depois 10%, 5%, 5%, 3%, 2% (veículos adquiridos 01/07/2025–31/12/2027) | §7(2a) EStG ⚠️ verificar escala |
| Thesaurierungsbegünstigung | Alíquota de lucros retidos de empresas individuais/sociedades de pessoas (§34a EStG) reduzida de 28,25% → 27% (2028–2029), 26% (2030–2031), 25% (2032) | §34a EStG ⚠️ verificar escala exata |
| Pesquisa (*Forschungszulage*) | Base máxima elevada para €12 milhões a partir de 2026 | FZulG |

Combinação com a GewSt: em 2032, carga média nominal ≈ **10,55% + ~14% = ~24,5–25%** ⚠️ (estimativa; depende do *Hebesatz*).

### 2.2 Imposto municipal sobre atividade empresarial (*Gewerbesteuer* — GewSt)

- **Cálculo:** lucro tributável ajustado (*Gewerbeertrag*) × **Steuermesszahl 3,5%** (§11(2) GewStG) × **Hebesatz** municipal (multiplicador, §16 GewStG).
- **Hebesatz mínimo legal: 200%** (§16(4) GewStG) → GewSt mínima efetiva de **7%**. Exemplos (⚠️ verificar Hebesatz 2026 de cada município): Berlim 410%, Hamburgo 470%, Munique 490%, Frankfurt 460%, Colônia 475%, Düsseldorf 440%; municípios-paraíso como Monheim am Rhein 250% ⚠️ e Grünwald 240% ⚠️.
- **Adições (*Hinzurechnungen*, §8 GewStG):** 25% da soma de despesas de financiamento (juros integrais; 20% de aluguéis de bens móveis; 50% de aluguéis de imóveis; 25% de royalties/licenças) que exceda **€200.000** (franquia).
- **Exclusões (*Kürzungen*, §9 GewStG):** 1,2% do valor unitário de imóveis próprios; dividendos de participações ≥ 15% no início do ano (*gewerbesteuerliches Schachtelprivileg*, §9 nº 2a/7 GewStG); lucros de estabelecimentos permanentes no exterior (§9 nº 3).
- **Franquia (*Freibetrag*)** de €24.500 apenas para pessoas físicas e sociedades de pessoas (§11(1) GewStG) — não se aplica a GmbH.
- **Não dedutível** da base do KSt nem da própria GewSt (§4(5b) EStG). Para pessoas físicas/sócios de sociedades de pessoas, crédito do GewSt contra ESt até 4× o *Messbetrag* (§35 EStG).

### 2.3 Carga combinada típica (2026)

| Hebesatz | GewSt efetiva | KSt + Soli | **Total** |
|---|---|---|---|
| 200% (mínimo) | 7,00% | 15,825% | **22,83%** |
| 400% | 14,00% | 15,825% | **29,83%** |
| 410% (Berlim) | 14,35% | 15,825% | **30,18%** |
| 490% (Munique) | 17,15% | 15,825% | **32,98%** |

Média nacional usualmente citada: **~29,9–30%** (PwC Worldwide Tax Summaries).

### 2.4 Regras de base de cálculo

| Regra | Conteúdo | Base legal |
|---|---|---|
| **Zinsschranke** (limitação de juros — "interest barrier") | Despesa líquida de juros dedutível até **30% do EBITDA fiscal**; **Freigrenze** (limite de isenção) de **€3 milhões** de despesa líquida; exceções (*Konzernklausel* para entidade não pertencente a grupo; *Escape-Klausel* de equity ratio) restringidas a partir de 2024 (Wachstumschancengesetz: conceito de "juros" ampliado; carry-forward de EBITDA) | §4h EStG; §8a KStG |
| Juros entre partes relacionadas | Precisam respeitar *arm's length*; desde 2024 o §1(3d)–(3e) AStG exige demonstrar capacidade de pagamento e finalidade econômica de financiamentos intra-grupo; taxa de juros de referência do grupo (rating do grupo) | §1 AStG |
| **Verlustvortrag** (prejuízo fiscal a compensar) | Indefinido no tempo; **Mindestbesteuerung** (tributação mínima): compensação integral até **€1 milhão**; acima disso, só **70%** do lucro excedente (VZ **2024–2027**; volta a **60%** a partir de 2028); GewSt: sempre €1 milhão + 60% | §10d EStG; §10a GewStG; Wachstumschancengesetz ⚠️ verificar se prorrogado |
| **Verlustrücktrag** (carry-back) | Até €1 milhão (€10 milhões em 2022–2023), **3 anos** anteriores a partir de 2024 (somente para KSt/ESt, não GewSt) | §10d(1) EStG |
| Perda de prejuízos em mudança de controle | Transferência de > 50% das quotas em 5 anos → perda dos prejuízos (§8c KStG), salvo *Konzernklausel*, *Stille-Reserven-Klausel* ou *fortführungsgebundener Verlustvortrag* (§8d KStG) | §§8c, 8d KStG |
| **Organschaft** (consolidação fiscal) | Controladora com maioria dos votos (*finanzielle Eingliederung*) + **contrato de transferência de lucros** (*Ergebnisabführungsvertrag* — EAV) por ≥ **5 anos**, registrado no *Handelsregister*; para KSt e GewSt; IVA tem *umsatzsteuerliche Organschaft* (§2(2) nº 2 UStG) sem necessidade de EAV | §§14–19 KStG; §2(2) GewStG |
| Dividendos recebidos por corporação | **95% isentos** (§8b(1) e (5) KStG — 5% tratados como despesa não dedutível) → carga efetiva ~1,5%; **exige participação ≥ 10%** no início do ano (§8b(4) KStG — *Streubesitzdividenden*: <10% plenamente tributáveis); para GewSt, ≥ 15% (§9 nº 2a/7) | §8b KStG |
| Ganhos de capital na venda de participações | 95% isentos, **independentemente** do percentual de participação | §8b(2),(3) KStG |
| Despesas não dedutíveis | 30% de despesas de representação (*Bewirtungskosten*), presentes > €50/ano/pessoa, multas, metade da remuneração do conselho de supervisão, GewSt | §4(5) EStG; §10 KStG |
| *Verdeckte Gewinnausschüttung* (distribuição disfarçada de lucros) | Vantagens a sócios fora de condições de mercado são reintegradas ao lucro | §8(3) KStG |
| Lizenzschranke | Royalties pagos a partes relacionadas sujeitas a regime preferencial (*IP box*) não conforme ao *nexus approach* da OCDE com tributação efetiva < 25% (limite reduzido para **< 15%** a partir de 2024 pelo *Kreditzweitmarktförderungsgesetz* ⚠️ verificar) — dedução parcialmente vedada | §4j EStG ⚠️ verificar |

### 2.5 Tributação de dividendos e retenção na fonte

**Pessoa física residente:**
- **Abgeltungsteuer** (imposto definitivo sobre rendimentos de capital): **25% + Soli 5,5% = 26,375%** (+ *Kirchensteuer* 8–9% sobre o imposto, se membro de igreja) (§32d EStG). Isenção anual (*Sparer-Pauschbetrag*) de **€1.000** (€2.000 casais) (§20(9) EStG).
- Participações ≥ 25% (ou ≥ 1% com atividade profissional na empresa): opção pelo **Teileinkünfteverfahren** (60% tributável à tabela progressiva, 40% isento — §3 nº 40 e §32d(2) nº 3 EStG).

**Retenção na fonte sobre dividendos (*Kapitalertragsteuer* — KapESt):**
- **25% + Soli = 26,375%** (§43(1) nº 1, §43a(1) nº 1 EStG).
- **Corporação estrangeira não residente:** restituição de **2/5** do imposto retido mediante pedido ao BZSt → carga final de **15,825%** (§44a(9) EStG), sujeita ao teste antiabuso (§50d(3) EStG — substância econômica, atividade própria).
- **Diretiva Mães-Filhas (2011/96/UE)**: participação ≥ 10% por 12 meses, recebedora residente na UE → **0%** (§43b EStG), via *Freistellungsbescheinigung* (certificado de isenção) do BZSt ou restituição (§50c EStG).
- **Tratados (DBA)**: reduzem para 5–15% conforme o tratado. **Brasil: sem tratado** → controladora brasileira sofre **15,825%** no mínimo (via §44a(9)), ou 26,375% se não preencher os requisitos.
- Prazo do pedido de restituição: 4 anos após o ano do pagamento (§50c(3) EStG) ⚠️ verificar; pedidos via portal online do BZSt (obrigatório o formulário eletrônico desde 2024).

**Remessa de lucros de *Zweigniederlassung* (filial):** sem retenção na fonte (a Alemanha não tem *branch profits tax*).

### 2.6 Royalties e outros pagamentos a não residentes (§50a EStG)

| Pagamento | Retenção | Base legal |
|---|---|---|
| Royalties / licenças de direitos (patentes, marcas, software com direitos de exploração, know-how) | **15% + Soli = 15,825%** sobre o bruto | §50a(1) nº 3, (2) EStG |
| Atuação artística/esportiva na Alemanha | 15% + Soli | §50a(1) nº 1 |
| Remuneração de conselheiro (*Aufsichtsrat*) | 30% + Soli | §50a(1) nº 4 |
| Juros | Em geral **sem** retenção para não residentes (exceto juros garantidos por imóvel alemão, participações em lucros etc. — §49(1) nº 5 EStG) | §43 EStG |
| Serviços técnicos/consultoria prestados do exterior | Em regra **sem** retenção (não é renda doméstica se o serviço é prestado fora da Alemanha) | §49 EStG |

- O pagador declara e recolhe trimestralmente ao **BZSt** (até o 10º dia após o trimestre) (§50a(5) EStG; §73e EStDV).
- **Licenças de bancos de dados/software padrão sem direitos de exploração**: em regra não sujeitas (BMF-Schreiben de 27/10/2017 e 02/2022) ⚠️ verificar atualização.
- **Licenças de direitos registrados no Brasil sem nexo com a Alemanha:** discussão sobre "royalties extraterritoriais" (§49(1) nº 2 f EStG — direitos registrados em registro alemão, ex.: marca DPMA/EUIPO); reforma de 2024–2025 limitou a tributação a casos com partes relacionadas/abusivas ⚠️ verificar.

### 2.7 Pilar Dois — tributação mínima global (*Mindeststeuergesetz* — MinStG)

- Lei alemã de transposição da Diretiva (UE) 2022/2523: **Mindeststeuergesetz**, publicada em **27/12/2023** (BGBl. 2023 I Nr. 397), aplicável a exercícios iniciados **após 30/12/2023**.
- Escopo: grupos com receita consolidada ≥ **€750 milhões** em pelo menos 2 dos 4 exercícios anteriores.
- Instrumentos: **IIR** (*Primärergänzungssteuer*), **UTPR** (*Sekundärergänzungssteuer*, a partir de 2025), **QDMTT** nacional (*nationale Ergänzungssteuer*); alíquota mínima efetiva de **15%** por jurisdição; *Safe harbours* transitórios (CbCR) até 2026 ⚠️.
- Declaração (*Mindeststeuer-Bericht / GloBE Information Return*): prazo de **18 meses** no primeiro ano, depois 15 meses → primeira entrega até **30/06/2026** para exercícios civis de 2024.
- **"Side-by-side" (G7, junho/2025; pacote OCDE janeiro/2026):** grupos sediados em jurisdições com regime qualificado (EUA) isentos de IIR/UTPR ⚠️ verificar transposição na UE/Alemanha.
- **Brasil:** adotou adicional de CSLL como QDMTT (Lei 15.079/2024), a partir de 2025 → grupos brasileiros com subsidiárias alemãs ≥ €750 mi devem coordenar.

### 2.8 CFC — *Hinzurechnungsbesteuerung* (AStG)

- **§§7–14 AStG** (reformados pelo ATADUmsG, em vigor desde 2022).
- Controle: residentes alemães detêm, direta/indiretamente, **> 50%** dos direitos de voto, capital ou lucros de sociedade estrangeira (inclusive em conjunto com partes relacionadas) — §7(1),(2) AStG.
- **Renda passiva** (*passive Einkünfte*, catálogo §8(1) AStG) sujeita a **tributação baixa: < 15%** (reduzido de 25% para 15% a partir de **2024** — *Kreditzweitmarktförderungsgesetz*), §8(5) AStG.
- Tributação: renda imputada ao sócio alemão (sem isenção do §8b; integralmente tributável ao KSt; para GewSt também desde 2017).
- Exceção de substância para UE/EEE (§8(2) AStG). **Brasil não tem exceção** → subsidiária brasileira de grupo alemão com renda passiva (juros, royalties, etc.) e carga efetiva < 15% pode ser atingida — raramente, pois IRPJ+CSLL = 34%. Para *holding* brasileira acima de GmbH, a CFC alemã não se aplica (é a GmbH que é investida).
- **Brasil (para o lado inverso):** lucros da GmbH são tributados no Brasil pela regra de CFC brasileira (art. 77 Lei 12.973/2014 — tributação em bases universais, lucros da controlada no exterior tributados em 31/12 pelo IRPJ/CSLL, com crédito do imposto pago no exterior).

### 2.9 Preços de transferência (*Verrechnungspreise*)

- **Princípio arm's length** (*Fremdvergleichsgrundsatz*): §1 AStG (redação 2022 com métodos, intervalo interquartil — §1(3a) AStG: ajuste à **mediana** quando fora do intervalo).
- **Documentação** (§90(3) AO; *Gewinnabgrenzungsaufzeichnungsverordnung* — GAufzV): *Local File* para entidades com receitas intra-grupo de bens > **€6 milhões** ou de outros serviços > **€600.000** no ano anterior; *Master File* para receita ≥ **€100 milhões**; **CbCR** (§138a AO) para grupos ≥ €750 milhões.
- **Prazo de apresentação:** desde **2025** (DAC7-Umsetzungsgesetz), documentação deve ser entregue em **30 dias** após solicitação da autoridade (antes 60) e a *Transaktionsmatrix* (matriz de transações) é obrigatória junto (§90(3)–(4) AO) ⚠️ verificar aplicação temporal (aplicável a auditorias ordenadas após 31/12/2024).
- **Penalidades** (§162(3)–(4) AO): presunção contra o contribuinte; acréscimo de 5–10% do ajuste (mínimo €5.000); atraso: até €1 milhão, mínimo €100/dia.
- **Funktionsverlagerung** (transferência de funções): §1(3b) AStG; FVerlV 2022.
- **Brasil:** Lei **14.596/2023** — regras alinhadas à OCDE, obrigatórias desde **01/01/2024** (opcional em 2023); IN RFB 2.161/2023. Não há mais margens fixas; aproxima a documentação dos dois lados, facilitando defesa coerente de *intercompany*. **Sem tratado → sem MAP** (procedimento amigável) entre Brasil e Alemanha: risco de dupla tributação econômica em ajustes de TP **não eliminável** bilateralmente.

### 2.10 Diretivas de transparência DAC6/DAC7/DAC8

| Diretiva | Objeto | Alemanha |
|---|---|---|
| **DAC6** (2018/822) | Comunicação de mecanismos transfronteiriços de planejamento tributário (*grenzüberschreitende Steuergestaltungen*) com *hallmarks* | §§138d–138k AO; prazo **30 dias**; ao BZSt; multa até €25.000. Desde 2024 discute-se **regime nacional** para planejamentos domésticos ⚠️ (abandonado no Wachstumschancengesetz) |
| **DAC7** (2021/514) | Plataformas digitais reportam vendedores | *Plattformen-Steuertransparenzgesetz* (PStTG) desde 01/01/2023; reporte anual até 31/01 |
| **DAC8** (2023/2226) | Criptoativos (CARF) | *KStTG* (Kryptowerte-Steuertransparenzgesetz) a partir de 01/01/2026 ⚠️ verificar |
| **DAC9** (2025/872) | Intercâmbio de informações do Pilar Dois | Transposição até 31/12/2025 ⚠️ |

### 2.11 Imposto sobre transmissão de imóveis (*Grunderwerbsteuer* — GrESt)

- Alíquota definida por cada Estado (*Land*): **3,5% (Baviera) a 6,5%** (Brandemburgo, NRW, Sarre, Schleswig-Holstein); Berlim, Hesse 6,0%; Hamburgo **5,5%** (desde 2023) ⚠️ verificar alterações 2025/2026 (ex.: Bremen 5,5%; Saxônia 5,5% desde 2023; Turíngia reduziu para 5% em 2024).
- *Share deals*: transferência de **≥ 90%** das quotas de sociedade titular de imóvel em **10 anos** (§1(2a), (2b), (3) GrEStG — reforma de 01/07/2021) → incidência.
- Base: preço ou valor (*Bedarfswert*) — §8 GrEStG.

### 2.12 Outros tributos relevantes

- **Grundsteuer** (IPTU): reforma vigente desde **01/01/2025** (novos valores, modelos estaduais).
- **Erbschaft- und Schenkungsteuer** (heranças/doações): 7–50%; isenções de patrimônio empresarial (§§13a, 13b ErbStG).
- **Energiesteuer, Stromsteuer**: redução da *Stromsteuer* para indústria ao mínimo da UE (€0,50/MWh) a partir de 2026 ⚠️.
- **Kirchensteuer** só PF.

**Fontes (Seção 2):**
- https://www.gesetze-im-internet.de/kstg_1977/
- https://www.gesetze-im-internet.de/gewstg/
- https://www.gesetze-im-internet.de/estg/
- https://www.gesetze-im-internet.de/astg/
- https://www.gesetze-im-internet.de/ao_1977/
- https://www.gesetze-im-internet.de/minstg/
- https://kpmg.com/de/de/home/themen/2025/07/stinvsofortpg-bgbl.html
- https://www.ey.com/de_de/technical/steuernachrichten/steuerliches-investitionssofortprogramm-im-bundesrat
- https://www.ihk-muenchen.de/ratgeber/steuern/investitionsprogramm/
- https://www.bundesregierung.de/breg-de/aktuelles/wachstumsbooster-2351752
- https://taxsummaries.pwc.com/germany/corporate/taxes-on-corporate-income
- https://taxsummaries.pwc.com/germany/corporate/withholding-taxes
- https://www.bzst.de/DE/Unternehmen/Kapitalertraege/kapitalertraege_node.html
- https://www.bundesfinanzministerium.de

---

## 3. IVA — Umsatzsteuer

### 3.1 Alíquotas e regras gerais

| Item | Regra | Base legal |
|---|---|---|
| Alíquota geral (*Regelsteuersatz*) | **19%** | §12(1) UStG |
| Alíquota reduzida (*ermäßigter Steuersatz*) | **7%** — alimentos (Anexo 2), livros/jornais (inclusive digitais), transporte público local, hotelaria (pernoite), certas obras de arte; **refeições em restaurantes (exceto bebidas): 7% de forma permanente desde 01/01/2026** (Steueränderungsgesetz 2025) ⚠️ verificar promulgação | §12(2) UStG |
| Alíquota zero | Instalação de sistemas fotovoltaicos residenciais ≤ 30 kWp (desde 2023) | §12(3) UStG |
| Isenções com direito a crédito | Exportações (§4 nº 1a c/c §6), entregas intracomunitárias (§4 nº 1b c/c §6a) | §4 UStG |
| Isenções sem crédito | Financeiras, seguros, locação de imóveis (com opção §9), saúde, educação | §4 nº 8–29 UStG |
| Crédito (*Vorsteuerabzug*) | Requer fatura conforme §14 UStG (a partir de 2025/2027: e-fatura em B2B doméstico) | §15 UStG |
| Local da prestação de serviços B2B | Regra geral: sede do tomador (§3a(2) UStG) | §3a UStG |
| Importação | *Einfuhrumsatzsteuer* (IVA-importação) 19%/7%, cobrada pela alfândega (*Zoll*); dedutível como crédito; diferimento via conta de prazo (*Aufschubkonto*) | §§1(1) nº 4, 21 UStG |

### 3.2 Kleinunternehmerregelung (regime de pequeno empresário — §19 UStG)

Reforma pelo *Jahressteuergesetz 2024*, vigente desde **01/01/2025**:
- Receita do **ano anterior ≤ €25.000** **e** receita do **ano corrente ≤ €100.000** (limite "duro": ao ultrapassar €100.000 no ano corrente, a tributação normal começa **imediatamente**, a partir da operação que excede).
- Torna-se **isenção** verdadeira (antes era "não cobrança"), sem direito a crédito; fatura sem destaque de IVA com menção à isenção.
- **Novidade UE (Diretiva 2020/285):** pequenos empresários de outros Estados-membros podem usar o regime na Alemanha (e vice-versa) se receita na UE ≤ €100.000 (*procedimento KU via BZSt*, §19a UStG). **Não se aplica a empresas brasileiras** (somente estabelecidas na UE).

### 3.3 Reverse charge (*Steuerschuldnerschaft des Leistungsempfängers*, §13b UStG)

- Serviços prestados por empresa **estrangeira** (inclusive brasileira) a empresário alemão: IVA devido pelo **tomador** (§13b(1) e (2) nº 1, (5) UStG). A empresa brasileira **não precisa se registrar** para IVA na Alemanha em regra quando presta só B2B serviços sujeitos a reverse charge.
- Domésticos: obras de construção, sucata, telemóveis/chips (≥ €5.000), certificados de emissão, gás/eletricidade entre revendedores, ouro etc. (§13b(2) nº 2–11 UStG).
- Fatura deve conter "*Steuerschuldnerschaft des Leistungsempfängers*" (§14a(5) UStG).

### 3.4 Comércio intra-UE, OSS e IOSS

| Regime | Aplicação | Limite/condição |
|---|---|---|
| Entrega intracomunitária isenta | B2B com USt-IdNr válida do adquirente; *Gelangensbestätigung* (prova de transporte) | §6a UStG; §17a UStDV |
| **Zusammenfassende Meldung** (ZM — declaração recapitulativa) | Entregas e serviços B2B intra-UE; mensal (ou trimestral se ≤ €50.000) até o 25º dia | §18a UStG |
| **OSS** (*One-Stop-Shop*, união/não-união) | Vendas a distância B2C intra-UE e serviços B2C; limite UE de **€10.000** (acima: IVA do país do consumidor). Empresa **não-UE** (brasileira) prestando serviços B2C a consumidores da UE: **OSS não-união** (registro em um único Estado) | §§18i, 18j UStG; Diretiva 2017/2455 |
| **IOSS** (*Import-One-Stop-Shop*) | Vendas a distância de bens importados de valor intrínseco **≤ €150** a consumidores na UE; empresa brasileira precisa de **intermediário** estabelecido na UE | §18k UStG |
| Marketplaces | Plataforma é fornecedor presumido (*fiktiver Lieferer*) para importações ≤ €150 e vendas de vendedores não-UE | §3(3a) UStG; §25e UStG (responsabilidade) |
| Supressão do limite de €150 de isenção aduaneira | Reforma aduaneira da UE: taxa fixa de **€3 por item** em pequenas encomendas a partir de **01/07/2026** ⚠️ verificar (acordo do Conselho dez/2025) | Código Aduaneiro da União (revisão) |

**USt-IdNr** (*Umsatzsteuer-Identifikationsnummer*, formato DE + 9 dígitos): emitida pelo **BZSt** (§27a UStG), automaticamente quando requerida na inscrição; verificação online (*Bestätigungsverfahren* do BZSt; VIES da Comissão).

### 3.5 Declarações (*Umsatzsteuer-Voranmeldung* — UStVA) e anual

| Obrigação | Regra (desde 2025) | Base |
|---|---|---|
| UStVA **mensal** | IVA do ano anterior > **€9.000** ⚠️ (elevado de €7.500 pelo BEG IV, verificar) | §18(2) UStG |
| UStVA **trimestral** | IVA do ano anterior entre €2.000 e €9.000 | §18(2) UStG |
| Dispensa | IVA do ano anterior ≤ **€2.000** | §18(2) frase 3 |
| Prazo | **10º dia** após o período; *Dauerfristverlängerung* (prorrogação permanente de 1 mês) mediante pedido e antecipação de 1/11 (mensais) | §§46–48 UStDV |
| Empresas novas (*Neugründer*) | Regra de UStVA mensal obrigatória nos 2 primeiros anos **suspensa para 2021–2026** ⚠️ verificar prorrogação | §18(2) frase 6 |
| Declaração anual (*Umsatzsteuererklärung*) | Até 31/07 do ano seguinte (sem consultor); com *Steuerberater*, prazo estendido (ver 4.8); pequenos empresários §19 dispensados desde 2024 salvo exceções | §18(3) UStG |
| Formato | Eletrônico via **ELSTER** obrigatório | §18(1) UStG |
| Empresa estrangeira | Repartição centralizada: empresas **com sede no Brasil** são atendidas pelo *Finanzamt* competente conforme o país — para o Brasil: **Finanzamt Kassel-Hofgeismar** ⚠️ verificar (UStZustV) | UStZustV |

**Restituição de IVA a empresas não-UE (*Vorsteuer-Vergütungsverfahren*)**: empresas brasileiras sem operações tributáveis na Alemanha podem pedir restituição de IVA pago (feiras, viagens) ao BZSt **até 30/06** do ano seguinte (§18(9) UStG; §§59–61a UStDV), **somente se houver reciprocidade** (*Gegenseitigkeit*, §18(9) frase 4 UStG). O BMF mantém lista de países com reciprocidade; ⚠️ o **Brasil historicamente consta na lista de países SEM reciprocidade** (*Verzeichnis der Drittstaaten, mit denen keine Gegenseitigkeit besteht*) → restituição normalmente **indisponível** — verificar lista BMF atualizada. Combustível excluído para não-UE.

### 3.6 E-Rechnung obrigatória (fatura eletrônica B2B)

Introduzida pelo *Wachstumschancengesetz* (BGBl. 2024 I Nr. 108, 27/03/2024), alterando §14 UStG; BMF-Schreiben de 15/10/2024 e 2.º BMF-Schreiben de 15/10/2025 ⚠️ verificar data.

| Data | Obrigação |
|---|---|
| **01/01/2025** | Todas as empresas no país devem estar aptas a **receber** e-faturas (B2B doméstico). Basta uma caixa de e-mail. |
| 2025–2026 | Emissão: facultativa — ainda permitidas faturas em papel e PDF/outros formatos (este último com consentimento do destinatário) |
| **01/01/2027** | **Emissão obrigatória** para empresas com receita do ano anterior (2026) **> €800.000**; empresas ≤ €800.000 podem continuar emitindo papel/outros até 31/12/2027 |
| **01/01/2028** | Emissão obrigatória para **todas** as operações B2B domésticas; fim das faturas EDI que não cumprem EN 16931 |

- **Formato:** estruturado conforme **EN 16931** — **XRechnung** (XML puro) ou **ZUGFeRD ≥ 2.0.1** (PDF/A-3 híbrido com XML; perfis MINIMUM e BASIC-WL **não** são e-faturas válidas). PDF simples **não** é e-fatura.
- **Escopo:** apenas operações entre empresários **estabelecidos na Alemanha** (sede, estabelecimento permanente participante). Faturas **B2C, de exportação e de empresas estrangeiras sem estabelecimento** ficam fora. Faturas de pequeno valor (≤ **€250**) e passagens isentas.
- **Arquivamento:** em formato original (XML) por 8 anos (ver 4.9).
- ⚠️ **Lobbies pedem adiar** a etapa de 2027 para 2028; até a data de referência, sem alteração legal confirmada.
- **Sistema de reporte em tempo real** (CTC — *Meldesystem*): previsto pela ViDA a partir de 2030 para operações intra-UE; ⚠️ Alemanha ainda não definiu reporte doméstico.

### 3.7 ViDA — *VAT in the Digital Age*

Pacote adotado pelo Conselho em **11/03/2025**, publicado no JO em **25/03/2025** (Diretiva (UE) 2025/516; Regulamento (UE) 2025/517; Regulamento de Execução (UE) 2025/519):

| Pilar | Conteúdo | Data |
|---|---|---|
| E-fatura e *Digital Reporting Requirements* (DRR) | Estados podem impor e-fatura doméstica sem autorização da UE (desde a entrada em vigor); e-fatura **obrigatória em operações intra-UE B2B** com reporte quase em tempo real | **01/07/2030** |
| Economia de plataformas | Plataforma como fornecedor presumido para aluguel de curta duração e transporte de passageiros | **01/07/2028** (opcional até 2030) |
| Registro único de IVA | Ampliação do OSS, reverse charge obrigatório para não estabelecidos, IOSS obrigatório para plataformas | **01/07/2028** |

**Fontes (Seção 3):**
- https://www.gesetze-im-internet.de/ustg_1980/
- https://www.bundesfinanzministerium.de/Content/DE/FAQ/e-rechnung.html
- https://www.ihk.de/stuttgart/fuer-unternehmen/recht-und-steuern/steuerrecht/steuermeldungen/e-rechnungen-5864496
- https://www.etl.de/e-rechnung/zeitplan/
- https://www.bzst.de/DE/Unternehmen/Umsatzsteuer/umsatzsteuer_node.html
- https://eur-lex.europa.eu/eli/dir/2025/516/oj
- https://taxation-customs.ec.europa.eu/taxation/vat/vat-digital-age-vida_en
- https://taxsummaries.pwc.com/germany/corporate/other-taxes

---

## 4. Contabilidade, demonstrações e obrigações acessórias

### 4.1 Obrigação de escrituração (*Buchführungspflicht*)

- **Comercial:** todo *Kaufmann* (comerciante) — inclusive toda GmbH/AG/UG (*Formkaufmann*, §6 HGB; §13(3) GmbHG) — deve escriturar segundo os **GoB** (*Grundsätze ordnungsmäßiger Buchführung* — princípios de escrituração regular) (§238 HGB).
- **Dispensa** para *Einzelkaufleute* com receita ≤ **€800.000** e lucro ≤ **€80.000** em dois exercícios consecutivos (§241a HGB; valores desde 2024).
- **Fiscal derivada:** §140 AO (quem é obrigado por outras leis); **originária:** §141 AO (receita > €800.000 ou lucro > €80.000 — valores desde 2024).
- **GoBD** (*Grundsätze zur ordnungsmäßigen Führung und Aufbewahrung von Büchern, Aufzeichnungen und Unterlagen in elektronischer Form sowie zum Datenzugriff*): BMF-Schreiben de 28/11/2019, **alterado em 11/03/2024** (e-faturas, acesso a dados) e novamente em 2025 ⚠️ — rege escrituração digital, imutabilidade (*Unveränderbarkeit*), procedimentos documentados (*Verfahrensdokumentation*), acesso do fisco a dados (Z1/Z2/Z3, §147(6) AO).
- **Kassensicherungsverordnung**: caixas registradoras eletrônicas com **TSE** (*technische Sicherheitseinrichtung*) certificada; comunicação obrigatória ao fisco desde **01/01/2025** (§146a AO) ⚠️.
- Livros em **alemão** ou em língua viva (a autoridade pode exigir tradução) (§239(1) HGB; §146(3) AO); em princípio mantidos na Alemanha, com possibilidade de **escrituração no exterior** mediante autorização (§146(2a) AO) — inclusive no Brasil, se o fisco tiver acesso aos dados.
- **Moeda**: balanço em euro (§244 HGB).

### 4.2 Classes de porte (§267 HGB) — valores após a reforma de 2024

Elevados em ~25% pela lei de transposição da Diretiva Delegada (UE) 2023/2775 (*Gesetz zur Umsetzung der Richtlinie (EU) 2023/2775*, BGBl. 2024 I Nr. 120, de 16/04/2024), aplicáveis a exercícios iniciados após **31/12/2023** (opcional) e obrigatórios a partir de exercícios iniciados após 31/12/2024. Basta **2 de 3 critérios** em dois exercícios consecutivos.

| Classe | Ativo total (*Bilanzsumme*) | Receita (*Umsatzerlöse*) | Empregados (média) |
|---|---|---|---|
| **Kleinst** (micro, §267a) | ≤ €450.000 | ≤ €900.000 | ≤ 10 |
| **Klein** (pequena, §267(1)) | ≤ **€7,5 milhões** | ≤ **€15 milhões** | ≤ 50 |
| **Mittelgroß** (média, §267(2)) | ≤ **€25 milhões** | ≤ **€50 milhões** | ≤ 250 |
| **Groß** (grande, §267(3)) | > €25 milhões | > €50 milhões | > 250 |

Sociedades de capital aberto (*kapitalmarktorientiert*, §264d HGB) são sempre "grandes". As regras de porte se aplicam também à GmbH & Co. KG (§264a HGB).

### 4.3 Demonstrações anuais (*Jahresabschluss*)

| Elemento | Micro | Pequena | Média | Grande |
|---|---|---|---|---|
| Balanço (*Bilanz*) | Simplificado | Simplificado (§266(1)) | Completo | Completo |
| DRE (*Gewinn- und Verlustrechnung*) | Simplificada | Simplificada (§276) | Simplificada (§276) | Completa |
| Notas explicativas (*Anhang*) | Dispensadas se informações sob o balanço | Reduzidas (§288) | Reduzidas | Completas |
| Relatório da administração (*Lagebericht*) | Não | Não (§264(1)) | **Sim** | **Sim** |
| **Auditoria obrigatória** (*Abschlussprüfung*) | Não | Não | **Sim** | **Sim** (§316 HGB) |
| Prazo de elaboração (*Aufstellung*) | até 6 meses | até 6 meses | 3 meses | 3 meses (§264(1) HGB) |
| Publicação (*Offenlegung*) | Depósito (*Hinterlegung*) do balanço | Balanço + Anexo | Balanço, DRE, Anexo, Lagebericht, parecer (com alívios §327) | Completo |

- **Aprovação** pelos sócios da GmbH em até 8 meses (pequenas: 11 meses) (§42a(2) GmbHG).
- **Publicação:** em até **12 meses** após o encerramento do exercício, **no *Unternehmensregister*** (desde 01/08/2022, por força do DiRUG, substituiu o *Bundesanzeiger*) (§325 HGB). Multa administrativa (*Ordnungsgeld*) imposta pelo *Bundesamt für Justiz*: €2.500 a €25.000 (§335 HGB).
- **Consolidação** (*Konzernabschluss*, §290 HGB): obrigatória para controladora alemã, salvo isenção por tamanho (§293 HGB) ou por inclusão em consolidado de controladora superior — **inclusive extra-UE (Brasil)** se o consolidado brasileiro for equivalente e publicado em alemão/inglês na Alemanha (§292 HGB c/c KonBefrV) ⚠️ verificar equivalência IFRS/CPC.
- **Isenção de publicação de subsidiária** (§264(3) HGB): exige controladora com sede na **UE/EEE** e outras condições → **subsidiária de grupo brasileiro não pode usar §264(3)** se a controladora direta for brasileira.
- **IFRS:** obrigatório para o consolidado de companhias com valores mobiliários negociados em mercado regulado da UE (Regulamento (CE) 1606/2002; §315e HGB). Para as contas individuais (*Einzelabschluss*), HGB é obrigatório; IFRS só é permitido para fins de publicação (§325(2a) HGB). Base fiscal derivada do HGB (*Maßgeblichkeitsprinzip*, §5(1) EStG), com *E-Bilanz* (taxonomia XBRL; §5b EStG).
- **Diferenças HGB × IFRS/CPC brasileiro** relevantes: princípio da prudência (*Vorsichtsprinzip*), proibição de reconhecer ganhos não realizados (*Realisationsprinzip*), provisões para despesas futuras restringidas, leasing sem IFRS 16, *aktivierte Entwicklungskosten* opcional (§248(2)).

### 4.4 Sustentabilidade: CSRD/ESRS e Omnibus

- **CSRD** (Diretiva (UE) 2022/2464): a Alemanha **não havia transposto** a CSRD no prazo (06/07/2024); projeto *CSRD-Umsetzungsgesetz* (2024/2025) reapresentado em 2025 ⚠️ verificar se promulgado até 11/2026. Até a transposição, empresas alemãs aplicam a antiga *nichtfinanzielle Erklärung* (§§289b ss. HGB) — empresas de interesse público com > 500 empregados.
- **"Stop-the-clock"** (Diretiva (UE) 2025/794, de 14/04/2025): adiou em 2 anos as ondas 2 e 3 (reporte de grandes empresas não listadas para o exercício 2027; PMEs listadas 2028).
- **Omnibus I** — **Diretiva (UE) 2026/470**, publicada no JO em **26/02/2026**, em vigor em **18/03/2026**:
  - **CSRD:** apenas empresas com **> 1.000 empregados e > €450 milhões** de receita líquida; controladoras **não-UE**: receita na UE > €450 milhões e subsidiária/filial na UE com receita relevante (⚠️ limite de filial — verificar €200 milhões); transposição até **19/03/2027**.
  - **ESRS simplificados** (redução de ~60% dos *datapoints*) via ato delegado ⚠️ (adoção 2026).
  - **Proteção da cadeia de valor** (*value-chain cap*): empresas menores (< 1.000 empregados) só fornecem dados conforme padrão voluntário (VSME).
  - **CSDDD:** ver 8.3.
- **Impacto para brasileiros:** grupo brasileiro com receita na UE > €450 milhões pode ficar sujeito a reporte consolidado em nível de grupo (CSRD art. 40a) — a partir de exercício 2028 ⚠️ verificar.
- **EU-Taxonomie**: Regulamento (UE) 2020/852; simplificações (materialidade de 10%) por ato delegado de 2025 ⚠️.

### 4.5 Imposto de renda da pessoa física (*Einkommensteuer* — ESt) — tabela 2026

Tarifa progressiva (§32a EStG), valores 2026 (Steuerfortentwicklungsgesetz, BGBl. 2024 I Nr. 449):

| Faixa de renda tributável (solteiro) | Alíquota marginal |
|---|---|
| até **€12.348** (*Grundfreibetrag* — mínimo isento) | 0% |
| €12.349 – €17.799 ⚠️ | 14% → ~24% (progressão linear) |
| €17.800 – €69.878 ⚠️ | ~24% → 42% (progressão linear) |
| **€69.879 – €277.825** | **42%** (*Spitzensteuersatz*) |
| **a partir de €277.826** | **45%** (*Reichensteuer*) |

- Casais com tributação conjunta (*Zusammenveranlagung / Ehegattensplitting*): valores dobrados (mínimo isento €24.696).
- **Soli** 5,5% só incide acima da *Freigrenze* de imposto de €20.350 (solteiro, 2026) ⚠️ verificar valor; ~90% dos contribuintes isentos.
- *Kinderfreibetrag* 2026: €6.828 por criança (ambos os pais) + BEA €2.928 = €9.756; *Kindergeld* (abono) €259/mês ⚠️.
- Não residentes: tributação limitada (§1(4) EStG; §50 EStG) sem *Grundfreibetrag* integral, salvo opção §1(3) EStG (≥ 90% da renda na Alemanha).
- **Residência fiscal:** domicílio (*Wohnsitz*, §8 AO) ou residência habitual > **6 meses** (*gewöhnlicher Aufenthalt*, §9 AO).
- **Wegzugsbesteuerung** (exit tax, §6 AStG): saída de residente com participação ≥ 1% em sociedade (≥ €500.000 de custo em fundos) → tributação dos ganhos latentes; desde 2022 parcelamento em 7 anos sem diferimento indefinido para UE.

### 4.6 Steuerberater e papel profissional

- Profissão regulamentada (StBerG — *Steuerberatungsgesetz*); somente *Steuerberater*, *Wirtschaftsprüfer* (auditor), *Rechtsanwalt* e entes autorizados podem prestar consultoria tributária habitual (§§2, 3 StBerG).
- Honorários pela *Steuerberatervergütungsverordnung* (StBVV) — tabela mínima/máxima.
- Funções práticas: escrituração (*Finanzbuchhaltung*, geralmente via sistema **DATEV**), folha (*Lohnbuchhaltung*), UStVA, declarações anuais (KSt, GewSt, USt), *E-Bilanz*, representação perante o *Finanzamt* e auditoria fiscal (*Betriebsprüfung*).
- **Auditor** (*Wirtschaftsprüfer*, WPO) para médias/grandes.
- Benefício de prazo: declarações preparadas por consultor têm prazo estendido (ver 4.8).

### 4.7 Fiscalização e penalidades

- **Betriebsprüfung** (auditoria fiscal, §§193 ss. AO): grandes empresas — periodicidade quase contínua (*Anschlussprüfung*); desde 2025, novas regras de cooperação e *Teilabschlussbescheide* (§§197, 180(1a) AO — FKAustG/DAC7-UmsG).
- **Juros** (*Zinsen*, §233a AO): **0,15%/mês (1,8% a.a.)** desde 2019 (após decisão do BVerfG de 2021).
- **Multa por atraso** (*Verspätungszuschlag*, §152 AO): 0,25% do imposto/mês, mínimo €25/mês.
- **Prescrição** (*Festsetzungsverjährung*, §169 AO): 4 anos (5 em negligência grave; 10 em evasão).
- **Selbstanzeige** (denúncia espontânea, §371 AO).

### 4.8 Prazos de declarações anuais (*Abgabefristen*, §149 AO)

| Ano-calendário | Sem consultor | Com *Steuerberater* |
|---|---|---|
| 2024 | 31/07/2025 | **30/04/2026** |
| 2025 | 31/07/2026 | **01/03/2027** (28/02 cai em domingo) |
| 2026 em diante | 31/07 do ano seguinte | final de fevereiro do 2.º ano seguinte |

- Aplica-se a KSt, GewSt, USt (anual) e ESt. Prorrogações da era COVID **terminaram** com o ano-calendário 2024.
- **E-Bilanz** (balanço eletrônico) junto com a declaração (§5b EStG).

### 4.9 Guarda de documentos (*Aufbewahrungsfristen*)

| Documento | Prazo | Base legal |
|---|---|---|
| Livros, inventários, demonstrações anuais, relatórios, *Verfahrensdokumentation* | **10 anos** | §147(1) nº 1, (3) AO; §257(4) HGB |
| **Comprovantes contábeis** (*Buchungsbelege* — inclusive faturas recebidas/emitidas) | **8 anos** (reduzido de 10) — **BEG IV** (*Viertes Bürokratieentlastungsgesetz*, BGBl. 2024 I Nr. 323), com efeito para documentos cujo prazo não havia expirado em **01/01/2025** | §147(3) AO; §257(4) HGB; §14b UStG |
| Exceção | **Bancos, seguradoras e instituições de valores mobiliários**: mantido **10 anos** (lei de modernização do combate ao trabalho ilegal — SchwarzArbMoDiG, 2025) ⚠️ verificar regra de transição | §147(3) AO (nova redação) |
| Correspondência comercial (*Handels- und Geschäftsbriefe*) | **6 anos** | §147(1) nº 2–3 AO; §257(4) HGB |
| Contagem | A partir do final do ano civil em que o documento foi criado/registrado; suspensão enquanto relevante para tributos não prescritos (§147(3) frase 3 AO) | — |

**Fontes (Seção 4):**
- https://www.gesetze-im-internet.de/hgb/__267.html
- https://www.gesetze-im-internet.de/hgb/__325.html
- https://www.gesetze-im-internet.de/ao_1977/__147.html
- https://www.gesetze-im-internet.de/ao_1977/__149.html
- https://www.bundesfinanzministerium.de/Content/DE/Downloads/BMF_Schreiben/Weitere_Steuerthemen/Abgabenordnung/AO-Anwendungserlass/2019-11-28-GoBD.html
- https://www.ey.com/de_de/technical/steuernachrichten/laengere-aufbewahrungsfristen-bei-banken-versicherungen-und-wertpapierinstituten
- https://www.ihk.de/konstanz/recht-und-steuern/steuer-und-finanzpolitik/finverwal/aufbewahrung-von-geschaeftsunterlagen-1672476
- https://www.finanzamt.nrw.de/steuerinfos/weitere-themen/steuererklaerung/einkommensteuertarif
- https://www.lw.com/en/insights/eu-sustainability-omnibus-published-in-the-official-journal
- https://www.globalpolicywatch.com/2026/02/eu-csddd-csrd-omnibus-published-in-official-journal-transposition-delegated-acts-and-guidelines-are-next/
- https://www.unternehmensregister.de

---

## 5. Relação tributária Brasil–Alemanha

### 5.1 Status do acordo para evitar a dupla tributação (ADT / *DBA*)

| Marco | Data |
|---|---|
| Assinatura da Convenção Brasil–Alemanha | 27/06/1975 (Brasília) |
| Promulgação no Brasil | Decreto Legislativo 92/1975; **Decreto 76.988/1976** |
| **Denúncia pela Alemanha** | Notificada em **07/04/2005** ⚠️ (data de notificação a verificar) |
| **Fim da aplicação** | Deixou de produzir efeitos a partir de **01/01/2006** (rendimentos pagos/creditados desde então). No Brasil: **Ato Declaratório Executivo SRF nº 72/2005** declara o encerramento; **Decreto 5.654/2005** revogou o decreto de promulgação |
| Motivo | Divergências sobre crédito presumido (*tax sparing / fiktive Anrechnung*), tributação de serviços técnicos (Brasil retendo sobre serviços via art. 12/21) e posição brasileira fora do padrão OCDE ⚠️ |
| Negociações de novo acordo | Rodadas exploratórias desde ~2015–2018 sem conclusão. Segundo a **GTAI** ("Recht kompakt Brasilien", 2026), os governos **retomaram oficialmente as negociações em 2026**. Em 22/11/2026 **não há novo acordo assinado** nem em vigor ⚠️ acompanhar BMF ("Stand der Doppelbesteuerungsabkommen", publicado anualmente em janeiro) |

**Conclusão operacional:** em 2026 **não existe ADT Brasil–Alemanha**. Não há limitação de retenções, nem MAP, nem regra de estabelecimento permanente do tratado, nem *tie-breaker* de residência. A eliminação da dupla tributação depende **exclusivamente das regras unilaterais** de cada país. (Para comparação: a Alemanha tem tratados com Argentina — renovado — e México; o Brasil tem acordos com Áustria, Bélgica, Dinamarca, Espanha, França, Holanda, Itália, Luxemburgo, Portugal, Suécia, Suíça, entre outros — relevante para **estruturação via holding intermediária**, sujeita a antiabuso: §50d(3) EStG na Alemanha; PPT/MLI e substância no Brasil.)

### 5.2 Crédito unilateral na Alemanha

| Contribuinte | Mecanismo | Base legal |
|---|---|---|
| PF residente na Alemanha com renda de fonte brasileira | **Anrechnung** (crédito) do imposto brasileiro pago, limitado ao ESt alemão proporcional à renda estrangeira (*per country limitation*); ou, por opção, **Abzug** (dedução como despesa) | **§34c(1) e (2) EStG**; §34d EStG (definição de renda estrangeira) |
| Rendimentos de capital sob Abgeltungsteuer | Crédito limitado a 25% por rendimento | §32d(5) EStG |
| Corporação residente (GmbH) com renda de fonte brasileira | Crédito do imposto brasileiro contra o KSt (não contra a GewSt), limitado | **§26 KStG** (c/c §34c EStG) |
| Dividendos recebidos de subsidiária brasileira por GmbH | **95% isentos** (§8b KStG) — o IRRF brasileiro (a partir de 2026: **10%**, ver 5.4) **não é creditável** (pois a renda é isenta) → custo final | §8b KStG; §26 KStG |
| GewSt | Sem crédito; dividendos de subsidiária ≥ 15% excluídos (§9 nº 7 GewStG); lucros de estabelecimento permanente no Brasil excluídos (§9 nº 3) | GewStG |
| Lucro de estabelecimento permanente no Brasil de empresa alemã | Sem tratado → **não há isenção**; tributado na Alemanha com crédito (§26 KStG), exceto GewSt (excluída) | §26 KStG |

**Atenção:** como a Alemanha só credita impostos "**equivalentes ao ESt/KSt alemão**" (Anexo 12 EStR), discute-se o crédito da **CSLL** (aceita na prática como imposto sobre a renda ⚠️), não se credita **CIDE**, **PIS/Cofins** e **ISS**.

### 5.3 Crédito unilateral no Brasil

- **PJ:** art. 26 da **Lei 9.249/1995** — compensação do imposto de renda pago no exterior sobre lucros, rendimentos e ganhos de capital computados no lucro real, limitado ao IRPJ/CSLL brasileiro incidente sobre essas rendas; regulamentação **IN RFB 1.520/2014** (CFC) e art. 87 Lei 12.973/2014 (crédito sobre lucros de controladas, inclusive imposto indireto até o 1º nível em certos casos). Em **01/2026** a RFB publicou o **ADI RFB nº 1/2026** sobre compensação de tributos pagos no exterior por controladas e coligadas ⚠️ verificar conteúdo.
- **PF:** compensação do IR pago no exterior com base em **reciprocidade de tratamento**. A Receita reconhece reciprocidade com a Alemanha pelo **Ato Declaratório (Interpretativo) SRF nº 16/2005** (e antes ADI SRF 28/2000 ⚠️), com base no §34c EStG; a IN SRF 208/2002 (art. 1º §2º) e o manual do IRPF dispensam prova de reciprocidade para Alemanha, Reino Unido e EUA. Limite: diferença entre o IRPF calculado com e sem o rendimento (Lei 14.754/2023 para aplicações financeiras/entidades no exterior). Excedente não é restituível.
- **Lei 14.754/2023** (offshores e aplicações financeiras de PF no exterior, desde 2024): rendimentos de aplicações financeiras na Alemanha tributados a **15%** na declaração anual; crédito do imposto alemão (Abgeltungsteuer) admitido **somente** se houver tratado ou reciprocidade — Alemanha qualifica via reciprocidade ⚠️ verificar interpretação da RFB para a Lei 14.754.

### 5.4 Retenções em remessas Brasil → Alemanha (2026)

| Pagamento do Brasil para beneficiário alemão | IRRF | Outros tributos brasileiros | Observações |
|---|---|---|---|
| **Dividendos/lucros** | **10%** a partir de **01/01/2026** (Lei **15.270/2025**, alterando art. 10 Lei 9.249/1995); lucros apurados até 2025, deliberados até 31/12/2025, permanecem isentos | — | Crédito opcional ao não residente quando carga efetiva IRPJ+CSLL+IRRF exceder alíquotas nominais (34%) — dependente de regulamentação ⚠️. Na Alemanha (GmbH recebedora) dividendos 95% isentos → IRRF é custo |
| **Juros sobre capital próprio** (JCP) | **15%** (25% se paraíso fiscal) | — | JCP: Lei 9.249/1995 art. 9º; ⚠️ alterações da Lei 15.270/2025/LC sobre JCP (alíquota elevada para 17,5%? verificar) |
| **Juros** de empréstimos | 15% | IOF-câmbio | Sujeito a regras de subcapitalização (Lei 12.249/2010) |
| **Royalties** (marcas, patentes, know-how) | **15%** | **CIDE 10%** (Lei 10.168/2000); **PIS/Cofins-Importação 9,25%** (sobre serviços/certas licenças — Lei 10.865/2004); ISS (se serviço) | Dedutibilidade limitada a 1%–5% da receita (Portaria MF 436/1958; arts. 52, 71 Lei 4.506/1964) — revogada por Lei 14.596/2023 para partes relacionadas a partir de 2024 ⚠️ verificar |
| **Serviços técnicos e assistência técnica** | **15%** | **CIDE 10%**; PIS/Cofins-Importação 9,25%; **ISS 2%–5%** (LC 116/2003) | Sem tratado, **não** há proteção do art. 7 → retenção aplica-se a qualquer serviço técnico |
| **Demais serviços** (não técnicos, ex.: comissões, consultoria administrativa) | **25%** (regra residual — art. 7º Lei 9.779/1999 c/c RIR/2018 art. 765) ⚠️ verificar enquadramento | PIS/Cofins-Imp. 9,25%; ISS | Grande custo pela ausência de tratado |
| **Software** (licença de uso/ cessão) | 15% (royalties) | CIDE não incide sobre licença de uso de software sem transferência de tecnologia (Lei 11.452/2007); PIS/Cofins conforme | Após STF (ADIs 1945/5659, 2021), software é serviço p/ ISS |
| Remessa a **paraíso fiscal** ou regime privilegiado | 25% | — | **A Alemanha não está** na lista da IN RFB 1.037/2010 |
| **IOF-câmbio** | 0,38% em regra para remessas; alterações do Decreto 12.499/2025 elevaram alíquotas em algumas operações (ex.: 3,5%) ⚠️ verificar aplicação a pagamentos de serviços/dividendos | — | |

**Reforma tributária brasileira (EC 132/2023; LC 214/2025):** importação de serviços passa a sujeitar-se a **CBS/IBS** em substituição gradual a PIS/Cofins e ISS: teste em **2026** (CBS 0,9% e IBS 0,1%, compensáveis), CBS plena em **2027**, IBS gradual 2029–2032, extinção de ISS/ICMS em 2033. Impacto: créditos amplos para importação de serviços (não cumulatividade plena) ⚠️.

### 5.5 Preços de transferência Brasil (Lei 14.596/2023)

- Adoção do **arm's length** da OCDE; vigência obrigatória **01/01/2024** (opcional 2023); IN RFB **2.161/2023**; documentação (Arquivo Local / Arquivo Global, CbCR) com entrega anual; multas de até 5% do valor das operações (mínimo R$ 20.000).
- Aproxima a coerência de documentação com a Alemanha (§1 AStG, §90 AO), mas **sem tratado não há ajuste correspondente** (*corresponding adjustment*) → planejar de forma consistente (mesma análise funcional, mesmo intervalo).
- Royalties intra-grupo: fim dos limites de dedutibilidade e da vedação de dedução de royalties pagos a controladora (para fatos geradores desde 2024) ⚠️ verificar interpretação RFB.

### 5.6 Acordo previdenciário Brasil–Alemanha

- **Acordo de Previdência Social** assinado em **03/12/2009**, aprovado pelo Congresso Nacional (decreto legislativo — número ⚠️ verificar) e promulgado pelo **Decreto 8.000/2013**; **em vigor desde 01/05/2013**.
- **Destacamento** (*Entsendung*): trabalhador enviado temporariamente permanece no sistema do país de origem por até **24 meses** (prorrogável mediante acordo das autoridades) ⚠️ verificar; certificado de deslocamento emitido pelo INSS (Brasil) / DVKA (Alemanha).
- **Totalização** de períodos de contribuição para aposentadoria por idade, invalidez e pensão; cobertura: no Brasil, RGPS/RPPS; na Alemanha, *Rentenversicherung* e seguro de acidentes (**não cobre** seguro-saúde nem desemprego → trabalhador destacado deve ter seguro-saúde na Alemanha).
- **Não** elimina IR: a renda do trabalho é tributada pelas regras unilaterais (183 dias **não** se aplica sem tratado; trabalho exercido na Alemanha é renda alemã — §49(1) nº 4 EStG — desde o primeiro dia, salvo isenções domésticas específicas ⚠️ verificar caso a caso). Empregador brasileiro sem estabelecimento na Alemanha: o *Lohnsteuer* pode ser exigido se houver *wirtschaftlicher Arbeitgeber* alemão (subsidiária que suporta o custo — §38(1) frase 2 EStG).

**Fontes (Seção 5):**
- https://www.gtai.de/de/trade/brasilien-wirtschaft/recht-kompakt
- https://www.bundesfinanzministerium.de/Content/DE/Standardartikel/Themen/Steuern/Internationales_Steuerrecht/Staatenbezogene_Informationen/staatenbezogene-info.html
- https://planalto.gov.br/CCIVIl_03/decreto/1970-1979/anexo/and76988-76.pdf
- https://okai.com.br/documento/2005-12-22/ato-declaratorio-interpretativo-srf-nº-16-de-22-de-dezembro-de-2005
- https://www.mayerbrown.com/pt/insights/publications/2025/12/enactment-of-law-no-15270-2025-which-establishes-dividend-taxation-expands-the-exemption-threshold-and-introduces-a-minimum-tax-on-high-incomes
- https://coimbrachaves.com.br/lei-cria-irpf-minimo-e-irrf-sobre-dividendos-ao-exterior/
- https://www.mayerbrown.com/pt/insights/publications/2026/01/tbu-offset-of-taxes-paid-abroad-by-controlled-and-affiliated-companies-rfb-interpretative-declaratory-act-no-1-2026
- https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2023/lei/l14596.htm
- https://www.gov.br/inss/pt-br/assuntos/acordos-internacionais
- https://www.dvka.de/de/arbeitgeber_arbeitnehmer/abkommensstaaten/brasilien/brasilien.html

---

## 6. Direito do trabalho, previdência e imigração

### 6.1 Proteção contra dispensa (*Kündigungsschutzgesetz* — KSchG)

- Aplica-se a estabelecimentos com **mais de 10 empregados** (contagem em tempo integral: ≤ 20h/semana = 0,5; ≤ 30h = 0,75) — §23(1) KSchG — e após **6 meses** de vínculo (§1(1)).
- Dispensa só é válida se **socialmente justificada**: motivos (i) **pessoais** (*personenbedingt* — ex.: doença prolongada), (ii) **comportamentais** (*verhaltensbedingt* — em regra com advertência prévia, *Abmahnung*), (iii) **operacionais** (*betriebsbedingt*), com **seleção social** (*Sozialauswahl*: tempo de serviço, idade, dependentes, deficiência — §1(3)).
- Ação do empregado em **3 semanas** (§4 KSchG); caso contrário, dispensa se torna eficaz.
- Prática: acordos de rescisão com *Abfindung* (indenização) — referência de mercado 0,5 salário mensal por ano de serviço (§1a KSchG como parâmetro).
- **Forma escrita obrigatória** para dispensa e distrato (§623 BGB) — **assinatura manuscrita**, e-mail/digital inválidos.
- **Aviso prévio legal** (§622 BGB): 4 semanas até o dia 15 ou fim do mês; pelo empregador, progressivo até **7 meses** (após 20 anos). Período de experiência (*Probezeit*) ≤ 6 meses: 2 semanas.
- Proteções especiais: gestantes (§17 MuSchG), licença parental (§18 BEEG), deficientes graves (§168 SGB IX — aprovação do *Integrationsamt*), membros do *Betriebsrat* (§15 KSchG).
- **Dispensa coletiva** (§17 KSchG): notificação à Agência de Emprego.

### 6.2 Representação de trabalhadores e codeterminação

| Instituto | Regra | Base |
|---|---|---|
| **Betriebsrat** (conselho de empresa/comissão de fábrica) | Pode ser eleito por iniciativa dos empregados em estabelecimentos com **≥ 5 empregados** permanentes com direito a voto | §1 BetrVG |
| Direitos de **Mitbestimmung** (codeterminação) | Consentimento obrigatório em: horário, horas extras, regras de conduta, **sistemas técnicos de monitoramento (inclusive software/IA)**, remuneração variável, férias coletivas | §87 BetrVG |
| Consulta prévia à dispensa | Dispensa sem ouvir o BR é **nula** | §102 BetrVG |
| Contratação/transferência (> 20 empregados) | Consentimento do BR | §99 BetrVG |
| *Wirtschaftsausschuss* | Comissão econômica com > 100 empregados | §106 BetrVG |
| **Interessenausgleich / Sozialplan** | Reestruturações (*Betriebsänderung*) em empresas > 20 empregados | §§111–112 BetrVG |
| **Codeterminação no conselho** | **DrittelbG**: > 500 empregados → 1/3 do *Aufsichtsrat* por empregados (GmbH passa a ter conselho obrigatório); **MitbestG**: > 2.000 → paridade | DrittelbG; MitbestG 1976 |
| Convenções coletivas (*Tarifverträge*) | Vinculam membros de sindicatos/associações patronais; *Allgemeinverbindlicherklärung* possível | TVG |

### 6.3 Salário mínimo (*Mindestlohn*)

| Período | Valor bruto/hora | Base |
|---|---|---|
| 01/01/2025 | €12,82 | 4. MiLoAnpV |
| **01/01/2026** | **€13,90** ✅ confirmado | 5. *Mindestlohnanpassungsverordnung* (proposta da *Mindestlohnkommission* de 27/06/2025) |
| **01/01/2027** | **€14,60** | idem |

- Teto do **Minijob** (*geringfügige Beschäftigung*) acompanha o mínimo: **€603/mês em 2026**; €633/mês em 2027 (§8(1a) SGB IV). Empregador paga encargos fixos (~**30%**: 13% KV, 15% RV, 2% imposto fixo + contribuições U1/U2/U3) ⚠️ verificar percentuais; empregado em regra contribui 3,6% RV (opção de dispensa).
- **Midijob** (*Übergangsbereich*): €603,01–€2.000/mês, contribuições do empregado reduzidas (§20(2) SGB IV).
- Salários mínimos setoriais (construção, cuidados — *Pflegemindestlohn*) mais altos.

### 6.4 Jornada e registro (*Arbeitszeitgesetz* — ArbZG)

- Máximo **8h/dia**, extensível a **10h** se a média de 8h for respeitada em 6 meses/24 semanas (§3 ArbZG); semana de 6 dias úteis → 48h máx. média.
- Intervalo: 30 min (> 6h), 45 min (> 9h) (§4); descanso de 11h entre jornadas (§5); proibição de trabalho aos domingos/feriados com exceções (§§9–10).
- **Registro de jornada (*Arbeitszeiterfassung*)**: obrigação geral reconhecida pelo **BAG** (Tribunal Federal do Trabalho), decisão de **13/09/2022 (1 ABR 22/21)**, com base no §3(2) nº 1 ArbSchG e no acórdão TJUE C-55/18 (CCOO, 14/05/2019). Projeto de reforma do ArbZG (registro eletrônico; flexibilização para **limite semanal** em vez de diário — previsto no acordo de coalizão 2025) ⚠️ verificar se aprovado até 11/2026.
- **Férias** mínimas: 24 dias úteis (semana de 6 dias) = **20 dias** em semana de 5 dias (§3 BUrlG); usual 25–30 dias.
- **Continuidade salarial em doença**: 6 semanas pagas pelo empregador (§3 EFZG); depois *Krankengeld* pela caixa de saúde. Desde 2023: atestado eletrônico (eAU).

### 6.5 Contratos de trabalho (*Nachweisgesetz* — NachwG)

- Contrato pode ser verbal, mas o empregador deve entregar documento com condições essenciais (§2 NachwG — reformada em **01/08/2022** pela Diretiva (UE) 2019/1152): partes, início, duração, local, função, remuneração com componentes, jornada, horas extras, férias, aviso prévio e procedimento de dispensa (incluindo o prazo de 3 semanas para ação), convenções aplicáveis.
- Desde **01/01/2025** (BEG IV) a **forma de texto** (*Textform*, ex.: PDF por e-mail) é suficiente, salvo setores do §2a SchwarzArbG (construção, hotelaria, transporte etc.) e se o empregado solicitar por escrito ⚠️ verificar detalhes.
- Multa: até €2.000 por infração (§4 NachwG).
- **Contrato por prazo determinado** (*Befristung*): sem motivo até **2 anos** com até 3 prorrogações (§14(2) TzBfG), forma escrita **antes** do início (§14(4)); empresas novas: até 4 anos (§14(2a)).
- **Lei aplicável** a contrato com empregado na Alemanha: escolha é possível (Roma I, art. 8), mas não afasta normas imperativas alemãs (KSchG, MiLoG, ArbZG, BUrlG).
- **AGG** (*Allgemeines Gleichbehandlungsgesetz* — antidiscriminação): indenização em recrutamento discriminatório (até 3 salários).
- **Entgelttransparenzgesetz** — transposição da Diretiva (UE) 2023/970 de transparência salarial até **07/06/2026**; ⚠️ verificar lei alemã aprovada (obrigações de faixas salariais em anúncios, direito à informação, relatórios de gap ≥ 100 empregados).

### 6.6 Seguridade social (*Sozialversicherung*) — 2026

| Ramo | Alíquota total | Empregado / Empregador | Teto mensal (*Beitragsbemessungsgrenze* — BBG) |
|---|---|---|---|
| **Aposentadoria** (*Rentenversicherung* — RV) | **18,6%** | 9,3% / 9,3% | **€8.450** (uniforme Leste/Oeste; €101.400/ano) |
| **Desemprego** (*Arbeitslosenversicherung* — AV) | **2,6%** | 1,3% / 1,3% | €8.450 |
| **Saúde** (*Krankenversicherung* — KV) | **14,6%** + *Zusatzbeitrag* médio **2,9%** (2026; varia por caixa) | Metade cada (paritário) | **€5.812,50** (€69.750/ano) |
| **Cuidados de longa duração** (*Pflegeversicherung* — PV) | **3,6%**; sem filhos > 23 anos: +0,6 p.p. (empregado) → 4,2%; redução de 0,25 p.p. por filho do 2º ao 5º (< 25 anos) | 1,8% / 1,8% (+ adicional do empregado; Saxônia: divisão diferente) | €5.812,50 |
| **Acidentes** (*Unfallversicherung*) | Variável por *Berufsgenossenschaft* (setor de risco) | 100% empregador | Variável |
| Contribuições complementares (empregador) | *Insolvenzgeldumlage* **0,15%**; U1 (doença, empresas ≤ 30 empregados) e U2 (maternidade) variáveis | Empregador | — |

- **Versicherungspflichtgrenze** (limite acima do qual o empregado pode optar por seguro-saúde privado — PKV): **€6.450/mês** (€77.400/ano) em 2026.
- **Bezugsgröße** 2026: €47.460/ano.
- Encargos totais aproximados: **~21% do salário para o empregador** e ~21% para o empregado (até os tetos).
- Folha: *Lohnsteuer* (retenção de IR) declarada/recolhida mensalmente até o **10º dia** (*Lohnsteuer-Anmeldung*, §41a EStG); contribuições sociais devidas no **antepenúltimo dia útil** do mês corrente (§23(1) SGB IV).
- Valores 2027 já publicados (SV-Rechengrößenverordnung 2027, set/2026) ⚠️ não incorporados.

### 6.7 Falsa autonomia (*Scheinselbstständigkeit*)

- Critério: integração na organização do contratante e sujeição a instruções (*Weisungsgebundenheit*) → vínculo de emprego (§7(1) SGB IV; §611a BGB).
- Consequências: contribuições retroativas (até **4 anos**, **30 anos** se dolo — §25 SGB IV), responsabilidade do empregador por ambas as partes, crime (§266a StGB), *Lohnsteuer* retroativo.
- Prevenção: **Statusfeststellungsverfahren** junto à *Deutsche Rentenversicherung Clearingstelle* (§7a SGB IV), inclusive prognóstico antes do início.
- Decisão **BSG 2022 ("Herrenberg")** sobre professores de música e alterações (§127 SGB IV transitório até 2026) ⚠️.
- **Trabalhadores remotos no Brasil** de empresa alemã: em regra sujeitos à lei/previdência brasileira (CLT/INSS) — risco de vínculo empregatício no Brasil e de estabelecimento permanente brasileiro.
- **Contratação de prestadores brasileiros para trabalho na Alemanha**: exige título de residência que permita atividade autônoma (§21 AufenthG) ⚠️.

### 6.8 Imigração laboral (*Fachkräfteeinwanderungsgesetz* — FEG)

Reforma de 2023 (BGBl. 2023 I Nr. 217), escalonada em **18/11/2023, 01/03/2024 e 01/06/2024**.

| Título | Requisitos-chave | Base |
|---|---|---|
| **Blaue Karte EU** (Cartão Azul) | Diploma superior reconhecido (ou equivalente; profissionais de TI com 3 anos de experiência sem diploma); oferta de emprego com salário ≥ **€50.700/ano (2026)**; profissões em escassez (*Engpassberufe*), recém-formados (≤ 3 anos) e TI: ≥ **€45.934,20/ano** (com aprovação da BA). Residência permanente após 27 meses (21 com alemão B1) | §18g AufenthG |
| *Fachkraft* com formação profissional/acadêmica | Qualificação reconhecida; qualquer emprego qualificado | §§18a, 18b AufenthG |
| **Chancenkarte** (Cartão de Oportunidade) | Desde **01/06/2024**: busca de emprego por até 1 ano; sistema de pontos (qualificação, idade, idioma, experiência, vínculo com a Alemanha) — mín. 6 pontos; meio de subsistência comprovado; permite trabalho de até 20h/semana | §20a AufenthG |
| *Anerkennungspartnerschaft* | Trabalho enquanto se reconhece a qualificação | §16d AufenthG |
| Experiência profissional (*Erfahrungssäule*) | 2 anos de experiência + formação reconhecida no país de origem + salário ≥ 45% da BBG RV (~€45.630 em 2026 ⚠️) ou empregador com convenção | §19c(2) AufenthG c/c BeschV §6 |
| Transferência intra-grupo (**ICT-Karte**) | Gestores/especialistas/trainees de grupo brasileiro transferidos à subsidiária alemã > 90 dias (até 3 anos) | §19 AufenthG (Diretiva 2014/66/UE) |
| Autônomo/empreendedor | Interesse econômico ou necessidade regional; plano de negócios; financiamento | §21 AufenthG |
| Viagens de negócios | Brasileiros dispensados de visto para estadas ≤ **90 dias em 180** (Schengen) para reuniões, feiras, negociações — **não** para trabalho produtivo (§30 BeschV lista atividades permitidas). **EES** (registro eletrônico de entradas/saídas) em operação desde **12/10/2025**; **ETIAS** previsto para o **último trimestre de 2026** ⚠️ verificar data | Reg. (UE) 2018/1806; 2017/2226; 2018/1240 |

- Reconhecimento de diplomas: portal *anabin* / ZAB (KMK); profissões regulamentadas (médicos, engenheiros com título protegido) exigem reconhecimento formal.
- **Naturalização**: lei de 2024 (StARModG, em vigor 27/06/2024) admite dupla cidadania; prazo de 5 anos (a via expressa de 3 anos foi **revogada** em 2025 ⚠️ verificar).

**Fontes (Seção 6):**
- https://www.gesetze-im-internet.de/kschg/
- https://www.gesetze-im-internet.de/betrvg/
- https://www.gesetze-im-internet.de/arbzg/
- https://www.gesetze-im-internet.de/nachwg/
- https://www.bundesregierung.de/breg-de/aktuelles/mindestlohn-steigt-2391010
- https://www.deutsche-rentenversicherung.de/DRV/DE/Ueber-uns-und-Presse/Presse/Meldungen/2025/250910-sv-rechengroessen-vo-2026.html
- https://www.tk.de/firmenkunden/service/fachthemen/fachthema-beitraege/sozialversicherungs-rechengroessen-2026-2203234
- https://www.haufe.de/personal/entgelt/beitragssaetze-zur-sozialversicherung_78_493770.html
- https://www.make-it-in-germany.com/de/visum-aufenthalt/arten/blaue-karte-eu
- https://www.rtpartner.de/immigration/blaue-karte-eu-mindestgehalt-2026/
- https://www.gesetze-im-internet.de/aufenthg_2004/

---

## 7. Contratos e solução de disputas

### 7.1 Direito contratual geral (BGB) e cláusulas padrão (*AGB-Recht*)

- **AGB** (*Allgemeine Geschäftsbedingungen* — condições gerais): cláusulas pré-formuladas para uso múltiplo (≥ 3 vezes), impostas por uma parte (§305(1) BGB). Cláusulas **individualmente negociadas** (*Individualabrede*, §305b) prevalecem — mas o ônus de provar a negociação real ("*ernsthaftes Aushandeln*", disposição efetiva de alterar o núcleo) é alto.
- **Controle de conteúdo** (*Inhaltskontrolle*, §307 BGB): nulidade de cláusulas que desfavoreçam desproporcionalmente a contraparte contra a boa-fé, especialmente se incompatíveis com o modelo legal (*gesetzliches Leitbild*). Listas de proibições §§308 e 309 aplicam-se a B2C, mas **no B2B (§310(1) BGB) funcionam como indício** de nulidade via §307 — *ponto de grande diferença com o Brasil*.
- **Exemplos de cláusulas B2B frequentemente nulas:** limitação de responsabilidade por **dolo/culpa grave** ou por danos à vida/saúde; limitação de responsabilidade por violação de deveres essenciais (*Kardinalpflichten*) abaixo do dano típico previsível; prazos de garantia excessivamente reduzidos; multas contratuais desproporcionais; inversão do ônus da prova; renúncia a compensação/retensão sem exceção para créditos incontroversos.
- **Batalha de formulários** (*battle of forms*): teoria do *knock-out* — cláusulas conflitantes não se aplicam, valendo a lei supletiva.
- **Consequência da nulidade:** cláusula cai, contrato subsiste com o direito supletivo (§306 BGB); **proibição de redução conservadora da validade** (*Verbot der geltungserhaltenden Reduktion*).
- Reforma: há debate (iniciativa *Frankfurter Initiative*, acordo de coalizão 2025) para **flexibilizar o AGB-Recht no B2B de grande porte** ⚠️ sem lei aprovada até 11/2026.
- Brasileiros frequentemente optam por **lei suíça** ou arbitragem para evitar o AGB-Recht; ⚠️ escolher lei estrangeira em contrato puramente doméstico alemão não afasta normas imperativas (Roma I, art. 3(3)).
- **Prescrição** geral: **3 anos** a partir do fim do ano em que surgiu o direito e o credor teve conhecimento (§§195, 199 BGB); defeitos na compra e venda: 2 anos (§438 BGB).
- **Juros de mora B2B:** taxa básica (*Basiszinssatz*) + **9 p.p.** (§288(2) BGB) + **€40** de lump-sum (§288(5)); prazo de pagamento > 60 dias em AGB presume-se inadequado (§271a BGB).

### 7.2 Direito comercial (HGB)

- **Dever de inspeção e reclamação** (*Untersuchungs- und Rügepflicht*, §377 HGB): entre comerciantes, o comprador deve inspecionar e reclamar de vícios **imediatamente** (*unverzüglich* — dias); omissão = aceitação → crucial para exportadores e importadores brasileiros.
- **Silêncio** em carta de confirmação comercial (*kaufmännisches Bestätigungsschreiben*) pode gerar contrato.
- **Prokura** (procuração comercial ampla, registrada — §§48 ss. HGB) e *Handlungsvollmacht* (§54 HGB).

### 7.3 Representante comercial (*Handelsvertreter*, §§84–92c HGB)

- Base na Diretiva 86/653/CEE.
- **Indenização de clientela** (*Ausgleichsanspruch*, **§89b HGB**): ao término do contrato, o agente tem direito a indenização pelos clientes captados de que o principal continua se beneficiando; **teto: 1 remuneração anual média dos últimos 5 anos**; prazo para reclamar: **1 ano** após o término; **não pode ser excluída antecipadamente** (§89b(4)). TJUE (C-338/14, *Quenon*; C-315/14 *Marchon*) e BGH ampliam aplicação analógica a **distribuidores** (*Vertragshändler*) integrados à rede do fornecedor e obrigados a transferir a base de clientes.
- **Exceção relevante (§92c HGB):** se o representante atua **fora da UE/EEE**, as partes podem afastar as regras imperativas (inclusive §89b) — útil para principal alemão com agente no **Brasil** (onde, porém, vale a Lei 4.886/1965 com indenização de 1/12 das comissões — normas de ordem pública brasileiras!). Inversamente, **agente na Alemanha de exportador brasileiro: §89b é imperativo** (TJUE C-381/98, *Ingmar*), mesmo com lei brasileira escolhida.
- Aviso prévio: 1 mês no 1º ano, até 6 meses após 5 anos (§89 HGB).
- **Del credere** e comissões (§§86b, 87 HGB).

### 7.4 Compra e venda internacional (CISG)

- **Alemanha**: Estado-parte desde **01/01/1991**; **Brasil**: desde **01/04/2014** (Decreto 8.327/2014).
- Aplica-se automaticamente a contratos de compra e venda de mercadorias B2B entre partes nos dois países (art. 1(1)(a)), **salvo exclusão expressa** (art. 6) — cláusula "lei alemã" **não** exclui a CISG (que faz parte do direito alemão); para excluir: "*unter Ausschluss des UN-Kaufrechts*".
- Diferenças práticas vs. BGB: prazo "razoável" de notificação de vícios (art. 39 — limite 2 anos), *fundamental breach* para resolução (art. 25/49), responsabilidade objetiva limitada por previsibilidade (art. 74) e isenção (art. 79).
- **Incoterms® 2020** (ICC) — cláusula de entrega e transferência de riscos.

### 7.5 Arbitragem e jurisdição estatal

| Meio | Destaques |
|---|---|
| **DIS** (*Deutsche Institution für Schiedsgerichtsbarkeit*) | Regulamento DIS **2018**; sede usual: Frankfurt, Munique, Hamburgo, Berlim, Colônia; regras para procedimentos acelerados; DIS Sports/Supplementary Rules |
| Lei de arbitragem | §§1025–1066 ZPO (Lei Modelo UNCITRAL); reforma da lei de arbitragem (*Modernisierung des Schiedsverfahrensrechts*) — projeto de 2024/2025 permitindo procedimentos em inglês perante tribunais estatais de apoio e publicação de sentenças ⚠️ verificar aprovação |
| Outras câmaras | ICC (Paris), Swiss Rules, CAM-CCBC (Brasil — Câmara de Comércio Brasil-Canadá) e **Câmara de Arbitragem da AHK/Câmara Brasil-Alemanha** ⚠️ verificar se ainda ativa |
| **Commercial Courts / Commercial Chambers** | *Justizstandort-Stärkungsgesetz* (BGBl. 2024 I Nr. 302 ⚠️), em vigor em **01/04/2025** (§§184a, 611 ss. ZPO; §§119b GVG): os *Länder* podem criar **Commercial Courts** nos tribunais regionais superiores (*Oberlandesgerichte*) como 1ª instância para disputas B2B com valor ≥ **€500.000** (mediante acordo das partes), com processo **integralmente em inglês**, *case management* e recurso ao BGH; e **Commercial Chambers** nos *Landgerichte* (processos em inglês). Já instalados: Baden-Württemberg (Stuttgart/Mannheim), Hamburgo, Hesse (Frankfurt), NRW (Düsseldorf), Baviera (Munique), Berlim, Baixa Saxônia ⚠️ verificar lista atual |
| Processo civil comum | Tribunais: *Amtsgericht* (até €5.000 — elevado para **€10.000** a partir de 2026 ⚠️ verificar), *Landgericht* (Câmara Comercial — *Kammer für Handelssachen*), OLG, BGH |

### 7.6 Reconhecimento e execução transfronteiriços

| Situação | Regime |
|---|---|
| **Sentença arbitral** brasileira na Alemanha | **Convenção de Nova York** de 1958 (Alemanha parte desde 1961; §1061 ZPO) — reconhecimento pelo OLG |
| Sentença arbitral alemã no Brasil | Convenção de Nova York (Brasil: Decreto **4.311/2002**); homologação pelo **STJ** (arts. 34–40 Lei 9.307/1996) |
| **Sentença judicial brasileira** na Alemanha | **Sem tratado bilateral** ⚠️; reconhecimento pelo §328 ZPO (competência internacional, citação regular, ordem pública, **reciprocidade** — *Verbürgung der Gegenseitigkeit*, §328(1) nº 5); a doutrina/jurisprudência alemã majoritariamente **reconhece reciprocidade com o Brasil** (o STJ homologa sentenças alemãs) ⚠️ verificar; execução via *Vollstreckungsurteil* (§§722, 723 ZPO) |
| Sentença judicial alemã no Brasil | **Homologação pelo STJ** (art. 105, I, "i" CF; arts. 960–965 CPC; RISTJ arts. 216-A ss.) — sem exigência de reciprocidade |
| Convenção da Haia de 2019 (Sentenças) | **UE** parte (vigente desde **01/09/2023**); **Brasil** assinou ⚠️ (data e ratificação não confirmadas) → ainda não aplicável Brasil–Alemanha ⚠️ |
| Convenção da Haia de 2005 (Eleição de foro) | UE parte; Brasil **não** parte |
| Citação | Convenção da Haia de 1965 (Citação) — Brasil aderiu (vigente 01/06/2019); Alemanha exige **tradução para o alemão** e via autoridade central; Convenção de Haia de 1970 (Provas) — ambos partes |
| **Apostila** | Convenção da Haia de 1961 — Brasil desde **14/08/2016**; Alemanha parte → documentos brasileiros para *Handelsregister*/notário exigem **apostila + tradução juramentada** (*beeidigter Übersetzer*) |
| Dentro da UE | Regulamento Bruxelas I-bis (1215/2012) — execução automática entre Estados-membros |

**Dica para o Advogado:** em contratos Brasil–Alemanha, **arbitragem** é preferível à jurisdição estatal: execução via Nova York nos dois países é mais previsível que o §328 ZPO/homologação STJ.

**Fontes (Seção 7):**
- https://www.gesetze-im-internet.de/bgb/__307.html
- https://www.gesetze-im-internet.de/bgb/__310.html
- https://www.gesetze-im-internet.de/hgb/__89b.html
- https://www.gesetze-im-internet.de/hgb/__92c.html
- https://www.gesetze-im-internet.de/zpo/__328.html
- https://www.disarb.org
- https://cms.law/de/deu/legal-updates/einfuehrung-von-commercial-courts-bundestag-beschliesst-justizstandort-staerkungsgesetz
- https://www.morganlewis.com/de/pubs/2025/07/the-introduction-of-commercial-courts-and-commercial-chambers-in-germany
- https://www.gleisslutz.com/sites/default/files/static/2026-10/justizstandort-staerkungsgesetz_tabelle_updated_2_october_2026.pdf
- https://uncitral.un.org/en/texts/salegoods/conventions/sale_of_goods/cisg/status
- https://www.hcch.net/en/instruments/conventions/status-table/?cid=137

---

## 8. UE e compliance

### 8.1 Proteção de dados — GDPR/DSGVO

- **DSGVO** (*Datenschutz-Grundverordnung* = Regulamento (UE) 2016/679) + **BDSG** (lei federal complementar) + **TDDDG** (cookies/telemídia, antiga TTDSG, desde 14/05/2024).
- **Encarregado (DPO — *Datenschutzbeauftragter*)**: obrigatório na Alemanha quando **≥ 20 pessoas** tratam dados pessoais de forma automatizada de modo permanente (§38 BDSG) — limite mais rígido que o GDPR.
- Sanções: até **€20 milhões ou 4%** do faturamento mundial (art. 83 GDPR). Autoridades estaduais (*Landesdatenschutzbehörden*) + BfDI federal.
- **Decisão de adequação mútua UE–Brasil:** ✅ **adotada**. A Comissão adotou a **Decisão de Execução (UE) 2026/179** (art. 45 GDPR) em **26/01/2026**, em vigor a partir de **28/01/2026** ⚠️ (data exata de entrada em vigor a confirmar no JO), reconhecendo a **LGPD** como essencialmente equivalente. Em paralelo, a **ANPD** emitiu a **Resolução CD/ANPD nº 32/2026** (26–27/01/2026) reconhecendo a UE como adequada (art. 33, I LGPD). Efeito: transferências **UE ↔ Brasil** sem necessidade de cláusulas contratuais padrão (SCC) ou BCR. Exclusões: tratamento exclusivamente para segurança pública, defesa, investigação criminal. Revisão periódica (4 anos).
- Na prática: mantêm-se DPA (art. 28), registros de tratamento (art. 30), DPIA etc.; empresa brasileira que oferece bens/serviços a pessoas na UE continua sujeita ao GDPR (art. 3(2)) e deve nomear **representante na UE** (art. 27).
- **Data Act** (Reg. (UE) 2023/2854) aplicável desde **12/09/2025**; **NIS-2** transposta na Alemanha (*NIS2UmsuCG*) ⚠️ promulgada em fins de 2025 — verificar; **Digital Omnibus** (nov/2025) propôs ajustes ao GDPR ⚠️ em tramitação.

### 8.2 Cadeias de fornecimento: LkSG

- **Lieferkettensorgfaltspflichtengesetz** (lei de devida diligência em cadeias de fornecimento): vigente desde **01/01/2023** (≥ 3.000 empregados na Alemanha) e desde **01/01/2024** para **≥ 1.000 empregados** na Alemanha (inclusive filiais de estrangeiras).
- Deveres: gestão de riscos, análise de riscos anual, declaração de princípios, medidas preventivas e corretivas, canal de denúncias, documentação (§§3–10 LkSG). Fiscalização: **BAFA**; multas até 2% do faturamento médio anual (> €400 milhões) e exclusão de licitações.
- **Reforma em tramitação:** projeto do governo (Kabinett **03/09/2025**; BT-Drs. 21/2474; 1ª leitura **16/01/2026**) para **eliminar retroativamente a obrigação de relatório** (§10(2)–(4)) e restringir multas a violações graves; em **02/07/2026** a coalizão acordou restringir o escopo a **≥ 5.000 empregados e > €1,5 bilhão** (alinhado à CSDDD pós-Omnibus). ⚠️ **Até 11/2026 não confirmada promulgação**. O BAFA **suspendeu** a análise de relatórios (§§12–13) desde fins de 2025.
- **Impacto para brasileiros:** fornecedores brasileiros de grupos alemães (agro, mineração, autopeças) recebem **cláusulas contratuais de compliance**, questionários e auditorias (*code of conduct*, *flow-down*). Atenção a cláusulas AGB que transferem riscos de forma desproporcional (§307 BGB).

### 8.3 CSDDD (Diretiva (UE) 2024/1760) após Omnibus I

- **Omnibus I** (Diretiva (UE) 2026/470): escopo restrito a empresas UE com **> 5.000 empregados e > €1,5 bilhão** de faturamento mundial; empresas **não-UE** com **> €1,5 bilhão** de faturamento **na UE**.
- **Transposição até 26/07/2028**; aplicação a partir de **26/07/2029**.
- Mudanças: foco em parceiros diretos (*tier 1*) com abordagem baseada em risco; eliminação do regime harmonizado de responsabilidade civil da UE; planos de transição climática **suprimidos** como obrigação de implementação ⚠️; multas máximas de **3%** do faturamento mundial ⚠️ verificar.

### 8.4 EU AI Act (Regulamento (UE) 2024/1689)

| Data | Obrigação |
|---|---|
| 01/08/2024 | Entrada em vigor |
| **02/02/2025** | Práticas proibidas (art. 5) e alfabetização em IA (*AI literacy*, art. 4) |
| **02/08/2025** | Modelos de IA de uso geral (GPAI), governança, sanções; Código de Prática GPAI (jul/2025) |
| **02/08/2026** | Obrigações de transparência (art. 50) — prazo adicional até **02/12/2026** para *watermarking* de sistemas generativos já no mercado |
| **02/12/2027** | Sistemas de **alto risco do Anexo III** (emprego/RH, crédito, educação, biometria) — **adiado** de 02/08/2026 pelo **Digital Omnibus sobre IA** (Regulamento (UE) **2026/1744**, publicado no JO em 24/07/2026, em vigor 27/07/2026) ⚠️ verificar número |
| **02/08/2028** | Alto risco do **Anexo I** (produtos regulados — máquinas, dispositivos médicos) — adiado de 02/08/2027 |

- Multas: até **€35 milhões / 7%** (práticas proibidas). Autoridade alemã: **Bundesnetzagentur** (lei de implementação — *KI-MIG* ⚠️ verificar aprovação).
- Para RH na Alemanha: uso de IA em recrutamento exige também **consentimento do Betriebsrat** (§87(1) nº 6 BetrVG; §90, §95 BetrVG).

### 8.5 CBAM (Regulamento (UE) 2023/956)

- **Fase transitória** (apenas relatórios trimestrais): 01/10/2023 – 31/12/2025.
- **Fase definitiva: desde 01/01/2026** — importações de **ferro e aço, alumínio, cimento, fertilizantes, hidrogênio e eletricidade** exigem *declarante CBAM autorizado* (*zugelassener CBAM-Anmelder*; na Alemanha: **DEHSt** — Umweltbundesamt).
- **Omnibus CBAM** (Regulamento (UE) **2025/2083**, out/2025): **isenção de minimis de 50 toneladas/ano** por importador (por massa, substitui o limite de €150), que exclui ~90% dos importadores mantendo ~99% das emissões; **venda de certificados** a partir de **01/02/2027**; **primeira declaração anual e entrega** de certificados (relativos a 2026) até **30/09/2027**; preço dos certificados 2026 = média **trimestral** dos leilões EU ETS (Q1/2026: €75,36; Q2: €75,28; Q3: €82,32 ⚠️ verificar Comissão).
- **Redução gradual da alocação gratuita** do EU ETS (fase-in do CBAM): 2,5% em 2026 → 100% em 2034.
- **Impacto Brasil:** exportações de **aço semiacabado e ferro-gusa** (MG, ES, PA), **alumínio** (primário e laminados) e **fertilizantes** (nitrogenados) — o importador europeu repassará o custo; exportadores devem fornecer **dados verificados de emissões incorporadas** (*embedded emissions*, por instalação) para evitar valores-padrão (*default values*, com *mark-up* progressivo a partir de 2026). Preço de carbono pago no Brasil (SBCE — Lei 15.042/2024, ainda em implementação) poderá ser deduzido no futuro (art. 9 CBAM) ⚠️.
- Expansão proposta (dez/2025) para produtos a jusante (*downstream*) e medidas anti-elusão ⚠️ em tramitação.

### 8.6 EUDR — Regulamento (UE) 2023/1115 (produtos livres de desmatamento)

- Commodities: **soja, carne bovina, café, cacau, óleo de palma, borracha, madeira** e derivados (couro, chocolate, móveis, papel…). Data de corte: **31/12/2020** (sem desmatamento após).
- **Adiamentos:** (i) Regulamento (UE) 2024/3234 → dez/2025; (ii) **Regulamento (UE) 2025/2650** (aprovado pelo Conselho em **18/12/2025**): aplicação a **grandes e médios operadores a partir de 30/12/2026** e a **micro e pequenas empresas a partir de 30/06/2027** (exceto setor de madeira já sob EUTR: 30/12/2026); produtos novos no Anexo I: 30/12/2027.
- Simplificações: somente o **primeiro operador que coloca no mercado** apresenta a declaração de devida diligência (*due diligence statement*); operadores a jusante apenas coletam números de referência; categoria de **micro e pequenos produtores primários** de países de **baixo risco** com declaração única simplificada; revisão de simplificação até **30/04/2026** ⚠️ (pode ter gerado nova proposta — verificar).
- **Classificação de risco por país** (Reg. de Execução (UE) 2025/1093, maio/2025): **Brasil = "risco padrão"** (*standard risk*) → devida diligência completa, controles de 3% dos operadores ⚠️ verificar atualização.
- **Exigências práticas para o agro brasileiro:** geolocalização (coordenadas/polígonos > 4 ha) de todas as parcelas de produção, prova de legalidade segundo a lei brasileira (Código Florestal, CAR, direitos indígenas/trabalhistas), segregação/rastreabilidade na cadeia (soja e café em *bulk* são o maior desafio), *Selo Verde*/plataformas de rastreabilidade (ex.: Agro Brasil + Sustentável) ⚠️.
- Autoridade competente alemã: **BLE** (*Bundesanstalt für Landwirtschaft und Ernährung*); lei nacional de implementação (*EUDR-Durchführungsgesetz*) ⚠️.

### 8.7 Lavagem de dinheiro (*Geldwäschegesetz* — GwG) e Transparenzregister

- GwG (2017, reformada): obrigados — bancos, notários, advogados (em certas transações), *Steuerberater*, imobiliárias, comerciantes de bens com pagamentos em dinheiro ≥ €10.000 (€2.000 para metais preciosos).
- **Transparenzregister** (§§18 ss. GwG): obrigatório para todas as pessoas jurídicas e sociedades registradas; beneficiário final (> 25%) com nome, data de nascimento, residência, nacionalidade, natureza do interesse. Acesso público suspenso após decisão do TJUE (C-37/20 e C-601/20, **22/11/2022**) — hoje acesso mediante **interesse legítimo** ⚠️.
- **Sociedades estrangeiras que adquirem imóveis na Alemanha** devem se registrar no Transparenzregister (§20(1) frase 2 GwG) — **holding brasileira** comprando imóvel alemão: obrigação direta; desde 2023 **proibição de pagamento em dinheiro** na compra de imóveis (§16a GwG; *Sanktionsdurchsetzungsgesetz II*).
- **Pacote AML da UE**: Regulamento (UE) 2024/1624 (*Single Rulebook*, aplicação **10/07/2027**), Diretiva 2024/1640 (AMLD6), **AMLA** (sede: **Frankfurt**, operando desde 07/2025).
- Limite de pagamento em dinheiro da UE: **€10.000** a partir de 07/2027 (Reg. 2024/1624).

### 8.8 Controle de investimentos estrangeiros (AWG/AWV)

- **Außenwirtschaftsgesetz** (AWG) e **Außenwirtschaftsverordnung** (AWV); autoridade: **BMWE** (*Bundesministerium für Wirtschaft und Energie*).
- **Controle setorial** (§§60 ss. AWV): defesa/criptografia — aquisição de **≥ 10%** por qualquer estrangeiro (não-alemão) → notificação obrigatória e efeito suspensivo.
- **Controle intersetorial** (§§55 ss. AWV): investidores **não-UE/EFTA** (inclui **Brasil**):
  - **Notificação obrigatória** (*Meldepflicht*, §55a AWV) e proibição de *closing* antes da aprovação para **infraestruturas críticas e 27 setores** (energia, TI, telecomunicações, mídia, saúde, semicondutores, IA, robótica, matérias-primas críticas, segurança alimentar ⚠️ verificar lista do §55a AWV): limite **10%** (infraestrutura crítica, software para KRITIS, telecom etc.) ou **20%** (demais setores sensíveis); acréscimos a 25%, 40%, 50%, 75%.
  - Demais setores: revisão *ex officio* a partir de **25%** dos votos, até 5 anos após a assinatura.
- Prazos: 2 meses (fase 1) + 4 meses (fase 2, prorrogável).
- **Investitionsprüfungsgesetz** — nova lei autônoma de controle de investimentos planejada (projeto 2025/2026) ⚠️ verificar; revisão do **Regulamento UE de triagem de IED** (2019/452) — acordo político dez/2025 ⚠️.
- **Controle de exportação**: Regulamento (UE) 2021/821 (dual use) e BAFA; sanções contra Rússia/Belarus (cláusula "*no Russia*", art. 12g Reg. 833/2014) em contratos de exportação para países terceiros, **inclusive o Brasil**.

### 8.9 Outras normas relevantes

- **Hinweisgeberschutzgesetz** (HinSchG, proteção a denunciantes): canal interno obrigatório para empregadores com **≥ 50 empregados** (desde 17/12/2023).
- **Verpackungsgesetz** (embalagens): registro no **LUCID** (*Zentrale Stelle Verpackungsregister*) **antes** de vender produtos embalados na Alemanha (inclusive vendedores estrangeiros/online); PPWR (Reg. (UE) 2025/40) aplicável a partir de **12/08/2026**.
- **ElektroG** (eletroeletrônicos, registro EAR), **BattDG**/Reg. Baterias 2023/1542, **Produktsicherheitsverordnung** GPSR (Reg. 2023/988, desde 13/12/2024 — exige operador econômico responsável na UE).
- **Lei de concorrência** (GWB): controle de concentrações (receita mundial > €500 milhões; um participante > €50 milhões e outro > €17,5 milhões na Alemanha); §19a GWB (plataformas).
- **Forced Labour Regulation** (Reg. (UE) 2024/3015): proibição de produtos de trabalho forçado a partir de **14/12/2027**.

**Fontes (Seção 8):**
- https://www.whitecase.com/insight-alert/mutual-adequacy-between-eu-and-brazil-new-era-transatlantic-data-transfers
- https://www.mayerbrown.com/en/insights/publications/2026/02/a-new-era-for-personal-data-transfers-brazil-and-european-union-establish-mutual-adequacy-decision
- https://www.edpb.europa.eu/system/files/2025-11/edpb_opinion_202528_brazil_adequacy_en_0.pdf
- https://www.gesetze-im-internet.de/lksg/
- https://www.bafa.de/DE/Lieferketten/lieferketten_node.html
- https://www.ihk.de/nordwestfalen/international/lieferketten/aktuelles-zum-lksg-6724308
- https://www.twobirds.com/de/insights/2026/germany/lksg--csddd--was-planen-bundesregierung-und-eu
- https://www.gibsondunn.com/eu-ai-act-omnibus-agreement-postponed-high-risk-deadlines-and-other-key-changes/
- https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism_en
- https://www.dehst.de/DE/CBAM/cbam_node.html
- https://www.ble.de/DE/Themen/Wald-Holz/Entwaldungsfreie-Produkte/Aktuelles/Aktuelles_node.html
- https://www.ihk.de/regensburg/fachthemen/nachhaltiges-wirtschaften/nachrichten-zur-nachhaltigkeit/eudr-vereinfachung-und-verschiebung-beschlossen-6926444
- https://www.gesetze-im-internet.de/awv_2013/
- https://www.transparenzregister.de

---

## 9. Acordo Mercosul–União Europeia

### 9.1 Status jurídico (em 22/11/2026)

| Marco | Data / situação |
|---|---|
| Acordo político original | 28/06/2019 |
| Conclusão das negociações (texto revisto + instrumento adicional ambiental) | **06/12/2024** (Montevidéu) |
| Divisão em dois instrumentos | **EMPA** (*EU–Mercosur Partnership Agreement* — acordo misto: político, cooperação + comércio; exige ratificação dos 27 Estados-membros) e **iTA** (*Interim Trade Agreement* — acordo provisório de comércio, competência exclusiva da UE) — proposta da Comissão em **03/09/2025** |
| Decisão do Conselho autorizando assinatura e aplicação provisória | **09/01/2026** (maioria qualificada; França e outros contra ⚠️); publicada no JO em 27/02/2026 |
| **Assinatura** | **17/01/2026, Assunção (Paraguai)** ⚠️ (algumas fontes indicam 19/01) |
| Parlamento Europeu | Em **21/01/2026** aprovou (334 × 324, 11 abstenções) pedido de **parecer ao TJUE** (art. 218(11) TFUE) sobre compatibilidade com os Tratados → **consentimento do PE suspenso** até o parecer (expectativa: 18–24 meses). Em 11/2026, **sem parecer** do TJUE |
| Brasil | **Decreto Legislativo nº 14/2026** (promulgado pelo Congresso em **17/03/2026**); **Decreto nº 12.953, de 28/04/2026** (promulgação presidencial) ⚠️ verificar conteúdo |
| **Aplicação provisória do iTA** | **Desde 01/05/2026** entre a UE e **todos** os quatro membros do Mercosul (Brasil, Argentina, Uruguai, Paraguai), após a Comissão decidir (27/02/2026) prosseguir apesar da consulta ao TJUE |
| EMPA | Pendente: parecer TJUE + consentimento PE + ratificações nacionais (incl. **Bundestag/Bundesrat** na Alemanha) |
| Salvaguardas agrícolas | Regulamento bilateral de salvaguarda da UE para produtos agrícolas sensíveis (carne bovina, aves, açúcar, etanol, arroz) com monitoramento e gatilhos de preço/volume ⚠️ verificar número do regulamento (adoção início de 2026) |

**Risco jurídico:** se o TJUE emitir parecer negativo, a aplicação provisória pode ser questionada/encerrada; o iTA permanece aplicável até ser substituído pelo EMPA ou denunciado. A Alemanha (governo federal) apoiou fortemente o acordo.

### 9.2 Desgravação tarifária (síntese)

| Lado | Cobertura | Cronograma |
|---|---|---|
| **UE** liberaliza importações do Mercosul | ~**92%** das importações (≈ 95% das linhas) | Imediata para grande parte dos industriais; até **10 anos** (alguns 12) para demais; produtos agrícolas sensíveis por **cotas (TRQ)** |
| **Mercosul** liberaliza importações da UE | ~**91%** das importações (≈ 90% das linhas) | ~10% das linhas imediatamente (01/05/2026); demais em até **10–15 anos** (alguns 18 ⚠️) |

**Destaques para produtos alemães entrando no Brasil (interesse de importadores e de subsidiárias):**
- **Automóveis** (TEC 35%): eliminação em **15 anos** com período de carência ⚠️ (veículos elétricos/híbridos com cronograma específico mais longo ⚠️ verificar); **autopeças** (14–18%): maioria em 10 anos.
- **Máquinas e equipamentos** (até 20%), **produtos químicos** (até 18%), **farmacêuticos** (até 14%): maioria em 10–15 anos.
- Vinhos e destilados (até 35%), queijos (cota) e chocolate.
- **Compras governamentais**: acesso de empresas da UE a licitações federais brasileiras (com margens de preferência transitórias para MPEs/saúde ⚠️).

**Destaques para exportadores brasileiros:**

| Produto | Regime UE no acordo ⚠️ verificar valores no texto final |
|---|---|
| Carne bovina | TRQ de **99.000 t** (peso carcaça) para o Mercosul, tarifa intracota **7,5%**, implementada em **6 etapas** anuais |
| Aves | TRQ **180.000 t** isenta, em 6 etapas |
| Suínos | TRQ 25.000 t (€83/t) |
| Açúcar | TRQ **180.000 t** (cota específica para o Brasil, intracota zero) |
| Etanol | **450.000 t** (uso químico, isenta) + **200.000 t** (outros usos, 1/3 da tarifa) |
| Arroz | 60.000 t; mel 45.000 t; milho/sorgo 1 milhão t |
| **Café** | Café verde já isento; **torrado e solúvel**: eliminação em até 4 anos |
| Suco de laranja, frutas, peixes, óleos vegetais | Eliminação em 0–10 anos |
| Industriais (calçados, têxteis, químicos, autopeças) | Majoritariamente imediata |
| Impostos de exportação do Mercosul | Limitações aos *direitos de exportação* (impostos de exportação) com exceções (ex.: Argentina) ⚠️ |

### 9.3 Regras de origem e procedimentos

- **Regras específicas por produto** (Anexo de regras de origem): mudança de classificação tarifária, valor de materiais não originários (*max. non-originating content*), operações mínimas insuficientes; **acumulação bilateral** (UE–Mercosul); *drawback* permitido com limites ⚠️.
- **Autocertificação**: **declaração de origem** (*statement on origin*) pelo exportador na fatura ou documento comercial; na UE, exportadores devem estar registrados no **REX** (*Registered Exporter System*) para remessas > €6.000 ⚠️; no Mercosul, período transitório de certificação por entidades habilitadas ⚠️ verificar.
- Validade da prova: 12 meses ⚠️; guarda de documentos: 3–5 anos ⚠️.
- **Mercadorias em trânsito** em 01/05/2026: declaração de origem podia ser apresentada em até **6 meses** após o início da aplicação provisória.
- Indicações geográficas: proteção de ~350 IGs europeias (incl. alemãs: *Bayerisches Bier*, *Münchener Bier*, *Nürnberger Lebkuchen* ⚠️) no Mercosul; período de transição para usuários prévios de termos como "parmesão"/"gruyère".
- **Capítulo de comércio e desenvolvimento sustentável**: compromissos do Acordo de Paris como elemento essencial; o EUDR, CBAM e LkSG **não** são afastados pelo acordo; mecanismo de "reequilíbrio" (*rebalancing*) solicitado pelo Mercosul contra medidas unilaterais da UE ⚠️.

### 9.4 Impacto prático para empresas brasileiras

1. **Exportação para a Alemanha**: verificar a classificação NCM/NC e cronograma; emitir declaração de origem correta (erros → cobrança retroativa de direitos + multa); usar cotas via sistema de licenças de importação da UE (carne, aves, açúcar).
2. **Importação de bens de capital alemães**: redução gradual de tarifa encarece "esperar" — avaliar também *ex-tarifário*.
3. **Serviços e investimentos**: capítulos de serviços (estabelecimento, telecomunicações, financeiro, transporte marítimo) com tratamento nacional — facilitam subsidiárias e filiais.
4. **Compliance ESG persiste**: EUDR (dez/2026), CBAM (2026), LkSG/CSDDD, *Forced Labour Regulation* — o acordo **não** elimina essas exigências.
5. **Imposto**: o acordo **não** trata de bitributação — a ausência de ADT Brasil–Alemanha continua (Seção 5).

**Fontes (Seção 9):**
- https://taxation-customs.ec.europa.eu/news/provisional-application-eu-mercosur-interim-trade-agreement-begins-1-may-2026-2026-04-24_en
- https://policy.trade.ec.europa.eu/eu-trade-relationships-country-and-region/countries-and-regions/mercosur/eu-mercosur-agreement_en
- https://policy.trade.ec.europa.eu/eu-trade-relationships-country-and-region/countries-and-regions/mercosur/eu-mercosur-agreement/factsheet-provisional-application-eu-mercosur-agreement-how-export-agricultural-goods_en
- https://www.whitecase.com/insight-alert/eu-provisionally-apply-eu-mercosur-interim-trade-agreement-pending-cjeu-opinion
- https://www.europarl.europa.eu/pdfs/news/expert/2026/1/press_release/20260116IPR32450/20260116IPR32450_en.pdf
- https://www.realinstitutoelcano.org/en/commentaries/the-european-parliament-halts-the-eu-mercosur-agreement-in-court-what-is-at-stake/
- https://www12.senado.leg.br/noticias/materias/2026/03/17/congresso-promulga-acordo-mercosul-uniao-europeia
- https://www2.camara.leg.br/legin/fed/decleg/2026/decretolegislativo-14-17-marco-2026-798811-norma-pl.html
- https://www.gov.br/mdic/pt-br/assuntos/noticias/2026/marco/aprovacao-do-acordo-de-parceria-mercosul-uniao-europeia-pelo-congresso-nacional
- https://www.intereconomics.eu/contents/year/2026/number/3/article/eu-mercosur-trade-agreement-from-negotiations-to-application.html
- https://www.ahkbrasil.com

---

## 10. Checklists práticos

### 10.1 Abrir uma GmbH a partir do Brasil

1. **Estrutura**: decidir entre GmbH (subsidiária), *Zweigniederlassung* (filial) ou *Repräsentanz*; avaliar holding intermediária em país com ADT com Brasil e Alemanha (ex.: Holanda, Espanha, Áustria) — testar substância (§50d(3) EStG; CFC brasileira; PPT).
2. **Documentos do sócio PJ brasileiro**: contrato/estatuto social, certidão simplificada da Junta Comercial, ata de nomeação de representantes, **apostilados** (Convenção da Haia) e com **tradução juramentada** para o alemão; passaportes dos GFs e procuradores.
3. **Procuração notarial** (se o sócio não comparecer): lavrada em cartório brasileiro com apostila ou no consulado alemão (SP, RJ, POA, Recife ⚠️; embaixada Brasília).
4. **Nome empresarial**: consulta prévia à IHK (distintividade, §18 HGB) e ao DPMA/EUIPO (marcas).
5. **Escritura** no notário (presencial, por procurador ou videoconferência DiRUG) — contrato social, nomeação do GF, lista de sócios (*Gesellschafterliste*, §40 GmbHG).
6. **Conta bancária** (antecipar KYC: estrutura societária, beneficiários finais, origem dos recursos) → integralizar ≥ €12.500; considerar bancos digitais/estrangeiros com licença alemã.
7. **Registro** no *Handelsregister* (via notário) → GmbH nasce com o registro (antes: *Vorgesellschaft* com responsabilidade de quem age — *Handelndenhaftung*, §11(2) GmbHG).
8. **Transparenzregister**: inscrever beneficiário(s) final(is).
9. **Gewerbeanmeldung** + **Fragebogen zur steuerlichen Erfassung** (ELSTER) em 1 mês → Steuernummer, USt-IdNr.
10. **Banco Central do Brasil**: registro do investimento brasileiro direto no exterior — **declaração CBE** (Capitais Brasileiros no Exterior) anual se ativos ≥ US$ 1 milhão (trimestral ≥ US$ 100 milhões) (Resolução BCB 279/2022 ⚠️ verificar); contrato de câmbio para remessa do capital (Lei 14.286/2021).
11. **Receita Federal**: participação em controlada no exterior → consolidação/tributação dos lucros (Lei 12.973/2014, art. 77 — **ECF** registro X/Y), e-Financeira, DIRPF dos sócios PF.
12. **Steuerberater** contratado (escrituração DATEV, folha, UStVA); definir exercício social e moeda funcional.
13. **Transfer pricing**: contratos *intercompany* (distribuição, serviços, licença, *cost-sharing*) escritos, assinados **antes** das operações, coerentes com Lei 14.596/2023 e §1 AStG; documentação *Local File* ao atingir os limites.
14. **Seguros**: D&O, responsabilidade civil (*Betriebshaftpflicht*), seguro-saúde de expatriados.
15. **Imigração** do GF/expatriados: ICT-Karte, Blue Card ou §21 AufenthG; registro de residência (*Anmeldung*, §17 BMG) em 2 semanas.

### 10.2 Exportar do Brasil para a Alemanha

1. **Classificação NCM → NC (Nomenclatura Combinada da UE)** e tarifa no **TARIC**; confirmar redução pelo **iTA Mercosul–UE** (desde 01/05/2026) e emitir **declaração de origem** correta.
2. **Incoterms 2020**: definir quem é o importador de registro; em DDP, o exportador brasileiro precisa de **número EORI** e possivelmente registro de IVA alemão (IVA-importação).
3. **Compliance de produto**: marcação CE (máquinas, eletrônicos), GPSR (operador responsável na UE), REACH/CLP (químicos), **EUDR** (soja, café, carne, cacau, madeira, couro — a partir de 30/12/2026: geolocalização + due diligence), **CBAM** (aço, alumínio, fertilizantes — dados de emissões para o importador; limite de 50 t), regras sanitárias/fitossanitárias (SPS; estabelecimentos habilitados pelo MAPA e listados pela UE), **Verpackungsgesetz** (LUCID) e ElektroG para vendas diretas.
4. **Contratos**: CISG aplicável por padrão; cláusula de foro/arbitragem; atenção ao §377 HGB (reclamação imediata) a favor do comprador alemão; condições gerais submetidas ao AGB-Recht se lei alemã.
5. **Distribuidores/agentes na Alemanha**: §89b HGB imperativo (indenização de clientela) — precificar o custo de saída.
6. **IVA**: vendas B2B com entrega na Alemanha (importador alemão) — sem IVA para o exportador; venda B2C e-commerce ≤ €150 → **IOSS** com intermediário; > €150 → IVA-importação na entrega.
7. **Tributação brasileira da exportação**: imunidade/isenção de ICMS, IPI, PIS/Cofins (e futuramente CBS/IBS); câmbio de exportação; Drawback.
8. **Pagamentos**: carta de crédito, *Hermes*-like garantias (ECA); risco de crédito; juros de mora §288 BGB.
9. **Propriedade intelectual**: registrar marca na UE (EUIPO) ou internacional (Protocolo de Madri — Brasil desde 2019).

### 10.3 Remeter lucros da Alemanha para o Brasil

1. **Aprovação** das contas e deliberação de distribuição (*Gewinnverwendungsbeschluss*, §29 GmbHG); respeitar capital social (§30 GmbHG — proibição de devolução de capital) e solvência.
2. **Retenção na Alemanha**: KapESt **26,375%** no pagamento (recolhida pela GmbH até o 10º dia do mês seguinte ao pagamento — §44 EStG); emitir *Steuerbescheinigung*.
3. **Pedido de restituição de 2/5** ao **BZSt** (§44a(9) EStG) → carga final **15,825%**, desde que a sócia brasileira cumpra §50d(3) EStG (renda de atividade própria / substância); prazo ⚠️ 4 anos.
4. Alternativas: **filial** (sem retenção na remessa); **holding UE/EEE intermediária** com ADT/Diretiva Mães-Filhas (0% na Alemanha) — exige substância real; **juros** de empréstimo do sócio brasileiro (sem retenção alemã, mas dedutibilidade limitada por Zinsschranke e preços de transferência; no Brasil, juros recebidos são tributados a 34%), **royalties** (15,825% §50a; dedutíveis — cuidado com §4j EStG), **serviços** (sem retenção; dedutíveis se arm's length).
5. **No Brasil**: lucros da controlada já tributados em 31/12 pela regra de CFC (art. 77 Lei 12.973/2014 — 34% IRPJ/CSLL, com crédito do KSt + Soli; a creditabilidade da **GewSt** como tributo sobre a renda é discutida ⚠️ verificar); o dividendo recebido não é tributado novamente (já oferecido). O IRRF alemão é crédito no Brasil (art. 26 Lei 9.249/1995; art. 87 Lei 12.973/2014) até o limite do tributo brasileiro.
6. **Câmbio**: ingresso via contrato de câmbio; atualizar **CBE** e registro no BCB (RDE-IED/ CBE ⚠️).
7. **Sócio PF brasileiro**: se participação detida diretamente por PF, aplica-se a Lei 14.754/2023 (controladas no exterior — opção de transparência; tributação de 15% sobre lucros em 31/12 se *entidade controlada* com renda passiva > 60% ou não), crédito do imposto alemão via reciprocidade (ADI SRF 16/2005).

### 10.4 Contratar na Alemanha

1. Definir **empregador**: GmbH/filial (com *Betriebsnummer*) ou **Employer of Record** (EoR) — atenção à *Arbeitnehmerüberlassungsgesetz* (AÜG: cessão de mão de obra exige licença; prazo máximo 18 meses) ⚠️ EoR pode configurar AÜG.
2. **Contrato escrito** com cláusulas do NachwG; período de experiência ≤ 6 meses; *Befristung* escrita antes do início; cláusula de não concorrência pós-contratual exige **compensação ≥ 50%** da última remuneração (§§74 ss. HGB) — sem ela, nula/não vinculante.
3. **Salário ≥ €13,90/h** (2026), convenções coletivas aplicáveis; registro de jornada.
4. **Registro na seguridade social** (DEÜV) e na caixa de saúde escolhida pelo empregado; *Lohnsteuer* via ELStAM; *Berufsgenossenschaft*.
5. **Expatriados brasileiros**: certificado de deslocamento (acordo previdenciário — até 24 meses ⚠️) + seguro-saúde; título de residência (ICT, Blue Card); dupla residência fiscal e tributação unilateral (sem 183 dias); política de *tax equalization*.
6. **Proteção de dados do empregado** (§26 BDSG / art. 88 GDPR ⚠️ — §26(1) BDSG parcialmente inaplicável após TJUE C-34/21, 30/03/2023).
7. **Betriebsrat**: se existir, envolver antes de sistemas de TI/monitoramento, horários e dispensas.
8. **Dispensa**: forma escrita com assinatura manuscrita; aviso prévio §622 BGB; KSchG após 6 meses em empresas > 10 empregados; ouvir Betriebsrat.
9. **Remuneração variável/stock options** da controladora brasileira: tributação como salário na Alemanha (no exercício/vesting conforme o caso; §19a EStG para start-ups ⚠️) e reporte pelo empregador.
10. **Benefícios**: previdência complementar (*bAV*) — direito do empregado à conversão salarial (§1a BetrAVG) com subsídio de 15% do empregador.

---

## 11. Tabela-resumo de alíquotas e prazos

### 11.1 Alíquotas (2026)

| Tributo / encargo | Alíquota | Base legal | Observação |
|---|---|---|---|
| Körperschaftsteuer | **15%** (14% 2028 → 10% 2032) | §23 KStG | Investitionssofortprogramm |
| Solidaritätszuschlag | 5,5% do KSt/ESt (PF: só acima da Freigrenze) | SolZG | 15,825% KSt+Soli |
| Gewerbesteuer | 3,5% × Hebesatz (≥ 200%) | §§11, 16 GewStG | ~7% a ~17%+ |
| **Carga corporativa total** | **~30%** (22,8%–33%) | — | |
| Dividendos entre corporações | 95% isentos (participação ≥ 10%) | §8b KStG | Efetivo ~1,5% |
| Abgeltungsteuer (PF) | 25% + Soli = 26,375% | §32d EStG | + Kirchensteuer |
| KapESt sobre dividendos (fonte) | 26,375% | §§43, 43a EStG | |
| Dividendos a corporação brasileira (líquido após restituição) | **15,825%** | §44a(9) EStG | Sem ADT |
| Royalties a não residentes | 15% + Soli = 15,825% | §50a EStG | |
| Juros a não residentes | Em regra 0% | §49 EStG | |
| ESt PF | 0% / 14%–42% / 45% | §32a EStG | Mínimo isento €12.348 |
| USt (IVA) | 19% / 7% / 0% | §12 UStG | |
| Grunderwerbsteuer | 3,5%–6,5% | GrEStG + leis estaduais | Share deal ≥ 90% |
| Pilar Dois | ETR mínima 15% | MinStG | Grupos ≥ €750 mi |
| CFC (baixa tributação) | < 15% | §8(5) AStG | |
| Previdência total (aprox.) | ~42% (≈ 21% + 21%) | SGB | Tetos €8.450 / €5.812,50 |
| Salário mínimo | €13,90/h (2026); €14,60/h (2027) | MiLoG + MiLoV5 | |
| **Brasil → Alemanha**: dividendos | IRRF 10% (desde 2026) | Lei 15.270/2025 | |
| Brasil → Alemanha: royalties / serviços técnicos | IRRF 15% + CIDE 10% + PIS/Cofins-Imp. 9,25% (+ ISS) | Leis 9.779/99, 10.168/00, 10.865/04 | Sem ADT |
| Brasil → Alemanha: demais serviços | IRRF 25% ⚠️ | RIR/2018 | |
| Brasil → Alemanha: juros / JCP | IRRF 15% ⚠️ (JCP) | Lei 9.249/95 | |

### 11.2 Prazos e limites-chave

| Obrigação | Prazo / limite | Base |
|---|---|---|
| Integralização mínima GmbH | €12.500 antes do registro | §7(2) GmbHG |
| Registro fiscal | 1 mês após início | §138 AO |
| Pedido de insolvência | 3 semanas (iliquidez) / 6 semanas (superendividamento) | §15a InsO |
| UStVA | 10º dia do mês seguinte (mensal > €9.000 ⚠️; trimestral > €2.000) | §18 UStG |
| ZM (declaração recapitulativa) | 25º dia | §18a UStG |
| Lohnsteuer-Anmeldung | 10º dia | §41a EStG |
| Contribuições sociais | Antepenúltimo dia útil do mês | §23 SGB IV |
| §50a (royalties) | 10º dia após o trimestre | §50a(5) EStG |
| KapESt (dividendos) | 10º dia do mês seguinte ao pagamento | §44(1) EStG |
| Declarações anuais 2025 | 31/07/2026 (sem consultor) / 01/03/2027 (com Steuerberater) | §149 AO |
| Elaboração do balanço | 3 meses (média/grande) / 6 meses (pequena) | §264 HGB |
| Publicação (Unternehmensregister) | 12 meses | §325 HGB |
| Documentação TP após pedido | 30 dias (desde 2025) | §90(4) AO |
| DAC6 | 30 dias | §138f AO |
| Guarda de comprovantes | 8 anos (bancos/seguradoras: 10) | §147 AO; §257 HGB |
| Guarda de livros/balanços | 10 anos | idem |
| Ação contra dispensa | 3 semanas | §4 KSchG |
| Indenização do representante | Reclamar em 1 ano; teto 1 remuneração anual média | §89b HGB |
| Reclamação de vícios B2B | Imediatamente | §377 HGB |
| Prescrição civil geral | 3 anos (fim do ano) | §195 BGB |
| E-fatura — recebimento | Desde 01/01/2025 | §14 UStG |
| E-fatura — emissão | 01/01/2027 (> €800.000) / 01/01/2028 (todos) | §27(38) UStG |
| Kleinunternehmer | ≤ €25.000 ano anterior e ≤ €100.000 ano corrente | §19 UStG |
| CSRD (Omnibus) | > 1.000 empregados e > €450 mi; transposição 19/03/2027 | Dir. 2026/470 |
| CSDDD (Omnibus) | > 5.000 empregados e > €1,5 bi; aplicação 26/07/2029 | Dir. 2026/470 |
| EUDR | 30/12/2026 (grandes/médias) / 30/06/2027 (micro/pequenas) | Reg. 2025/2650 |
| CBAM | Fase definitiva 01/01/2026; certificados à venda 01/02/2027; 1ª declaração 30/09/2027; limite 50 t/ano | Reg. 2023/956; 2025/2083 |
| AI Act alto risco | 02/12/2027 (Anexo III) / 02/08/2028 (Anexo I) | Reg. 2024/1689; 2026/1744 ⚠️ |
| Mercosul–UE (iTA) | Aplicação provisória desde 01/05/2026 | Decisão do Conselho 09/01/2026 |
| Adequação GDPR Brasil | Vigente desde 01/2026 | Dec. Exec. (UE) 2026/179 |

---

## 12. Glossário alemão–português

| Termo alemão | Tradução / sentido |
|---|---|
| *Abfindung* | Indenização rescisória (negociada) |
| *Abgeltungsteuer* | Imposto definitivo sobre rendimentos de capital (PF) |
| *Amtsgericht* | Tribunal de primeira instância local (inclui registro comercial e insolvência) |
| *Anrechnung* | Crédito (compensação) de imposto estrangeiro |
| *Aufsichtsrat* | Conselho de supervisão |
| *Betriebsprüfung* | Auditoria/fiscalização tributária |
| *Betriebsrat* | Conselho/comissão de empregados |
| *Betriebsstätte* | Estabelecimento permanente |
| *Bilanzsumme* | Ativo total |
| *Buchführungspflicht* | Obrigação de escrituração |
| *DBA (Doppelbesteuerungsabkommen)* | Acordo para evitar dupla tributação |
| *Ergebnisabführungsvertrag (EAV)* | Contrato de transferência de resultados (Organschaft) |
| *Finanzamt* | Repartição fiscal local |
| *Geschäftsführer* | Administrador/gerente da GmbH |
| *Gewerbeanmeldung* | Registro de atividade empresarial na prefeitura |
| *Gewerbesteuer* | Imposto municipal sobre atividade empresarial |
| *GoB / GoBD* | Princípios de escrituração regular / regras de escrituração digital |
| *Handelsregister* | Registro de comércio (Junta Comercial) |
| *Handelsvertreter* | Representante comercial |
| *Hebesatz* | Multiplicador municipal da Gewerbesteuer |
| *Hinzurechnungsbesteuerung* | Tributação CFC |
| *Jahresabschluss* | Demonstrações financeiras anuais |
| *Kapitalertragsteuer* | Imposto retido na fonte sobre rendimentos de capital |
| *Kleinunternehmer* | Pequeno empresário (isenção de IVA) |
| *Körperschaftsteuer* | Imposto de renda das pessoas jurídicas |
| *Kündigung* | Dispensa / denúncia de contrato |
| *Lagebericht* | Relatório da administração |
| *Lohnsteuer* | Imposto retido sobre salários |
| *Mitbestimmung* | Codeterminação |
| *Offenlegung* | Publicação das demonstrações |
| *Organschaft* | Consolidação fiscal |
| *Stammkapital* | Capital social (GmbH) |
| *Steuerberater* | Consultor tributário habilitado |
| *Überschuldung* | Superendividamento (passivo a descoberto) |
| *Umsatzsteuer (USt)* | IVA |
| *Umsatzsteuer-Voranmeldung* | Declaração periódica de IVA |
| *Verlustvortrag* | Compensação de prejuízos fiscais |
| *Verrechnungspreise* | Preços de transferência |
| *Zahlungsunfähigkeit* | Insolvência de caixa (iliquidez) |
| *Zinsschranke* | Limitação de dedutibilidade de juros |
| *Zweigniederlassung* | Filial registrada |

---

## 13. Mapa de incertezas (⚠️)

Itens a verificar antes de parecer formal:

1. **ADT Brasil–Alemanha**: GTAI afirma retomada oficial das negociações em 2026; não há texto assinado. Monitorar lista anual do BMF ("Stand der DBA") e a Receita Federal.
2. **Lei 15.270/2025**: regulamentação do crédito ao não residente sobre IRRF de 10% em dividendos; eventual alteração de JCP; aplicação para lucros de 2025 deliberados em 2025.
3. **Mercosul–UE**: parecer do TJUE pendente; valores exatos de cotas/cronogramas (verificar textos no JO); número do regulamento de salvaguarda; validade do decreto de promulgação brasileiro.
4. **LkSG**: reforma (fim do relatório; escopo 5.000 empregados) não confirmada como promulgada até 11/2026.
5. **E-fatura**: pedidos de adiamento da etapa de 2027; novo BMF-Schreiben.
6. **CSRD na Alemanha**: lei de transposição (*CSRD-Umsetzungsgesetz*) e transposição do Omnibus até 19/03/2027.
7. **AI Act Digital Omnibus**: número do regulamento (2026/1744) e datas — confirmar no JO.
8. **Aufbewahrung**: regra de transição para setor financeiro (10 anos).
9. **Mindestbesteuerung 70%** (2024–2027) e eventual prorrogação; §4j EStG (limite 15%).
10. **Reformas trabalhistas**: ArbZG (limite semanal, registro eletrônico), Entgelttransparenz (prazo 07/06/2026), Tariftreuegesetz federal.
11. **Restituição de IVA a não-UE**: status de reciprocidade do Brasil na lista do BMF.
12. **CBAM**: preços trimestrais 2026 e expansão a produtos a jusante.

**Fontes gerais:**
- https://www.bundesfinanzministerium.de
- https://www.gesetze-im-internet.de
- https://www.bzst.de
- https://www.gtai.de
- https://www.handelsregister.de
- https://www.ahkbrasil.com
- https://eur-lex.europa.eu
- https://taxsummaries.pwc.com/germany
- https://www.recht.bund.de (Bundesgesetzblatt eletrônico)
