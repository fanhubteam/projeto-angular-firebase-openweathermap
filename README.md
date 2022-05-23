# Angular + Firebase Weather Forecast App

# Objetivo

O objetivo final do app é o usuario apos logado conseguir ver a previsao do tempo utilizando a geo localizacao do navegador.

# Requisitos de Stack

- repo publico no Github
- Firebase Authentication
- Firebase Hosting
- Angular
- API do open weather map (https://openweathermap.org/api/one-call-3)
- API do JS de geo localizacao (https://developer.mozilla.org/pt-BR/docs/Web/API/Geolocation_API)

# Fluxo de navegacao do usuario

- O usuário precisa acessar uma URL.
- Se o usuário não estiver logado, redirecionar ele para o fluxo de login
- O fluxo de login deve ser feito utilizando o Firebase Authentication utilizando o Google como provider de OAuth (Login with Google)
- Apos logado o usuario deve ser direcionado para uma tela a onde o navegador pede acesso a geo localizacao do usuario utilizando a Geolocation API do Javascript
- Com as informacoes de Geo (lat,log) é esperado que a aplicacao faca uma requisicao para a API do Open Weather Map para trazer as informacoes de previsao de tempo dado a latitude e longitude.

# Diferencial

- Conseguir fazer um fluxo de deploy continuo utilizando o GitHub Actions
