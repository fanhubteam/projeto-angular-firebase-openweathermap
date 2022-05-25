# Angular + Firebase Weather Forecast App

# Objetivo

O objetivo final do app é o usuário após logado conseguir ver a previsão do tempo utilizando a geolocalização do navegador.

# Requisitos de Stack

- repo público no Github
- Firebase Authentication
- Firebase Hosting
- Angular
- API do open weather map (https://openweathermap.org/api/one-call-3)
- API do JS de geo localizacao (https://developer.mozilla.org/pt-BR/docs/Web/API/Geolocation_API)

# Fluxo de navegação do usuário

- O usuário precisa acessar uma URL.
- Se o usuário não estiver logado, redirecionar ele para o fluxo de login
- O fluxo de login deve ser feito utilizando o Firebase Authentication utilizando o Google como provider de OAuth (Login with Google)
- Após logado o usuário deve ser direcionado para uma tela aonde o navegador pede acesso a geolocalização do usuário utilizando a Geolocation API do Javascript
- Com as informações de Geo (lat,log) é esperado que a aplicação faça uma requisição para a API do Open Weather Map para trazer as informações de previsão de tempo dado a latitude e longitude.

# Diferencial

- Conseguir fazer um fluxo de deploy contínuo utilizando o GitHub Actions

# Terminei, e agora?

Envie um e-mail para arthur@fanhub.com.br com o link do seu repositório. Também envie uma disponibilidade para batermos um papo via Google Meet (40 minutos da sua agenda) não esqueça de colocar o link do seu linkedin.

Boa sorte.


