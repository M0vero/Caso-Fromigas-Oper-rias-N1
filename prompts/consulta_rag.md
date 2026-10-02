# Prompt — consulta RAG manual

## Fontes selecionadas
Antes da consulta, a pessoa responsável seleciona e lê manualmente apenas:
1. `apoio/caso_sanitizado.md` — fatos do caso fictício.
2. `apoio/fonte_1.md` — Constituição, dispositivos indicados.
3. `apoio/fonte_2.md` — CLT e NR-15, dispositivos indicados.
4. `docs/limites_e_sigilo.md` — restrições do projeto.

Isto é RAG manual: a seleção, leitura e recuperação de trechos é feita por pessoa; não existe índice vetorial nem busca automática.

## Instrução para a resposta
> Responda em português e apenas com base nos trechos verificados nas fontes selecionadas acima. Trate o caso como inteiramente fictício. Para cada tópico, separe (a) o que o relato diz, (b) a regra que consta da fonte e (c) o limite da análise. Cite o caminho do arquivo e o artigo/inciso/item usado. Analise, sem quantificar, jornada e horas extras, intervalo, repouso semanal/domingos, insalubridade, dano extrapatrimonial, reflexos e honorários. Aponte quais dados faltam. Não invente fatos, prova, laudo, valor, regra ou resultado de recurso. Se uma fonte não sustentar a afirmação, diga que não foi possível confirmá-la e deixe a questão em aberto. Termine esclarecendo que é material didático, não aconselhamento jurídico, e que a redação oficial e a aplicação exigem conferência humana.

## Registro de execução
Anotar data, trechos efetivamente consultados e ferramenta/modelo, se houver, em `evidencias/resposta_inicial.md`. Não registrar credenciais ou dados pessoais.
