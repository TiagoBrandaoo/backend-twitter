README - Back-End Twitter Clone
Este é o repositório do back-end do projeto Twitter Clone. O projeto é desenvolvido utilizando as seguintes tecnologias e bibliotecas:

Node.js: Ambiente de execução JavaScript no servidor.
Express.js: Framework web para construção de aplicativos em Node.js.
Mongoose: ODM (Object-Document Mapping) para interagir com o banco de dados MongoDB.
Bcrypt: Biblioteca para criptografia de senhas.
Cors: Middleware para habilitar o CORS (Cross-Origin Resource Sharing).
jsonwebtoken: Biblioteca para geração e verificação de tokens de autenticação.
Configuração do Projeto
Para executar o projeto em seu ambiente local, siga as etapas abaixo:

Certifique-se de ter o Node.js e o MongoDB instalados em sua máquina.
Clone este repositório em sua máquina local.
Execute o comando npm install para instalar as dependências do projeto.
Certifique-se de que o MongoDB esteja em execução.
Abra o arquivo index.js e verifique se a URL de conexão com o MongoDB está correta. Por padrão, está definido como mongodb://localhost/twitter-clone.
Execute o comando npm start para iniciar o servidor.
Agora você pode acessar o back-end do Twitter Clone em http://localhost:3000.

Funcionalidades
O back-end do Twitter Clone oferece as seguintes funcionalidades:

Registro de usuário: Envie uma solicitação POST para /register com um objeto JSON contendo username, email e password para criar um novo usuário.

Login de usuário: Envie uma solicitação POST para /login com um objeto JSON contendo email e password para autenticar e obter um token de acesso.

Criação de tweet: Envie uma solicitação POST para /tweets com um objeto JSON contendo text e um token de acesso válido no cabeçalho Authorization para criar um novo tweet.

Listagem de tweets: Envie uma solicitação GET para /tweets para obter uma lista de tweets em ordem decrescente de criação.

Observações
Certifique-se de configurar corretamente as variáveis de ambiente e as políticas de segurança ao implantar este projeto em um ambiente de produção.

Se você encontrar algum problema ou tiver alguma dúvida, sinta-se à vontade para abrir uma issue neste repositório.
