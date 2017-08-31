## Programação Orientada a Objetos

A programação nesse paradigma se caracteriza pela identificação de classes e objetos num dado domínio. Seguindo a analogia, objetos são cada ingrediente ou recipiente que uma receita manipula. Por exemplo, macarrão parafuso, uma dada quantidade de água, uma panela específica, são objetos necessários para o preparo de um macarrão instantâneo. Classes, por sua vez, são os tipos de ingredientes ou recipientes que são utilizados em alguma receita. Neste caso, macarrão, água e panela, descritos de forma geral, representam as classes desses objetos. Ou seja, classes classificam um conjunto de objetos. Essa classificação envolve a descrição de características comuns como peso, cor, formato das massas de macarrão, e maneiras específicas para a manipulação desses objetos, como lavar e cozinhar os massas. Para o exemplo do macarrão instantâneo, temos:

~~~~~~~~
1.  Classe: Macarrao     
2.      Caracteristicas: cor, formato, peso
3.      Operacoes: lavar, cozinhar
4.  
5.  Classe: Panela
6.      Caracteristicas: capacidade, material
7.      Operacoes: lavar, aquecer, adicionar ingrediente
8.  
9.  Classe: Agua     
10.      Caracteristicas: quantidade     
11.      Operacoes: molhar
12.  
13. Objeto Macarrao instantaneo = Macarrao amarelo, formato trança, 200gr
14.  
15. Objeto Cacarola = Panela 1 litro, teflon
16.  
17. Objeto Porcao de agua = Agua 500 ml
18.  
19. Cacarola.adicionar (Porcao de agua)
20. Cacarola.adicionar (Macarrao instantaneo)
21. Cacarola.aquecer (3min)
~~~~~~~~

Nas linhas 1, 5 e 9 temos o início da declaração das classes Macarrão, Panela e Água, respectivamente. A classe Macarrão, por exemplo, possui como características a cor, o formato e o peso. Como operacões para manipulá-lo, temos a operação de lavar e a de cozinhar. Nas linhas 13, 15 e 17 temos a instanciação das classes definidas, ou seja, a criação de exemplos das classes. Observe que na criação de cada objeto são fornecidos dados específicos que correspondem às características da classe. Por exemplo, na linha 13, o objeto Macarrão instantâneo é criado com o tipo amarelo, formato de trança e com 200gr. Os outros objetos são criados de forma correspondente. Nas linhas 19, 20 e 21 os objetos são combinados para o preparo do macarrão. Na linha 19 a caçarola, que é um objeto do tipo panela, recebe uma porção de água. Na linha seguinte, a mesma caçarola recebe a porção de macarrão instantâneo. Finalmente, na linha 21 a caçarola é aquecida por 3 min.

