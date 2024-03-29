# Pratica de Operadores e Input/Output
Complete os seguintes códigos. Lembre-se de que os códigos não são necessariamente iguais aos originais.

### Como executar o código
Rodar o seguinte codigo num terminal
```
py ex1.py
``` 

## Exercicio 1: Criar Scratch à partir do código
Apos finalizar os exercicios, escolher algum dos codigos do Exercicio 3 ate 8, e criar uma versao dele no sistema web [SCRATCH](https://scratch.mit.edu) para programação visual
O código-fonte `ex1.py` devera printar o link para o seu projeto scratch como por exemplo:

> #SCRATCH#`XXXXXXX`

Onde:
`XXXXXXX` seria o url do seu projeto

## Exercicio 2: Criar codigo a partir do scratch
Os **bots** são robôs que desempenham tarefas automatizadas pré-definidas, amplamente utilizados em uma série de plataformas e serviços online.
Foi fornecido um [projeto](https://scratch.mit.edu/projects/494279233) no sistema web [SCRATCH](https://scratch.mit.edu), que simula um *bot* de um hospital.

O desafio é visualizar, testar e analisar o [projeto](https://scratch.mit.edu/projects/494279233) para depois simular na linguagem de programação `Python`. Para fazer isso, você precisa fazer alterações no arquivo `ex2.py`.

## Exercicio 3 : Hashmat, o bravo guerreiro
Arquivo a editar e modificar `ex3.py`

### Descrição

Hashmat é um bravo guerreiro que com seu grupo de jovens soldados se move de um lugar para outro para lutar contra seus oponentes. Antes de lutar, ele apenas calcula uma coisa, `a diferença entre seu número de soldado e o número de soldado do oponente`. A partir dessa diferença, ele decide se luta ou não. O número de soldado de Hashmat nunca é maior do que seu oponente.

### Input
A primeira linha do arquivo de entrada é um inteiro **t** que denota quantos conjuntos de entradas existem. Cada uma das próximas **t** linhas contém `dois números em cada linha`. Esses dois números em cada linha denotam, primeiro o número de soldados no exército de seu oponente e em segundo lugar o número de soldados no exército de Hashmat.

### Output

Para cada linha de entrada, imprima a `diferença de número de soldados entre o exército de Hashmat e o exército de seu oponente`. Cada saída deve estar em linha separada.

### Sample Input
```
3
10 12
10 14
100 200
```

### Sample Output
```
2
4
100
```
[arquivo original UVA](https://onlinejudge.org/index.php?option=onlinejudge&Itemid=8&page=show_problem&problem=996)

## Exercicio 4 : Resposta Automática
Arquivo a editar e modificar `ex4.py`

### Descrição
No mês passado, Alice despreocupadamente inseriu seu nome em um sorteio de um *Tapmaster 4000*. Ao verificar seu e-mail hoje, ela encontrou uma carta que dizia:
*“Parabéns, Alice! Você ganhou um Tapmaster 4000. Para reclamar seu prêmio, você deve responder à seguinte pergunta de teste de habilidade. ”*

Os sentimentos iniciais de surpresa e alegria de Alice transformaram-se rapidamente em desânimo. Seu recorde de vida para perguntas de teste de habilidade é abismal 3 certos e 42 errados.

A Mad Skills, empresa líder no desenvolvimento de perguntas para teste de habilidade, foi contratada para fornecer perguntas para teste de habilidade para este sorteio *Tapmaster 4000* em particular. Eles decidiram criar uma pergunta de teste de habilidade diferente para cada vencedor, de forma que os vencedores não pudessem colaborar para responder à pergunta.

Você pode ajudar Alice a ganhar o *Tapmaster 4000* resolvendo a questão do teste de habilidade?

### Input
A primeira linha do arquivo de entrada é um inteiro **t** que denota número de casos de teste. Cada caso de teste contém um inteiro **n** `(−1000 ≤ n ≤ 1000)` em cada linha. Este **n** deve ser substituído na pergunta do teste de habilidade abaixo.

### Output
Para cada caso de teste, produza a resposta para a seguinte pergunta do teste de habilidade em uma linha por si só:
*“Multiplique **n** por 567, depois divida o resultado por 9, some 7492, multiplique por 235, divida por 47 e subtraia 498. `Qual é o dígito na coluna das dezenas?`”*


### Sample Input
```
2
637
-120
```

### Sample Output
```
1
3
```
[arquivo original UVA](https://onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=2542)

## Exercicio 5 : Voltar para a Física do Ensino Médio
Arquivo a editar e modificar `ex5.py`

### Descrição
Uma partícula tem velocidade e aceleração iniciais. Se sua velocidade após certo tempo for **v**, então `qual será seu deslocamento no dobro desse tempo?`

### Input
A primeira linha do arquivo de entrada é um inteiro **t** que denota número de casos de teste. Cada caso de teste contém dois inteiros em cada linha. Esses dois inteiros denotam o valor de **v** (−100 ≤ v ≤ 100) e **t** (0 ≤ t ≤ 200) (**t** seria no tempo em que a partícula ganha aquela velocidade)

### Output
Para cada linha de entrada imprima um único inteiro em uma linha denotando `o deslocamento em dobro daquele tempo`.

### Sample Input
```
2
0 0
5 12
```

### Sample Output
```
0
120
```
[arquivo original UVA](https://onlinejudge.org/external/100/p10071.pdf)

## Exercicio 6: Medindo tabuas
Arquivo a editar e modificar `ex6.py`

### Descrição
Uma turma da facultade resolveu medir um conjunto de tabuas que estavam abanadas numa sala. Para isso, os estudantes registravam as medidas de cada lado da tabua. Maria que tinha chegado tarde, por castigo, teve que calcular tanto o perimetro quanto a area de cada uma das tabuas. Você pode ajudar Maria com essa tarefa?


### Input
A primeira linha do arquivo de entrada é um inteiro **t** que denota número de casos de teste. Cada caso de teste contém dois flotantes em cada linha. Esses dois valores denotam o valor de **a** e **b**. 

### Output
Para cada linha de entrada imprima dois floats com um decimal em uma linha denotando primeiro a area e segundo o perimetro.

### Sample Input
```
2
1 2
1.3 6.7

```

### Sample Output
```
2.0 6.0
8.7 16.0

```
