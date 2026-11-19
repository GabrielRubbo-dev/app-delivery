# AiQueFome! 🍔🏍️

O **AiQue Fome!** é um protótipo de aplicativo de delivery desenvolvido como parte da minha jornada inicial de aprendizado em programação, permitindo explorar na prática o desenvolvimento de uma interface móvel, a navegação de usuários e a integração com serviços de backend. 

## 🛠️ Tecnologias e Ferramentas

Com base na arquitetura do projeto, estas foram as principais tecnologias utilizadas:
- **Linguagem:** Kotlin
- **Plataforma:** Android
- **Design e UI:** AndroidX, Material Design e XML
- **Autenticação e Banco de Dados:** Firebase (Auth, Database)
- **Integração:** Google Sign-In API
- **Ferramentas:** Android Studio e Gradle

## 🧠 O Maior Desafio (e como resolvi)

Durante o desenvolvimento deste protótipo, a etapa mais difícil sem dúvida foi **implementar o login através da API do Google**. 

A integração inicial foi complexa porque exigia entender o fluxo de autenticação OAuth, gerar e configurar chaves de segurança (certificados SHA-1) no console de desenvolvedor do Google e conectar tudo isso ao Firebase para gerenciar a sessão do usuário no aplicativo. Eu resolvi esse obstáculo seguindo tutoriais passo a passo na comunidade e utilizando o Gemini como auxilio. 

## 🚀 Como rodar o projeto na sua máquina

Se você quiser clonar e testar este projeto no seu próprio computador, siga os passos abaixo:

1. **Clone este repositório:**
   Abra o seu terminal e digite o comando:
   ```bash
   git clone [https://github.com/SEU-USUARIO/aique-fome.git](https://github.com/SEU-USUARIO/aique-fome.git)
