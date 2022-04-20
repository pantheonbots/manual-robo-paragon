---
title: "Configurações do Canal"
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "configuracoes"
weight: 12
toc: true
---

Esta é a seção mais importante do setup, onde você fará a configuração do tamanho do canal. Dê preferência ao canal manual sempre que possível, pois essa estratégia é melhor aproveitada com analises manuais de suporte e resistência.

#### Se Canal Automático

- **Horário inicial da criação do canal:** Configura o horário de início da criação do canal automático

- **Horário final da criação do canal:** Configura o horário final da criação do canal automático

- **Distância mínima (0: sem mínimo):** Configura uma distância mínima caso o canal automático for muito estreito

- **Distância máxima (0: sem máxima):** Configura uma distância mínima caso o canal automático for muito largo

- **Cálculo do preço:** Configura a forma do candlestick usada para capturar os preços dentro do canal automático definido pelo horário e calcular o preço máximo e minimo de todo o período do horário de cálculo para gerar o canal automático

- **Alinhamento ao ajustar o máximo ou mínimo:** Essa opção é usada quando as opções "Distância mínima" ou "Distância máxima" se sobrepoem no calculo automático. Exemplo, se o canal automático gerou um canal de 300 pontos, e você configurou a distância máxima de 200, o canal de 200 deve ser alinhado usando alguma referência. Nesse caso você pode optar pelas opções "Canal Inferior", ou seja, o suporte será no menor preço calculado e a resistência 200 pontos, "Canal Superior", ou seja, o suporte será no maior preço calculado e o suporte 200 pontos abaixo, ou "Canal Central", onde o canal de 200 pontos do exemplo ficaria centralizado entre os 2 precos calculados automaticamente

#### Se Canal Manual

Esta é a melhor opção para extrair a melhor performance do robô Paragon. Ao configurar os 2 preços, o robô usará esses 2 preços como referência e replicará indefinidamente para cima ou para baixo a distância do canal configurado

- **Preço superior do canal:** Configura o preço do canal de resistência (superior)

- **Preço inferior do canal:** Configura o preço do canal de suporte (inferior)
