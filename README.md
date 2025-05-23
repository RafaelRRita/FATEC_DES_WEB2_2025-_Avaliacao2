# FATEC_DES_WEB2_2025-_Avaliacao2
Avaliacao 2 da materia de Desenvolvimento Web 2

# Sistema de Gerenciamento de Produtos Artesanais 🛍️

Este é um sistema simples em PHP com MySQL, utilizando PDO, voltado para o **cadastro, listagem, remoção e gerenciamento de produtos artesanais**, com controle de acesso via login.

## 📌 Funcionalidades

- Autenticação de usuários (login/logout)
- Cadastro de produtos artesanais
- Listagem de produtos cadastrados
- Remoção de produtos
- Interface com Bootstrap responsiva

---

## 🔐 1. Página de Login (`index.php`)

A primeira página do sistema é a tela de **login**, onde o usuário deve informar suas credenciais para acessar o sistema.

- Caso as informações estejam corretas, o usuário é redirecionado para a **página inicial (home.php)**.
- Se estiverem incorretas, uma mensagem de erro é exibida.
- O acesso para o login e "admin" e a senha e "admin".
  
![image](https://github.com/user-attachments/assets/1529f1c4-5d23-4d7c-a08d-c11b5969b297)

---


## 🏠 2. Página Inicial (`home.php`)

Após o login, o usuário acessa o painel principal, onde encontra **ícones ou botões de navegação** para as seguintes seções:

- **Cadastrar Produto** – Envia o usuário para a página de cadastro.
- **Visualizar Produtos** – Redireciona para a página que exibe todos os produtos(artesanais) cadastrados.
- **Remover Produtos** – Vai para a página de remoção de produtos (com confirmação).
- **Logout** – Finaliza a sessão e retorna à tela de login.

![image](https://github.com/user-attachments/assets/61fe1d33-d75c-4bc7-ae7e-2155d26367b5)


---

## ➕ 3. Página de Cadastro (`cadastro_produto.php`)

Permite o **cadastro de novos produtos** no banco de dados. O formulário inclui os seguintes campos:

- Nome do produto
- Preço
- Descrição
- Categoria

Após o envio, os dados são salvos no banco de dados (artesanato_db) e o usuário pode continuar cadastrando mais produtos ou voltar para o menu principal.

![image](https://github.com/user-attachments/assets/e2727a91-31b0-4267-94a1-1488f560d6d4)


---

## 📋 4. Página de Listagem (`listar.php`)

Exibe uma **tabela com todos os produtos cadastrados**, incluindo:

- ID
- Nome
- Preço
- Descrição
- Categoria

Cada item é mostrado de forma clara e organizada usando o estilo do Bootstrap.

![image](https://github.com/user-attachments/assets/36197519-627b-4b48-ba26-3ad10cf50bef)


---

## 🗑️ 5. Página de Remoção (`remover_produto.php`)

Mostra uma lista semelhante à de listagem, porém com um **botão "Remover" ao lado de cada item**.

- Ao clicar em "Remover", o sistema pede uma **confirmação**.
- Após a confirmação, o produto é excluído do banco de dados.

![image](https://github.com/user-attachments/assets/9d59b9b2-9ced-4e11-a0f9-3b02290cd908)


---

## 🚪 6. Logout (`logout.php`)

Finaliza a sessão do usuário logado, retornando à tela de login e invalidando o acesso à área interna até novo login.

---

## 🛠️ Tecnologias Utilizadas

- **PHP 7+**
- **MySQL** com **PDO**
- **Bootstrap 5** (via CDN)
- **HTML5/CSS3**
- Sessões PHP para autenticação

---

