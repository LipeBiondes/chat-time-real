# chat-time-real

Site do projeto de chat - Primeira Versão

## Sobre o Projeto

Este projeto é a primeira versão do front-end de um site de chat. Ele permite que os usuários façam login, enviem mensagens e vejam mensagens de outros usuários em tempo real. Abaixo está um resumo do código JavaScript que implementa essas funcionalidades:

### Funcionalidades

- **Login de Usuário**: Os usuários podem fazer login inserindo um nome. Cada usuário recebe uma cor aleatória para identificar suas mensagens.
- **Envio de Mensagens**: Após o login, os usuários podem enviar mensagens que serão exibidas na tela.
- **Recebimento de Mensagens**: As mensagens enviadas por outros usuários são recebidas e exibidas em tempo real.
- **Scroll Automático**: A tela de chat rola automaticamente para mostrar as mensagens mais recentes.

### Código JavaScript

O código JavaScript principal é responsável por gerenciar o login, envio e recebimento de mensagens, e a interface do usuário. Aqui estão alguns dos principais trechos de código:

- **Seleção de Elementos**: Seleciona os elementos do DOM necessários para o login e chat.
- **Cores Aleatórias**: Gera uma cor aleatória para cada usuário.
- **Criação de Mensagens**: Cria elementos de mensagem para o usuário atual e outros usuários.
- **Processamento de Mensagens**: Processa as mensagens recebidas do servidor WebSocket.
- **Manipulação de Login**: Gerencia o evento de login do usuário.
- **Envio de Mensagens**: Envia mensagens para o servidor WebSocket.

Esta é uma visão geral do projeto de chat em sua primeira versão. Mais funcionalidades e melhorias serão adicionadas nas próximas versões.
