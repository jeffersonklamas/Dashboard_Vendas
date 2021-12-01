Aprendendo a aprender:

O desafio neste mini-projeto foi o de construir um pequeno **Data Warehouse** usando o [PostgreSQL](https://www.postgresql.org/), popular as tabelas, praticar um pouco de **ETL** - **E**xtract, **T**ransform e **L**oad e na sequência conectar ao **Power BI** para desenvolver os relatórios.

O principal foi conhecer a ferramenta na prática com o PostgreSQL e o desenvolvimento de banco de dados relacional, bem como o conhecimento e suas diferenças entre banco de dados transacional e banco de dados consolidado ou dimensional para criação de relatórios e acompanhamentos de indicadores.

Sequência para desenvolvimento do banco de dados:

* Definição do problema.
* Modelo Lógico ( Para entender o relacionamento entre as entidades).
* Modelo Físico ( A implementação do Banco de Dados).
* Implementação do **DW** (criar a tabela, definir as colunas, tipos de dados e etc)
* **ETL** (**E**xtract, **T**ransform e **L**oad) carregar os dados para o **DW**
* Construir visualizações e relatórios no Power BI

Colunas criadas:

| Coluna        | Descrição                                           |
| ------------- | --------------------------------------------------- |
| ID_Produto    | Identificador único de cada produto                 |
| Produto       | Nome do Produto                                     |
| Segmento      | Segmento do Produto                                 |
| Categoria     | Categoria do Produto                                |
| Segmento      | Segmento do produto                                 |
| Fabricante    | Fabricante do Produto                               |
| ID_Loja       | ID da Loja onde foi efetuada a venda (Único)        |
| Loja          | Loja onde foi efetuada a venda                      |
| Cidade        | Cidade da loja onde foi efetuada a venda            |
| Estado        | Estado da Loja onde foi efetuada a venda            |
| Vendedor      | Nome do Vendedor                                    |
| SobreNome     | Sobre Nome do Vendedor                              |
| ID_Vendedor   | ID do vendedor (Único)                              |
| Data Completa | Data da Venda (neste momento definido com ID Único) |
| DIA           | A ser implementado                                  |
| Mes           | A ser implementado                                  |
| Ano           | A ser implementado                                  |
| Valor Venda   | Valor da venda                                      |

Como utilizei dados fictícios e pequenos, a criação do **DW** foi tranquila e de grande aprendizado no momento, compreender a lógica para estruturação de um banco de dados e seus detalhes, no momento criei algo básico para estudo, junto com a prática de **ETL**.

DW Criado![dwcriado](C:\Users\jeffe\Documents\CURSOS_DSA\POWER_BI\Cap10_Bancos_Relacionais\EstudoDeCaso_4\imagens\miniprojeto.png)



No **Power BI** no momento por ser um banco de dados pequenos e para teste, usei a opção se conectar com banco de dados na opção **importar** e não na **DirectQuery** por ser esta opção para volumes de dados maior do que 1gb.

E a visualização no **Power BI** para demonstrar a solução aos tomadores de decisão.

Neste caso, a perguntas respondidas seriam:

* Quais Fornecedores poderia ter uma melhor negociação para aquisição e venda de produtos nas lojas da rede.
* Qual segmento investir para alavancar as vendas.

Imagem Dashboard![Dashboard](C:\Users\jeffe\Documents\CURSOS_DSA\POWER_BI\Cap10_Bancos_Relacionais\EstudoDeCaso_4\imagens\dashboardMiniProjeto4.png)

## Ferramentas Usadas

* PostgreSQL 13.
* pgAdmin.
* Power BI Desktop.
* Sistema Operacional Windows.
* Vontade para aprender.