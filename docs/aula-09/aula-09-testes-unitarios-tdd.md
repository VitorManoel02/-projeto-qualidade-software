# 🔹 1. Funcionalidades escolhidas

## 👤 Integrante – Vitor Manoel

Durante a atividade foram desenvolvidas e testadas três funcionalidades do sistema LocalEats.

---

### Funcionalidade 1 – Cálculo do total do pedido com valor mínimo

#### Arquivo da implementação

`/src/aula-09/pages/pedido.py`

#### Arquivo de testes

`/src/aula-09/tests/test_pedido.py`

#### Descrição

Responsável por calcular o valor total do pedido e verificar se o valor mínimo exigido foi atingido.

#### Regras de negócio

* O total deve ser a soma dos itens
* O pedido precisa atingir o valor mínimo
* Caso contrário, deve gerar erro

---

### Funcionalidade 2 – Aplicação de desconto percentual

#### Arquivo da implementação

`/src/aula-09/pages/desconto.py`

#### Arquivo de testes

`/src/aula-09/tests/test_desconto.py`

#### Descrição

Aplica um desconto percentual sobre o valor do pedido.

#### Regras de negócio

* O percentual deve estar entre 0% e 100%
* O valor final não pode ser negativo

---

### Funcionalidade 3 – Cálculo da taxa de entrega

#### Arquivo da implementação

`/src/aula-09/pages/entrega.py`

#### Arquivo de testes

`/src/aula-09/tests/test_entrega.py`

#### Descrição

Calcula a taxa de entrega conforme a distância.

#### Regras de negócio

* Até 3km → taxa fixa
* Acima de 3km → taxa adicional
* Distância negativa → erro
