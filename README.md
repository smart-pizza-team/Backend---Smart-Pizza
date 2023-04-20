# Backend - Smart-Pizza

O repositório do Backend em NodeJS para um sistema de administração de restaurantes para um projeto da escola pode ser descrito da seguinte forma:

## Sistema de Administração de Restaurantes

Este é o repositório do Backend em NodeJS de um sistema de administração de restaurantes, desenvolvido para um projeto da escola. O objetivo deste sistema é permitir que os proprietários e funcionários de um restaurante possam gerenciar as informações e operações relacionadas ao estabelecimento, como cadastro de pratos, controle de estoque, gerenciamento de pedidos, entre outros.

### Tecnologias Utilizadas

(0Dev-Dependências0)

1 - "@types/bcryptjs": "^2.4.2",
2 - "@types/cors": "^2.8.12",
3 - "@types/express": "^4.17.13",
4 - "@types/jsonwebtoken": "^8.5.8",
5 - "@types/multer": "^1.4.7",
6 - "ts-node-dev": "^1.1.8",
7 - "typescript": "^4.5.5"


(0Dependências0)

1 - "@prisma/client": "^3.9.2",
2 - "bcryptjs": "^2.4.3",
3 - "cors": "^2.8.5",
4 - "dotenv": "^16.0.0",
5 - "express": "^4.17.2",
6 - "express-async-errors": "^3.1.1",
7 - "jsonwebtoken": "^8.5.1",
8 - "multer": "^1.4.4",
9 - "prisma": "^3.9.2"

### Funcionalidades Implementadas

- Autenticação de usuários (proprietários e funcionários)
- Cadastro, edição e exclusão de pratos
- Controle de estoque de ingredientes
- Gerenciamento de pedidos (criação, edição, exclusão e consulta)
- Geração de relatórios de vendas

### Como Executar

Para executar este projeto, siga os seguintes passos:

1. Clone este repositório em sua máquina local
2. Execute o comando `yarn install --force` para instalar as dependências
3. Crie um banco de dados MySQL e configure as credenciais no arquivo `.env`
4. Execute o comando `yarn run migrate` para criar as tabelas do banco de dados
5. Execute o comando `yarn run start` para iniciar o servidor web

### Como Contribuir

Se você deseja contribuir para este projeto, basta seguir os seguintes passos:

1. Crie um fork deste repositório em sua conta do GitHub
2. Crie uma nova branch para sua contribuição: `git checkout -b minha-nova-funcionalidade`
3. Faça as alterações necessárias e faça um commit: `git commit -m "Adiciona nova funcionalidade"`
4. Faça um push para a branch criada: `git push origin minha-nova-funcionalidade`
5. Abra um pull request para este repositório e aguarde a revisão e aprovação de sua contribuição. 

### Autor

Este projeto foi desenvolvido por [seu nome aqui], como parte do projeto final da disciplina de Desenvolvimento Web.
