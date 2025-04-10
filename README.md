## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## Tipos primitivos ( Primitive Types ).

No Java existem algumas palavras reservadas para a representação dos tipos de dados básicos que precisam ser manipulados para a construção de programas. Esses tipos de dados são conhecidos como tipos primitivos ( Primitive Types ).

Eles são os seguintes.
byte, short, int, long, float, double, char e boolean, esses tipos não são considerados objetos. Eles são armazenados diretamente na pilha de memória, ( Memory stack).

# Dio-Trilha-Java-B-sico
Início java básico.
Tipos de variáveis.
Os oito tipos primitivos em Java.

🔢 **Inteiros (sem casas decimais).**
| Tipo  | Uso Memória | Tamanho  | Valor Mínimo       | Valor Máximo       |
|-------|-------------|----------|--------------------|--------------------|
| byte  |    1 byte   | 8 bits   | -128               | 127                | 

Obs: Com os computadores modernos, se tornou desnecessário utilizar os tipos short e byte, pois não precisamos nos preocupar tanto assim com o espaço de memória reduzido.

| short |    2 byte   | 16 bits  | -32.768            | 32.767             |
| int   |    4 byte   | 32 bits  | -2³¹ (-2.147.483.648) | 2³¹-1 (2.147.483.647) | 

Obs: Int é o mais utilizado para representar números inteiros.

| long  |    5 byte   |64 bits   | -2⁶³               | 2⁶³-1              |

Da mesma forma, dificilmente utilizaremos o tipo long, pois não é tão comum trabalharmos com valores tão grandes.

🔣 **Decimais (com casas decimais) ou Seja são do tipo fracionário.**
|  Tipo  |  Tamanho  |  Precisão                 |
|--------|-----------|---------------------------|
|  float |   32 bits |  ~ 6 - 7 Dígitos decimais | 

Obs: sempre no final de qualquer valor que seja do tipo float colocar F ou f e long coloacar o L ou l.

Obs: Apesar de o tipo float ocupar metade da memória consumida do que o tipo double, ele e menos utilizado. Ele só mantém uma precisão decimal entre 6 e 7 dígitos.

| double |  64 bits  |  ~ 15    Dígitos decimais | 

🔡 **Outros Tipos Primitivos.**
| Tipo    | Descrição                              | Exemplo       |
|---------|----------------------------------------|---------------|
| char    | Um único caractere Unicode (16 bits)   | 'A', '1', '#' |
| boolean | Representa `true` ou `false` (lógico)  | true, false   |



OBS: String não é primitivo, é um objeto.


**Declaração de Variáveis**

Variável é uma identificação d um espaço em memória utilizado pelo nosso programa. Toda variável é composta por: tipo de dados + identificação + valor atribuído.  
Ex:
<Tipo> <nomeVariável> <atribuiçãoDeValorOpcional>
<int> <idade> = <45>

public class TiposDeVariaveis {
    public static void main(String[] args) throws Exception {
        double PI = 3.1415;
        System.out.print(PI); 
        
        // Quando o nome da variável está em caixa alta o valor não pode ser alterado.
       //  Nesse exemplo PI está escrito em caixa alta.
    }
}







