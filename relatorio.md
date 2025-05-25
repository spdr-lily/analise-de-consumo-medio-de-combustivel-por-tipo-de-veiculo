## **Relatório do Projeto: Análise do Consumo Médio de Combustível por Tipo de Veículo**

### **1\. Introdução**

Este projeto tem como objetivo analisar e visualizar o consumo médio de combustível por tipo de veículo. Através da utilização de dados e bibliotecas de visualização, busca-se fornecer insights claros e concisos sobre o desempenho de diferentes categorias de veículos em relação ao consumo de combustível.

### **2\. Metodologia**

A metodologia adotada no projeto envolve as seguintes etapas:

1. **Coleta e Armazenamento de Dados:**

   * Os dados de consumo de combustível são armazenados em um DataFrame do Pandas.  
   * Os dados são inseridos diretamente no código através de um dicionário Python, contendo os tipos de veículos e seus respectivos consumos.  
2. **Processamento e Análise dos Dados:**

   * A biblioteca Pandas é utilizada para criar e manipular o DataFrame.  
   * O consumo médio de combustível é calculado por tipo de veículo utilizando a função `groupby()` e `mean()`.  
3. **Visualização dos Dados:**

   * A biblioteca Matplotlib é empregada para gerar um gráfico de barras, facilitando a comparação visual do consumo médio entre os diferentes tipos de veículos.

### **3\. Detalhamento das Etapas**

#### **3.1. Coleta e Armazenamento de Dados**

Os dados de consumo de combustível são organizados em um dicionário Python e, em seguida, convertidos em um DataFrame do Pandas. O DataFrame é estruturado com duas colunas: `tipo_veiculo` e `consumo`.

#### **3.2. Processamento e Análise dos Dados**

Para calcular o consumo médio por tipo de veículo, utiliza-se o método `groupby()` do Pandas para agrupar os dados pela coluna `tipo_veiculo` e, em seguida, calcula-se a média da coluna `consumo` com o método `mean()`.

#### **3.3. Visualização dos Dados**

Um gráfico de barras é gerado para comparar o consumo médio de combustível entre os tipos de veículos. O eixo x representa os tipos de veículos, e o eixo y representa o consumo médio em km/l.

### **4\. Resultados**

O gráfico de barras resultante apresenta de forma clara o consumo médio de combustível para cada tipo de veículo, permitindo uma análise comparativa visual rápida e eficaz.

### **5\. Conclusão**

Este projeto demonstrou a eficácia da utilização das bibliotecas Pandas e Matplotlib para análise e visualização de dados. A metodologia aplicada permitiu calcular e apresentar de forma clara o consumo médio de combustível por tipo de veículo, facilitando a compreensão das diferenças de desempenho entre eles.
