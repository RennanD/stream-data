<h1 align="center" >
  <img src="./.github/logo.png" width = "100px">
</h1>

<h1 align="center"> Stream.Data 🕹️ </h1>


<h3 align="center">
  Desafio proposto no Ignite de React Native da Rocketseat.
</h3>

# Clonando este projeto

```
git clone https://github.com/RennanD/stream-data.git
```

# ❗️ Requisitos

- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/lang/en/) (Opicional)
- [Expo cli](https://docs.expo.io/get-started/installation/)


## 💻 Detalhes do Aplicativo

<h1 align="center">
  <img alt="WebApp" src="./.github/smartphone.svg" width = "120px">
</h1>


<p>
  Neste projeto utilizei:
</p>

- [Expo](https://docs.expo.io/bare/exploring-bare-workflow/) como abstração do React Native.
- [Expo Authetication]() e [AuthSessions]() para criar o login social com a Twicth Tv.

### Criando O Aplicativo na Twitch
Como estamos utilizando autenticação via OAuth, precisamos configar nosso aplicativo 
dentro do console da Twitch, para isso temos esse [guia](https://efficient-sloth-d85.notion.site/Preparando-ambiente-3ca815f6798f45b1a92f76a41d59c7bb). 

### Configurando o client_id

Na raiz do projeto, crie um arquivo `.env` e copie o conteúdo do arquivo `.env.exemple` para dentro do `.env`, logo após preencha do valor do `CLIENT_ID`, com o valor do id de cliente que está no console da Twitch.

### ⚡️ Iniciando a aplicação

Para iniciar a aplicação, em uma aba do terminal e na raiz do projeto execute:

```
yarn
expo start

# ou

npm install
expo start
```
## Iniciando o projeto no emulador/simulado

### IOS 🍎

Na interface do servidor do Expo, clique em `Run on iOS simulator`

### Android 👾

Na interface do servidor do Expo, clique em `Run on Android device/emulator`

## Para rodar o aplicativo no dispositivo físico

Primeiro, faça o download do aplicativo Expo go.
  - [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR&gl=US)
  - [IOS](https://apps.apple.com/br/app/expo-go/id982107779)

Com o Expo Go instalado, escaneie o qrcode que aparece na interface do expo


# App Demo 

<h1 align="center">
  <img alt = "The app" src = "./.github/stream-data.gif" width = "300px" />
</h1>
