# 🔐 Firebase Authentication App

## 📌 Descrição

Aplicação web simples desenvolvida com Firebase Authentication, permitindo cadastro, login e gerenciamento de sessão de usuários.

O sistema altera dinamicamente a interface conforme o estado de autenticação, proporcionando uma experiência interativa e funcional.

---

## 🚀 Tecnologias Utilizadas

* HTML5
* JavaScript (ES6)
* Firebase Authentication

---

## ⚙️ Funcionalidades

### 🔑 Autenticação

* Cadastro de usuário com email e senha
* Login com validação
* Tratamento de erros (email inválido, senha fraca, etc.)

### 🔄 Sessão

* Persistência de login com `onAuthStateChanged`
* Usuário permanece logado após recarregar a página

### 🎨 Interface Dinâmica

* Tela de login/cadastro quando não autenticado
* Exibição do email do usuário quando autenticado

### 🚪 Logout

* Encerramento de sessão com um clique

### ⏳ Loading

* Indicador visual durante:

  * Login
  * Cadastro
  * Verificação de autenticação

---

## 📸 Prints da Aplicação

### Tela de Login / Cadastro

![Tela de Login](./prints/login.png)

### Usuário Logado

![Usuário Logado](./prints/logado.png)

---

## 🔗 Deploy

Acesse a aplicação online:
👉 https://seu-site.vercel.app

---

## 🛠️ Como executar o projeto

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/firebase-auth-app.git
```

2. Abra o arquivo `index.html` no navegador

3. Configure o Firebase:

* Crie um projeto no Firebase
* Ative Authentication (Email/Senha)
* Substitua o objeto `firebaseConfig` no arquivo `app.js`

---

## 📚 Aprendizados

Este projeto demonstra na prática:

* Integração com Firebase Authentication
* Gerenciamento de estado de autenticação
* Manipulação de DOM com JavaScript puro
* Boas práticas de UX (loading e feedback)

---

## 👨‍💻 Autor

Desenvolvido por você 🚀

---

## 📌 Observação

Este projeto tem fins educacionais e foi desenvolvido como atividade prática para aprendizado de autenticação com Firebase.

