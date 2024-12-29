# Chat Online

Este é um projeto de aplicação web para um chat em tempo real utilizando WebSockets. O sistema é composto por um frontend e um backend, permitindo que usuários possam se conectar, enviar e receber mensagens em tempo real.

## Tecnologias Utilizadas

### Frontend
- **HTML**
- **CSS** (com design responsivo e estilizações personalizadas)
- **JavaScript** (para manipulação de DOM e WebSockets)

### Backend
- **Node.js**
- **WebSocket** (biblioteca `ws` para gerenciamento das conexões)
- **Dotenv** (para gerenciar variáveis de ambiente)

## Funcionalidades

### Frontend
1. **Login**: O usuário pode inserir um nome para se identificar no chat.
2. **Envio de mensagens**: Permite enviar mensagens para outros participantes do chat.
3. **Recebimento de mensagens**: Exibe as mensagens de outros usuários na interface.
4. **Design responsivo**: Interface otimizada para diferentes dispositivos.

### Backend
1. **Gerenciamento de conexões**: Utiliza WebSockets para manter a comunicação bidirecional.
2. **Broadcast de mensagens**: Distribui mensagens recebidas para todos os clientes conectados.

## Estrutura do Projeto

### Frontend
```
project-root/
|-- index.html
|-- css/
|   |-- style.css
|-- js/
    |-- script.js
```

### Backend
```
project-root/
|-- src/
|   |-- server.js
|-- .env
|-- package.json
```

## Configuração e Execução

### Backend
1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Instale as dependências com o comando:
   ```bash
   npm install
   ```
3. Crie um arquivo `.env` na raiz do projeto e defina a porta do servidor (opcional):
   ```env
   PORT=8080
   ```
4. Inicie o servidor:
   - Modo produção:
     ```bash
     npm start
     ```
   - Modo desenvolvimento:
     ```bash
     npm run dev
     ```

### Frontend
1. Abra o arquivo `index.html` no navegador.
2. Insira um nome de usuário na tela de login e comece a conversar!

## ScreenShots
Login 
![image](https://github.com/user-attachments/assets/74e93b3d-eaec-4eb3-8d82-d6e82ab53d80)


## Contribuição
Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades.

1. Realize um fork do repositório.
2. Crie uma nova branch para sua contribuição:
   ```bash
   git checkout -b minha-contribuicao
   ```
3. Envie suas alterações:
   ```bash
   git push origin minha-contribuicao
   ```
4. Abra um Pull Request.

## Licença
Este projeto está licenciado sob a licença MIT.

---

**Autor**: Eder Souza

