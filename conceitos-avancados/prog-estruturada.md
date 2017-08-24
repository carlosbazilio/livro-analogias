## Programação Estruturada

Paradigmas de programação são formas diferentes de se programar, mas que tem o mesmo objetivo, que é resolver algum problema, ou elaborar alguma receita. Nesta e nas 3 próximas seções (Programação Funcional, Lógica e Orientação a Objetos) veremos formas diferentes de se programar. Para tal, criaremos um programa em cada paradigma que simula a preparação de um macarrão instantâneo.

Na programação estruturada, os programas são organizados em módulos (operações), os quais deveriam ter funções específicas e são acionados para o preparo do prato.

~~~~~~~~
prato: Macarrao amarelo, 200gr
liquido: Agua, 500ml

Cozinhar (Alimento, Tempo) {
	// Operações para realizar o cozimento
}

Preparo () {
	Cozinhar (prato + liquido, 3min)
}

Preparo ()
~~~~~~~~

Neste programa, nas linhas 1 e 2 temos os valores (estruturas) que serão utilizados ao longo do programa. Nas linhas 4 e 8 temos o início de 2 módulos, os quais são chamados à partir da linha 12. O módulo Cozinhar, à partir da linha 4, recebe um Alimento a ser cozido e o Tempo de cozimento. Ou seja, olhando para a linha 4 sabemos o que é necessário para o funcionamento deste módulo. Em programação, o módulo é uma função e o que ele necessita são os seus parâmetros, que juntamente com o que este retorna constituem sua assinatura. Essa característica não acontece no módulo Preparo, o qual inicia na linha 8, o que torna implícito o que este módulo manipulará. Ou seja, fica a cargo do programador estruturar seus programas (receitas) da maneira mais legível possível.
