## Recursão

![](/assets/recursao.jpg)

Considere o preparo de uma gelatina. Esta seguirá uma sequência de passos como qualquer outra receita. Se imaginarmos um bolo que tem uma camada de sorvete ou massa (farinha) e outra de gelatina, cada destas camadas pode ser tratada por uma rotina separada. A combinação da chamada destas rotinas é o preparo do bolo desejado. 

Agora considere que queiramos preparar um bolo de camadas coloridas de gelatina. Se nunca preparou uma gelatina, saiba que esta é preparada com água quente, que depois de uma mistura vai para a geladeira para endurecer. Como queremos várias camadas coloridas, teremos que preparar uma camada por vez, de forma a evitar que as camadas se misturem. Empilhamos cada novo preparo sobre as camadas já feitas, as quais devem estar prontas (endurecidas). Preparamos novas camadas até uma situação limite (situação de parada), como o limite da forma disponível. Recursão na Computação é exatamente esse processo de uma mesma rotina ser chamada em sequência até que uma condição seja satisfeita.

Abaixo apresento a estrutura típica de uma função recursiva usando nossa analogia: 

~~~~~~~~
1. **prepara_gelatina** (num_camadas) 
2.     Se (num_camadas == 0) // Forma cheia 
3.         Termina preparo 
4.     Mistura pó de qualquer sabor com água quente 
5.     Despeje na forma 
6.     Leve a geladeira para endurecer 
7.     **prepara_gelatina** (num_camadas - 1)
~~~~~~~~

No exemplo acima, a função **prepara_gelatina** inicia na linha 1 possui como parâmetro o número de camadas **num_camadas**. Na linha 2 há um teste, chamado caso base, o qual verifica se ainda há algo para fazer. Neste caso, se a forma já foi preenchida até seu limite. Caso o limite tenha sido alcançado, a função é terminada na linha 3 e nenhuma das linhas seguintes é realizada.

Caso a forma ainda não esteja preenchida, continuamos o preparo a partir da linha 4 em diante. O ponto chave da receita acima está na linha 7, onde uma camada acabou de ser preparada e uma nova precisa ser feita. Como os passos a serem dados são idênticos aos anteriores, é importante não sermos repetitivos e duplicarmos os preparos realizados da linha 2 até a 6. Para evitar esta repetição, chamamos a função novamente na linha 7, nos preocupando em atualizar o parâmetro, neste caso, diminuindo a quantidade de camadas que ainda faltam ser preparadas.

Resumindo, podemos descrever o problema de preparar **num_camadas** recursivamente como sendo o preparo de **1** camada **+** o preparo das **num_camadas - 1** restantes, onde está última parte é a chamada recursiva. Observe que nossa gelatina pode ter 1, 5 ou 50 camadas, a função é a mesma.
