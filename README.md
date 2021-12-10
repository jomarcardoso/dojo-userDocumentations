# Documentação de bibliotecas de software e design systems para usuários finais


## 1. Determine os propósitos empresariais da documentação

Apesar da razão funcional ser ajudar usuários a entenderem a usar o aplicativo, há outros motivos também, como ajudar a anunciar o programa, melhorar a imagem da empresa, e, mais importante, reduzir custos de suporte técnico. Em alguns casos, a documentação é necessária para cumprir certos regulamentos ou outras exigências legais.

- Sob nenhuma circunstância, no entanto, a documentação deve substituir um design de interface ruim. Se uma tela de um aplicativo requer páginas e páginas de documentação para explicá-la, é melhor mudar o design para deixá-la mais intuitiva.

## 2. Entenda o público para o qual está escrevendo a documentação

Há diversas maneiras de determinar como satisfazer suas necessidades com sua documentação.

- Observe os próprios usuários. Apesar dos títulos dos funcionários geralmente indicarem o que as pessoas fazem, pode haver uma variação considerável em como certos títulos são usados dentro de uma certa organização. **Entrevistando os possíveis usuários, é possível descobrir se suas impressões sobre suas necessidades são precisas ou não**.
- Observe a documentação existente. A documentação de versões anteriores do software, bem como especificações funcionais, fornecem alguma indicação do que o usuário precisará saber para usar o programa. Tenha em mente, no entanto, que **usuários finais não se interessam em como o programa funciona, mas sim pelo que ele pode fazer por elas**.
- Identifique as tarefas necessárias para realizar o trabalho e as que precisam ser realizadas antes delas.

## 3. Determine os formatos apropriados para a documentação

 A documentação de software pode ser estruturada em 1 ou 2 formatos, o manual de referência e guia de usuário. Às vezes uma combinação de formatos é a melhor abordagem.
 
- Um formato de manual de referência é devotado a explicar as características individuais de um aplicativo (botões, guias, campos e caixas de diálogo) e como elas funcionam. Muitos arquivos de ajuda são escritos nesse formato, que exibe um tópico relevante sempre que um usuário clicar no botão de ajuda de uma certa tela.
- Um formato de guia de usuário explica como usar o programa para realizar uma tarefa em particular. Esses guias normalmente são impressos ou exibidos virtualmente em PDFs, apesar de alguns arquivos de ajuda incluírem tópicos de como realizar tarefas em particular (esses tópicos de ajuda geralmente não são sensíveis ao contexto, apesar deles poderem conter links para tópicos que sejam). Os guias de usuário geralmente tomam a forma de tutoriais, com um resumo das tarefas a serem realizadas na introdução e instruções dadas nos passos numerados.

## 4. Decida quais formas a documentação deve tomar.

A documentação de software para usuários finais pode tomar uma de várias ou diversas formas: manuais impressos, documentos PDF, arquivos de ajuda ou ajuda online. Cada forma é feita para mostrar ao usuário como usar cada uma das funções do programa, seja na forma de um walkthrough ou tutorial; no caso de arquivos de ajuda e ajuda online, pode-se incluir vídeos de demonstração, bem como texto e imagens.

- **Arquivos de ajuda devem ser indexados e pesquisáveis por palavras chav**e para que os usuários encontrem a informação desejada rapidamente. Apesar de ferramentas de escrita poderem gerar índices automaticamente, é melhor fazê-lo manualmente, usando termos que os usuários provavelmente buscarão.

## 5. Como escrever

### Título e primeiro parágrafo

Procure escrever um título que já deixe claro do que se trata aquele texto. E caso a pessoa tenha alguma dúvida, o primeiro parágrafo serve de apoio para entender se é nesse documento que ela vai encontrar a informação que procura.

> Guia de Acessibilidade Mobile
> 
> Este documento é um guia de referência para descobertas recentes e novas práticas que devem ser disseminadas em nosso projeto para continuamente melhorar a acessibilidade do mobile app. Neste momento, nossos esforços estão focados nos leitores de tela VoiceOver (iOS) e TalkBack (Android).

## Dicas

- O texto deve ser organizado para leitura fácil, com imagens posicionadas próximas do texto relacionado a elas. Divida a documentação em seções e tópicos de forma lógica. Cada seção ou tópico pode ser referenciado com um "veja também" ou links, conforme necessário.
- As ferramentas de documentação listadas acima podem ser suplementadas com um programa de criação de screenshots, como o Snagit, se a documentação exigir diversos screenshots. 
- Assim como com outras documentações, essas capturas de tela devem ser inclusas para ajudar a explicar como o programa funciona, e não para impressionar o usuário.
O tom é particularmente importante, especialmente ao escrever documentação para usuários finais. Chame-os de "você" ao invés de "usuários".

## Referências

https://pt.wikihow.com/Escrever-Documenta%C3%A7%C3%A3o-de-Software

http://www.softwaredocumentation.info/DocumentingSoftware.aspx

http://www.techscribe.co.uk/ta/how-to-write-user-documentation.htm

http://www.techscribe.co.uk/ta/how-to-write-instructions.htm

Rodney Ruff, Omaha, NE; experiência em escrita técnica/autor de arquivos de ajuda desde 1997

## Minhas teorias

Uma documentação deve ser independente do seu entorno, pois não deve-se julgar que o usuário leu outros conteúdos antes de chegar no atual. Para resolver isso é bom apenas avisar o usuário que ele pode precisar de conhecimentos adicionais e indicar onde ele pode buscar.

Não forçar o usuário a dar saltos de ida e volta na documentação para ele entender o que precisa, essa prática tira a foco da pessoa que tem que se situar novamente onde tinha parado. Um salto pode ser feito para evitar que o usuário leia mais do que ele precisa para resolver o seu problema e assim pode-se criar uma jornada para ele.

Evitar fazer comentários que não agregam no entendimento do conteúdo do manual naquele momento. Por exemplo no caso da documentação do Redux, que hoje está mudada onde várias vezes eles paravam para explicar sobre funções puras e objetos simples e fazia quem lia pensar em assuntos que aquele conhecimento era necessário para poder prosseguir, então muitas vezes tinha que pesquisar em outro lugar para entender aqueles termos e perdia o foco do entendimento.

Criar jornadas. Não ensine algo que prepare para outra coisa sendo que não será usado naquele momento, pois quando chegar a hora de usar o usuário pode ter esquecido. O mesmo exemplo do Redux que ensinava vários conceitos antes de começar, aí a última coisa que ensinavam era o Store que é a peça principal de uma aplicação feita em Redux. Se na documentação de como usar eles começassem diretamente pelo Store, o usuário poderia ir aplicando e melhorando conforme lê e ganha mais conhecimento.

Se colocar no lugar do usuário. Se não consegue, peça que algum usuário leia e te dê o retorno.
