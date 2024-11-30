# Implementacao_e_Analise_do_Algoritmo_de_K-means_com_o_Dataset_Human_Activity_Recognition

# Descrição do Projeto
Este projeto tem como objetivo realizar a análise e o agrupamento de atividades humanas com base em dados de sensores provenientes do Human Activity Recognition Using Smartphones Dataset. Utilizando técnicas de aprendizado de máquina, o modelo aplica o algoritmo K-means para realizar o agrupamento das atividades (como WALKING, SITTING, STANDING, etc.) com base em medições de acelerômetros e giroscópios.

O projeto inclui etapas de pré-processamento, normalização dos dados, análise exploratória, escolha do número ideal de clusters e visualizações interativas para entender o agrupamento das atividades.

# Configuração do ambiente:

1-Abra o arquivo principal do projeto no Jupyter Notebook ou qualquer ambiente Python compatível.
Instale as dependências necessárias, como pandas, numpy, scikit-learn, matplotlib, seaborn e requests, utilizando o comando:
  pip install pandas numpy scikit-learn matplotlib seaborn requests
  
2-Carregar e Processar os Dados:

O script carrega os dados diretamente de links remotos hospedados no GitHub.
Certifique-se de estar conectado à internet para que os dados sejam carregados corretamente.

3-Executar o Código:

Execute o script passo a passo para carregar os dados, normalizar as variáveis, aplicar K-means, e gerar visualizações interativas.
O código irá calcular métricas como o Silhouette Score e a Inércia para avaliar a qualidade dos clusters.

4-Visualizações e Avaliação:

O script exibe gráficos interativos (2D e 3D) usando PCA (redução de dimensionalidade) para mostrar a distribuição dos clusters.
A análise de métricas, como o Silhouette Score, é apresentada ao final para indicar a qualidade do agrupamento.

OBS: Outra alternativa é rodar o código usando o google collab configurado para o python.

# Estrutura dos Arquivos
├── Implementação_e_Análise_do_Algoritmo_de_K_means_com_o_Dataset_Human_Activity_Recognition.ipynb  # Código principal do projeto
├── README.md             # Documentação do projeto

# Tecnologias Utilizadas
Linguagem: Python

Bibliotecas principais:
1-pandas e numpy: para manipulação e análise de dados.
2-matplotlib e seaborn: para visualização gráfica.
3-scikit-learn: para implementação dos modelos de aprendizado de máquina (K-means, PCA).
4-requests: para carregar dados diretamente dos links remotos.


# Resultados Esperados
O modelo irá gerar clusters de atividades humanas a partir dos dados dos sensores.

Será exibido o Silhouette Score e a Inércia do K-means para avaliar a qualidade dos clusters.

Gráficos interativos (2D e 3D) serão gerados usando PCA para visualizar como as atividades estão agrupadas.

A distribuição das atividades nos clusters será exibida, mostrando como as diferentes atividades são agrupadas.

# Autores e Colaboradores

Victor César do Rosário Calheiros: Pré-processamento e análise exploratória de dados, implementação dos modelos de aprendizado de máquina.


Daniel de Souza Pereira: Desenvolvimento de visualizações e métricas de avaliação.
