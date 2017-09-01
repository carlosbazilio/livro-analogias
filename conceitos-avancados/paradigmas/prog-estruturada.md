## Programação Estruturada

Na programação estruturada, os programas são organizados em módulos (operações), os quais deveriam ter funções específicas e são acionados para o preparo do prato.

~~~~~~~~
1.  prato: Macarrao amarelo, 200gr
2.  liquido: Agua, 500ml
3. 
4.  Cozinhar (Alimento, Tempo) {
5. 	   // Operações para realizar o cozimento
6.  }
7. 
8.  Preparo () {
9. 	   Cozinhar (prato + liquido, 3min)
10. }
11.
12. Preparo ()
~~~~~~~~

Neste programa, nas linhas 1 e 2 temos os valores (estruturas) que serão utilizados ao longo do programa. Nas linhas 4 e 8 temos o início de 2 módulos, os quais são chamados à partir da linha 12. O módulo Cozinhar, à partir da linha 4, recebe um Alimento a ser cozido e o Tempo de cozimento. Ou seja, olhando para a linha 4 sabemos o que é necessário para o funcionamento deste módulo. Em programação, o módulo é uma função e o que ele necessita são os seus parâmetros, que juntamente com o que este retorna constituem sua assinatura. Essa característica não acontece no módulo Preparo, o qual inicia na linha 8, o que torna implícito o que este módulo manipulará. Ou seja, fica a cargo do programador estruturar seus programas (receitas) da maneira mais legível possível.
