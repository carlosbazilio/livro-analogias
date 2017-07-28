
# Conceitos Avançados


## APIs

Em restaurantes, pedidos de clientes são feitos após estes consultarem o cardápio do restaurante. Um cardápio indica que pratos podem ser preparados na cozinha daquele restaurante e os respectivos preços, ou seja, o que o cliente deverá fornecer (pagar) para ter aquele prato. Eventualmente, nos cardápios aparecem opções, como o ponto de cozimento de uma carte (mal passada, ao ponto ou bem passada), a forma de adoçamento de um suco (sem açúcar, com açúcar ou adoçante), as quais precisam ser indicadas pelo cliente. Ou seja, o restaurante é um provedor de serviços e o cliente é quem os utiliza. Com isso, o cardápio pode ser encarado como a API (Application Program Interface) do restaurante, o qual indica tudo que o restaurante oferece e o que precisa ser entregue para que o serviço seja fornecido.


## Programação Genérica

Na programação genérica, usualmente criamos operações de alto-nível, as quais podem ser aplicadas a diferentes tipos de valores. Exemplos típicos são coleções (pilhas, filas, ...). Por exemplo, podemos empilhar inúmeros tipos de valores (números, strings, pratos, carros, etc). A programação é genérica pois o funcionamento das operações para o tipo pilha independem dos tipos de valores manipulados. Sem utilizar exemplos óbvios como pilha de pratos, copos e panelas, podemos fazer uma analogia do comportamento genérico destes tipos com o preparo de uma vitamina. Nestas, há uma idéia geral de preparo, que consiste em se levar ao liquidificador um líquido (água, leite ou algum suco), eventualmente algo adocicado (açúcar ou mel), e as frutas, verduras e/ou legumes, das quais se deseja preparar a vitamina. Observe que o preparo geral independe de quais ingredientes serão utilizados, o que caracteriza o comportamento genérico.


## Programação em Rede

Cozinhas interligadas de alguma forma que podem depender uma da outra para o preparo de algum prato, seja fornecendo ingredientes ou partes de um preparo. Outro exemplo de programação em rede na cozinha aparece quando um restaurante possui uma cozinha para preparação dos pratos e um bar para preparação dos drinks. Ingredientes como frutas são compartilhadas entre estes setores, os quais precisam interagir para que não falte ingrediente ou parte de um preparo em ambos.


## Programação na Nuvem

Suponha que você deseja organizar um jantar para 20 pessoas, mas sua cozinha não comporta o preparo de tantas receitas: há apenas panelas pequenas, não há utensílios suficientes, dentre outras restrições. Uma solução para este problema é contratar um serviço de buffet, o qual se encarrega de todo preparo e entrega do jantar. Excetuando questões de qualidade, para nós, clientes, pouco importa como e onde o prato foi feito. O fundamental é ter os pratos solicitados na hora e local que desejarmos. A cozinha do buffet, seus cozinheiros e toda a infraestrutura requerida, estão na chamada nuvem em Computação, um espaço abstrato do ponto de vista dos clientes. É importante observar que para o cliente, a vantagem do uso deste tipo de serviço é não ter que adquirir uma infraestrtura complexa para uma atividade eventual, como o jantar em questão. 


## Programação Concorrente

A programação concorrente permite que possamos identificar num programa trechos de códigos independentes, os quais poderiam executar em qualquer ordem. Isso permite, por exemplo, que consigamos executar o programa mais rapidamente processando estes trechos independentes simultaneamente. Essa aceleração costuma ser diminuída quando estes trechos precisam compartilham algum recurso. 

Na cozinha, um exemplo de concorrência acontece no preparo da massa, recheio e cobertura de um bolo. Como serão combinados em algum momento, é importante que sejam iniciados em momentos independentes para que não haja espera na combinação. Nesta situação, um retardo pode ocorrer quando diferentes partes do preparo compartilham um mesmo recurso, como uma batedeira. No momento em que uma parte do preparo precisa utilizar a batedeira, esta não pode estar sendo utilizada por outra parte. Nesta situação, a parte que necessitou por último deverá aguardar até a primeira terminar. Essa espera pode atrasar o momento em que as partes serão combinadas. No caso da batedeira, para evitar o risco de se misturar ingredientes de partes distintas, uma parte da receita precisa terminar por completo seu uso para que outra possa iniciar. Se o utensílio a ser compartilhado é uma faca elétrica, é possível que as partes da receita não precisem encerrar o uso deste utensílio por completo, ou seja, o uso pode ser trocado entre as partes ao longo do preparo. Outra possibilidade de compartilhamento ocorre quando as partes podem compartilhar recursos sem interrupção. Por exemplo, um relógio pode ser usado para controlar a realização de partes do preparo simultaneamente. Esta forma é mais interessante porque não impõe retardo em nenhuma das partes.


## Programação Móvel

Programar para dispositivos móveis é como cozinhar para crianças. A essência é a mesma, mas com algumas restrições. Por exemplo, pratos infantis normalmente não levam álcool ou alimentos muito gordurosos no preparo. Os organismos das crianças, principalmente as bem pequenas, ainda estão em fase de crescimento e não conseguem digerir grandes quantidades de alimentos. Além disso, os pratos das crianças costumam ser decorados de forma a serem atraentes para o público alvo.

Para quem cozinha e precisa atender os 2 públicos (adulto e infantil, ou seja, desktop e móvel, respectivamente), essa distinção tende a atrapalhar, pois é mais fácil cozinhar um mesmo prato para 2 pessoas do que 2 pratos distintos. Isso se dá porque receitas diferentes usualmente requerem ingredientes diferentes, utensílios diferentes e ainda tem tempo de preparo diferenciado. Quanto a decoração dos pratos infantis, a analogia na programação móvel é a elaboração da interface, pois as telas são menores e os aplicativos precisam ter interfaces simples e intuitivas.


## Programação Web

A programação para web pode ser associada a uma cozinha que funciona para serviço de entrega. Na programação web o cliente consome o prato fora do restaurante, como num serviço de entrega. Isso traz alguns bnefícios para o cliente, como o fato de poder consumir seu alimento onde quiser, bastando que este tenha um telefone para solicitá-lo. Na programação web, o que é essencial para um cliente é ter uma conexão a web e um navegador. Num restaurante convencional, o cliente deve se deslocar até este para fazer sua refeição. Na programação, isso é equivalente a instalar um software para poder utilizá-lo. Questões como ir de taxi, à pé, em transporte coletivo, se está chovendo no dia, trânsito, podem ser associadas às complicações de se instalar um software, como versão disponível para um Sistema Operacional específico, download do software, independente do seu tamanho, etc.

Em sistemas web, o cliente pode ter algumas facilidades como a associação do seu número de telefone com seu endereço. Isso faz com que este cliente não precise mais informar seu endereço nos próximos pedidos. Na programação, o servidor web, onde ficam armazenadas as aplicações web, registra informações dos clientes de forma a retornar dados mais personalizados. Na programação web, o termo que se refere ao local onde são armazenadas essas informações particulares se chama sessão. Na cozinha, apesar do registro dessas informações serem comuns, não há um nome de termo associado.


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


## Programação Orientada a Objetos

A programação nesse paradigma se caracteriza pela identificação de classes e objetos num dado domínio. Seguindo a analogia, objetos são cada ingrediente ou recipiente que uma receita manipula. Por exemplo, macarrão parafuso, uma dada quantidade de água, uma panela específica, são objetos necessários para o preparo de um macarrão instantâneo. Classes, por sua vez, são os tipos de ingredientes ou recipientes que são utilizados em alguma receita. Neste caso, macarrão, água e panela, descritos de forma geral, representam as classes desses objetos. Ou seja, classes classificam um conjunto de objetos. Essa classificação envolve a descrição de características comuns como peso, cor, formato das massas de macarrão, e maneiras específicas para a manipulação desses objetos, como lavar e cozinhar os massas. Para o exemplo do macarrão instantâneo, temos:

~~~~~~~~
Classe: Macarrao     
    Caracteristicas: cor, formato, peso
    Operacoes: lavar, cozinhar

Classe: Panela
    Caracteristicas: capacidade, material
    Operacoes: lavar, aquecer, adicionar ingrediente

Classe: Agua     
    Caracteristicas: quantidade     
    Operacoes: molhar

Objeto Macarrao instantaneo = Macarrao amarelo, formato trança, 200gr

Objeto Cacarola = Panela 1 litro, teflon

Objeto Porcao de agua = Agua 500 ml

Cacarola.adicionar (Porcao de agua)
Cacarola.adicionar (Macarrao instantaneo)
Cacarola.aquecer (3min)
~~~~~~~~

Nas linhas 1, 5 e 9 temos o início da declaração das classes Macarrão, Panela e Água, respectivamente. A classe Macarrão, por exemplo, possui como características a cor, o formato e o peso. Como operacões para manipulá-lo, temos a operação de lavar e a de cozinhar. Nas linhas 13, 15 e 17 temos a instanciação das classes definidas, ou seja, a criação de exemplos das classes. Observe que na criação de cada objeto são fornecidos dados específicos que correspondem às características da classe. Por exemplo, na linha 13, o objeto Macarrão instantâneo é criado com o tipo amarelo, formato de trança e com 200gr. Os outros objetos são criados de forma correspondente. Nas linhas 19, 20 e 21 os objetos são combinados para o preparo do macarrão. Na linha 19 a caçarola, que é um objeto do tipo panela, recebe uma porção de água. Na linha seguinte, a mesma caçarola recebe a porção de macarrão instantâneo. Finalmente, na linha 21 a caçarola é aquecida por 3 min.


## Banco de Dados

Um sistema de gerenciamento de banco de dados pode ser visto como um robô cuja função básica é guardar e recuperar ingredientes, ou partes de uma receita, para o preparo completo desta. Como as cozinhas tem distribuição de espaços diferentes, assim como suas mobílias, é necessário que este robô seja programado para trabalhar em um leiaute específico. Ou seja, um sistema de gerenciamento de banco de dados pode ser considerado uma ferramenta programada de suporte à execução de outros programas.

Um banco de dados, como ouvimos popularmente, é, tecnicamente falando, um conjunto de arquivos que armazena dados para algum fim. Como há um minisistema (robô) específico para manipular esses dados, estes podem estar em qualquer disposição que o robô compreenda. Os dados podem ser armazenados como outros ingredientes na cozinha, ou seja, dentro de armários/dispensas.


## Frameworks

Frameworks podem ser encarados como alimentos semiprontos como uma pizza pré-cozida. A utilização destes alimentos, assim como dos frameworks, agiliza o processo de criação de receitas e implementação de sistemas. Numa pizza pré-cozida só temos que adicionar ingredientes, sem restrição, para personalizarmos esta pizza ao nosso gosto. Algumas já vem com alguns ingredientes, outras vem somente com a massa, mas todas já antecipam alguns passos do processo de preparo. 


## Desenvolvimento Tradicional x Desenvolvimento Ágil

A Engenharia de Software é uma subárea da Computação responsável por criar métodos, processos e metodologias que visam a criação de softwares de qualidade e de forma eficiente. Formas diferentes de criar um software, suas implicações, a participação dos clientes, a divisão em etapas, dentre outras atividades, são decisões tomadas nesta área. Apesar da tarefa de criar um software ser muito mais complexa que a elaboração e preparo de uma receita, uma analogia provável é analisarmos os fundamentos que baseiam um curso de Culinária.

Fazendo analogia com o desenvolvimento de software tradicional, quando vamos a um restaurante, consultamos o cardápio para saber o que comeremos. Fazemos o pedido e, após um tempo, recebemos o prato preparado. Infelizmente, não é pouco frequente o prato não nos agradar, seja pelo ponto do cozimento de algum alimento, seja por conter algum ingrediente que não desejávamos e que não sabíamos que era utilizado. Nos restaurantes mais caros, é comum o prato ser refeito ao gosto cliente, e o restaurante absorve o prejuízo. Nos mais baratos, é comum os clientes comerem pouco do prato. Em ambas situações os clientes saem, no mínimo, desapontados com o serviço prestado.

No desenvolvimento ágil, a analogia pode ser feita aos restaurantes onde há maior interação entre cliente e cozinheiro. Por exemplo, imagine que os pratos são preparados na frente do cliente, o qual pode sugerir personalizações de forma a deixar o prato mais adequado ao seu gosto. Essa interação aumenta a chance de que o prato preparado agrade por completo o cliente, o que também diminui a chance do restaurante ter prejuízo com o preparo. 


