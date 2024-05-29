# Projeto CRUD fullstack

## Descrição do Projeto

Este projeto consiste em um sistema de CRUD de usuários, onde é possível visualizar
todos os usuários cadastrados na base de dados, editar suas informações conforme necessário,
excluir usuários existentes e cadastrar novos usuários.


## ℹ️ Observação Instruções de Instalação

- Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo [Clique aqui](https://nodejs.org/).
- Certifique-se de ter o MySQL instaldo em sua máquina. Você pode baixá-lo [Clique aqui](https://www.mysql.com/downloads/)
- Clone este repositório para o seu ambiente local.
---

## 🚀 Como Executar o Projeto

### Backend (API)

1. **Acesse a pasta `api`.**
   
2. **Instale as dependências:**

    ```bash
    npm install
    ```

3. **Configure suas credenciais do MySQL no arquivo `db.json`.**

4. **Inicie o servidor backend:**

    ```bash
    npm start
    ```

   A API estará acessível em [http://localhost:8800](http://localhost:8800).

---

### Frontend

1. **Acesse a pasta `frontend`.**

2. **Instale as dependências:**

    ```bash
    npm install
    ```

3. **Inicie o servidor frontend:**

    ```bash
    npm start
    ```

   O frontend estará acessível em [http://localhost:3000](http://localhost:3000).

---


## 📚 Dependências e Bibliotecas Utilizadas

### API (Backend)

- **express**: Framework Node.js para construção de aplicativos web.
- **mysql**: Driver Node.js para MySQL, utilizado para comunicação com o banco de dados.
- **cors**: Middleware express para habilitar o CORS (Cross-Origin Resource Sharing).
- **nodemon**: Ferramenta para reiniciar automaticamente o servidor sempre que houver alterações no código.

### Frontend (Cliente)

- **react**: Biblioteca JavaScript para construção de interfaces de usuário.
- **react-dom**: Pacote de renderização DOM para React.
- **react-icons**: Biblioteca de ícones para React.
- **react-scripts**: Conjunto de scripts e configurações para projetos React.
- **react-toastify**: Biblioteca para exibir notificações no estilo toast em aplicativos React.
- **styled-components**: Biblioteca para estilização de componentes em React.
- **axios**: Cliente HTTP baseado em Promise para o navegador e Node.js.


## Rotas da API

As rotas da API estão definidas no arquivo `api/routes/user.js`:

- **GET (http://localhost:3000/)**: Retorna a lista de todos os usuários cadastrados.
- **POST (http://localhost:3000/)**: Adiciona um novo usuário à base de dados.
- **PUT (http://localhost:3000/:id)**: Atualiza as informações de um usuário específico.
- **DELETE (http://localhost:3000/:id)**: Exclui um usuário específico da base de dados.

---

## ℹ️ Observações
Certifique-se de ter o Node.js e o MySQL instalados em seu ambiente de desenvolvimento.
