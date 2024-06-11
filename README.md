# Projeto CRUD de Séries de TV

Este é o seu primeiro projeto em C# utilizando .NET, que implementa um sistema CRUD (Create, Read, Update, Delete) em memória para gerenciar séries de TV.

## Funcionalidades

- **Adicionar Série**: Permite adicionar uma nova série ao sistema.
- **Listar Séries**: Exibe uma lista de todas as séries cadastradas.
- **Atualizar Série**: Permite atualizar os dados de uma série existente.
- **Excluir Série**: Permite excluir uma série do sistema.
- **Visualizar Série**: Exibe os detalhes de uma série específica.

## Tecnologias Utilizadas

- [C#](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [.NET](https://dotnet.microsoft.com/)

## Pré-requisitos

- [.NET SDK](https://dotnet.microsoft.com/download) instalado

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/gabrielcamurcab/series-dotnet.
   ```

2. Navegue até o diretório do projeto:

    ```bash
    cd series-dotnet
    ```

3. Restaure as dependências do projeto:
   ```bash
   dotnet restore
   ```

4. Compile o projeto:
   ```bash
   dotnet build
   ```

5. Execute o projeto:
   ```bash
   dotnet run
   ```

## Estrutura do Projeto

- **Program.cs**: Ponto de entrada do programa.
- **Série.cs**: Classe que representa uma série de TV.
- **SrieRepositorio.cs**: Classe que gerencia o armazenamento e manipulação das séries.
- **EntidadeBase.cs**: Classe base para entidades, contendo o ID.
- **IRepositorio.cs**: Interface para o repositório de séries.

## Como Usar

Ao executar o projeto, você verá um menu no console com as opções disponíveis:

1. **Listar séries**: Exibe uma lista de todas as séries cadastradas.
2. **Inserir nova série**: Permite adicionar uma nova série.
3. **Atualizar série**: Permite atualizar os dados de uma série existente.
4. **Excluir série**: Permite excluir uma série do sistema.
5. **Visualizar série**: Exibe os detalhes de uma série específica.
6. **Limpar Tela**: Limpa o console.
7. **Sair**: Encerra a execução do programa.

Siga as instruções do menu para gerenciar suas séries de TV.

## Exemplo de Uso

### Adicionar uma Nova Série

1. Selecione a opção "2 - Inserir nova série".
2. Siga as instruções para inserir o gênero, título, ano de início e descrição da série.

### Listar Séries

1. Selecione a opção "1 - Listar séries" para ver todas as séries cadastradas.

### Atualizar uma Série

1. Selecione a opção "3 - Atualizar série".
2. Insira o ID da série que deseja atualizar.
3. Siga as instruções para atualizar as informações da série.

### Excluir uma Série

1. Selecione a opção "4 - Excluir série".
2. Insira o ID da série que deseja excluir.

### Visualizar uma Série

1. Selecione a opção "5 - Visualizar série".
2. Insira o ID da série que deseja visualizar.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

Para mais informações, entre em contato com [projetosdocamurca@gmail.com](mailto:projetosdocamurca@gmail.com).
