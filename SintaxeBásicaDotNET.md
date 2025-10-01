<h1 align="center"> DIO | Resumo .NET </h1>

Repositório para armazenar resumos das aulas do [bootcamp da DIO sobre .NET](https://web.dio.me/track/avanade-back-end-com-net-e-ia).

## 📙 Sintaxe Bãsica do C#

- [Documentação C#](https://learn.microsoft.com/pt-br/dotnet/csharp/).

### Criação
|Codigo|Explicação|
|------|----------|
|`dotnet new console`|Cria um novo arquivo|
|`dotnet build`|Copila o projeto, transforma seu código em um conjunto de binários|

### Abstração
```
Mundo Real ----------> Representação no programa
                          │
                          ├── criar a classe ----> molde do objeto
                          │              │
                          │              ├── propriedades
                          │              └── métodos
                          │
                          └── depois eu uso o molde para concretizar meu objeto
```

### Convenções e sintaxe
- Todo nome de classe tem que começar com maiúsculo
- Só pode usar palavras reservadas colocando @ antes delas. [Ex.: @if]
- `/n` --> quebra linha
- no c# usa-se camelCase e PascalCase:
   - PascalCase
   - Classes
   - Propriedades
   - Métodos
- camelCase
   - Variáveis
- Não se abrevia nome de propriedade, variável e classe
- Nome do arquivo = nome da classe
- Não pode caractere especial em variável (com exceção do _ )

### Tipos importantes
- string
- char
- bool
- int
- long
- decimal
- double
- float
- DateTime

