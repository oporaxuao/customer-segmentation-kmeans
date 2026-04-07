Segmentação de Clientes com Clustering K-Means
Este projeto foi desenvolvido como parte do módulo de modelagem avançada do curso de Ciência de Dados da EBAC. O objetivo principal é transformar dados brutos de comportamento de consumo em inteligência estratégica, identificando perfis distintos de clientes para direcionamento de campanhas de marketing personalizadas.

📊 O Desafio
Agrupar uma base de clientes com base em suas características de renda e hábitos de gasto, permitindo que o time de negócio entenda as diferentes personas e otimize o ROI de marketing através da personalização.

🛠️ Tecnologias Utilizadas
Linguagem: Python

Bibliotecas de Manipulação: Pandas, NumPy

Visualização: Matplotlib, Seaborn

Machine Learning: Scikit-learn (K-Means)

📈 Metodologia e Resultados
1. Processamento de Dados
Realizei a limpeza e a normalização dos dados para garantir que a escala das variáveis (Renda vs. Pontuação de Gastos) não enviesasse o algoritmo de clustering.

2. Definição do Número de Clusters
Utilizei o método Elbow (Cotovelo) e a análise de Silhouette Score para determinar o número ideal de grupos. O modelo final foi consolidado com 5 clusters, alcançando um Silhouette Score de 0.272, indicando segmentações bem definidas.

3. As Personas Identificadas
Com base na análise dos centros de cada cluster, identifiquei as seguintes estratégias:

Cluster 0 (Estáveis): Público mais velho, renda estável e gastos moderados. Foco em fidelização.

Cluster 1 (Poupadores): Alto poder aquisitivo, mas baixa frequência de gastos. Foco em campanhas de exclusividade.

Cluster 2 (Engajados): Jovens com renda média e alto volume de compras. Foco em eventos e experiências.

Cluster 3 (Premium): Alta renda e alto padrão de gastos recorrentes. Foco em serviços VIP e networking.

Cluster 4 (Consumistas): Jovens com renda menor que priorizam o shopping. Foco em descontos e tendências.

📁 Como rodar o projeto
Clone o repositório.

Certifique-se de ter o Python e o Jupyter Notebook instalados.

Instale as dependências: pip install pandas scikit-learn matplotlib seaborn

Abra o arquivo .ipynb e execute as células para ver a análise completa.
