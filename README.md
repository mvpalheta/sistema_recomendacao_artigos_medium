# sistema_recomendacao_artigos_medium
Este projeto tem como finalidade apresentar uma aplicação de sistema de recomendação baseado em conteúdo a partir de dados obtidos, via webscraping, de artigos divulgado no [Medium](https://medium.com/), que é uma plataforma de divulgação rápida de artigos de diversos temas, atualmente composta de 170 milhões de leitores, que tem ganhado muitos seguidores na área de inteligência artficial com milhares de artigos divulgados mensalmente com temas relacionados à esta área. Para tanto, o projeto foi dividido em 4 partes:

**Parte 1 - Webscraping:** Para esta fase, foi utilizado o ótimo código dispobilizado [neste repositório](https://github.com/harrisonjansma/Medium_Scraper) pelo Harrison Jansma (muito obrigado cara!!!). Como realizei algumas pequenas modificações no código original, vou disponibilizá-lo aqui novamente. Para maiores detalhes sobre como o script funciona e como utilizá-lo sugiro consultar o repositório original;

**Parte 2 - Leitura e limpeza dos dados:** Nesta parte, é realizada uma "faxina" nos dados a fim de prepará-los para análise;

**Parte 3 - EDA:** Nesta parte é apresentada uma breve análise exploratória sobre os dados coletados, após a fase de limpeza, com a finalidade de ser obter uma visão geral sobre eles;

**Parte 4 - Sistema de recomendação:** Aqui é apresentada a construção de um sistema de recomendação básico, baseado em conteúdo, a partir dos artigos divulgados no Medium, onde o usuário pode informar o título de um artigo e com base no título, autor e publicação serão sugeridos artigos semelhantes.
