<h1 align="center">
  <br>
  <img src="imagens/bancodedados.png" alt="Imagem de um banco de dados" width="500">
  <br>
    <br>
    <p align="center"> Semana 12 - Banco de Dados <p>
</h1>


<h2> O que é um Banco de dados? </h2>

Bancos de dados ou bases de dados são conjuntos de arquivos relacionados entre si com registros sobre pessoas, lugares ou coisas. São coleções organizadas de dados que se relacionam de forma a criar algum sentido e dar mais eficiência durante uma pesquisa ou estudo cientifico.



<h2> Quais são os principais bancos de dados e suas diferenças? </h2>

Antes de explicar os tipos de bancos de dados disponíveis, é necessário definir suas duas categorias: banco de dados relacionais e não relacionais.

Bancos de dados relacionais são fundamentados no paradigma da orientação a conjuntos. Seus dados são armazenados em estruturas denominadas tabelas. Cada tabela é composta por colunas (atributos e linhas), tuplas ou registros.

Eles costumam ser mais utilizados para dados tabulares, de fácil inserção e recuperação. Sua linguagem é o SQL (Structured Query Language) e seus principais representantes são <i> <b> Oracle, SQL Server, MySQL e PostgreSQL </i> </b>.

Os bancos relacionais são a opção ideal para sistemas ERP, CRM ou de gerenciamento financeiro, em que é necessária uma grande consistência de dados. Criado em 1970 por Edgar Frank Codd, esse modelo é o sucessor dos modelos hierárquico e em rede.

Já os bancos de dados não relacionais são soluções para situações nas quais os bancos relacionais não atendem. Um exemplo são os ambientes com dados mistos (imagens, mapas e tabelas), que não podem ser tabulados em linhas e colunas. Também é utilizado em grandes soluções baseadas em nuvem.

Eles são conhecidos como NoSQL (Not Only SQL, ou em português, não apenas SQL). Buscam consistência nas informações armazenadas, disponibilidade do banco de dados e tolerância ao particionamento das informações. Seus bancos mais conhecidos são <i> <b> MongoDB, Redis e Cassandra </i> </b>.

A escolha do banco de dados ideal depende primordialmente de sua aplicação .



<h1 align="center">
  <br>
  <img src="imagens/mongodb.png" alt="mulher negra usando computador" width="250">
  <br>
    <br>
    <p align="center"> MongoDB <p>
</h1>


MongoDB é um dos bancos de dados NoSQL mais utilizados, open source e se encontra disponível para Windows, Linux e OSX. Seu lançamento ocorreu em fevereiro de 2009 pela empresa 10gen, e sua linguagem de programação é o C++, o que garante ótima performance.

É orientado a documentos (document database) no formato JSON. Isso significa que não apresenta como restrição a necessidade de ter tabelas e colunas criadas previamente, o que permite que um documento represente toda a informação necessária no formato de um JSON.

MongoDB foi criada com Big Data em mente, e suporta escalonamento horizontal ou vertical. Usa replica sets, que são instâncias espelhadas e sharding (ou dados distribuídos), o que o torna uma excelente opção para grandes volumes de dados.

<h1> <p align ="center"> Alguns comandos utilizados no  MongoDB <p> </h1> 


<h3><i><ul> 
<li> Criar um banco de dados - USE NOME DO BANCO DE DADOS</li>
<li> Exibir os banco de dados existentes - SHOW DBS </li>
<li> Criar uma coleção - DB.CRAETECOLLECTION('NOME-DA-COLLECTION')</li>
<li> Remover banco de dados atual - DB.DROPDATABASE()</li>
<li> Listar todas as Collections - SHOW COLLECTIONS </li>
<li> Buscar todos os registros de uma Collection - DB.NOMEDACOLLECTION.FIND()</li>
<li> Trazer o retorno de uma forma mais amigavel - DB.NOMEDACOLLECTION.FIND().PRETTY()</li>
<li> Incluir vários registros de uma unica vez - DB.NOMEDACOLLECTION.INSERTMANY ( [ {" OBEJTO A SER INSERIDO"} ] )</li>






