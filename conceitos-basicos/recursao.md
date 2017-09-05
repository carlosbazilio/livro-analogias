## Recursão

![](/assets/recursao.jpg)

Considere o preparo de uma gelatina. Esta seguirá uma sequência de passos como qualquer outra receita. Se imaginarmos um bolo que tem uma camada de sorvete ou massa (farinha) e outra de gelatina, cada destas camadas pode ser tratada por uma rotina separada. A combinação da chamada destas rotinas é o preparo do bolo desejado. 
Agora considere que queiramos preparar um bolo de camadas coloridas de gelatina. Se nunca preparou uma gelatina, saiba que esta é preparada com água quente, que depois de uma mistura vai para a geladeira para endurecer. Como queremos várias camadas coloridas, teremos que preparar uma camada por vez, de forma a evitar que as camadas se misturem. Empilhamos cada novo preparo sobre as camadas já feitas, as quais devem estar prontas (endurecidas). Preparamos novas camadas até uma situação limite (situação de parada), como o limite da forma disponível. Recursão na Computação é exatamente esse processo de uma mesma rotina ser chamada em sequência até que uma condição seja satisfeita.

