<h1 align="center">Ignite React Native - IgniteGym</h1>

<p align="center">
  <img 
    src="https://img.shields.io/badge/React Native-%5E0.71.8-blue" 
    alt="React Native Ver. ^0.71.8"
  />
  <img 
    src="https://img.shields.io/badge/Typescript-%5E5.0.4-blue"
    alt="Typescript Ver. 5.0.4" 
  />
   <img 
    src="https://img.shields.io/badge/Expo-%5E48.0.6-black" 
    alt="Expo Ver. ^48.0.6"
  />
  <img
    src="https://img.shields.io/badge/Ignite-2023-green" 
    alt="Ignite-2023"
  />
  <img 
    alt="License"
    src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033"
  />
</p>

<div align="center">

  ![Last commit](https://img.shields.io/github/last-commit/Jonathan-Rios/ignite-n-react-native-ignite-gym?color=4DA1CD 'Last commit') &nbsp;
  ![Repo size](https://img.shields.io/github/repo-size/Jonathan-Rios/ignite-n-react-native-ignite-gym?color=4DA1CD 'Repo size') &nbsp;
  ![Languages](https://img.shields.io/github/languages/count/Jonathan-Rios/ignite-n-react-native-ignite-gym?color=4DA1CD 'Languages') &nbsp;

</div>


<br>

<h3 align="center">Imagem prévia da aplicação</h3>

<div align="center">
  <img src=".github/project-preview.gif?style=flat" alt="Cover" width="310" height="650">
</div>
 
<br>

## 💻 Projeto
Descrição do projeto:
Essa aplicação foi desenvolvida para estudos seguindo os ensinamentos da **[Rocketseat](https://www.rocketseat.com.br/)** no curso Ignite **[Ignite](https://www.rocketseat.com.br/ignite)** .

Esse projeto consta uma aplicação mais completa contendo:
* Criação e Autenticação de usuários
* Fila de requisição para refresh token
* Upload de Imagem com edição básica
* Consumo de API
* Navegação com ReactNavigation StackNavigation e BottomTabsNavigation
* Armazenamento/Gerenciamento de dados localmente com AsyncStorage
* Tratamento de erros

Já que o foco desse projeto era o desenvolvimento da aplicação em React Native, foi fornecido um servidor Node pelo curso, o qual consta nessa pasta "api".
  
 
## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [ReactNative](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.dev/)
- [NativeBase](https://nativebase.io/)

## 🚀 Como executar

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone https://github.com/Jonathan-Rios/ignite-n-react-native-ignite-gym.git

$ cd ignite-n-react-native-ignite-gym
```

Encontrará duas pastas mobile e api, sendo a mobile a aplicação e a api o servidor disponibilizado na aula.
Será necessário os dois para o funcionamento.

Para iniciar o mobile, siga os passos abaixo:

Será necessário para iniciar que tenha instalado o [Expo CLI](https://docs.expo.dev/get-started/installation/)
 
```bash
# Acesse a pasta da aplicação
$ cd mobile

# Instalar as dependências
$ expo install

# Iniciar o projeto
$ expo start

# Será informado um IP (o da sua máquina) pelo expo, vamos precisar dele para substituir no arquivo
# "ignite-n-react-native-ignite-gym/mobile/src/services/api.ts" para se comunicar com o servidor.
```
Para rodar o servidor(API)
 
```bash
# Estando na pasta ignite-n-react-native-ignite-gym
# Acesse a pasta do servidor
$ cd api

# Instalar as dependências
$ npm install

# Iniciar o servidor
$ npm run dev
```


## 📝 License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE.md) para mais detalhes.

<br />


## 📓 Anotações pessoais

<h3>Comandos utilizados</h3>

```bash
  ➜ npx create-expo-app ignitegym --template
  ✔ Choose a template: › Blank (TypeScript)

  # Utilizado para fazer o mapeamento das pastas
  ➜ npm install -D babel-plugin-module-resolver
  # Instalados, configuramos os arquivos ( babel.config.js e tsconfig.json)

  # Como instalar fontes pelo Expo
  ➜ expo install expo-font @expo-google-fonts/roboto
  
  ➜ npm install native-base #Framework bem utilizado no mundo react native
  ➜ expo install react-native-svg@12.1.1 #Diferente da web, react native precisa de suporte para svg
  ➜ expo install react-native-safe-area-context@3.3.2

  # Permite manipular SVG como um componente
  ➜ npm install -D react-native-svg-transformer # É necessário as configurações do arquivo (metro.config.js)
  # Atenção: se o SVG que quer manipular houver alguma cor predefinida dentro dele, ele vai obedecer a cor predefinida.

  #Pare a aplicação e feche os apps no emulador (essa dependência mexe com o código nativo, pode gerar dores de cabeça)
  ➜ npm install @react-navigation/native
  ➜ expo install react-native-screens react-native-safe-area-context #O Safe area já foi instalado, deixei por ser dependência do navigation
  
  ➜ npm install @react-navigation/native-stack # Navegação de "pilha"
  ➜ npm install @react-navigation/bottom-tabs # Navegação menu inferior

  ➜ expo install expo-image-picker # Precisa das configurações no arquivo (app.json)
  ➜ expo install expo-file-system # Utilizamos para conseguir pegar informações como o tamanho de um arquivo.

  ➜ npm install react-hook-form
  ➜ npm install @hookform/resolvers
  ➜ npm install yup
  ➜ npm install axios
  ➜ expo install @react-native-async-storage/async-storage

```
 
---
<br />


<a href="https://github.com/Jonathan-Rios">
 <img src="https://github.com/Jonathan-Rios.png" width="100px;" alt="" style="border-radius:50%" />
 <br />
 <sub><b>Jonathan Rios Sousa</b></sub></a>

💠 NeverStopLearning 💠
 

[![Linkedin Badge](https://img.shields.io/badge/-Jonathan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/)](https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/) 
[![Gmail Badge](https://img.shields.io/badge/-jonathan.riosousa@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jonathan.riosousa@gmail.com)](mailto:jonathan.riosousa@gmail.com)