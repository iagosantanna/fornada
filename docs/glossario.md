# Glossário — Confeitaria Três Fornos

A ponte entre como a Dona Célia fala e como o código fala.
Se ela diz uma palavra e o código diz outra, este arquivo é onde a gente combina que é a mesma coisa — e exatamente qual coisa.

**Regra de entrada:** a palavra passa se responder "sim" para pelo menos duas destas:
1. A Dona Célia usa no dia a dia da confeitaria?
2. Tem um significado específico aqui que alguém de fora entenderia errado?
3. Vai aparecer no código, como classe, campo ou status?

**Convenção de nomes no código:** entidades em `PascalCase` (Order), campos e estados em `snake_case` (lead_time, confirmed).

---

## Coisas (viram classes/tabelas)

| Termo do negócio | O que significa na Três Fornos | Nome no código |
| --- | --- | --- |
| Encomenda | Pedido feito com antecedência para retirar ou receber em data marcada | `Order` |
| Item da encomenda | Cada produto dentro da encomenda, com quantidade e personalização | `OrderItem` |

## Valores e medidas (viram campos)

| Termo do negócio | O que significa na Três Fornos | Nome no código |
| --- | --- | --- |
| Sinal | Valor pago adiantado para confirmar a encomenda | `deposit` |
| Antecedência | Tempo mínimo entre fazer a encomenda e a data de retirada | `lead_time` |
| Capacidade diária | Quanto a confeitaria consegue produzir em um dia | `daily_capacity` |
| Personalização | Pedido especial no produto: texto no bolo, tema, sabor fora do cardápio | `customization` |

## Formas de entrega

| Termo do negócio | O que significa na Três Fornos | Nome no código |
| --- | --- | --- |
| Retirada / entrega | O cliente busca na loja / a loja leva até o cliente | `pickup` / `delivery` |

## Estados (momentos do ciclo de vida)

| Termo do negócio | O que significa na Três Fornos | Nome no código |
| --- | --- | --- |
| Desistência | Cliente cancela ou não aparece para retirar, depois que a confeitaria já aceitou o pedido. É diferente de um pedido que a própria confeitaria recusou. "(a confirmar: se conta como desistência quando o sinal já foi pago ou só quando não houve sinal)" | `canceled_by_customer` (status de `Order`) |

## Pessoas e papéis (quem faz o quê)

_(em aberto — hipótese H2 do briefing: quem além da Dona Célia opera o sistema)_

## Eventos (coisas que acontecem e mudam a situação)

| Termo do negócio | O que significa na Três Fornos | Nome no código |
| --- | --- | --- |
| Aceite do pedido | Momento em que a Dona Célia decide que a confeitaria dá conta de fazer aquela encomenda naquele dia. Só a partir do aceite o pedido vira compromisso e entra na produção. "(a confirmar: se o aceite depende do sinal pago ou são duas etapas separadas)" | `accepted` (status de `Order`) / evento `OrderAccepted` |

---

## Dúvidas abertas (candidatas a `entrevista-01.md`)

- A desistência conta quando o sinal já foi pago? E quando o cliente só some sem avisar?
- O aceite vem antes ou depois do sinal? Ou são a mesma coisa na cabeça da Dona Célia?
- Existe um limite claro de "não dá mais" ou é sempre no feeling? (liga com a Capacidade diária)
- Personalização é sempre cobrada à parte ou depende do caso?

## Como este arquivo conversa com os outros

- Cada "(a confirmar)" aqui é uma pergunta marcada para a entrevista com a Dona Célia.
- Cada termo aqui deve aparecer no `briefing.md` pelo menos uma vez, para a gente não inventar palavra nova sem necessidade.
- Termo que sai do código sai daqui também.