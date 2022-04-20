# Introdução ao Portugol
## Aprenda como utilizar uma estrutura de repetição
### Objetivo da aula
- Aprender o que é uma estrutura de repetição e como utiliza-la.

### Definição 
Dentro de lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou um contador.

---
## O que são linguagens de programação?
### Objetivo da Aula
- Aprender o que são linguagens de programação
- Introdução ao Portugol (utilizando pseudocódigos na prática)

### Definição
Liguagem de Programação é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (Software). Um software pode ser desenvolvido para rodar em um computador, dipositivo móvel ou em qualquer equipamento que permita sua execução.

O que é óbvio para você, certamento não é óbvio para uma máquina. E se você quer que a máquina faça algo para você, vocẽ precisa, "Falar com ela".

> A Função das linguagens de programação é servir de um meio de comunicação entre computadores e humanos.

### Baixo nível e Alto nível

- **Alto nível**\
Essas são aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem de máquina.

- **Baixo nível**\
É aquela que se aproxima mais da linguagem de máquina. Essas são as que você precisa ter o conhecimento direto da arquitetura do computador para fazer alguma coisa.

### Compiladas e Interpretadas
- **Compiladas**\
É uma linguagem de programação em que o código fonte, é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação.
- **Interpretadas**\
É uma linguagem de programação em que o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador.

### O que é Portugol?
Portugol é uma pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independentemente de linguagem de programação.

É uma pseudoliguagem que permite ao programador pensar no problema em si e não no equipamento que irá executar o algoritmo.


WEB IDE PORTUGOL: <https://portugol-webstudio.cubos.io/ide/>

---
## Aprenda a utilizar desvios condicionais e boas praticas em programação
### Objetivos da aula
- Aprender a utilizar os desvios condicionais (estrutura de decisão) no portugol
- Boas práticas de programação - comentários no código

### Desvio condicional - SE
É utilizada a palavra reservada `se`, a condição a ser testada entre parenteses e as instruções que devem ser executadas entre chaves caso o desvio seja `verdadeiro`

**EXEMPLO**

```bash
se(media >= 7){
    escreva("parabéns!! Vocẽ foi aprovado!!")
}
```

### SE-SENAO
Agora vamos imaginar que se a condição for `falsa` um outro conjunto de comandos deve ser executado. Quando iremos encontrar esta situação?

```bash
se(media >= 7 ){
    escreva("parabéns!! Você foi aprovado!!")
}
senao{
    escreva("Infelizmente você foi reprovado")
}
```

### CASO
Este comando é similar aos comandos `se` e `senao`, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o `se`, ele possue algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.

**EXEMPLO**
```bash
inteiro valor = 0
escolha(valor){
    caso 1:
    escreva("Ok! Abrir Netflix!!")
    pare

    caso 2:
    escreva("Ok! Abrir Amazon Prime!!")
    pare

    caso 3:
    escreva("Ok! Abrir HBO Max!!")
    pare

    caso contrario:
    escreva("você deve esconher as opções 1, 2 ou 3")
}

```
---

## Trabalhando com laços de repetição em Portugol
### Objetivo da Aula
- Aprender a utilizar laços de repetição no portugol

### Definição
Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou um contador.

---
## Aplicação prática com matrizes e vetores
### Objetivo da Aula
- Entender o que é uma matriz e um vetor e entender a sua aplicação prática.
### Definição
Uma matriz é uma coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados continuamente na memória.\
A individualização de cada variável de um vetor é feita através do uso de índices.\
Os Vetores são matrizes de uma só dimensão.

[Back :leftwards_arrow_with_hook:](../README.md)
