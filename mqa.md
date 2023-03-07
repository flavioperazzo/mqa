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

Por essa razão, seguimos aqui a mesma lógica, no intuito de diminuir resistências desde agora. Para tanto, vamos tentar responder algumas questões iniciais, para introduzir o conteúdo aqui proposto. Para iniciar, vamos refletir sobre alguns questionamentos.

### O que é estatística?

Segundo Agresti e Finlay (2012), a estatística é um conjunto de métodos utilizados para obter e analisar dados em estudos de pesquisa quantitativa. Podemos esquematizá-la em torno de três dimensões: delineamento, descrição e inferência. Essa é a forma típica em que o conteúdo é apresentado em livros acadêmicos. Em geral, para todas elas, é preciso planejamento e, posteriormente, execução.

> O **delineamento** da pesquisa diz respeito a como os dados serão coletados, envolvendo a escolha de sujeitos e instrumentos. 

> A **descrição** dos dados é feita por meio de gráficos, tabelas e resumos numéricos. 

> A **inferência** é o processo de fazer previsões com base nos dados coletados, utilizando testes de hipóteses.

Para além dessas definições, é importante também entender a diferença entre alguns termos clássicos, sempre necessários para se pensar na execução de uma pesquisa quantitativa. Isto é, sujeitos, população, amostra, parâmetro e estatística.

> Os **sujeitos** são as entidades observadas em um estudo, podendo ser pessoas, famílias, escolas, cidades, empresas, entre outros. 

> A **população** é o conjunto completo de sujeitos de interesse em um estudo, enquanto a **amostra** é o subconjunto da população a partir do qual os dados são coletados. 

> O **parâmetro** é um resumo numérico da população, enquanto a **estatística** é um resumo numérico dos dados amostrais.

### Qual a origem da estatística?


### Por que estudar estatística?
### Preciso ser um matemático para aprender estatística e aplicá-la em minhas pesquisas?


⬆️[Sumário](#sumário)