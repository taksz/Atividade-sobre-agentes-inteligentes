# Exercício 2.3

## a. **FALSO**

**Justificativa:** Racionalidade depende do que o agente percebe, não de tudo o que existe no ambiente. Com informação parcial ele ainda pode escolher a melhor ação possível.

**Exemplo ou contraexemplo:** O aspirador que só vê o quadrado onde está é racional com a regra “sujo → aspira; limpo → muda de quadrado”.

## b. **VERDADEIRO**

**Justificativa:** O agente reativo só olha a percepção atual. Se a melhor ação depende do passado, ele não consegue acertar sempre.

**Exemplo ou contraexemplo:** O agente recebe sempre o mesmo sinal “bip” e só ganha pontos se agir na 3ª vez. Sem memória, ele não sabe qual é a 3ª vez.

## c. **VERDADEIRO**

**Justificativa:** Se o desempenho não depende das ações, qualquer ação rende o mesmo, então todo agente é racional.

**Exemplo ou contraexemplo:** Ambiente em que a pontuação é sempre a mesma, faça o agente o que fizer.

## d. **FALSO**

**Justificativa:** A função recebe todo o histórico de percepções. O programa recebe só a percepção atual e precisa guardar o passado por conta própria, se precisar.

**Exemplo ou contraexemplo:** A função do aspirador usa toda a sequência de percepções; o programa recebe só [posição, sujeira] do momento.

## e. **FALSO**

**Justificativa:** O programa roda em uma máquina com memória e tempo limitados. Algumas funções não podem ser calculadas ou exigem memória infinita.

**Exemplo ou contraexemplo:** Uma função que diz se qualquer programa vai parar ou não (problema da parada) não é computável.

## f. **VERDADEIRO**

**Justificativa:** Se todas as ações dão o mesmo resultado, escolher ao acaso também é ótimo.

**Exemplo ou contraexemplo:** Ambiente determinista em que a pontuação é igual para qualquer ação: o agente aleatório é racional.

## g. **VERDADEIRO**

**Justificativa:** A racionalidade depende de agente, ambiente e medida de desempenho. Se dois ambientes pedem as mesmas ações, o mesmo agente é racional nos dois.

**Exemplo ou contraexemplo:** O aspirador reativo é racional no mundo de dois quadrados e também em outro igual, só com sujeira inicial diferente.

## h. **FALSO**

**Justificativa:** Não observar o ambiente não torna qualquer ação boa. O agente ainda pode escolher uma ação pior que outra disponível.

**Exemplo ou contraexemplo:** Num ambiente sem sensores, em que aspirar dá pontos, um agente que nunca aspira é irracional.

## i. **FALSO**

**Justificativa:** Racionalidade é maximizar o resultado esperado, não garantir vitória. No pôquer há cartas ocultas e sorte.

**Exemplo ou contraexemplo:** O agente aposta com um par de ases, certo pelas probabilidades, mas o adversário completa uma trinca e ganha.
