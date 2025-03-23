O conjunto é uma noção primitiva, normalmente entendido como uma coleção de elementos.

Os elementos de um conjunto podem ser listados dentro de pares de chaves, como:

A = {1, 2, 3, 4}

Também existe o conjunto vazio, ao qual nenhum elemento participa.

**Ø = {}**

## Diagrama de Venn-Euler

O diagrama de Venn-Euler representa visualmente vários conjuntos, evidenciando seus elementos comuns e os elementos exclusivos, isto é, aqueles que pertencem somente a um dos conjuntos.

O conjunto universo corresponde ao conjunto de todos os elementos de uma amostra ou pesquisa.

Por exemplo, suponha que foi feito a seguinte pesquisa com 100 pessoas:

- 30 Gostam apenas de português
- 22 Gostam apenas de matemática
- 28 gostam de ambas
- 20 não gostam de nenhuma delas.

Podemos representar essa situação no seguinte diagrama:


[[Drawing 2025-03-22 10.30.47.excalidraw]]
Nesse diagrama, podemos ainda obter informações adicionais:

O conjunto universo é de 100 pessoas

58 pessoas gostam de português

50 gostam de matemática

a

## Operações lógicas nos conjuntos

### Conjunto complementar

O conjunto complementar de A é composto pelos elementos do conjunto universal que não pertencem ao conjunto A. As duas representações matemáticas mais comuns são _ e _ .

Em termos lógicos, o conjunto complementar se relaciona com o operador NÃO. O conjunto complementar _ e _ pode ser entendido como não A.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/cea04e11-3959-4830-8c67-ff55a70e997f/d4c4a9c3-0936-45eb-b3c3-cedcde45d413/image.png)

Uma propriedade interessante dos conjuntos complementares é que eles seguem leis semelhantes às leis De Morgan, isto é:

- O complementar da união é a intersecção dos complementares
    - $(A ⋃ B)^c = (A^c ⋂ B^c)$
- O complementar da intersecção é a união dos complementares.
    - $(A ⋂ B)^c = (A^c⋃B^c)$

### Intersecção

É associada à palavra E. A intersecção de dois conjuntos corresponde aos elementos que pertencem a todos eles simultaneamente.

Por exemplo, considere os conjuntos:

A = {1, 3, 5, 7, 9}

B = {0, 3, 6, 9, 12}

A intersecção entre eles corresponde ao conjunto A∩B = {3, 9}.

Em termos de raciocínio verbal, a intersecção é associada à expressão “Algum B é A”.

É interessante citar que existem dois casos particulares em que as intersecções são chamadas de subconjuntos. Quando dizemos “Algum B é A”, não podemos excluir as possibilidades que um esteja incluso em outro.

### Diferença de dois conjuntos

A diferença entre os conjuntos A e B, representada por A - B ou por A\B, é composta pelos elementos de A que não pertencem a B.

Por exemplo, considere os seguintes conjuntos:

- A = {1, 3, 5, 7, 9} • B = {0, 3, 6, 9, 12}

A diferença entre os dois são dadas por:

A\ B = {1, 5, 7}

B\A = {0, 6, 12}

É interessante notar que é possível calcular tanto a diferença A\B como a diferença B-A. Perceba que os conjuntos A\**B e B**\A são disjuntos, ou seja, não possuem nenhum elemento em comum.

### União

A união ou reunião é normalmente associada à palavra OU. A união de dois conjuntos corresponde aos elementos que pertencem a qualquer um deles. Considere o seguinte exemplo. • A = {1, 3, 5, 7, 9} • B = {0, 3, 6, 9, 12}

A união entre eles, corresponde ao conjunto:

{0, 1, 3, 5, 6, 7, 9, 12}