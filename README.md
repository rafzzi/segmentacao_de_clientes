# segmentacao_de_clientes
método de clusterização para segmentação de clientes utilizando
a análise RFM (recency, frequency, monetary).

## NOTEBOOK: 
segmentação_clientes.ipynb

### CARREGAMENTO DOS DADOS
### ANÁLISE VISUAL
Entendendo a necessidade da clusterização
### ANÁLISE RFM
Engenharia de features para aquisição da recencia, frequência e receita.
### CLUSTERIZAÇÃO
Utilizando o método KMeans da bilioteca sklearn
#### NÚMERO DE CLUSTERS
Escolhendo qual o n_clusters adequado para utilizar como hiperparâmetro através de três métricas distintas:
- visualmente (regra do cotovelo)
- análise matemática (distância entre ponto e reta)
- coeficiente de silhueta
#### CLUSTERIZAÇÃO DA RECÊNCIA
Clusterizando com KMeans e ordenando a numeração de cluster para servir como uma pontuação
#### CLUSTERIZAÇÃO DA FREQUÊNCIA
Clusterizando com KMeans e ordenando a numeração de cluster para servir como uma pontuação
#### CLUSTERIZAÇÃO DA RECEITA
Clusterizando com KMeans e ordenando a numeração de cluster para servir como uma pontuação
### SEGMENTAÇÃO DE CLIENTES
['Premium', 'Master', 'Business', 'Inativo']
#### ANÁLISE VISUAL
Verificando como os clusters se organizam no espaço RFM plotando as combinações
(Recencia x Frequencia, Frequencia x Receita, Recencia x Receita)
