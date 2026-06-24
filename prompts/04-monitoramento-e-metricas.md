# Fase 4 — Monitoramento e métricas

> Prompts de IA para medir se o sistema de coordenação está funcionando: interpretar fluxo, auditar a saúde do sistema e comunicar progresso à liderança.
>
> Parte da [camada de IA](../docs/09-ia-em-cada-fase.md) do estudo de caso.

---

## Interpretar métricas de fluxo do nível 2

**Quando usar:** ao analisar os dados do board (lead time, WIP, bloqueios) e precisar entender o que eles dizem.
**O que você recebe:** uma leitura dos números com gargalos e tendências.

> Você é um analista de fluxo especializado em sistemas de coordenação. Interprete as métricas do meu board de Flight Level 2.
>
> **Métricas atuais:** [lead time de ponta a ponta, WIP no FL2, número de itens bloqueados, tempo médio em bloqueio, throughput]
> **Contexto:** [mudanças recentes na operação, número de times]
>
> Produza:
> 1. **Leitura das métricas** — o que cada número indica sobre a saúde da coordenação.
> 2. **Gargalos** — onde o fluxo está travando (qual coluna, qual transição).
> 3. **Tendências** — o que está melhorando ou piorando e o possível motivo.
> 4. **Ações sugeridas** — 2 ou 3 experimentos, cada um com a métrica que deve mover.
>
> Lembre que velocity dos times não mede coordenação. Foque nas métricas de fluxo de ponta a ponta.

**Dica de uso:** desconfie de throughput subindo com WIP também subindo. Costuma ser acúmulo de trabalho em paralelo, não aceleração real.

---

## Diagnosticar a saúde do sistema de coordenação

**Quando usar:** periodicamente, para avaliar se o sistema FL2 ainda serve ao propósito ou se degradou.
**O que você recebe:** um diagnóstico da saúde do sistema, além das métricas brutas.

> Você é um consultor que audita sistemas Flight Levels. Avalie a saúde do meu sistema de coordenação nível 2, indo além dos números.
>
> **Como o sistema opera hoje:** [como o board é usado, como as cadências acontecem, quem participa]
> **Sintomas percebidos:** [o que parece estar funcionando bem e o que parece ter esfriado]
>
> Produza:
> 1. **Saúde por dimensão** — board, cadências, métricas, engajamento dos times.
> 2. **Sinais de degradação** — board inchado, cadência virando status, visibilidade virando cobrança.
> 3. **Causa provável** de cada sintoma.
> 4. **Correções prioritárias** — o que ajustar primeiro para maior impacto.
>
> Seja franco sobre sinais de que o sistema virou burocracia. Um FL2 que não gera decisão deixou de coordenar.

**Dica de uso:** rode este diagnóstico a cada poucos meses. Sistemas de coordenação degradam silenciosamente — o board incha, as reuniões esvaziam de decisão, e ninguém percebe até o fluxo travar de novo.

---

## Construir a narrativa de progresso para a liderança

**Quando usar:** ao reportar o avanço do portfólio coordenado para a liderança de produto e engenharia.
**O que você recebe:** uma narrativa executiva ancorada no fluxo real de entregas.

> Você é um especialista em comunicação executiva no contexto de Flight Levels. Traduza o estado do meu board de coordenação numa narrativa de progresso para a liderança.
>
> **Estado das entregas coordenadas:** [o que avançou, o que está em risco, o que travou]
> **Objetivos a que se conectam:** [os OKRs ou metas relacionados]
> **Público:** [liderança de produto, engenharia, diretoria]
>
> Produza:
> 1. **Narrativa executiva** — um parágrafo que conta como as entregas estão movendo os objetivos.
> 2. **Riscos que exigem decisão** — o que a liderança precisa decidir ou apoiar.
> 3. **O número que sustenta a história** — a métrica de fluxo mais relevante, com contexto.
> 4. **Próximos marcos** — o que esperar no próximo período.
>
> Fale em linguagem de negócio e decisão, não em jargão de fluxo. A liderança quer saber se os objetivos avançam, não os detalhes do board.

**Dica de uso:** lidere pela conclusão (objetivos avançando ou em risco) e só então mostre o dado que a sustenta. Liderança quer a leitura, não o dashboard.

---

**Fase anterior:** [Fase 3 — Operação e facilitação](03-operacao-e-facilitacao.md)
**Próxima fase:** [Fase 5 — Melhoria contínua](05-melhoria-continua.md)
