# Dashboard de Mercado de Dados (Power BI)
![Página 1 do Dashboard](/Projeto%20Dashboards/Imagens/Projeto%20Power%20BI%20-%20p.1.jpg)

## Introdução
Este projeto apresenta um dashboard desenvolvido em Power BI para analisar o mercado global de vagas na área de dados em 2024, explorando informações como cargos, salários e distribuição geográfica das oportunidades.

O objetivo é transformar dados de vagas em visualizações que permitam compreender tendências do mercado e apoiar profissionais interessados em ingressar ou evoluir na área de dados.

Este projeto foi desenvolvido como parte do curso prático de Power BI ministrado por Luke Barousse.

## Habilidades técnicas aplicadas

### Planejamento do projeto
Antes de abrir o Power BI, o projeto foi guiado por duas perguntas fundamentais:
* **Que problema estamos tentando resolver?** A dificuldade de encontrar informações consolidadas sobre salários e tendências no mercado de dados.
* **Quem são os stakeholders?** Candidatos que precisam decidir onde focar seus estudos e buscas.

### Escolha Estratégica de Visuais
Neste projeto, cada vizualização foi escolhida com um propósito específico:
* **Cartões:** Exibição direta dos números principais para resposta rápida.
* **Gráfico de Linhas:** O melhor visual para análise de tempo, permitindo enxergar se as vagas estão aumentando ou diminuindo mês a mês.
* **Gráfico de Barras (Horizontal):** Ideal para comparação entre categorias com nomes longos, onde a leitura na horizontal evita que o texto fique cortado.
* **Gráfico de Dispersão (Scatter Plot):** Cruzamento do salário por hora com o salário mensal para encontrar valores atípicos (outliers), correlações e exibir uma linha de tendência.
* **Matriz:** Organização de dados relevantes, com ajuste de unidades (exibição em milhares) para facilitar a leitura. Na matriz, também foram aplicadas formatações condicionais e
mini gráficos.
* **Indicador:** Para apresentar a mediana do salário e compará-la com o salário mínimo, máximo e médio, de forma objetiva.
* **Gráfico de Rosca:** Uma versão moderna para exibir percentuais em relação ao total, sem muitas divisões, com a diferença entre as partes clara.
* **Treemap:** Ideal para mostrar o tipo de trabalho que "domina" o mercado.

### Experiência do Usuário
O relatório não é estático, ele foi desenhado para ser explorado:
* **Segmentação de Dados:** Filtros interativos para escolher cargos ou níveis de experiência.
* Botões e Marcadores (Bookmarks):** Menu de navegação fluido entre as páginas.
* **Drill-Through:** Você pode clicar em um cargo específico na página geral e "mergulhar" em uma página de detalhes exclusiva daquela função.
* **Painel de Seleção:** Organização interna para garantir que cada elemento visual apareça no momento certo.

## Visão Geral do Dashboard

### 1ª Página: Panorama Geral do Mercado

![Página 1 do Dashboard](/Projeto%20Dashboards/Imagens/Projeto%20Power%20BI%20-%20p.1.jpg)

Esta é a central de controle do mercado de dados. Apresenta KPIs importantes como contagem total de vagas, salários medianos e cargos mais comuns, oferecendo uma visão rápida do que está acontecendo no mercado de trabalho.

### 2ª Página: Detalhes por Cargo (Drill-Through)

![Página 2 do Dashboard](/Projeto%20Dashboards/Imagens/Projeto%20Power%20BI%20-%20p.2.jpg)

Esta é a página de análise profunda. Utilizando a funcionalidade de Drill-Through, o usuário sai do resumo e mergulha em detalhes específicos de um cargo, incluindo informações como a análise geoespacial indicando onde estão as melhores oportunidades e quais plataformas dominam as contratações em cada categoria.

## Conclusão
Este projeto demonstra como dados brutos podem ser transformados em informações claras e úteis quando organizados com uma abordagem de Business Intelligence. Mais do que construir visualizações, o processo envolveu compreender qual pergunta precisava ser respondida e quem seria o usuário final do dashboard.

Definir o problema e entender as necessidades do usuário foi fundamental para orientar todas as decisões do projeto, desde a estrutura do relatório até a forma de apresentar os insights. Esse direcionamento permitiu criar um dashboard que facilita a exploração das informações e torna a análise do mercado de trabalho em dados mais acessível.

Como resultado, o projeto evidencia a importância de unir análise de dados, pensamento crítico e foco no usuário para transformar dados em suporte real para a tomada de decisões.