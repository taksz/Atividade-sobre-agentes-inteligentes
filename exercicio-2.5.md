# Exercício 2.5

## Agente

**Definição:** É qualquer coisa que percebe o ambiente por meio de sensores e age sobre ele por meio de atuadores. Ele decide o que fazer para tentar alcançar um objetivo.

**Exemplo:** Um robô aspirador: sente a sujeira com sensores e aspira com seu motor.

## Função de agente

**Definição:** É a descrição abstrata do comportamento do agente: para cada histórico possível de percepções, ela diz qual ação o agente toma. Ela diz o que o agente faz, mas não como isso é calculado.

**Exemplo:** Uma tabela do aspirador que liga cada sequência de percepções (como “sujo”, “limpo”) a uma ação (aspirar, mover).

## Programa de agente

**Definição:** É o código que implementa a função de agente em uma máquina real. Ele recebe só a percepção atual e devolve uma ação; se precisar do passado, tem de guardá-lo na memória.

**Exemplo:** O código `se sujo: aspirar, senão: mover` rodando no robô aspirador.

## Racionalidade

**Definição:** É escolher, a cada momento, a ação que deve dar o melhor resultado esperado, com base no que o agente percebeu e sabe. Ser racional não é ser onisciente nem garantir sucesso.

**Exemplo:** Atravessar a rua quando ela parece livre é racional, mesmo que um imprevisto raro aconteça.

## Autonomia

**Definição:** É a capacidade de o agente agir com base na própria experiência e percepções, e não só no que o projetista programou. Quanto mais ele aprende e se adapta, mais autônomo é.

**Exemplo:** Um robô que aprende sozinho o mapa da casa é mais autônomo que outro que já vem com o mapa fixo.

## Agente reativo

**Definição:** É o agente que decide só com a percepção atual, usando regras do tipo “se tal situação, faça tal ação”. Ele não tem memória nem planeja o futuro.

**Exemplo:** Um termostato: se a temperatura passa do limite, liga o ar-condicionado.

## Agente baseado em modelo

**Definição:** É o agente que guarda um estado interno com o que não está visível agora. Para isso usa um modelo de como o mundo muda e de como suas ações o afetam.

**Exemplo:** Um carro autônomo que lembra do veículo que entrou no ponto cego e continua levando-o em conta.

## Agente baseado em objetivos

**Definição:** É o agente que escolhe suas ações pensando em uma meta a alcançar. Ele busca ou planeja a sequência de ações que o leva até ela.

**Exemplo:** Um GPS que procura a rota até o destino escolhido pelo usuário.

## Agente baseado em utilidade

**Definição:** É o agente que compara os resultados possíveis por uma medida de “satisfação” (utilidade) e escolhe a ação de maior utilidade esperada. Serve quando há vários fatores ou incerteza.

**Exemplo:** Um app de rotas que pondera tempo, pedágio e segurança para escolher o melhor caminho.

## Agente com aprendizagem

**Definição:** É o agente que melhora com a experiência: ele observa os resultados de suas ações e ajusta seu comportamento para ter desempenho melhor com o tempo.

**Exemplo:** Um filtro de spam que aprende com as mensagens que o usuário marca como lixo.
