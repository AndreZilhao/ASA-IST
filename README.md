# ASA-IST
Projectos de Algoritmos de Sintese de Dados

# O Problema

Paul Erdos (1913-1996) foi reconhecidamente um dos maiores matemáticos do século XX.
Para além das suas valiosas contribuições em teoria dos conjuntos, teoria dos números ou teoria
dos grafos (entre outras áreas), Erdos ficou conhecido por ser autor de mais de 1500 artigos
científicos. Para tal, Erd ̋os colaborou com mais de 500 outros matemáticos na co-autoria desses
artigos.
Dada a extensão das colaborações de Paul Erdos, tornou-se popular calcular o número de
Erdos dos cientistas. O número de Erdos é definido como sendo a distância colaborativa de
uma pessoa a Paul Erdos. Considera-se que os co-autores de artigos com Paul Erd ̋os estão à
distância de 1. Os co-autores de artigos com co-autores de Paul Erdos estão à distância de 2, e
assim sucessivamente. Considera-se que o número de Erdos de Paul Erdos é 0.

#Input

O ficheiro de entrada deverá conter a informação sobre colaborações entre cientistas. Considera-
se que um cientista colabora com outro se são co-autores de pelo menos um artigo científico. O
input é definido da seguinte forma:

• Uma linha com o número de pessoas N (N ≥ 2) e o número de relações de colaboração C
separados por um espaço em branco.

• Uma linha com o número entre 1 e N que identifica Paul Erdos.

• Uma lista de C linhas, em que cada linha contém dois inteiros u e v (separados por um
espaço em branco) indicando que a pessoa identificada por u tem pelo menos uma co-
autoria com a pessoa identificada por v.

Assume-se que a identificação das pessoas é um inteiro entre 1 e N e que todas as N pessoas
estão a uma distância colaborativa finita de Paul Erdos.

#Output

Suponha que M é o maior valor de número de Erdos que se deduz do input. O programa deverá
escrever no output a seguinte informação:

• Uma linha com o valor M.

• Uma sequência de M linhas em que a linha i (1 ≤ i ≤ M) corresponde ao número de
pessoas com número de Erdos igual a i.

#Exemplos

input 1
8 9
1
12
13
34
42
25
56
67
75
48

output 1
3
2
2
3
2

input 2
8 9
3
12
13
34
42
25
56
67
75
68

output 2
5
2
1
1
2
1
