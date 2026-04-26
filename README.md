# SIAC --- Scientific Iterative Adversarial Convergence

Metodologia original para produção científica com integridade estrutural em tempos de IA generativa.

A SIAC opera com dois papéis (Operador humano e Executor) em cinco fases conectadas por gates obrigatórios. Em vez de prescrever princípios éticos, estrutura um processo no qual rastreabilidade, adversarialidade, declaração de lacunas e falseabilidade observável emergem como propriedades do fluxo de trabalho.

```mermaid
flowchart TD
    F0["F0\nDescoberta\n(10 perguntas)"]
    G1{Gate\nEntendimento}
    F1["F1\nPlanejamento\n(venue, escopo, entregável)"]
    G2{Gate\nPlano}
    F2["F2\nCrítica Adversarial\n(dimensões por categoria)"]
    F3["F3\nRevisão\n(disposição de achados)"]
    G3{Gate\nExecução}
    F4["F4\nExecução\n(+ SIAC-log)"]

    F0 --> G1 --> F1 --> G2 --> F2
    F2 --> F3
    F3 -->|bloqueantes\npendentes| F2
    F3 -->|convergiu| G3
    G3 --> F4
    F4 -.->|Retorno de emergência\n(qualquer fase, se premissa colapsa)| F0

    style F0 fill:#4a90d9,color:#fff
    style F1 fill:#4a90d9,color:#fff
    style F2 fill:#c0392b,color:#fff
    style F3 fill:#e67e22,color:#fff
    style F4 fill:#27ae60,color:#fff
    style G1 fill:#f0f0f0,color:#333
    style G2 fill:#f0f0f0,color:#333
    style G3 fill:#f0f0f0,color:#333
```

**Papéis:** O **Operador** (pesquisador) detém agência sobre decisões. O **Executor** (colega, LLM ou o próprio pesquisador) conduz o processo e produz crítica. Os gates exigem aprovação explícita do Operador.

## Arquivos

- **[SIAC.md](SIAC.md)** --- Especificação operacional completa da metodologia. Pode ser usada diretamente como prompt de sistema para um LLM ou como guia para execução manual.
- **[artigo3_vibe_writing_integridade_ia.pdf](artigo3_vibe_writing_integridade_ia.pdf)** --- Artigo que fundamenta a SIAC: diagnóstico de *vibe writing*, crítica epistemológica a diretrizes normativas e descrição metodológica com meta-exemplo iterativo.
- **[SIAC-log.md](SIAC-log.md)** --- Registro paralelo da aplicação da SIAC ao próprio artigo: rodadas adversariais com achados, disposições, justificativas e atualizações pontuais da metodologia. Demonstra o método em uso e materializa a auditabilidade que a SIAC reivindica como mecanismo central.

## Como usar

**Com LLM como Executor:** forneça o conteúdo de `SIAC.md` como instrução de sistema. O LLM iniciará perguntando o modo de operação (escrita do zero ou revisão de rascunho).

**Sem LLM:** siga as fases descritas em `SIAC.md` como roteiro de autoavaliação. As 10 perguntas, dimensões de crítica e classificação de achados funcionam independentemente do executor.

## Autora

Jasmine Moreira --- Doutora em Educação (UFPR); Doutoranda em Engenharia de Software (CPGEI/UTFPR); Especialista em Sistemas Cognitivos (INDT, Manaus).

## Licença

Este trabalho está disponível sob licença [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
