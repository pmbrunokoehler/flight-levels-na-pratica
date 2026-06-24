# Diagramas — Arquitetura Flight Levels

> Os diagramas do estudo de caso reunidos em um lugar, em Mermaid (renderiza nativamente no GitHub). Reutilize e adapte.

## Visão geral dos três níveis

```mermaid
flowchart TD
    subgraph FL3["Flight Level 3 — Estratégico"]
        STRAT["Objetivos e OKRs<br/>priorização de iniciativas"]
    end

    subgraph FL2["Flight Level 2 — Coordenação"]
        COORD["Board de coordenação<br/>entregas que cruzam times"]
    end

    subgraph FL1["Flight Level 1 — Operacional"]
        T1["Squad A"]
        T2["Squad B"]
        T3["Squad C"]
    end

    STRAT -->|"iniciativas descem"| COORD
    COORD -->|"prioridade desce"| T1
    COORD -->|"prioridade desce"| T2
    COORD -->|"prioridade desce"| T3
    T1 -.->|"status sobe"| COORD
    T2 -.->|"status sobe"| COORD
    T3 -.->|"status sobe"| COORD
    COORD -.->|"avanço sobe"| STRAT
```

> 📝 **[PREENCHER]:** ajuste o número de squads à sua realidade.

## A flight route: do OKR ao épico

```mermaid
flowchart LR
    OKR["OKR estratégico"]
    INIT["Iniciativa"]
    FL2["Item de coordenação<br/>(FL2)"]
    EPIC["Épicos nos squads<br/>(FL1)"]

    OKR --> INIT --> FL2 --> EPIC
    EPIC -.->|"progresso real"| FL2
    FL2 -.->|"avanço"| INIT
    INIT -.->|"leitura do KR"| OKR
```

## As cinco atividades aplicadas ao nível 2

```mermaid
mindmap
  root((Flight Level 2))
    Visualizar
      Board de coordenação
      Dependências visíveis
    Criar foco
      Limite de WIP
      Item = valor que cruza times
    Interações ágeis
      Cadência de coordenação
      Cadência de priorização
      Visibilidade p/ liderança
    Medir
      Lead time ponta a ponta
      WIP no FL2
      Tempo em bloqueio
    Melhorar
      Ajuste de cadências
      Refino do board
```

## Como usar estes diagramas

Cole o bloco Mermaid correspondente no documento onde fizer sentido, ou mantenha este arquivo como referência visual central do repositório. No GitHub, os diagramas Mermaid renderizam automaticamente — não é preciso gerar imagens.

> 📝 **[PREENCHER]:** se quiser personalizar, substitua "Squad A/B/C" por nomes funcionais anonimizados que reflitam a sua estrutura (ex.: "Squad de Core", "Squad de Integrações"), mantendo o sigilo sobre a empresa.
