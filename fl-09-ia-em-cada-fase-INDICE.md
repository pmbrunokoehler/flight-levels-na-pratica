# 09 — IA em cada fase da implementação

> A camada de IA do estudo de caso. Os prompts são específicos para *implementar e operar* um sistema de coordenação Flight Levels — não são prompts genéricos de gestão (esses vivem no repositório [ai-pm-playbook](https://github.com/pmbrunokoehler/ai-pm-playbook)).

Para manter cada fase navegável e independente, os prompts ficam em arquivos separados na pasta [`prompts/`](prompts/), um por fase do ciclo de implementação. Cada arquivo segue o mesmo formato: quando usar, o que você recebe, o prompt pronto para copiar e uma dica de uso.

## As cinco fases

| Fase | Arquivo | O que cobre |
|------|---------|-------------|
| 1 | [Preparação e diagnóstico](prompts/01-preparacao-e-diagnostico.md) | Mapear o fluxo de valor, decidir se FL2 é a resposta, identificar flight items |
| 2 | [Design e implementação](prompts/02-design-e-implementacao.md) | Desenhar o board, calibrar granularidade, desenhar as cadências |
| 3 | [Operação e facilitação](prompts/03-operacao-e-facilitacao.md) | Preparar a cadência, destravar dependências, conectar OKR à entrega |
| 4 | [Monitoramento e métricas](prompts/04-monitoramento-e-metricas.md) | Interpretar fluxo, auditar a saúde do sistema, narrativa para a liderança |
| 5 | [Melhoria contínua](prompts/05-melhoria-continua.md) | Retro do sistema, detectar desvios, planejar a expansão |

## Como esta camada se conecta ao estudo de caso

Cada fase dialoga com os documentos do case: a preparação com o [01](fl-01-contexto.md), o design com o [03](fl-03-design.md) e o [04](fl-04-cadencias.md), o monitoramento com o [06](fl-06-metricas.md), e a melhoria contínua com o [07](fl-07-erros.md). A intenção é que você leia o caso para entender *o que* foi feito, e use os prompts para *fazer* no seu próprio contexto — com IA acelerando cada passo.

A regra de ouro vale para todos: a qualidade da saída depende do contexto que você fornece. A IA acelera o raciocínio e organiza a estrutura, mas as decisões continuam sendo suas.

> 📝 **[PREENCHER]:** ajuste o link do `ai-pm-playbook` para a URL real quando publicá-lo. Se você usou IA de fato em alguma fase da implementação real, acrescente aqui uma nota curta contando como — transforma "prompts que montei" em "prompts que usei".
