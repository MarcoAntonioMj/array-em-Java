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
## Inicialização de arrays

- A inicialização de arrays em Java pode ser feita de diversas maneiras, como por exemplo:
```
int[] numeros = {1, 2, 3, 4, 5};
```
- Declarando um array com tamanho fixo e depois atribuindo valores a cada posição:
```
int[] numeros = new int[5];
numeros[0] = 1;
numeros[1] = 2;
numeros[2] = 3;
numeros[3] = 4;
numeros[4] = 5;
```
- Declarando um array com tamanho variável, definido pelo usuário:
```
Scanner input = new Scanner(System.in);
System.out.print("Digite o tamanho do array: ");
int tamanho = input.nextInt();

int[] numeros = new int[tamanho];
for (int i = 0; i < tamanho; i++) {
    System.out.print("Digite o valor para o elemento " + i + ": ");
    numeros[i] = input.nextInt();
}
```
## O acesso a elementos de um array

O acesso a elementos de um array é feito utilizando seu índice, que começa em 0. Por exemplo, para acessar o primeiro elemento de um array numeros, podemos usar numeros[0]. Para acessar o terceiro elemento, podemos usar numeros[2].

A manipulação de arrays pode ser feita de diversas maneiras, como por exemplo:

Alterando o valor de um elemento:

```
numeros[2] = 10;
```
- Copiando um array para outro:
```

int[] numerosCopia = Arrays.copyOf(numeros, numeros.length);
```
- Ordenando os elementos de um array:
```
Arrays.sort(numeros);


```
- Buscando um elemento em um array:
```
int posicao = Arrays.binarySearch(numeros, 3);
```
## A iteração em arrays 
A iteração em arrays pode ser feita utilizando diversas estruturas de repetição, como o for, o while e o foreach. Um exemplo de iteração utilizando o for é o seguinte:
```
for (int i = 0; i < numeros.length; i++) {
    System.out.println("O elemento na posição " + i + " é: " + numeros[i]);
}
```
Um exemplo de iteração utilizando o foreach é o seguinte:
```
for (int num : numeros) {
    System.out.println("O elemento é: " + num);
}
```
Essas são apenas algumas das possibilidades de inicialização, acesso, manipulação e iteração em arrays em Java. Há muitas outras coisas que você pode fazer com arrays em Java, como por exemplo, encontrar o maior e o menor valor em um array, somar todos os elementos de um array, verificar se um array contém um determinado valor e muito mais.

