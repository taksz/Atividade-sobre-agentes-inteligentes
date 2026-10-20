# Exercício 2.4

Considerei: jogador de linha no futebol; robô submarino autônomo em Titã (cenário hipotético); agentes de software nos casos 3 e 7.

## 1. Jogar futebol

| Campo | Resposta |
|---|---|
| Atividade e agente | Jogar futebol – Jogador de linha |
| Objetivo e hipóteses | Ajudar a equipe a vencer. Partida oficial, 11 contra 11. |
| P – Desempenho | Gols, vitória, passes certos, faltas evitadas. |
| E – Ambiente | Campo, bola, colegas, adversários, árbitro. |
| A – Atuadores | Pernas, pés, cabeça, voz. |
| S – Sensores | Visão, audição, tato, noção de posição. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Parcialmente observável | Não vê tudo ao redor nem as intenções dos outros. |
| Número de agentes | Multiagente (coopera e compete) | Colegas e adversários. |
| Previsibilidade | Estocástico | Bola e outros jogadores são imprevisíveis. |
| Dependência entre decisões | Sequencial | Cada jogada afeta as próximas. |
| Mudança durante a decisão | Dinâmico | O jogo não para enquanto decide. |
| Natureza dos elementos | Contínuo | Posição, velocidade e tempo. |
| Conhecimento do funcionamento | Conhecido | Regras e física conhecidas. |

## 2. Explorar os oceanos de Titã

| Campo | Resposta |
|---|---|
| Atividade e agente | Explorar os oceanos de Titã – Robô submarino |
| Objetivo e hipóteses | Mapear e coletar amostras. Sem outros agentes e sem controle em tempo real da Terra. |
| P – Desempenho | Área mapeada, amostras coletadas, dados enviados, robô preservado. |
| E – Ambiente | Oceano sob o gelo, correntes, pressão, temperatura. |
| A – Atuadores | Hélices, braço coletor, broca, antena. |
| S – Sensores | Sonar, câmera, termômetro, sensor de pressão, energia. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Parcialmente observável | Pouca visibilidade e sensores limitados. |
| Número de agentes | Agente único | Não há outros agentes. |
| Previsibilidade | Estocástico | Correntes e falhas são imprevisíveis. |
| Dependência entre decisões | Sequencial | Energia e posição afetam o futuro. |
| Mudança durante a decisão | Dinâmico | Correntes e gelo mudam. |
| Natureza dos elementos | Contínuo | Posição e pressão variam continuamente. |
| Conhecimento do funcionamento | Desconhecido | Pouco se sabe sobre o ambiente. |

## 3. Comprar livros usados de IA na Internet

| Campo | Resposta |
|---|---|
| Atividade e agente | Comprar livros usados de IA na Internet – Agente de software comprador |
| Objetivo e hipóteses | Comprar os livros certos com bom preço. Orçamento fixo. |
| P – Desempenho | Livros obtidos, preço baixo, boa condição, vendedor confiável. |
| E – Ambiente | Sites, anúncios, vendedores, outros compradores. |
| A – Atuadores | Busca, mensagens, ofertas, pagamento. |
| S – Sensores | Páginas dos anúncios, avaliações, e-mails. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Parcialmente observável | Não vê todos os anúncios nem a condição real do livro. |
| Número de agentes | Multiagente (competitivo) | Outros compradores e vendedores. |
| Previsibilidade | Estocástico | Preços e estoque mudam sem aviso. |
| Dependência entre decisões | Sequencial | Cada compra reduz o orçamento. |
| Mudança durante a decisão | Dinâmico | Anúncios mudam e são vendidos. |
| Natureza dos elementos | Discreto | Anúncios, preços e passos de compra. |
| Conhecimento do funcionamento | Conhecido | Regras de compra conhecidas. |

## 4. Jogar uma partida de tênis

| Campo | Resposta |
|---|---|
| Atividade e agente | Jogar uma partida de tênis – Tenista |
| Objetivo e hipóteses | Vencer a partida. Simples, regras oficiais. |
| P – Desempenho | Pontos, games e sets ganhos, poucos erros. |
| E – Ambiente | Quadra, rede, bola, adversário, vento. |
| A – Atuadores | Pernas, braço e raquete. |
| S – Sensores | Visão, tato, audição. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Parcialmente observável | Não sabe o efeito da bola nem a intenção do adversário. |
| Número de agentes | Multiagente (competitivo) | O adversário joga contra. |
| Previsibilidade | Estocástico | Quique, vento e erros. |
| Dependência entre decisões | Sequencial | Pontos e cansaço ligam as decisões. |
| Mudança durante a decisão | Dinâmico | Bola e adversário se movem. |
| Natureza dos elementos | Contínuo | Posição, velocidade e tempo. |
| Conhecimento do funcionamento | Conhecido | Regras e física conhecidas. |

## 5. Praticar tênis contra uma parede

| Campo | Resposta |
|---|---|
| Atividade e agente | Praticar tênis contra uma parede – Tenista treinando |
| Objetivo e hipóteses | Melhorar a técnica. Sem adversário. |
| P – Desempenho | Rebatidas seguidas, precisão. |
| E – Ambiente | Parede, bola, raquete, piso. |
| A – Atuadores | Pernas, braço e raquete. |
| S – Sensores | Visão, tato, audição. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Completamente observável | Bola, parede e quadra ficam todas à vista do jogador. |
| Número de agentes | Agente único | Não há outro jogador. |
| Previsibilidade | Estocástico | Pequenas irregularidades no piso e na parede deixam o quique um pouco imprevisível. |
| Dependência entre decisões | Sequencial | Cada rebatida leva à próxima. |
| Mudança durante a decisão | Dinâmico | A bola se move. |
| Natureza dos elementos | Contínuo | Posição e velocidade. |
| Conhecimento do funcionamento | Conhecido | Física do rebote conhecida. |

## 6. Realizar um salto de altura

| Campo | Resposta |
|---|---|
| Atividade e agente | Realizar um salto de altura – Atleta saltador |
| Objetivo e hipóteses | Passar a barra na maior altura. Três tentativas por altura. |
| P – Desempenho | Altura vencida, tentativas usadas. |
| E – Ambiente | Pista, barra, colchão, vento. |
| A – Atuadores | Pernas, tronco, braços. |
| S – Sensores | Visão, equilíbrio, tato dos pés. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Parcialmente observável | Não percebe bem a posição do corpo no ar. |
| Número de agentes | Agente único | Outros atletas não interferem. |
| Previsibilidade | Estocástico | Corpo e vento variam. |
| Dependência entre decisões | Sequencial | A corrida define o salto. |
| Mudança durante a decisão | Semidinâmico | O ambiente quase não muda, mas há tempo-limite. |
| Natureza dos elementos | Contínuo | Movimento e altura. |
| Conhecimento do funcionamento | Conhecido | Regras conhecidas. |

## 7. Participar de um leilão com lances

| Campo | Resposta |
|---|---|
| Atividade e agente | Participar de um leilão com lances – Agente de lances |
| Objetivo e hipóteses | Ganhar o item sem passar do valor máximo. Leilão inglês. |
| P – Desempenho | Lucro (valor do item − preço), respeitar o limite. |
| E – Ambiente | Casa de leilões, item, outros licitantes. |
| A – Atuadores | Enviar lance, desistir. |
| S – Sensores | Preço atual, lances dos outros, tempo restante. |

**Classificação do ambiente**

| Propriedade | Classificação | Justificativa |
|---|---|---|
| Observabilidade | Parcialmente observável | Não sabe quanto os outros pagariam. |
| Número de agentes | Multiagente (competitivo) | Disputam o mesmo item. |
| Previsibilidade | Estocástico | Reações dos outros são imprevisíveis. |
| Dependência entre decisões | Sequencial | Cada lance muda o preço. |
| Mudança durante a decisão | Dinâmico | Outros dão lances enquanto decide. |
| Natureza dos elementos | Discreto | Lances em valores fixos. |
| Conhecimento do funcionamento | Conhecido | Regras do leilão conhecidas. |

## Conclusão

**(1) Tênis x parede:** Na partida, o adversário é outro agente que reage ao jogador: o ambiente é multiagente, competitivo, parcialmente observável e mais imprevisível, e o agente precisa pensar na estratégia. Contra a parede, só há um agente, tudo fica à vista e o rebote é quase previsível. Por isso serve para treinar técnica, mas não tática.

**(2) Informação incompleta na compra:** O agente não sabe a condição real do livro nem o que outros vendedores têm. Precisa decidir com incerteza, usando avaliações e comparando preços.

**(3) Influência de outros agentes:** No futebol, os outros são colegas (cooperação) e adversários (competição). No leilão são só competidores, e o lance de um muda o que os outros farão.
