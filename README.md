# Dados-e-power-query


Etapa de Extração e Limpeza (Power Query)
Nesta fase, o foco é o "antes e depois" dos dados brutos.
O que mostrar: Print da tela do Editor do Power Query.
Ações principais:
Tipagem de Dados: Alterar colunas de texto para decimal ou data.
Remoção de Nulos: Filtrar linhas vazias ou substituir valores.
Divisão de Colunas: Separar endereços ou nomes compostos.
Legenda no Relatório: "Conexão com a fonte de dados e aplicação de tipagem correta para evitar erros de cálculo." 

2. Etapa de Transformação (Modelagem)
Aqui você demonstra como os dados se conversam.
O que mostrar: Print da aba Exibição de Modelo (o diagrama de relações).
Ações principais:
Criar relacionamentos (1:N) entre tabelas Dimensão e Fato.
Ocultar colunas desnecessárias para o usuário final.
Legenda no Relatório: "Estruturação do esquema Estrela (Star Schema) para otimizar a performance das consultas." 

3. Etapa de Enriquecimento (Cálculos DAX)
Onde a inteligência do negócio acontece.
O que mostrar: A barra de fórmulas com uma medida complexa selecionada.
Exemplos de DAX para incluir:
Total Vendas = SUM(Vendas[Valor])
Vendas Ano Anterior = CALCULATE([Total Vendas], SAMEPERIODLASTYEAR('Calendário'[Data]))
Legenda no Relatório: "Criação de medidas expressivas para análise de tendências e comparativos temporais." 

4. Etapa de Visualização (Dashboard Final)
O resultado consolidado.
O que mostrar: O dashboard pronto com filtros (Slicers) e gráficos interativos.
Destaque: Gráficos de barras, cartões com indicadores (KPIs) e uma matriz detalhada.
Legenda no Relatório: "Interface final para tomada de decisão, permitindo drill-down e filtros dinâmicos
