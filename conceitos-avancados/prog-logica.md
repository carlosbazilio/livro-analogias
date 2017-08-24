## Programação Lógica 

Esta forma de se programar caracteriza-se pela utilização da teoria de lógica para criação de programas. Iniciamos pela definição de fatos, ou seja, o que consideramos como verdade inicialmente. Após, criamos regras, as quais geram verdades à partir de fatos e/ou de outras regras. Esse conjunto de regras e fatos são chamados de nossa base de conhecimento. Por último, podemos realizar consultas sobre essa base para verificar se alguma informação é verdade. Para nossa analogia, temos :

~~~~~~~~
Fatos:
Ingrediente (macarrao, 200gr) 
Ingrediente (agua, 500ml)
Recipiente (panela, 1 litro) 
Eletro (fogao, aquecer)

Regras:
Se tivermos um ingrediente qualquer e agua e um eletro de aquecer entao podemos obter o ingrediente cozido

Consulta:
Conseguimos obter macarrao instantaneo do programa acima?
~~~~~~~~

Das linhas 1 à 5 temos a declaração de fatos a serem usados neste programa lógico. Por exemplo, na linha 2 declaramos que temos um macarrão de 200gr como um ingrediente. Nas linha 8 à 9 temos uma regra, a qual gera novos fatos à partir da base. Neste caso, a regra geral indica que se temos algum ingrediente adicionado à agua e aquecido podemos cozinhá-lo. Na linha 12 temos a execução do programa lógico, o qual realiza uma consulta sobre os fatos e regras definidos. Neste caso, se conseguimos obter macarrão instantâneo do programa. Note que não tivemos a preocupação de especificar de forma rigorosa o programa, usando alguma sintaxe precisa e bem definida. O objetivo é apenas ilustrar ao leitor o formato geral de programas lógicos.

