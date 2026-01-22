# Análise de Desempenho Acadêmico de Estudantes

## Visão Geral do Projeto

Este projeto é uma análise exploratória de dados (EDA) focada em identificar os principais fatores que influenciam o desempenho acadêmico de estudantes, com o objetivo de propor soluções para melhorar os resultados educacionais. Utilizando um dataset abrangente de fatores de desempenho estudantil, o projeto demonstra habilidades em manipulação de dados, análise estatística e visualização, culminando em recomendações práticas.

## O Problema

O desafio central era investigar a existência de um desempenho acadêmico abaixo do esperado em um grupo de estudantes e, a partir daí, descobrir as causas raiz desse problema. A análise buscou responder a perguntas como: "Qual a quantidade de alunos com desempenho ruim?", "O que está por trás desse baixo desempenho?" e "O que pode ser feito para reverter a situação?".

## A Solução

A solução envolveu um processo de análise de dados estruturado:

1.  **Extração e Limpeza de Dados**: Carregamento do dataset de desempenho de estudantes e pré-processamento para lidar com valores nulos e garantir tipos de dados corretos.
2.  **Análise Exploratória (EDA)**: Investigação das relações entre diversas variáveis (como horas estudadas, envolvimento parental, acesso a recursos, motivação, frequência, etc.) e o desempenho nos exames.
3.  **Identificação de Fatores Chave**: Utilização de estatísticas descritivas, agrupamentos e visualizações para pinpointar os fatores com maior impacto no desempenho acadêmico.
4.  **Proposição de Recomendações**: Com base nas descobertas, foram formuladas recomendações direcionadas para escolas e pais, visando a melhoria do desempenho geral dos alunos.

## Insights e Resultados Principais

A análise revelou que o desempenho médio dos alunos estava abaixo do ideal. Os fatores mais críticos identificados foram:

*   **Frequência Escolar (Attendance)**: Apresentou a **correlação positiva mais forte (0.58)** com as notas dos exames, indicando que a presença regular é fundamental.
*   **Envolvimento Parental (Parental_Involvement)**: Níveis mais altos de envolvimento parental foram associados a um desempenho significativamente melhor.
*   **Horas de Estudo (Hours_Studied)**: Uma correlação positiva moderada (0.45) foi observada, reforçando a importância do tempo dedicado ao estudo.
*   **Acesso a Recursos (Access_to_Resources)**: Alunos com acesso 'High' a recursos educacionais tendem a ter melhores resultados.

## Recomendações Finais

Para otimizar o desempenho acadêmico, as escolas devem priorizar:

*   **Programas de Incentivo à Frequência**: Estratégias para garantir a assiduidade dos alunos.
*   **Fortalecimento do Envolvimento Parental**: Iniciar programas que capacitem os pais a apoiar ativamente a educação.
*   **Orientação sobre Hábitos de Estudo**: Oferecer suporte para o desenvolvimento de rotinas e métodos de estudo eficazes.
*   **Garantia de Acesso a Recursos**: Assegurar acesso equitativo a materiais e tecnologia.

## Visão Geral do Código

O notebook `[Nome_do_Seu_Notebook].ipynb` (sugiro renomeá-lo para algo como `student_performance_analysis.ipynb`) demonstra as seguintes habilidades:

*   **Manipulação de Dados com Pandas**: Uso eficiente de `pandas` para carregamento (`pd.read_csv`), limpeza (`isna().sum()`, `dropna()`, `astype()`), seleção (`loc`), agregação (`groupby().agg()`) e criação de novas colunas (`apply()`).
*   **Visualização de Dados com Plotly Express**: Criação de gráficos interativos (`px.histogram`, `px.scatter`) para explorar relações entre variáveis e apresentar insights de forma clara.
*   **Análise Estatística**: Cálculo de desvio padrão (`std()`), média (`mean()`), mediana (`median()`), e correlação (`corr()`) para entender a distribuição e as relações dos dados.
*   **Organização e Boas Práticas**: O notebook está estruturado em sessões lógicas (`# Importar bibliotecas`, `# Tratamento de dados`, `# Análise de Fatores Categóricos`, etc.) com comentários claros, facilitando a compreensão do fluxo da análise.

Este projeto reflete minha capacidade de transformar dados brutos em insights acionáveis, utilizando ferramentas e técnicas de Data Science para resolver problemas do mundo real.

## Como Executar

1.  Clone este repositório.
2.  Certifique-se de ter as bibliotecas `pandas` e `plotly-express` instaladas (`pip install pandas plotly-express`).
3.  Abra o arquivo `.ipynb` em um ambiente como Jupyter Notebook ou Google Colab.
4.  Execute as células sequencialmente para reproduzir a análise.
