# Análise de Dados de Clientes de um Shopping Center

## Descrição do Projeto
Este projeto realiza uma análise exploratória dos dados de clientes de um shopping center. O objetivo é compreender o perfil dos clientes, seus hábitos de consumo e identificar possíveis relações entre as variáveis disponíveis, como idade, renda anual e pontuação de gastos.

## Conjunto de Dados
O conjunto de dados utilizado neste projeto é o `Mall_Customers.csv`, que contém as seguintes informações:
* `CustomerID`: ID único do cliente
* `Gender` (Gênero): Gênero do cliente (Masculino/Feminino)
* `Age` (Idade): Idade do cliente
* `Annual Income (k$)` (Renda Anual): Renda anual do cliente em milhares de dólares
* `Spending Score (1-100)` (Pontuação de Gastos): Pontuação atribuída pelo shopping com base no comportamento do cliente e na natureza dos gastos

## Análise e Etapas
1.  **Exploração dos dados:** Verificação de tipos de dados, valores nulos e estatísticas descritivas.
2.  **Limpeza e Preparação:** A coluna `CustomerID` foi removida por não ser relevante para a análise. As colunas foram renomeadas para facilitar a manipulação.
3.  **Visualização:** Foram criados gráficos, como barras, para visualizar a distribuição de variáveis como a Renda Anual por Gênero.

## Tecnologias Utilizadas
* **Python**
* **Bibliotecas:**
    * `pandas` - Para manipulação e análise dos dados.
    * `matplotlib.pyplot` - Para a criação de gráficos e visualizações.
    * `seaborn` - Para aprimorar a estética dos gráficos.
    * `scipy` - Para análises estatísticas.
