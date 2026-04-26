# SIAC-log — Artigo 3: Vibe Writing e Integridade Acadêmica em Tempos de IA

**Data da sessão:** 2026-04-21
**Artigo-alvo:** `artigo3_vibe_writing_integridade_ia.tex`
**Operadora:** Jasmine Moreira
**Executor:** LLM (Claude Opus 4.7, 1M context)

---

## 1. Metadados da sessão

| Atributo | Valor |
|----------|-------|
| Modo ativo | B — Revisão de rascunho existente |
| Modo de engajamento | (i) — Revisão profunda com verificação externa confirmada |
| Categoria do artigo | Proposta de método |
| Venue declarado em F1 | Educação & Realidade (UFRGS, Qualis A1 — Educação) |
| Output type em F1 | (d) lista cirúrgica por prioridade, granularidade de parágrafo |
| Output type em F4 | **alterado para aplicação direta** (reabertura do Gate de Execução autorizada pela Operadora) |
| Referências validadas externamente | 13 (11 originais + 2 da rodada complementar de 2026-04-25) |
| Decisões não verificadas | 4 (registradas na Seção 6 deste log) |
| Rodada complementar | 2026-04-25 — incorporação de Miao \& Holmes (2023) e Chayka (2023); registrada na Seção 11 |
| Rodada R3 | 2026-04-25 — adversarial externa por análise de IA terceira; 5 achados (2 🔴 + 3 🟡); todos corrigidos; registrada na Seção 12 |
| Rodada R4 | 2026-04-25 — segunda análise externa de IA terceira; 2 achados (1 🟡 + 1 🟢) sobreviveram ao crivo adversarial; ambos corrigidos; registrada na Seção 13 |
| Rodada R5 | 2026-04-25 — terceira análise externa; 1 achado 🟡 sobreviveu (atualização do meta-exemplo com R3+R4 e caveat sobre crivo F2); corrigido; registrada na Seção 14 |
| Rodada R6 | 2026-04-25 — validação integrada sobre texto pós-R5; 6 achados em dois grupos (2 🔴 + 3 🟡 + 1 🟢); todos corrigidos; registrada na Seção 15 |
| Atualização pontual pós-R6 | 2026-04-26 — adição da dimensão F2 *Coerência epistemológica entre fontes citadas* à metodologia, motivada por observação de falha recorrente em pesquisadores em formação; registrada na Seção 16 |
| Atualização pontual de cobertura | 2026-04-26 — quatro adições à F2 motivadas por revisão de literatura sobre erros recorrentes em iniciantes (web search); duas dimensões universais novas, uma adição condicional, uma cláusula em dimensão existente; registrada na Seção 17 |

---

## 2. Mapa das 10 perguntas (estado final)

| # | Pergunta | Estado | Observação |
|---|----------|--------|------------|
| 🔴 1 | Contribuição | Respondida | SIAC como abordagem operacional que instancia 4 mecanismos de integridade; nicho diferenciado de EQUATOR/RR/AC declarado |
| 🔴 2 | Metodologia | Respondida | Análise epistemológica + estrutural + comparativa; meta-exemplo com limitação de auto-SIAC declarada |
| 🔴 3 | Problema | Respondida | Paradoxo Schilke-Reimann; incentivo ao ocultamento |
| 🔴 4 | Conclusões | Respondida | SIAC altera qualidade do viés (não elimina); complemento a orientação + peer review |
| 🟡 5 | Estado da arte | Respondida + ampliada | Sampaio, Schilke, Gomes, V&M, DS, AR + EQUATOR/RR/AC (parcial) |
| 🟡 6 | Relevância | Respondida | Vibe writing como fenômeno emergente 2025-26; 20,5%/7,5%/6% Gomes&Mendes; 3,3M NSB 2022 |
| 🟡 7 | Limitações | Expandida | 8 subseções em 6.1 (incluindo simulabilidade, agência não mecanizada, auto-SIAC subótima) |
| 🟢 8 | Tema | Respondida | Integridade acadêmica em tempos de IA generativa |
| 🟢 9 | Direção futura | Respondida | Implementação empírica; estudo de interação com orientação/peer review |
| 🟢 10 | Categoria | Respondida | Proposta de método |

---

## 3. F2/F3 Rodada 1 — Achados e disposições

| # | Achado | Tipo | Pergunta | Disposição | Justificativa |
|---|--------|------|----------|-----------|---------------|
| 1 | Adequação editorial ao venue (Educação & Realidade) | 🔴 | 5-7 | Postergado | **Justificativa pendente** — decisão não verificada |
| 2 | Omissão declaração de uso de IA no próprio artigo | 🔴 | 2-7 | Corrigir | Paradoxo performativo: texto prescreve transparência e não declara uso; corrigido via nova seção |
| 3 | Integridade de referências — 15 sub-achados | 🔴🟡 | 5 | Corrigir | Erros bibliográficos e atribuições; verificados em PDFs locais |
| 4 | Saltos lógicos (3 passagens) | 🔴 | 4 | Corrigir | Autocontradição 4.4; volume≠invisibilidade 2.5; OSC atribuição 4.2 |
| 5 | Epistemologia nomeada mas não sustentada | 🟡 | 1 | Corrigir | Removidos label `realismo_critico` e linguagem realista; filiação filosófica não introduzida |
| 6 | Voz autoral LLM | 🟡 | transversal | Corrigir (parcial) | Negrito retórico, "materializa", anglicismos reduzidos; passe estilístico adicional pendente |
| 7 | Comparação com métodos incompleta | 🔴 | 1 | Corrigir + sub-gate | Expansão 2.4 com EQUATOR/RR/AC/red teaming; **busca externa pendente** |
| 8 | Limitações confortáveis (3 omissões) | 🟡 | 7 | Corrigir | 6.1.6/7/8 adicionadas (simulabilidade, agência, ritualização) |
| 9 | Viés de confirmação em Schilke | 🟡 | 1-3 | Corrigir | Calibrado: "13 experimentos"; atenuação declarada; algorithm appreciation (Logg) referenciada |
| 10 | Tensão individual/institucional | 🔴 | 1 | Corrigir | Fórmula de complementaridade: SIAC individual em complemento a orientação + peer review + diretrizes |
| 11 | Calibração retórica | 🟡 | transversal | Corrigir | "consolida-se"→"emerge"; "janela estreita" removida; metalinguagem §7.7 removida |
| 12 | Autonomia cognitiva não discutida | 🟡 | 7 | Corrigir | 5.2 expandida: pesquisadores em formação pressupõem orientação externa |

**Resultado R1:** 12 achados; 5 🔴; todos com disposição; 1 postergado (com risco registrado).

---

## 4. F2/F3 Rodada 2 — Refinamentos

| # | Achado | Tipo | Disposição | Justificativa |
|---|--------|------|-----------|---------------|
| R2-1 | Sub-gate de novidade verificável pendente (refinamento de R1-7) | 🔴 | Resolução (i) — busca externa | Operadora executará busca no Scopus/WoS para confirmar diferenciação de EQUATOR/RR/AC |
| R2-2 | Auto-SIAC subótima: declarar explicitamente | 🟡 | Corrigir | Reforço à tese: SIAC não substitui orientação externa; evidência nesta própria revisão (R1 externa encontrou achados não vistos pela autora) |
| R2-3 | R2 prospectiva sobre texto não corrigido — ambiguidade metodológica | 🔴 | Resolução (i) — R2 real após aplicação | Aplicar correções de R1 primeiro; R2 real será conduzida sobre o texto atualizado |

**Resultado R2:** 3 achados; 2 🔴; todos dispostos.

**Decisão de convergência:** R1 + R2 acumulam 15 achados, 0 bloqueantes irresolúveis após aplicação das correções. Reconhece-se que R6 (validação integrada — termo cunhado nesta tabela como "R2 real", renomeado em 2026-04-25 para evitar ambiguidade após R3, R4 e R5) ainda precisa ser conduzida sobre o texto corrigido — convergência declarada é condicional.

---

## 5. Gate de Execução e F4

- **Plano aprovado** após F3 R2.
- **Output type originalmente registrado:** (d) lista cirúrgica.
- **Output type final:** aplicação direta das correções ao arquivo `.tex`, autorizada pela Operadora (reabertura do Gate de Execução).
- **Materiais/referências extras autorizados para incorporação:** PDFs já na pasta (Lancet 2024; Colquhoun 2017); referências sugeridas (EQUATOR/RR/AC/Logg) marcadas com `% REF A VERIFICAR` no texto e como `% bibitem` comentado em `thebibliography`.

### Status de aplicação das correções por ID

| ID | Status | Observações |
|----|--------|-------------|
| 01 Saltos lógicos | ✓ Aplicado | Seção 4.4 (título e §1); 2.5; 4.2 Mec.1; Conclusão §7.3 |
| 02 Vizinhança metodológica | ✓ Aplicado (sub-gate pendente) | Expansão Seção 2.4 com EQUATOR/RR/AC/red teaming; busca externa da Operadora pendente |
| 03 Individual/institucional | ✓ Aplicado | 6.1.1; Conclusão §7.3, §7.4, §7.7 |
| 04 Declaração de IA | ✓ Aplicado | Nova seção antes de Referências |
| 05 Referências 🔴 | ✓ Aplicado | Gomes/Mendes iniciais; Schilke 104405; V&M 1923-1928; NSB ano 2022; Sampaio + São Paulo + ISBN |
| 06 Atribuições | ✓ Aplicado | Schilke restrição a pesquisa removida; V&M modelo quadrante; OSC inferência autoralizada; Rosenthal explicitada como analogia |
| 07 Epistemologia | ✓ Aplicado | Label `realismo_critico` → `mecanismos_vs_prescricao`; linguagem moderada |
| 08 Voz LLM | ~ Parcial | "materializa" (7 ocorrências) substituído; algumas construções "não X, mas Y" reduzidas; passe amplo pendente |
| 09 Limitações omitidas | ✓ Aplicado | 6.1.6, 6.1.7, 6.1.8 adicionadas |
| 10 Viés Schilke | ✓ Aplicado | Calibrado em 2.2 + Introdução §3; Logg et al. (2019) referenciada com `% REF A VERIFICAR` |
| 11 Calibração retórica | ✓ Aplicado | Abstract pt+en; Conclusão §7.3 e §7.7 |
| 12 Autonomia cognitiva | ✓ Aplicado | Seção 5.2 bullet "Viés circular" expandido |
| 13 Auto-SIAC subótima | ✓ Aplicado | Parágrafo final em 5.10; subseção 6.1.8 |
| 14 Venue | Postergado | Decisão pendente da Operadora |
| 15 PDFs extras | ✓ Aplicado | Bagenal/Lancet e Colquhoun adicionados à bibliografia e ao texto (Seção 4.2 Mec.1) |

---

## 6. Decisões não verificadas (risco residual)

| # | Decisão | Risco | Ação recomendada |
|---|---------|-------|------------------|
| NV-1 | Achado 1 (venue) postergado sem justificativa em 1-2 frases (SIAC exige para 🔴) | Decisão de venue pode afetar reestruturação significativa (abstract, introdução, posicionamento disciplinar) | Operadora deve fornecer justificativa ou reclassificar achado |
| NV-2 | Unifesp Resolução 17/2025 — apenas despacho (documento SEI 3134393) auditado | PDF do despacho confirma existência e divulgação da Resolução e do modelo de declaração, mas o escopo preciso ("em todos os documentos finais submetidos para avaliação ou publicação") não é verificável sem acesso ao documento SEI 3127023 | Obter documento primário para confirmar atribuição |
| NV-3 | Sampaio et al. — recomendações específicas ("documentar *prompts*, supervisionar resultados, avaliar criticamente") atribuídas sem verificação nos capítulos de Princípios Práticos | As práticas citadas são coerentes com a estrutura do sumário, mas não foram confrontadas com o corpo do texto | Consultar capítulos "Princípios Práticos" (pp. 27-43) do livro antes de submissão |
| NV-4 | Sub-gate de novidade verificável (R2-1) — busca externa de diferenciação entre SIAC e EQUATOR/RR/Adversarial Collaboration pendente | A expansão da Seção 2.4 declara nicho específico da SIAC, mas a confirmação externa depende de consulta bibliográfica sistemática | Operadora executará busca no Scopus/WoS e confirmará ou ajustará a delimitação |

### Referências com comentário `% REF A VERIFICAR` no texto (sem PDF na pasta)

- **Simera et al. (2010)** — EQUATOR Network
- **Chambers (2013)** — Registered Reports
- **Nosek et al. (2018)** — Preregistration revolution
- **Mellers, Hertwig & Kahneman (2001)** — Adversarial collaboration
- **Cowan et al. (2020)** — Extended adversarial collaboration
- **Logg, Minson & Moore (2019)** — Algorithm appreciation

Todas marcadas também como `% bibitem` comentado em `thebibliography` para descomentar após verificação.

---

## 7. Dimensões suspensas

Nenhuma dimensão de crítica foi suspensa em F2. Todas as dimensões universais e condicionais (proposta de método; venue definido; Executor LLM) foram aplicadas.

---

## 8. 🔴 Declaráveis aceitos pela Operadora

Nenhum 🔴 foi aceito como irresolúvel estrutural (declarável). Todos os 🔴 identificados foram dispostos como "corrigir" (exceto Achado 1, postergado).

A limitação do meta-exemplo (auto-SIAC subótima, identificada em R1 Achado 4 interno da autora e em R2-2 desta revisão externa) foi incorporada como limitação declarada na Seção 6.1.8 e no parágrafo final de 5.10 — configuração de "declarada + corrigida" em vez de "declarável aceito".

---

## 9. Pendências para próxima rodada (R6 — validação integrada)

Após a Operadora:
1. Revisar o texto corrigido
2. Executar a busca externa do sub-gate (NV-4)
3. Obter PDFs das referências marcadas `% REF A VERIFICAR`
4. Decidir venue (ID 14 + NV-1)
5. Confirmar atribuições pendentes (NV-2, NV-3)

O Executor deve conduzir **R6 — validação integrada** sobre o texto atualizado, com foco em:
- Refinamentos de voz autoral (ID 08 sanitização ampla)
- Verificação de que as correções aplicadas em R1 não introduziram novos problemas
- Reavaliação da adequação ao venue após decisão
- Achados de segundo nível que só aparecem após texto estabilizado

---

## 10. Nota metodológica

Esta revisão externa identificou 15 achados em um texto que a autora declarava ter passado por duas rodadas internas de SIAC (R1 interna com 12 achados; R2 interna com 6 achados) com convergência declarada. Os achados identificados aqui **não se sobrepõem** aos achados das rodadas internas — o que é registro empírico de que auto-SIAC é estruturalmente subótima mesmo para o criador da metodologia, reforçando a tese teórica do artigo sobre a necessidade de instâncias externas de verificação (orientação acadêmica, peer review).

Este próprio SIAC-log está sujeito às limitações declaradas em 6.1.6 (simulabilidade do SIAC-log) e 6.1.7 (agência do Operador não mecanizada). A integridade do registro depende da disciplina da Operadora em mantê-lo contemporâneo ao processo, e não retrospectivo.

---

## 11. Rodada complementar — Incorporação de evidência externa (2026-04-25)

**Disparador:** A Operadora submeteu para análise o documento UNESCO *Guidance for generative AI in education and research* (Miao & Holmes, 2023; tradução portuguesa de 2024 + original em inglês de 2023) como nova evidência potencialmente relevante para a metodologia SIAC e para o artigo. A submissão configura aplicação de F2 com material externo — não rodada nova sobre o texto, mas avaliação de incorporação por evidência adicional após convergência declarada em R2.

### 11.1 Achados e disposições

| # | Achado | Tipo | Disposição | Justificativa |
|---|--------|------|-----------|---------------|
| C-1 | UNESCO §6.6 cita Chayka (2023) com termo canônico "writing without thinking" para o fenômeno que o SIAC chama de "vibe writing com etapas intermediárias" | 🟡 | Corrigir | Termo canônico ancora a tese em referência institucional internacional e oferece fundamentação adicional na literatura |
| C-2 | UNESCO §6.4 documenta homogeneização argumentativa como mecanismo distinto do viés circular já tratado no SIAC | 🟡 | Corrigir | Limitação do Executor LLM não tratada nas LIMITAÇÕES atuais; manifesta-se em F4 (produção) e não em F2 (crítica) |
| C-3 | Proposta inicial sobre declaração de uso de IA com base em UNESCO §6.2 e §5.1 | 🟢 | Descartar | Análise direta do original em inglês mostrou que UNESCO trata apenas de detecção (watermarks) e direitos autorais; declaração por autores vem de venues (ICMJE, COPE) e diretrizes editoriais, não da UNESCO |

**Resultado da rodada complementar:** 3 achados; 2 corrigidos com referência direta; 1 descartado após análise refinada do original em inglês.

### 11.2 Verificação externa realizada

- Existência da UNESCO Guidance confirmada via página oficial UNESCO (consultada em 2026-04-25); ID 386693 (original em inglês, 2023, ISBN 978-92-3-100612-8, DOI 10.54675/EWZM9535) e ID 390241 (tradução portuguesa, 2024, ISBN 978-92-3-700028-1). PDFs em `referencias/`.
- Confirmação de que não há segunda edição nem versão revisada da Guidance. Documento adjacente *AI and the Future of Education: Disruptions, Dilemmas and Directions* (UNESCO, 2025, ID 395236) é antologia complementar focada em educação, não em pesquisa científica — não substitui Miao & Holmes (2023).
- Comparação verbatim entre original em inglês e tradução portuguesa confirma fidelidade da tradução nos trechos-chave (§6.4, §6.6, §6.2). Nenhuma divergência semântica relevante.
- Referência Chayka (2023) verificada via The New Yorker e RealClearBooks: data correta de publicação **12 de julho de 2023** (corrigida no `.tex` após primeira inserção como "1 de agosto" — aplicação da própria limitação "Referências" do SIAC ao processo de redação).

### 11.3 Alterações no SIAC.md

| Local | Alteração |
|-------|-----------|
| LIMITAÇÕES DO EXECUTOR LLM (entre "Voz autoral" e "Lógica") | Novo item "Homogeneização argumentativa" com instrução operacional (Operador declara posição heterodoxa antes de F4; em F3 confronta texto com plano) |
| Linha de fechamento das LIMITAÇÕES | Reformulada com ancoragem em "escrever sem pensar" e explicitação da inversão cognitiva que o SIAC opera |

### 11.4 Alterações no artigo

| Local | Alteração |
|-------|-----------|
| §2.1 "O Consenso Normativo" | Novo parágrafo apresentando UNESCO como instância internacional do mesmo paradigma normativo de Sampaio et al. — mesma marca compartilhada (princípios sem mecanismo) |
| §5.2 "Limitações Arquiteturais do Executor LLM" | Novo item "Homogeneização argumentativa" com citação direta a Miao & Holmes (2023) |
| Fechamento das Limitações Arquiteturais | Reformulado com referência a Miao & Holmes (2023, p. 38) e Chayka (2023); explicita que SIAC inverte a ordem cognitiva induzida pela IAGen |
| Bibliografia | Duas entradas novas em ordem alfabética por bibkey: `chayka2023` (entre `bagenal2024` e `colquhoun2017`) e `miao2023` (entre `limongi2024` e `nosek2012`) |

### 11.5 Status pós-rodada

Alterações aplicadas em ambos os artefatos. Nenhuma decisão pendente desta rodada — todos os achados dispostos e correções confirmadas. As pendências da Seção 6 (NV-1 a NV-4) permanecem inalteradas. A Seção 9 (R6 — validação integrada sobre texto corrigido) permanece pendente e agora abrange também o texto pós-incorporação UNESCO.

### 11.6 Nota metodológica

Esta rodada complementar é caso de aplicação do retorno suave ao loop F2-F3 quando nova evidência externa surge após convergência declarada — distinto do "Retorno de emergência à F0" definido no SIAC, pois nenhuma premissa central colapsou e o escopo permaneceu inalterado. A evidência UNESCO reforçou e fundamentou posições já defendidas no artigo, em vez de refutá-las. A homogeneização argumentativa (achado C-2) é a única adição genuinamente nova à metodologia; "escrever sem pensar" (achado C-1) é reformulação ancorada em literatura de uma posição já operacionalmente presente no SIAC desde a versão original.

---

## 12. Rodada R3 — Adversarial externa por análise de IA terceira (2026-04-25)

**Disparador:** A Operadora submeteu análise crítica do artigo produzida por outra IA (ChatGPT, sob persona "Pátia") para avaliação adversarial. Aplicação direta de F2 com material externo, com adicional metodologicamente relevante: a análise externa foi submetida ao mesmo crivo F2 do SIAC.

### 12.1 Avaliação da análise externa

A análise foi classificada como redundante adversarialmente. Os pontos apresentados como "achados" eram reformulações de limitações já declaradas no artigo (ausência de validação empírica em §6.1 e §7.7; circularidade do meta-exemplo em §5.10 e §6.1.8; dependência do operador em §5.2 e §6.1.7; risco de "rebranding" de Design Science em §2.4). A análise também aplicou critério inadequado à categoria do artigo (penalizou ausência de experimento em uma proposta de método). Os 5 achados gerados a seguir não vêm da análise — vêm da rodada F2 desencadeada por sua submissão.

### 12.2 Achados e disposições

| # | Achado | Tipo | Disposição | Justificativa registrada |
|---|--------|------|-----------|--------------------------|
| R3-1 | Falseabilidade do método não declarada (risco de irrefutabilidade) | 🔴 | Corrigir | "Produzir critério verificável dentro do método em vez de remeter a instâncias externas" |
| R3-2 | Diferenciação operacional vs. diretrizes normativas não articulada proceduralmente | 🔴 | Corrigir | "Trabalho metódico sem pressão de tempo + tarefa inevitável para defesa do método" |
| R3-3 | Estabilidade do Executor LLM não tratada (versionamento, reprodutibilidade) | 🟡 | Corrigir | "melhor corrigir" — disposição decidida em conjunto com R3-4 e R3-5 |
| R3-4 | Custo de adoção / paradoxo de aprendizagem (perfil que mais se beneficia opera com mais dificuldade) | 🟡 | Corrigir | "melhor corrigir" — disposição decidida em conjunto com R3-3 e R3-5 |
| R3-5 | Posicionamento explícito da SIAC no quadrante de Vasconcelos & Marušić | 🟡 | Corrigir | "melhor corrigir" — disposição decidida em conjunto com R3-3 e R3-4 |

**Resultado:** 5 achados; 2 🔴 corrigidos com justificativa registrada; 3 🟡 corrigidos. Rodada encerrada.

### 12.3 Alterações aplicadas

| Achado | Local | Alteração |
|--------|-------|-----------|
| R3-1 | SIAC.md, nova seção `## CRITÉRIOS DE FALHA` (entre COMPORTAMENTO e FLUXO) | Quatro condições observáveis: falha de disposição, de coerência, de cobertura adversarial e de inversão cognitiva; argumento de que metodologia que não pode falhar não tem capacidade explicativa |
| R3-1 | Artigo, nova subseção §5.14 "Critérios de Falha" | Versão expandida com fundamentação epistemológica: distinção falseabilidade de método vs. teoria; posição compartilhada com Design Science (Hevner et al., 2004) e Action Research (Kemmis \& McTaggart, 2005) |
| R3-2 | Artigo, nova subsubseção em §4.3 "Comparação procedural com diretrizes normativas" | Tabela com 7 linhas mapeando princípio → mecanismo SIAC → observável; cobre Sampaio et al. (2024), Unifesp 17/2025 e Miao & Holmes (2023); parágrafo de fechamento articula que a diferença não está no que se prescreve mas em como a transgressão se torna identificável |
| R3-3 | SIAC.md, novo item em LIMITAÇÕES DO EXECUTOR LLM após "Viés circular" | "Estabilidade e versionamento": registrar modelo, versão e data no SIAC-log; reprodutibilidade SIAC é do processo e do log, não da saída literal do Executor |
| R3-3 | Artigo, novo item em §5.2 (Limitações Arquiteturais do Executor LLM) | Mesmo conteúdo do SIAC.md em formato itemize |
| R3-4 | Artigo, nova subsubseção §6.1.9 "Paradoxo de Aprendizagem" | Nomeia a tensão entre público-alvo e capacidade de adoção; articula orientação acadêmica como mitigação escalonada (orientador opera com orientando até autonomia); declara que "vibe writing com SIAC-log decorativo" é o risco quando orientação é ausente |
| R3-5 | Artigo, novo parágrafo ao final de §2.3 (A Questão da Agência: Vasconcelos e Marušić) | Posiciona explicitamente a SIAC entre Steneck e Russell no quadrante de V&M: agência distribuída individual articulada com agência coletiva externa pressuposta; SIAC instancia proceduralmente o que V&M argumentam ser pressuposto tácito |

### 12.4 Status pós-aplicação

Todas as cinco correções aplicadas em SIAC.md e no artigo. Rodada R3 encerrada com 0 achados pendentes. As pendências da Seção 6 (NV-1 a NV-4) permanecem inalteradas. A Seção 9 (R6 — validação integrada sobre texto corrigido) agora abrange o texto pós-R3 — convergência declarada continua condicional à aplicação de R6 sobre o texto integrado.

### 12.5 Nota metodológica

R3 é caso instrutivo de aplicação do SIAC à própria entrada externa. A análise terceira foi submetida ao mesmo crivo crítico que o artigo. O resultado — avaliação de redundância da análise em si — não invalidou-a como ferramenta de geração: rendeu 5 achados, todos corrigidos. Reforça a tese central do artigo: integridade não está na declaração de processo, mas no processo declarado e auditável. A análise externa, se aceita por autoridade ("é uma IA pensando"), seria validação vazia. Submetida a crivo SIAC, gerou achados úteis. O ato de criticar a análise antes de absorver suas posições é parte do método.

Os três 🟡 (R3-3 a R3-5) revelaram-se mais consequentes do que aparentavam à primeira inspeção. R3-3 acrescenta limitação arquitetural antes não declarada (versionamento). R3-4 nomeia tensão constitutiva (paradoxo de aprendizagem) que estava implícita em §6.1.5 e §6.1.7. R3-5 transforma uso retórico de V\&M em posicionamento teórico explícito. Rodada com saldo metodológico positivo: a entrada externa redundante gerou refinamentos que o ciclo interno R1+R2 não havia produzido — instância empírica adicional da tese de que auto-SIAC é subótima e que entrada externa, mesmo quando aparentemente trivial, pode ativar achados não detectados internamente.

---

## 13. Rodada R4 — Segunda adversarial externa por análise de IA terceira (2026-04-25)

**Disparador:** A Operadora submeteu segunda análise crítica do artigo produzida por ChatGPT após aplicação de R3. A análise reconheceu três das cinco correções de R3 (R3-2 procedural, R3-3 versionamento, R3-5 V&M) e o meta-exemplo, mas falhou em registrar duas correções já aplicadas (R3-1 §5.14 *Critérios de Falha* e R3-4 §6.1.9 *Paradoxo de Aprendizagem*), apresentando os pontos correspondentes como bloqueantes ainda em aberto. Padrão consistente com a primeira análise: leitura parcial das seções centrais do artigo.

### 13.1 Avaliação da análise externa

A análise propôs três blocos de texto "prontos para inserção". Crivo aplicado:

| Bloco proposto | Avaliação |
|----------------|-----------|
| §4.X *Condições de Falha e Falseabilidade* | Quatro de cinco condições propostas duplicam a §5.14 já existente (pseudo-rastreabilidade ≈ falha de disposição; estagnação adversarial ≈ falha de cobertura; divergência empírica ≈ falha de cobertura). Apenas "colapso de agência" é genuinamente aditivo |
| §6.X *Tensão operador iniciante* | Duplica §6.1.9 com framing mais abstrato; perde concretude (sem mecanismo de orientação escalonada, sem nome para o modo de falha) |
| §2.4.X *Irredutibilidade vs Design Science* | Maior parte duplica §2.4 existente; vocabulário "ortogonalidade" e exemplo concreto (modelo preditivo) podem somar clareza |

### 13.2 Achados efetivos da rodada

Após o crivo, dois achados sobreviveram:

| # | Achado | Tipo | Disposição | Justificativa registrada |
|---|--------|------|-----------|--------------------------|
| R4-1 | Falha de colapso de agência não declarada como condição observável (transformação da limitação §6.1.7 em critério de falha) | 🟡 | Corrigir | "Concordo com as proposições" — incorporação acrescenta condição genuinamente nova ao §5.14 e fecha o ciclo entre limitação declarada e observável |
| R4-2 | Distinção SIAC × Design Science pode ser articulada com mais força via exemplo concreto e linguagem de ortogonalidade | 🟢 | Corrigir | "Concordo com as proposições" — ganho de clareza sem expansão substantiva |

**Resultado:** 2 achados efetivos a partir de 3 blocos propostos pela análise externa; ambos corrigidos. Rodada encerrada.

### 13.3 Alterações aplicadas

| Achado | Local | Alteração |
|--------|-------|-----------|
| R4-1 | SIAC.md, quinta condição em CRITÉRIOS DE FALHA | "Falha de colapso de agência": disposições da Operadora replicam sugestões do Executor sem justificativa independente; identificável por inspeção comparativa F2 → F3 |
| R4-1 | Artigo, quinta condição em §5.14 | Mesmo conteúdo em itemize, com nota explícita de que a condição transforma a limitação declarada em §6.1.7 em critério observável de falha |
| R4-2 | Artigo, frase final de §2.4.3 *Implicações para o Problema da IA* | "As abordagens são ortogonais: um artefato pode satisfazer Design Science e ainda falhar SIAC; inversamente, processo SIAC-correto não garante artefato útil. Design Science responde 'o artefato funciona?'; a SIAC responde 'o processo que produziu este artefato é auditável?'." |

### 13.4 Status pós-aplicação

Todas as correções de R4 aplicadas. Rodada encerrada. As pendências da Seção 6 (NV-1 a NV-4) permanecem inalteradas. A Seção 9 (R6 — validação integrada) agora abrange texto pós-R4.

### 13.5 Nota metodológica

R4 reforça o padrão observado em R3: análise externa de IA terceira tende a redundância, mas o crivo adversarial extrai signal de noise. Da segunda análise, três blocos foram propostos; após inspeção, apenas dois fragmentos sobreviveram — um deles (colapso de agência) genuinamente aditivo, o outro (ortogonalidade Design Science) acréscimo de clareza retórica sobre argumento já presente. Saldo de R4 menor que de R3, consistente com convergência: rodadas externas posteriores tendem a render menos quando os achados de fundo já foram absorvidos.

A condição "colapso de agência" merece registro adicional: é caso em que crítica externa transformou uma limitação declarada (§6.1.7) em critério observável de falha (§5.14). Esse movimento — de "isto pode acontecer e não temos como impedir" para "isto pode acontecer e podemos identificar quando aconteceu" — é exatamente o tipo de refinamento que distingue prescrição de mecanismo. A análise externa, mesmo redundante em sua maior parte, contribuiu para tornar o método mais coerente com a tese que o sustenta.

---

## 14. Rodada R5 — Terceira adversarial externa por análise de IA terceira (2026-04-25)

**Disparador:** A Operadora submeteu terceira análise crítica do artigo, agora avaliando o próprio SIAC-log como artefato. A análise propôs adicionar mini-seção "Evidência processual" ao artigo, reivindicando que o registro paralelo constitui "evidência empírica de segunda ordem" e "validação comportamental da tese".

### 14.1 Avaliação da análise externa

Crivo aplicado em três frentes:

| Afirmação da análise | Avaliação |
|----------------------|-----------|
| SIAC-log seria "evidência empírica de segunda ordem" | Sobreafirmação. n=1, autoaplicação, sem controle. É demonstração de viabilidade (Design Science), não evidência empírica no sentido que a expressão sugere |
| SIAC-log "resolveria a crítica empírica" do artigo | Falso. Objeção empírica clássica pede experimento controlado, variação, baseline. SIAC-log não fornece nada disso. Continua sendo gap declarado em §7.7 |
| Mini-seção "Evidência processual" como adição ao artigo | Redundante com §5.10 (meta-exemplo), §5.11 (Por Que Este Meta-Exemplo Importa) e §6.1.8 (Auto-SIAC Subótima). Adicionar produziria triplicação |

A análise reconheceu corretamente um sinal: o SIAC-log registra padrão consistente com a tese §6.1.8 (rodadas externas geraram achados não produzidos pelas internas). Mas inflacionou o peso epistemológico do sinal e propôs solução textualmente excessiva.

### 14.2 Achado efetivo da rodada

Após o crivo, um único achado sobreviveu:

| # | Achado | Tipo | Disposição | Justificativa registrada |
|---|--------|------|-----------|--------------------------|
| R5-1 | Meta-exemplo (§5.10–§5.11) cobre apenas R1 e R2; rodadas R3 e R4 conduzidas posteriormente não estão refletidas no artigo, apenas no SIAC-log paralelo | 🟡 | Corrigir (versão ambiciosa) | "Ambicioso" — atualização do meta-exemplo + acréscimo de caveat sobre crivo F2 fortalece argumento contra leitura simplificadora "qualquer crítica serve" |

**Resultado:** 1 achado efetivo da análise externa após crivo. Rodada encerrada.

### 14.3 Alterações aplicadas

| Local | Alteração |
|-------|-----------|
| Artigo, nova subsubseção §5.10.5 *Rodadas Externas Pós-Redação* + nova `Tabela \ref{tab:siac_log_externas}` | Tabela com 5 atributos (Disparador, Achados gerados, Sobreposição com R1+R2, Adições à metodologia, Convergência) cobrindo R3 e R4 e Consolidado externo |
| Artigo, §5.11 *Por Que Este Meta-Exemplo Importa*, novo parágrafo | Observação empírica: zero sobreposição entre achados internos e externos; declaração explícita de que é demonstração de viabilidade, não evidência empírica de eficácia |
| Artigo, §5.11, segundo parágrafo novo | Caveat sobre crivo F2: o valor não está na crítica externa, está no filtro adversarial aplicado a ela; R4 como instância concreta (3 blocos propostos → 2 fragmentos após inspeção) |

### 14.4 Status pós-aplicação

R5 encerrada. Pendências da Seção 6 (NV-1 a NV-4) inalteradas. R6 (validação integrada) sobre texto pós-R5 permanece pendente.

### 14.5 Nota metodológica

R5 cumpre a função que R3 e R4 estabeleceram como padrão: análise externa redundante em sua proposição inicial, signal extraído pelo crivo F2. A particularidade desta rodada está no objeto da análise: pela primeira vez, o objeto da crítica externa não foi o conteúdo do artigo, foi o próprio SIAC-log. A análise encontrou algo real (rodadas externas geraram achados não detectados internamente) e propôs uma elaboração desproporcional ao peso epistemológico do achado (designá-lo "evidência empírica" e dedicar-lhe seção própria).

A correção aplicada preserva o sinal e descarta a inflação: a observação está agora incorporada ao próprio meta-exemplo, com caveats explícitos sobre seus limites (n=1, sem controle, sem generalização) e com adição substantiva — o caveat sobre crivo F2 articula explicitamente que a metodologia não recomenda multiplicar críticos externos, mas submeter cada entrada ao mesmo filtro dimensional. Esta é distinção operacionalmente relevante: protege a SIAC contra leitura simplificadora "abrir para muitos revisores" que descaracterizaria o método.

R5 também ilustra um padrão menor: ao longo de cinco rodadas adversariais, o saldo de achados decresce (R1: 12; R2: 6; R3: 5; R4: 2; R5: 1). Isso é convergência decrescente esperada e corrobora, em outro nível, a arquitetura iterativa do SIAC: cada rodada eleva o critério, e quando os achados de fundo são absorvidos, rodadas posteriores rendem cada vez menos. O custo crescente de leitura externa (cada nova rodada exige decisão sobre se vale o tempo de execução) é também observável — a análise de R5 dedicou três blocos textuais ao que rendeu apenas um achado efetivo.

---

## 15. Rodada R6 — Validação integrada pós-R5 (2026-04-25, em curso)

**Disparador:** Execução do IOU metodológico registrado em §4 (achado R2-3 da sessão original) e mantido em aberto na §9. Validação integrada sobre o texto pós-R5: verificar se as correções acumuladas introduziram problemas novos, identificar achados visíveis apenas com texto estabilizado, conferir se resoluções anteriores se sustentam.

**Renomeação:** o IOU foi originalmente cunhado como "R2 real" em 2026-04-21 (linha 73, achado R2-3). Renomeado para R6 em 2026-04-25 para evitar ambiguidade após R3, R4 e R5 — registro auditável da decisão preservado em §4 deste log.

### 15.1 Achados grupo 1 e disposições

| # | Achado | Tipo | Pergunta | Disposição | Justificativa registrada |
|---|--------|------|----------|-----------|--------------------------|
| R6-1 | Referências cruzadas hardcoded quebradas após renumerações de R3 e R5: §5.10 (linha 941) deve ser §5.11 (Meta-Exemplo); §5.5 (linha 1008) deve ser §6.4 (Complementaridade) | 🔴 | 7 + integridade documental | Corrigir (opção a, com `\ref{label}`) | "O problema veio precisamente de números hardcoded que quebraram após renumerações; a solução robusta previne recorrência" |
| R6-2 | Abstract (PT e EN) menciona "duas rodadas iterativas" e omite contribuições de R3-R5 (Critérios de Falha, Comparação procedural, Falha de colapso de agência, Paradoxo de Aprendizagem) | 🟡 | 1 + coerência título-abstract-conclusão | Corrigir (opção a, reescrita completa) | (escolhida pela Operadora; justificativa não exigida para 🟡 mas implícita: abstract é porta de entrada do artigo) |
| R6-3 | §6.5 lista "Comparação controlada" entre o que o artigo não oferece, mas Tabela `tab:procedural` em §4.3 já oferece comparação procedural | 🟡 | 7 | Corrigir | (escolhida pela Operadora) |

**Resultado parcial grupo 1:** 3 achados, 1 🔴 + 2 🟡, todos corrigidos.

### 15.2 Alterações aplicadas — grupo 1

| Achado | Local | Alteração |
|--------|-------|-----------|
| R6-1 | Artigo, §5.11 (linha 637) | Adicionado `\label{subsec:meta_exemplo}` |
| R6-1 | Artigo, §6.4 (linha 1033) | Adicionado `\label{subsec:complementaridade}` |
| R6-1 | Artigo, §5.13 (linha 941) | "(Seção 5.10)" → "(Seção \ref{subsec:meta_exemplo})" |
| R6-1 | Artigo, §6.1.9 (linha 1008) | "(Seção 5.5)" → "(Seção \ref{subsec:complementaridade})" |
| R6-2 | Artigo, abstract PT (linha 63) | Reescrita completa: cinco rodadas, critérios de falha, comparação procedural, paradoxo de aprendizagem, UNESCO, Schilke & Reimann citados |
| R6-2 | Artigo, abstract EN (linha 72) | Reescrita completa em paralelo ao PT |
| R6-3 | Artigo, §6.5 (linha 1056) | "Comparação controlada" → "Validação empírica controlada" |

### 15.3 Achados grupo 2 e disposições

| # | Achado | Tipo | Pergunta | Disposição | Justificativa registrada |
|---|--------|------|----------|-----------|--------------------------|
| R6-4 | Inconsistência entre abstract reescrito em R6-2 ("cinco rodadas, três externas") e tab:siac_log_externas (apenas R3 e R4 listadas, ou seja, duas externas). Erro introduzido pela própria correção R6-2 | 🔴 | 1 + integridade documental | Corrigir (opção a, alinhar abstract com tabela: 4 rodadas) | "Alinhar abstract com tabela preserva separação conceitual: R5 foi meta-rodada sobre o log, não rodada regular sobre o conteúdo" |
| R6-5 | Termo interno "R2 real" exposto na tab:siac_log_externas (linha 909) — vestígio da renomeação para R6 não propagado para o artigo | 🟡 | 7 + integridade documental | Corrigir | "R2 real" é nomenclatura interna do log sem significado para o leitor do artigo |
| R6-6 | Possível percepção de duplicação argumentativa entre §6.1.8 (Auto-SIAC subótima) e §6.1.9 (Paradoxo de Aprendizagem) | 🟢 | coerência argumentativa | Corrigir | Adicionar frase de transição que torna explícita a distinção (afinidade cognitiva vs. capacidade cognitiva geral) |

**Resultado grupo 2:** 3 achados, 1 🔴 + 1 🟡 + 1 🟢, todos corrigidos.

### 15.4 Alterações aplicadas — grupo 2

| Achado | Local | Alteração |
|--------|-------|-----------|
| R6-4 | Artigo, abstract PT (linha 63) | "cinco rodadas iterativas (duas internas e três externas)" → "quatro rodadas iterativas (duas internas e duas externas)" |
| R6-4 | Artigo, abstract EN (linha 72) | "five iterative rounds (two internal, three external)" → "four iterative rounds (two internal, two external)" |
| R6-5 | Artigo, tab:siac_log_externas linha "Convergência" | "R2 real sobre texto pós-R4 permanece pendente" → "validação integrada sobre texto consolidado permanece pendente" |
| R6-6 | Artigo, §6.1.9 (parágrafo de abertura) | Adicionado parágrafo de transição: "A subseção anterior tratou da auto-SIAC como problema de afinidade cognitiva entre autor e trabalho. O paradoxo aqui é distinto: refere-se à capacidade cognitiva geral exigida pela metodologia. Os dois problemas convergem na mesma mitigação --- orientação externa ativa --- mas operam em planos diferentes." |

### 15.5 Status pós-aplicação

R6 encerrada. Grupos 1 e 2 fechados, 6 achados todos com disposição registrada e correção aplicada. Pendências da Seção 6 (NV-1 a NV-4) permanecem inalteradas.

**O IOU metodológico originalmente registrado em §4 (achado R2-3) está fechado.** A "validação integrada sobre o texto consolidado" — herdada como "R2 real" e renomeada R6 — foi conduzida; o texto pós-R5 foi auditado em duas passagens; achados foram identificados e corrigidos; nenhum bloqueante irresolúvel restou.

### 15.6 Nota metodológica

R6 cumpriu a função para a qual foi desenhada e produziu uma observação metodologicamente relevante: o achado R6-4 detectou erro introduzido pela própria correção de R6-2 (grupo 1) — instância empírica de "Falha de cobertura adversarial" como definida em §5.14 do artigo. F2 do grupo 1 não capturou que o abstract reescrito superestimava o número de rodadas externas; foi necessário o grupo 2 para identificar.

Esse padrão é instrutivo: rodadas adversariais não convergem em uma única passagem mesmo após cinco iterações anteriores. O grupo 1 aplicou correções e o grupo 2 verificou se as correções introduziram novos problemas — exatamente o que a §5.14 declara como necessário. R6 funcionou como auditoria do próprio processo de correção, não apenas do texto original.

Saldo final de achados ao longo do percurso completo: R1 = 12, R2 = 6, R3 = 5, R4 = 2, R5 = 1, R6 = 6 (em duas passagens). A subida de R5 → R6 não contradiz a tese de convergência decrescente: R6 é validação sobre texto inteiro acumulado de seis rodadas anteriores e tinha mandato amplo, enquanto R5 era análise de objeto específico (o SIAC-log). A natureza dos achados de R6 é de coerência integrada — propriedade que só se torna observável depois que muitos materiais foram acumulados.

---

## 16. Atualização pontual pós-R6 — Dimensão de coerência epistemológica entre fontes (2026-04-26)

**Disparador:** Pergunta da Operadora sobre se a SIAC, na sua forma atual, é capaz de detectar articulação inadvertida de referências de tradições teóricas incompatíveis — caso identificado como recorrente em artigos de pesquisadores em formação.

**Diagnóstico:** As três dimensões F2 mais próximas (Consistência epistemológica, Cobertura de trabalhos anteriores, Lógica) tocam o problema parcialmente, mas nenhuma trata especificamente de **compatibilidade entre as fontes citadas**. A *Consistência epistemológica* trata da coerência interna do trabalho; a *Cobertura* verifica se o que o texto afirma sobre cada fonte corresponde ao que a fonte diz; a *Lógica* captura justaposição sem conexão causal. O caso descrito — fontes de tradições incompatíveis articuladas como mutuamente sustentadoras, com o autor não sabendo da incompatibilidade — escapa às três.

**Decisão:** Incorporar a dimensão como universal de F2. Justificativa principal: o artigo declara pesquisadores em formação como público-alvo central (§6.1.5, §6.1.9); não ter dimensão para a falha mais característica desse perfil enfraquece a reivindicação. Custo de incorporar é modesto (uma frase em três locais); custo de não incorporar é incoerência entre público declarado e cobertura efetiva.

**Alterações aplicadas:**

| Local | Alteração |
|-------|-----------|
| [SIAC.md](SIAC.md), F2 dimensões universais entre "Cobertura de trabalhos anteriores" e "Premissas silenciosas" | Nova dimensão *Coerência epistemológica entre fontes citadas* com formulação operacional (Executor LLM levanta suspeita pela limitação Conteúdo de fontes; Operador ou orientação confirma) |
| Artigo, §5.6 lista de dimensões universais | Espelhamento da dimensão com referência cruzada a §5.2 (Limitações Arquiteturais do Executor LLM) via novo `\label{subsec:limitacoes_executor_llm}` |
| Artigo, §6.1.9 (Paradoxo de Aprendizagem) | Parágrafo final que articula a nova dimensão como instância concreta do paradoxo: a SIAC fornece o sub-gate, mas o iniciante não dispõe sozinho dos recursos para resolvê-lo — a mitigação é estrutural (orientação), não cognitiva (refinamento metodológico) |
| Artigo, §5.6 | Novo `\label{subsec:f2}` para resolver referência cruzada de §6.1.9 |

**Status:** Atualização aplicada. Não constitui rodada nova (R7) — é refinamento pontual após o encerramento de R6, conforme a Operadora declarou em 2026-04-25 que adiante seriam alterações pontuais.

**Nota metodológica:** Esta atualização ilustra um padrão ortogonal aos seis rodadas anteriores. Os achados de R1 a R6 foram em sua maioria sobre como o artigo apresenta a SIAC — coerência interna, cobertura, posicionamento, integridade documental. Esta atualização é sobre **a metodologia em si**: identifica gap funcional na cobertura adversarial da SIAC e o preenche. É a primeira alteração pós-R6 que modifica a F2 substantivamente, em vez de refinar o texto que descreve a F2.

---

## 17. Atualização pontual de cobertura — Quatro adições à F2 (2026-04-26)

**Disparador:** Reflexão da Operadora sobre se haveria outros casos comuns em redação de iniciantes além da coerência epistemológica entre fontes (Seção 16). Acordou-se realizar busca na internet sobre erros mais comuns para verificar a cobertura da F2.

### 17.1 Diagnóstico

Busca conduzida em quatro frentes (português e inglês): erros comuns em redação científica, problemas em revisão de literatura, dificuldades de pesquisadores em formação, fraquezas características em escrita acadêmica. Mapeamento dos 22 erros mais recorrentes contra as dimensões existentes da F2 mostrou que a maioria está coberta. Quatro lacunas remanescentes:

| Lacuna | Cobertura atual | Decisão |
|--------|-----------------|---------|
| Posicionamento autoral perante referências (resumo sem análise crítica) | Parcial — *Cobertura de trabalhos anteriores* não exige posicionamento | Nova dimensão universal |
| Encadeamento textual / fluxo narrativo | Parcial — *Consistência lógica* trata premissa-conclusão, não transições textuais | Nova dimensão universal |
| Apresentação numérica (decimais, algarismos significativos) | Ausente | Item adicional em *Empírico* condicional |
| Consistência de estilo de citação | Parcial — *Integridade de referências* trata existência | Cláusula adicional em *Integridade de referências* |

### 17.2 Alterações aplicadas

| Local | Alteração |
|-------|-----------|
| [SIAC.md](SIAC.md), F2 universais entre *Cobertura* e *Coerência epistemológica entre fontes* | Nova dimensão *Posicionamento autoral perante as referências*: o texto analisa cada fonte ou apenas resume; cada citação confrontada com posição do trabalho |
| Artigo, §5.6 lista universal | Espelhamento da dimensão *Posicionamento autoral perante as referências* |
| [SIAC.md](SIAC.md), F2 universais entre *Consistência lógica* e *Declaração de limitações* | Nova dimensão *Encadeamento textual*: fio narrativo entre seções e parágrafos; transições articulam relação ou apenas justapõem |
| Artigo, §5.6 lista universal | Espelhamento da dimensão *Encadeamento textual* |
| [SIAC.md](SIAC.md), dimensão condicional *Empírico* | Item adicional *apresentação numérica* (precisão proporcional, formatação consistente) |
| Artigo, §5.6 dimensões condicionais Empírico | Espelhamento do item *apresentação numérica* |
| [SIAC.md](SIAC.md) e Artigo, dimensão *Integridade de referências* | Cláusula adicional sobre consistência de estilo de citação |

**Status:** Atualização aplicada. Não constitui rodada nova — refinamento pontual de cobertura.

### 17.3 Nota metodológica

Esta atualização tem natureza distinta da Seção 16. Lá, a adição (Coerência epistemológica entre fontes) veio de uma observação isolada da Operadora sobre falha recorrente. Aqui, a adição veio de varredura sistemática da literatura sobre erros característicos do público-alvo, com mapeamento explícito contra a cobertura existente.

O padrão é instrutivo: das 22 categorias de erro mapeadas, 18 já estavam cobertas. A SIAC, mesmo antes destas adições, tinha cobertura efetiva ampla — as quatro lacunas identificadas eram refinamentos, não buracos estruturais. Isso sustenta a observação de que a metodologia, ao longo das seis rodadas anteriores, foi se calibrando para o público-alvo declarado por iteração interna mais leitura externa, não por revisão sistemática única. A varredura agora conduzida funciona como auditoria de cobertura — confirma que o método cobre a maioria dos modos de falha conhecidos e identifica os refinamentos remanescentes.

Saldo de dimensões F2 universais: 16 → 18 (acréscimo de duas). Saldo de dimensões condicionais: inalterado (apenas item adicional em *Empírico* e cláusula em *Integridade de referências*). O incremento é modesto e mantém a SIAC operável.
