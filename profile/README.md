# VitrineIA

**Inteligência comercial para lojistas de shopping centers.**

A VitrineIA transforma dados de visitantes e de vendas em decisões estratégicas, conectando o comportamento do público do shopping às necessidades dos lojistas.

---

## Sumário

- [Visão Geral](#visão-geral)
- [Problema](#problema)
- [Solução](#solução)
- [Arquitetura e Stack Tecnológica](#arquitetura-e-stack-tecnológica)
- [Privacidade e Conformidade](#privacidade-e-conformidade)
- [Entregas do Hackathon](#entregas-do-hackathon)
- [Documentação](#documentação)
- [Fluxo de Contribuição](#fluxo-de-contribuição)
- [Equipe](#equipe)

---

## Visão Geral

A VitrineIA é uma plataforma de inteligência comercial e engajamento para o ambiente de shopping centers. Ela conecta o comportamento dos visitantes aos dados comerciais das lojas, permitindo que lojistas compreendam o público, identifiquem oportunidades de negócio e planejem ações conjuntas com outros estabelecimentos.

## Problema

Os lojistas de um shopping atendem públicos com interesses variados, mas dispõem de pouca informação estruturada sobre o perfil dos consumidores que circulam pelo empreendimento. Isso dificulta o mapeamento de oportunidades comerciais e a identificação dos fatores que influenciam o desempenho de cada operação.

## Solução

A plataforma opera em três frentes integradas:

1. **Coleta de intenções de compra:** totens com QR Code oferecem recompensas instantâneas em troca da participação em pesquisas rápidas de preferência. Os dados são tratados de forma anonimizada, em conformidade com a LGPD.
2. **Análise de dados:** as informações coletadas são cruzadas com os dados comerciais das lojas, e técnicas de mineração de dados, como regras de associação, identificam padrões de consumo e relações entre segmentos.
3. **Recomendações com IA generativa:** os resultados consolidados alimentam um assistente de IA que sugere campanhas conjuntas, vendas cruzadas e oportunidades de vendas aos lojistas.

## Arquitetura e Stack Tecnológica

| Camada | Tecnologia |
| :--- | :--- |
| Frontend | Next.js |
| Backend | Java com Spring Boot |
| Banco de dados | PostgreSQL |
| Inteligência e dados | Regras de associação (mineração de dados) e API de IA generativa |

O detalhamento da arquitetura, dos requisitos e das decisões técnicas está na documentação do projeto.

## Privacidade e Conformidade

O tratamento de dados segue os princípios da Lei Geral de Proteção de Dados (LGPD). Os lojistas têm acesso apenas a informações agregadas e anonimizadas sobre os visitantes, e os dados comerciais de cada estabelecimento são isolados dos demais.

## Entregas do Hackathon

| Etapa | Prazo | Escopo | Status |
| :--- | :--- | :--- | :--- |
| Etapa 1 | 13/11, até 12h | Planejamento técnico, arquitetura, protótipos e documentação inicial (`./docs`) | Concluída |

## Documentação

A documentação técnica, a arquitetura, os requisitos e os protótipos estão disponíveis no diretório [`./docs`](./docs).

## Fluxo de Contribuição

Toda alteração é integrada por meio de pull request com revisão obrigatória de outro integrante da equipe, sem commits diretos na branch principal.

## Equipe

Organização **Charizard-Rackarun**

- Kelwen Lourenço
- Carlos
- Thiago
- Warly Martins
