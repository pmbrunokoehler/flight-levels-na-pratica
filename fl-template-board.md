# Template — Board de Coordenação (Flight Level 2)

> Modelo enxuto para começar. Adapte as colunas ao caminho real que uma entrega percorre no seu contexto. Comece com menos colunas do que acha que precisa.

## Estrutura mínima sugerida

| Coluna | O que vive aqui | Critério de saída |
|--------|-----------------|-------------------|
| **Opções** | Itens candidatos, ainda não comprometidos | Decisão de que vale priorizar |
| **Em definição** | Itens sendo detalhados o suficiente para iniciar | Definição clara + times identificados |
| **Pronto para iniciar** | Itens definidos, aguardando capacidade | Time com capacidade para puxar |
| **Em andamento** | Entregas ativas, atravessando os times | Trabalho concluído em todos os times envolvidos |
| **Em validação** | Entregas em verificação/homologação | Validação aprovada |
| **Concluído** | Entregas finalizadas | — |

> 📝 **[PREENCHER]:** ajuste as colunas para o fluxo real. Nem todo contexto precisa de "Em validação" separado; alguns precisam de uma coluna de "Bloqueado" explícita. O board deve espelhar o seu caminho, não este modelo.

## Regras de uso recomendadas

- **Limite de WIP:** defina um número máximo de itens em "Em andamento". Sem limite, o board vira lista de desejos e o fluxo trava.
- **Sinalização de bloqueio:** marque visualmente itens parados por dependência. O tempo em bloqueio é o dado mais revelador do board.
- **Granularidade:** um item = uma entrega de valor que cruza times. Se couber inteiro dentro de um time, ele não pertence a este board.
- **Dono da movimentação:** defina quem atualiza o board e quando (idealmente na cadência de coordenação, com todos vendo).

## O que NÃO colocar aqui

- Tarefas internas de um único time (pertencem ao board de FL1 daquele time).
- Subtarefas técnicas de implementação.
- Qualquer item cujo progresso só interessa a um time.
