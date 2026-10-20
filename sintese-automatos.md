# Síntese com autômatos

**Caso:** 5. Praticar tênis contra uma parede (robô treinador).

**Estados:** Aguardando, Posicionando, Golpeando.

**Percepções:** p1 = bola se aproximando; p2 = bola ao alcance; p3 = bola parada/perdida.

**Ações:** a1 = mover-se; a2 = rebater; a3 = recolher a bola.

**Regras (estado atual + percepção → próximo estado e ação):**

1. (Aguardando, p1) → (Posicionando, a1)
2. (Posicionando, p2) → (Golpeando, a2)

Depois do golpe o robô volta ao estado Aguardando; se perceber p3, usa a3 para recolher a bola.

**Como o estado guarda o passado:** O estado guarda em que etapa do ciclo o robô está, ou seja, o que já aconteceu (ele já se posicionou, agora vai rebater).

**Limitação:** Com poucos estados, o robô não lembra velocidade nem efeito das bolas anteriores.
