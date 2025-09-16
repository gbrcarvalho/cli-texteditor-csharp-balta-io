# Editor de Texto - Aplicação CLI

Aplicação CLI de Editor de Texto simples em C#, do curso Fundamentos do C# de André Baltieri

https://balta.io/cursos/fundamentos-csharp

Um editor de texto de console simples escrito em C#, que permite criar, abrir e salvar arquivos de texto. Este projeto foi desenvolvido para exercitar conceitos fundamentais de C# e manipulação de arquivos.

## Funcionalidades

- **Abrir arquivo** - Lê e exibe o conteúdo de arquivos de texto existentes
- **Criar novo arquivo** - Permite escrever texto e salvar em um novo arquivo
- **Menu** - Sistema de navegação simples e direto
- **Operação contínua** - Retorna ao menu principal após cada operação realizada
- **Manipulação de arquivos** - Utiliza StreamReader e StreamWriter para operações de I/O

## Requisitos

- Framework .NET .NET Core/5+
- Compilador C#

## Como executar

1. Compilar:
   ```PowerShell
   PS unidade:\caminho\cli-texteditor-csharp-balta-io> dotnet build
   ```
   
2. Executar:
   ```PowerShell
   PS unidade:\caminho\cli-texteditor-csharp-balta-io> dotnet run
   ```

## Uso

Quando iniciar a aplicação, você verá um menu com as seguintes opções:

```
O que você deseja fazer?
1 - Abrir arquivo
2 - Criar novo arquivo
0 - Sair
```

### Passo a passo:

#### Para abrir um arquivo:

1. Selecione a opção 1
2. Digite o caminho completo do arquivo quando solicitado
3. O conteúdo será exibido na tela
4. Pressione qualquer tecla para retornar ao menu

#### Para criar um novo arquivo:

1. Selecione a opção 2
2. Digite o texto desejado (o texto será inserido linha por linha)
3. Pressione ESC quando terminar de escrever
4. Digite o caminho onde deseja salvar o arquivo
5. O arquivo será salvo e você retornará ao menu principal

#### Para sair:

1. Selecione a opção 0 para encerrar a aplicação

## Licença

Este é um projeto educacional desenvolvido com o intuito de exercitar os conceitos fundamentais do C# relacionados à manipulação de arquivos e interface de console. Sinta-se livre para usar e modificar conforme necessário.
