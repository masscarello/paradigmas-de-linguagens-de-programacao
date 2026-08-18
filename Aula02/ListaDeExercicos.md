Lista de exercícios

Evolução das Principais Linguagens de Programação

1. A genealogia das linguagens não é uma escada de progresso.
Explique essa afirmação e apresente dois fatores históricos que fazem
uma linguagem influenciar outra sem necessariamente substituí-la.
R: a afirmação quer dizer que a evolução das linguagens não ocorre de forma continua, como se uma fosse sempre melhor que a anterior. As linguagens surgem e se complementam nem sempre a linguagem que surgiu irá substituir a outra elas coexistem.

 Dois fatores históricos que demonstra isso são os avanços tecnológicos onde a criação de linguagens de programação mais modernas influenciou práticas de desenvolvimento, mas linguagens antigas, como C e COBOL, continuam sendo utilizadas em diversos sistemas.
 Intercâmbio cultural e científico, O contato entre diferentes povos, universidades e empresas permite a troca de conhecimentos e ideias, fazendo com que linguagens incorporem características umas das outras sem que deixem de existir. Um exemplo é a influência do inglês na terminologia da informática, presente em várias linguagens e tecnologias.

2. Plankalkül não foi implementada em sua época. Ainda assim, por que
ela é relevante para a história das linguagens? Cite três recursos
antecipados por seu projeto e explique o valor de um deles.

 R: Plankalkul não foi implementado porém trouxe conceitos importantes usados até hoje como, tipo de dados, vetores e matrizes, operadores condicionais e estruturas de controle, que está presente em grande parte das linguagens usadas hoje. Ou seja o conceito que ela trouxe foi de grande impacto, não dependendo de ser implementada para impactar as linguagens de programação

3. Compare Short Code, Speedcoding e os sistemas A-0/A-1/A-2 quanto
ao problema enfrentado e à estratégia adotada. Por que chamá-los
simplesmente de compiladores modernos seria impreciso? 

 R: Short Code
 Facilitar a programação, evitando escrever diretamente em código de máquina.
 Usava uma notação simbólica, que era interpretada para realizar as operações.
    Speedcoding
 Tornar a programação do IBM 701 mais rápida e acessível, reduzindo o trabalho de programação em máquina.
 Criou uma linguagem simplificada e um sistema que traduzia suas instruções para operações da máquina.
     A-0/A-1/A-2
 Automatizar a programação e reduzir a necessidade de escrever rotinas repetitivas em código de máquina.
 Utilizava sub-rotinas armazenadas e chamadas por nomes, que eram combinadas/traduzidas pelo sistema para formar o programa executável.

 eles foram passos importantes na história da tradução de linguagens, mas representam formas experimentais e iniciais de automação da programação, e não compiladores modernos no sentido atual.

4. Explique por que o projeto Fortran precisou convencer
programadores de que código traduzido podia competir com código de
máquina escrito à mão. Relacione desempenho, custo de programação
e adoção.

 R:A proposta do Fortran foi mostrar que o compilador poderia gerar código com desempenho próximo ao código feito à mão, ao mesmo tempo em que permitia escrever programas de forma muito mais rápida e simples.
 o código de máquina/assembly podia ter ótimo desempenho, mas exigia muito tempo e esforço para ser escrito e mantido.
 E o Fortran aumentava a produtividade do programador, reduzindo o custo e o tempo de desenvolvimento, sem sacrificar excessivamente o desempenho.
 Isso ajudou a estabelecer os compiladores e as linguagens de alto nível como alternativas viáveis à programação diretamente em máquina.

5. Lisp surgiu em um contexto diferente de Fortran. Compare os
domínios, a representação de dados e o estilo de computação
favorecido pelas duas linguagens.
 
 R: Fortran foi projetado para fazer cálculos numéricos de forma eficiente, enquanto Lisp foi concebido para manipular símbolos e estruturas complexas de dados. Essa diferença de objetivos explica por que as duas linguagens seguiram caminhos tão distintos na história da programação.

6. Avalie três contribuições de ALGOL 60 que ultrapassaram sua
adoção comercial. Por que uma linguagem pode ser muito influente sem
dominar o mercado?

 R: O ALGOL 60, permitiu organizar programas em blocos com escopos bem definidos, influenciando linguagens posteriores como Pascal, C e outras, possibilitou que um procedimento chamasse a si próprio, recurso fundamental para resolver problemas de forma elegante e que se tornou comum em muitas linguagens, sua especificação utilizou a Backus-Naur Form (BNF), ajudando a estabelecer uma maneira rigorosa de definir a sintaxe das linguagens de programação. Essa contribuição teve enorme impacto no desenvolvimento de linguagens posteriores.

 Uma linguagem pode ser muito influente sem dominar o mercado porque influência técnica e sucesso comercial são coisas diferentes. O mercado depende de fatores como disponibilidade de compiladores, suporte de empresas, compatibilidade com sistemas existentes, comunidade de usuários e custos de migração. Assim, mesmo que uma linguagem não seja amplamente utilizada comercialmente, suas ideias podem ser incorporadas por outras linguagens que alcançam muito mais usuários. O ALGOL 60 é um exemplo clássico: sua influência sobre o projeto de outras linguagens foi muito maior que sua participação direta no mercado.

7. COBOL foi desenhada para processamento comercial. Mostre como
domínio e público influenciaram sua legibilidade, seus registros e sua
relação com FLOW-MATIC.
 R: como o público incluía profissionais de negócios e programadores que precisavam trabalhar com sistemas administrativos, o COBOL adotou uma sintaxe próxima da linguagem natural, com palavras como ADD, SUBTRACT, MOVE e IF. A intenção era tornar os programas mais fáceis de ler e entender.
  O COBOL ofereceu registros e estruturas hierárquicas de dados permitindo representar documentos e cadastros de maneira próxima à organização real das informações, o COBOL aproveitou ideias da FLOW-MATIC, linguagem desenvolvida por Grace Hopper para processamento de negócios. A influência aparece especialmente na preocupação com programas legíveis, manipulação de dados comerciais e uso de uma sintaxe próxima ao inglês.
   Assim, o COBOL não foi pensado apenas para executar cálculos rapidamente: ele foi projetado para expressar operações comerciais de forma compreensível e trabalhar diretamente com grandes volumes de registros.
8. Compare Basic e PL/I como respostas ao desejo de ampliar o acesso
ou o alcance da programação. Qual compromisso de projeto aparece
em cada caso?  
 R: BASIC foi criado para facilitar o aprendizado e o acesso à programação, especialmente para estudantes e iniciantes. Seu compromisso de projeto foi simplicidade em troca de menor sofisticação e controle. A linguagem tinha uma sintaxe relativamente simples e permitia começar a programar rapidamente.

 PL/I: buscou ampliar o alcance de uma forma diferente: pretendia ser uma linguagem mais geral e abrangente, reunindo recursos para programação científica, comercial e de sistemas. Seu compromisso foi versatilidade em troca de maior complexidade. Ao tentar atender a muitos domínios, incorporou uma grande quantidade de recursos.

 Em resumo: o BASIC priorizou simplicidade e acessibilidade, enquanto o PL/I priorizou generalidade e poder de expressão.
9. APL, SNOBOL e SIMULA 67 seguiram direções distintas. Associe cada linguagem ao seu foco e identifique uma contribuição duradoura de cada uma.
 R: APL → foco em computação matemática e manipulação de arrays/vetores, buscando expressar operações complexas de forma muito concisa. Contribuição duradoura: a ideia de operações vetorizadas e de trabalhar com arrays como elementos centrais da linguagem, influenciando linguagens e ambientes de computação numérica posteriores.

 SNOBOL → foco em processamento e manipulação de textos, especialmente busca e reconhecimento de padrões. Contribuição duradoura: seus mecanismos avançados de pattern matching, que anteciparam ideias importantes para processamento de strings e reconhecimento de padrões.

 SIMULA 67 → foco em simulação de sistemas e modelagem de processos. Contribuição duradoura: introduziu conceitos fundamentais de programação orientada a objetos, especialmente classes, objetos, herança e mecanismos relacionados à abstração de dados.

 APL destacou-se pela computação com arrays, SNOBOL pelo processamento de padrões e textos, e SIMULA 67 pela modelagem orientada a objetos

10. Defina ortogonalidade no projeto de linguagens e use ALGOL 68 para discutir a diferença entre regularidade e simplicidade. Uma linguagem muito ortogonal é automaticamente fácil de usar?
 R: 



