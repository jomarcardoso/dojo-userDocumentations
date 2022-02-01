# Documentação de software para usuários 

Um guia de uso ou manual do usuário tem como principal função ajudar os usuários a entenderam o seu produto. Um manual de software pode ser para apresentar uma aplicação, uma biblioteca, um design system, entre outros. Apesar de apresentarem as informações de forma diferente todos esses guias possuem assuntos comuns, como usuário alvo, objetivo do documento, formato a ser disponibilizado e vários elementos comuns como dúvidas comuns, suporte... Além de instruir o usuário a documentação serve também para divulgar o produto, melhorar a imagem dele e principalemente reduzir custos de suporte, que muitas vezes envolve o tempo dos desenvolvedores que trabalham no respectivo produto.

Você tem a missão de fazer seu produto ser entendido pelo seus clientes, a documentação então deve servir como um instrumento para isso e não apenas serem páginas sem uso.
Por isso também, uma documentação não deve ser feita com o objetivo de consertar um produto, nesses casos pode ser necessário escrever muito para avisar o usuário sobre todas as nuâncias e problemas que podem ocorrer. Antes disso, melhore seu produto para que a documentação seja mais objetiva possível e sob nenhuma circunstância, deve substituir um mal planejamento. Se algo precisa de vários páginas para minimamente ser usado, é melhor repensar o elemento daquele produto e torná-lo mais intuitivo.

**Figura 1: Tupolev Tu-154**

![tupolev fora de controle](https://i.imgur.com/LVNzvxc.gif?noredirect)

Nesse gif da Figura 1 mostra um avião que logo após a decolagem perdeu o controle e precisou retornar para um pouso forçado. Uma investigação concluiu que a causa da perda de controle foi um mau funcionamento do sistema de piloto automático. Aparentemente, um engenheiro o conectou incorretamente, causando estragos nos controles do avião, que segundo Lito do canal Aviões e Músicas, as cores dos fios eram intuitivas para serem ligadas "verde com verde", "vermelho com vermelho"... Porém no manual dizia que deveria ser ligado diferente, um bom exemplo de como o manual não é a forma mais segura e eficiente de solucionar os problemas do produto.

## História

O primeiro e mais importante marco da sociedade para a criação das documentações foi a criação da escrita Cuneiforme, Figura 1, entre 4000 e 3200 a.C. Antes dos sumérios desenvolverem a escrita, a maneira de transmitir o conhecimento dos povos pré-históricos era predominantemente oral e por isso havia poucos registros, além das pinturas rupestres, deixados por eles. Nessa época quando o transmissor falessia, ficaria a cargo dos ouvintes continuar a transmitir e caso acontecesse alguma fatalidade com aquele povo, o conhecimento todo deixaria de existir. Um exemplo de povo que passou por essa transição foi o povo hebreu que desde a sua origem com seu o patricar Abraão até antes de aproximarem dos egípcios não tinham o conhecimento da escrita e após Moisés aprender com os egípcios, fez um registro retroativo de tudo que foi passado para ele de forma oral, por isso essas histórias eram pobres em detalhes e com datas normalmente zeradas.

**Figura 2: escrita cuneiforme**

![exemplo de escrita cuneiforme na pedra](https://www.estudopratico.com.br/wp-content/uploads/2015/11/escrita-cuneiforme-1200x675.jpg)

Infelizmente, várias empresas do século XXI têm o mesmo problema de povos da pré-escrita. A informação de sistemas complexos, aliada a códigos com grande débito técnico, é transmitida por via oral, formando silos de conhecimento em forma de colaboradores. Quando esses silos estão inacessíveis, fica a cargo dos desenvolvedores fazerem um trabalho de arqueólogo e escavar o código, para tentar entender o que as pessoas que o escreveram queriam dizer.

## Documentação de conhecimentos

Antes de falarmos sobre o que podemos documentar, precisamos entender o conceito de conhecimento tácito e explícito, dividido pela filosofia. O conhecimento tácito é aquele que a pessoa adquiriu ao longo da vida, pela experiência. Geralmente é difícil de ser formalizado ou explicado a outra pessoa, pois é subjetivo e inerente às habilidades de uma pessoa. Já o conhecimento explícito é o conhecimento que já foi ou pode ser articulado, codificado e armazenado de alguma forma em alguma mídia. Ele pode ser prontamente transmitido para outras pessoas. Baseado nesse entendimento, entende-se que a documentação é a formalização dos conhecimentos que pode ser explicitado em alguma mídia. Para começar uma documentação é muito mais prático buscar todo conhecimento explícito, porém conforme avança a projeto de documentar, deve-se tentar formalizar qualquer conhecimento tácito sobre o produto e evitar casos em que somente alguns sabem mexer ou resolver um problema e ele não está descrito em lugar algum.

Documentação é o conjunto de todos documentos, que são todas as fontes contendo informações que ajudem a tomar decisões, comuniquem decisões tomadas, registrem assuntos de interesse da organização ou do indivíduo. Tem como característica reunir informações escritas acumuladas numa série sucessiva de anotações, quando dizem respeito a uma organização ou a um indivíduo, assumem a característica de documento. O conjunto dos documentos passa a constituir a documentação, com fins comerciais, industriais, jurídicos, escolares, etc.

## Metodologia ágil e documentação

O Manifesto Ágil foi um marco para a organização e planejamento nos projetos de sofware. Ele veio solucionar o problema de planejar tudo no começo, executar e em algum momento perceber que o que está sendo feito não era o esperado. Do Manifesto Ágil também vem a frase "Software em funcionamento mais que documentação abrangente". Essa afirmação pode ser mal interpretada, como a documentação não ser algo importante, mas entendo o ágil, sabe-se que o objetivo é priorizar a entrega do produto antes de qualquer outra coisa e não como nos antigos modelos de projeto de sofware onde criava-se uma vasta documentação para só depois começar o desenvolvimento. Gerar documentação inicial pode ser um grande problema. A ideia inicial, até o fim da concepção, pode pivotar de tantas maneiras que irá demandar alto esforço para manter a documentação atualizada, ou até ser completamente descartada e refeita do zero. Tirando a documentação de especificações, opte por sempre documentar o produto no final.

Baseado também no livro Código Limpo, pode-se dizer que software bem escrito não precisa ser documentado, mas mesmo que um software possua uma ótima arquitetura e fortes laços com técnicas clean code, apenas os devs têm o controle do fonte e conhecimento em traduzir para uma linguagem de alto nível, então se o usuário do seu produto não tem acesso a esse código ou então terá dificuldades de entendê-lo a documentação será efetiva para o esclarecimento do que a aplicação faz.

Documentar o software faz parte do desenvolvimento do produto, mesmo em metodologias ágeis, por isso é preciso responder a seguinte pergunta: "o sofware funciona bem sem a documentação dele?" Se não, como pode ser considerado software funcionando se ele só irá funcionar adequadamente com as instruções do manual dele. Outra questão que deve-se fazer é "o valor da documentação é maior que o custo de criar e manter?" Os agilistas devem considerar escrever a documentação quando essa é a melhor maneira de atingir as metas relevantes ou quando ela é parte fundamental e compõe o produto, pois do que adiantaria um produto entregue se ninguém sabe usá-lo.

Como você vê na Figura 2, a estratégia ágil é adiar a criação de todos os documentos o mais tarde possível, criando-os antes de precisar deles por meio de uma prática chamada "documento atrasado". Por exemplo, as visões gerais do sistema são melhor escritas no final do desenvolvimento de uma versão porque você sabe o que realmente construiu. Da mesma forma, a maioria da documentação de usuário e suporte também é melhor escrita no final do ciclo de vida. Ao esperar para documentar as informações depois de estabilizadas, você reduz tanto o custo quanto o risco associado à documentação. O custo é reduzido porque você não perderá tempo documentando informações que mudam, o que, por sua vez, o motiva a atualizar a documentação. O risco é reduzido porque há uma chance significativamente menor de que sua documentação existente esteja desatualizada.

**Figura 2: curva de esforço na escrita da documentação**

![image](https://user-images.githubusercontent.com/27368585/150263512-b97ef20f-5ac9-476f-81ad-0b656cdcb84a.png)

Assim como qualquer produto no modelo ágil, a documentação não precisa ser perfeita, apenas boa o suficiente, então muitas vezes ela estará desatualizada em alguns pontos e da mesma forma como o resto do produto no modelo ágil, a documentação pode ter seus ciclos, onde se escreve, apresenta, recebe os comentários e age sobre eles. Essa prática previne de se afastar do que seus clientes realmente precisam.

## O que não documentar

**O óbvio:** documentar algo apenas por ficar bonito na página principal da wiki da empresa não irá valer a pena, não irá agregar valor e será mais uma informação para manter (ou esquecer).

## 1. Determine os propósitos empresariais da documentação

Um guia do usuário deve sempre responder a pergunta "como eu faço... ?" Então se o guia ficar muito extenso irá atrapalhar nessa resposta.

## 2. Entenda o público para o qual está escrevendo a documentação

Você deve estar próximo do seu público, deve ouvir as necessidades deles e entender o que eles realmente precisam.

Não adianta escrever algo que não será usado. Entenda as perguntas do usuário, e quando for escrever, coloque-se no lugar dele.

Outra coisa importante é identificar o conhecimento dos usuários. Essa doc será consumida por pessoas dentro de um time numa empresa, ou pelo público em geral num projeto open source? 

Após identificadas as personas pode ser necessário criar documentações separadas.

O ideal de uma documentação é servir tanto para pessoas experientes como as recém chegadas na empresa, para isso, muitas vezes é preciso adaptar o nível técnico ou detalhamento de acordo com o contexto de quem lerá, mantendo o texto tão didático quanto possível para todos os públicos. Para essa documentação única deve-se sempre se atentar de que o "óbvio" é relativo; às vezes, achamos que qualquer um entende aquilo que consideramos simples, mas isso nem sempre é verdade.

Você é um especialista que conhece os termos, as suposições e os atalhos da área de assunto. Não dê saltos lógicos ou de conteúdo que os não especialistas não entendam. Possivelmente, você deve "afirmar o óbvio", porque o público não conhece o assunto, no entanto, não forneça informações desnecessárias, então se uma frase for suficiente, não inclua uma página de capturas de tela.

Há diversas maneiras de determinar como satisfazer suas necessidades com sua documentação.

- Observe os próprios usuários. Apesar dos títulos dos funcionários geralmente indicarem o que as pessoas fazem, pode haver uma variação considerável em como certos títulos são usados dentro de uma certa organização. **Entrevistando os possíveis usuários, é possível descobrir se suas impressões sobre suas necessidades são precisas ou não**.
- Observe a documentação existente. A documentação de versões anteriores do software, bem como especificações funcionais, fornecem alguma indicação do que o usuário precisará saber para usar o programa. Tenha em mente, no entanto, que **usuários finais não se interessam em como o programa funciona, mas sim pelo que ele pode fazer por elas**.
- Identifique as tarefas necessárias para realizar o trabalho e as que precisam ser realizadas antes delas.


- Antecipar perguntas: É basicamente um exercício de empatia: tente antecipar as dúvidas que possam surgir ao longo do texto e já respondê-las no mesmo local de aparecimento.

## 3. Determine os formatos apropriados para a documentação

A documentação de software pode ser estruturada em 1 ou 2 formatos, o manual de referência e o guia de usuário. Às vezes uma combinação de formatos é a melhor abordagem.

O formato de manual de referência tem o objetivo de explicar as características individuais do produto, como cada elemento funciona. Esse manual pode ser usado
junto ao produto, como uma dica de uso ou um informações vindas de um botão de ajuda. Os manuais de referência podem também ser estruturados na forma de documentos, assim ter as informações de cada elemento do produto em um só lugar. Essa abordagem de centralizar o conteúdo exige que o conteúdo seja indexado, conter exemplos práticos e se possível ter uma forma de busca. Manuais de referência são muito comuns nas universidades para instruir os estudantes na escrita de seus artigos seguindo os padrões que a universidade exige https://www.unaerp.br/arquivos/manual_referenciatc.pdf.
 
Um formato de guia de usuário explica como usar o programa para realizar uma tarefas em particular. Diferente do manual de referência o guia foca nos casos de uso do usuário e não nas partes isoladas do produto, por isso os guias geralmente tomam a forma de tutoriais, com um resumo das tarefas a serem realizadas na introdução e instruções dadas nos passos numerados. Muitas vezes o guia do usuário pode ter vídeos para cada tarefa, mostrando os passos que o usuário deve seguir, como um passo a passo de uma receita mostrada na TV.

Geralmente cada tópico do guia é independente do seu contexto, focado apenas na atividade atual, para que o usuário consiga sem muita instrução periférica resolver o seu problema. Sempre que possível evite saltos de conteúdos, eles dificultam o entendimento, as vezes repetir um pouco do conteúdo é melhor que tirar o foco do usuário. Voltando no exemplo da receita, muito mais fácil toda a receita em um lugar do que buscar em cada página como se faz cada camada. Em casos em que precisa da realização de uma tarefa prévia ou a repetição de conteúdo ficar muito extensa é possível fazer links para esses outros materiais. Apesar de cada tópico ser autosuficiente deve-se oferecer ao usuário a possibilidade de visitar os manuais de referência dos elementos envolvidos na respectiva tarefa ou então ter links para outros guias complementares.

## 4. Decida quais formas a documentação deve tomar.

A documentação de software para usuários finais pode tomar uma de várias ou diversas formas: manuais impressos, documentos PDF, arquivos de ajuda ou ajuda online. Cada forma é feita para mostrar ao usuário como usar cada uma das funções do programa, seja na forma de um walkthrough ou tutorial; no caso de arquivos de ajuda e ajuda online, pode-se incluir vídeos de demonstração, bem como texto e imagens.

## 5. Como escrever

O conceito de "single source of truth" (única fonte da verdade) prega que um único local seja mantido como fonte de consulta para todas as questões relativas a um assunto. É mais fácil manter as atualizações sob controle em um único local, portanto essa é uma boa prática a se buscar.

> eu mesmo: as vezes é melhor ter algo copiado do que jogar o usuário de um lado para o outro.

Um documento desnecessariamente longo é um documento difícil de ler e de manter. Tente delimitar até onde explicar um tópico dentro da doc ou quando é hora de linkar pra um tutorial externo mais especializado. Para pessoas mais avançadas que possam precisar de mais detalhes, essa é uma forma de dar o caminho sem penalizar as outras com conteúdo extra.

Ainda na linha do item anterior, é preciso ser tão objetivo quanto possível. Se um processo tangente começar a ficar muito detalhado, pode ser necessário separá-lo em outra documentação.

Reforçando esse ponto colocado anteriormente, evitar detalhes que podem facilmente mudar diminui drasticamente a frequência com que a documentação ficará desatualizada. Se os detalhes inconstantes em questão puderem ser encontrados em uma fonte externa mais atualizada (por exemplo, informações sobre um plugin ou dependência de terceiros), é melhor linkar a ela do que replicar esse conteúdo dentro da sua documentação.

Peça a revisão de pessoas familiarizadas com o sistema documentado, pra que elas validem se você cobriu todos os pontos e se não esqueceu de nada. Depois, peça a revisão de pessoas não familiarizadas. Essa é a parte mais importante para simular como uma pessoa nova entenderá a documentação, e geralmente é onde se recebe mais feedbacks.

Os parágrafos de instruções devem iniciar com verbos dizendo o que ela precisa fazer: "Abra a válvula...", "Pressione o botão de emergência...", "Informe o seu supervisor...".

Agrupe as procedimentos semelhantes, ordenando do mais usado para o menos usado. Em casos em que o "guia do usuário" e o "manual de referência" ficam no mesmo arquivo, pode dividir o arquivo em duas partes, começando pelo guia.

### Título principal e primeiro parágrafo

Procure escrever um título que já deixe claro do que se trata aquele texto. E caso a pessoa tenha alguma dúvida, o primeiro parágrafo serve de apoio para entender se é nesse documento que ela vai encontrar a informação que procura.

> Guia de Acessibilidade Mobile
> 
> Este documento é um guia de referência para descobertas recentes e novas práticas que devem ser disseminadas em nosso projeto para continuamente melhorar a acessibilidade do mobile app. Neste momento, nossos esforços estão focados nos leitores de tela VoiceOver (iOS) e TalkBack (Android).

### Resolver primeiro, detalhar depois

Cada dia mais as pessoas esperam que a tecnologia resolva seus problemas e de forma rápida, por isso essa técnica rapidamente resolver o problema da pessoa é amplamente difundida no meio digital, vide o sucesso do Google que sua página principal não é mais um site de pesquisa e sim um resolvedor de problema onde pode-se peruntar qualquer coisa que ele te responde, seja um cálculo, significado da palavra, tradução, entre outros. Essa praticidade deve ser trazida para a documentação, a solução do problema da pessoa deve estar nas primeiras linhas seja do capítulo ou da página. A leitura extensa também é algo bom, porém ela não será feita no momento em que a pessoa procura solução e sim quando que ela quer aprofundar seus conhecimentos sobre o produto.

A maioria das pessoas não irá ler a documentação e sim, escaneá-la para rapidamente encontrar o que precisa. Por isso é importante estabelecer uma hierarquia visual para facilitar o entendimento rápido e localização das informações. Após isso, deve-se testar a eficácia da hierarquia definida, verificando se é possível pular direto pra um tópico no meio do texto e entender o que está acontecendo ali. Muitas vezes numa instrução será preciso explicar ao usuário que ele precisa completar passos anteriores àquele para continuar sua tarefa e isso deve ficar claro no início da etapa. A aplicação mais útil aqui é explorar a formatação do texto para criar níveis de título e subtítulo e, assim, agrupar conjuntos macro e micro de informações. Outro recurso que pode facilitar a rápida procura é o uso de imagens, principalmente na forma de banners, para que o usuário consiga atráves de uma imagem resumida do que se trata aquele capítulo.

Outro motivo para não misturar instruções com informações contextuais, é para não criar distrações para o usuário, até mesmo por questões de acessibilidade, como TDAH, então quando for necessário contextualizar é recomendado que seja feito antes da instrução.

> Uma das coisas que tive dificuldade de aprender, foi o Redux, além de ser um conceito mais complexo de entender, todos os materiais que eu encontrava, explicavam da mesma forma. Começava pelo detalhamento explicando todos os recursos da tecnologia para no fim ensinar o principal mecanismo e só nesse momento tudo poderia fazer sentido, porém isso era um problema para mim, pois sempre que eu chegava no final já havia esquecido o começo, ou seja, não seguia a hierarquia de resolver primeiro e detalhar depois. Outro problema dos materiais que lia, é que sempre que no meio do texto falava-se termos complexos que são usados no Redux, o que é um problema quando se está tentando aprender algo e descobre que possui outras lacunas de conhecimento a serem preenchidas, então para resolver isso os manuais já vinham com a explicação desses termos inseridas dentro do conteúdo, mas aí além de eu não entender por não conhecer o vocabulário, perdia totalmente o foco do aprendizado, para entender o significado daquele termo. Tempos depois descobri que se não falassem desses termos o meu entendimento seria o mesmo, então não precisava nem mencioná-los, nem explicá-los.

 Você deve se esforçar para viajar o mais leve possível, escrevendo apenas na documentação suficiente para a situação em questão, que é apenas boa o suficiente para cumprir seu propósito.

O documento grande provavelmente teria a maioria das informações necessárias para manter e aprimorar seu sistema, mas você confiaria nas informações contidas nele? O documento mais curto provavelmente não conteria as informações detalhadas de que você precisa, mas forneceria um mapa de onde você poderia mergulhar no código-fonte ou em outros documentos para obter detalhes.

### Informação fácil de



### Saltos de conteúdos
 

 
 Fazer link de conteúdos e não repetí-los, isso evita uma sobrescrita de informações desatualizadas. (ver sobre evitar saltos)

### Hierarquia da informação

A melhor forma de apresentar o conteúdo pode variar dependendo do tipo de processo a ser descrito. Instruções passo a passo ficam mais claras se enumeradas; opções de ação sem ordem definida ficam bem organizadas em tópicos; um assunto menos técnico pode ficar bem resolvido com um FAQ, e assim por diante. Na dúvida, teste mais de um formato antes de definir.

Não escrever listas muito extensas, no máximo 10 itens. Se possível divida a lista em mais tópicos.


Instruções de passo a passo são aquelas que o usuário deve seguir uma sequência de atividades para poder concluir determinada tarefa. Essas instruções ficam mais claras quando enumeradas, pois nesse caso a ordem é importante e uma instrução só pode ser concluída após a outra. Uma etapa pode ser pulada caso o usuário já tenha feito ela em outro momento ou ela seja opcional. Mas atenção, uma etapa opcional não são informações adicionais e sim um passo a mais que terá um resultado final diferente.

O começo e o fim das instruções devem ser bem definidos, iniciando por um título que descreve a instrução e ao fim sempre deixar bem claro quando acabaram as instruções para o usuário não ficar se pergutando se falta alguma coisa ou para onde ele segue naquele momento.



### Índice e pesquisa

Arquivos de ajuda devem ser indexados e pesquisáveis por palavras chave para que os usuários encontrem a informação desejada rapidamente. Apesar de ferramentas de escrita poderem gerar índices automaticamente, é melhor fazê-lo manualmente, usando termos que os usuários provavelmente buscarão.

O índice, sumário ou tabela de conteúdos, serve para facilitar a pré-visualização do conteúdo e também para navegação rápida no texto.

### Detalhes que enriquecem

Incluir links dos materiais usados como referência no final da doc é uma boa prática tanto para creditar os autores quanto para leitores que possam se interessar em conhecer melhor aqueles assuntos. Sempre que fizer uma referência a um conceito ou processo, como por exemplo Markdown, selecione um material complementar sobre aquele assunto e crie um link. Assim, uma pessoa que não saiba exatamente do que se trata ou queira detalhes pode consultar uma fonte selecionada por você, o que garante que vocês estarão na mesma página (pun intended).

Screenshots, gifs, ilustrações, gráficos, memes… Escolha a melhor forma de ilustrar o conteúdo e use quantas figuras forem necessárias pra tornar o texto mais dinâmico e didático.

Quando for possível, crie um exemplo de uso do processo descrito para ilustrar sua aplicação na prática. Esse detalhe sempre fará toda a diferença na clareza da mensagem.


## 6. Oque escrever

Em docs mais técnicas, uma seção de Troubleshooting (solução de problemas) pode ser especialmente útil para documentar erros e obstáculos conhecidos e mostrar o caminho para contorná-los. É importante manter essa seção atualizada, visto que não é incomum passarmos mais tempo tentando solucionar bugs do que desenvolvendo de fato.

Na maioria dos casos, é interessante que ao final do documento conste um canal de contato para sanar dúvidas e enviar sugestões. Se for um Readme no GitHub, essa seção também pode orientar sobre como e quando abrir uma issue no repositório.

## Divulgação

Não importa o quão bem escrita é a documentação se ninguém sabe que ela existe.

## Dicas

- O texto deve ser organizado para leitura fácil, com imagens posicionadas próximas do texto relacionado a elas. Divida a documentação em seções e tópicos de forma lógica. Cada seção ou tópico pode ser referenciado com um "veja também" ou links, conforme necessário.
- As ferramentas de documentação listadas acima podem ser suplementadas com um programa de criação de screenshots, como o Snagit, se a documentação exigir diversos screenshots. 
- Assim como com outras documentações, essas capturas de tela devem ser inclusas para ajudar a explicar como o programa funciona, e não para impressionar o usuário.
O tom é particularmente importante, especialmente ao escrever documentação para usuários finais. Chame-os de "você" ao invés de "usuários".

## Conclusão

Você não pode agradar a todos os usuários o tempo todo, no entanto, com uma avaliação cuidadosa dos usuários típicos e das tarefas que eles realizam, você pode criar uma documentação excelente que ajuda a maioria dos usuários. Essa documentação diminuirá seus custos de suporte e aumentará sua reputação.

## Referências

https://pt.wikihow.com/Escrever-Documenta%C3%A7%C3%A3o-de-Software

http://www.softwaredocumentation.info/DocumentingSoftware.aspx

http://www.techscribe.co.uk/ta/how-to-write-user-documentation.htm

http://www.techscribe.co.uk/ta/how-to-write-instructions.htm

https://www.techscribe.co.uk/techw/improving-instructions.htm

Rodney Ruff, Omaha, NE; experiência em escrita técnica/autor de arquivos de ajuda desde 1997

https://medium.com/larimaza-pt/como-escrever-boas-documenta%C3%A7%C3%B5es-b36131d78f7c

https://pt.wikipedia.org/wiki/Conhecimento_expl%C3%ADcito

https://pt.wikipedia.org/wiki/Conhecimento_t%C3%A1cito

https://blog.geekhunter.com.br/qual-e-a-importancia-da-documentacao-de-software/

https://blog.db1.com.br/projetos-ageis-documentar-ou-nao/

http://www.agilemodeling.com/essays/agileDocumentationBestPractices.htm

https://www.youtube.com/watch?v=pnKm5ondK7Q&t=632s

https://jalopnik.com/russian-pilots-once-landed-a-plane-in-one-piece-despite-1847261398

## Minhas teorias

Uma documentação deve ser independente do seu entorno, pois não deve-se julgar que o usuário leu outros conteúdos antes de chegar no atual. Para resolver isso é bom apenas avisar o usuário que ele pode precisar de conhecimentos adicionais e indicar onde ele pode buscar.

Não forçar o usuário a dar saltos de ida e volta na documentação para ele entender o que precisa, essa prática tira a foco da pessoa que tem que se situar novamente onde tinha parado. Um salto pode ser feito para evitar que o usuário leia mais do que ele precisa para resolver o seu problema e assim pode-se criar uma jornada para ele.

Evitar fazer comentários que não agregam no entendimento do conteúdo do manual naquele momento. Por exemplo no caso da documentação do Redux, que hoje está mudada onde várias vezes eles paravam para explicar sobre funções puras e objetos simples e fazia quem lia pensar em assuntos que aquele conhecimento era necessário para poder prosseguir, então muitas vezes tinha que pesquisar em outro lugar para entender aqueles termos e perdia o foco do entendimento.

Criar jornadas. Não ensine algo que prepare para outra coisa sendo que não será usado naquele momento, pois quando chegar a hora de usar o usuário pode ter esquecido. O mesmo exemplo do Redux que ensinava vários conceitos antes de começar, aí a última coisa que ensinavam era o Store que é a peça principal de uma aplicação feita em Redux. Se na documentação de como usar eles começassem diretamente pelo Store, o usuário poderia ir aplicando e melhorando conforme lê e ganha mais conhecimento.

Se colocar no lugar do usuário. Se não consegue, peça que algum usuário leia e te dê o retorno.
