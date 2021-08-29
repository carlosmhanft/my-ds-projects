# Previsão de casos de inadimplência

Utilizamos um base de clientes e criar modelos para prever se será inadimplente ou não.

Projeto criado utilizando um notebook dentro do google drive.

Passo-a-Passo:

1. Importação da base de treino e análise exploratória.
2. Tratando nulos e valores missing.
3. Criando e excluindo variáveis para chegar na ABT (Analytical Base Table).
4. Rodamos 4 modelos com configurações "default".
5. Aplicamos validação cruzada e aplicamos rebalanceamento da variável target.
6. Aplicamos tuning nos hiper-parâmetros
7. Analisamos as métricas e buscamos o modelo com a melhor relação de "recall" e "AUC".
8. Decidimos o modelo e rodamos na base de teste
