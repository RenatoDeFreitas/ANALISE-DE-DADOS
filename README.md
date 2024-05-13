### Objetivo deste repositório

Aprender Power BI é fundamental para qualquer profissional que lida com análise de dados. Ele permite a criação de visualizações interativas e painéis informativos que ajudam na tomada de decisões baseadas em dados. O objetivo é dominar todas as etapas do processo, desde a coleta e limpeza dos dados até a apresentação de insights por meio de dashboards dinâmicos e informativos.

### Roadmap de Estudos em Power BI

| Nome da Etapa                   | Descrição e Importância                               | Exemplo de Utilização em DAX                        |
|--------------------------------|-------------------------------------------------------|-----------------------------------------------------|
| Coleta de Dados                 | Processo de coletar dados de diversas fontes         | `SELECT * FROM tabela;`                             |
| Limpeza e Transformação        | Limpeza dos dados e transformação para análise        | `FILTER(tabela, coluna > 0);`                        |
| Modelagem de Dados              | Estruturação e relacionamento dos dados               | `CALCULATE(SUM(tabela[valor]), FILTER(tabela, coluna = "X"));` |
| Criação de Medidas e Métricas  | Definição de métricas e cálculos personalizados       | `VAR media = AVERAGE(tabela[coluna]);`               |
| Visualização de Dados          | Criação de gráficos e painéis de visualização         | `BAR CHART: SUMMARIZECOLUMNS(tabela[categoria], "Vendas", SUM(tabela[vendas]));` |
| Criação de Dashboards          | Composição de dashboards para análise e apresentação  | `PIE CHART: SUMMARIZE(tabela, tabela[categoria], "Vendas", SUM(tabela[vendas]));` |


