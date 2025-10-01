<h1 align="center"> DIO | Resumo Operadores no C# </h1>

Repositório para armazenar resumos das aulas do [bootcamp da DIO sobre .NET](https://web.dio.me/track/avanade-back-end-com-net-e-ia).

- [Documentação C#](https://learn.microsoft.com/pt-br/dotnet/csharp/).

## 📙 Operador de Atribuição
|Codigo|Explicação|
|------|----------|
|`=`|Usado para atribuir valores a variáveis|

## 📙 Operadores Aritméticos
### Ordem dos operadores
1. ()
2. Math.Pow() - exponenciação
3. *, /, %
4. +, -

### Combinando tipos de operadores
```
int c = 25;

//Caso eu queira atribuir mais 5 a essa variável, posso fazer de duas formas:

c = c + 5;
c += 5;

//Isso funciona para os demais operadores aritiméticos
```

## 📙 Convertendo tipos de variáveis - cast/casting
### Const e Parse
```
int a = convert.toInt32("5");
ou
int a = int.Parse("5');

Console.WriteLine(a);

//A diferença está no tratamento de valores null, o convert vai devolver 0 e o Parse vai devolver um erro
```
#### TryParse
```
String a = "15-";
int b = 0;

int c = int.TryParse(a, out b);

Console.WriteLine(c);
```
### Convertendo string
```
//Posso converter string assim:

int inteiro = 5;
string a = inteiro.toString;

Console.WriteLine();
```
### Cast Implícito
```
int a = 5;
double b = a;

//Os valores de double cabe números maiores que o int, então o int cabe no double. O contrário não é verdade.
```
## 📙 Oeradores condicionais
|Operador|Significado|
|--------|-----------|
|`==`|Igual|
|`>`|Maior|
|`<`|Menor|
|`>=`|Maior ou igual|
|`<=`|Menor ou igual|
|`!=`|Diferente|

## 📙 Oeradores Lógicos
|Operador|Significado|
|--------|-----------|
|`&&`|And|
|`||`|Or|
|`!`|Not|
