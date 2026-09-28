# Fornada

**Autor:** Iago Sant'anna

Sistema de encomendas para confeitarias artesanais, feito com Python e Django.

> Projeto de portfólio guiado por IA em formato de estágio simulado: a Fornada e a cliente
> Confeitaria Três Fornos são fictícias; o processo, as decisões e o código são reais.

**Status:** Fase 0 — onboarding

**Stack:** Python · pytest · Django

## Contexto

A **Confeitaria Três Fornos** é um negócio familiar comandado pela Dona Célia. A operação hoje é simples na essência, mas depende inteiramente de memória e de um caderno: os pedidos chegam por telefone e WhatsApp, são anotados à mão e repassados para a produção de forma verbal.

Estrutura conhecida do negócio:

- **~150 encomendas por mês**
- **3 fornos** e **4 pessoas na produção**
- **Picos de demanda** às sextas, sábados e datas comemorativas
- Atendimento por **telefone e WhatsApp**, sem sistema de registro
- Controle de caixa **informal**

Dona Célia tem pouco contato com sistemas e vai ser a principal usuária da solução. O piloto foi desenhado para **3 meses**, com o objetivo de acompanhar cerca de **450 encomendas** e medir a redução de erros, esquecimentos e tempo gasto para registrar um pedido.

## O problema

Sem um sistema de registro, a Três Fornos perde dinheiro e qualidade em quatro frentes principais:

- **Erros de anotação** — cerca de **1 em cada 20 pedidos** sai errado (sabor, data, texto do bolo), gerando bolo refeito, retrabalho e cliente insatisfeito.
- **Desistência sem sinal** — clientes cancelam depois do bolo pronto, e a confeitaria arca com ingredientes, tempo e horas de trabalho perdidas.
- **Sobrecarga da produção** — a loja aceita mais encomendas do que consegue entregar em um mesmo dia, causando atrasos, hora extra e queda na qualidade.
- **Falta de controle financeiro** — ninguém sabe com clareza quanto faturou no mês nem quais produtos dão mais lucro. Preço e cardápio acabam decididos no escuro.

Além disso, toda a informação depende do caderno e da memória da Dona Célia. Se ela não estiver presente, o pedido se perde. Não há histórico confiável para medir cancelamentos, perdas ou clientes que furam — o que impede qualquer decisão baseada em dados.

O projeto nasce para tirar as encomendas do caderno, centralizar as informações e dar à Dona Célia visibilidade sobre o que entra, o que sai e o que dá lucro.

## Regras de negócio

As regras ficam em [docs/regras-de-negocio.md](docs/regras-de-negocio.md).

## Solução

_Em construção — a partir da Fase 1._

## Decisões técnicas

Registradas em [docs/decisoes/](docs/decisoes/).

## Como rodar

### 1. Pré-requisitos

Python 3.14 e Git.

### 2. Clone o repositório

```bash
git clone https://github.com/iagosantanna/fornada.git
cd fornada
```

### 3. Crie o ambiente virtual

```bash
python -m venv .venv
```

No Linux, se o comando `python` não existir, use `python3`.

### 4. Ative o ambiente virtual

No Windows, pelo Git Bash:

```bash
source .venv/Scripts/activate
```

No Windows, pelo PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

No Linux:

```bash
source .venv/bin/activate
```

### 5. Instale as dependências

```bash
pip install -r requirements.txt
```

### 6. Rode os testes

```bash
pytest
```

Por enquanto o resultado esperado é `no tests ran`, porque os testes chegam na Fase 1.

## Aprendizados

_Atualizado a cada sprint review._