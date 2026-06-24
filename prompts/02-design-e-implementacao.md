# Fase 2 — Design e implementação

> Prompts de IA para desenhar o sistema: o board, as rotas e as cadências. Use depois de concluir a [Fase 1](01-preparacao-e-diagnostico.md), com o fluxo de valor já mapeado.
>
> Parte da [camada de IA](../docs/09-ia-em-cada-fase.md) do estudo de caso.

---

## Desenhar o board de coordenação

**Quando usar:** ao estruturar as colunas do board a partir do fluxo de valor real.
**O que você recebe:** uma proposta de colunas (flight route) com critérios de entrada e saída de cada estágio.

> Você é um especialista em desenho de boards Flight Levels nível 2. Ajude-me a desenhar as colunas do board de coordenação a partir do meu fluxo de valor.
>
> **Fluxo de valor:** [descreva as etapas que uma entrega coordenada percorre]
> **Particularidades:** [bloqueios comuns, etapas de validação, dependências externas]
>
> Produza:
> 1. **Colunas propostas** — os estágios do board, do backlog à conclusão.
> 2. **Critério de entrada e saída** de cada coluna — o que define que um item pode avançar.
> 3. **Onde sinalizar bloqueios** — como tornar visível o trabalho parado.
> 4. **O risco de inchaço** — quais colunas tendem a virar "depósito" e como evitar.
>
> Mantenha o board o mais enxuto possível. Menos colunas, desde que reflitam o caminho real. Um board que tenta mostrar tudo deixa de coordenar.

**Dica de uso:** comece com menos colunas do que a IA sugerir. É mais fácil adicionar um estágio quando sentir falta do que remover um que nunca foi usado.

---

## Calibrar a granularidade dos flight items

**Quando usar:** quando os itens do board estão grandes demais (parados por semanas) ou pequenos demais (poluindo a coordenação).
**O que você recebe:** uma recalibragem do tamanho ideal dos itens de coordenação.

> Você é um especialista em fluxo de trabalho Flight Levels. Os itens do meu board de coordenação não estão no tamanho certo. Ajude-me a recalibrar.
>
> **Sintoma atual:** [os itens ficam "em andamento" por muito tempo / o board tem itens demais / outro]
> **Exemplos de itens atuais:** [descreva genericamente alguns itens do board hoje]
>
> Produza:
> 1. **Diagnóstico de granularidade** — os itens estão grandes ou pequenos demais, e como isso se manifesta.
> 2. **Tamanho-alvo** — o que um flight item de FL2 deveria representar no meu contexto.
> 3. **Como fatiar os grandes** — preservando o caráter de "entrega coordenada que cruza times".
> 4. **Como agrupar os pequenos** — ou rebaixá-los ao FL1 se forem internos.
>
> O item ideal representa uma entrega de valor coordenada — visível o suficiente para a liderança acompanhar, sem ser tão grande que esconda o progresso.

**Dica de uso:** se um item fica "em andamento" por mais de um ciclo da sua cadência principal, quase sempre ele é grande demais e precisa ser fatiado.

---

## Desenhar as cadências

**Quando usar:** ao definir quais reuniões de coordenação criar, evitando o excesso.
**O que você recebe:** um conjunto mínimo de cadências, cada uma com a pergunta que justifica sua existência.

> Você é um especialista em cadências de coordenação Flight Levels. Ajude-me a desenhar o conjunto mínimo de reuniões para sustentar a coordenação, sem cair no excesso de reuniões.
>
> **Contexto:** [número de times, com que frequência entregam, onde estão as dependências]
> **Decisões que precisam acontecer regularmente:** [o que precisa ser decidido — desbloqueio, priorização, visibilidade para liderança]
>
> Produza:
> 1. **Cadências propostas** — apenas as necessárias, cada uma com a pergunta única que ela responde.
> 2. **Para cada cadência** — frequência, duração, público mínimo e a decisão esperada.
> 3. **O que NÃO precisa de reunião** — o que pode ser resolvido de forma assíncrona.
> 4. **Sinais de excesso** — como saber se estou criando reuniões demais.
>
> Princípio: se uma cadência não tem uma pergunta que só ela responde, ela não deveria existir. Coordenação não é quantidade de reunião.

**Dica de uso:** comece com uma única cadência (a de coordenação) e adicione outras só quando sentir falta de uma pergunta que nenhuma reunião existente responde.

---

**Fase anterior:** [Fase 1 — Preparação e diagnóstico](01-preparacao-e-diagnostico.md)
**Próxima fase:** [Fase 3 — Operação e facilitação](03-operacao-e-facilitacao.md)
