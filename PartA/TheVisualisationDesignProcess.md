# O Processo de Design dos Dados

Neste segundo capítulo, descreverei o processo de design de visualização de dados em torno do qual os capítulos do livro são organizados. Você aprenderá por que usar uma abordagem de processo é importante para organizar e otimizar seu pensamento – levando você desde a centelha inicial de curiosidade, passando por disputas com dados, para fazer malabarismos com as inúmeras opções que moldam uma solução de design.

O processo organiza as atividades em uma sequência de partes gerenciáveis ​​para que as coisas certas sejam abordadas na ordem certa. Você não pode esperar encontrar uma ótima solução por acaso se suas práticas de trabalho são caóticas e confusas. Você será auxiliado por algumas dicas práticas adicionais e bons hábitos para empregar em todo o processo.

A qualidade de sua tomada de decisão é a principal diferença entre uma visualização bem-sucedida e uma que falha. Para maximizar a eficácia de facilitar a compreensão do seu público, as partes seccionais do capítulo apresentarão os três princípios de um bom design de visualização.

## 2.1 Processo de design: organizando sua tomada de decisão

Para quem é novo na área, uma das primeiras coisas a entender é a ideia de que não existe qualquer noção de perfeição na visualização de dados. Pode ser simultaneamente frustrante e libertador saber que existem soluções boas e ruins, mas não existem soluções perfeitas. Para ter perfeição, você precisa de condições imaculadas, livres de pressão, constrangimento ou falha. É assim que as coisas funcionam agora na vida real. Sempre haverá demandas empurrando e puxando você em direções diferentes. Haverá deficiências nos dados que o frustrarão ou limitações na capacidade técnica que o impedirão. Conforme descrito no Capítulo 1, as pessoas, como recipientes, apresentam uma diversidade de necessidades que, na realidade, nem sempre pode ser satisfeita. Reconhecer que o perfeito é inalcançável ajuda a nos aliviar de uma sensação incômoda de que, de alguma forma, podemos ter deixado de encontrar a solução perfeita. Nunca haverá apenas uma única solução possível para um problema.

A premissa central deste livro é que a tomada de decisão é a competência chave na visualização de dados: ou seja, decisões eficazes, tomadas com eficiência. Para conseguir isso, você precisa seguir um processo de design que organize seu pensamento e seja sustentado por princípios robustos para otimizar seu pensamento.

Discutiremos os princípios em breve, mas primeiro vamos analisar brevemente o processo de design geral (Figura 2.1).

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/95d62098-eb5d-4bc3-912a-e227167e0384.png)

_Figura 2.1 Os quatro estágios do processo de design de visualização de dados (1ª estágio: formulando sua apresentação, 2ª estágio: trabalhando com dados, 3ª estágio: estabelecendo seu pensamento editorial, 4ª estágio: desenvolvendo as soluções de design_

Ao longo das quatro etapas que compõem esse processo, existem duas fases principais. Os três primeiros estágios, apresentados na Parte B deste livro até os Capítulos 3 a 5, envolvem atividades que descrevo como relativas ao “pensamento oculto” da visualização de dados. Essas etapas abrangem o trabalho preparatório que informa o que você está visualizando, para quem e, crucialmente, por quê:

1. <strong>Formulando seu briefing</strong>: planejando, definindo e iniciando seu projeto.
2. <strong>Trabalhando com dados</strong>: coletando, manipulando e preparando seus dados.
3. <strong>Estabelecendo seu pensamento editorial</strong>: definindo o que você vai mostrar ao seu público.

A segunda fase principal do processo fica inteiramente com o estágio 4 e isso envolve o desenvolvimento de sua solução de design, a manifestação visual do trabalho preparatório que você realizou. Esta fase está relacionada com o <em>como</em>.

As cinco camadas de design distintas que compõem a anatomia de qualquer solução de visualização – representação de dados, interatividade, anotação, cor e composição – são abordadas na Parte C deste livro, nos Capítulos 6 a 10, respectivamente. Conforme explicado anteriormente, um tratamento detalhado das atividades técnicas está além do escopo deste texto.

Não vou descrever essas etapas do processo com mais profundidade aqui – os próximos oito capítulos existem para fazer isso. Em vez disso, aqui estão algumas observações sobre por que é importante seguir um processo de design.

<strong>Reduzindo a aleatoriedade de sua abordagem:</strong> O valor desse processo de design é que ele molda seus pontos de entrada e fechamento. Como você inicia um processo? Como você sabe quando terminou? Como mencionei, a grande extensão das coisas em que você terá que pensar, mesmo com projetos simples, pode ser uma perspectiva bastante avassaladora. Essa abordagem divide os principais estágios em um sistema de pensamento conectado que ajudará a progredir em seu trabalho e preservar a coesão entre suas atividades. Ele leva você de forma incremental ao desenvolvimento de uma solução, com cada estágio se baseando no anterior e informando o próximo.

<strong>Cada projeto é diferente</strong>: cada visualização apresenta novos desafios. Mesmo que você esteja apenas reproduzindo o mesmo relatório todo mês, não há duas instâncias desse relatório que envolvam exatamente o mesmo contexto. O simples fato de ter um mês a mais de dados, por exemplo, pode expô-lo a valores maiores, valores menores, novos valores e valores expirados. Se você tem dados simples ou grandes quantidades de dados complexos, duas horas ou dois meses, o processo que você segue será sempre o mesmo. Você deve seguir a mesma sequência de pensamento, independentemente do tamanho, velocidade e complexidade do seu desafio. A principal diferença é que quaisquer extremos nas circunstâncias que você enfrenta amplificarão as tensões em cada estágio do processo e exigirão mais da necessidade de uma tomada de decisão completa, eficaz e oportuna.

> Eu costumo continuar me referindo ao brief original (mesmo que seja um briefing que eu mesmo fiz) para continuar verificando se os conceitos que estou criando marcam todas as caixas certas. Ou às vezes fico animado com uma ideia, mas se falo sobre isso com amigos e é difícil descrevê-la de forma eficaz, sei que o conceito não é claro o suficiente. Às vezes, apenas esquecer um pouco ele é o suficiente para separar o bem do mal! Ter um fluxo de trabalho estabelecido é importante para mim, pois me ajuda a cobrir todas as bases de um projeto e me sentir confiante de que meu conceito tem uma lógica sólida.
>
> <small>Stefanie Posavec, Designer de Informação</small>

<strong>Adaptabilidade</strong>: O termo <em>processo</em> contrasta consideravelmente com <em>procedimento</em>. O processo descrito neste livro fornece uma estrutura para pensar, em vez de instruções para aprender e seguir. Um bom processo deve oferecer adaptabilidade e remover a inflexibilidade de um procedimento definido. Em qualquer projeto de visualização, você precisará responder a requisitos revisados, dados adicionais que surgirem ou uma mudança na direção criativa. Um bom processo protege a adaptabilidade e amortece o impacto de circunstâncias mutáveis como essas. Embora as atividades apresentadas neste livro estejam em um arranjo linear, sempre será necessário haver espaço para iteração.

Haverá muitas ocasiões em que você terá que rever decisões ou refazer atividades de uma maneira diferente, especialmente se cometer erros. O que é mais importante nestas situações é como<br>graciosamente você falha e com que rapidez você se recupera.

<strong>Proteja a experimentação</strong>: A abordagem de processo que estou defendendo não é excessivamente sistemática e não compromete o espaço para experimentação. Quando há pressões no tempo, a necessidade de se concentrar e evitar distrações é compreensível. Aspirar a reduzir o esforço desperdiçado e melhorar a eficiência é totalmente razoável, mas ainda é preciso buscar oportunidades – nas circunstâncias certas – para que a imaginação floresça. Na realidade, poucos projetos oferecem muito espaço para uma exploração criativa de longo alcance, mas quando uma oportunidade se apresenta para você trabalhar em um assunto adequado à criatividade, você deve aceitá-la. E não deixe de aproveitar!

> Eu realmente sinto que a experimentação (mesmo por causa da experimentação) é importante, e eu a encorajaria fortemente. Existem infinitas possibilidades de diagramação e comunicação visual, então ainda temos muito a explorar. Acho que uma boa regra é nunca permitir que seu design ou implementação obscureça o entendimento do leitor sobre o ponto central de sua peça. No entanto, eu estaria disposto a renunciar a isso, às vezes, para permitir inovação e experimentação. Isso acaba nos levando para a frente, de uma forma ou de outra.
>
> <small>Kennedy Elliott - Editor Gráfico na National Geographic</small>


<strong>A primeira ocasião, não a última</strong>: cada atividade que você inicia nos diferentes estágios do processo provavelmente representará a primeira ocasião em que você prestará atenção a esses assuntos, mas não a ocasião final. Pense no sequenciamento como sendo semelhante a um efeito <em><a href="https://pt.wikipedia.org/wiki/Economia_do_gotejamento">trickle down</a></em>. Veja, por exemplo, a preocupação recorrente em pensar no seu público. Você primeiro encontrará a necessidade de definir um perfil das características do seu público antecipado durante a primeira etapa do processo, "Formulação de seu brief". No entanto, a preocupação com o que eles sabem, o que eles precisam saber e quão interessados ​​eles estarão irão ocorrer até o fim. Preocupações como essas nunca devem sair do seu radar. A lista de preocupações só aumentará, mas a intenção é que o processo dê a você a melhor chance de manter todos os pratos necessários girando pelo tempo que precisarem.</p>

Ao longo do livro, há vinhetas frequentes de conselhos e dicas úteis para você adotar para aproveitar ao máximo esse processo. Estes são informados por entrevistas com pessoas que trabalham no campo, bem como por minhas próprias experiências práticas, e são fornecidos com cada tópico. Existem alguns hábitos recomendados que são aplicáveis ​​a todas as etapas deste processo, relevantes para novatos ou visualizadores experientes, como segue.</p>

<strong>Gestão do tempo</strong>: Qualquer trabalho criativo rapidamente engole todo o tempo disponível. Você fica tentado a experimentar coisas, explorar ideias diferentes, tentar uma última tentativa de buscar características interessantes de seus dados. É fácil ser consumido pelas demandas de alongamento das atividades ao longo deste processo. Quando você chega a um prazo, ou afunda ou nada: para alguns, a pressão do tique-taque do relógio é incapacitante, afetando especialmente seu pensamento criativo; outros prosperam com a adrenalina que desperta, aguçando seu foco como resultado. </p>

Independentemente de como você responde aos prazos iminentes, um bom planejamento é vital. A gestão do tempo é a essência de um bom planejamento. Mantém um processo coeso e no caminho certo. Com a experiência de trabalhar em diferentes projetos, sua capacidade de prever quanto tempo alocar para diferentes atividades melhorará. Dito isso, cada projeto apresenta seu próprio perfil de demandas, portanto, sempre encontre tempo antes de partir para estimar onde seus prováveis ​​compromissos serão mais necessários. Não se esqueça de considerar o tempo para responsabilidades facilmente negligenciadas, como reuniões de supervisores, chamadas pelo Skype, pesquisa e gerenciamento de arquivos.</p>

<strong>Mindsets</strong>: Independentemente do tipo de visualização em que você está trabalhando, seu processo envolverá uma mistura de atividades conceituais e práticas. Às vezes, eles serão alocados em uma equipe, explorando a variedade de talentos em diferentes momentos do processo. Em outras ocasiões, você estará trabalhando sozinho, e a diversidade dessas atividades aumentará consideravelmente sua mente. Às vezes você está pensando, às vezes você está criando; às vezes você precisa ser criativo, às vezes você precisa ter um olho nos detalhes</p>

* <em>Pensamento</em>: Os deveres aqui serão de natureza conceitual, exigindo imaginação e julgamento, como formular sua curiosidade, definir as necessidades de seu público, raciocinar suas perspectivas editoriais e tomar decisões sobre escolhas de design viáveis.
* <em>Fazer</em>: São tarefas ativas que envolvem o cérebro através de empreendimentos mais práticos, como esboçar ideias, conduzir pesquisas, manter discussões com um cliente ou verificar dados.
* <em>Criação</em>: São tarefas construtivas mais práticas, caracterizadas pelo uso de ferramentas para atividades como manipulação de dados, criação de gráficos e design de recursos de apresentação.

> Você precisa de um olho de design para projetar e um olho de não-designer para sentir o que você projetou. Como disse Paul Klee, "Veja com um olho, sinta com o outro".
>
> <small>Oliver Reichenstein, fundador da Information Architects (iA)</small>

Para o escopo deste livro, o foco está em grande parte no pensamento. Acho a noção de "estados" cerebrais relevante aqui, especialmente o estado "alfa". Este é o estado em que nossa mente está, mais comumente, quando nos sentimos especialmente relaxados. Ocupar esse estado ajuda a aumentar sua imaginação e processo de pensamento. Acho que faço alguns dos meus pensamentos mais astutos no chuveiro ou logo antes de dormir à noite. Essas são as ocasiões em que provavelmente estou entrando em um estado relaxado. Encontro as mesmas condições ao realizar longas viagens de trem ou voos. Eu o uso para ajudar a contemplar o progresso que estou fazendo em uma tarefa. Isso me permite escapar do ruído presente ao fazer tarefas mais práticas.

> Como falo a linguagem dos dados, posso falar com bastante eficiência com os especialistas que os criaram. Não demora muito, mesmo que o assunto seja novo para mim, para que eles me digam quaisquer ressalvas ou tendências importantes. Também acho que é porque abordo essa conversa como jornalista, onde estou principalmente para ouvir. Acho que se você ouvir, as pessoas falam. (Parece tão óbvio, mas é tão importante.) Acho que se você fizer uma pergunta perspicaz, algo que os faça dizer “oh, isso é um bom ponto”, toda a conversa se abre. Agora vocês dois estão do mesmo lado, tentando levar esses ótimos dados ao público de uma maneira compreensível.
>
> <small>Katie Peek, Designer de Visualização e Jornalista Científica</small>

<strong>Documentação</strong>: É tolice afirmar que a caneta e o papel são humildes ferramentas importantes para os visualizadores. Afinal, a menos que você esteja produzindo trabalhos artesanais desenhados à mão, os aplicativos técnicos serão mais aplicáveis ​​para a maior parte do seu processo. No entanto, caneta e papel provarão ser um verdadeiro aliado para ajudá-lo a documentar pensamentos e capturar esboços. Não confie em sua memória; se você tem uma grande ideia, esboce-a. Você não precisa de grande talento artístico, só precisa tirar as coisas da cabeça e colocá-las no papel, principalmente se estiver colaborando com outras pessoas. Se você tiver a sorte de ser fluente com uma ferramenta e achar mais natural usá-la para “esboçar” ideias do que caneta e papel, então isso é absolutamente bom, desde que seja o meio mais rápido para fazê-lo.

Seja usando caneta e papel, ou uma ferramenta como Word ou Google Docs, tomar notas é um hábito útil para desenvolver. Ele ajuda você a documentar detalhes importantes, como:

* Listas de tarefas com detalhes de prazos e precedentes;
* Informações sobre as fontes de dados que você está usando;
* Detalhes de cálculos ou manipulações complicadas que você aplicou aos seus dados;
* Um registro de quaisquer suposições que você tenha feito;
* Terminologia, abreviaturas, siglas – propriedades técnicas dos seus dados que são cruciais para a sua compreensão;
* Perguntas e respostas que você recebeu ou ainda não recebeu;
* Questões ou problemas que você experimentou ou pode prever;
* Listas de desejos de recursos ou ideias que você gostaria de explorar;
* Fontes de inspiração, como sites ou revistas que você descobre;
* Ideias que você teve ou rejeitou.

Tomar notas é mais facilmente pregado do que feito. Eu sou o menos competente dos anotadores, mas encontrei uma maneira de tornar isso um hábito forçado e isso se mostra valioso.

<strong>Comunicação</strong>: A comunicação é uma atividade de mão dupla. Trata-se de ouvir as partes interessadas e o seu público: o que eles querem, o que esperam, que ideias têm? Em particular, que conhecimento eles têm sobre o seu assunto? A comunicação é falar com os outros: apresentar ideias, atualizar o progresso, buscar feedback, compartilhar seus pensamentos sobre possíveis soluções e promovendo e vendendo seu trabalho (independentemente do cenário, você precisará fazer isso). Você não pode evitar as demandas de comunicação, então não se esconda atrás de seu laptop – saia e interaja com pessoas que podem ajudar ou a quem você pode ajudar.

Associada à necessidade de boas habilidades de comunicação está a importância da pesquisa. Você não pode saber tudo sobre seu assunto, sobre o significado de seus dados, sobre as qualidades relevantes e irrelevantes que ele possui. Como você verá mais tarde, os dados em si só podem nos dizer muito; muitas vezes, apenas nos diz onde podem existir coisas interessantes, não o que realmente explica por que elas são interessantes. Converse com pessoas inteligentes que conhecem um assunto melhor do que você ou com pessoas que não conhecem o assunto, mas são apenas inteligentes.

> Pesquisa é fundamental. Dados, sem interpretação, são apenas uma mistura de palavras e números – fora de contexto e desprovidos de significado. Se bem feita, a pesquisa não apenas fornece uma base sólida sobre a qual construir seu gráfico/visualização, mas também atua como uma fonte de inspiração e um guia para a criatividade. Um bom pesquisador deve ser um jogador de equipe com a capacidade de pensar criticamente, analiticamente e criativamente. Eles devem ser um solucionador de problemas proativo, identificando possíveis armadilhas e fornecendo vários roteiros para superá-las. Em suma, sua inclusão deve ampliar e não restringir os talentos dos outros.
> 
> <cite><strong>Amanda Hobbs</strong>, Pesquisadora e Editora de Conteúdo Visual</cite>

<strong>Atenção aos detalhes</strong>: O processo que você segue incorpora o conceito de “agregação de ganhos marginais”. Você precisa observar as pequenas coisas. Mesmo que muitas de suas decisões pareçam pequenas e inconsequentes, elas merecem toda a sua atenção. Assim como as anotações, a importância de verificar cada detalhe pode não ser uma característica natural para alguns. No entanto, erros encontrados em seu trabalho podem ser prejudiciais e certamente prejudicarão a confiança do seu público, como você aprenderá em breve. Eu sei por experiência como um erro pode minar a integridade de um projeto inteiro, mesmo que isso pareça injusto e desproporcional considerando tudo o que estava correto. Comece cada projeto com o compromisso de eliminar erros e aprender com a dor quando você falha. Não é fácil: não tenho dúvidas de que deixarei pelo menos um erro neste livro e ele me assombrará. Pode ajudar, se você está tão imerso em seu próprio trabalho e se torna cego para ele, procure outros profissionais para ajudá-lo.

<strong>"Mate seus queridinhos"</strong>: Uma consequência recorrente de enfrentar tantas decisões na visualização é a necessidade de demonstrar a disciplina de não fazer algo. É fácil aplaudir a si mesmo por ideias brilhantes, mas ocasionalmente essas ideias nas quais você investiu profundamente simplesmente não funcionarão. Mesmo que você tenha investido pesadamente em tempo e energia emocional, não seja teimoso. Quando algo não está funcionando, aprenda a matá-lo. Caso contrário, tal preciosidade impedirá a qualidade do seu trabalho. Ficar cego para coisas que não estão funcionando ou ignorar o feedback construtivo dos outros será destrutivo.

<strong>Aprender</strong>: A aprendizagem reflexiva consiste em rever o seu trabalho, examinar o resultado e avaliar a sua abordagem. O que você fez bem? O que você faria de diferente? Quão bem você gerenciou seu tempo? Você tomou as melhores decisões que pôde, dadas as restrições que existiam? Aprenda com os outros. Leia como outras pessoas enfrentam seus desafios de visualização. Talvez compartilhar o seu? Você descobrirá que realmente aprende sobre algo quando encontrar espaço para escrever sobre isso e explicá-lo aos outros. Escreva seus projetos, apresente seu trabalho para outras pessoas e, ao fazê-lo, isso o forçará a pensar "por que fiz o que fiz?"

Use também a aprendizagem reflexiva para encontrar seu processo. O que é apresentado neste livro é proposto, não imposto. Se você não conseguir que essa abordagem se adeque à sua personalidade, ao propósito do seu projeto ou ao ritmo de como você precisa trabalhar com os outros, modifique-a. Nós somos todos diferentes. Tome isso como uma estrutura recomendada, mas depois dobre-a, estique-a e faça-a funcionar para você. À medida que você se torna mais experiente (e confiante por ter sido exposto a diferentes desafios), as atividades envolvidas no design de visualização de dados se tornarão uma segunda natureza. Você provavelmente se tornará felizmente inconsciente até mesmo de observar um processo.

## 2.2 Princípios de design: otimizando sua tomada de decisão

Se o objetivo da visualização de dados, conforme definido no primeiro capítulo, é facilitar o entendimento, todos os julgamentos feitos durante o processo de design devem contribuir para isso.

A maioria das escolhas é relativamente clara e basear seu julgamento no bom senso, informado pelos três primeiros estágios preparatórios, será inteiramente razoável. No entanto, para situações mais sutis, quando podem haver várias opções complexas se apresentando, você enfrentará um dilema. Fazer uma escolha exigirá mais do que apenas bom senso. É quando ajuda consultar uma estrutura de princípios de design.

Na visualização de dados, existem relativamente poucas regras universais a serem seguidas. Existem sugestões úteis baseadas em evidências que o levam a “sempre faça isso” e “nunca faça isso”, mas mesmo elas estão expostas a um ponto de ruptura legítimo. Isso ocorre porque cada decisão que precisa ser tomada é acompanhada por muitas dependências contextuais.

Os princípios que informam minhas próprias convicções de design de visualização originaram-se além dos limites deste assunto. Dieter Rams foi um designer industrial e de produtos alemão mais famoso associado à empresa Braun. Por volta do final dos anos 1970 e início dos anos 1980, ele estava se preocupando com o estado e a direção do <em>design thinking</em> e, dado seu papel proeminente na indústria, sentiu a responsabilidade de desafiar a si mesmo, seu próprio trabalho e seu próprio pensamento. Ele fez a pergunta simples: 'Meu design é bom design?' Ao dissecar seu trabalho em resposta a essa pergunta, ele concebeu dez princípios que simbolizavam os aspectos importantes do que ele considerava um bom design (Figura 2.2).

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/b7c37f9c-0c4d-4dad-8f95-5bc1e0ce5b8f.png)

_Figura 2.2 Dieter Rams - Dez Princípios do Bom Design_

1. Bom design é inovativo
2. Bom design fazer um produto útil
3. Bom design é estético
4. Bom design faz um produto compreensível
5. Bom design é discreto
6. Bom design é verdadeiro
7. Bom design é duradouro
8. Bom design é minucioso até o último detalhe
9. Bom design é ambientalmente amigável
10. Bom design é um o mínimo de design possível

Em '<em>De architectura</em>', uma tese sobre arquitetura escrita por volta de 15 a.C. por <a href="https://pt.wikipedia.org/wiki/Vitr%C3%BAvio" target="_blank" rel="noreferrer noopener">Marcus Vitruvius Pollio</a>, um arquiteto romano, o autor declara que a essência da qualidade na arquitetura é moldada pela relevância social da obra, não pela forma ou acabamento final para aquela forma. Ele afirma que uma boa arquitetura só pode ser medida de acordo com o valor que ela traz para as pessoas que a utilizam. Em uma tradução da obra de 1624, Sir Henry Wotton oferece uma versão parafraseada de uma das noções mais duradouras de Vitruvius de que uma “construção de poços tem três condições: firmeza, comodidade e prazer”. Uma tradução atualizada disso seria “robusta, útil e bonita”.

Coletivamente, essas fontes separadas informaram os três princípios chave mostrados na Figura 2.3 que acredito se aplicarem a qualquer julgamento de eficácia na visualização de dados.


![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/21be3783-9936-4d40-a8a3-425270c2adf3.png)

_Figura 2.3 Os Três Princípios do Bom Design de Visualização_

<strong>É confiável?</strong>
O tratamento dos dados é razoável e fiel ao titular? O design de representação e apresentação tem integridade?

<strong>É utilizável?</strong>
A representação dos dados e do assunto é relevante? O design de representação e apresentação é adequadamente incompreensível?

<strong>É estético?</strong>
A representação e a apresentação são atraentes?

À medida que você passa pelo processo, esses princípios guiarão as escolhas que você faz. Vamos examiná-los com mais detalhes, enquadrando-os em relação aos dez princípios de bom design de Rams, bem como aos três de Vitruvius.

## Princípio 1: Um bom design de visualização é confiável

Este primeiro princípio é tornar sua visualização confiável, que mapeia diretamente um dos dez princípios de Dieter Rams (Figura 2.4) e incorpora o desejo de Vitruvius por robustez. Trata-se de confiabilidade e é alcançado garantindo e sustentando a confiança de seu público.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/a9e8f924-4207-4af7-be15-4df8da36381d.png)

_Figura 2.4 Mapeamento de 'confiabilidade' nos dez princípios dos carneiros_


> "O bom design é honesto. Não faz um produto parecer mais inovador, poderoso ou valioso do que realmente é. Não tenta manipular o consumidor com promessas que não podem ser cumpridas."
>
><cite>Dieter Rams</cite>

A dificuldade para um visualizador surge quando há potencialmente múltiplas versões diferentes, mas legítimas, de uma “verdade” dentro do mesmo contexto de dados ou assunto. Isso atrapalha um pouco as coisas. Um copo meio cheio também está meio vazio. Ambos os pontos de vista são objetivamente verdadeiros, mas o que você escolhe focar é subjetivo. Na visualização de dados raramente há uma visão única da verdade. Você faz a ligação sobre o que é mais relevante no contexto do seu trabalho. Isso é algo que exploraremos no Capítulo 5 sobre pensamento editorial.

Mesmo que a escolha feita possa ser imparcial, é o ato de escolher que cria uma forma inevitável de viés. Quando você escolhe fazer uma coisa, geralmente está escolhendo não fazer outra. A decisão de mostrar as previsões para um partido político vencedor de uma eleição mudando ao longo do tempo usando um gráfico de linhas também pode incorporar a decisão de não mostrar como a previsão se parece geograficamente, supondo que os dados estejam disponíveis. Qualquer visualização será uma agregação de decisões entre as quais muitas são moldadas por uma razoável subjetividade. Nenhuma visualização é puramente objetiva, mesmo que pareça retratar essa qualidade.

Em vez de ser consumido pela inevitabilidade dos preconceitos que se espalham pelo seu trabalho, e talvez ver isso como uma boa razão para não empreendê-lo, seu foco é mais bem direcionado para garantir que o caminho escolhido seja confiável. Na ausência de uma única verdade objetiva, o que você pode fazer para garantir a confiança em sua verdade subjetivamente selecionada?

A confiança deve ser conquistada, mas é difícil de garantir e fácil de perder. Como diz a tradução de um provérbio holandês, “a confiança chega a pé e parte a cavalo”. Confiança é algo que um visualizador deve tentar nutrir por meio de precisão e transparência, eliminando dúvidas ou disputas legítimas de um espectador. No entanto, é mais fácil falar do que fazer, pois os visualizadores têm apenas uma certa quantidade de controle sobre isso porque nosso público são pessoas. Sim, eles novamente. Uma visualização pode ser verdadeira, mas vista, irracionalmente, como não confiável. Por outro lado, uma visualização que pode não ser verdadeira ainda pode ser confiável (talvez um resultado mais perigoso que abra uma discussão separada, mas um para outros livros abordarem). Nenhuma dessas experiências é satisfatória: as últimas podemos e devemos evitar; o primeiro é algo que nos esforçamos para derrubar.

Vamos considerar um exemplo que ilustra a fragilidade da confiança. Na Figura 2.5, o gráfico mostrado exibe o número de assassinatos cometidos com armas de fogo na Flórida durante um determinado período de tempo. Os dados são enquadrados em torno da promulgação da lei 'Stand Your Ground' (algo como <em>Mantenha-se firme</em> em tradução livre) em 2005. O gráfico usa um eixo y vertical invertido com uma área preenchida de vermelho ocupando o espaço abaixo da linha de base do eixo x, crescendo para baixo à medida que o número de mortes aumenta. Alguns dos valores de pico estão em 1990 e 2007.

Quando este artigo foi publicado, muitos comentaristas reclamaram às pressas, comentando como a inversão do eixo y os havia enganado. Eles confundiram a área vermelha com o plano de fundo e viram os dados como formados pela “montanha branca” emergindo em primeiro plano. Ao interpretar mal o gráfico, eles estavam vendo os valores de pico como sendo os de 1999 e 2005, os pontos mais altos dessa aparente montanha branca. Essa ilusão é causada por um efeito conhecido como percepção figura-fundo pelo qual uma forma de fundo (a área branca) pode ser inadvertidamente reconhecida como a forma de primeiro plano, e vice-versa com a área vermelha vista como o fundo. Apesar de eventualmente ler o gráfico e poder descobrir a visão correta do gráfico, para muitos espectadores, qualquer confiança foi perdida: eles sentiram que foram enganados. Uma acusação exacerbada, sem dúvida, pela natureza emotiva do assunto: qualquer quadro sobre crimes com armas de fogo desperta paixões independentemente de sua forma.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/29556905-0536-4bb5-85e2-97f9701bfa99.png)

_Figura 2.5 Mortes por armas na Flórida (Reuters)_

Embora a abordagem para inverter o eixo y possa não ser totalmente convencional, era uma abordagem legítima. O problema foi sem dúvida causado pela linha de grade visualmente proeminente para 1000 que inadvertidamente emoldurou a “montanha branca”, mas, criativamente falando, tentar transmitir o efeito de pingar sangue era uma metáfora plausível a ser seguida.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/ea9ca29b-f6fb-49eb-8620-27e2ababfd9b.png)

_Figura 2.6 O pedágio sangrento do Iraque, por Simon Scarr (South China Morning Post)_


Ele estava emulando um trabalho de visualização proeminente e célebre, de vários anos atrás, mostrando o número de mortos durante o conflito no Iraque (Figura 2.6). Ser inspirado e influenciado pelas técnicas demonstradas por outros visualizadores é algo a ser incentivado como uma forma importante de aprimorar nossas habilidades.

O ponto chave é que não houve intenção de enganar. A falta de confiança expressa por alguns foi consequência de um conjunto bem intencionado de decisões de design. Isso demonstra como a confiança é vulnerável, especialmente no ambiente pressionado de uma redação, onde a produção de trabalho é implacável e muitas vezes há apenas uma única oportunidade de publicar uma determinada peça para um público enorme e amplo. Mesmo nesta era de plataformas de mídia em grande parte digitais, é difícil interceptar, retirar e revisar o trabalho. “Você não tem uma segunda chance para causar uma primeira impressão”, como diz o ditado.


### O Tratamento dos Dados é Razoável e Fiel ao Sujeito?

A confiabilidade é uma causa que deve guiar todas as suas decisões, não apenas aquelas que surgem na fase final do processo focada no design. Os princípios são enquadrados como princípios de design porque é através do seu trabalho de design que todas as suas decisões se materializarão visualmente. Ganhar confiança é algo que vai desde a primeira tarefa preparatória.

É durante o primeiro estágio que as sementes iniciais são costuradas para como você pode lidar criativamente com seu assunto. Como você acabou de testemunhar, se estiver trabalhando em tópicos potencialmente emotivos, isso apenas aumentará a exposição potencial a preconceitos e opiniões. Como você aprenderá no Capítulo 3, ao considerar seu assunto e estabelecer suas ideias sobre o propósito de seu trabalho, haverá alguns contextos que se prestam a explorar as qualidades emotivas de seu assunto, mas outros não. A confiança será prejudicada se você tiver julgado mal o tom de voz.

> Os dados e os conjuntos de dados não são objetivos; são criações do design humano. Os vieses ocultos nos estágios de coleta e análise apresentam riscos consideráveis [em termos de inferência].
>
> <cite>Kate Crawford, pesquisadora principal da Microsoft Research NYC</cite>

Trabalhar com dados, o segundo estágio do processo, é indiscutivelmente onde a confiança está mais em jogo. Você é o depositário com a responsabilidade de ser fiel aos dados que possui e ao assunto que os incorpora. Você precisa ter cuidado com o manuseio dos dados e ser transparente com o que decide fazer com eles. Há perguntas críticas que você pode precisar responder para garantir que sua abordagem para lidar com os dados seja razoável, como as seguintes:

* Como os dados foram coletados: de onde e usando qual método?
* Que cálculos ou modificações você aplicou?
* Você fez suposições significativas ou aplicou alguma regra de contagem específica?
* Quais critérios foram usados para os valores de dados que você decidiu incluir e excluir da exibição?

### O design de representação e apresentação tem integridade?

Um princípio fundamental da visualização de dados é nunca enganar o receptor. Evitar possíveis mal-entendidos, imprecisões, confusões e distorções é a principal preocupação quando se pensa na integridade de como seu trabalho é representado e apresentado. Existem muitos recursos possíveis de design de visualização que podem levar a vários graus de desconfiança, intencional ou não, conforme exibido no exemplo anterior; Explorarei muitos deles mais adiante:

* Às vezes, os gráficos são usados ​​de maneiras que efetivamente corrompem seu uso. Um exemplo seria usar gráficos de pizza para exibir partes de porcentagem que excedem 100%.
* Experiências funcionais não confiáveis ​​com projetos interativos. A solução funciona e, especificamente, funciona da maneira que promete ou se espera que funcione (como a velocidade de carregamento)?
* Anotações ausentes, como títulos claros, introduções, títulos de eixos, rótulos, notas de rodapé e fontes de dados. Todos esses recursos ajudam o espectador a entender o que está consumindo; quando eles estão faltando, pode levar à confusão e suspeita.
* Erros cometidos com quaisquer estatísticas ou legendas apresentadas irão manchar a precisão percebida de todo o trabalho.
* O eixo quantitativo de um gráfico de barras não deve ser 'truncado'. Ou seja, o valor de origem da linha de base deve ser zero, caso contrário, a exibição resultante distorcerá os julgamentos de tamanho de barra percebidos.
* O tamanho das áreas geométricas, como os tamanhos dos círculos, às vezes pode ser mal calculado usando o diâmetro como base da variação do tamanho em vez da área da forma. Isso resulta em valores quantitativos desproporcionalmente dimensionados.
* Quando um gráfico baseado em duas dimensões de dados é apresentado em formato 3D, mas consumido em formato 2D (como uma exibição estática em uma tela ou impresso), essa escolha de design decorativo distorce os tamanhos de valor percebido - você não pode ajustar seu ponto de vista para acomodar por perspectiva, distância do processo ou ver recursos obstruídos. Assim, o 3D só deve ser considerado quando há meios dinâmicos para um espectador mudar seu ponto de vista para navegar em torno de uma forma 3D e vê-la de perspectivas 2D sob medida.
* A proporção de aspecto (altura x largura) da exibição de um gráfico de linhas pode afetar a inclinação percebida das linhas de conexão que revelam as tendências de uma série contínua de valores ao longo do tempo. Se a área da carta for muito estreita, a inclinação será embelezada; muito largo e a inclinação é amortecida.
* Ao retratar a análise espacial através de um mapa temático, existem diferentes projeções de mapeamento que traduzem um globo esférico em um mapa 2D achatado. O tratamento matemático aplicado a essa tradução pode alterar significativamente o tamanho ou a forma percebida das regiões, potencialmente distorcendo sua percepção. Mais sobre isso no Capítulo 10.
* O tamanho ou a sequência no layout de uma obra pode levantar suspeitas se conteúdos aparentemente importantes forem diminuídos na hierarquia visual, como empurrados para o fundo ou reduzidos em tamanho.

Os exemplos nas Figuras 2.7 e 2.8 exibem dois gráficos mostrando a mesma análise, mas apresentados de forma diferente. Reserve um momento para refletir sobre quanta confiança você sente que é alcançada por essas respectivas peças. Para contextualizar, ambos foram extraídos de artigos que discutiam questões sobre a propriedade da casa própria, de modo que normalmente seriam apresentados juntamente com a análise escrita em sua forma original publicada.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/78d939a3-a534-4ddc-871b-c9e40855b7ee.png)

_Figura 2.7 Habitação e Propriedade de Casas no Reino Unido (Equipe de Conteúdo Digital ONS)_


![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/70b5a942-cede-4c11-9dfd-a59bf51c31e1.png)

_Figura 2.8 Número decrescente de jovens proprietários (Daily Mail)_

Como eu disse, ambos os gráficos usam os mesmos dados e usam o mesmo tipo de gráfico para representar a análise; chegam até mesmo à mesma conclusão sumária. No entanto, na minha opinião, o primeiro gráfico, produzido pelo Escritório de Estatísticas Nacionais do Reino Unido (ONS), possui maior credibilidade e autoridade e, portanto, muito mais de minha confiança, do que a segunda visualização, produzida pelo Daily Mail.

A primeira razão para esta opinião diz respeito a como a peça do ONS é mais informativa e transparente sobre os dados e o assunto. Enquanto o Daily Mail se refere ao ONS como fonte dos dados, ele não inclui mais detalhes sobre a fonte de dados, informações que estão incluídas no gráfico do ONS ao lado de outros recursos como a legenda, uma explicação sobre os períodos anuais. opções de cores para as barras. A opção de ver e baixar os dados associados é exclusiva do gráfico do ONS, pois foi publicado na Web, portanto, é injusto contrastar a ausência desse recurso no gráfico do Daily Mail.

A segunda razão é mais instintiva e influenciada pelo meu gosto pessoal. As cores utilizadas no gráfico do ONS são reservadas, mas esteticamente atraentes e transmitem uma certa segurança. Por outro lado, a paleta de cores do Daily Mail parece carente. Parece estar desejando atenção com bastões coloridos e doces doentios. A imagem da chave da casa no fundo é visualmente inofensiva, mas parece preguiçosa e derivada. O tipo de letra, o tamanho da fonte e a coloração do texto parecem baratos. O texto do ONS é educado e transmite autoridade. Esses recursos de apresentação são estilísticos e, portanto, mais ponderados no sentido de buscar a "elegância" em seu design, como descreveremos em breve, mas os três princípios estão inquestionavelmente interconectados em alguns lugares.

No geral, minha opinião sobre o nível de confiança que tenho nessas peças é parcialmente razoável e parcialmente irracional. Crucialmente, também é muito influenciado pelos preconceitos que trago para o encontro. Não confio no Daily Mail como fonte de qualquer informação, ao passo que confio no ONS. É difícil desfazer esses sentimentos e preconceitos que trazemos para o processo de visualização. A plataforma e o local em que seu trabalho é publicado (por exemplo, site ou local de origem) serão influentes: as visualizações encontradas em mídias já suspeitas criarão obstáculos difíceis de superar.

### Princípio 2: Um bom design de visualização é acessível</a></h4>

Este segundo princípio é tornar sua visualização acessível, que mapeia três dos dez princípios de bom design de Dieter Rams (Figura 2.9), bem como o desejo de Vitruvius de ser útil.


![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/68441f93-1e97-4110-a342-6ad7cb21dbff.png)

_Figura 2.9 Mapeamento de 'acessibilidade' nos dez princípios de Rams_

A acessibilidade no design de visualização está preocupada em dar ao seu público acesso a uma compreensão útil. Deve ser relevante para o assunto e relevante para as suas necessidades. Isso precisa ser alcançado de uma forma que não exija esforço indevido para perceber, interpretar e compreender.

### A representação dos dados e o assunto são relevantes?

O primeiro aspecto da acessibilidade diz respeito à relevância da visualização que você está retratando para o seu público. Julgar a relevância é uma questão subjetiva e contextualizada relacionada à utilidade potencial de sua visualização: estou fornecendo ao meu público acesso ao entendimento mais útil sobre esse assunto? Relevância é um conceito um tanto mutável que é, em parte, baseado em qualidades como interesse e pertinência.

Também é, fundamentalmente, moldado pelo que você realmente tem disponível para apresentar ao seu público. Você pode criar a visualização mais lindamente projetada, mas se ninguém achar relevante a análise específica que você escolheu retratar sobre um assunto, qualquer motivação que seu público teve para se envolver com seu trabalho pode ser prejudicada.

Imagine que você está visitando uma cidade pela primeira vez e pede ajuda a um transeunte para chegar à estação ferroviária principal. Infelizmente, eles não podem guiá-lo até a estação, mas sabem como chegar à biblioteca principal. Nessas circunstâncias, o que era útil para você aprender não correspondia ao que era possível para o transeunte transmitir. As instruções para a biblioteca não lhe dão acesso ao entendimento que você realmente precisa e, portanto, são irrelevantes. No entanto, suponha que você descubra mais tarde que a estação ferroviária fica do outro lado da rua da biblioteca; as informações disponíveis sobre como chegar à biblioteca agora são instantaneamente promovidas a serem relevantes. É apenas uma pena que seja tarde demais.

> "A principal diferença que eu acho na produção de visualização de dados/infográficos a serviço do jornalismo versus outros contextos (como a arte) é que sempre há um objetivo subjacente e final: ser útil. Não apenas bonito ou eficiente – embora algo possa (e deva!) ser tudo isso. Mas o jornalismo apresenta um certo conjunto de restrições. Um jornalista deve sempre fazer a pergunta: como posso tornar isso mais útil? Como o que estou criando pode ajudar alguém, ensinar alguém, mostrar algo novo a alguém?"
>
> <cite>Lena Groeger, Jornalista Científica, Designer e Desenvolvedora da ProPublica</cite>

Qualquer julgamento de relevância também será determinado pelo nível de sofisticação do conteúdo. No glossário de termos da Introdução, você verá a distinção entre termos <em>complexos</em> e <em>simples</em>. Como visualizador, você pode julgar mal o nível de sofisticação exigido pelo seu público e simplificar demais um assunto complexo. Talvez houvesse muitas perspectivas interessantes sobre o assunto que você poderia e deveria ter incluído, mas em vez disso você apenas apresentou um gráfico simplificado e isso pode disfarçar muitas das principais nuances sobre o assunto. Da mesma forma, talvez você tenha feito um grande esforço para incluir várias visualizações de gráficos relacionados que fornecem uma ampla cobertura de diferentes aspectos do seu assunto, quando o que seu público precisa é apenas de um gráfico simples e alguns insights rápidos de título. Em cada caso, você não forneceu acesso adequado ao conteúdo relevante.

Isso é evidentemente uma coisa difícil de julgar, especialmente quando você tem um público variado com diversos interesses. Você só pode fazer muito, e certamente não deve esperar acertar para todos os espectadores em potencial. Mas é uma questão crucial para se preocupar. A maioria dos tópicos e atividades abordados nos Capítulos 3, 4 e 5 se preocupam em guiá-lo para um julgamento razoável de relevância.

### O Design de Representação e Apresentação é Adequadamente Compreensível?

Em contraste com a relevância, a adequação do design analisa a utilidade de uma perspectiva diferente. Isso é menos sobre a consequência do uso de uma visualização e mais sobre a compreensão de como usá-la.

A acessibilidade no design é alcançada removendo quaisquer obstruções relacionadas ao design e ao conteúdo enfrentadas por seus espectadores. Expresso de outra forma, pensando no oposto de acessível (confuso), você pode garantir que um espectador evite uma experiência confusa com seu trabalho? A confusão é o atrito entre o ato de compreender (esforço) e a obtenção da compreensão (recompensa).

O que constitui atrito mínimo é moldado, inevitavelmente, pelo contexto e pelas características do público, o que torna a noção de acessibilidade um conceito um tanto variável. Nem sempre é possível eliminar o atrito, e é por isso que um julgamento de atrito “adequado” é uma perspectiva pragmática a ser adotada. Os esforços precisam ser proporcionais às recompensas oferecidas. Nem todo processo de compreensão pode ou deve ser rápido e simples, mas alcançar acessibilidade significa eliminar atrasos desnecessários nesse processo.

Demonstrar empatia pelo seu público, apreciar o ambiente em que eles encontram seu trabalho e como eles precisam usá-lo estão no centro do pensamento de design acessível. Aqui estão alguns dos fatores mais cruciais.

> "Devemos prestar a mesma atenção para entender o objetivo do projeto em relação ao seu público. Isso envolve a compreensão de princípios de percepção e cognição, além de outros fatores relevantes, como cultura e níveis de educação, por exemplo. Mais importante, significa combinar cuidadosamente as tarefas na representação com as necessidades, expectativas, conhecimentos, etc. do nosso público. As visualizações são projetos centrados no ser humano, pois não são universais e não serão eficazes para todos os seres humanos de maneira uniforme. Como produtores de visualizações, sejam elas concebidas para exploração de dados ou comunicação de informações, precisamos levar em consideração aqueles que estão do outro lado da equação e que enfrentarão os desafios de decodificar nossas representações."
>
> <cite>Isabel Meirelles, Professora, Universidade OCAD (Toronto)</cite>

Entendendo um assunto: O que seu público sabe e não sabe sobre um assunto terá uma influência significativa no grau em que eles consideram uma visualização acessível. O que é considerado inacessível para um grupo de público pode ser totalmente acessível para outro. Ler uma placa de rua escrita em japonês é totalmente inacessível para quem não fala japonês, mas seria totalmente acessível para alguém que conhece o idioma. Se essa placa de rua for encontrada em Tóquio, é contextualmente apropriada, mas em [Newcastle upon Tyne](https://pt.wikipedia.org/wiki/Newcastle_upon_Tyne) não seria.

Como demonstrei no primeiro capítulo ao interpretar os gráficos sobre futebol e "Winglets and Spungles", se você não entender um assunto, isso instantaneamente aumenta as chances de confusão por ignorância. A interpretação é impedida.

Embora o conhecimento existente seja importante, a principal propriedade do assunto que mais influencia a acessibilidade é o nível intelectual que ele incorpora. Em outras palavras, é um assunto complicado, complexo ou simples para qualquer um entender? Isso nos leva novamente a uma discussão sobre a semântica da linguagem, mas essas diferenças são cruciais em como fazemos julgamentos sobre a adequação da acessibilidade:

* <em>Complicado</em> refere-se ao conhecimento do assunto ou uma habilidade que é tipicamente intrincadamente técnica, provavelmente única e difícil de entender. Requer um certo nível de intelecto ou talento inerente para fazê-lo. A matemática que sustentou os pousos na Lua é complicada. O funcionamento interno de uma caldeira é complicado. Fazer o bolo <em>Baked Alaska</em> (com sucesso) é complicado. O conhecimento ou habilidade em questão é adquirível e o aprendizado envolvido é superável, mas somente alcançado através de muito tempo, trabalho árduo e, geralmente, com a ajuda de especialistas externos.
* <em>Complexo</em> está associado a sistemas ou contextos que não têm conclusão perfeita ou mesmo estado final. Gerenciar relacionamentos é complexo. O mesmo com a paternidade: há livros e pessoas oferecendo conselhos, mas não há um livro de regras sobre como fazê-lo bem o tempo todo – nenhuma maneira definitiva de realizá-lo. Os elementos da paternidade podem não ser necessariamente complicados – como lembrar de cortar as cascas dos sanduíches de Sergio para evitar uma birra – mas as naturezas inter-relacionadas de eventos e pressões estão se moldando e colidindo para torná-lo muito difícil de dominar.
* <em>Simples</em>, para os propósitos deste livro, diz respeito a um assunto que é inerentemente fácil de entender. Pode ser pequeno em dimensão e escopo, o que significa que não há muito conhecimento para adquirir e é improvável que exija muita prática para sustentar, independentemente da experiência anterior. Também é bastante isolado, pois não possui outras interconexões que afetem seu estado.

Ao trabalhar com um assunto complexo ou complicado, seu instinto pode ser tentar simplificá-lo. Simplificar é um processo redutivo que traduz um estado complexo ou complicado em uma forma simplificada, geralmente eliminando detalhes ou nuances. Há situações que justificarão tornar o processo de compreensão mais rápido e fácil, embora esse não seja um objetivo universal.

> "Esforce-se pela clareza, não pela simplicidade. É fácil “emburrecer alguma coisa”, mas extremamente difícil fornecer clareza enquanto mantém a complexidade. Eu odeio a palavra “simplificar”. De muitas maneiras, como pesquisadora, é a ruína da minha existência. Eu prefiro “explicar”, “esclarecer” ou “sintetizar”. Se você tirar a complexidade de um tópico, você degrada sua existência e difama sua importância. As palavras não são suas inimigas. Pensamentos complexos não são seus inimigos. A confusão é. Não confunda seu público. Não fale com eles, não os engane e certamente não minta para eles."
>
> <cite>Amanda Hobbs, Pesquisadora e Editora de Conteúdo Visual</cite>

Nem tudo pode ou deve ser simples. O processo de simplificação pode arriscar que o assunto seja simplificado demais ao ponto da obscuridade. Ao remover sutilezas e tecnicismos importantes, isso pode ser tão prejudicial para a acessibilidade percebida quanto deixar um assunto complexo ou complicado muito exigente intelectualmente. E se o seu público for suficientemente sofisticado com capacidade e motivação para lidar com o processo de aprendizado necessário para entender um tópico difícil? Ao simplificar as coisas, seria negada a eles essa oportunidade de aprendizado e acesso negado ao entendimento relevante. Um público, neste caso, pode justificadamente se sentir apadrinhado quando confrontado com um retrato simplificado demais.

Ao considerar o nível de seu assunto e a natureza de sua análise, se você acha que seu público não entenderá o que você está apresentando, você tem uma escolha: simplificar ou esclarecer

* <em>Simplifique</em> quando seu público não tem conhecimento ou capacidade para lidar com um assunto complicado e não precisa adquirir profundo conhecimento sobre ele.
* <em>Esclareça</em> quando seu público não tem o conhecimento, mas tem a capacidade de lidar com um assunto complicado, com assistência. Forneça recursos de anotações para explicar sobre o que é o assunto, como lê-lo, quais recursos são significativos e o que tudo isso significa. Não subestime a capacidade do seu público de estar disposto e ser capaz de compreender tópicos sobre os quais eles não têm entendimento prévio. Muitas vezes, é isso que eles querem de uma experiência de visualização.

Outro risco de criar confusão é o descuido e a complacência: não assuma domínio de domínio entre todo o seu público com o uso de siglas, abreviaturas ou linguagem técnica ambíguas. Explique o que precisa ser explicado. Inclua anotações para títulos, escalas e unidades, explicando as fontes de dados e associações de cores. Esses são todos os recursos que contribuem muito para eliminar a confusão.

<strong>Design de representação:</strong> Além da complexidade do assunto, outra questão a considerar é a complexidade da representação. Ou seja, a complexidade percebida de tipos de gráficos incomuns ou desconhecidos. Nem todo gráfico que encontramos é familiar. E quando algo não é familiar, é compreensível como isso expõe um risco de confusão.

Às vezes, a falta de familiaridade é um gatilho para culpar o visualizador: “Por que eles usaram um gráfico que eu nunca vi antes?” Esse déficit em saber ler um tipo de gráfico novo ou desconhecido não é uma falha por parte do o espectador, é simplesmente a falta de exposição prévia do espectador a esses diferentes métodos. Mas e se houvesse uma boa razão para usar esse gráfico? Pode ser a maneira mais astuta de retratar a análise mais relevante sobre um assunto. Claro, pode ser visualmente complicado, mas essa pode ser a única maneira de mostrar isso.

Tudo é novo uma vez. É por isso que aprendemos e por que somos capazes de aprender. Para superar os tipos de gráficos que não são familiares, um visualizador deve ter os meios para aprender a perceber e interpretar um gráfico. Essa perspectiva pode naturalmente frustrar algumas pessoas que a veem como um obstáculo crítico que não estão dispostos a entreter. Mesmo com a melhor intenção e o fornecimento de orientação útil, se um espectador simplesmente não estiver disposto a fazer o esforço, você terá pouca influência adicional para superar esse bloqueio.

<strong>Tempo:</strong> Refere-se às características do encontro e à duração do tempo ou atenção que os espectadores podem ter disponível para processar a compreensão. Você precisa considerar se, no momento de consumir uma visualização, os espectadores estão em uma situação de pressão. Eles estão com pressa? Eles precisam de insights rápidos ou há espaço para um envolvimento mais prolongado? Talvez eles não tenham tempo para ler sobre os antecedentes de um assunto ou aprender a ler um determinado gráfico porque há decisões operacionais diretas em jogo. Se assim for, somente através do imediatismo da compreensão essa visualização será considerada eficaz. Além disso, se você criar uma solução interativa com um número excessivo de recursos, a riqueza de funcionalidades pode prejudicar seu uso. O público pode não ter o desejo necessário de fazer um esforço para interrogar e manipular a exibição. Mais cliques podem significar mais obstáculos para a compreensão

<strong>Atitude e emoção:</strong> Como espectadores, às vezes não estamos no clima certo. Podemos estar cansados ​​e preguiçosos, ou tivemos um dia particularmente ruim. Nesses momentos, a perspectiva de se envolver até mesmo com a visualização mais atraente e bem projetada pode parecer demais. Eu passo todos os meus dias olhando para visualizações e posso reconhecer o quão indiferente eu me sinto em relação ao trabalho quando a fadiga aparece.

Uma extensão do humor é a confiança. Às vezes, o público pode não se sentir suficientemente equipado para embarcar em uma visualização se for sobre um assunto desconhecido, mesmo que haja assistência disponível. Pode ser um pouco irracional, mas eles não desejam se envolver, especialmente se isso os leva além de sua zona de conforto em termos das demandas que lhes são pedidas para interpretar e compreender.

<strong>Design de apresentação:</strong> em que formato seus espectadores precisarão consumir seu trabalho? Eles vão precisar de trabalho criado para uma saída impressa ou uma plataforma digital. Isso precisa ser compatível com uma pequena tela como em um smartphone ou tablet? Algum espectador terá deficiências visuais que precisam ser acomodadas?

Se o que você cria for consumido fora do formato nativo pretendido, como visualizar um grande infográfico com um pequeno texto em um celular, isso impedirá a experiência do espectador. Como e onde seu trabalho é consumido muitas vezes estará além de seu controle e você não pode mitigar para todas as eventualidades.


### Princípio 3: Um bom design de visualização é elegante

O terceiro princípio é tornar sua visualização elegante, que mapeia novamente mais três dos dez princípios do bom design de Dieter Rams (Figura 2.10) e o desejo de beleza de Vitruvius. A elegância se preocupa em criar uma estética que atraia seu público e perdure, sustentando um sentimento positivo ao longo da experiência, muito além dos momentos iniciais de engajamento.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/b3860c57-b55b-4df1-8412-2a82433f08c8.png)

_Figura 2.10 Mapeando a 'Elegância' nos Dez Princípios de Rams_

O design elegante é apresentado como o terceiro princípio por um bom motivo. Quaisquer escolhas que você faça para alcançar a 'elegância' não devem prejudicar a conquista da confiabilidade e acessibilidade em seu design. De fato, a busca de outros princípios muitas vezes já leva a uma certa elegância como subproduto.

> “Ao trabalhar em um problema, nunca penso em beleza. Eu penso apenas em como resolver o problema. Mas quando termino, se a solução não for bonita, sei que está errada.”
>
> <cite>Richard Buckminster Fuller, Celebrado Inventor e Visionário</cite>

### O Design de Representação e Apresentação é Atraente?

A busca da elegância é tão ilusória quanto uma definição prática. O que dá a algo uma qualidade elegante? Os adjetivos que surgem em minha mente são elegantes, dignos e graciosos. A elegância tem uma atemporalidade que transcende noções mais fugazes como chique ou <em>cool</em>.

A elegância é mais evidente quando está faltando. É quando o design de uma visualização carece de coesão e inspiração, especialmente nos elementos de cor e composição que informam sua aparência. Por outro lado, conforme expresso pelo princípio de Rams "Bom design é o mínimo de design possível", o design elegante acelera você para o conteúdo e para a compreensão.

Em seu livro<em> The Shape of Design</em>, o designer Frank Chimero faz referência a um provérbio Shaker: "Não faça algo a menos que seja necessário e útil; mas se for ambos, não hesite em torná-lo bonito". Ao servir os princípios do design confiável e acessível, você terá coberto tanto o necessário quanto o útil. Como sugere Chimero, se servimos à mente, nosso coração está nos dizendo que agora é a hora de pensar sobre a beleza. Existem vários componentes do <em>design thinking</em> que acredito que contribuem para alcançar a elegância no design.

<strong>Elimine o arbitrário</strong>: como em qualquer trabalho criativo, uma boa edição é uma habilidade extremamente valiosa. Cada decisão de design que você toma – cada ponto, cada pixel deve ser justificável. Nada que permaneça em seu trabalho deve ser considerado arbitrário, baseado em gostos aleatórios, nem redundante, oferecendo valor supérfluo. Estes irão distrair e, pior, podem distorcer o processo de compreensão. Mesmo que suas escolhas não sejam baseadas em raciocínio empírico, você ainda deve ser capaz de oferecer justificativa para cada recurso incluído, bem como qualquer recurso significativo excluído.

A eliminação do arbitrário não deve ser confundida com a busca do minimalismo, que é uma abordagem brutal que elimina o arbitrário e depois corta mais fundo. No contexto da visualização, o minimalismo pode ser um ato desnecessariamente selvagem e austero que pode ser inadequado com o estilo de trabalho necessário.

<strong>Rigor:</strong> Um visualizador dedicado deve estar preparado para agonizar com os menores detalhes e querer resolver até mesmo as menores imprecisões na largura de pixel. O desejo de tratar seu trabalho com esse nível de atenção demonstra respeito pelo seu público: você quer que eles possam experimentar qualidade, então orgulhe-se da precisão. Nem todas as decisões compartilham o mesmo significado, mas precisamos atender a todas as decisões igualmente, cuidando dos pequenos detalhes. Não deixe de verificar as coisas e não corte cantos por não testar. Vai valer a pena. No entanto, somos apenas humanos e nem todos os problemas podem ser detectados e erradicados.

> "Tudo deve ter uma razão - Um princípio que aprendi como designer gráfico que ainda se aplica à visualização de dados. Em essência, tudo precisa ser racionalizado e ter uma lógica de porque está no design/visualização, ou está fora."
>
> <cite>Stefanie Posavec, designer de informação</cite>

<strong>Estilo:</strong> Este é outro conceito difícil de definir, especialmente porque a palavra tem um significado diferente para pessoas diferentes. Foi um pouco manchado pelas antigas queixas em torno de algo demonstrando estilo sobre substância. Quando parece que o estilo sobre a substância esteve no centro da tomada de decisão, a consequência geralmente provará ser uma experiência obstruída ou distorcida. Desenvolver um estilo é uma manifestação de design elegante. As decisões em torno da seleção de cores, tipografia e composição são questões que determinam seu estilo. O mesmo acontece com a experimentação na implantação de diferentes técnicas de representação ou recursos interativos. O desenvolvimento de um estilo cria um grau de consistência e confiabilidade em seus valores de design mais fortes que podem ser implantados repetidamente. É algo que precisa de tempo para se desenvolver à medida que você encontra sua voz de design.

> "Você não chega lá [beleza] com cosméticos, você chega lá cuidando dos detalhes, polindo e refinando o que você tem. Isso é, em última análise, uma questão de gosto treinado, ou o que os falantes de alemão chamam de fingerpitzengefühl (“sensação da ponta do dedo”)".
>
><cite>Oliver Reichenstein, fundador da Information Architects (iA)</cite>

Muitas organizações de notícias e mídia procuram ativamente criar seus próprios guias de estilo para ajudar visualizadores, editores gráficos e desenvolvedores a navegar pelas águas agitadas do <em>design thinking</em>. Esta é uma tentativa consciente de promover a consistência na abordagem, bem como criar eficiência. Nessas organizações, a pressão de prazos apertados das demandas perpétuas do ciclo de notícias significa que criar eficiência é de enorme valor. Ao remover o fardo de ter sempre que pensar do zero sobre suas escolhas de design, os visualizadores são deixados para gastar mais tempo no desafio fundamental do que mostrar e não se atrapalhar em como mostrá-lo. Os estilos mais eficazes se destacam como instantaneamente reconhecíveis: há uma razão pela qual você pode escolher instantaneamente o trabalho do New York Times, The Guardian ou do Financial Times.

<strong>A decoração deve ser aditiva, não negativa:</strong> as artes decorativas são historicamente consideradas como uma intersecção entre o útil e o belo. O termo decoração quando aplicado a dados carrega uma conotação diferente. É frequentemente usado em críticas à percepção de fantasias de dados usando floreios visuais supérfluos para provocar atenção, geralmente quando o conteúdo é desinteressante ou fino em sua substância.

>— Suponho que se possa dizer que nosso trabalho tem uma certa assinatura. Estilo, para mim, tem uma conotação negativa de “dar um tapa” para embelezar algo sem muito significado. Não temos como objetivo ter uma assinatura (visual) reconhecível, em vez disso, criar um trabalho que realmente importe e seja único. Praticamente todos os nossos projetos são personalizados e têm um resultado final diferente. Essa é uma das razões pelas quais nos preocupamos mais em trabalhar de acordo com valores e princípios que transcendem projetos individuais e acredito que é isso que torna nosso trabalho reconhecível.”
>
><cite>Thomas Clever, Cofundador da CLEVER°FRANKE, uma Data-Driven Experiences Estúdio</cite>

Com moderação, os enfeites visuais podem oferecer meios eficazes para garantir e sustentar o apelo de um público. Consideraremos o papel das ideias no Capítulo 3, onde o conselho principal deve sempre ser conduzido principalmente por dados e seu público, não por suas ideias. No entanto, há ocasiões no processo de design em que você deve abraçar o talento criativo, a novidade e a diversão. As pessoas gostam de coisas boas. Às vezes, os espectadores desejam algo que desperte um envolvimento emocional mais otimista e direto. Uma singularidade de estilo é uma existência monótona para todos nós.<br>Em certas circunstâncias, pode ser necessário considerar o emprego da sedução estética para criar uma forma de apelo que atraia os espectadores e os encoraje a se envolver com um assunto que, de outra forma, não consideraria relevante. Isso pode envolver o uso de novos dispositivos visuais ou funcionais que atraem e desempenham um papel útil.

Este é especialmente o caso quando suas ideias são congruentes com o assunto ou a mensagem principal. Os trabalhos apresentados nas Figuras 2.11 e 2.12 mostram melhorias atraentes na apresentação de fundo e no estilo de representação. As escolhas em cada caso são harmoniosas com os respectivos temas de preços do cacau (gráfico de barras ‘The KitKat’) e vendas online de lâminas de barbear (gráficos de barras criados raspando pedaços de espuma de barbear). Em cada caso, essas opções de design oferecem uma solução de design bastante charmosa que não prejudica a mensagem. Eles complementam as informações apresentadas sem obstrução ou distração

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/97dae70d-a8a4-4f76-a1b3-669075c7ca43.png)

_Figura 2.11 A Ásia Perde seu Gosto por Chocolate, pelo Departamento Gráfico (Wall Street Journal)_


![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/3af1fd0e-0bc7-4a70-91a3-99b3a33a5f28.png)

_Figura 2.12 Razor Sales Move Online, Longe da Gillette, pelo Departamento Gráfico (Wall Street Journal)_

Alguns podem argumentar que os espectadores serão incentivados a se envolver com uma visualização se for relevante para eles e eles não precisam ser seduzidos por novas escolhas de aparência. De fato, se eles precisam ser convencidos a olhar para algo, talvez eles não devam ser considerados o público-alvo?

Alguns podem argumentar que os espectadores serão incentivados a se envolver com uma visualização se for relevante para eles e eles não precisam ser seduzidos por novas escolhas de aparência. De fato, se eles precisam ser convencidos a olhar para algo, talvez eles não devam ser considerados o público-alvo? Talvez em um ambiente de negócios ou operacional, as necessidades de indivíduos, funções e grupos sejam muito mais claras. Em outros lugares, no mundo real, geralmente há considerações mais sutis sobre a melhor forma de se conectar a um público demográfico potencialmente diversificado. De fato, como espectador, seu interesse por um assunto só pode se materializar como consequência da experiência de uma visualização. Pode não ter existido de antemão como um pré-requisito motivador, e sem algum senso inicial de atração ou intriga sentido em relação à perspectiva de uma visualização, um espectador pode perder a chance de descobrir essa conexão.

Para concluir esta discussão sobre princípios, deixe-me explicar por que sinto que três dos dez originais de Rams não se encaixam como ideais universais para visualização de dados (Figura 2.13).

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/680c914a-d5f0-4f2c-8b95-a6d4df441450.png)

_Figura 2.13 Considerando os Princípios Não Universais de Carneiros_

<strong>Um bom design é inovador:</strong> a maioria das visualizações usa métodos de gráficos experimentados e testados que estão em jogo há anos. Ao contrário do design de produtos, por exemplo, não é necessário que os visualizadores concebam constantemente novas formas de representação ou técnicas de apresentação. Você pode ter um desejo pessoal de ser inovador, alinhado aos objetivos pessoais sobre o desenvolvimento de suas habilidades, talvez repensando como lidar com projetos anteriores. Não é que a visualização de dados nunca seja sobre inovação, apenas que não é um princípio universal. Dito isto, é claro que existem circunstâncias em que a inovação é importante. No contexto de limitações ou constrangimentos impostos, para superar um determinado desafio, a inovação materializa-se. Você também precisa dele quando as soluções estabelecidas não resolvem novos problemas.

Às vezes, tento olhar para as restrições de forma positiva por causa disso. Considere as circunstâncias enfrentadas pelo diretor Steven Spielberg durante as filmagens de Tubarão. As primeiras tentativas de criar um modelo de tubarão de aparência convincente provaram ser tão falhas que, em grande parte da produção programada do filme, Spielberg ficou sem um tubarão visível para trabalhar. Tais eram os recursos de tempo decrescentes que ele não podia esperar por uma solução para filmar as sequências de ação, então ele teve que trabalhar com uma combinação de adereços e dispositivos visuais. Objetos sendo interrompidos, como barris ou bóias flutuantes e, notoriamente, uma falsa barbatana de tubarão perfurando a superfície, foram apenas algumas das táticas que ele usou para criar a sugestão de um tubarão em vez de realmente mostrá-lo. Eventualmente, um modelo viável de tubarão foi desenvolvido para servir as últimas cenas, mas, como todos sabemos agora, por não podermos mostrar o tubarão durante a maior parte do filme, o suspense foi imensamente aumentado. Isso o tornou um dos filmes mais duradouros de sua geração. A inovação necessária que surgiu dos recursos limitados e da pressão crescente levou a uma solução que certamente transcendeu qualquer outro resultado que teria surgido se houvesse liberdade de restrições. Abrace as circunstâncias que aumentam sua necessidade de ser inovador; apenas não sinta que é uma busca obrigatória para todos os contextos de visualização.

<strong>Um bom design é duradouro:</strong> A tradução desse princípio para o contexto da visualização de dados pode ser feita de diferentes maneiras. ‘Longa duração’ pode estar relacionado ao desejo de preservar a funcionalidade contínua de um projeto digital, por exemplo. É bastante desmoralizante a frequência com que os favoritos do navegador que apontam para visualizações antigas já se esgotaram ou a frequência com que os trabalhos digitais expiram devido à falta de suporte sustentado. A evolução da tecnologia também corre o risco de tornar obsoletas as funcionalidades mais antigas. Felizmente, a longa história da visualização impressa e do trabalho infográfico em particular tem um legado que é mais simples de preservar, em muitos aspectos.

Outra forma de interpretar ‘longa duração’ é na durabilidade da técnica. Gráficos de barras ou gráficos de linhas, por exemplo, são sempre úteis, sempre sendo usados, sempre disponíveis quando você precisa deles. 'Long-lasting' também pode estar relacionado à rejeição da moda atual, preservando uma abordagem atemporal do design thinking que combina com a discussão sobre elegância.

Sinto que ‘duradouro’ se aplica mais de perto ao assunto e aos dados retratados em uma visualização. A expiração da precisão dos dados sobre uma atividade que mudou desde então prejudica o potencial de longa duração de um projeto. Este é particularmente o caso de assuntos relativos a assuntos atuais. A análise sobre a perda de vidas durante a Segunda Guerra Mundial é atemporal porque nada agora vai mudar a natureza ou a extensão dos dados subjacentes (a menos que surjam novas descobertas). A análise dos filmes de maior bilheteria de hoje mudará assim que novos grandes filmes forem lançados e o tempo passar. Então, novamente, a ideia de longa duração é específica do contexto, em vez de ser uma meta universal para visualização de dados.

<strong>Um bom design é amigo do ambiente:</strong> Este é, obviamente, um objetivo nobre, mas a relevância deste princípio deve ser novamente posicionada no nível contextual, com base nas circunstâncias específicas de um determinado projeto. Se o seu trabalho for impresso, os recursos utilizados prejudicarão a compatibilidade ambiental desse projeto. Desenvolver um rico interativo que está sendo constantemente martelado por usuários em todo o mundo sobrecarrega o servidor de hospedagem e o fornecimento de energia associado. Julgamentos específicos sobre o alcance do impacto ambiental do trabalho de visualização, de forma realista, cabem aos protagonistas e partes interessadas envolvidas.

Por fim, um comentário sobre a necessidade de uma visualização ser memorável. Isso é frequentemente proposto como um objetivo universal na visualização de dados, mas eu discordo. Se a acessibilidade perfeita de uma visualização leva a que ela também seja memorável, então maravilhoso. Se a elegância do seu pensamento de design, possivelmente incluindo certos floreios visuais memoráveis, deixa um legado na mente do espectador, então este será um excelente subproduto do seu trabalho. Como objetivo em si, alcançar a memorabilidade deve ser considerado, novamente, no nível contextual com base nos objetivos específicos de uma determinada obra e levando em consideração a capacidade do público-alvo.

## Resumo: O Processo de Design de Visualização

### Processo de Design

Neste capítulo, você foi apresentado ao processo de design, a sequência de atividades em torno das quais o conteúdo do livro é organizado:

1. Formulando seu briefing: planejando, definindo e iniciando seu projeto.
2. Trabalhando com dados: coletando, manipulando e preparando seus dados.
3. Estabelecendo seu pensamento editorial: definindo o que você vai mostrar ao seu público.
4. Desenvolvendo sua solução de design: fazendo escolhas de design sobre como você representa e apresenta o que deseja mostrar ao seu público.

Ele explicou por que um processo é importante seguir:

* Reduz a aleatoriedade de sua abordagem.
* Oferece adaptabilidade para acomodar requisitos e circunstâncias em constante mudança.
* Protege o valor da experimentação.
* Cada estágio alcançado representa a primeira ocasião em que você começará a realizar essa atividade, não o último.

### Princípios de design

Onde o processo oferece eficiência, os princípios de design garantem a eficácia. A segunda seção apresentou três princípios-chave para ajudar a construir a clareza de suas convicções em torno da diferença entre o design de visualização eficaz e ineficaz:

1. Uma boa visualização de dados é confiável: é confiável? A representação dos dados e do assunto é fiel? O design de representação e apresentação tem integridade?
2. Uma boa visualização de dados é acessível: é utilizável? A representação dos dados e do assunto é relevante? A representação e o design da apresentação são adequadamente compreensíveis?
3. Uma boa visualização de dados é elegante: é estética? O design de representação e apresentação é atraente?

### Dicas e táticas gerais

Você também recebeu algumas dicas gerais antes de colocar o processo em prática:

* A importância de uma boa gestão do tempo.
* A necessidade de ocupar diferentes mentalidades em momentos diferentes, alternando perfeitamente entre pensar, fazer e fazer.
* Documentar seu processo de pensamento, capturar esboços e fazer anotações.
* A comunicação é uma relação de mão dupla: trata-se de falar e ouvir.
* A atenção aos detalhes é uma obrigação: a integridade do seu trabalho é primordial.
* Não seja precioso, tenha a disciplina de não fazer as coisas, de matar ideias, de evitar rastejamento de escopo.
* Use o aprendizado reflexivo para melhorar suas capacidades e fazer o processo funcionar para você.
