# 📱 Projeto React Native - Rick and Morty API

Este é um aplicativo desenvolvido em **React Native**, utilizando a CLI oficial [`@react-native-community/cli`](https://github.com/react-native-community/cli), como parte de uma atividade avaliativa do 4º semestre do curso de **Desenvolvimento de Software Multiplataforma (DSM)** da **Fatec Franca**.

O app consome uma **API pública do Rick and Morty** para exibir informações detalhadas de personagens por nome ou ID.

Desenvolvido por **Felipe Ferreira** e **Cláudio Matos**.

---

## 🚀 Funcionalidades

- 🔍 Busca de personagens por **nome ou ID**
- 📄 Exibição de informações detalhadas: nome, espécie, status, origem e imagem
- ⚛️ Consumo de API REST com **axios**
- 📱 Interface desenvolvida para **Android** via emulador ou dispositivo físico

---

## ⚙️ Requisitos

Antes de iniciar, certifique-se de ter:

- **Node.js** instalado (versão recomendada: 14 ou superior)
- **npm** ou **Yarn**
- **Android Studio** com um emulador configurado
- Ambiente React Native configurado ([guia oficial](https://reactnative.dev/docs/environment-setup))

---

## 📦 Instalação

1. **Clone o repositório**:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio
```

2. **Acesse a pasta do projeto**:

```bash
cd nome-do-repositorio
```

3. **Instale as dependências**:

```bash
# com npm
npm install

# ou com yarn
yarn install
```

---

## ▶️ Executando o Projeto

### 1. Inicie o Emulador Android

Antes de iniciar o projeto, **abra o Android Studio** e **inicie manualmente um emulador Android** ou conecte um dispositivo físico com depuração USB ativada.

### 2. Inicie o Metro Bundler

Abra um terminal na raiz do projeto e rode:

```bash
npm start
# ou
yarn start
```

Deixe essa aba do terminal aberta.

### 3. Em outro terminal, execute o app em um emulador Android

```bash
npm run android
# ou
yarn android
```

Se tudo estiver corretamente configurado, o app será exibido no emulador ou dispositivo físico.

---

## 🧪 Como Usar

1. Abra o app
2. Faça o login
3. Digite o nome ou ID de um personagem
4. Veja as informações retornadas pela API do Rick and Morty

---

## 📚 Dependências Principais

| 📦 Pacote                                | 📌 Descrição                                               |
|------------------------------------------|------------------------------------------------------------|
| `react-native`                           | Framework para desenvolvimento mobile multiplataforma      |
| `@react-native-community/cli`            | CLI oficial para criação e manutenção de apps React Native |
| `axios`                                  | Cliente HTTP para consumo de APIs                          |
| `react-navigation`                       | Navegação entre telas no React Native                      |
| `@react-navigation/native`               | Navegação declarativa entre componentes                    |
| `react-native-reanimated`                | Biblioteca de animações fluidas                            |


