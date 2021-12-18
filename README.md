# Documentação de software para usuários 

Um guia de uso ou manual do usuário tem como principal função ajudar os usuários a entenderam o seu produto. Um manual de software pode ser para apresentar uma aplicação, uma biblioteca, um design system, entre outros. Apesar de apresentarem as informações de forma diferente todos esses guias possuem assuntos comuns, como usuário alvo, objetivo do documento, formato a ser disponibilizado e vários elementos comuns como dúvidas comuns, suporte... Além de instruir o usuário a documentação serve também para divulgar o produto, melhorar a imagem dele e principalemente reduzir custos de suporte, que muitas vezes envolve o tempo dos desenvolvedores que trabalham no respectivo produto.

No entanto, uma documentação não deve ser feita com o objetivo de consertar um produto. Nesses casos pode ser necessário escrever muito para avisar o usuário sobre todas as nuâncias e problemas que podem ocorrer. Antes disso, melhore seu produto para que a documentação seja mais objetiva possível e sob nenhuma circunstância, deve substituir um mal planejamento. Se algo precisa de vários páginas para minimamente ser usado, é melhor repensar o componente daquele produto e torná-lo mais intuitivo.

História do avião que precisava do manual das cores dos fios.

## 1. Determine os propósitos empresariais da documentação

Um guia do usuário deve sempre responder a pergunta "como eu faço... ?" Então se o guia ficar muito extenso irá atrapalhar nessa resposta e um material auxiliar chamado manual de referência pode ser utilizado.

## 2. Entenda o público para o qual está escrevendo a documentação

Não adianta escrever algo que não será usado. Entenda a pergunda público alvo.

Não esquecer da diferença de conhecimentos, a documentação deve servir tanto para pessoas experientes como as recém chegadas na empresa.

Quando for escrever coloque-se no lugar do usuário principal.

Você é um especialista que conhece os termos, as suposições e os atalhos da área de assunto. Não dê saltos lógicos ou de conteúdo que os não especialistas não entendam. Possivelmente, você deve "afirmar o óbvio", porque o público não conhece o assunto, no entanto, não forneça informações desnecessárias, então se uma frase for suficiente, não inclua uma página de capturas de tela.

Há diversas maneiras de determinar como satisfazer suas necessidades com sua documentação.

- Observe os próprios usuários. Apesar dos títulos dos funcionários geralmente indicarem o que as pessoas fazem, pode haver uma variação considerável em como certos títulos são usados dentro de uma certa organização. **Entrevistando os possíveis usuários, é possível descobrir se suas impressões sobre suas necessidades são precisas ou não**.
- Observe a documentação existente. A documentação de versões anteriores do software, bem como especificações funcionais, fornecem alguma indicação do que o usuário precisará saber para usar o programa. Tenha em mente, no entanto, que **usuários finais não se interessam em como o programa funciona, mas sim pelo que ele pode fazer por elas**.
- Identifique as tarefas necessárias para realizar o trabalho e as que precisam ser realizadas antes delas.

Essa doc será consumida por pessoas dentro de um time numa empresa, ou pelo público em geral num projeto open source? É preciso adaptar o nível técnico ou detalhamento de acordo com o contexto de quem lerá, mantendo o texto tão didático quanto possível. Lembre-se de que o óbvio é relativo; às vezes, achamos que qualquer um entende aquilo que consideramos simples, mas isso nem sempre é verdade (alô, síndrome do impostor!).

Após identificadas as personas pode ser necessário criar documentações separadas.

- Antecipar perguntas: É basicamente um exercício de empatia: tente antecipar as dúvidas que possam surgir ao longo do texto e já respondê-las no mesmo local de aparecimento.

## 3. Determine os formatos apropriados para a documentação

 A documentação de software pode ser estruturada em 1 ou 2 formatos, o manual de referência e guia de usuário. Às vezes uma combinação de formatos é a melhor abordagem.
 
- Um formato de manual de referência é devotado a explicar as características individuais de um aplicativo (botões, guias, campos e caixas de diálogo) e como elas funcionam. Muitos arquivos de ajuda são escritos nesse formato, que exibe um tópico relevante sempre que um usuário clicar no botão de ajuda de uma certa tela.
- Um formato de guia de usuário explica como usar o programa para realizar uma tarefa em particular. Esses guias normalmente são impressos ou exibidos virtualmente em PDFs, apesar de alguns arquivos de ajuda incluírem tópicos de como realizar tarefas em particular (esses tópicos de ajuda geralmente não são sensíveis ao contexto, apesar deles poderem conter links para tópicos que sejam). Os guias de usuário geralmente tomam a forma de tutoriais, com um resumo das tarefas a serem realizadas na introdução e instruções dadas nos passos numerados.

## 4. Decida quais formas a documentação deve tomar.

A documentação de software para usuários finais pode tomar uma de várias ou diversas formas: manuais impressos, documentos PDF, arquivos de ajuda ou ajuda online. Cada forma é feita para mostrar ao usuário como usar cada uma das funções do programa, seja na forma de um walkthrough ou tutorial; no caso de arquivos de ajuda e ajuda online, pode-se incluir vídeos de demonstração, bem como texto e imagens.

- **Arquivos de ajuda devem ser indexados e pesquisáveis por palavras chav**e para que os usuários encontrem a informação desejada rapidamente. Apesar de ferramentas de escrita poderem gerar índices automaticamente, é melhor fazê-lo manualmente, usando termos que os usuários provavelmente buscarão. O índice, ou "Table of contents" como muitos chamam, serve para facilitar a pré-visualização do conteúdo e também para navegação rápida no texto. Se a ferramenta permitir âncoras (links que levam a pontos da mesma página), abuse delas.

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

### Organização do conteúdo

**Hierarquia da informação:** Quem tem contato com design já tem familiaridade com esse conceito: a idéia é estabelecer uma hierarquia visual para facilitar o entendimento rápido e localização das informações. A aplicação mais útil aqui é explorar a formatação do texto para criar níveis de título e subtítulo (como os headings de h1 a h6 no HTML), e assim agrupar conjuntos macro e micro de informações. Podemos também usar negrito, itálico e até mesmo cores (como o vermelho em pontos de atenção) para adicionar entonação ao texto, da mesma forma que faríamos no discurso falado.

A melhor forma de apresentar o conteúdo pode variar dependendo do tipo de processo a ser descrito. Instruções passo a passo ficam mais claras se enumeradas; opções de ação sem ordem definida ficam bem organizadas em tópicos; um assunto menos técnico pode ficar bem resolvido com um FAQ, e assim por diante. Na dúvida, teste mais de um formato antes de definir.

A esmagadora maioria das pessoas não lê, escaneia. Por isso, é preciso testar a eficácia daquela hierarquia de informação, verificando se é possível pular direto pra um tópico no meio do texto e entender o que está acontecendo ali. É isso que a maioria das pessoas fará na sua doc, por melhor escrita que ela esteja (sinceridade!).

Usar lista com números quando a ordem é importante e com símbolos quando não é.

Explicar se o usuário precisa completar passos anteriores àquele. Se for fazer um alerta, avise antes de dar a instrução, ou antes da lista onde tem a instrução.

Não misturar instruções com informações contextuais, se for preciso contextualizar, fazer antes das instruções (exemplo redux que trouxe).

Não escrever listas muito extensas, no máximo 10 itens. Se possível divida a lista em mais tópicos.

Sempre deixar bem claro quando acabaram as instruções para o usuário não ficar se pergutando se falta alguma coisa ou para onde ele segue naquele momento.

### Detalhes que enriquecem

Incluir links dos materiais usados como referência no final da doc é uma boa prática tanto para creditar os autores quanto para leitores que possam se interessar em conhecer melhor aqueles assuntos. Sempre que fizer uma referência a um conceito ou processo, como por exemplo Markdown, selecione um material complementar sobre aquele assunto e crie um link. Assim, uma pessoa que não saiba exatamente do que se trata ou queira detalhes pode consultar uma fonte selecionada por você, o que garante que vocês estarão na mesma página (pun intended).

Screenshots, gifs, ilustrações, gráficos, memes… Escolha a melhor forma de ilustrar o conteúdo e use quantas figuras forem necessárias pra tornar o texto mais dinâmico e didático.

Quando for possível, crie um exemplo de uso do processo descrito para ilustrar sua aplicação na prática. Esse detalhe sempre fará toda a diferença na clareza da mensagem.


## 6. Oque escrever

Em docs mais técnicas, uma seção de Troubleshooting (solução de problemas) pode ser especialmente útil para documentar erros e obstáculos conhecidos e mostrar o caminho para contorná-los. É importante manter essa seção atualizada, visto que não é incomum passarmos mais tempo tentando solucionar bugs do que desenvolvendo de fato.

Na maioria dos casos, é interessante que ao final do documento conste um canal de contato para sanar dúvidas e enviar sugestões. Se for um Readme no GitHub, essa seção também pode orientar sobre como e quando abrir uma issue no repositório.

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

## Minhas teorias

Uma documentação deve ser independente do seu entorno, pois não deve-se julgar que o usuário leu outros conteúdos antes de chegar no atual. Para resolver isso é bom apenas avisar o usuário que ele pode precisar de conhecimentos adicionais e indicar onde ele pode buscar.

Não forçar o usuário a dar saltos de ida e volta na documentação para ele entender o que precisa, essa prática tira a foco da pessoa que tem que se situar novamente onde tinha parado. Um salto pode ser feito para evitar que o usuário leia mais do que ele precisa para resolver o seu problema e assim pode-se criar uma jornada para ele.

Evitar fazer comentários que não agregam no entendimento do conteúdo do manual naquele momento. Por exemplo no caso da documentação do Redux, que hoje está mudada onde várias vezes eles paravam para explicar sobre funções puras e objetos simples e fazia quem lia pensar em assuntos que aquele conhecimento era necessário para poder prosseguir, então muitas vezes tinha que pesquisar em outro lugar para entender aqueles termos e perdia o foco do entendimento.

Criar jornadas. Não ensine algo que prepare para outra coisa sendo que não será usado naquele momento, pois quando chegar a hora de usar o usuário pode ter esquecido. O mesmo exemplo do Redux que ensinava vários conceitos antes de começar, aí a última coisa que ensinavam era o Store que é a peça principal de uma aplicação feita em Redux. Se na documentação de como usar eles começassem diretamente pelo Store, o usuário poderia ir aplicando e melhorando conforme lê e ganha mais conhecimento.

Se colocar no lugar do usuário. Se não consegue, peça que algum usuário leia e te dê o retorno.
