# Descrição
Este projeto tem como objetivo desenvolver um modelo de classificação capaz de prever quais usuários têm uma alta probabilidade de cancelar suas assinaturas em uma plataforma de streaming. A previsão de churn é fundamental para que a empresa possa tomar decisões estratégicas, reduzir as taxas de cancelamento e otimizar a retenção de clientes.

Através de um conjunto de dados contendo informações sobre as contas dos clientes, como idade, gênero, dias de assinatura, número de dispositivos conectados, entre outros, o modelo será treinado para identificar perfis de usuários mais propensos a deixar a plataforma.

# Estrutura do Projeto

- client_id: Identificação única do cliente.
- age: Idade do cliente.
- gender: Gênero do cliente.
- region: Região de origem do cliente.
- subscription_days: Número de dias com a assinatura ativa.
- subscription_type: Tipo de conta do cliente (ex.: premium, básica).
- num_contents: Número de conteúdos assistidos na plataforma.
- avg_rating: Avaliação média dos conteúdos pelo cliente.
- num_active_profiles: Número de perfis ativos associados à conta.
- num_streaming_services: Número de serviços de streaming que o cliente utiliza.
- devices_connected: Quantidade de dispositivos conectados à conta.
-cchurned: Se o cliente cancelou a assinatura (1) ou não (0).

# Bibliotecas

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
