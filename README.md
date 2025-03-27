# Flutter Magic Book

Este guia passo a passo ajudará você a instalar e configurar o Flutter em seu sistema, até criar e rodar seu primeiro aplicativo.

## 1. Instalando o Flutter

### 1.1 Baixando o Flutter SDK

Acesse o site oficial: [Flutter.dev](https://flutter.dev)

Escolha o sistema operacional:

* **Windows:** Baixe o `.zip`
* **MacOS:** Baixe o `.dmg`
* **Linux:** Baixe o `.tar.xz`

### 1.2 Extraindo o SDK

* **Windows:** Extraia o arquivo para `C:\src\flutter` (evite espaços no caminho)
* **MacOS/Linux:** Extraia para um diretório de sua escolha (`/home/usuario/flutter` ou `/Users/usuario/flutter`)

### 1.3 Configurando o PATH

Adicione o caminho do Flutter ao `PATH` do sistema:

#### **Windows:**

Adicione `C:\src\flutter\bin` às variáveis de ambiente.

#### **MacOS/Linux:**

Execute no terminal:

```sh
export PATH="$PATH:/caminho/para/flutter/bin"
```

### 1.4 Verificando a Instalação

Abra um terminal e execute:

```sh
flutter doctor
```

Isso verificará se todos os requisitos estão configurados corretamente.

## 2. Configurando o Ambiente de Desenvolvimento

### 2.1 Instalando o Android Studio (Opcional)

* Baixe e instale o **Android Studio**
* No Android Studio, vá até **Configurações > SDK Manager** e instale o **Android SDK** e o **Flutter Plugin**

### 2.2 Instalando o Visual Studio Code (Alternativa ao Android Studio)

* Baixe e instale o **VS Code**
* Instale a extensão do Flutter no **Marketplace**

### 2.3 Configurando um Emulador

* No Android Studio, acesse **AVD Manager** e crie um dispositivo virtual.
* Inicie o emulador ou conecte um dispositivo físico.

## 3. Criando e Executando seu Primeiro App

### 3.1 Criando um Novo Projeto

Execute no terminal:

```sh
flutter create meu_app
cd meu_app
```

### 3.2 Rodando o Aplicativo

Para rodar no emulador ou dispositivo conectado:

```sh
flutter run
```

## 4. Imagens Ilustrativas

### Baixando o Flutter

![image](https://github.com/user-attachments/assets/69477887-fa3f-4fc1-8f39-0bae9720f6ea)

### Configurando o PATH

Extraia o arquivo do Flutter baixado, coloque a pasta `flutter` na raiz do diretório, copie o caminho da pasta `bin` e adicione como um novo `PATH`.

![image](https://github.com/user-attachments/assets/4e377ded-71e8-4c59-b9c1-da975657a9f1)

### Flutter Doctor

Rode o comando `flutter doctor` no CMD. Depois, vá no seu Android Studio e habilite essas opções.

![image](https://github.com/user-attachments/assets/b541fa9b-0517-46e1-aa56-d534b0c4675b)

Após isso, basta rodar novamente o `flutter doctor` e copiar o comando que ele mandar você rodar e executar.

### Rodando o App

```sh
flutter create "nameapp"
```
