# Análise Exploratória de Dados - Dataset Tips

Este repositório contém exercícios de **Análise Exploratória de Dados (EDA)** usando o dataset `tips` do Seaborn. O objetivo é praticar estatísticas descritivas, visualizações gráficas e análise de padrões de gorjetas e contas em restaurantes.

## Tecnologias utilizadas

- Python 3.x
- pandas
- seaborn
- matplotlib

## Conteúdo do repositório

O repositório inclui 10 exercícios completos:

1. **Carregamento do dataset e exploração inicial**
   - Exibir as 5 primeiras linhas
   - Informações das colunas com `.info()`
   - Estatísticas básicas com `.describe()`

2. **Análise de total_bill e tip**
   - Valor médio e máximo de `total_bill`
   - Mediana de `tip`
   - Contagem de registros por dia da semana

3. **Histogramas e Boxplots**
   - Histograma da coluna `tip` com 15 intervalos
   - Boxplot de `total_bill` por sexo do cliente
   - Interpretação visual dos gráficos

4. **Gráfico de dispersão**
   - Scatterplot entre `total_bill` e `tip`
   - Diferenciação por cor (`sex`) ou tamanho (`size`)
   - Identificação de relação linear aparente

5. **Média de gorjetas por dia**
   - Cálculo da média de `tip` por dia da semana
   - Gráfico de barras comparativo
   - Identificação do dia com maior média de gorjetas

6. **Outliers em total_bill**
   - Boxplot para identificar possíveis outliers
   - Filtragem e exibição de registros com `total_bill > 50`

7. **Matriz de correlação**
   - Correlação entre `total_bill`, `tip` e `size`
   - Visualização com heatmap
   - Interpretação das variáveis mais relacionadas

8. **Análise por sexo e fumante**
   - Média de `tip` por `sex` e `smoker` com `groupby`
   - Gráfico de barras comparando homens e mulheres, fumantes e não fumantes

9. **Histograma sobreposto**
   - Comparação de `total_bill` entre clientes fumantes e não fumantes
   - Cores diferentes para cada grupo
   - Interpretação da distribuição das contas

10. **Percentual da gorjeta**
    - Criação da coluna `percent_tip = tip / total_bill * 100`
    - Estatísticas descritivas da nova coluna
    - Scatterplot entre `percent_tip` e `size`
    - Interpretação se grupos maiores dão proporcionalmente mais ou menos gorjeta

