# Flight Levels na Prática

> Um relato prático de como estruturei a coordenação entre múltiplos squads usando Flight Levels (nível 2), conectando estratégia a entregas — com os acertos, os erros e o que faria diferente.

A maior parte do conteúdo sobre Flight Levels é teórica. Este repositório é o oposto: um estudo de caso de implementação real, anonimizado, focado em quem precisa coordenar vários times que compartilham um objetivo e não conseguem enxergar o trabalho de ponta a ponta.

> **Nota sobre confidencialidade:** todos os exemplos são anonimizados. Nomes de empresas, produtos, pessoas e dados sensíveis foram removidos ou substituídos por equivalentes genéricos. O que permanece são os conceitos, as decisões de design e os aprendizados — aplicáveis a qualquer organização.

---

## O problema que motivou tudo

Vários squads trabalhando num mesmo produto, cada um ágil dentro das suas fronteiras, mas o fluxo de valor de ponta a ponta travado: dependências invisíveis, prioridades desalinhadas entre times, e uma liderança que não conseguia responder com confiança "quando isso fica pronto?".

Cada time otimizava o próprio pedaço. O sistema como um todo não andava.

**Flight Levels nível 2** foi a resposta para tornar a coordenação entre times visível e gerenciável, sem transformar squads autônomos em engrenagens controladas de cima.

---

## O que você encontra aqui

| Documento | Conteúdo |
|-----------|----------|
| [01 — Contexto e problema](fl-01-contexto.md) | O cenário inicial e por que a coordenação estava quebrada |
| [02 — O que é Flight Levels](fl-02-o-que-e.md) | Introdução honesta ao modelo, com créditos a Klaus Leopold |
| [03 — Design do nível 2](fl-03-design.md) | Flight items, flight routes e o board de coordenação |
| [04 — Cadências e interações](fl-04-cadencias.md) | As reuniões que sustentaram a coordenação |
| [05 — De OKRs a entregas](fl-05-okrs.md) | Como conectei o objetivo estratégico ao épico do time |
| [06 — Métricas e resultados](fl-06-metricas.md) | O que medimos e o que de fato melhorou |
| [07 — Erros e aprendizados](fl-07-erros.md) | O que não funcionou e o que eu faria diferente |
| [08 — Como aplicar no seu contexto](fl-08-aplicar.md) | Um guia para você adaptar isso ao seu cenário |

### Artefatos prontos para reuso

| Artefato | Descrição |
|----------|-----------|
| [Diagramas](fl-diagramas.md) | Diagramas Mermaid: visão geral dos três níveis, flight route e mapa de atividades |
| [Template — Board de coordenação](fl-template-board.md) | Estrutura mínima do board FL2 com colunas, regras de uso e o que evitar |
| [Template — Cadências](fl-template-cadencias.md) | Checklist de validação e modelos para as principais cadências |

---

## Resultado principal

> Redução de **40% no lead time médio** de entrega — não porque os times ficaram mais rápidos, mas porque o tempo que o trabalho passava *esperando entre times* caiu drasticamente.

---

## Para quem é este repositório

- **Agile Coaches e Scrum Masters** buscando uma camada de coordenação entre times sem burocracia
- **Product Managers e Delivery Managers** que precisam de visibilidade end-to-end sem perder a autonomia dos squads
- **Gestores e líderes** que querem conectar estratégia (OKRs) às entregas do dia a dia
- **Project Managers** migrando de gestão de projeto para gestão de fluxo

Não é um curso de Flight Levels — é o relato de quem implementou, ajustou e aprendeu na prática.

---

## Como usar este material

1. **Comece pelo [contexto](fl-01-contexto.md)** para entender o problema que este modelo resolve.
2. **Leia o [design do nível 2](fl-03-design.md)** para ver as decisões de estrutura do board.
3. **Consulte os [erros e aprendizados](fl-07-erros.md)** antes de sair implementando — evita armadilhas comuns.
4. **Use o [guia de aplicação](fl-08-aplicar.md)** como roteiro para o seu próprio contexto.
5. **Adapte os [templates](fl-template-board.md)** ao seu fluxo.

---

## Aviso importante

Flight Levels é um modelo de pensamento criado por **Klaus Leopold** e Siegfried Kaltenecker. Este repositório é uma aplicação prática e pessoal do modelo — não é material oficial da Flight Levels Academy.

Para o conteúdo de origem:
- [flightlevels.io](https://www.flightlevels.io/)
- Livro: *Flight Levels: Leading Organizations with Business Agility* — Klaus Leopold

---

## Sobre o autor

**Bruno Willian Koehler** — Delivery Manager & Agile Leader com 15+ anos liderando times de produto e engenharia. Estruturei a coordenação de portfólio via Flight Levels nível 2 numa operação de fintech, conectando OKRs estratégicos às entregas dos times.

[LinkedIn](https://linkedin.com/in/bruno-koehler) · brunokoehler@outlook.com

---

## Licença

[MIT](fl-LICENSE) — use, adapte e compartilhe livremente.
