# 🎮 Xbox Game Pass Subscriptions Sales Dashboard

Projeto desenvolvido em Excel para análise de vendas de assinaturas Xbox.

## Objetivo

Analisar as vendas das assinaturas:
- EA Play Season Pass
- Minecraft Play Season Pass

O dashboard apresenta:

- Valor total de vendas por produto, assinaturas mensais, trimestrais e anuais
- Mês com maior volume de vendas
- Mês com menor volume de vendas
- Gráfico comparativo, assianturas que são autorenováveis ou não
- Data e hora do Update de dados

---

## Estrutura do Projeto


---

## 🗂️ Estrutura da Base de Dados

A planilha de base para os cálculos dos resultados exibidos no dasboard contém:

| Coluna | Descrição |
|--------|------------|
| Data | Data da venda |
| Mês | Mês da venda |
| Produto | Tipo de assinatura |
| Valor Venda | Valor pago |

---

## Métricas Calculadas

###  Total por Produto
Utilizando a função `SOMASE`.

###  Total por Mês
Calculado por meio de Tabela Dinâmica.

###  Mês com Maior Venda
Utilizando as funções:
- `MÁXIMO`
- `CORRESP`
- `ÍNDICE`

###  Mês com Menor Venda
Utilizando as funções:
- `MÍNIMO`
- `CORRESP`
- `ÍNDICE`

---

##  Como Reproduzir

1. Baixe o arquivo `Planilha de Vendas.xlsx`
2. Abra no Excel
3. Interaja com o gráfico e as informações do topo utilizando os botões de Subscription Type na lateral esquerda do dashboard, selecionando qual tipo de assinatura do Xbox deseja visualizar as vendas, Annual, Monthly ou Quartely (anual, mensal ou trimestral).

---

##  Tecnologias Utilizadas

- Microsoft Excel
- Tabelas Dinâmicas
- Funções condicionais
- Fórmulas estatísticas

---

##  Resultado

O dashboard permite visualizar rapidamente:

- Valor total de inscrições por tipo de assinatura e duração da assinatura, sendo, EA Play Season Pass ou Minecraft Play Season Pass.
- Gráfico com informação se as assinaturas serão autorenováveis ou não
- Mês de melhor desempenho de vendas da Xbox
- Mês de pior desempenho de vendas da Xbox

---

##  Autora

Camila Ferreira da Silva Cavalcante
