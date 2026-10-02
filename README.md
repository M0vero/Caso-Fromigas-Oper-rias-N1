# Caso-Fromigas-Oper-rias-N1 — Formigas Operárias x Formigueiro S.A.

## Objetivo
Este repositório demonstra um fluxo didático, rastreável e revisado por pessoa para responder a uma consulta trabalhista hipotética com apoio de fontes selecionadas manualmente (RAG manual). O caso é integralmente fictício. O material não é aconselhamento jurídico nem substitui análise profissional dos fatos e da legislação vigente.

## Público e limites
Material para fins de estudo sobre IA, organização de projeto, consulta com fontes e conferência humana. Antônia Operária, Formigueiro S.A., Formigópolis/SC, sindicato, pessoas, registros e eventos são elementos ficcionais criados para a atividade. Não há processo real, cliente, documento sigiloso ou dado pessoal real. Não use este repositório para orientar um caso concreto.

## Fluxo do projeto
1. Preserve o relato bruto em `entrada/relato_bruto.md` e prepare uma versão de trabalho sem identificadores reais em `apoio/caso_sanitizado.md`.
2. Consulte manualmente as fontes primárias escolhidas em `apoio/fonte_1.md` e `apoio/fonte_2.md`.
3. Limite a consulta e a resposta às fontes e aos fatos fictícios, conforme `docs/limites_e_sigilo.md` e `docs/especificacao.md`.
4. Registre a consulta em `prompts/consulta_rag.md` e a primeira resposta em `evidencias/resposta_inicial.md`.
5. Faça uma segunda rodada crítica com `prompts/auditoria.md`; registre achados em `evidencias/verificacao.md`.
6. Registre decisões, correções e pendências em `evidencias/revisao_humana.md` e publique a versão revisada em `entrega/orientacao_inicial.md`.

## Estrutura
```text
meucasoficticio/
├── README.md
├── entrada/relato_bruto.md
├── apoio/
│   ├── caso_sanitizado.md
│   ├── fonte_1.md
│   └── fonte_2.md
├── docs/
│   ├── limites_e_sigilo.md
│   └── especificacao.md
├── prompts/
│   ├── consulta_rag.md
│   └── auditoria.md
├── evidencias/
│   ├── resposta_inicial.md
│   ├── verificacao.md
│   ├── auditoria.md
│   └── revisao_humana.md
└── entrega/orientacao_inicial.md
```

## Critérios de aceitação
- Respostas dissertativas usam conceitos com cautela e separam fato, fonte e inferência.
- O caso continua inteiramente fictício; nenhuma informação real ou protegida é acrescentada.
- Cada afirmação jurídica relevante da orientação aponta para fonte e trecho verificável; lacunas ficam explícitas.
- A consulta RAG limita a resposta ao conteúdo selecionado e pede indicação de arquivo e seção.
- Há registro da resposta inicial, verificação, auditoria e decisão humana, inclusive correções e pontos não resolvidos.
- A orientação final não inventa valores, datas, documentos, resultados probatórios ou conclusões que o caso não fornece.

## Uso e reprodução
Abra a pasta no VS Code. Leia este README e siga o fluxo acima. As fontes são links para textos oficiais; confira a versão vigente antes de qualquer uso fora da atividade. O histórico Git registra a organização do projeto e o fechamento do fluxo.

## Repositório
URL pública: https://github.com/M0vero/Caso-Fromigas-Oper-rias-N1

## Proveniência e data
O relato bruto foi fornecido para esta atividade. As fontes oficiais foram consultadas em 02/10/2026. A versão sanitizada e as evidências são artefatos didáticos produzidos para a parte 2 da atividade.
