# Previsão de Churn em Plataforma de Streaming

## Descrição do Projeto

Este projeto aborda o desafio de **Previsão de Churn em Plataforma de Streaming**, cujo objetivo é desenvolver um modelo de classificação para prever quais usuários têm alta chance de cancelar a assinatura em uma plataforma de streaming. O problema de churn é crítico para empresas que desejam reduzir a perda de clientes, e esta análise busca identificar o perfil de usuários que tendem a deixar o serviço para que ações preventivas possam ser tomadas.

## Funcionalidades

- **Análise Exploratória dos Dados**: Exploração inicial do conjunto de dados para compreender a distribuição das variáveis, presença de valores faltantes e estatísticas descritivas.
- **Preparação dos Dados**: Tratamento de valores nulos, transformação de variáveis categóricas e normalização dos dados para garantir qualidade na modelagem.
- **Modelagem com Regressão Logística**: Criação de um modelo de classificação utilizando regressão logística para prever o churn.
- **Tuning e Otimização**: Ajuste dos hiperparâmetros do modelo para maximizar a acurácia e precisão da previsão.
- **Random Forest**: Implementação de um modelo de Random Forest com Grid Search para comparação de desempenho com a regressão logística.
- **Visualizações e Interpretação**: Visualização dos resultados por meio de matrizes de confusão e análise das métricas de desempenho do modelo.

## Requisitos

Para executar este projeto, são necessárias as seguintes bibliotecas Python:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Descrição da Base de Dados

O conjunto de dados fornecido inclui informações sobre os clientes de uma plataforma de streaming e suas características demográficas, comportamentais e de uso. A tabela de dados contém as seguintes colunas principais:

- **client_id**: ID único do cliente.
- **age**: Idade do cliente.
- **gender**: Gênero do cliente.
- **region**: Região de origem do cliente.
- **subscription_days**: Quantidade de dias como assinante.
- **subscription_type**: Tipo de conta (Basic, Standard, Premium).
- **num_contents**: Quantidade de conteúdos assistidos.
- **avg_rating**: Avaliação média dos conteúdos pelo cliente.
- **num_active_profiles**: Número de perfis ativos na conta.
- **num_streaming_services**: Quantidade de serviços de streaming que o cliente possui.
- **devices_connected**: Número de dispositivos conectados à conta.
- **churned**: Indicador se o cliente cancelou a conta (0 = não, 1 = sim).

## Resultados

Após o treinamento e a avaliação dos modelos, os principais resultados obtidos foram:

- **Regressão Logística**:
  Acurácia: 81.57%

- **Random Forest (com Tuning)**:
  Acurácia: X%

Esses resultados destacam as características que impactam o churn e ajudam a identificar os usuários com maior probabilidade de cancelar a assinatura, permitindo à empresa desenvolver estratégias para aumentar a retenção.

## Contato

Se você tiver dúvidas ou sugestões, entre em contato por [vitor13muniz09@gmail.com](mailto:vitor13muniz09@gmail.com).
