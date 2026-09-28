# Entrevista — Dona Célia

**Contexto:** conversa inicial para levantar requisitos do sistema de pedidos da Confeitaria Três Fornos.
**Como usar:** perguntar uma de cada vez, com calma, deixando ela contar histórias. As hipóteses do `briefing.md` estão linkadas para orientar a escuta, não precisam ser lidas para ela.

---

## Pergunta 01

**Pergunta:**
Dona Célia, me conta como é hoje quando alguém liga ou manda mensagem pedindo um bolo. O que a senhora faz desde o começo do pedido até a entrega? Quem anota, onde anota e como avisa quem vai fazer?

**O que queremos descobrir:**
O passo a passo real do processo, quem participa e onde as informações circulam (ou se perdem).

**Hipóteses linkadas:**
- **H2** — Quem mais opera o sistema além dela? (a resposta aparece aqui: quem anota, quem repassa para a produção)
- **H10** — O sistema vai se integrar ao WhatsApp ou o registro será manual? (saber se o WhatsApp hoje é canal único ou divide espaço com telefone e balcão)
- **H1** (parcial) — Observar como ela lida com o aparelho durante a conversa ajuda a testar a hipótese de design sobre celular vs. computador.

**Sinais de alerta para anotar:**
- Se ela diz "eu anoto tudo de cabeça" em algum momento.
- Se o repasse para a produção é sempre verbal.
- Se existe mais de um caderno ou mais de um lugar de anotação.

---

## Pergunta 02

**Pergunta:**
Num dia comum, quantas encomendas a senhora recebe? Como a senhora percebe se dá conta de fazer todas ou se precisa dizer não para alguma?

**O que queremos descobrir:**
O volume real por dia, os picos (sexta, sábado, datas comemorativas) e o critério que ela usa para aceitar ou recusar um pedido.

**Hipóteses linkadas:**
- **H3** — O volume mensal já é conhecido (~150/mês). O que falta é como ele se distribui entre dias comuns, sextas, sábados e datas comemorativas.
- **H4** — Como a confeitaria decide se aceita um pedido? Existe limite por dia, por produto ou por horário, ou é sempre no feeling?

**Sinais de alerta para anotar:**
- Se o "não dá mais" tem um número claro (ex.: "não faço mais de 8 bolos por dia") ou se é intuição.
- Se existem produtos que sempre estouram a capacidade.
- Se as datas comemorativas mudam a regra do jogo.

---

## Pergunta 03

**Pergunta:**
A senhora costuma pedir um dinheiro adiantado, o sinal? Como o cliente paga? E quando alguém desiste ou não vem buscar, o que acontece?

**O que queremos descobrir:**
A política de sinal (se existe, quanto, quando, como) e o que acontece de fato quando o cliente desiste ou não retira.

**Hipóteses linkadas:**
- **H5** — Qual é a política de sinal? Percentual, valor fixo, forma de pagamento e momento da cobrança?
- **H6** — O que acontece quando o cliente desiste ou não retira? Cobra algo? Registra em algum lugar?

**Sinais de alerta para anotar:**
- Se o sinal é sempre pedido ou depende do cliente / do valor / do tipo de bolo.
- Se existe diferença entre "desistiu avisando" e "furou sem avisar".
- Se ela registra em algum lugar quando alguém desiste (ou se isso some).

---

## Pergunta 04

**Pergunta:**
O que a senhora precisa saber do pedido para não errar? Sabor, recheio, tamanho, data, hora, nome, recado no bolo, entrega ou retirada? Que pedidos costumam ser mais complicados?

**O que queremos descobrir:**
Quais campos são obrigatórios em todo pedido, quais são exceção e onde estão os erros mais comuns (os 1 em cada 20).

**Hipóteses linkadas:**
- **H7** — Quais informações são obrigatórias em todo pedido e quais são exceções?
- **H11** (parcial) — Saber se a produção precisa de detalhes de receita, insumos e custos, ou se basta a lista de pedidos.

**Sinais de alerta para anotar:**
- Se ela cita algum campo que a gente não tinha pensado (ex.: restrição alimentar, cor da cobertura, forma de pagamento).
- Se os erros acontecem mais por esquecimento de anotação ou por confusão de leitura no caderno.
- Se existe pedido "padrão" que nunca dá erro e pedido "especial" que sempre dá.

---

## Pergunta 05

**Pergunta:**
No fim do mês, o que a senhora gostaria de saber sobre a loja? Quanto entrou e quanto saiu? Quais bolos vendem mais? Quais deixam mais dinheiro? Quantos pedidos foram esquecidos ou cancelados? Como a senhora faz para saber disso hoje?

**O que queremos descobrir:**
Quais números importam para ela, com que frequência quer vê-los e como resolve isso hoje (provavelmente no escuro).

**Hipóteses linkadas:**
- **H8** — Quais relatórios são realmente úteis para Dona Célia e com que frequência ela quer vê-los?

**Sinais de alerta para anotar:**
- Se ela fala de "sentimento" em vez de número (ex.: "acho que chocolate vende mais").
- Se ela nunca pensou em lucro por produto, só em faturamento total.
- Se ela quer ver isso no celular, no papel ou não quer ver (delegar).

---

## Hipóteses ainda sem pergunta dedicada

Estas hipóteses do briefing não estão cobertas diretamente nas 5 perguntas e podem virar uma segunda rodada de entrevista:

- **H1** — Dona Célia consegue usar um sistema no celular sem ajuda frequente, ou prefere computador? (observar durante a conversa)
- **H9** — A confeitaria tem internet estável? Usa apenas celular? Há computador no balcão? (pergunta técnica, melhor confirmar com quem cuida da parte de estrutura)
- **H10** — Integração com WhatsApp vs. registro manual (retomada depois de entender melhor o processo)
- **H11** — Detalhes de receita, insumos e custos na produção (perguntar para quem produz, não para Dona Célia)

---

## Observações gerais

- Cada "a confirmar" do `briefing.md` deve ter uma resposta aqui depois da entrevista.
- Se alguma resposta contradizer um dado que já tínhamos como certo, atualizar o briefing — não a fala dela.
- Toda suposição nova que surgir na conversa entra no briefing marcada como `[a confirmar]`, não como fato.
