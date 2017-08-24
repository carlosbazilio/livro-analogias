## Programação Funcional

Na programação funcional tudo é visto como função. Considere o preparo de um macarrão instantâneo. A água pode ser considerada uma função que, combinada em alguma quantidade com algum outro objeto, com um alimento, pode molhá-lo levemente, parcialmente ou inundá-lo. O macarrão pode ser ele próprio, ou seja, uma função identidade. Uma panela pode ser uma função que, dados quaisquer ingredientes, retorna um armazenamento para estes. A função fogo, quando recebe algo para ser aquecido e um intervalo de tempo, aquece este algo pelo tempo fornecido. Com isso, o programa para preparo de um macarrão pode ser dado da seguinte forma:

~~~~~~~~
fogo(tempo, recipiente) -> recipiente {...}
panela(ingredientes) -> recipiente {...}
agua(quantidade) -> ingrediente {...}
macarrao(quantidade) -> ingrediente {...}
> fogo( 3min, panela( agua( 300ml ), macarrao( 200gr ) ))
~~~~~~~~

Das linhas 1 à 4 temos as declarações das funções que são chamadas na linha 5. Essas funções são similares aos módulos da Programação Estruturada. Entretanto, na Programação Funcional, estas seguem algumas regras rigorosas: i) tudo que uma função necessita deve ser passado por parâmetro; ii) uma função sempre retorna algum valor, ou seja, sempre podemos pegar o resultado de uma função e passá-lo na chamada de outra. Por exemplo, a função fogo declarada na linha 1, recebe uma quantidade de tempo e um recipiente por parâmetro, e retorna um recipiente. Na linha 5, temos a chamada da função fogo, a qual recebe como parâmetro o tempo 3min e o resultado da chamada da função panela, que por sua vez recebe como parâmetros o resultado da chamada das funções agua e macarrão.
