# 🩸 Sangria - Controle de Doações v2.0

Sistema web completo desenvolvido em Python com Flask para auxiliar na triagem de doadores de sangue, controlar a elegibilidade e gerenciar os registros. Esta é a versão 2.0, com uma interface completamente redesenhada e um painel de controle para administradores.

---

## ✨ Funcionalidades Principais

* **Interface Moderna e Responsiva:** Visual totalmente refeito, focado em uma experiência de usuário limpa e agradável em qualquer dispositivo.
* **Sistema de Autenticação:** Cadastro e login de usuários com senhas seguras (hash).
* **Painel de Administrador:** Uma visão exclusiva para administradores, que permite:
    * Visualizar todos os doadores cadastrados.
    * Remover registros de doadores.
    * Gerar planilhas `.xlsx` com todos os dados para controle externo.
* **Triagem Inteligente:** Formulário de triagem para usuários comuns, com lógica no backend para determinar a aptidão do doador.
* **API Robusta:** Endpoints para adicionar, listar e remover doadores de forma dinâmica com JavaScript.

---

## 📸 Telas do Sistema

<p align="center">
  <img src="URL_DA_IMAGEM_DO_PAINEL_ADMIN" alt="Painel do Administrador" width="700">
  <br>
  <em>Painel do Administrador com a lista de doadores e opção de remoção.</em>
</p>

<p align="center">
  <img src="URL_DA_IMAGEM_DA_TELA_DE_LOGIN" alt="Tela de Login" width="700">
  <br>
  <em>Nova tela de login do projeto.</em>
</p>

---

## 🛠️ Tecnologias Utilizadas

* **Backend:** Python, Flask, SQLite
* **Frontend:** HTML5, CSS3, JavaScript
* **Bibliotecas Python:** Flask-Login, Werkzeug, Openpyxl

---

## 🚀 Como Executar Localmente

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/PD3-Sangria/E-triagem-v2.git](https://github.com/PD3-Sangria/E-triagem-v2.git)
    ```
2.  Navegue até a pasta do projeto e crie um ambiente virtual:
    ```bash
    cd E-triagem-v2
    python -m venv venv
    ```
3.  Ative o ambiente virtual e instale as dependências:
    ```bash
    # Windows
    .\venv\Scripts\activate
    # Linux/macOS
    # source venv/bin/activate
    
    pip install -r requirements.txt
    ```
4.  Inicialize o banco de dados:
    ```bash
    flask init-db
    ```
5.  Execute a aplicação:
    ```bash
    flask run
    ```
A aplicação estará disponível em `http://127.0.0.1:5000`.
