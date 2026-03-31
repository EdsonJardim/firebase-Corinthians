# 🔐 Firebase Corinthians

## 📌 Descrição

Aplicação web desenvolvida utilizando Firebase Authentication para cadastro, login e gerenciamento de sessão de usuários.

O sistema permite autenticação com email e senha, mantendo o usuário logado mesmo após recarregar a página, além de alterar dinamicamente a interface conforme o estado de autenticação.

---

## 🚀 Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (ES6)
* Firebase Authentication

---

## ⚙️ Funcionalidades

### 🔑 Autenticação

* Cadastro de usuário com email e senha
* Login com validação
* Tratamento de erros (senha fraca, email inválido, etc.)

### 🔄 Sessão

* Persistência de login com `onAuthStateChanged`
* Usuário permanece logado após atualizar a página

### 🎨 Interface Dinâmica

* Tela de login/cadastro quando não autenticado
* Exibição do email do usuário quando autenticado

### 🚪 Logout

* Encerramento de sessão com botão de logout

### ⏳ Loading

* Indicador de carregamento durante autenticação

---

## 📸 Prints da Aplicação

### 🔐 Tela de Login / Cadastro

![Tela de Login](./prints/login.png)

### 👤 Usuário Logado

![Usuário Logado](./prints/logado.png)

---

## ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/firebase-Corinthians.git
```

### 2. Acesse a pasta

```bash
cd firebase-Corinthians
```

### 3. Execute o projeto

```bash
npx serve
```

### 4. Abra no navegador

```
http://localhost:3000
```

---

## 🔥 Configuração do Firebase

1. Acesse o Firebase Console
2. Crie um projeto
3. Ative **Authentication**
4. Habilite **Email e Senha**
5. Copie a configuração e cole no `app.js`

---

## 📁 Estrutura do Projeto

```
firebase-Corinthians/
├── index.html
├── style.css
├── app.js
├── README.md
└── prints/
    ├── login.png
    └── logado.png
```

---

## 📚 Aprendizados

* Integração com Firebase Authentication
* Manipulação de DOM com JavaScript
* Gerenciamento de estado de autenticação
* Boas práticas de UX (loading e feedback)

---

## 👨‍💻 Autor

Edson Eduardo 🚀

---

## 📌 Observação

Projeto desenvolvido para fins educacionais como atividade prática de autenticação com Firebase.

