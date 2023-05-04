# sql-server-awesome [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

![Progresso](https://progress-bar.dev/3/?title=Completo%20&width=160&color=54aeff)

Lista de técnicas e ferramentas para trabalhar com o sistema gerenciador de banco de dados relacional Microsoft SQL Server

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **SQL Server Awesome**
| :label: Tecnologias | TSQL, SQL, PowerShell
| :rocket: URL         | https://github.com/jvsouza/sql-server-awesome
| :fire: Desafio     | https://cursos.alura.com.br/formacao-microsoft-sql-server-2022

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://raw.githubusercontent.com/jvsouza/sql-server-awesome/main/image/vitrine.png?text=vitrinedev#vitrinedev)

## Detalhes do projeto
Textos e imagens que descrevam seu projeto, suas conquistas, seus desafios, próximos passos, etc...

## Estrutura de arquivos:
```text
├── image
│   └── vitrinedev.png
├── script
│   ├── example_01.sql (join)
│   └── example_02.sql (stored-procedure)
├── LICENSE
└── README.md
```

## Conteúdo
- [Installation](#installation)
- [Ferramenta](#ferramenta)
- [SSMS](#ssms)
- [Formatador](#formatador)
- [Consulta](#consulta)
- [T-SQL](#tsql)

### Installation
- [SQL Server (Developer)](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

### Ferramenta
- [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

### SSMS
- [Suplemento (Add-In)](/SSMS/SSMS_Addins.md) 
- [Bloco de código (Snippet)](/SSMS/SSMS_Snippets)
- [Atalhos (Shotcut)](/SSMS/SSMS_Shortcuts.md) 
- [Dicas (Tip)](/SSMS/SSMS_Tips.md)

### Formatador
- [SQL Format](http://www.dpriver.com/pp/sqlformat.htm) - Instant SQL Formatter
- [ExtendsClass](https://extendsclass.com/sql-formatter.html) - Online SQL formatter

### Consulta
* [Intro to SQL](https://github.com/datacamp/courses-introduction-to-sql) - DataCamp
  - [Venkatramani Rajgopal](https://venkat-rajgopal.github.io/Essential-SQL/)
* [SQL all kinds of join queries](https://huklee.github.io/2017/01/28/021.SQL-all-kinds-of-join-queries/)
* [Subqueries (Derived Table)](https://docs.microsoft.com/en-us/sql/relational-databases/performance/subqueries)
* [Learn SQL Cookbook](https://learnsql.com/cookbook/) - learnsql.com
  - [Window Functions vs. GROUP BY](https://learnsql.com/blog/sql-window-functions-vs-group-by/)
  - [SQL Window Functions Cheat Sheet](https://learnsql.com/blog/sql-window-functions-cheat-sheet/) 
* [Date and Time](https://docs.microsoft.com/en-us/sql/t-sql/functions/date-and-time-data-types-and-functions-transact-sql)
  - [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) 
  - [GETDATE](https://docs.microsoft.com/en-us/sql/t-sql/functions/getdate-transact-sql), [GETUTCDATE](https://docs.microsoft.com/en-us/sql/t-sql/functions/getutcdate-transact-sql)
  - [YEAR](https://docs.microsoft.com/en-us/sql/t-sql/functions/year-transact-sql), [MONTH](https://docs.microsoft.com/en-us/sql/t-sql/functions/month-transact-sql), [DAY](https://docs.microsoft.com/en-us/sql/t-sql/functions/day-transact-sql)
  - [DATEPART](https://docs.microsoft.com/en-us/sql/t-sql/functions/datepart-transact-sql), [DATENAME](https://docs.microsoft.com/en-us/sql/t-sql/functions/datename-transact-sql)
  - [DATEADD](https://docs.microsoft.com/en-us/sql/t-sql/functions/dateadd-transact-sql), [DATEDIFF](https://docs.microsoft.com/en-us/sql/t-sql/functions/datediff-transact-sql)
  - [ISDATE](https://docs.microsoft.com/en-us/sql/t-sql/functions/isdate-transact-sql)
* [String](https://docs.microsoft.com/en-us/sql/t-sql/functions/string-functions-transact-sql)
  - [LEN](https://docs.microsoft.com/en-us/sql/t-sql/functions/len-transact-sql), [LEFT](https://docs.microsoft.com/en-us/sql/t-sql/functions/left-transact-sql), [RIGHT](https://docs.microsoft.com/en-us/sql/t-sql/functions/right-transact-sql)
  - [UPPER](https://docs.microsoft.com/en-us/sql/t-sql/functions/upper-transact-sql), [LOWER](https://docs.microsoft.com/en-us/sql/t-sql/functions/lower-transact-sql)
  - [CHARINDEX](https://docs.microsoft.com/en-us/sql/t-sql/functions/charindex-transact-sql), [PATINDEX](https://docs.microsoft.com/en-us/sql/t-sql/functions/patindex-transact-sql)
  - [STRING_AGG](https://docs.microsoft.com/en-us/sql/t-sql/functions/string-agg-transact-sql), [STRING_SPLIT](https://docs.microsoft.com/en-us/sql/t-sql/functions/string-split-transact-sql)
* [Aggregate](https://docs.microsoft.com/en-us/sql/t-sql/functions/aggregate-functions-transact-sql)
  - Statistical aggregate functions
    - [SUM](https://docs.microsoft.com/en-us/sql/t-sql/functions/sum-transact-sql), [COUNT](https://docs.microsoft.com/en-us/sql/t-sql/functions/count-transact-sql), MIN, and MAX
    - [AVG](https://docs.microsoft.com/en-us/sql/t-sql/functions/avg-transact-sql),VAR, VARP, [STDEV](https://docs.microsoft.com/en-us/sql/t-sql/functions/stdev-transact-sql) and STDEVP
* [Analytic Functions](https://docs.microsoft.com/en-us/sql/t-sql/functions/analytic-functions-transact-sql)
  - [LAG](https://docs.microsoft.com/en-us/sql/t-sql/functions/lag-transact-sql), [LEAD](https://docs.microsoft.com/en-us/sql/t-sql/functions/lead-transact-sql)

### TSQL
- [Introduction to Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/introduction-to-transact-sql/)
- [Sort and filter results in T-SQL](https://docs.microsoft.com/en-us/learn/modules/sort-filter-queries/)
- [Combine multiple tables with JOINs in T-SQL](https://docs.microsoft.com/en-us/learn/modules/query-multiple-tables-with-joins/)
- [Write Subqueries in T-SQL](https://docs.microsoft.com/en-us/learn/paths/get-started-querying-with-transact-sql/)
- [Use built-in functions and GROUP BY in Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/use-built-functions-transact-sql/)
- [Modify data with T-SQL](https://docs.microsoft.com/en-us/learn/modules/modify-data-with-transact-sql/)

## Shields
[![](https://img.shields.io/github/languages/top/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/languages/count/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/license/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/languages/code-size/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/repo-size/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/last-commit/jvsouza/sql-server-awesome)]()
