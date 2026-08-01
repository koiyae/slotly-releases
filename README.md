<p align="center">
  <img
    src="https://github.com/user-attachments/assets/aa3f2112-2cb9-4355-903e-94519f14ccc9"
    alt="Logo do Slotly"
    width="300"
  >
</p>
O **Slotly** é um aplicativo Android para gerenciamento de disponibilidade e agendamento de horários entre clientes e prestadores de serviço.

Este repositório contém o APK e demonstrações em vídeo do aplicativo em funcionamento.

## Principais funcionalidades

- Cadastro e autenticação de usuários
- Perfis de cliente e prestador de serviço
- Configuração de horários disponíveis
- Agendamento de serviços
- Cancelamento e acompanhamento de agendamentos
- Persistência de dados com Firebase
- Interface moderna desenvolvida com Jetpack Compose

## Demonstração
https://github.com/user-attachments/assets/f58de7e1-1aa1-4409-a9f1-1276c0af3b1f

https://github.com/user-attachments/assets/6482845d-29df-47c2-abc3-a4fa069751c5

## Baixar o aplicativo

A versão mais recente do APK está disponível na página de releases:

[Baixar Slotly APK](https://github.com/koiyae/slotly-releases/releases/tag/1.0)

## Requisitos

- Android 8.0 ou superior
- Conexão com a internet
- Permissão para instalar APKs externos

### Como instalar

1. Baixe o arquivo `.apk`.
2. Abra o arquivo no dispositivo Android.
3. Caso solicitado, autorize a instalação de aplicativos de fontes desconhecidas.
4. Conclua a instalação e abra o Slotly.

> O APK é disponibilizado exclusivamente para demonstração e testes.

## Tecnologias utilizadas

### Aplicativo Android

- **Kotlin** — linguagem principal do projeto
- **Jetpack Compose** — construção declarativa das interfaces
- **Material Design 3** — componentes e identidade visual
- **Compose Navigation** — navegação entre telas com rotas tipadas
- **Kotlin Serialization** — serialização das rotas de navegação
- **AndroidX Lifecycle** — gerenciamento do ciclo de vida
- **ViewModel** — gerenciamento de estado e lógica das telas
- **StateFlow e Coroutines** — estados reativos e operações assíncronas
- **Android Credential Manager** — gerenciamento moderno de credenciais
- **Google Identity Services** — autenticação com conta Google
- **Android Location APIs** — obtenção e tratamento da localização do usuário
- **GeoFire** — consultas e cálculos relacionados à localização geográfica

### Backend e persistência

- **Firebase Authentication** — cadastro, login e gerenciamento de sessões
- **Cloud Firestore** — armazenamento de usuários, serviços, disponibilidades e agendamentos
- **Firestore Security Rules** — autorização, validação e proteção dos dados
- **Firebase Local Emulator Suite** — testes locais das regras de segurança
- **Firebase BoM** — gerenciamento compatível das versões das bibliotecas Firebase

### Arquitetura e organização

- **MVVM (Model–View–ViewModel)** — separação entre interface, estado e lógica
- **Repository Pattern** — isolamento do acesso ao Firebase e outras fontes de dados
- **Domain Models** — representação das regras e entidades do negócio
- **Unidirectional Data Flow** — estado direcionado do ViewModel para a interface
- **Componentização com Compose** — componentes reutilizáveis e telas desacopladas
- **Separação por camadas** — organização entre `data`, `domain` e `ui`

### Testes e qualidade de código

- **JUnit 4** — testes unitários
- **Compose UI Test** — testes da interface construída com Compose
- **AndroidX Test** — infraestrutura de testes instrumentados
- **Espresso** — testes de interação no Android
- **Firebase Rules Unit Testing** — testes automatizados das regras do Firestore
- **Detekt** — análise estática e padronização do código Kotlin

### Build e ferramentas

- **Gradle com Kotlin DSL** — configuração e automação do build
- **Gradle Version Catalog** — gerenciamento centralizado das dependências
- **Android Gradle Plugin**
- **Jetpack Compose BoM** — compatibilidade entre bibliotecas Compose
- **Android Studio**
- **Git e GitHub** — versionamento e hospedagem do projeto

## Sobre o projeto

O Slotly foi desenvolvido como um projeto Android nativo, com foco em:

- Componentização da interface
- Navegação tipada
- Separação entre UI e acesso a dados
- Segurança das operações no Firestore
- Experiência simples para clientes e prestadores

## Autor

Desenvolvido por **koiyae**.

- [GitHub](https://github.com/koiyae)
- [LinkedIn](https://www.linkedin.com/in/brunosimoes1/)


