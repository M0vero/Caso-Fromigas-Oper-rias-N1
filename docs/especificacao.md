# Especificação do fluxo

## Objetivo
Produzir uma orientação didática inicial sobre o caso trabalhista inteiramente fictício, usando consulta RAG manual com fontes normativas oficiais selecionadas, rastreabilidade por arquivo/seção, auditoria crítica e revisão humana.

## Entradas autorizadas
- `apoio/caso_sanitizado.md`: único resumo factual autorizado para a consulta.
- `apoio/fonte_1.md`: Constituição Federal, art. 7º nos incisos apontados.
- `apoio/fonte_2.md`: CLT e NR-15, dispositivos apontados.
- `docs/limites_e_sigilo.md`: regras de segurança e escopo.

O relato bruto é preservado para proveniência e não é necessário enviar a ferramentas externas. Nenhuma outra fonte ou memória deve ser usada para preencher lacunas.

## Público e formato
Público: estudante que precisa entender como organizar e conferir uma resposta assistida por IA. Resposta em português, Markdown, com seções: síntese limitada; análise por tema; fatos ausentes; fontes; ressalva didática. Distinguir `Fato do relato`, `Regra da fonte` e `Análise/limite`.

## Critérios de aceitação
1. Cada regra jurídica material traz arquivo e dispositivo ou item verificável.
2. A resposta cobre jornada/horas extras, intervalo, repouso semanal/domingos, insalubridade, dano extrapatrimonial, reflexos e honorários, sem resolver questões que os dados não permitem.
3. Diferencia alegações, afirmações narrativas sobre a sentença e fatos comprovados apenas dentro da ficção.
4. Não inventa resultado do recurso, grau pericial, valor, salário ou cálculo.
5. Declara os dados faltantes e a necessidade de conferência humana e da redação vigente.
6. Não usa informação externa às fontes selecionadas; fontes são manualmente escolhidas, não recuperadas por sistema automático.

## Procedimento
1. Ler o caso sanitizado e as fichas de fonte.
2. Extrair somente as regras listadas nas fichas, confirmando o dispositivo no link oficial.
3. Redigir a resposta inicial com o prompt registrado em `prompts/consulta_rag.md`.
4. Auditar cobertura, rastreabilidade, inferências, lacunas e limites com `prompts/auditoria.md`.
5. Registrar correções e decisões humanas em `evidencias/revisao_humana.md`.
6. Revisar a entrega final contra os critérios acima. Registrar como pendente qualquer conferência que não tenha sido realizada.

## Registro
Este repositório registra o procedimento e o conteúdo didático, não dados de produção, chamadas automáticas, nem validação jurídica profissional. Não há automação, treinamento ou inferência de modelo implementados.
