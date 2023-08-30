Resumo de estudos sobre banco de dados. 


SGBD (Sistema de Gerenciamento de Banco de Dados): 
São sistemas responsáveis pelo gerenciamento de informações em bancos de dados.
A sigla SGBD é oriunda do termo em inglês DBMS (Database Management System).

Cluster:
Em termos de banco de dados e sistemas de computação, um cluster é um grupo de computadores ou servidores interconectados que atuam como uma única unidade coesa.
O objetivo é melhorar desempenho, disponibilidade e confiabilidade, distribuindo tarefas e recursos entre os componentes.

Em Bancos de Dados:
Um cluster de banco de dados envolve múltiplos servidores organizados para gerenciar e processar dados.
Dois tipos principais de clusters:
1. Cluster de Alta Disponibilidade (HA):
   - Vários servidores sincronizados para garantir continuidade em caso de falha.
2. Cluster de Balanceamento de Carga:
   - Distribuição de carga para melhorar o desempenho.

Clusters lidam com cargas intensas, aumentam escalabilidade e garantem disponibilidade contínua.
Implementados com configurações de rede, armazenamento compartilhado e software de gerenciamento.

Transações ACID:
Conjunto de propriedades que garantem consistência e confiabilidade dos dados:
- Atomicidade: Todas as operações em uma transação são executadas com sucesso ou nenhuma.
- Consistência: Transações transformam dados de um estado válido para outro.
- Isolamento: Transações independentes, evitando conflitos.
- Durabilidade: Mudanças confirmadas são permanentemente salvas, mesmo após falhas.

Banco de Dados SQL vs. NoSQL:

SQL (Bancos de Dados Relacionais):
- Dados em tabelas.
- Esquema definido previamente.
- Relacionamentos entre tabelas.
- Consistência forte.

NoSQL (Bancos de Dados Não Relacionais):
- Flexibilidade no esquema.
- Adequado para cenários específicos.
- Modelos variados (gráficos, documentos, valor-chave, etc.).
- Consistência flexível.

Introdução a Bancos de Dados NoSQL:

NoSQL = NOT only SQL.
Não seguem modelos tradicionais de tabelas e relacionamentos.
Projetados para alta escalabilidade e flexibilidade na estrutura de dados.
Uso comum em cenários onde consistência imediata não é crítica.

Vantagens NoSQL:
- Flexibilidade na modelagem.
- Alta escalabilidade.
- Melhor desempenho em consultas intensivas.
- Tolerância a falhas.

Desvantagens:
- Consistência imediata menor.
- Suporte a consultas complexas varia entre SGBDs.

  NoSQL (Bancos de Dados Não Relacionais)

Tipos de Bancos de Dados NoSQL:

1. **Key-Value**:
   - Armazena dados em pares chave-valor.
   - Chave é um identificador único para acessar o valor.
   - Exemplos: Redis, Riak, Amazon DynamoDB.
   - Uso: Armazenamento de informações de sessão de usuário.

2. **Documento**:
   - Armazena dados em documentos semiestruturados (JSON, BSON).
   - Exemplos: MongoDB, Couchbase, Apache CouchDB.
   - Uso: Armazenamento de informações de produtos em catálogos.

3. **Coluna**:
   - Armazena dados em formato de colunas.
   - Alta escalabilidade e eficiência em consultas.
   - Exemplos: Apache Cassandra, ScyllaDB, HBase.
   - Uso: Armazenamento de registros de log em sistemas de registro de aplicativos.

4. **Grafos**:
   - Armazena e coleta dados interconectados com foco em relacionamentos.
   - Exemplos: Neo4j, Amazon Neptune, JanusGraph.
   - Uso: Armazenamento de perfis de usuários e conexões em redes sociais.

5. **Outros**:
   - Existem outros tipos específicos com funcionalidades únicas.

Bancos de Dados NoSQL são projetados para lidar com alto volume de dados, escalabilidade e flexibilidade em modelos de dados. Eles são amplamente usados em cenários onde a estrutura dos dados pode variar e as relações entre os dados são complexas, como em redes sociais, análise de big data e aplicações web em escala.


MongoDB

    Características Gerais:
    O MongoDB é um banco de dados não relacional orientado a documentos, projetado para lidar com grandes volumes de dados. Ele oferece escalabilidade horizontal e uma modelagem flexível que se adapta às necessidades variadas dos projetos.

    Estrutura de Documentos:
    Uma das principais características do MongoDB é que ele não exige um esquema fixo para os dados. Os documentos são armazenados em formato BSON (Binary JSON), que permite uma estrutura semiestruturada. Isso proporciona agilidade na evolução dos dados ao longo do tempo.

    Vantagens:
        Flexibilidade na Modelagem de Dados: A ausência de um esquema rígido permite que os desenvolvedores ajustem os documentos de acordo com as necessidades do aplicativo, sem a necessidade de modificações complexas.
        Escalabilidade Horizontal: O MongoDB é capaz de lidar com grandes volumes de dados e alto tráfego por meio de clusters, distribuindo a carga entre os nós, o que facilita a escalabilidade.
        Consultas Ricas e Complexas: O sistema oferece recursos avançados de consulta, incluindo suporte a consultas complexas, agregações e indexações para otimizar o desempenho.
        Alta Disponibilidade e Tolerância a Falhas: O MongoDB suporta réplicas e failover automático para garantir a disponibilidade contínua dos dados mesmo em caso de falhas.

    Desvantagens:
        Menor Consistência Imediata: Comparado a bancos de dados relacionais, o MongoDB pode ter uma consistência imediata menor, devido à natureza distribuída e à ausência de bloqueios rígidos.
        Consultas Complexas Demandam Conhecimento: Consultas mais complexas podem requerer um conhecimento mais profundo das funcionalidades do MongoDB e um planejamento adequado.
        Consumo Maior de Espaço: Devido à flexibilidade dos documentos, o armazenamento em MongoDB pode consumir mais espaço em comparação com bancos de dados relacionais.

    Aplicações e Casos de Uso:
        Aplicações Web Flexíveis e Escaláveis: O MongoDB é especialmente útil em aplicações web que precisam de flexibilidade e escalabilidade para lidar com volumes variáveis de dados.
        Análise de Big Data: Sua capacidade de lidar com grandes volumes de dados o torna adequado para análise de big data, onde a coleta e processamento de informações são essenciais.
        Armazenamento de Dados Semiestruturados: O formato BSON permite o armazenamento de dados semiestruturados, como informações variáveis em uma coleção.
        Geolocalização e Redes Sociais: Em casos de uso que envolvem geolocalização ou redes sociais, o MongoDB pode ser usado para armazenar dados interconectados, como perfis de usuários e conexões.

O MongoDB oferece uma alternativa poderosa aos bancos de dados relacionais, sendo especialmente adequado para cenários em que a flexibilidade e a escalabilidade são essenciais.
