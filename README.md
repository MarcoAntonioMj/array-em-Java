# Array-em-Java
Repositório para revisar Array e Coleções 
## Declaração de arrays
A declaração de um array em Java é a especificação do tipo de dado que será armazenado no array, seguido pelo nome do array e pelos colchetes que indicam que é um array. A sintaxe básica é a seguinte:
```
tipo[] nomeDoArray;
```
Onde tipo é o tipo de dado que será armazenado no array, e nomeDoArray é o nome que você dá ao array. Por exemplo, se quisermos criar um array de inteiros com o nome numeros, a declaração seria assim:
```
int[] numeros;
```
Também é possível inicializar o array ao mesmo tempo que o declaramos. Para fazer isso, podemos usar a sintaxe a seguir:
```
tipo[] nomeDoArray = {elemento1, elemento2, elemento3, ..., elementoN};
```
Onde elemento1, elemento2, elemento3, ..., elementoN são os valores que queremos armazenar no array. Por exemplo, para criar um array de inteiros chamado notas com os valores 8, 9 e 10, a declaração seria:
```
int[] notas = {8, 9, 10};

```
Também é possível declarar um array de objetos em Java. Nesse caso, a sintaxe seria similar à declaração de um array de qualquer outro tipo, exceto que o tipo seria o nome da classe do objeto que queremos armazenar. Por exemplo, para criar um array de objetos String com o nome palavras, a declaração seria assim:
```
String[] palavras;
```
Depois de declarar um array em Java, é possível acessar e modificar seus elementos usando o índice do elemento desejado, que começa em 0. Por exemplo, para acessar o primeiro elemento do array notas, que é 8, podemos fazer o seguinte:
```
int primeiraNota = notas[0];
```
Para modificar o valor do segundo elemento do array notas, que é 9, podemos fazer o seguinte:
```
notas[1] = 10;
```
