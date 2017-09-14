# Introdução

![](/assets/cozinha.jpeg)

Neste livro apresentaremos conceitos de **programação** fazendo **analogia** com a **culinária**. Para tal não é necessário ser um "mestre cuca" para entender as analogias apresentadas. Utilizamos este artifício como forma de facilitar o entendimento de conceitos na programação. Os conceitos abordados vão desde a programação básica, para iniciantes, até conceitos mais avançados, exigidos a programadores experientes.

Antes de falarmos de programação efetivamente, vamos apresentar de maneira minimalista, mas suficiente, o que é um computador. Na verdade, o esquema abaixo descreve de maneira geral todos os sistemas computacionais que temos contato: celulares, tablets, robôs, forno microondas, etc. 

![](/assets/sistema-computacional.jpg)

Neste esquema, o **Processador** é o cérebro do sistema, o qual controla todo o seu funcionamento. Apesar de muito poderoso e rápido, só nada conseguiria fazer. Para ajudar na sua tarefa temos os outros 4 componentes do diagrama: a **Memória**, os dispositivos de **Entrada**, **Saída** e **Armazenamento**.

A **Memória**, também chamada de memória principal ou memória RAM, é o componente responsável pelo armazenamento rápido de informações. O nosso cérebro também possui uma porção para este fim. Quando precisamos guardar um número de telefone "de cabeça", por não posssuirmos no momento nada para registrá-lo, usamos essa porção do cérebro. Conseguimos registrar muito rapidamente, mas conseguimos esquecer com igual velocidade também.

Na situação em que queremos registrar a informação de forma mais duradoura, usamos os **Dispositivos de Armazenamento**, também chamados de memória secundária. Da mesma forma que temos muitas alternativas para registrar um número de telefone (caderno de anotações, agenda do celular, papel de pão, etc), o processador tem diversos dispositivos para registrar suas informações: disco rígido, cartão de memória, CD-Rom, etc. O registro nestes dispositivos garante um tempo de vida útil muito maior que a memória. Nos computadores, a informação é retida na memória enquanto este está ligado, se esvaziando quando o desligamos. Processo similar deve ocorrer com nosso cérebro quando vamos dormir, ao menos para as informações que foram obtidas sem muito esforço.

Outro aspecto fundamental para que nosso cérebro funcione é o contexto onde ele se encontra. Problemas enfrentados no dia a dia são fundamentais para manter nosso cérebro em funcionamento. E estes problemas são percebidos com nossos sentidos: visão, olfato, paladar, audição e tato. Estes sentidos permitem que nos comuniquemos com o mundo, assim como os **Dispositivos de Entrada** (teclado, mouse, microfone, etc) e os **Dispositivos de Saída** (monitor, impressora, etc) permitem que possamos interagir com os computadores. Alguns sentidos possuem uma única direção, como a visão e a audição. Estes são utilizados apenas para fornecer informação (entrada) ao cérebro. O tato, por sua vez, tem o papel de nos dar a percepção do formato, a textura das coisas (entrada), mas também permite que troquemos as coisas de lugar (saída). Com o computador não é diferente. Um teclado é usualmente utilizado como um dispositivo de entrada. Um monitor, por sua vez, pode ter a tela sensível ao toque, o que o torna um dispositivo de entrada e saída. Apesar disso, os papéis de entrada e saída são bem definidos, como pode ser visto no sentido das setas do esquema anterior.

A seguir veremos analogias básicas destes componentes em nossa cozinha.

<img src="/assets/cozinha.jpeg" width="320"/> <img src="/assets/computador.jpeg" width="320"/>

Uma **cozinha** pode ser associada a um **computador**. É nela em que tudo acontece. Um computador executa programas, assim como uma cozinha é utilizada para preparar receitas. O computador é operado por um usuário, o qual tem necessidades específicas e utiliza o computador para automatizá-las. Da mesma forma as receitas só são preparadas quando há clientes famintos demandando estas.

<img src="/assets/bancada.jpeg" width="320"/> <img src="/assets/memoria.jpeg" width="320"/>

Quando dizemos que utilizamos uma cozinha (e não um quarto), já subentendemos que uma série de elementos comuns de uma cozinha estarão disponíveis. A cada destes elementos fazemos uma associação a componentes num computador. **Pias** e **bancadas** constituem a **memória principal**, pois elementos são armazenados ali de forma temporária, apenas para o preparo de uma receita. Ingredientes, vasilhames, até a descrição da receita em si, são colocados nesta memória para auxiliar o preparo da receita.

Na cozinha é recomendável que sempre deixemos a bancada limpa. Isso agiliza o preparo de novas receitas, além de garantir higiene na manipulação dos alimentos. Essa limpeza é importante também pois o espaço disponível na bancada é limitado. Todas essas características valem para o uso da memória num computador. Ela precisa ser desocupada com frequência, usada de forma consciente, para que não se esgote rapidamente.

No preparo de receitas que envolvem muitos ingredientes, ou no preparo de mais de uma receita simultaneamente, é comum a bancada não ser suficiente. Neste caso, costumamos manter alguns ingredientes no armário, se possível próximo da bancada para não atrasar no preparo na receita. Este espaço reservado nos armários para o preparo de uma receita, em função da bancada estar cheia, é chamado de **memória virtual** no computador. Ou seja, quando grandes programas executam no computador, em uma memória limitada, eventualmente é necessário que parte destes programas sejam colocados nos discos rígidos para que outras partes possam ser executadas.

<img src="/assets/geladeira.jpg" width="320"/> <img src="/assets/hd.jpeg" width="320"/>



Para que diversas receitas possam ser preparadas, é necessário que uma cozinha esteja bem equipada para permitir o armazenamento adequado de produtos e utensílios domésticos. Para tal utilizamos **armários**, **geladeiras** e **freezers**, os quais representam nossa **memória secundária**, ou seja, dispositivos que armazenam nossos produtos por um tempo muito maior que nossas pias e bancadas.

<img src="/assets/fogao.jpeg" width="320"/> <img src="/assets/cpu.jpeg" width="320"/>

Para que o preparo da receita possa de fato ocorrer, **fogões**, **fornos** e **microondas** costumam ser peças fundamentais, para onde vão todo nosso esforço na cozinha. Esses elementos, na Computação, são os **processadores**. Como na cozinha, há muitos tipos, os quais podem diferir pela velocidade de processamento, consumo de energia, material utilizado, etc. Estas e outras características, juntamente com a competição de mercado, determinam os preços desses componentes.

<img src="/assets/cozinha-projeto.jpeg" width="320"/> <img src="/assets/computador-arquitetura.jpeg" width="320"/>

Um **arquiteto** na construção civil tem como uma de suas atribuições garantir a melhor distribuição destes elementos numa cozinha. Esta distribuição deve garantir que estes elementos funcionem da forma mais **eficiente** possível. Por exemplo, uma bancada sempre está próxima de uma pia, pois é comum na cozinha a tarefa de descascar e lavar, por exemplo. Ou seja, a distribuição otimiza as tarefas mais frequentes. De forma igual ocorre na Computação, onde um **arquiteto de hardware** projeta a máquina de forma que seus componentes funcionem da forma mais eficiente possível. Por exemplo, no uso do fogão, durante um preparo, os ingredientes podem ser necessários em momentos distintos, e um retardo ao pegar um ingrediente pode resultar num prato com cozimento fora do ideal, por exemplo. Relação similar ocorre entre **processador** e **memória** num computador.

<img src="/assets/cozinheiros.jpg" width="320"/> <img src="/assets/programadoras.jpg" width="320"/>

As receitas são elaboradas por **chefes de cozinha** e preparadas por cozinheiros. A elaboração destas é feita baseada na experiência do chefe com diferentes ingredientes, que combinados darão o efeito desejado. Tendo em vista que ingredientes similares podem causar o mesmo efeito, como manteiga e azeite, um mesmo prato pode ser preparado de diferentes formas. De forma similar ocorre na programação, onde programas diferentes podem ter o mesmo resultado. Os chefes são os **programadores** que elaboram receitas de acordo com o pedido de seus clientes.

<img src="/assets/robo.jpg" width="320"/>

Os **cozinheiros**, por sua vez, tem a tarefa metódica de executar o que está descrito na receita. Essa execução é feita passo a passo, na mesma ordem listada na receita. É comum que cozinheiros improvisem, alterem a receita durante o preparo, seja pela falta de algum ingrediente, seja com o intuito de dar um toque pessoal à receita. Na Computação, o papel do cozinheiro é exercido pelo **interpretador** de uma linguagem, ou seja, o programa que os cozinheiros executam para interpretar as receitas. A única diferença é que não há toque pessoal na Computação, ou seja, o interpretador só executa aquilo que está descrito, nada mais, nada menos. No máximo pode ocorrer a falta de algum ingrediente. Mesmo nesta situação, é necessário que o interpretador já saiba de antemão qual caminho alternativo seguir. Se pensarmos bem, com o cozinheiro acontece a mesma coisa, pois ele precisa ter vivido aquela situação de falta de algum ingrediente para conhecer seus possíveis substitutos.

Pensando numa cozinha industrial, onde a quantidade de pratos a serem preparados simultaneamente é grande, é fundamental que haja um pessoal de apoio para garantir o bom funcionamento da cozinha. Chamaremos estes de **assistentes do cozinheiro**, os quais localizam os ingredientes e utensílios nos armários e geladeiras, arrumam estes quando há necessidade, arrumam também a bancada, lavam a louça que já foi utilizada e que poderá ser reutilizada, controlam a temperatura do fogo, ou seja, dão todo o apoio para que as receitas possam ser preparadas da melhor forma possível. Na Computação estes são chamados de **Sistemas Operacionais**. A forma como estes funcionam varia de fabricante para fabricante, assim como as cozinhas possuem organizações bem particulares. Observem que iniciamos este parágrafo considerando cozinhas industriais. Mas, tendo em vista os papéis cruciais desempenhados pelos assistentes, não é de se estranhar que toda cozinha tenha alguém com este papel. Da mesma forma, encontramos Sistemas Operacionais tanto em grandes centros computacionais como em computadores domésticos, tablets, celulares e qualquer outro equipamento que execute diferentes programas.

Para que as cozinhas funcionem é fundamental que hajam alimentos. Estes alimentos são entregues por **fornecedores**, os quais podem ser encarados como os **dispositivos de entrada** de nosso computador. Da mesma forma, podemos encarar a **forma de entrega** de nossos preparos (entrega a domicílio, no restaurante, etc) como os **dispositivos de saída**.

Abaixo segue um resumo das analogias de base para este livro:

<a name="analogias"></a>

| Culinária | Programação |
| :--- | :--- |
| Cozinha | Computador |
| Receita | Programa |
| Chefe | Programador |
| Cozinheiro | Interpretador |
| Assistentes de Cozinheiro | SO |
| Pia/Bancada | Memória Principal |
| Armários/Geladeira | Memória Secundária |
| Cliente | Usuário |
| Livro de Receitas | Sistema |
| Material para criar receitas | IDE |

Agora que introduzimos as analogias básicas e gerais entre Computação e Culinária, podemos iniciar a apresentação das analogias entre receitas e programas, as quais são o objetivo principal deste livro.

