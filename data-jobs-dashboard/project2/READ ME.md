# Dashboard de Mercado de Dados 2.0 (Power BI)

![Darshboard completo](/data-jobs-dashboard/images/Projeto%20Power%20BI%20-%20versão%2002.jpg)

## Introdução

Este projeto apresenta a segunda versão do dashboard de análise do mercado de trabalho na área de dados, desenvolvido em Power BI a partir de um dataset real de vagas publicadas em 2024.

O objetivo desta versão foi aprofundar a análise e aprimorar a estrutura do relatório, aplicando conceitos mais avançados de modelagem de dados, DAX e interatividade.

Diferente da primeira versão, este dashboard foi organizado em uma única página, reunindo os principais indicadores do mercado de dados em um único painel, permitindo uma análise rápida sobre salários, vagas, empresas contratantes e habilidades mais demandadas.

O projeto foi desenvolvido acompanhando as orientações do curso prático de Power BI ministrado por Luke Barousse, mas também inclui visualizações e análises adicionais que considerei relevantes para enriquecer o dashboard.

## Habilidades técnicas aplicadas

### ETL e Transformação de Dados (Power Query)

O Power Query foi utilizado para preparar e transformar os dados antes da modelagem.

Entre as transformações aplicadas estão:

* criação de colunas personalizadas.
* uso de colunas condicionais.
* substituição de valores.
* criação de colunas a partir de exemplos.
* limpeza de dados e remoção de espaços ou valores inconsistentes.

Também foi criada uma nova tabela baseada em outra, separando informações que estavam em uma única coluna com múltiplos valores, utilizando a opção dividir coluna por delimitador em linhas.

Esse processo permitiu estruturar melhor os dados para análise das habilidades exigidas nas vagas.

### Modelagem de Dados e Relacionamentos

Neste projeto foi desenvolvido um modelo de dados relacional, conectando diferentes tabelas do dataset para permitir análises mais completas.

Foram aplicados conceitos importantes como:

* Relacionamentos entre tabelas.
* Organização do modelo seguindo princípios de Star Schema.

Essa estrutura melhora a performance do relatório e permite que filtros e análises funcionem corretamente entre as diferentes tabelas.

### Cálculos e Métricas com DAX

O projeto utiliza diversas medidas explícitas em DAX para calcular indicadores relevantes.

Entre os principais conceitos aplicados estão:

* criação de medidas explícitas.
* organização das medidas em uma tabela de medidas.
* uso de funções estatísticas, como MEDIAN.
* funções matemáticas como DIVIDE.
* funções de filtro como CALCULATE.

Também foi utilizada a função ALLSELECTED, permitindo calcular percentuais que respeitam os filtros aplicados pelo usuário, mas ignoram filtros internos do visual.

Essas técnicas permitem criar análises mais robustas e dinâmicas dentro do relatório.

### Parâmetros e Interatividade

O projeto também explora o uso de parâmetros no Power BI, permitindo que o usuário altere o comportamento de visualizações. Foi utilizado o parâmetro de campos, que permite alternar dinamicamente entre diferentes métricas no gráfico, como:

* contagem de vagas
* salário anual mediano
* salário mediano por hora

Isso permite que o usuário explore diferentes perspectivas no mesmo visual.

### Escolha Estratégica de Visuais

Neste dashboard, diferentes tipos de visualização foram utilizados para destacar aspectos específicos dos dados:

* Cards: exibição rápida dos principais indicadores (número de vagas, salário mediano e habilidades por vaga).

* Gráficos de Barras: comparação entre cargos, empresas e habilidades mais demandadas.

* Gráfico de Linha: análise da evolução das vagas ao longo do tempo.

* Gráficos de Rosca: comparação de percentuais, como vagas com trabalho remoto ou exigência de diploma.

### Visão Geral do Dashboard

Nesta versão, o dashboard foi estruturado em uma única página, funcionando como um painel de controle do mercado de dados.

Entre os principais indicadores apresentados estão:

Job Count: número total de vagas analisadas

Skills Per Job: média de habilidades exigidas por vaga

Median Hourly Salary: salário mediano por hora

Median Yearly Salary: salário mediano anual

O relatório também permite explorar:

* empresas que mais publicam vagas.
* evolução das vagas ao longo do tempo.
* habilidades mais demandadas no mercado.
* comparação de salários entre cargos.
* distribuição de vagas com trabalho remoto.
* vagas que exigem ou não diploma.

Essa estrutura permite que o usuário tenha uma visão rápida e interativa do mercado de dados, explorando diferentes aspectos das oportunidades disponíveis.

## Conclusão

Esta segunda versão do dashboard demonstra como técnicas de ETL, modelagem de dados, DAX e visualização em Power BI podem transformar grandes volumes de dados em uma ferramenta útil para análise do mercado de trabalho.

Ao consolidar as principais informações em um painel interativo, o dashboard permite explorar rapidamente tendências de contratação, salários e habilidades mais valorizadas na área de dados.

Além de aplicar conceitos técnicos, o projeto também reforça a importância de estruturar dashboards pensando na experiência do usuário e na clareza da informação, transformando dados complexos em insights acessíveis.