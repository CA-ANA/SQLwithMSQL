# SQLwithMSQL
<p><b>História do SQL</b></p>

A linguagem SQL foi desenvolvida no começo dos anos 70, na cidade de São José, Califórnia, em um projeto chamado System R da IBM, do inglês International Business Machines, cujo objetivo era comprovar a viabilidade da implementação de um modelo relacional, que um estudioso chamado Codd estava propondo.

Esse estudioso <b>elaborou uma forma estruturada de realizar consultas nos bancos de dados que estavam surgindo</b>, chamados <b><i>“bancos de dados relacionais”.</b></i>

Com o <b>surgimento</b> dos bancos de dados relacionais <i>(ou DBMS, do inglês, Data Base Management System, “Sistema de Gerenciamento de Banco de Dados")</i>, Codd considerou criar uma linguagem que <b>facilitasse</b> a extração e manipulação de dados, além da manipulação das estruturas desse banco aproveitando a característica de relacionamento entre eles.

Porém, não era apenas a IBM que estava trabalhando com os novos bancos de dados relacionais. Por volta dos anos 80, a Oracle, dentre outras empresas, também estava buscando maneiras mais fáceis de manipular essas novas estruturas.

Mais para o final dos anos 80 e início dos 90, o órgão americano, o <b>ANSI</b> (da sigla <i>American National Standard Institute</i>), estabeleceu alguns <b>padrões</b> para as consultas dos bancos de dados relacionais.

Então, foi criada a <b>linguagem SQL</b>, do inglês <i>Structured English Query Language</i>, que traduzindo seria algo como “linguagem de consulta estruturada em inglês”. 

O <b>principal objetivo da linguagem SQL </b>é padronizar a maneira como os registros são consultados nos bancos de dados relacionais. Atualmente, os bancos relacionais aderem ao padrão SQL, que vai além das consultas: é usado também, na criação, alteração, estruturação e manipulação do banco de dados, além da maneira como banco de dados interage com a segurança, entre outros usos.

Entre as <b>vantagens do banco de dados relacional</b>, a primeira é que essa <b>padronização</b> utilizando a linguagem SQL tem um custo reduzido do aprendizado. Por exemplo, o profissional com conhecimento sobre o SQL da Oracle conseguirá manipular facilmente o MySQL ou SQL Server da Microsoft. Por mais que existam diferenças - principalmente na parte de funções -, a adaptação do profissional não é uma questão complicada.

Outra vantagem, é a <b>portabilidade</b>. Por exemplo, é mais simples migrar sistemas que usam Oracle para SQL Server ou para MySQL, ou vice-versa. Lembrando que quanto mais for utilizado o <b>SQL Standard </b>definido pelo ANSI, mais fácil será essa portabilidade no futuro. Então, é útil evitar as funções específicas do banco de dados e permitir que o programa realize essa tarefa.

Já a <b>longevidade</b> é a garantia de que os seus relatórios ou processos utilizando o SQL irão funcionar por um longo período, já que estarão sempre adaptados ao padrão ANSI. Ou seja, ao efetuar um upgrade de banco de dados o seu sistema não ficará fora de serviço.

Outro benefício é a <b>comunicação</b>. O fato da maioria utilizar SQL permite a facilidade de comunicação entre os sistemas. Como, por exemplo, processos de ETL, (extract, transform and load), ou de integração entre sistemas que ficam mais simples de serem desenvolvidos, já que ambos utilizam o SQL padrão.

Por último temos a <b>liberdade de escolha</b>. Por existir um padrão de linguagem, se a empresa for optar pelo uso de um banco de dados relacional não ficará presa à linguagem de comunicação, por exemplo, já que são bem semelhantes. Ao tomar essa decisão, a corporação irá utilizar outros critérios de escolha, como performance, hardware, custo, entre outros.

Contudo, essa padronização não possui apenas vantagens, há algumas <b>desvantagens</b> - ainda que poucas. A primeira é a <b>privação da criatividade</b>. O SQL possui limitações que podem não atender às novas demandas no mercado na linguagem SQL, principalmente com o surgimento das redes sociais e dos enormes volumes de dados, o chamado <b>big data</b>. Ou seja, há uma carência nas coletas de dados que estão trafegando na internet.

Para tal, estão surgindo outros bancos que usam padrões diferentes dos bancos de dados relacionais, o chamado <b>NoSQL</b>. Estes atendem de forma mais eficiente as demandas de tabelas de big data , como no caso das redes sociais. Lembrando que estamos nos referindo a estruturas que <b>escapam do padrão ANSI</b> e que, por isso, exigem um aprendizado mais específico.

Outro ponto é a <b>escassez</b> de estruturação da linguagem SQL, já que ela não possui <b>if, for e when</b>, isto é, comandos condicionais como as demais linguagens de programação.

Para conseguir suprir essa carência da estruturação, os bancos de dados relacionais da Oracle, SQL e MySQL criaram suas <b>linguagens próprias</b> internas que realizam esse conjunto de estruturação usando a linguagem SQL, mas que acaba se afastando um pouco do padrão ANSI.

Falando um pouco sobre o padrão ANSI, este possui <b>três grupos de comandos</b>. O primeiro, é o <b>DDLs</b>, ou <i>Data Definition Language</i> (linguagem de definição de dados). Os DDLs são a parte da linguagem SQL que <b>permite a manipulação das estruturas do banco de dados</b>. Como, por exemplo, criar um banco, tabelas, índices, apagar as tabelas e alterar a política de crescimento de índice. Ou seja, os comandos que envolvem a estrutura do banco de dados relacionais são os comandos do tipo DDL.

O segundo grupo de comandos são os chamados <b>DML</b>, ou <i>Data Manipulation Language</i> (linguagem de manipulação de dados). Esse grupo visa <b>gerenciar os dados</b>: incluindo, alterando e excluindo informações nas estruturas do banco, como as tabelas. Além disso, realizam as consultas, buscam as informações das estruturas e exibem para o usuário.

Finalmente, chegamos nos comandos <b>DCL</b>, ou <i>Data Control Language</i> ("linguagem de controle de dados"). Este grupo nos permite <b>administrar o banco de dados</b> como, por exemplo, o controle de acesso, o gerenciamento do usuário, gerenciar o que cada usuário(a) pode ou não visualizar, gerenciar o banco ao nível de estrutura (como a política de crescimento, como e onde será armazenado no disco), administrar os processos, saber quantos processos estão sendo executados, controle de log e assim por diante.
