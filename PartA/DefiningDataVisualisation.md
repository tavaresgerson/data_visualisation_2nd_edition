# Definindo a Visualização de Dados

Este capítulo de abertura apresentará a visualização de dados através sob o prisma de uma definição proposta. Cada componente que compõe esta definição será explorado em profundidade para ilustrar algumas das principais características e complexidades deste assunto.

A segunda parte do capítulo irá posicionar a visualização de dados no contexto de outras disciplinas ou campos relacionados, explicando onde existem sobreposições ou distinções claras. No geral, este capítulo procurará forjar um entendimento compartilhado que ajudará a definir o tom e o raciocínio para a estrutura deste livro.

## 1.1 O Que é Visualização de Dados?

É útil começar este livro com uma definição de visualização de dados (Figura 1.1). Isso ajuda a garantir que nós (você leitor, eu escritor) tenhamos um entendimento mútuo, desde o início, sobre o que se entende por visualização de dados no contexto deste texto. Os componentes desta definição esculpem o assunto em perspectivas distintas em torno das quais o conteúdo deste livro é organizado.

![figura 1.1](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/fe1540c1-e992-4107-9c78-51f93527a780.png)

_Figura 1.1: Uma definição para visualização de dados_

Deixe-me aprofundar isso e descrever os papéis e as relações entre cada componente expresso. Também explicarei onde e como esses tópicos serão abordados. Em primeiro lugar, vamos analisar os dados.

Dados são nomes e valores. São agrupamentos, descrições e medidas. São datas e locais. Será útil para as discussões deste livro pensar nos dados como sendo normalmente estruturados em forma de tabela, com linhas de registros e colunas de variáveis. A maioria dos dados que comumente encontramos existirá em formato textual, numérico ou combinado, mas também vale a pena notar as oportunidades que existem cada vez mais para trabalhar com ativos de dados em formas de mídia de imagens, áudio e vídeo.

No Capítulo 4, você aprenderá sobre a importância de desenvolver uma compreensão íntima de seus dados para se familiarizar totalmente com suas propriedades, sua condição e suas qualidades.

Você verá que os dados são o elemento fundamental que orienta as decisões nesse processo de design. Sem dados não há material para alimentar nem necessitar de uma visualização. Por outro lado, sem visualização, o objetivo dos dados pode não ser cumprido. Isso não quer dizer que devemos sempre visualizar os dados, absolutamente não, mas na maioria das circunstâncias devemos aproveitar o valor máximo dos dados se não, há oportunidades perdidas.

Para explicar, aqui está uma ilustração simples. Quando os dados são apresentados em uma tabela, é uma tarefa simples para um visualizador varrer as linhas e colunas para buscar valores de relevância ou descobrir pontos de dados específicos que despertam interesse. Por exemplo, ao visualizar a tabela na Figura 1.2, deve ser bastante simples descobrir qual foi a participação percentual das vendas on-line de uma Empresa X em abril de 2016. Agora, procure a participação percentual das vendas da loja em dezembro de 2011.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/bffcd0ef-40cd-4d4b-80bc-06889ccbc6d1.png)

_Figura 1.2: Proporção de % de vendas por canal ao longo do tempo_

Como visualizador, sua tarefa é simplesmente encontrar a interseção de linha e coluna relevante: observe a exibição de valor e leia-a. A participação percentual das vendas on-line da Empresa X em abril de 2016 é de 84 e para as vendas da loja em dezembro de 2011 é de 71.

Para descobrir qual canal de vendas teve a segunda maior porcentagem em vendas no mês de agosto de 2014, novamente, basta encontrar a linha relevante, comparar os três valores quantitativos ao longo dessa linha e determinar qual coluna de canal contém o valor em segundo lugar. Para este mês, o canal online, com 44, teve a segunda maior participação percentual das vendas.

As limitações da leitura de dados quando apresentados desta forma surgem quando queremos responder a questões mais amplas: ou seja, indagações que transcendem o escopo de uma resposta originada de um único ou pequeno número de pontos de dados adjacentes. Na mesma tabela, quão fácil você acha para identificar as tendências principais em cada canal de vendas durante o período exibido?

Você provavelmente pode verificar que a participação percentual das vendas para as lojas começa bastante alta e depois cai para nada, a participação percentual das vendas on-line começa bastante baixa e atinge o máximo de 100%, e a participação percentual das vendas por telefone é consistentemente pequena.

Embora demore um pouco para estudar os valores em cada coluna do canal de vendas para formar essa observação resumida, ainda é possível. Mas e se suas observações precisarem ser formadas mais rapidamente? E se você precisasse saber mais sobre os padrões localizados de altos e baixos nessas tendências globais? E se você quisesse identificar a primeira ocasião em que a participação percentual das vendas on-line excedeu a participação percentual das vendas na loja? Quando foi a última vez que a participação percentual das vendas na loja ultrapassou a das vendas online? Em quais períodos os diferentes canais de vendas experimentaram as mudanças mais aceleradas para cima ou para baixo?

Essas são as perguntas mais difíceis de responder com eficiência e precisão apenas com os dados. Isso ocorre porque a síntese de observações de vários valores em diferentes linhas e colunas para perceber relacionamentos mais amplos não explora plenamente as capacidades de nosso sistema visual – como nossos olhos e mente trabalham juntos para dar sentido a objetos e padrões. Ler valores isoladamente, armazená-los em nossa memória de curto prazo e compará-los em nossa cabeça com outros valores isolados é um desafio mental. Não é impossível, pois ainda podemos fazer isso com apenas uma tabela de dados, mas levará muito tempo e esforço.

Essa carga de trabalho também só aumentará à medida que os dados aumentarem em volume e complexidade. Por exemplo, e se esta tabela tivesse 1.000 linhas de profundidade e houvesse 20, 50 ou 100 colunas diferentes para trabalhar? Ou, e se as quantidades tivessem tamanhos de valor semelhantes e variação mais modesta? Quão fácil seria então notar padrões significativos?

O cerne de tudo isso é que podemos olhar para os dados, mas não podemos realmente vê-los. Para ver os dados, precisamos representá-los de uma forma visual diferente.

Voltando à definição, o termo <strong>representação visual</strong> é sem dúvida a atividade por excelência da visualização de dados. A representação envolve a tomada de decisões sobre como você vai retratar seus dados visualmente para que o entendimento do assunto que ele oferece possa ser acessível ao seu público. Em termos simples, trata-se de gráficos e do ato de selecionar o gráfico certo para mostrar os recursos de seus dados que você considera mais relevantes.

Os blocos de construção de qualquer gráfico são marcas e atributos. As marcas podem ser pontos, linhas ou formas e são usadas para representar itens de dados. Um exemplo de um item de dados da tabela na Figura 1.2 seria a 'parte percentual das vendas das lojas durante junho de 2014'. Não o valor em si, mais a coisa sobre o valor.

Atributos, às vezes descritos como canais, são variações visuais de marcas para representar os valores associados a cada um. Isso inclui propriedades como diferentes escalas de tamanho, cor ou posição. Se o item de dados for 'porcentagem de participação das vendas das lojas durante junho de 2014', um atributo seria usado para representar o valor associado, neste caso 72. Se marcas e atributos são os ingredientes, as diferentes combinações usadas criam diferentes tipos de gráficos – as receitas.

A Figura 1.3 mostra um gráfico dos dados mostrados na tabela da Figura 1.2. Aqui os dados são representados usando um gráfico de linhas, um tipo de gráfico comum usado para mostrar como os valores quantitativos mudam ao longo do tempo. Nesse caso, os itens de dados são representados por marcas de ponto, posicionadas na interseção das posições x e y relevantes para cada mês e canal de relatório. Os atributos aqui utilizados são, em primeiro lugar, as linhas conectadas que unem a série contínua de valores para cada canal e, em segundo lugar, as cores distintas aplicadas para distinguir cada caminho de linha e associá-las à sua respectiva categoria de canal de vendas.

![figura 1.3](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/3834faa9-5705-4c62-af96-7347a76f01f9.png)

_Figura 1.3: Proporção da porcentagem de vendas por canal ao longo do tempo_

Como visualizador, você digitaliza este gráfico para formar observações sobre os três canais de vendas individualmente e, em seguida, compará-los entre si. As comparações feitas entre canais separados são especialmente relevantes para esses dados, pois as quantidades mostradas são representativas de partes de um todo 100%. Isso significa que, em qualquer ponto ao longo da linha do tempo, a alteração no valor de um canal afetará os valores dos outros dois.

Consumir esses dados em forma de gráfico, em vez de ler uma tabela, permite que um visualizador processe grupos de vários pontos de dados simultaneamente para identificar as encostas e planícies, os picos e vales, bem como as lacunas e cruzamentos entre as linhas. Embora a precisão de determinar um ponto de dados individual (por exemplo, a partir do gráfico, qual foi a participação percentual das vendas on-line em abril de 2016?) padrões e relacionamentos, por sua vez, tornam-se mais precisos. A história do aumento do domínio das vendas on-line e o declínio relacionado das vendas nas lojas é imediatamente aparente, mas o que chama a atenção aqui é um padrão intenso de fluxo e refluxo durante o período de meados de 2014 a meados de 2015, dos quais as respectivas mudanças significativas na trajetória das vendas online e em loja se materializaram e continuam.

O gráfico tem os mesmos dados que a tabela, mas é representado de forma diferente. Se esta visualização de gráfico é melhor do que uma visualização de tabela depende da finalidade da sua comunicação e das necessidades do seu público. Você não faz gráficos de dados porque pode, você faz isso porque fornece uma janela para ver diferentes recursos de dados. Exploraremos os julgamentos que você precisa fazer sobre o que deseja mostrar ao seu público no Capítulo 5 e, em particular, no Capítulo 6, onde você aprenderá sobre a ampla variedade de tipos de gráficos estabelecidos que são comumente usados pelos visualizadores de hoje. Esses gráficos variam em complexidade e composição. Cada um é capaz de acomodar diferentes tipos de dados e retratar diferentes tipos de análise. Este capítulo ampliará seu vocabulário visual, dando-lhe uma apreciação de mais maneiras de expressar seus dados. Também aumentará a sofisticação de como você faz escolhas eficazes.

O próximo componente da definição é a <strong>apresentação</strong>, que diz respeito a todas as outras decisões de design que compõem a anatomia completa de qualquervisualização. Como este texto está focado em criar a visualização como um meio de comunicação com os outros, a apresentação diz respeito a como escolhemos “empacotar” um trabalho de visualização para transmiti-lo a um público, independentemente do meio ou método de divulgação.

A apresentação visual inclui opções de design, como a possível aplicação de interatividade, recursos de anotação, todas as questões relacionadas ao uso de cores e à composição do trabalho. Considerando o gráfico de linhas na Figura 1.3, se ele fosse destinado à Web, você poderia imaginar a interatividade sendo útil para oferecer detalhes de dicas de ferramentas de rótulos de valor ao passar o mouse sobre partes de cada linha. Você pode oferecer controles para modificar o intervalo de tempo do eixo x ou filtrar para ocultar ou mostrar diferentes linhas de interesse. Existem alguns recursos de anotação já exibidos com este gráfico, como o título, a legenda de cores e as escalas dos eixos x e y. Você também pode adicionar legendas para fornecer explicações sobre alguns dos padrões mais visíveis nos dados. Como mencionado, a cor já é usada como atributo, para distinguir as linhas de cada categoria de canal de vendas, mas a aplicação da cor se estende por todos os elementos visíveis, incluindo o sombreamento de fundo, cores das linhas de grade e coloração de qualquer texto ou rótulos. Por fim, a composição está relacionada ao tamanho e posicionamento de todos os elementos de design, como as dimensões da área do gráfico, o alinhamento e o tamanho do título e o posicionamento dos rótulos dos eixos.

O pensamento de projetar a anatomia completa de uma visualização – combinando representação visual e apresentação – é inevitavelmente interconectado. A seleção de um tipo de gráfico aciona inerentemente a necessidade de pensar sobre o espaço e o lugar que ele ocupará na tela ou na página; um recurso interativo clicável que revela legendas anotadas requer uma reflexão cuidadosa sobre como estilizar o texto e quais cores usar. Há muitas decisões de design aparentemente pequenas a serem tomadas na visualização, pequenas coisas que se somam para ter um grande impacto. Durante os estágios iniciais de aprendizado deste assunto, é útil dividir o pensamento de sua apresentação e abordar essas preocupações de design como camadas separadas. Os Capítulos 7–10 explorarão cada uma dessas questões de design separadamente, mas com profundidade suficiente, traçando o perfil das opções disponíveis e os fatores que influenciam suas decisões. À medida que você ganha experiência e segurança, a natureza inter-relacionada das escolhas que você faz se tornará mais transparente e você será estimulado pela profundidade de pensamento exigida de você.

O componente final da definição expressa que a visualização de dados visa facilitar o entendimento. Tudo neste livro se resume essencialmente a ajudá-lo a atingir esse objetivo. Vamos lidar com o termo facilitar em breve, mas vamos nos concentrar por enquanto na palavra compreensão.

A noção de compreensão é bastante ampla. Para explicar melhor sua relevância para a visualização de dados, precisamos, novamente, nos voltar para a perspectiva de um espectador.

Ao consumir uma visualização, o espectador passará por um processo de compreensão que envolve três fases: perceber, interpretar e compreender (Figura 1.4). Estes não são apenas sinônimos para a mesma palavra, mas transmitem distinções no foco cognitivo.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/d091e5a3-34c9-4862-9313-6e0c23f2f961.png)

_Figura 1.4: As três fases do entendimento_

Para o benefício desta ilustração, vamos considerá-los como ocorrendo em uma sequência linear, com fases sucessivas sendo dependentes da fase anterior ter sido realizada. Para um espectador, tentando conscientemente entender uma visualização e extrair compreensão de uma visualização, essas diferentes fases parecerão bastante indiscerníveis. Eles podem parecer ocorrer em paralelo. Os espectadores são humanos – há ocasiões em que interpretações rápidas dos recursos de título de um gráfico são feitas antes que todo o conteúdo tenha a chance de ser percebido primeiro.

Vejamos as características e diferenças entre essas fases referindo-se, inicialmente, a um gráfico de exemplo (Figura 1.5) que apresenta algumas estatísticas de destaque sobre a carreira do jogador Lionel Messi no FC Barcelona.

A primeira fase é a percepção, e isso diz respeito ao ato de ler um gráfico: 'o que eu vejo?'. Um visualizador decodifica como os dados são representados para formar observações iniciais sobre os principais recursos dos dados exibidos:

* <em>Qual gráfico está sendo usado?</em>
* <em>Que itens de dados as marcas representam? Que associações de valor os atributos representam?</em>
* <em>Qual intervalo de valores é exibido?</em>
* <em>Os dados e sua representação são confiáveis?</em>

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/7d365465-4d4f-4879-9830-2e95d4be11ef.png)

_Figura 1.5: Lionel Messi: Jogos e Gols para o FC Barcelona_

No exemplo, vemos um gráfico de barras agrupado mostrando valores quantitativos de pares de categorias ao longo do tempo. Este é um tipo de gráfico com o qual estou familiarizado e, portanto, me sinto instantaneamente à vontade com a perspectiva de consumi-lo.

Vejo que o tempo é plotado no eixo x em anos – ou, mais especificamente, temporadas de futebol – e uma medida quantitativa compartilhada está no eixo y. Existem duas categorias distintas de barras para cada estação, com a associação de cores explicada por uma chave de explicação integrada ao título. As barras cor de vinho mostram os jogos disputados em uma temporada e as barras azuis o número de gols marcados. Esse título também ajuda a estabelecer clareza sobre o que os dados estão mostrando. À medida que o método de representação é entendido, as observações iniciais começam a se formar sobre as principais características do display:

* <em>Que características – formas, padrões, diferenças ou conexões – são observáveis?</em>
* <em>Onde estão os valores maiores, médios e menores? (conhecidos como julgamentos de "magnitude escalonada").</em>
* <em>Onde estão os mais e os menos? Onde está a média ou normal? (julgamentos de "comparação global").</em>

Ao digitalizar o gráfico, meus olhos são atraídos para as barras dominantes no meio e para a direita da tela. Estou particularmente interessado no par de barras mais alto em 2011/12. Com a ajuda oferecida pelas linhas de grade horizontais e rótulos dos eixos, posso perceber com razoável confiança que o maior número de gols marcados foi 73 e o maior número de jogos disputados foi 60. Posso ver que as barras cor de vinho - mostrando os jogos disputados - são relativamente estáveis em tamanho desde cerca de 2008/09, mas as barras azuis são mais irregulares. As alturas da barra para ambas as categorias são muito menores quanto mais à esquerda a série temporal for. Olhando entre as categorias, não há consistência na relação, pois as barras bordô são às vezes maiores que seus vizinhos azuis algumas vezes menores.</p>

A <em>interpretação</em>, a segunda fase da compreensão; traduz essas observações em significado quantitativo e/ou qualitativo. Interpretar envolve assimilar o que você observou com o que você sabe sobre o assunto. O que significa o que você viu, dado o assunto?

* <em>Que características – formas, padrões, diferenças ou conexões – são interessantes?</em>
* <em>Quais recursos são esperados ou inesperados?</em>
* <em>Quais recursos são importantes em relação ao assunto?</em>

A tarefa de extrair interpretações das observações que fiz no gráfico é ajudada consideravelmente pelo meu interesse e conhecimento do futebol. Eu sei que se um jogador marca mais de 25 gols em uma temporada isso é muito bom, e marcar mais de 35 é excepcional. Alcançar 50, 60 ou mesmo 70 gols em uma temporada é francamente absurdo, especialmente no nível mais alto do jogo. Eu sei que é raro um jogador marcar em uma proporção superior a um gol por jogo jogado, então as temporadas em que uma barra azul excede a altura das barras cor de vinho representam uma estatística bastante notável. Eu poderia elaborar algumas das características que esperava (e veria) neste gráfico com base em saber os períodos em que diferentes gerentes estiveram no comando do Barcelona, ​​quais outros jogadores estavam no time e como o time se saiu de um temporada para a próxima. Eu sei o que esperar em termos da forma clássica do arco da carreira de um jogador de futebol e posso mapear isso para o de Messi, antecipando que em algum momento – mas ainda não – a ascensão clássica, o pico e o platô serão inevitavelmente seguidos por um declínio constante.

Como este comentário demonstra, a capacidade de um espectador de realizar uma interpretação racional será significativamente determinada por fatores externos à própria visualização. O grau de conhecimento que os espectadores possuem sobre o assunto retratado e sua capacidade de fechar uma lacuna de conhecimento é fundamental. Para cumprir a percepção de um gráfico, os espectadores precisam do contexto de escala; para cumprir a interpretação de um gráfico, os espectadores precisam do contexto do assunto. Além disso, há a questão da vontade. No momento de consumir uma visualização, nem todos têm a inclinação para se envolver com ela, principalmente se não tiverem interesse em um assunto ou se ele não tiver relevância imediata para suas necessidades.

Minha conexão com o assunto futebol me ajudou a entender mais sobre o significado das características dos dados em comparação com outros espectadores que podem não ter conhecimento do esporte. Mudar o assunto do futebol para um tópico totalmente inventado, mas usando o mesmo gráfico com os mesmos dados, reforça isso. Na Figura 1.6 vemos um gráfico exibindo dados sobre os avistamentos de Winglets e Spungles.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/114b7fea-a181-438a-be11-a22eae245b56.png)

_Figura 1.6 Total de Avistamentos de Winglets e Spungles_

Ainda consigo perceber o gráfico, observando as mesmas características que fiz quando retratava a quantidade de jogos e gols de Messi, mas como não tenho conhecimento desse assunto não posso interpretá-lo. Eu não tenho ideia do que são Winglets e Spungles, então não posso formar qualquer noção razoável do que é interessante, surpreendente ou importante sobre os recursos desta tela. Meu processo de compreensão pára após a fase de percepção.

Como isso ilustra, qualquer déficit na conexão de um espectador com um assunto impedirá fundamentalmente o progresso em direção à interpretação performática. Além disso, isso pode aumentar o risco de o espectador extrair interpretações espúrias ou sem suporte de uma exibição visual.

Em situações em que um espectador em potencial pode não possuir conhecimento suficiente de um assunto, será necessário que o visualizador ajude a preencher a lacuna entre a observação e o significado. Isso pode ser alcançado por meio de elementos de design simples, como o fornecimento de legendas, a inclusão de títulos e o uso astuto de cores para criar ênfase, por exemplo. O espectador deve então assumir a responsabilidade de aprender com a assistência prestada. Como denota a coloração roxa do círculo de fase do meio mostrado na Figura 1.4, formar interpretações úteis e razoáveis é uma responsabilidade compartilhada.

A fase final do entendimento é a compreensão, que é a consequência ou legado reflexivo da experiência de comunicação. Os espectadores agora consideram o que as interpretações significam para si mesmos. O que pode ser inferido como importante para você sobre as interpretações que você fez?

* <em>O que foi aprendido? Reforçou ou desafiou o conhecimento existente? Foi iluminado com novos conhecimentos?</em>
* <em>Que sentimentos foram despertados? A experiência teve um impacto emocional?</em>
* <em>O que se faz com esse entendimento? É apenas conhecimento adquirido ou algo para inspirar ação, como tomar uma decisão ou motivar uma mudança de comportamento?</em>

No meu caso, o resultado do entendimento alcançado a partir do gráfico de Messi não é nada muito dramático ou emocional. Não há ação direta ligada a isso, mas apenas reflito sobre ganhar uma impressão elevada, formada a partir desses dados, sobre o quão sensacional ele foi e continua sendo um jogador de futebol. Para os fanáticos do Barcelona que o assistem jogar todas as semanas, eles já terão formado esse entendimento. Essa informação apenas reafirmaria o que eles já sabiam. Para outros menos familiarizados com o assunto, pode ser mais esclarecedor, mas apenas se eles tiverem algum interesse necessário.

O '<em>uau</em>' de uma pessoa é o '<em>eu sabia que</em>' de outra pessoa é o '<em>eu não me importo</em>' de outra pessoa. Mesmo que você tenha apenas duas pessoas em seu grupo de público-alvo, você tem potencialmente dois perfis de espectadores diferentes. Nem sempre podemos antecipar o que eles não sabem, o que eles querem saber e qual é a relevância para eles de saber alguma coisa.

A <em>Visualização</em> de dados é apenas um agente de comunicação e não uma garantia do que o espectador faz com a oportunidade de compreensão que lhe é apresentada. Existem diferentes sabores de compreensão, diferentes consequências de compreensão formadas nesta fase final. Muitas visualizações serão criadas com a ambição de simplesmente informar, como o gráfico de Messi alcançado para mim, talvez para adicionar apenas um grão extra à pilha de conhecimento sobre um assunto. Nem toda visualização existe para levar o espectador a algum momento de grande descoberta, insights surpreendentes ou decisões de mudança de vida no estilo de Hollywood. Tudo bem, porém, desde que o resultado se ajuste ao propósito pretendido, algo que discutiremos com mais profundidade no Capítulo 3.

Mais uma vez, a associação do espectador com o assunto retratado influenciará muito essa fase de compreensão. Voltando aos dados mostrados anteriormente sobre o percentual de vendas por canal ao longo do tempo para a Empresa X, vamos supor que este foi um gráfico produzido para avaliar a eficácia de uma estratégia corporativa para consolidar as operações em um modelo de vendas somente online.

O resultado das interpretações formadas a partir deste gráfico pode levar à conclusão de que, quaisquer que sejam as ações tomadas, elas foram bem-sucedidas. Dependendo de quando a meta de vendas 100% online era esperada, pode ser que este gráfico demonstre sucesso total. Também pode revelar um sucesso tardio. Talvez a empresa esperasse 100% de vendas online muito mais cedo do que quando foram alcançadas. Por outro lado, a análise apresentada pode revelar padrões inesperados de vendas. Os canais online estão claramente dominando, mas e se a empresa ainda mantiver as despesas de manutenção das lojas, com custos de pessoal e estoque atolados no que parece ser um modelo expirado? Pode haver custos substanciais atribuídos às operadoras de telefonia esperando o telefone tocar para fazer uma venda potencial. Mas ninguém está ligando, então talvez a empresa devesse considerar a reestruturação.

Todos esses são caminhos razoáveis ​​para os quais a compreensão desses dados pode levar. Mas, neste ponto, devo revelar que o contexto real desses dados na verdade não tinha nada a ver com vendas. Esse assunto foi escolhido para fins de ilustração, mas os dados eram na verdade sobre outra coisa.

Especificamente, esses eram dados sobre as previsões em constante mudança durante a noite das eleições de 2016 nos EUA. Os valores dos dados vieram do FiveThirtyEight, um respeitado site conhecido pelo uso de técnicas estatísticas para analisar e contar histórias sobre eleições e vários outros assuntos ricos em dados. As quantidades referem-se às previsões de ‘chances de ganhar a presidência’ para os dois principais candidatos do partido, bem como percentuais residuais de ‘outros resultados’ para compor o agregado de 100%. A dimensão temporal diz respeito aos horários da noite da eleição (8 de novembro de 2016), quando os principais resultados foram declarados, influenciando as mudanças apresentadas no resultado previsto em cada ponto.

A Figura 1.7 mostra o mesmo gráfico de antes, com as mesmas quantidades plotadas e com o mesmo design, mas agora refletindo o verdadeiro contexto do assunto, conforme indicado pelo título atualizado, chave de cores e escalas do eixo x.

![desc](https://s3.sa-east-1.amazonaws.com/tavares-blog/images/f23ce22a-a045-4b67-85bb-c970cc9cc0f8.png)

_Figura 1.7 % de chance prevista de ganhar a presidência (eleições dos EUA, 8 de novembro de 2016)_

Independentemente de onde você se sente politicamente, o contexto revisado dos dados retratados neste gráfico mudará inquestionavelmente como você se sente sobre o que vê agora. Não é mais apenas um gráfico de vendas de rotina restrito em relevância a um pequeno grupo de pessoas na Empresa X. Agora é uma visualização sobre um evento importante na história moderna, cujo resultado a maioria das pessoas no planeta tem alguma conexão ou consciência disso.

Há consequências da emoção ao consumir esses dados. Alguns reviverão o júbilo selvagem da vitória inesperada de seu candidato, outros recuarão horrorizados com a memória da derrota inesperada de seu candidato.

Há consequências do esclarecimento. Alguns verão esses padrões atraentes de fluxo e refluxo pela primeira vez, outros pelo menos se lembrarão dessa história de montanha-russa que se desenrola na TV ou na cobertura da web durante à noite.

Há também reações racionais. Consumir este gráfico agora, muitos meses ou anos depois, oferece a oportunidade de uma análise mais ponderada, em contraste com a configuração original desses dados sendo consumidos ao vivo nos EUA e no resto do mundo por meio de um rastreador de previsão em mudança dinâmica e dramática . À luz fria do dia, perguntas podem ser feitas (e têm sido) sobre o rigor dos métodos de votação, bem como os cálculos usados ​​para criar tais previsões. "Como eles podem estar tão errados?" alguns perguntaram, enquanto outros responderam com "Como eles poderiam estar mais certos, é um sistema eleitoral complicado!?"

Do seu ponto de vista como visualizador, esta fase final de compreensão é algo sobre o qual você terá controle limitado. Tudo depende. Pode ser frustrante para as pessoas que estão aprendendo visualização e que querem apenas a resposta: 'Como eu entrego entendimento ao meu público?!'

Na minha experiência, os fatores que mais influenciam o sucesso de uma visualização não são técnicos, são contextuais e, além disso, humanos. Os espectadores são pessoas. As pessoas são diferentes, e as pessoas são complexas. Eles podem ser irracionais e imprevisíveis, ou impassíveis e desengajados. Você pode levar um cavalo à água, mas não pode fazê-lo beber: não pode forçar os espectadores a se interessarem em ler seu trabalho, nem a entender o significado do que você apresenta, nem controlar como eles reagem a essa experiência. Mesmo que sua visualização mostre claramente que uma ação precisa ser tomada, você não pode garantir que os espectadores reconheçam que há necessidade de agir, estarão em posição de agir e, de fato, saberão como agir.

É neste ponto que devemos reconhecer as ambições e – mais importante – as limitações do que a visualização de dados pode oferecer. Voltando à definição pela última vez, as ilustrações que examinamos neste capítulo confirmam por que o termo facilitação é, de forma realista, o máximo que um visualizador pode fazer. Pode parecer um dever bastante morno, uma espécie de fuga que abdica da responsabilidade pelo resultado – por que não aspirar a alcançar algo mais concreto do que "facilitar"?

Eu uso para facilitar porque chega ao cerne das tensões que os visualizadores enfrentam. Há momentos em que o ônus é nosso, e outros em que o ônus é do espectador. O design de visualização não pode mudar o mundo, só pode torná-lo um pouco mais suave. Os visualizadores podem controlar a saída, mas não o resultado; na melhor das hipóteses, podemos esperar ter apenas alguma influência sobre ele. O restante deste livro trata de como otimizamos essa influência.

## 1.2 Distinções

Tendo mergulhado na definição proposta para visualização de dados, agora vale a pena reconhecer alguns outros termos e disciplinas associados com os quais você pode estar familiarizado ou ciente.

As sutilezas e a semântica dos campos de definição são preocupações recorrentes à medida que novas tecnologias se desenvolvem e técnicas criativas evoluem. À medida que a participação cresceu na última década, a visualização de dados foi polinizada de forma cruzada com sensibilidades criativas e analíticas provenientes de diferentes origens. As fronteiras tradicionais começam a se confundir e o valor prático de preservar as distinções dogmáticas diminui de acordo. Em última análise, quando alguém é encarregado de criar um retrato visual de dados, realmente importa se a criação é rotulada e arquivada em "visualização de dados" ou "infográfico", desde que atinja o objetivo de ajudar o público a alcançar alguma forma de compreensão?

No entanto, as distinções de assunto precisam ser compreendidas. É importante que as pessoas se identifiquem com uma disciplina específica na qual tenham experiência reconhecida. Vale, portanto, esclarecer algumas distinções propostas, para que, mais uma vez, estejamos na mesma página de entendimento.

<strong>Infográficos</strong>: A distinção clássica entre infográficos e visualização de dados diz respeito ao formato e ao conteúdo. Os infográficos eram tradicionalmente criados para consumo impresso, em jornais ou revistas, por exemplo. Os melhores infográficos explicam as coisas graficamente – sistemas, eventos, histórias – e muitas vezes podem ser generalizados como gráficos explicativos. Os infográficos contêm gráficos (elementos de visualização), mas também podem incluir ilustrações, imagens fotográficas, diagramas e texto. Atualmente, a arte do design infográfico continua a ser produzida para saída estática – em oposição à interativa – independentemente de como e onde o trabalho é publicado.

No início desta década houve uma explosão em diferentes formas de infográficos. De uma perspectiva purista, essa onda de trabalho era geralmente vista como uma forma inferior de design infográfico. Essas peças foram impulsionadas principalmente pelo desejo de marketing por "cliques", acima de qualquer desejo real de facilitar o entendimento. Se o seu motivo é "traseiros nos assentos", então eu sinto que este é um esforço diferente para infográficos puros e eu questionaria a legitimidade de anexar o termo infográfico a esses designs; talvez, em vez disso, pôsteres informativos ou gráficos de torre (eles geralmente existiam com uma dimensão de largura fixa e comprimento enorme para serem incorporados em sites e plataformas de mídia social) pudessem ser usados. É importante não descartar totalmente o valor evidente – ainda que superficial – desse tipo de trabalho, como demonstrado pela eventual história de sucesso viral. Mas sinto que o interesse popular por essas formas agora diminuiu e o infográfico autêntico de qualidade superior conseguiu se recuperar desse barulho.

<strong>Visualização de informações</strong>: pessoas mais inteligentes do que eu usam rótulos de visualização de dados e visualização de informações de forma intercambiável, sem pensar muito nas diferenças relevantes. A distinção geral tende a ser moldada pela ênfase em foco no material de entrada (dados) ou na natureza da forma de saída (informações). É comum que a visualização de informações seja usada como o termo para definir o trabalho que se preocupa principalmente com a visualização de estruturas de dados abstratas, como árvores ou gráficos (redes), bem como outros dados qualitativos (portanto, concentrando-se mais em relacionamentos do que em quantidades).

<strong>Design da informação</strong>: O design da informação é uma prática de design preocupada com a apresentação da informação. Está frequentemente associado às atividades de visualização de dados; de fato, às vezes é apresentado como o principal campo ao qual pertence a visualização de dados. Inquestionavelmente, ambos compartilham um motivo subjacente para facilitar a compreensão. No entanto, na minha opinião, o design da informação tem uma aplicação muito mais ampla relacionada ao design de muitas formas diferentes de comunicação visual, particularmente aquelas com um viés instrucional ou funcional, como dispositivos de orientação, como mapas de edifícios hospitalares ou no design de utilitários.

<strong>Jornalismo de dados</strong>: Também conhecido como jornalismo orientado a dados (DDJ), trata-se da importância cada vez mais reconhecida de ter habilidades numéricas, de dados e de informática no campo do jornalismo. Em certo sentido, é uma adaptação da visualização de dados, mas com raízes inquestionavelmente mais profundas nas responsabilidades do repórter/jornalista.

<strong>Análise visual:</strong> Algumas pessoas usam esse termo para se referir ao trabalho de visualização de estilo analítico, como painéis, que servem ao papel de sistemas de suporte à decisão operacional ou fornecem instrumentos de inteligência de negócios. O termo também é usado para descrever o raciocínio analítico e a exploração de dados facilitados por ferramentas visuais interativas. Isso se alinha com o papel da análise exploratória de dados que discutirei no Capítulo 4.

<strong>Ciência de dados</strong>: como um campo, a ciência de dados é difícil de definir, por isso é mais fácil considerá-la através das lentes de um cientista de dados. Os cientistas de dados são um pouco parecidos com um unicórnio, pois possuem – ou espera-se que possuam – um repertório quase absurdo de recursos que cobrem a gama de demandas envolvidas na coleta, manuseio, análise e apresentação de dados. Normalmente, o cientista de dados trabalha com dados de grande tamanho e complexidade. Os cientistas de dados têm fortes habilidades matemáticas, estatísticas e de ciência da computação, para não mencionar uma experiência comercial astuta, e também devem possuir as chamadas habilidades "mais suaves", como resolução de problemas, comunicação e apresentação.

<strong>Visualização científica</strong>: Esta é outra forma de um termo usado por muitas pessoas para diferentes aplicações. Alguns rotulam a análise exploratória de dados como visualização científica (desenhando os métodos científicos para analisar e raciocinar sobre os dados). Outros o relacionam com o uso da visualização para conceber conjuntos de dados altamente complexos e multivariados especificamente relacionados a assuntos de cunho científico (como as funções de modelagem do cérebro ou estruturas moleculares).

<strong>Arte de dados</strong>: Além das disputas sobre os méritos de certos trabalhos infográficos, a arte de dados é sem dúvida a outra disciplina relacionada à visualização que historicamente despertou mais debate. Mais uma vez, talvez seja razoável sugerir que o ruído está mais silencioso hoje em dia, mas sua simples existência ainda consegue acabar com certas seções dos illuminati de visualização de dados. Os artistas de dados trabalham com uma matéria-prima semelhante na forma de dados, mas seu objetivo não é facilitar o tipo de entendimento que uma visualização de dados buscaria. A arte de dados é mais sobre buscar uma forma de autoexpressão ou exibição estética usando dados como tinta e algoritmos como pincel. Como espectador, o significado que você extrai das exibições de arte de dados depende inteiramente da interpretação pessoal que ela convida.

<strong>Dashboard</strong>: Estes são métodos populares para exibir várias visualizações e informações estatísticas. Os painéis geralmente assumem a forma de algum instrumento organizacional que oferece visualizações rápidas e detalhadas de muitas dimensões analíticas e de informações diferentes. Os painéis não são um tipo de gráfico exclusivo, mas devem ser considerados composições que compreendem vários tipos de gráfico.

<strong>Storytelling</strong>: Este é um termo cada vez mais comum que muitas vezes é mal utilizado e mal compreendido, o que é bastante compreensível. As histórias são geralmente construídas sobre alguma noção de movimento, mudança ou narrativa. Gráficos que mostram tendências ou atividades em um plano temporal ou mapas que retratam relações espaciais oferecem exibições que são mais consistentes com a ideia de uma história. Um gráfico de barras sozinho não representa uma história, no sentido que a maioria das pessoas dá ao termo, mas se você mostrar um par de gráficos de barras para representar uma comparação de antes e depois, você criou uma dinâmica de mudança.

Da mesma forma, se você incorporar gráficos em alguma apresentação temporal, como uma apresentação de slides ou um vídeo, o gráfico se tornará um adereço e um narrador poderá desenhar a história verbalmente. Nesse caso, é o cenário e a entrega que são consistentes com a noção de narrativa, não o gráfico em si.

Outra distinção a ser feita é entre histórias que são explicitamente comunicadas e histórias que se formam por meio da interpretação. A famosa história de seis palavras À venda: sapatos de bebê, nunca usados ​​por Ernest Hemingway não é apresentado como uma história, mas a história é acionada em nossa mente quando lemos esta passagem e começamos a inferir significado, implicação e contexto. Uma história está sendo apresentada somente se for acompanhada por alguma explicação do significado dos dados. Caso contrário, qualquer história derivada é o que os próprios espectadores formam.


### Resumo: definindo a visualização de dados</a></strong></p>

Neste capítulo, você foi apresentado ao assunto da visualização de dados, aprendendo uma definição que moldará grande parte da estrutura e do conteúdo deste livro:

> A representação visual e apresentação de dados para facilitar a compreensão.

Os diferentes componentes que formam esta definição foram explicados, com foco particular nas nuances em torno da facilitação da compreensão. As três fases distintas de compreensão foram descritas:

* <em>Percepção: o que vejo?</em>
* <em>Interpretação: o que significa, dado o assunto?</em>
* <em>Compreenção: o que significa para mim?</em>

A segunda seção explicou algumas das distinções e sobreposições com outras disciplinas relacionadas.
