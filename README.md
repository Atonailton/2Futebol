# Consulta de Jogo de Futebol

Este é um projeto simples em **HTML**, **CSS** e **JavaScript** que permite ao usuário consultar o placar de um jogo de futebol em tempo real utilizando a API de Futebol da RapidAPI. O sistema retorna o placar do primeiro e segundo tempo, e quem marcou o primeiro gol.

## Funcionalidade

- Permite pesquisar jogos ao digitar o nome de um time.
- Exibe as informações do jogo ao vivo: 
  - Nome dos times.
  - Placar do primeiro tempo.
  - Placar do segundo tempo.
  - Quem marcou o primeiro gol.
  
## Requisitos

Este projeto depende da [API de Futebol da RapidAPI](https://rapidapi.com/). Você precisará de uma chave de API para utilizá-la.

## Como usar

1. **Obter a chave da API**:
   - Acesse [API-Football no RapidAPI](https://rapidapi.com/api-football/api/api-football-v1) e crie uma conta.
   - Obtenha a chave da API clicando em "Get your API Key".
   
2. **Substituir a chave da API**:
   - Abra o arquivo `index.html` e substitua a chave da API no código:
   ```javascript
   'X-RapidAPI-Key': 'SUA_CHAVE_AQUI', // Substitua com a chave obtida
