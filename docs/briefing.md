# Briefing — Confeitaria Três Fornos

## 1. Cliente
- **Nome:** Confeitaria Três Fornos
- **Responsável:** Dona Célia
- **Perfil:** negócio familiar, atendimento por telefone e WhatsApp, pedidos anotados em caderno.
- **Estrutura conhecida:** 3 fornos e 4 pessoas na produção.
- **Relação com tecnologia:** Dona Célia tem pouco contato com sistemas. [a confirmar: qual aparelho ela usa no dia a dia — celular ou computador]
- **Quem usa hoje:** Dona Célia e possíveis ajudantes/familiares. [a confirmar]
- **O que já existe:** caderno de anotações, conversas de WhatsApp, telefone, controle de caixa informal. [a confirmar]
- **Restrições:** internet, aparelho disponível (celular/computador), rotina da confeitaria. [a confirmar]
- **Expectativa:** organizar encomendas, reduzir esquecimentos, controlar sinal/pagamento e saber quanto entra no mês.

## 2. Processo atual: do pedido no WhatsApp até a retirada
1. **Contato do cliente:** cliente manda mensagem no WhatsApp ou liga.
2. **Anotação:** Anota no caderno nome, sabor, recheio, tamanho, data, horário, texto do bolo, valor e se pagou sinal.
3. **Confirmação:** Responde ao cliente confirmando os detalhes; às vezes há troca de mensagens até fechar.
4. **Decisão de aceite:** Avalia de cabeça se a produção consegue entregar naquele dia/horário.
5. **Sinal/pagamento:** Combina valor adiantado e forma de pagamento (Pix, dinheiro, cartão). [a confirmar]
6. **Repasse para produção:** Informa quem vai fazer o bolo, geralmente de forma verbal ou mostrando o caderno.
7. **Produção:** O bolo/encomenda é feito no dia combinado.
8. **Retirada/entrega:** Cliente busca na confeitaria ou recebe em casa. [a confirmar]
9. **Fechamento:** Pagamento final é recebido e, às vezes, anotado.
10. **Fim do dia/mês:** Dona Célia tenta somar valores e entender o que vendeu, mas sem um controle organizado.

## 3. Dores e impacto
- **Esquecimento ou erro de anotação:** cerca de 1 em cada 20 pedidos sai errado (sabor, data, texto). Isso gera bolo refeito, retrabalho e cliente insatisfeito.
- **Desistência sem sinal:** cliente cancela depois do bolo pronto. A confeitaria perde ingredientes, tempo e horas de trabalho.
- **Excesso de encomendas para o mesmo dia:** a produção não dá conta, causando atrasos, hora extra e queda na qualidade.
- **Falta de controle financeiro:** ninguém sabe com clareza quanto faturou no mês nem quais produtos dão mais lucro. Preço e cardápio acabam decididos no escuro.
- **Dependência do caderno e da memória:** se Dona Célia não estiver, a informação fica perdida ou espalhada.
- **Dificuldade de medir cancelamentos, perdas e clientes que furam:** não há histórico confiável para agir.

## 4. Objetivo do piloto
- Criar um sistema simples para registrar e acompanhar pedidos de encomenda.
- Tirar as anotações do caderno e centralizar as informações em um só lugar.
- Reduzir esquecimentos, erros de sabor/data/texto e retrabalho.
- Ajudar a controlar quantos pedidos cabem por dia, evitando sobrecarga da produção.
- Registrar sinal, pagamento, status do pedido e cancelamentos.
- Mostrar, de forma fácil, faturamento, produtos mais vendidos e pedidos por período.
- Ser usável pela Dona Célia e pela equipe, com poucos cliques e linguagem simples.
- **Meta do piloto:** testar por **3 meses**, acompanhar **cerca de 450 encomendas** (base de ~150 por mês) e medir redução de erros, esquecimentos e tempo gasto para registrar um pedido.

## 5. Hipóteses: o que ainda não sabemos

### Sobre pessoas e uso
- **H1:** Dona Célia consegue usar um sistema no celular sem ajuda frequente, ou prefere computador?
  - *Hipótese de design (a confirmar com ela):* precisa de letras grandes, poucos passos e linguagem do dia a dia.
- **H2:** Quem mais vai operar o sistema além dela? Filhos, atendentes, funcionários da produção?

### Sobre demanda e capacidade
- **H3:** O volume mensal é conhecido (~150 encomendas/mês). O que falta saber é **como ele se distribui entre os dias** — qual o pedido médio em dia comum, em sexta e sábado, e em datas comemorativas.
- **H4:** Como a confeitaria decide se aceita um pedido? Existe limite por dia, por produto ou por horário, ou é sempre no feeling?

### Sobre dinheiro
- **H5:** Qual é a política de sinal? Percentual, valor fixo, forma de pagamento e momento da cobrança?
- **H6:** O que acontece quando o cliente desiste ou não retira? Cobra algo? Registra em algum lugar?

### Sobre dados e operação
- **H7:** Quais informações são obrigatórias em todo pedido e quais são exceções?
- **H8:** Quais relatórios são realmente úteis para Dona Célia e com que frequência ela quer vê-los?
- **H9:** A confeitaria tem internet estável? Usa apenas celular? Há computador no balcão?
- **H10:** O sistema vai se integrar ao WhatsApp ou o registro será manual?
- **H11:** A produção precisa de detalhes de receita, insumos e custos, ou basta a lista de pedidos?

---

## Dados conhecidos do negócio
| Dado | Valor |
| --- | --- |
| Encomendas por mês (média) | ~150 |
| Fornos disponíveis | 3 |
| Pessoas na produção | 4 |
| Picos de demanda | Sextas, sábados e datas comemorativas |
| Duração do piloto | 3 meses |
| Volume estimado no piloto | ~450 encomendas |