# 01 — Contexto e problema

> Antes de qualquer solução, o cenário. Esta seção descreve o ambiente em que a coordenação estava quebrada — sem isso, nenhuma decisão de design faz sentido.

## O ambiente

Uma operação de tecnologia com múltiplos squads trabalhando sobre um mesmo produto financeiro. Cada time era ágil dentro das próprias fronteiras: tinha seu backlog, suas cerimônias, seu ritmo de entrega. No papel, tudo funcionava. Na prática, o produto como um todo andava devagar.

> 📝 **[PREENCHER]:** descreva brevemente o ambiente real (sem identificar a empresa). Sugestão de variáveis a informar: número de squads, composição de cada um (devs back/front, QA, UX, PO), modelo de trabalho (remoto/híbrido), cadência de entrega (ex.: quinzenal), e o tipo de produto em termos genéricos (ex.: "produto de pagamentos B2B").

## Os sintomas

O que se via no dia a dia:

- **Dependências invisíveis.** Um time descobria tarde que dependia da entrega de outro, e o trabalho parava esperando.
- **Prioridades desalinhadas.** Cada squad priorizava o que fazia sentido para si, mas a soma das prioridades locais não entregava o objetivo do produto.
- **Falta de visibilidade de ponta a ponta.** A liderança via o que cada time fazia isoladamente, mas não conseguia enxergar o fluxo de valor inteiro — da ideia à entrega ao cliente.
- **Previsão frágil.** A pergunta "quando isso fica pronto?" não tinha resposta confiável, porque ninguém via o caminho completo que uma entrega percorria entre os times.

> 📝 **[PREENCHER]:** acrescente 1 ou 2 sintomas específicos que você observou na sua operação. Quanto mais concreto, mais o leitor se identifica.

## A causa-raiz

O problema não era falta de agilidade nos times. Cada squad já era eficiente no seu pedaço. O problema estava no **espaço entre os times** — na coordenação do fluxo de valor que atravessava todos eles.

É a metáfora que Klaus Leopold usa: se cada time é responsável por uma fileira de teclas do teclado e melhora a velocidade de digitar a própria fileira, o cliente que quer escrever uma carta só se beneficia se todas as fileiras funcionarem de forma orquestrada. Otimizar um time isolado não acelera a entrega de valor ao cliente. O gargalo real vive na interação entre eles.

## Por que não bastava "melhorar os times"

A tentação inicial costuma ser pedir mais velocidade a cada squad. Mas acelerar partes de um sistema com a coordenação quebrada só aumenta o acúmulo de trabalho parado entre as etapas. O que faltava não era capacidade de execução local — era um nível de coordenação que tornasse visível e gerenciável o fluxo entre os times.

Esse é exatamente o problema que o Flight Level 2 endereça. A próxima seção explica o modelo antes de entrarmos no design.

> 📝 **[PREENCHER]:** se houver, inclua o "momento de virada" — o episódio concreto que deixou claro que o problema era de coordenação e não de execução (ex.: uma entrega importante que atrasou por dependência não mapeada). Histórias específicas são o que tornam um case memorável em entrevista.
