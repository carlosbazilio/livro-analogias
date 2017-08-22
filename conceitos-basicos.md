# Conceitos Básicos

## Conversão de Tipos - Casting

{width=60%}
![Conversão de tipos - Imagem extraída do site Comida e Bebida (http://comida.umcomo.com.br/)](images/originals/casting2.jpg)

Propriedade que permite que um valor de um tipo (ingrediente) seja "convertido" em outro. Por exemplo, quando um número real é atribuído a um inteiro, apenas a parte inteira é armazenada neste último. Analogamente, quando lavamos o arroz, um vasilhame contém a água e o arroz. Quando usamos uma peneira para secá-lo, o novo vasilhame conterá apenas o arroz. Há diversas outras situações onde ocorre um casting na cozinha: alimentos antes e após serem descascados, a criação de cubos de arroz após este ser preparado, os enfeites feitos com frutas, verduras e legumes para embelezar pratos e mesas, dentre outros. Observem que em todas as situações o ingrediente que está sendo manipulado é praticamente o mesmo, foi apenas modificado para atender a um fim específico.

Exemplo na cozinha:

~~~~~~~~
vasilhame <- farinha peneirada 

canecão <- suco de maracujá cuado 
~~~~~~~~

Nos exemplos acima, o ato de peneirar a farinha ou cuar um suco não modificam os alimentos por completo, mas alteram estes de maneira que fiquem mais adequados para algum uso. 


## Subrotinas 

![Subrotinas - Imagem extraída do site Mexido de Idéias (http://www.mexidodeideias.com.br/)](images/originals/subrotina.jpg)

No preparo de receitas que tomam muitos passos, é comum que partes da receita sejam preparadas em separado, seja por utilizarem um conjunto de ingredientes diferentes, seja por necessitarem de preparo em momentos distintos para depois serem combinados num único prato. Na preparação de um bolo, por exemplo, é comum prepararmos o recheio e a cobertura separados do preparo da massa do bolo. Ou seja, os preparos do recheio e da cobertura são como "subreceitas", assim como funções e procedimentos num programa também são chamados de subprogramas. A utilização de subprogramas e subreceitas em programas e receitas, respectivamente, também é interessante do ponto de vista da organização, uma vez conseguimos particionar nossa tarefa maior em tarefas menores. Outro ponto a observar é a possibilidade de reutilizarmos partes de uma receita em outra, como uma cobertura de bolo de chocolate em um pudim.


## Parâmetros / Argumentos

![Parâmetros/Argumentos - Trecho de receita extraído do site (http://cupcakes.blog.br/)](images/originals/parametros.png)

Toda receita listada num livro de receitas possui uma porção resultante, a qual indica para quantas pessoas este preparo atenderá. Esta quantidade sempre está ligada à quantidade de ingredientes utilizados, os quais são informados e usualmente podem ser alterados de forma proporcional. Por exemplo, se uma receita leva 1 litro de leite, 2 ovos, 500gr. de farinha e serve 4 pessoas, geralmente podemos prepará-la para 2 pessoas fornecendo metade dos ingredientes. Os ingredientes, neste caso, são chamados de parâmetros e/ou argumentos[^params] na programação. Todas as receitas possuem esta característica, ou seja, podemos dizer que todas as receitas são parametrizadas. Essa característica existe tanto para uma receita como um todo quanto para partes de preparo internas a uma receita (subreceita).

[^params]: Diferenciando tecnicamente, **argumentos** são os valores a serem passados para uma função, enquanto que **parâmetros** são os nomes das variáveis nas funções que receberão os valores passados.


## Bibliotecas

{width=40%}
![Biblioteca - Imagem extraída do site (http://www.casaevideo.com.br/)](images/originals/biblioteca.jpg)

No preparo de uma receita, é comum precisarmos de utensílios mais complexos, como **batedeiras**, **liquidificadores**, **multiprocessadores** e **mixers**, os quais têm como papel agilizar alguma tarefa manual. Estes utensílios são armazenados nos armários e são tirados de lá e colocados na bancada quando necessários. Entretanto, como nossa bancada é limitada, não há espaço para se colocar tanto equipamento junto. Isso pode forçar o cozinheiro, ou seu auxiliar, a retirar este utensílio da bancada quando não for mais necessário ou não estiver sendo utilizado num dado momento. Na programação, este comportamento se assemelha ao uso de **bibliotecas**, as quais são ferramentas que simplificam a criação de um programa por permitirem a abstração de operações complexas, como uma biblioteca para execução de funções trigonométricas. Na cozinha, quando temos que misturar bem alguns produtos, podemos utilizar um liquidificador e podemos abstrair sobre a forma como este foi construído. Para utilizá-lo, basta sabermos como este é operado. Estas bibliotecas podem ser utilizadas ou não, o que depende do problema abordado e da forma de resolvê-lo.


## Coleções

{width=60%}
![Coleções - Imagem extraída do site (http://www.comunidadebancodoplaneta.com.br/)](images/originals/colecoes.jpg)

Coleções são sacolas, sacos com lacre ou qualquer outro recipiente utilizado para armazenar vários ingredientes, os quais podem ser de tipos diferentes. Esse armazenamento pode ser temporário, apenas durante o preparo de uma receita, ou por um longo tempo, para durar por várias receitas. Neste último caso, estes são colocados em armários e geladeiras (hds) ou freezers (hds externos). Dada a natureza dos ingredientes, eventualmente pode ser necessário que estes sejam armazenados segundo alguma ordem. Por exemplo, se estes possuem data de validade, é fundamental que os mais antigos sejam os primeiros a serem recuperados.


## Arquivos 

![Arquivos - Imagem extraída do site (http://gastronomiaeeu.blogspot.com.br/)](images/originals/arquivos.jpg)

Arquivos podem ser vistos como alimentos prontos, semiprontos ou até crus, que são armazenados para serem usados num momento futuro, em outras receitas ou até na mesma, caso esta leve muito tempo para ficar pronta, por exemplo. A possibilidade deste armazenamento permite que receitas demoradas possam ser preparadas em partes, sem que nada estrague neste processo. Como vimos no capítulo anterior, geladeiras, armários e freezers são nossa memória secundária na cozinha. Nestas o que armazenamos são os alimentos que serão ingredientes das receitas ou partes de uma receita sendo preparada. 


## Ponteiros

{width=60%}
![Ponteiros - Imagem extraída do site (http://www.casasepis.com.br/)](images/originals/ponteiros.jpg)

Considere uma cozinha comercial que ofereça serviço de quentinhas, as quais são pratos de refeições completos servidos a empregados e fornecidos usualmente em pratos de alumínio descartável. Suponha que a quantidade de pedidos varie bastante ao longo dos dias e que os recipientes (porta-quentinhas que armazenam os pratos de alumínio) utilizados para acondicionamento das quentinhas não são baratos. O comerciante decide por alugar estes recipientes sob demanda, ou seja, à medida que pedidos são solicitados ele aluga recipientes na mesma proporção. Os aluguéis são diários e é fundamental que o comerciante solicite a retirada destes recipientes para que não seja computado um novo aluguel. Ao longo do dia, a cozinha pode reutilizar tantas vezes quanto quiser um recipiente. 

Na programação, ponteiros são endereços de memória utilizados para referenciar áreas onde valores são armazenados. Tipicamente, estas áreas de memória são alocadas de forma dinâmica, ou seja, durante a execução do programa e numa quantidade previamente indeterminada. Esse mecanismo é útil porque permite, para programas que utilizem volumes grandes de informação de forma eventual, maior flexibilização na reserva de espaço em memória. Ou seja, o programador pode escolher o que é reservado estaticamente (alocação fixa, que perdura durante toda a execução do programa) e o que é reservado dinamicamente (alocação variável, onde não se sabe quando uma área de memória será reservada e que tamanho ela terá). Este último caso é exatamente a situação das quentinhas, pois o comerciante não tem idéia de quantas quentinhas serão pedidas num dado dia. O pedido explicíto de retirada dos recipientes de quentinhas é a remoção das áreas de memórias alocadas dinamicamente, passo fundamental para que a memória disponível para um programa não se esgote. Na cozinha, seria termos tantos recipientes desperdiçados a ponto da venda começar a dar prejuízos.

Esta questão do desperdício é tão crucial na cozinha quanto na programação. Para resolver o problema deste último, muitas linguagens de programação oferecem um mecanismo chamado coleta de lixo. Este mecanismo monitora as áreas de memória e remove as que não são mais referenciadas à partir de algum ponto num programa. Na cozinha, é como se o serviço que oferece os recipientes controlasse automaticamente os aluguéis e já agendasse a retirada ao final do dia.


## Abstração

{width=60%}
![Abstração - Imagem extraída do site (http://chezmari.tumblr.com/)](images/originals/abstracao.jpg)

Na programação, fazemos uso da abstração quando utilizamos recursos simples para descrever cenários complexos. Na culinária, encontramos uso da abstração quando uma receita contém uma etapa descrita em apenas uma frase, mas que tomará vários passos para ser feita. Por exemplo, numa receita de pudim encontrei a seguinte etapa: "Com o açúcar prepare um caramelo claro". Esta etapa pode ser descrita como colocar o açúcar no fogo, misturá-lo sem parar até que fique com uma consistência pastosa.
Ou seja, o cozinheiro que escreveu a receita abstraiu a complexidade da etapa a ser realizada. Este mecanismo é muito importante para tornar mais sucintas, porém igualmente expressivas, as receitas e os programas.


## Exceções

![Exceções - Imagem extraída do site (http://www.otv.tv.br/programa/o-gourmet/](images/originals/excecoes.jpg)

Na cozinha, é comum planejarmos alguma receita e, durante o preparo, algum passo causar um erro e inviabilizar a receita inicial. Esse erro pode ser causado por muitos fatores, como um forno desregulado, um ingrediente usado fora da validade por descuido, ou até uma distração que causa um cozimento ou fritura além do ideal. Numa cozinha industrial, este erro causará o descarte do preparo e uma nova preparação. Numa casa, usualmente tentamos resgatar o preparo fazendo um outro prato. Em ambas as situações, os chefes de cozinha podem, quando as chances de erro são grandes, planejar previamente pratos alternativos, como fazer um ovo mexido quando se deseja fazer um ovo com gema perfeita e ela se parte. Esta forma de se pensar em pratos alternativos, ou até no descarte completo do preparo, é chamada de tratamento de exceções na programação. Tanto na programação quanto na cozinha, no tratamento de uma exceção é necessário que a cozinha seja limpa e/ou rearrumada para que outros pratos possam ser preparados, reaproveitando ou não o preparo já feito. 