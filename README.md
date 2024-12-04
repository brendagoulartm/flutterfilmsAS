# 🎥 Aplicativo de Filmes Populares  
**Desenvolvido por:** Brenda Goulart Machado  
**Disciplina:** Desenvolvimento de Sistemas Móveis  
**Universidade:** ULBRA  

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=Finalizado&color=GREEN&style=for-the-badge)

---

# 🛠️ Ferramentas Utilizadas  
- **Flutter**: Framework para desenvolvimento multiplataforma.  
- **Dart**: Linguagem de programação utilizada no Flutter.  
- **Firebase**: Autenticação e gerenciamento de banco de dados.  
- **API de Filmes**: Fonte de dados dinâmicos com informações sobre filmes populares.  

---

# 💡 Sobre o Projeto  
Este aplicativo permite aos usuários explorar filmes populares por meio de uma interface intuitiva. Após autenticar-se com uma conta, o usuário acessa uma lista de filmes com informações como título, sinopse, avaliação e data de lançamento.  

### Principais Funcionalidades:
- **Tela de Login**: Usando Firebase Authentication para acesso seguro.  
- **Listagem de Filmes**: Consumo de uma API pública para exibir os filmes mais populares de 2024.  
- **Detalhes dos Filmes**: Informações adicionais ao selecionar um filme.  
- **Botão de Navegação**: Retorna à tela inicial de forma rápida e prática.  

---

# 🧰 Pré-requisitos  
Antes de iniciar, você precisa instalar os seguintes softwares:  
- [Flutter SDK](https://flutter.dev)  
- [Android Studio](https://developer.android.com/studio)  
- Conta no [Firebase](https://firebase.google.com/)  

---

# 🚀 Passo a Passo para Configuração  

## **1. Configurando o Android Studio**  
1. Baixe e instale o Android Studio: [Link Oficial](https://developer.android.com/studio).  
2. Durante a instalação, inclua o **Android Virtual Device (AVD)**.  
3. No Android Studio, vá até **Tools > Device Manager**.  
4. Clique em **Create Device** e escolha um modelo de dispositivo.  
5. Baixe a imagem do sistema operacional Android e finalize a configuração.  
6. Inicie o emulador clicando no ícone de "play".

 ---

# 🔥Configurando o Firebase

1. Instalação do Cli do Firebase com o comando "npm install -g firebase-tools", podendo baixar manualmente pelo link " https://firebase.google.com/docs/cli?hl=pt-br#sign-in -test-cli " e escolhe seu sistema operacional.
2. No seu prompt de comando "cmd" use o comando "firebase login".
3. Comando "dart pub global activate flutterfire_cli".
4. Dentro do diretório do projeto desse comando "flutterfire configure".
5. Depois digite esse "flutter pub add firebase_core".
6. Depois digite esse "flutter pub add firebase_core".

 ---

# 💻 Configurando o Flutter e o Dart no Windows

1. Baixe o Flutter SDK: Flutter.dev.
2. Extraia os arquivos para um diretório acessível (ex.: C:\src\flutter).
3. Adicione o Flutter ao PATH do sistema.
4. Confirme a instalação com o comando: flutter doctor

---

# 🎬 Sobre o meu projeto:
A **TMDB API** (The Movie Database) é uma API gratuita que fornece informações detalhadas sobre filmes, séries e artistas. Utilizamos o endpoint `/movie/popular` para acessar uma lista dos filmes mais populares, retornando dados como título, sinopse, avaliações e imagem de capa. A URL base da API é `https://api.themoviedb.org/3`, e para utilizá-la é necessário obter uma chave de API criando uma conta no site oficial da TMDB.
O aplicativo foi desenvolvido com Flutter e Dart, proporcionando uma solução multiplataforma eficiente e de fácil manutenção. O Firebase foi escolhido para autenticação e armazenamento de dados devido à sua integração simples com o Flutter, escalabilidade e robustez. Com o Firebase, implementamos login de usuários e gerenciamento de dados, garantindo uma experiência fluida e segura para os usuários.

   
 <div>
    <a href="https://www.instagram.com/bremachado__//" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:brendagoulart675@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/brenda-machado33/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"> </a>   
</div>
