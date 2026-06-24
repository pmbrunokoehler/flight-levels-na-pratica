# Fase 1 — Preparação e diagnóstico

> Prompts de IA para a fase que antecede qualquer board. O objetivo aqui é decidir se Flight Levels nível 2 é mesmo a resposta e mapear o terreno antes de construir.
>
> Parte da [camada de IA](../docs/09-ia-em-cada-fase.md) do estudo de caso. Estes prompts são específicos de Flight Levels; para prompts genéricos de gestão, veja o repositório [ai-pm-playbook](https://github.com/brunokoehler/ai-pm-playbook).

> 📝 **[PREENCHER]:** ajuste o link do `ai-pm-playbook` para a URL real quando publicá-lo.

---

## Mapear o fluxo de valor de ponta a ponta

**Quando usar:** no início, para enxergar o caminho que uma entrega percorre entre os times antes de tentar coordená-lo.
**O que você recebe:** um mapa do fluxo com etapas, times envolvidos e os pontos de transição onde o trabalho tende a esperar.

> Você é um especialista em fluxo de valor e coordenação entre times. Ajude-me a mapear o fluxo de ponta a ponta de uma entrega na minha operação.
>
> **Contexto:**
> - Produto/serviço: [descreva em termos genéricos]
> - Times envolvidos: [liste os times e o que cada um faz]
> - Como uma entrega nasce e chega ao cliente hoje: [descreva o caminho como você o entende]
>
> Produza:
> 1. **O fluxo mapeado** — as etapas que uma entrega percorre, do início ao cliente, indicando qual time atua em cada uma.
> 2. **Pontos de transição** — onde o trabalho passa de um time para outro (são os candidatos a gargalo).
> 3. **Riscos de espera** — em quais transições o trabalho provavelmente fica parado esperando, e por quê.
> 4. **Perguntas de validação** — o que eu deveria confirmar com os times para validar este mapa.
>
> Foque nas transições entre times, não no trabalho interno de cada um. É no espaço entre eles que mora o problema de coordenação.

**Dica de uso:** valide o mapa gerado com pessoas de times diferentes. Cada time enxerga só o próprio pedaço; o mapa real emerge do cruzamento das visões.

---

## Diagnóstico: coordenação ou execução?

**Quando usar:** para decidir se o seu problema é de coordenação entre times (onde Flight Levels ajuda) ou de execução interna (onde não ajuda).
**O que você recebe:** um diagnóstico que evita aplicar a ferramenta errada ao problema.

> Você é um consultor de agilidade organizacional cético e honesto. Meu objetivo é descobrir se Flight Levels nível 2 é a resposta certa para o meu problema, ou se eu estaria aplicando a ferramenta errada.
>
> **Sintomas que observo:** [descreva o que acontece — atrasos, retrabalho, dependências, falta de visibilidade, etc.]
> **O que já tentei:** [o que foi feito até agora e o resultado]
>
> Produza:
> 1. **Classificação dos sintomas** — quais apontam para problema de coordenação entre times e quais apontam para execução interna de um time.
> 2. **Veredito** — Flight Levels nível 2 endereça o meu problema principal? Seja direto, inclusive se a resposta for "não".
> 3. **Alternativas** — se parte do problema for de execução, o que endereçaria isso melhor.
> 4. **Risco de aplicar FL2 aqui** — o que pode dar errado se eu implementar coordenação onde o problema é outro.
>
> Não force a recomendação de Flight Levels. Prefiro um "não" honesto a uma implementação que não resolve.

**Dica de uso:** se a IA "empurrar" Flight Levels mesmo com sintomas de execução, desconfie e refine o contexto. Um bom diagnóstico às vezes conclui que a ferramenta não serve — e isso economiza meses.

---

## Identificar candidatos a flight items

**Quando usar:** depois de mapear o fluxo, para definir o que merece subir ao board de coordenação.
**O que você recebe:** uma lista de candidatos a flight items, separando o que cruza times do que é interno.

> Você é um especialista em desenho de sistemas Flight Levels. Ajude-me a identificar quais itens de trabalho devem viver no board de coordenação (nível 2) e quais devem ficar nos times (nível 1).
>
> **Fluxo de valor mapeado:** [cole ou descreva o fluxo da etapa anterior]
> **Tipos de trabalho que temos hoje:** [liste exemplos genéricos de entregas, iniciativas, projetos]
>
> Produza:
> 1. **Candidatos a flight item (FL2)** — o que depende de mais de um time e precisa ser coordenado.
> 2. **O que fica no FL1** — o que é interno a um único time e não pertence ao board de coordenação.
> 3. **Casos ambíguos** — itens que poderiam ir para qualquer nível, com o critério para decidir.
> 4. **Teste de granularidade** — para cada candidato, se ele é grande demais (esconde progresso) ou pequeno demais (polui a coordenação).
>
> Aplique a pergunta de controle: "isto precisa ser coordenado entre times?". Se a resposta for não, vai para o FL1.

**Dica de uso:** na dúvida, deixe o item no FL1. É mais fácil promover um item ao board de coordenação quando ele revela dependências do que remover o excesso depois que o board já inchou.

---

**Próxima fase:** [Fase 2 — Design e implementação](02-design-e-implementacao.md)
