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

* [Tools](#tools)
* [Installation](#installation)
* [Administration](#administration)
* [Querying](#querying)
* [Database Design](#database-design)
* [Development](#development)

### Database Tools
* [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
    * [Course: SSMS Shortcuts and Secrets](https://www.youtube.com/watch?v=h04qEu8vJYc&list=PLoM-GGCV9ZrKqqR2fhxuy-oKookinG4nx) - Kendra Little
* [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is)
    * [The A to S of Azure Data Studio :tv:](https://www.youtube.com/watch?v=F0bIBFuH93c) 
* [Visual Studio Code](https://code.visualstudio.com/) - Free. Built on open source. Runs everywhere.


-----
## Installation
* [SQL Server Developer](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)


## <a name="formatter"></a>Formatters
- [SQL Format](http://www.dpriver.com/pp/sqlformat.htm) - Instant SQL Formatter
- [Poor SQL](http://poorsql.com/) - Instant Free and Open-Source T-SQL Formatting (look here for the plugins and whatnot: https://github.com/TaoK/PoorMansTSqlFormatter )
- [ExtendsClass](https://extendsclass.com/sql-formatter.html) - Online SQL formatter



## Querying
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
### YouTube :tv:
* [SQL Server Queries](https://www.youtube.com/watch?v=2-1XQHAgDsM&list=PL6EDEB03D20332309) - WiseOwlTutorials
* [Querying with Transact-SQL (Channel 9)](https://channel9.msdn.com/Series/Querying-with-Transact-SQL)
* [Like (Advanced) ~11min](https://www.youtube.com/watch?v=d-fnQtWdiW4) - Database by Doug
* [Intro to Structured Query Language](https://www.youtube.com/playlist?list=PLJ81tOM0EcYfzm7ET5_G8XsXz-RJF4vqc) - Database by Doug
### Books
* [Learn T-SQL Querying (Free)](https://www.packtpub.com/free-ebook/learn-t-sql-querying/9781789348811) - Packt
### Learning
#### Get Started Querying with Transact-SQL
* [Get Started Querying with Transact-SQL (Path)](https://docs.microsoft.com/en-us/learn/paths/get-started-querying-with-transact-sql/) - Microsoft Learn
1. [Introduction to Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/introduction-to-transact-sql/)
1. [Sort and filter results in T-SQL](https://docs.microsoft.com/en-us/learn/modules/sort-filter-queries/)
1. [Combine multiple tables with JOINs in T-SQL](https://docs.microsoft.com/en-us/learn/modules/query-multiple-tables-with-joins/)
1. [Write Subqueries in T-SQL](https://docs.microsoft.com/en-us/learn/paths/get-started-querying-with-transact-sql/)
1. [Use built-in functions and GROUP BY in Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/use-built-functions-transact-sql/)
1. [Modify data with T-SQL](https://docs.microsoft.com/en-us/learn/modules/modify-data-with-transact-sql/)

## SSMS
- [SSMS addins](/SSMS/SSMS_Addins.md) (**37 useful free and paid SSMS Addins**)
- [SSMS Snippets](/SSMS/SSMS_Snippets)
- [SSMS Shortcuts](/SSMS/SSMS_Shortcuts.md) (**More than 300 Shortcuts**)
- [SSMS Tips](/SSMS/SSMS_Tips.md) (**Complete guide about hidden gems of SSMS**)

## Shields
[![](https://img.shields.io/github/languages/top/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/languages/count/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/license/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/languages/code-size/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/repo-size/jvsouza/sql-server-awesome)]()
[![](https://img.shields.io/github/last-commit/jvsouza/sql-server-awesome)]()
