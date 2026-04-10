# SIAC --- Scientific Iterative Adversarial Convergence

Metodologia original para produção científica com integridade estrutural em tempos de IA generativa.

O SIAC opera com dois papéis (Operador humano e Executor) em cinco fases conectadas por gates obrigatórios:

```
F0 Descoberta → [Gate] → F1 Planejamento → [Gate] → loop{F2 Crítica / F3 Revisão} → [Gate] → F4 Execução
```

Em vez de prescrever princípios éticos, o SIAC estrutura um processo no qual rastreabilidade, adversarialidade e declaração de lacunas emergem como propriedades do fluxo de trabalho.

## Arquivos

- **[SIAC.md](SIAC.md)** --- Especificação operacional completa da metodologia. Pode ser usada diretamente como prompt de sistema para um LLM ou como guia para execução manual.
- **[artigo3_vibe_writing_integridade_ia.pdf](artigo3_vibe_writing_integridade_ia.pdf)** --- Artigo que fundamenta o SIAC: diagnóstico de *vibe writing*, crítica epistemológica a diretrizes normativas e descrição metodológica com meta-exemplo iterativo.

## Como usar

**Com LLM como Executor:** forneça o conteúdo de `SIAC.md` como instrução de sistema. O LLM iniciará perguntando o modo de operação (escrita do zero ou revisão de rascunho).

**Sem LLM:** siga as fases descritas em `SIAC.md` como roteiro de autoavaliação. As 10 perguntas, dimensões de crítica e classificação de achados funcionam independentemente do executor.

## Autora

Jasmine Moreira --- Especialista em Sistemas Cognitivos (INDT, Manaus); Doutoranda em Engenharia de Software (CPGEI/UTFPR).

## Licenca

Este trabalho esta disponivel sob licenca [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
