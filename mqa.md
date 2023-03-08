# Métodos Quantitativos Aplicados: uma abordagem simplificada

## ⬇️ Sumário
1. 📖 [Prefácio](#Prefácio)
2. 📖 [Introdução](#Introdução)
3. 📖 [Delineamento](#Delineamento)
   3.1. 📖 [Mensuração e Escalas](#Mensuração e Escalas)
   3.2. 📖 [Criação de Questionários](#Criação de Questionários)
   3.3. 📖 [Amostragem](#Amostragem)
4. 📖 Descrição(#Amostragem)
5. 📖 Inferência(#Amostragem)
#
## 📖 Prefácio
Quando se fala em métodos quantitativos, em um primeiro momento, muitos de nós ficamos ansiosos só de pensar sobre. Eu conheço essa sensação, tanto na condição de discente quanto na de docente. Isto é, eu já passei pelo mesmo processo que muitas pessoas também experienciam quando se trata desse tipo de conteúdo. Já senti insegurança ao me matricular em disciplinas da área, bem como vivencio isso no meu meio acadêmico, seja com orientandos, alunos e colegas de trabalho. Acredito que isso é algo bastante natural, pois cada um de nós tem preferência por determinados assuntos. Afinal, em nosso processo formativo e de vida, nos identificamos com uma determinada visão de mundo, que nos leva para escolhas sobre como entendemos a realidade que nos cerca. Nesse processo, também acabamos construindo algumas resistências com relação à determinados conteúdos. 

Tomando por base minha própria experiência, por exemplo, disciplinas como matemática e estatística nem sempre nos são apresentadas com a devida aplicabilidade ou por docentes com formação na nossa área de aplicação. Isso dificulta, muitas vezes, o aprendizado e ajuda a criar barreiras. Todavia, acredito que há uma luz no fim do túnel. Posso afirmar com segurança que se eu consegui chegar até aqui, acredite, você também conseguirá. Para tentar convencê-lo, vou contar um pouco da minha trajetória. 

Desde 2018 sou resposável pela disciplina de Métodos Quantitativos Aplicados (*aka* MQA) no Programa de Pós-Graduação em Gestão Pública e Cooperação Internacional (PGPCI) da Universidade Federal da Paraíba (UFPB). Se me perguntassem se um dia eu teria imaginado que isso ocorreria, certamente a resposta seria negativa. Afinal, minha trajetória de pesquisa iniciou como a de muitos outros estudantes de pós-graduação na área de Ciências Sociais e Humanas, buscando refúgio nos métodos qualitativos, com a falsa impressão de que eles são mais simples. 

Essa história só começou a mudar a partir do meu doutorado, quando a vontade se juntou com a oportunidade Explicando melhor, eu já tinha colocado como meta aprender métodos quantitativos. Por sorte, tive a chance de experienciar que tais conteúdos não precisam, necessariamente, vir carregados de fórmulas e expressões matemáticas. Ou seja, embora essenciais, é possível adotar uma abordagem aplicada, tentando simplificar e dar sentido prático ao que os discentes e pesquisadores realmente necessitam ao utilizar as técnicas estatísticas. 

Nessa trajetória, tive a sorte de contar com colegas, aos quais tenho muito a agradecer, que passavam pelo mesmo processo. Logo, para mim, foi como iniciar uma jornada rumo a mares desconhecidos, nunca d'antes navegados, com a devida liberdade poética, com uma tripulação motivada e colaborativa, em que todos se ajudavam. Além disso, contei com a oportunidade de experienciar o ensino de métodos quantitativos com o [Professor Franzé Costa](http://lattes.cnpq.br/8038204590897494), o qual também tenho agradecimento, que proporcionou essa experiência ao longo de quatro disciplinas que cursei e me incentivou, posteriormente, a assumir a missão de ministrar a disciplina de Métodos Quantitativos Aplicados no PGPCI.

Bom, toda prosa é boa e haveria muito mais ainda a ser contado. Mas, chega de conversa fiada e vamos ao que interessa. Aqui nesse material, você vai encontrar um conjunto de informações que, espero, possam auxiliar na utilização em pesquisas quanti, como gostamos de dizer. É minha esperança também que o conteúdo possa diminuir uma eventual resistência no aprendizado. Ele é voltado para quem está iniciando na temática, seja estudante de graduação ou pós-graduação, para curiosos e para quem deseja simplesmente complementar conhecimentos. O foco dos exemplos recai sobre questões típicas das Ciências Sociais e Humanas. Todavia, pela natureza ampla da sua aplicação, o conteúdo também pode ajudar quem está em outras áreas do conhecimento. Logo, qualquer dúvida adicional sobre o conteúdo, você pode sempre entrar em contato comigo por email, caso lhe seja conveniente.

Para navegar no conteúdo, o sumário foi pensado dentro da perspectiva de delineamento, descrição e inferência. Isto é, além deste prefácio e da introdução, os assuntos são apresentados seguindo uma concepção de planejamento e aplicação de métodos quantitativos. Utilize-o para ajudar a encontrar o tópico de interesse mais rapidamente. 

⬆️[Sumário](#sumário)

## 📖 Introdução
O livro "Como Mentir com Estatística" foi publicado em 1954 (HUFF, 2016). Apesar do tempo desde a sua primeira edição e das diversas mudanças no âmbito da sociedade, ele ainda continua bastante atual. Por isso, é com esse conteúdo, escrito por um jornalista, e não por um acadêmico, que costumo iniciar o a disciplina de Métodos Quantitativos Aplicados. O intuito é aproximar a temática para o que vivenciamos no nosso cotidiano, permeado por um bombardeio de informações, números e gráficos. Ora, se não conseguirmos fazer a devida apreciação e entender o que nos é apresentado, seremos reféns do que nos é passado, para não dizer manipulados. Além disso, o conteúdo do livro supracitado foge do academicismo e da linguagem matemática/estatística que tanto causa arrepios em muitos de nós. Ou seja, serve como um esquema geral da disciplina, tentando reduzir a ansiedade nos estudantes e criar uma expectativa do que vem pela frente. 

Por essa razão, seguimos aqui a mesma lógica, no intuito de diminuir resistências desde agora. Para tanto, vamos tentar responder algumas questões iniciais, para introduzir o conteúdo aqui proposto. Para começar, vamos refletir sobre alguns questionamentos.

### Qual a origem da estatística?
Pesquisando sobre de onde vem o termo estatística, é possível identificar que sua origem vem do latim *"status"*, que significa "estado", sendo introduzido na Alemanha no século XVIII. No entanto, já no século XVII, na Inglaterra, a estatística era conhecida como "Aritmética do Estado" (*Political Arithmetic*) e consistia na análise de registros de nascimentos e mortes, que posteriormente originaram as primeiras tábuas de mortalidade. Para a estatística se tornar uma disciplina científica foi necessário aguardar o desenvolvimento do cálculo de probabilidades. Por isso, o desenvolvimento da estatística matemática e suas aplicações ocorrem mais para o fim do século XIX. Nesse contexto, alguns personagens foram importantes. Vamos elencar quatro deles, apenas como exercício exemplificativo, já que seria possível incluir mais nomes.

- Francis Galton foi um importante estatístico inglês cujas contribuições são amplamente reconhecidas. Galton criou o conceito de correlação estatística e promoveu amplamente a regressão à média, que é um conceito importantíssimo da análise de dados. Além disso, ele introduziu o uso de questionários e pesquisas para coletar dados, ajudando também a desenvolver a psicometria. 
- Karl Pearson, um estatístico inglês, fez importantes contribuições, sendo responsável por fundamentar muitos dos métodos "clássicos" que são comumente utilizados atualmente. Dentre outros, ele desenvolveu o coeficiente de correlação produto-momento, que é uma medida da força de associação entre duas variáveis ​​quantitativas, bem como o teste qui-quadrado de Pearson, que é usado para testar a independência de duas variáveis. 
- William Sealy Gosset, também inglês, é conhecido pelo pseudônimo de "*Student*". Gosset é conhecido por suas contribuições para a estatística, em particular a distribuição t de Student, que foi desenvolvida durante seus estudos na cervejaria Guinness. Ele observou que, quando as amostras eram pequenas, a distribuição das médias amostrais não seguia a distribuição normal exata, e desenvolveu uma nova distribuição que levava em consideração o tamanho da amostra. Essa distribuição, conhecida como distribuição t de Student, é amplamente utilizada em testes de hipóteses e análise de dados. Gosset trabalhou com Karl Pearson, mas, como funcionário da Guinness, não podia publicar sob seu nome. Por isso, ele criou o pseudônimo e publicou suas descobertas sob esse nome. 
- Ronald Fisher, geneticista e biólogo inglês, é conhecido por ter desenvolvido a análise de variância (ANOVA), uma técnica estatística que permite comparar as médias de três ou mais grupos de dados. Além disso, Fisher foi o primeiro a propor o uso do valor p como uma medida rigorosa da confiabilidade de uma amostra de dados como fonte de previsão científica. Ele também desenvolveu a técnica de máxima verossimilhança, que é usada para estimar os parâmetros de um modelo estatístico a partir de dados observados, e contribuiu para o planejamento de experimentos.

### O que é estatística?

Segundo Agresti e Finlay (2012), a estatística é um conjunto de métodos utilizados para obter e analisar dados em estudos de pesquisa quantitativa. Podemos esquematizá-la em torno de três dimensões: delineamento, descrição e inferência. Essa é a forma típica em que o conteúdo é apresentado em livros acadêmicos. Em geral, para todas elas, é preciso planejamento e, posteriormente, execução.

* O **delineamento** da pesquisa diz respeito a como os dados serão coletados, envolvendo a escolha de sujeitos e instrumentos. Isso nos leva a necessidade de entender o que está envolvido no processo de mensuração, escalas, criação de questionários e amostragem.
* A **descrição** dos dados é feita por meio de gráficos, tabelas e resumos numéricos. Aqui é preciso construir conhecimento sobre organização e limpeza de dados, gráficos, medidas de posição, dispersão e forma.
* A **inferência** é o processo de fazer previsões com base nos dados coletados, utilizando testes de hipóteses. Para tanto, é preciso ter noção sobre distribuições de probabilidade as técnicas disponíveis, que dependem do tipo de variáveis que temos em mão.

Para além dessas definições, é importante também entender a diferença entre alguns termos clássicos, sempre necessários para se pensar na execução de uma pesquisa quantitativa. Isto é, sujeitos, população, amostra, parâmetro e estatística.

* Os **sujeitos** são as entidades observadas em um estudo, podendo ser pessoas, famílias, escolas, cidades, empresas, entre outros. 
* A **população** é o conjunto completo de sujeitos de interesse em um estudo, enquanto a **amostra** é o subconjunto da população a partir do qual os dados são coletados. 
* O **parâmetro** é um resumo numérico da população, enquanto a **estatística** é um resumo numérico dos dados amostrais.

### Por que estudar estatística?
O estudo da estatística é extremamente importante para quaquer estudante de Ciências Sociais e Humanas. Sim, digo isso mesmo para aqueles que escolheram essa área porquê não queriam ter que lidar com matemática e afins. Afinal, a estatística é uma ferramenta de grande potencial para contribuir com o conhecimento e atender as demandas profissionais. Você vai encontrar dados estatísticos em publicações acadêmicas, relatórios governamentais e organizacionais etc. 

Sobre a parte acadêmica, foco deste material, faço aqui uma pergunta complementar: quem nunca se incomodou em ler uma publicação e ter que pular a parte das tabelas de resultados porquê parecia uma língua estrangeira? O *mainstream* do conhecimento científico ainda se baseia em pesquisas quantitativas. Os principais periódicos são recheados de modelagens e testes comparativos de variáveis. Logo, se você quer ser pesquisador e, com o perdão da redundância, resolver problemas de pesquisa, ter pelo menos um conhecimento básico de estatística é fundamental.  

Exemplos, que andam lado a lado com a aplicação prática, são: formulação e avaliação de políticas públicas, impactos ações governamentais, de uma campanha de marketing, comunicações organizacionais, fatores que afetam as crenças políticas, grau de satisfação com o sistema educacional, decisões sobre quando se aposentar etc. Ou seja, já deu para perceber que, quando bem analisados, os dados podem fornecer informações valiosas sobre a relação entre o que chamamos de variáveis. É possível, por exemplo, estudar se determinado estrato da população avaliar melhor ou pior a qualidade dos serviços de saúde pública, baseando-se em uma medida quantitativa como a média. Portanto, o estudo da estatística pode ajudar a compreender os fenômenos de interesse e a tomar decisões baseadas em evidências.

Por fim, deixo aqui também a reflexão sobre quem já fez esse tipo de questionamento: "por que devo aprender estatística se é mais fácil contratar alguém para fazer a análise de dados por mim?". Ora, se você pensa ou já pensou assim, aqui sugiro que você tente mudar isso. Afinal, delegar ou terceirar essa etapa é extremamente arriscado. Já presenciei estudantes se complicando quando avaliadores, em banca de mestrado e doutorado, que entendiam de uma determinada técnica que foi aplicada no trabalho, questionando elementos básicos, mas não obtendo as respostas esperadas. Ou seja, identificando, claramente, que uma importante etapa foi colocada sob a resposabilidade de outra pessoa. 

Lembre-se, um estatístico vai saber rodar qualquer teste que você solicite. Todavia, como comento na próxima questão, é você o responsável pelo trabalho e, consequentemente, pelas conclusões e relação com a teoria subjacente do seu tema de pesquisa. Acredite, quando você compreende o que está utilizando, a estatística vai se tornar prazerosa e te trazer confiança. 

### Preciso ser um matemático para aprender estatística e aplicá-la em minhas pesquisas?
A resposta aqui é um óbvio não. Todavia, isto não significa que não seja importante ter conhecimento sobre o que está subjacente à técnica que estamos utilizando. Ou seja, utilizando uma analogia, quando vamos tirar nossa carteira de motorista, nosso treinamento envolve a parte teórica e a parte prática. A primeira é importante para não cometermos escolhas equivocadas ao dirigir, como por exemplo, trafegar na contramão quando há uma placa indicativa sobre essa proibição. A segunda é necessária para podermos, efetivamente, utilizar o veículo. Logo, conhecer o que chamamos de mecânica dos testes estatísticos e, sua consequente álgebra operacional, é importante para não utilizarmos um teste quando não o deveríamos. Afinal, quando a premissa não está correta, vamos ter conclusões enviesadas. 

Como já disse, não se assuste ou ache que precisa ser um especialista em matemática. A verdade é que a maior parte dos motoristas não sabe como desmontar um motor, por exemplo. Ainda assim, são capazes de serem excelentes condutores. Logo, nós, enquanto pesquisadores da área de Ciências Sociais e Humanas, precisamos saber quando utilizar uma técnica e como operar um programa para auxiliar a implementá-la. Isto é, o cálculo e operacionalização são realizados pelos programas estatísticos e não por você no seu caderno. 

É necessário compreender, no entanto, que a estatística requer um conjunto de competências essenciais para ser adequadamente aplicada, especialmente em Ciências Sociais Aplicadas e Humanas. Dentre elas, destacam-se: os fundamentos de matemática, a teoria estatística, os fundamentos de computação e o conteúdo substantivo especializado. Este último, arrisco dizer, é o mais importante e, talvez, o mais negligenciado. No afã de utilizar uma técnica, o pesquisador pode se esquecer que a discussão dos resultados com a teoria é o que mais importa.

Dito de outra forma, o problema do pesquisador quantitativo de software é comum, no qual o usuário sabe apertar os botões e analisar tudo o que o software gera, mas não sabe calcular uma média. Apenas saber como usar o software estatístico não garante uma análise apropriada, sendo vital entender o método antes de usá-lo e, principalmente, a teoria do campo de conhecimento da sua pesquisa. Logo, é comum também a aplicação de métodos inapropriados. Consequentemente, análises incorretas ocorrem quando os pesquisadores não tomam tempo suficiente para entender o método estatístico, as suposições para o seu uso ou a sua adequabilidade para um problema específico. Você precisa entender qual método selecionar, quais opções escolher daquele método e como tirar conclusões válidas do resultado.

Aqui, deixo registrado três recomendações importantes (Sharpe *et al.*, 2011):

- Faça um planejamento da sua pesquisa sempre. Isto é, para onde vou e por quê.
- Estatística não tem a ver apenas com o fazer. Realizar cálculos e exibir gráficos são parte do trabalho, mas, você pode deixar isso para os programas. Concentre--se em interpretar os resultados.
- Faça o exercício de relatar o que aprendeu, de modo que outra pessoa possa entender o seu trabalho. Até que isso aconteça, seu trabalho deve continuar.

### Qual programa devo utilizar para analisar meus dados?
A resposta a essa questão é: depende. Com o avanço da capacidade computacional e desenvolvimento de programas, temos uma vasta gama de opções para escolher. Logo, vou tentar desenvolver a resposta começando com outra pergunta: qual o seu objetivo como pesquisador quantitativo? 

Se for aprender e realizar análises mais elementares, como descrição de dados, testes de comparação de médias ou até regressão com estimações mais tradicionais, voce pode utilizar editores de planilha (*e.g.* libreoffice calc, google planilhas, microsoft excel etc.) ou programas estatísticos com interface gráfica amigável (*e.g.* jamovi, jasp, PSPP etc.). A vantagem desses programas é sua curva de aprendizado mais rápida, não requerendo, por exemplo, conhecimentos mais avançados ou mesmo noção de lógica de programação.

Agora, se você quer se enveredar por análises mais complexas, sem as limitações do que já está implementados nos programas citados, o R é a escolha mais natural disponível. Aqui não existe se é possível realizar, mas, sim, como implementar. Essa linguagem e seus desdobramentos em aplicativos, tem sido largamente utilizada por cientistas de dados. Seu potencial de automação e de análise é, praticamente, ilimitado. 

Todavia, aqui cabe a ressalva de que há uma curva de aprendizagem maior. Você vai, necessariamente, ter que dedicar um tempo para se habituar a lógica de programação, o que pode assustar em um primeiro momento. Aliado a ansiedade já comentada que os métodos quantitativos carregam, isso pode tornar o aprendizado ainda mais demorada, na minha percepção e experiência. Algumas soluções podem auxiliar na utilização do R, a exemplo do R Studio e do RKWard.

Do meu ponto de vista pedagógico, no campo de Ciências Sociais e Humanas, considerando o contexto formativo dos estudantes, acredito que iniciar o conhecimento por programas com interfaces gráficas mais amigáveis é mais produtivo. Ou seja, para quebrar resistências, programas como o Jamovi e o Jasp são bastante interessantes. Daí, a depender do interesse do estudante, ele pode continuar sua jornada formativa com cursos adicionais e, se enveredar pelo R, caso tenha necessidade e o queira. Particularmente, utilizo o Jamovi na disciplina de Métodos Quantitativos Aplicados, recebendo excelente retorno e facilidade na condução da aula.

Gostaria de comentar, para finalizar, que eu advogo pelo *software livre*. Ou seja, existem ótimas opções proprietárias, como o Minitab, SPSS, Microsoft Excel etc. Todavia, acredito que a utilização desses programas só devem ser realizadas se o estudante tiver a licença, que não costuma ser barata. No passado, com a menor quantidade de opções livres, seria mais tolerável usar opções alternativas, o que é diferente da situação atual. 

``` 
Vídeo sobre qual programa utilizar
https://youtu.be/Rzd7bIKkOAg
```

**** Lista de programas estatísticos recomendados
- Jamovi: https://www.jamovi.org/
- Jasp: https://jasp-stats.org/
- PSPP: https://www.gnu.org/software/pspp/
- RKWard: https://rkward.kde.org/
- R Studio: https://posit.co
- R: https://cran.r-project.org/

⬆️[Sumário](#sumário)

3. 📖 [Delineamento](#Delineamento)
   3.1. 📖 [Mensuração e Escalas](#Mensuração e Escalas)