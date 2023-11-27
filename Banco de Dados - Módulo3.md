<sub> 📂Curso Vem Ser Tech Dados - Ada Tech Turma 1102 </sub>

# 💻 Banco de Dados - Módulo 3 

<details>
<summary>Introdução</summary>

---
Bancos de dados são uma das tecnologias mais importantes do mundo moderno. Eles são amplamente utilizados para armazenar, gerenciar e recuperar grandes quantidades de informações de maneira eficiente e segura. Um banco de dados é um sistema organizado de informações que pode ser acessado, gerenciado e atualizado de maneira conveniente. Em termos simples, um banco de dados é um armário gigante que armazena informações sobre tudo, desde os nomes de clientes até informações de produtos, registros financeiros e muito mais.

Os bancos de dados são usados em uma ampla variedade de aplicações, desde simples aplicativos de desktop até sistemas de gerenciamento de grandes empresas e organizações governamentais. Eles permitem que as informações sejam armazenadas e acessadas rapidamente e de maneira confiável, tornando-os uma parte vital de muitos sistemas de tecnologia da informação.

## 📌 Utilidade de um banco de dados

Um banco de dados é como um grande armário de arquivos, mas em vez de papel, ele armazena informações digitais. Ele é projetado para armazenar e gerenciar grandes quantidades de dados de maneira organizada e eficiente. Assim como um armário de arquivos é útil para manter documentos organizados e fáceis de encontrar, um banco de dados é útil para armazenar e acessar informações de maneira rápida e eficiente.

Imagine que você tem uma loja on-line que vende roupas. Você precisa gerenciar informações sobre seus produtos, clientes, pedidos, pagamentos e estoques. Você pode armazenar essas informações em planilhas, arquivos de texto ou até mesmo em papel. No entanto, conforme sua loja cresce, gerenciar essas informações manualmente pode se tornar cada vez mais difícil e demorado.

Aqui é onde um banco de dados pode ser útil. Com um banco de dados, você pode armazenar todas essas informações em uma única fonte confiável e organizada. Você pode facilmente acessar e atualizar informações sobre seus produtos, clientes e pedidos em tempo real, em vez de ter que procurar em vários arquivos ou documentos. Você pode gerar relatórios e análises para ajudar a entender melhor seu negócio e tomar decisões informadas com base nos dados.

Outra analogia que pode ajudar a entender a utilidade de um banco de dados é um catálogo de biblioteca. Imagine que você é o bibliotecário de uma grande biblioteca e precisa gerenciar informações sobre todos os livros em sua coleção. Você pode armazenar essas informações em fichas de papel em uma caixa de arquivo. No entanto, à medida que a biblioteca cresce, gerenciar essas informações manualmente pode se tornar cada vez mais difícil e demorado.

Novamente, com um banco de dados, você pode armazenar informações sobre todos os livros em sua coleção em uma única fonte confiável e organizada. Você pode facilmente acessar e atualizar informações sobre títulos, autores, editoras e categorias em tempo real. Você pode gerar relatórios para ajudar a entender melhor a coleção da biblioteca e até fazer recomendações aos usuários com base nos dados.

## 📌 Mais sobre o PostgreSQL

O PostgreSQL é um sistema de gerenciamento de banco de dados relacional de código aberto que foi lançado pela primeira vez em 1989. Ele foi criado como um projeto de pesquisa na Universidade da Califórnia em Berkeley, nos Estados Unidos, e desde então tem sido amplamente adotado por empresas e organizações em todo o mundo.

O PostgreSQL é conhecido por sua confiabilidade, escalabilidade e desempenho. Ele foi projetado para suportar cargas de trabalho pesadas e é altamente personalizável, permitindo que os usuários ajustem o sistema de acordo com suas necessidades específicas. Além disso, ele é altamente compatível com padrões do setor e oferece suporte a muitos recursos avançados, como transações ACID, índices em texto completo, integridade referencial e muito mais. Ele é uma das ferramentas de banco de dados mais populares do mercado, oferecendo recursos avançados de segurança, confiabilidade e escalabilidade.

Uma das principais características do PostgreSQL é sua capacidade de suportar objetos complexos, como arrays, JSON, XML e geometrias espaciais. Ele também oferece suporte a muitos tipos de dados diferentes, incluindo números, datas, strings e muito mais. Isso o torna uma escolha popular para aplicativos que envolvem muitos dados complexos e variados.

Outra característica notável do PostgreSQL é sua capacidade de ser estendido por meio de módulos adicionais, conhecidos como extensões. Essas extensões permitem que os usuários adicionem novos recursos e funcionalidades ao sistema sem precisar modificar o código-fonte principal. Isso torna o PostgreSQL altamente personalizável e adaptável a uma ampla variedade de casos de uso.

Muitas grandes empresas confiam no PostgreSQL para armazenar seus dados críticos. Aqui estão alguns exemplos de empresas que utilizam essa tecnologia:

- Apple: a Apple usa o PostgreSQL para gerenciar dados do iTunes, App Store e Apple Music.

- Cisco: a Cisco usa o PostgreSQL como banco de dados principal para sua plataforma de gerenciamento de rede.

- Fujitsu: a Fujitsu usa o PostgreSQL como banco de dados principal para seus sistemas de gerenciamento de inventário.

- Skype: o Skype usa o PostgreSQL para armazenar dados de bate-papo e histórico de chamadas.

- Reddit: o Reddit usa o PostgreSQL para armazenar dados de usuários, postagens e comentários.

## Referências e materiais complementares
- PostgreSQL: https://www.postgresql.org/about/

---

</details>

<details>
<summary>Tipos de Bancos de Dados</summary>

---

Existem dois tipos principais de bancos de dados: bancos relacionais e bancos não relacionais.

Os bancos de dados relacionais são baseados em uma estrutura de tabelas inter-relacionadas. Os dados são organizados em tabelas, cada uma com uma coluna para um tipo específico de dado e cada linha contendo uma entrada individual. As tabelas são inter-relacionadas por meio de chaves primárias e estrangeiras, que são usadas para vincular os dados em diferentes tabelas. O SQL (Structured Query Language) é a linguagem de programação mais comumente usada para manipular bancos de dados relacionais.

Por outro lado, os bancos de dados não relacionais são projetados para armazenar dados sem a estrutura rígida de tabelas e esquemas relacionais. Eles são mais flexíveis em termos de como os dados são organizados e podem ser mais escaláveis e tolerantes a falhas do que os bancos de dados relacionais. Eles também podem ser usados para armazenar tipos de dados mais complexos, como documentos, gráficos e dados de séries temporais. Exemplos de bancos de dados não relacionais incluem bancos de dados de documentos, bancos de dados de grafos e bancos de dados de séries temporais.

A principal diferença entre bancos de dados relacionais e não relacionais é a forma como os dados são estruturados e organizados. Os bancos de dados relacionais têm uma estrutura de tabelas rígida, com colunas e linhas organizadas em uma grade, enquanto os bancos de dados não relacionais têm uma estrutura mais flexível, com dados armazenados em uma hierarquia de documentos ou grafos.

Outra diferença importante é a maneira como os dados são consultados e manipulados. Os bancos de dados relacionais usam SQL para consultar e manipular dados, enquanto os bancos de dados não relacionais geralmente usam uma API baseada em objetos ou documentos para manipular dados.

Ambos os tipos de bancos de dados têm suas próprias vantagens e desvantagens, e a escolha entre um banco de dados relacional ou não relacional dependerá das necessidades e requisitos específicos do projeto. Os bancos de dados relacionais são mais adequados para projetos com estruturas de dados rígidas e requisitos de transação, enquanto os bancos de dados não relacionais são mais adequados para projetos que precisam armazenar dados não estruturados ou semiestruturados e exigem escalabilidade e flexibilidade.

## 📌 Principais diferenças

Banco de Dados Relacional (RDBMS): é o tipo mais comum de banco de dados, que usa uma estrutura de tabelas relacionais para armazenar dados. O modelo relacional é baseado em relações matemáticas entre as tabelas e é capaz de garantir a integridade dos dados através do uso de chaves primárias, chaves estrangeiras e restrições de integridade referencial. Exemplos de bancos de dados relacionais incluem PostgreSQL, MySQL, Oracle e SQL Server.

Banco de Dados de Colunas: neste tipo de banco de dados, os dados são armazenados em colunas em vez de linhas, como nos bancos de dados relacionais tradicionais. Isso permite que as consultas sejam executadas de forma mais rápida em grandes conjuntos de dados e melhora o desempenho de consultas analíticas. Exemplos de bancos de dados de colunas incluem o Apache Cassandra e o Apache HBase.

Banco de Dados de Documentos: neste tipo de banco de dados, os dados são armazenados em documentos individuais, como JSON ou XML. Cada documento contém todos os dados relacionados em um único registro e pode ser aninhado para criar uma estrutura hierárquica de dados. Exemplos de bancos de dados de documentos incluem o MongoDB e o Couchbase.

Banco de Dados de Grafos: neste tipo de banco de dados, os dados são armazenados em grafos, que consistem em nós e arestas. Os nós representam entidades e as arestas representam as conexões entre eles. Isso permite consultas sofisticadas que exploram as relações complexas entre os dados. Exemplos de bancos de dados de grafos incluem o Neo4j e o OrientDB.

Banco de Dados de Tempo Real (In-Memory): neste tipo de banco de dados, os dados são armazenados em memória RAM em vez de em disco. Isso permite um acesso muito rápido aos dados, tornando-o ideal para aplicativos que exigem baixa latência, como sistemas de negociação financeira, jogos online e processamento de dados em tempo real. Exemplos de bancos de dados de tempo real incluem o SAP HANA e o MemSQL.

## 📌 Exemplos de bancos de dados não relacionais

Como modelo de banco de dados, os bancos de dados NoSQL (Not Only SQL) têm como característica principal o fato de não utilizarem uma estrutura de tabelas relacionais como nos bancos de dados relacionais tradicionais, como o PostgreSQL. Em vez disso, os bancos de dados NoSQL são projetados para manipular grandes quantidades de dados não estruturados ou semiestruturados e trabalhar com escalabilidade horizontal em vários servidores.

Aqui estão alguns exemplos de bancos de dados NoSQL e suas principais características:

- DynamoDB: é um banco de dados de valor-chave totalmente gerenciado pela Amazon Web Services (AWS). Ele é projetado para alta disponibilidade, escalabilidade e desempenho, além de ser totalmente gerenciado. O DynamoDB é comumente usado para armazenar informações do usuário em aplicativos móveis e para gerenciar sessões de jogos online.

- Redis: é um banco de dados em memória de código aberto que permite armazenar dados em chave-valor, com suporte a diferentes tipos de dados, como strings, hashes, listas, conjuntos e sorted sets. O Redis é conhecido por sua velocidade e alta escalabilidade, sendo comumente usado para cache, filas de mensagens e gerenciamento de sessões.

- Cassandra: é um banco de dados distribuído de colunas amplamente usado em aplicativos com grande volume de dados, incluindo análise de dados, gerenciamento de registros, gerenciamento de conteúdo e gerenciamento de mídia social. O Cassandra tem alta escalabilidade horizontal e oferece recursos como replicação de dados em vários datacenters para garantir alta disponibilidade.

- MongoDB: é um banco de dados de documentos de código aberto que armazena dados em formato BSON (uma variação do formato JSON). O MongoDB é conhecido por sua escalabilidade horizontal, flexibilidade e velocidade, além de ser usado em aplicativos da web, de comércio eletrônico e de mídia social.

- Neo4j: é um banco de dados de grafo que permite modelar dados como nós e relacionamentos. Ele é frequentemente usado em aplicativos que envolvem redes sociais, análise de dados e sistemas de recomendação. O Neo4j é conhecido por sua capacidade de pesquisar relações complexas entre dados e sua escalabilidade horizontal.

- HBase: O Apache HBase é um banco de dados NoSQL distribuído, de colunas e baseado no Apache Hadoop. Ele é projetado para armazenar grandes quantidades de dados com alta velocidade de leitura e gravação, e suporta operações em tempo real e análise de dados em lote. O HBase é usado em vários casos de uso, como armazenamento de dados de sensores IoT (Internet das Coisas), análise de logs, processamento de eventos em tempo real e sistemas de recomendação. Ele é amplamente utilizado por empresas que precisam armazenar grandes quantidades de dados e executar análises em tempo real ou perto do tempo real.

### Referências e materiais complementares

- DynamoDB: https://aws.amazon.com/dynamodb/
- Redis: https://redis.io/
- Cassandra: https://cassandra.apache.org/
- MongoDB: https://www.mongodb.com/
- Neo4j: https://neo4j.com/
- Apache HBase: https://hbase.apache.org/

---

</details>

<details>
<summary>Instalação do PostgreSQL</summary>
  
---

## 📌 Instalação do PostgreSQL no Windows:

A maneira mais fácil de instalar o PostgreSQL no Windows é através do instalador disponível no site oficial.

- O link para download é: https://www.postgresql.org/download/windows/

Basta baixar o arquivo de instalação correspondente à versão desejada, executá-lo e seguir as instruções na tela. É importante lembrar que durante a instalação é possível selecionar os componentes que deseja instalar, como a ferramenta gráfica pgAdmin. Além disso, também é possível escolher o local de instalação e a senha do usuário admin. Após a instalação, o PostgreSQL estará pronto para uso.

Para mais informações sobre a instalação do PostgreSQL no Windows, consulte a documentação oficial disponível em: https://www.postgresql.org/docs/current/tutorial-install.html

## 📌 Instalação do PostgreSQL no Linux:
No Linux, a instalação do PostgreSQL varia de acordo com a distribuição Linux que está sendo utilizada. Para distribuições baseadas em Debian, como o Ubuntu, o PostgreSQL pode ser instalado usando o gerenciador de pacotes apt-get. Para isso, basta executar o seguinte comando no terminal:

```python
sudo apt-get install postgresql
```

Para outras distribuições Linux, é necessário verificar a documentação específica da distribuição para obter as instruções de instalação.

Após a instalação, é possível configurar o PostgreSQL utilizando o utilitário de linha de comando chamado psql. Para mais informações sobre a instalação do PostgreSQL no Linux, consulte a documentação 3 oficial disponível em: https://www.postgresql.org/download/linux/

## 📌 Instalação do PostgreSQL no Mac
No Mac, o PostgreSQL pode ser instalado usando o Homebrew, que é um gerenciador de pacotes para o macOS. Para instalar o PostgreSQL usando o Homebrew, basta executar o seguinte comando no terminal:

```python
brew install postgresql
```
Após a instalação, é possível configurar o PostgreSQL utilizando o utilitário de linha de comando chamado psql. Para mais informações sobre a instalação do PostgreSQL no Mac, consulte a documentação oficial disponível em: https://www.postgresql.org/download/macosx/

## 📌 Instalação do PostgreSQL utilizando Docker
O Docker é uma plataforma para desenvolvimento, distribuição e execução de aplicativos em contêineres. Com o Docker, é possível criar um ambiente isolado para executar o PostgreSQL.

Leia mais sobre docker em: https://docs.docker.com/

Para isso, basta executar o seguinte comando no terminal:

```python
docker run --name postgres -e POSTGRES_PASSWORD=<senha> -d postgres
```

Neste comando, substitua "" pela senha desejada para o usuário "postgres". Após a execução do comando, o PostgreSQL será iniciado em um contêiner Docker isolado. É possível conectar-se ao PostgreSQL dentro do contêiner usando o utilitário de linha de comando psql.

Para mais informações sobre o uso do PostgreSQL com o Docker, consulte a documentação oficial disponível em: https://hub.docker.com/_/postgres/

## 📌 Referências e materiais complementares
- Documentação: https://www.postgresql.org/docs/

---

</details>

<details>
<summary>DDL e DML</summary>
  
---

DDL significa Data Definition Language, que é uma linguagem utilizada para definir a estrutura e as características dos dados em um banco de dados. DDL é usado para criar, modificar e excluir objetos no banco de dados, como tabelas, índices, views e outros objetos.

Uma analogia para entender o DDL é compará-lo com a construção de uma casa. Assim como um arquiteto projeta a estrutura de uma casa, o DDL é usado para projetar a estrutura de um banco de dados. O arquiteto decide onde as paredes devem ser colocadas, quantos quartos a casa terá, como a cozinha será configurada, entre outras coisas. De maneira semelhante, o DDL determina a estrutura do banco de dados, como as tabelas que serão criadas, quais campos elas terão e como serão relacionadas entre si.

Já o DML significa Data Manipulation Language, que é uma linguagem usada para manipular os dados dentro de um banco de dados. DML é usado para inserir, atualizar, excluir e recuperar dados em um banco de dados. Isso significa que o DML é usado para fazer operações de leitura e escrita nos dados armazenados em um banco de dados.

Uma analogia para entender o DML é compará-lo com a manipulação de objetos em uma sala. Suponha que você queira mudar a posição de uma mesa em uma sala. Você pode movê-la para um novo local, atualizando a posição dela. Da mesma forma, com o DML, você pode atualizar dados em uma tabela para refletir mudanças na informação.

### Referências e materiais complementares
- https://www.postgresql.org/docs/current/ddl.html
- https://www.postgresql.org/docs/current/dml.html

---

</details>

<details>
<summary>Databases</summary>
---
  
Para criar ou remover um banco de dados no PostgreSQL, é necessário ter privilégios de superusuário ou de um usuário com permissões suficientes para criar ou remover um novo banco de dados.

## 📌 Inserindo bases de dados
Existem algumas maneiras de criar um banco de dados no PostgreSQL: através do utilitário de linha de comando createdb, através da interface gráfica do pgAdmin (ou qualquer outro SGDB que esteja utilizando) ou utilizando um comando SQL.

## Criando um banco de dados com o comando createdb
Antes de qualquer coisa, devemos nos conectar ao prompt, digitando no terminal o comando:

```python
sudo -i -u postgres psql
```
No exemplo acima, fizemos login com o usuário postgres ao prompt do PostgreSQL.

Para sair do prompt, basta digitarmos:
```python
\q
```
Para criar um banco de dados usando o createdb, basta executar o seguinte comando no terminal:

```python
createdb <nome_do_banco_de_dados>
```

Substitua <nome_do_banco_de_dados> pelo nome desejado para o banco de dados. Por exemplo:

```python
createdb meu_banco_bonito
```

Para visualizar a lista de bases de dados criadas, basta utilizarmos o comando:
```python
\l
```
## 📌 Criando um banco de dados utilizando linguagem SQL
O comando CREATE DATABASE é usado para criar um banco de dados no PostgreSQL. Ele pode ser executado tanto no utilitário de linha de comando psql quanto em outras ferramentas que suportam a execução de comandos SQL.

Para executar este comando, devemos estar com a janela de execução do SQL aberta, utilizando, por exemplo o pgAdmin.

O formato básico do comando é o seguinte:

```python
CREATE DATABASE nome_do_banco_de_dados;
```

Substitua `nome_do_banco_de_dados ` pelo nome desejado para o banco de dados. É possível especificar outras opções ao criar um banco de dados, como o proprietário do banco de dados, a codificação de caracteres e a localização do banco de dados. Algumas opções comuns incluem:

OWNER para definir o proprietário do banco de dados.
ENCODING para definir a codificação de caracteres do banco de dados.
LC_COLLATE e LC_CTYPE para definir as configurações de localização do banco de dados.
Por exemplo, o seguinte comando cria um banco de dados chamado "minha_base_de_dados" com o proprietário "meu_usuario" e codificação de caracteres "UTF8":

```python
CREATE DATABASE minha_base_de_dados
WITH    OWNER meu_usuario
        ENCODING 'UTF8'
        LC_COLLATE 'pt_BR.UTF-8'
        LC_CTYPE 'pt_BR.UTF-8';
```

Uma vez criado, o banco de dados pode ser acessado e gerenciado usando outros comandos SQL ou ferramentas de administração do PostgreSQL, como o pgAdmin.

É importante notar que a criação de um banco de dados requer permissões de superusuário ou de um usuário com permissões suficientes para criar um banco de dados. Se você não tem as permissões necessárias, você receberá uma mensagem de erro ao tentar criar o banco de dados.

Para mais informações sobre o comando CREATE DATABASE e outras opções disponíveis, consulte a documentação oficial do PostgreSQL.

## 📌 Removendo bases de dados
Para remover um banco de dados no PostgreSQL também podemos utilizar as mesmas formas da criação, via prompt, script SQL ou interface gráfica.

### Removendo um banco de dados com o comando dropdb
Para remover um banco de dados usando o dropdb, basta executar o seguinte comando no terminal:

```python
dropdb <nome_do_banco_de_dados>
```
Substitua `<nome_do_banco_de_dados>` pelo nome desejado para o banco de dados. Por exemplo:

```python
dropdb meu_banco_bonito
```
## 📌 Removendo um banco de dados utilizando linguagem SQL
Para remover um banco de dados existente utilizando linguagem SQL, basta executar o comando:

```python
DROP DATABASE nome_do_banco_de_dados;
```
Além disso, podemos adicionar o parâmetro IF EXISTS, ele funciona como um validador para quando o banco de dados mencionado não existir, o PostgreSQL somente ignorar ao invés de retornar um erro.

```python
DROP DATABASE IF EXISTS meu_banco_bonito;
```
### Referências e materiais complementares
- https://www.postgresql.org/docs/current/app-createdb.html

- https://www.postgresql.org/docs/current/sql-createdatabase.html

- https://www.postgresql.org/docs/current/app-dropdb.html

- https://www.postgresql.org/docs/current/sql-dropdatabase.html

---

</details>

<details>
<summary>Tabelas</summary>

---

## 📌 Criação de tabelas
Para criar uma tabela no PostgreSQL, você precisa usar a linguagem DDL (Data Definition Language) e a sintaxe é a seguinte:

```python
CREATE TABLE nome_da_tabela (
  nome_do_campo1 tipo_do_campo1,
  nome_do_campo2 tipo_do_campo2,
  ...,
  nome_do_campoN tipo_do_campoN
);
```
Por exemplo, para criar uma tabela chamada "clientes" com dois campos, "id" e "nome", o comando seria o seguinte:

```python
CREATE TABLE clientes (
  id SERIAL PRIMARY KEY,
  nome VARCHAR(50)
);

```
Este comando cria uma tabela "clientes" com um campo "id" que é um número serial (ou seja, um número sequencial gerado automaticamente pelo PostgreSQL) e um campo "nome" que é uma string de até 50 caracteres.

Não se preocupe com o "PRIMARY KEY" ainda, isso será abordado nos próximos capítulos.

## 📌 Edição de tabelas
Para editar uma tabela existente no PostgreSQL, você pode usar o comando ALTER TABLE. Por exemplo, se você quiser adicionar um novo campo "email" à tabela "clientes", o comando seria o seguinte:

```python
ALTER TABLE clientes ADD COLUMN email VARCHAR(50);
```
Este comando adiciona um novo campo chamado "email" à tabela "clientes" com um comprimento máximo de 50 caracteres.

## 📌 Exclusão de tabelas
Finalmente, para excluir uma tabela no PostgreSQL, você pode usar o comando DROP TABLE. Por exemplo, se você quiser excluir a tabela "clientes", o comando seria o seguinte:

```python
DROP TABLE clientes;
```
Este comando exclui a tabela "clientes" e todos os dados armazenados nela.

É importante notar que a exclusão de uma tabela é uma operação permanente e irrevogável. Portanto, sempre se certifique de ter feito um backup dos dados importantes antes de executar um comando DROP TABLE.

## 📌 Tipos de dados mais comuns
Nos exemplos acima, falamos dos tipos int e varchar, porém, existem alguns outros tipos de dados que são possíveis de serem utilizados, que nos auxiliam para situações específicas.

### Tipos numéricos:
- INTEGER: armazena números inteiros com sinal. O tamanho padrão é de 4 bytes, mas pode ser especificado um tamanho maior ou menor. É usado para armazenar dados numéricos que representam quantidades inteiras, como a quantidade de itens em um pedido.

- BIGINT: armazena números inteiros com sinal de 8 bytes. É usado para armazenar dados numéricos que representam quantidades maiores que o INTEGER, como o número de habitantes de uma cidade ou país.

- NUMERIC: armazena números decimais com precisão arbitrária. É usado para armazenar valores monetários ou outros dados numéricos que requerem alta precisão.

- DOUBLE PRECISION: armazena números de ponto flutuante de dupla precisão. É usado para armazenar dados numéricos que requerem alta precisão e uma grande faixa de valores, como as coordenadas geográficas de um local.

### Tipos de texto
- VARCHAR: armazena strings de comprimento variável. É usado para armazenar dados de texto de comprimento variável, como nomes de pessoas ou endereços de e-mail.

- CHAR: armazena strings de comprimento fixo. É usado para armazenar dados de texto de comprimento fixo, como códigos postais ou números de identificação.

- TEXT: armazena strings de comprimento variável sem limite. É usado para armazenar grandes volumes de dados de texto, como descrições de produtos ou comentários em um site.

É comum a utilização do tipo `varchar` na maioria dos casos, pois geralmente campos de tamanhos variados são armazenados como texto. O `varchar` armazena apenas os caracteres salvos, e deixa o resto do espaço vazio e disponível para outro dado.

Por exemplo: uma coluna do tipo `varchar(50)` que recebe o texto: 'Ada tecnologia', utiliza apenas 14 "espaços" na memória, e deixa os outros 36 disponíveis para outros registros. Ele ocupa menos espaço em memória, porém, em operações de atualização é penalizado, pois o banco de dados precisa "procurar" outro espaço em memória para realocar o conteúdo caso seja maior.

Já uma coluna do tipo `char(50)` que recebe o mesmo texto: 'Ada tecnologia', utiliza todos os 50 "espaços" disponíveis, portanto, ocupa mais espaço em memória. Em contrapartida, as operações de atualização são extremamente rápidas, pois a coluna já tem todo o espaço disponível "reservado" para ela.

### Tipos de data e hora
- DATE: armazena datas (ano, mês, dia). É usado para armazenar informações de datas, como datas de nascimento ou datas de eventos.

- TIME: armazena horas do dia. É usado para armazenar informações de hora, como horários de início ou fim de eventos.

- TIMESTAMP: armazena datas e horas com precisão de milissegundos. É usado para armazenar informações de datas e horas precisas, como timestamps de criação ou modificação de registros.

### Tipos booleanos
- BOOLEAN: armazena valores verdadeiro ou falso. É usado para armazenar dados booleanos, como se um usuário está conectado ou desconectado.
Tipos de array
- ARRAY: armazena uma lista de valores de um tipo de dado específico. É usado para armazenar coleções de dados, como uma lista de itens em um pedido ou as cores favoritas de um usuário.

### Tipos especiais
- JSON e JSONB: armazena dados em formato JSON (JavaScript Object Notation), usado para armazenar dados semiestruturados que podem ser facilmente lidos por outras aplicações ou sistemas.

- UUID: armazena identificadores únicos universais (UUIDs), que são frequentemente usados em sistemas distribuídos para identificar de forma única recursos em um cluster.

Você pode ver todos os tipos disponíveis para utilização no PostgreSQL em: https://www.postgresql.org/docs/current/datatype.html

## 📌 Default values
Em PostgreSQL, um valor padrão (ou "default value") é um valor que é automaticamente atribuído a uma coluna se nenhum valor é especificado para ela durante a inserção de dados.

Por exemplo, vamos supor que você tem uma tabela "clientes" com as colunas "id", "nome", "email" e "data de cadastro". Você pode definir um valor padrão para a coluna "data de cadastro" para que, quando um novo registro for adicionado à tabela, a data atual seja automaticamente inserida para essa coluna. Isso pode ser útil, pois evita a necessidade de inserir manualmente a data a cada vez que um novo registro é adicionado.

Aqui está um exemplo de como definir um valor padrão em PostgreSQL:

```python
CREATE TABLE clientes (
    id SERIAL PRIMARY KEY,
    nome VARCHAR(100),
    email VARCHAR(100),
    data_de_cadastro TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```
Neste exemplo, a coluna "data_de_cadastro" é definida com um valor padrão de "CURRENT_TIMESTAMP", que é uma função que retorna a data e hora atual do sistema. Isso significa que, se nenhum valor for especificado para essa coluna durante a inserção de dados, o PostgreSQL irá automaticamente inserir a data e hora atual.

Outro exemplo pode ser de uma tabela de pedidos, onde a coluna "status" pode ter um valor padrão "pendente" para todos os novos pedidos:

```python
CREATE TABLE pedidos (
    id SERIAL PRIMARY KEY,
    descricao VARCHAR(100),
    valor DECIMAL(10,2),
    status VARCHAR(20) DEFAULT 'pendente'
);
```
Neste exemplo, a coluna "status" é definida com um valor padrão "pendente", que será automaticamente inserido se nenhum valor for especificado durante a inserção de dados.

Além disso, é importante observar que um valor padrão pode ser definido para qualquer tipo de coluna, incluindo texto, números, datas, booleanos etc. É uma ferramenta útil para garantir a consistência dos dados em uma tabela e simplificar a inserção de dados.

### Referências e materiais complementares
- https://www.postgresql.org/docs/current/sql-createtable.html
- https://www.postgresql.org/docs/current/sql-droptable.html
- https://www.postgresql.org/docs/current/sql-altertable.html
- https://www.postgresql.org/docs/current/datatype.html
- https://www.postgresql.org/docs/current/ddl-default.html

---
</details>

<details>
<summary>Primary e Foreign Keys</summary>

---

  ## 📌 Chaves primárias (Primary Keys ou PKs)
No PostgreSQL, uma Primary Key é uma restrição que define uma coluna ou conjunto de colunas em uma tabela como uma chave primária. A Primary Key é usada para identificar de forma exclusiva cada linha da tabela. Cada tabela pode ter apenas uma Primary Key.

Um exemplo de Primary Key seria em uma tabela de usuários, onde a coluna "ID" é definida como Primary Key. Isso garante que cada usuário tenha um ID exclusivo e permite que outras tabelas se relacionem com a tabela de usuários usando o ID como referência.

Outro exemplo seria em uma tabela de produtos, onde a coluna "Código do Produto" é definida como Primary Key. Isso garante que cada produto tenha um código único e permite que outras tabelas se relacionem com a tabela de produtos usando o código do produto como referência.

Uma analogia para entender a importância de uma Primary Key seria como uma identidade para uma pessoa. Assim como cada pessoa tem um CPF exclusivo, cada linha em uma tabela precisa ter um identificador exclusivo para ser identificado corretamente.

Além disso, a Primary Key também pode ajudar a melhorar o desempenho das consultas, pois o PostgreSQL cria automaticamente um índice para a coluna ou conjunto de colunas que fazem parte da Primary Key. Isso torna mais rápido encontrar e acessar linhas específicas na tabela.

Em resumo, a Primary Key é uma restrição importante no PostgreSQL que garante que cada linha de uma tabela tenha um identificador exclusivo e ajuda a melhorar o desempenho das consultas.

Para criar uma Primary Key em uma tabela no PostgreSQL, você pode usar a seguinte sintaxe:

```python
ALTER TABLE tabela
ADD CONSTRAINT nome_da_pk PRIMARY KEY (coluna);
```
Onde "tabela" é o nome da tabela em que você deseja criar a Primary Key, "nome_da_pk" é um nome de sua escolha para a Primary Key e "coluna" é o nome da coluna que você deseja definir como a chave primária.

Por exemplo, para criar uma Primary Key na tabela "usuarios" com a coluna "id" como chave primária, você pode usar o seguinte comando:

```python
ALTER TABLE usuarios
ADD CONSTRAINT pk_usuarios_id PRIMARY KEY (id);
```
Isso irá adicionar uma Primary Key chamada "pk_usuarios_id" na tabela "usuarios" usando a coluna "id" como chave primária.

Ao criar uma tabela no PostgreSQL, você também pode definir a Primary Key usando a cláusula "PRIMARY KEY". Isso é útil quando você está criando uma tabela e deseja definir a chave primária desde o início. Veja o exemplo abaixo:

```python
CREATE TABLE usuarios (
  id SERIAL PRIMARY KEY,
  nome VARCHAR(50),
  email VARCHAR(50)
);
```
## 📌 Chaves estrangeiras (Foreign Keys ou FKs)
Foreign Keys, ou chaves estrangeiras, são uma ferramenta importante para estabelecer relacionamentos entre tabelas em um banco de dados. Uma Foreign Key é uma coluna (ou um conjunto de colunas) em uma tabela que se refere a uma Primary Key em outra tabela. A Foreign Key é usada para garantir que os dados em uma tabela estejam relacionados aos dados em outra tabela, mantendo a integridade referencial do banco de dados.

Imagine que o seu banco de dados é um grande quebra-cabeça com várias peças interligadas. A Primary Key é como a peça central do quebra-cabeça, que serve como base para todas as outras peças se encaixarem. Já a Foreign Key é como uma peça que se encaixa em outra peça, estabelecendo uma relação entre elas. Se você tentar encaixar uma peça em um lugar que não corresponde, ou se faltar uma peça, o quebra-cabeça não ficará completo e não será possível ver a imagem completa. Da mesma forma, se você não definir corretamente as Primary Keys e Foreign Keys no seu banco de dados, ele ficará desorganizado e inconsistente, dificultando a recuperação dos dados.

Vamos ver alguns exemplos para entender como as Foreign Keys funcionam:

## 📌 Tabela de Produtos e Tabela de Categorias
Suponha que você tem uma tabela de produtos e outra tabela de categorias. Cada produto pode estar associado a uma única categoria. Para estabelecer esse relacionamento, você pode adicionar uma coluna chamada "id_categoria" na tabela de produtos e definir essa coluna como uma Foreign Key que referencia a Primary Key da tabela de categorias.

```python
CREATE TABLE categorias (
  id SERIAL PRIMARY KEY,
  nome VARCHAR(50)
);

CREATE TABLE produtos (
  id SERIAL PRIMARY KEY,
  id_categoria INTEGER,
  nome VARCHAR(50),
  preco NUMERIC(10,2),
  FOREIGN KEY (id_categoria) REFERENCES categorias(id)
);
```

Neste exemplo, a tabela "produtos" tem uma coluna "id_categoria" que se refere à coluna "id" da tabela "categorias". A cláusula "FOREIGN KEY" é usada para definir essa relação. Dessa forma, sempre que um produto é inserido na tabela "produtos", é necessário especificar uma categoria existente na tabela "categorias" para associá-lo.

### Referências e materiais complementares
https://www.postgresql.org/docs/current/ddl-constraints.html

---
</details>

<details>
<summary>Constraints</summary>
  
---

Constraints (restrições) são regras que podem ser aplicadas a colunas ou tabelas inteiras em um banco de dados para garantir a integridade e consistência dos dados. As constraints podem ser aplicadas para impor limites, restrições ou regras que devem ser respeitadas para que os dados sejam armazenados no banco.

Imagine que as constraints são como regras em um jogo de tabuleiro. Cada regra especifica o que pode e o que não pode ser feito durante o jogo. Por exemplo, em um jogo de xadrez, existem regras que especificam como as peças podem se mover no tabuleiro. Se um jogador tentar mover uma peça de uma maneira que não está de acordo com as regras, a jogada será inválida e ele terá que voltar atrás. Da mesma forma, se você tentar inserir um valor que não atenda a uma constraint em uma coluna de um banco de dados, a inserção será inválida e você terá que corrigir o valor ou a constraint para continuar.

## 📌 CHECK
A constraint CHECK é usada para impor uma condição específica em uma coluna. Por exemplo, podemos definir uma constraint CHECK para garantir que a coluna "idade" de uma tabela de usuários tenha valores entre 18 e 99 anos. Veja:

```python
CREATE TABLE usuarios (
  id SERIAL PRIMARY KEY,
  nome VARCHAR(50),
  idade INTEGER,
  CONSTRAINT idade_maior CHECK (idade >= 18 AND idade <= 99)
);
```
Isso garante que caso seja inserido um valor não previsto pela constraint, o banco de dados irá gerar um erro e o registro não será inserido.

## 📌 NOT NULL
A constraint NOT NULL é usada para especificar que uma coluna não pode ter valores nulos. Por exemplo, podemos definir uma constraint NULL para garantir que a coluna "email" de uma tabela de usuários não seja nula.

```python
CREATE TABLE usuarios (
  id SERIAL PRIMARY KEY,
  nome VARCHAR(50),
  email VARCHAR(50) NOT NULL
);
```
Isso garante que caso seja inserido um valor nulo na coluna email, o banco de dados irá gerar um erro e o registro não será inserido.

## 📌 UNIQUE
A constraint UNIQUE é usada para garantir que os valores em uma coluna sejam exclusivos. Por exemplo, podemos definir uma constraint UNIQUE para garantir que a coluna "email" de uma tabela de usuários tenha valores únicos.

```python
CREATE TABLE usuarios (
  id SERIAL PRIMARY KEY,
  nome VARCHAR(50),
  email VARCHAR(50) UNIQUE
);
```
Isso garante que caso seja inserido um valor na coluna email que já exista em outro registro, o banco de dados irá gerar um erro e o registro não será inserido.

### Referências e materiais complementares
- https://www.postgresql.org/docs/current/ddl-constraints.html
---

</details>

<details>
<summary>Inserção de Dados</summary>
---

</details>

<details>
<summary>Edição de Dados</summary>
---

</details>

<details>
<summary>Exclusão de Dados</summary>
---

</details>

<details>
<summary>Consulta simples</summary>
---

</details>

<details>
<summary>MER e DER</summary>
---

</details>

<details>
<summary>Formas normais</summary>
---

</details>

<details>
<summary>JOINS</summary>
---

</details>

<details>
<summary>Union</summary>
---

  
</details>

<details>
<summary>Agregação</summary>
---

</details>

<details>
<summary>Cast</summary>
---

</details>

<details>
<summary>Views</summary>
---

</details>

