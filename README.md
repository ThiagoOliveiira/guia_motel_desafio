# 📌 Guia Motéis - Desafio vaga

## 📖 Sobre o Projeto
Este é um aplicativo  **Guia Motéis** desenvolvido em **Flutter**, utilizando a arquitetura **MVVM + Clean Architecture** para garantir organização, escalabilidade e separação de responsabilidades.


### 🔹 Screenshot e video de demonstração

https://github.com/user-attachments/assets/9ce5dc39-8b20-4d85-b805-125fd6a4239f

<p align="left">
   <img src = "/assets/screenshot/home_guia_motel.png" alt="Home do App" width = "200" />
   <img src = "/assets/screenshot/home_guia_motel_2.png" alt="Home do App" width = "200" />
</p>


## 🚀 Como Executar o Projeto

### 🔹 Pré-requisitos
Antes de executar o projeto, certifique-se de ter:
- Flutter instalado ([Download Flutter](https://flutter.dev/docs/get-started/install))
- Dart SDK atualizado
- Dependências do projeto instaladas
 
   Utilizar a versão 3.29.0 do Flutter
   
   ```bash
   flutter pub get
   flutter run
   ```

### 🔹 Passos para rodar
1. Clone o repositório:
   ```sh
   git clone https://github.com/ThiagoOliveiira/guia_motel_desafio.git
   cd guia_moteis
   ```
2. Instale as dependências:
   ```sh
   flutter pub get
   ```
3. Execute o aplicativo:
   ```sh
   flutter run
   ```

## 🏗️ Estrutura do Projeto
A arquitetura segue o **MVVM + Clean Architecture**, garantindo separação de camadas e reutilização de código.

```
lib/
├── core/               # Camada central com classes auxiliares e de erro
│   ├── error/         # Camada de tratamento de erros
│   ├── network/        #  
│
├── data/               # Camada de dados (Repositórios e Models)
│   ├── datasources/   # Fonte de dados da API
│   ├── models/        # Modelos dos dados
│   ├── repositories/  # Implementação dos repositórios
│
├── domain/             # Camada de domínio (Regras de negócio)
│   ├── entities/      # Entidades principais do app
│   ├── repositories/  # Contratos dos repositórios
│   ├── usecases/      # Casos de uso do aplicativo
│
├── presentation/       # Camada de apresentação (UI e lógica da interface)
│   ├── viewmodel/     # Gerenciamento de estado com Cubit
│   ├── views/         # Telas do aplicativo
│   ├── widgets/       # Componentes reutilizáveis
│
│── │── main.dart      # Ponto de entrada do aplicativo
|    
|── |── injection_container.dart   # Injeção de dependência com GetIt.
│
```

## 🔹 Funcionalidades
- ✅ Listar os moteis disponiveis no endpoint disponibilizado ✅
- ✅ Arquitetura modular **MVVM + Clean Architecture** ✅
- ✅ Gerenciamento de estado com **Cubit** ✅

## 📚 Tecnologias Utilizadas
- **Flutter**: Framework principal
- **Dart**: Linguagem de programação
- **GetIt**: Injeção de depêndencia
- **Cubit (Bloc)**: Gerenciamento de estado

---
🚀 **Agora é só rodar o projeto e começar a usar!** 🚀

#
