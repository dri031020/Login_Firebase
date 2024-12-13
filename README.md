# Projeto de Autenticação com Firebase 🔑

Este projeto demonstra como integrar a autenticação do Firebase em uma aplicação web, incluindo funcionalidades de login com Google e recuperação de senha e também detalhes sobre como o sistema funciona e como ele é implementado.

## Funcionalidades ✨

### 1. Login com Google 🟢
O usuário pode fazer login utilizando sua conta do Google. Após a autenticação bem-sucedida, o sistema redireciona o usuário para a página inicial (`homepage.html`). Isso é feito através do fluxo de autenticação fornecido pelo Firebase, permitindo que o login seja realizado com segurança e facilidade.

**Fluxo de autenticação com Google:**
- O usuário clica no botão de login com o Google.
- Após o login, o Firebase redireciona o usuário para a página principal.

### 2. Recuperação de Senha 🔄
Se o usuário esquecer sua senha, ele pode recuperar o acesso à conta. Ao clicar no link "Recuperar Senha", o usuário será solicitado a informar seu endereço de e-mail. O sistema valida o e-mail fornecido e, se estiver correto, um e-mail com um link para redefinir a senha será enviado.

**Fluxo de recuperação de senha:**
- O usuário clica no link "Recuperar Senha".
- É solicitado o e-mail para o envio do link de redefinição.
- O sistema valida o e-mail e envia um link para redefinir a senha.

### 3. Interface 🚀
O projeto foi desenvolvido com uma interface simples e funcional. O design é responsivo e permite que os usuários façam login ou recuperem sua senha de forma intuitiva.

## Imagens do Projeto 📸

**Tela de Login com Google:**
 ![login com google firebase](https://github.com/user-attachments/assets/df948006-5ad1-40e5-92e2-019098c7ed42)


**Tela de Recuperação de Senha:**
![recuperação se senha firebase](https://github.com/user-attachments/assets/aa0c1824-feec-416c-ad97-02f79dcd82b3)


**Tela de Cadastro:**
![criação de conta firebase](https://github.com/user-attachments/assets/38f9bb38-3bae-4029-81c2-bc89dc87deeb)

**Tela de Login inicial:**
![tela inicio firebase](https://github.com/user-attachments/assets/c2c5366c-162b-4727-8146-0dcc9c5b314a)

## Como Funciona 🤔

Este projeto utiliza a biblioteca de autenticação do Firebase, que simplifica a implementação de login com Google e recuperação de senha. A autenticação é realizada através de métodos assíncronos e é totalmente gerenciada pelo Firebase, garantindo segurança e agilidade no processo.

## Conclusão 🎉

Com este projeto, você tem um exemplo prático de como integrar o Firebase em sua aplicação para gerenciar autenticação de usuários de maneira eficiente. O uso de recursos como login social com Google e recuperação de senha facilita a experiência do usuário e aumenta a segurança.
