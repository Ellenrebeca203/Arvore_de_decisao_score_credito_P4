# Arvore_de_decisão_score_credito_P4
Projeto utilizando modelo de Machine Learning 'Árvore de Decisão' para prever variável alvo 'credit_score'.
## Objetivo do projeto
Fazer previsões da variável 'credit_score' afim de prever o risco de um indivíduo se tornar inadimplente com suas obrigações financeiras.

Avaliando o risco de emprestar dinheiro a um determinado indivíduo e, assim, tomar decisões mais informadas sobre a aprovação ou negação de crédito.

## Dados do dataset 
- Age : Idade dos nossos clientes.

- Income : Salário Mensal.

- Gender : Gênero.

- Education : Nível de escolaridade dos clientes.

- Marital : Status Civilmente.

- Number of Children : Quantidade de filhos.

- Home : Tipo de residência, alugada ou própria.

- Credit Score : Nossa variável preditora, o score de crédito dos clientes.

## Etapas do projeto
1. Etapa 1: Etapa de pré-processamento de dados, análise exploratória de dados, compreensão da correlação de variáveis e balanceamento.
-Carregamento e tratamento da base de dados: a base foi carregada e lida com a biblioteca do pandas, em seguida foi verificado os tipos de dados e se havia dados faltantes, incorretos ou Outliers. Foi feita a transformação de variáveis categóricas utilizando métodos como 'label encoding' e 'get dummies', permitindo uma análise destas variáveis com as outras. 

- Análise exploratória dos dados: nesta etapa foram utilizados gráficos para analisar o comportamento das variáveis.

- Separação das bases em treino e teste: foi feita a separação das bases de treino e teste através da biblioteca Sklearn, importando a classe train_test_split. O documeto foi salvo separando essas bases de treino e teste para posterior avaliação

2. Etapa 2: Etapa de aplicação do modelo de Machine Learning e Avaliação.
- Critérios e modelo: Na segunda parte do projeto foram carregados os dados de treino e teste, e aplicado o algortimo da Árvore de Decisão aos dados de treinamento, utilizando critério de Gini e random stat.

- Modelo e Avaliação: Foi realizado a aplicação do modelo de 'Árvore de Decisão' aos dados, e feita a avaliação do desempenho dele para os dados do dataset. 

## Conclusão
O modelo de Árvore de Decisão se mostrou bastante eficaz para os dados de teste, com suas métricas elevadas. 
Acurácia: 0.95
Recall:  0.93 
F1-score: 0.93
