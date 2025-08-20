Telecom X – Previsão de Churn (Parte 2)
📣 História do Desafio

Parabéns! 🎉 Após sua excelente análise exploratória de dados da Telecom X, você foi convidado a integrar a equipe de Machine Learning.
Sua missão agora é prever quais clientes têm maior chance de cancelar seus serviços, ajudando a empresa a reduzir o churn.

🎯 Objetivos do Projeto

Preparar e pré-processar os dados para Machine Learning.

Explorar os dados com gráficos analíticos.

Treinar dois modelos de classificação: Logistic Regression e Random Forest.

Avaliar os modelos com métricas de desempenho (accuracy, classification report, ROC AUC).

Interpretar a importância das variáveis e gerar insights estratégicos.

🧰 Bibliotecas Utilizadas
pandas, numpy, matplotlib, seaborn
scikit-learn: train_test_split, StandardScaler, LogisticRegression, RandomForestClassifier, classification_report, roc_auc_score

🚀 Etapas do Projeto

Carregamento dos dados

CSV: TelecomX_Data_tratado.csv

Limpeza da coluna alvo (Churn)

Convertida para 0 (No) e 1 (Yes)

Pré-processamento

Encoding de variáveis categóricas (get_dummies)

Normalização para Logistic Regression (StandardScaler)

Separação treino/teste

80% treino, 20% teste, stratified pela variável alvo

Treinamento dos modelos

Logistic Regression

Random Forest

Avaliação dos modelos

Classification report

ROC AUC

Análise exploratória e gráficos

Distribuição de churn

Churn por tipo de contrato, método de pagamento, gênero, senioridade

Distribuição de tenure

Quantidade de serviços contratados

Heatmap de correlação (apenas variáveis numéricas)

Importância das variáveis

Random Forest para identificar os top fatores de churn

Recomendações estratégicas

Incentivar contratos mais longos

Alertas/campanhas para clientes com pagamento eletrônico

Serviços de suporte técnico e backup online

Monitoramento contínuo dos clientes com alto risco de churn

📊 Exemplos de Gráficos

Distribuição de Churn

Churn por Tipo de Contrato

Churn por Método de Pagamento

Churn por Gênero e SeniorCitizen

Distribuição de Tenure

Churn por Quantidade de Serviços Contratados

Heatmap de correlação

🏆 Resultados

Modelos treinados: Logistic Regression e Random Forest

Métricas avaliadas: accuracy, classification report, ROC AUC

Top fatores de churn (Random Forest):

Contrato de menor duração

Método de pagamento eletrônico

Tenure baixo

Quantidade de serviços contratados

📌 Conclusão Estratégica

A análise preditiva permite à Telecom X identificar clientes com alto risco de churn.
Com base nos insights:

Focar em renovação de contratos longos

Melhorar campanhas de retenção para clientes que utilizam métodos de pagamento eletrônico

Oferecer serviços de suporte e proteção online

Monitorar clientes com baixo tenure e múltiplos serviços contratados
