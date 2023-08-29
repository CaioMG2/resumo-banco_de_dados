Resumo de estudos sobre banco de dados. 
Banco de Dados

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
