# Awesome Database Schema Diagramming

A curated list of tools for database schema visualization, modeling, and diagramming.

## Tools

### [dbdiagram.io](https://dbdiagram.io/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: [DBML (Database Markup Language)](https://dbml.dbdiagram.io/home/)
- **Schema Import**: MySQL, PostgreSQL, schema.rb
- **Database Connection**: Not supported
- **Reverse Engineering**: MySQL, PostgreSQL, schema.rb
- **Forward Engineering**: SQL DDL
- **Collaboration**: Link sharing (paid plan)
- **Visualization**: Drag & drop table positioning, auto-layout
- **Data Types**: MySQL, PostgreSQL
- **Pricing**: Free (up to 10 diagrams), Paid ($14+/month)
- **Import/Export**: PNG, PDF, MySQL, PostgreSQL

### [drawSQL](https://drawsql.app/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: None
- **Schema Import**: SQL
- **Database Connection**: Supported
- **Reverse Engineering**: SQL
- **Forward Engineering**: SQL DDL, Laravel Migrations
- **Collaboration**: Team collaboration, link sharing, embed links
- **Visualization**: 200+ templates
- **Data Types**: MySQL, PostgreSQL, SQL Server
- **Pricing**: Free (up to 15 tables), Paid ($19+/month)
- **Import/Export**: SQL, JSON, images

### [drawDB](https://www.drawdb.app/)
- **Features**: ERD creation, table/column definition, relationship definition, TODO management, timeline
- **DSL**: None
- **Schema Import**: SQL
- **Database Connection**: Not supported
- **Reverse Engineering**: SQL
- **Forward Engineering**: SQL DDL
- **Collaboration**: Link sharing
- **Visualization**: Customizable workspace, presentation mode
- **Data Types**: MySQL, PostgreSQL, SQLite, MariaDB, SQL Server
- **Pricing**: Free, Open Source
- **Import/Export**: JSON, images, SQL DDL, Markdown

### [Vertabelo](https://vertabelo.com/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: None
- **Schema Import**: SQL
- **Database Connection**: Supported
- **Reverse Engineering**: Supported
- **Forward Engineering**: SQL DDL
- **Collaboration**: Team accounts, sharing, access control
- **Visualization**: Snowflake schema, star schema, zoom, visual search
- **Data Types**: SQL Server, PostgreSQL, MySQL, Oracle, SQLite, Amazon Redshift
- **Pricing**: Free (limited models), Paid (user-based pricing)
- **Import/Export**: SQL, PNG

### [Azimutt](https://azimutt.app/)
- **Features**: ERD creation, table/column definition, relationship definition, data preview, query execution
- **DSL**: [AML (Azimutt Markup Language)](https://azimutt.app/docs/aml)
- **Schema Import**: SQL, Prisma, JSON
- **Database Connection**: Supported
- **Reverse Engineering**: Database connection, SQL, Prisma, JSON
- **Forward Engineering**: SQL, AML
- **Collaboration**: Supported
- **Visualization**: Multi-layout, supports up to 1000 tables
- **Data Types**: MySQL, PostgreSQL, SQLite, MongoDB
- **Pricing**: Free (online-only, limited features), Paid (€9+/month), On-premise
- **Import/Export**: SQL, JSON, AML

### [QuickDBD](https://www.quickdatabasediagrams.com/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: Simple text-based DSL
- **Schema Import**: MySQL, Oracle, SQL Server
- **Database Connection**: Not supported
- **Reverse Engineering**: MySQL, Oracle, SQL Server
- **Forward Engineering**: SQL DDL
- **Collaboration**: Online collaboration
- **Visualization**: Real-time preview
- **Data Types**: MySQL, Oracle, SQL Server
- **Pricing**: Free (1 diagram, up to 10 tables), Paid ($14+/month)
- **Import/Export**: PDF, SQL, CSV

### [ERD Plus](https://erdplus.com/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: None
- **Schema Import**: Not supported
- **Database Connection**: Not supported
- **Reverse Engineering**: Not supported
- **Forward Engineering**: SQL DDL
- **Collaboration**: Not supported
- **Visualization**: Chen notation, conceptual models, physical models, star schema
- **Data Types**: Oracle, MySQL, SQL Server, PostgreSQL, Teradata, IBM DB2, MS Access
- **Pricing**: Free
- **Import/Export**: SQL, PNG

### [SqlDBM](https://sqldbm.com/Home/)
- **Features**: ERD creation, table/column definition, relationship definition, views, stored procedures
- **DSL**: None
- **Schema Import**: SQL
- **Database Connection**: Supports Snowflake, Azure Synapse
- **Reverse Engineering**: Database connection, SQL
- **Forward Engineering**: SQL DDL
- **Collaboration**: Team collaboration, comments, tagging
- **Visualization**: Conceptual models, physical models, views, stored procedures
- **Data Types**: Snowflake, Azure Synapse, AlloyDB, Snowflake VARIANT data type
- **Pricing**: Free, Paid (user-based pricing), Enterprise
- **Import/Export**: SQL DDL, YAML, Confluence, Jira integration

## DSLs

### [AML (Azimutt Markup Language)](https://azimutt.app/docs/aml)
AML is a DSL used in Azimutt, a database visualization tool. It allows users to create ERDs quickly and intuitively, similar to sketching a database schema on a whiteboard. Azimutt is a commercial tool, and using AML features requires a paid plan. However, information on AML is limited, and official documentation is not easily accessible. AML focuses more on database schema representation than traditional ERD modeling.

#### ERD Representation
- Supports entities, attributes, and relationships (detailed information is limited)

#### Syntax
- Concise and highly readable

#### Tools
- Azimutt (available in paid plans)

### [DBML (Database Markup Language)](https://dbml.dbdiagram.io/home/)
DBML is an open-source DSL for defining and documenting database schemas. It features a simple, consistent, and human-readable syntax. DBML was designed to address common challenges in large and complex software projects, such as understanding database structures, comprehending table relationships, and dealing with outdated ERDs or SQL DDL scripts. It also supports conversion between DBML and SQL through various tools and integrations.

#### ERD Representation
- Defines tables, columns, indexes, relationships, and enums
- Supports data types, constraints, foreign keys, and comments

#### Syntax
- Concise and human-readable

#### Tools
- **dbdiagram.io**: Free tool for visualizing ERDs from DBML
- **dbdocs.io**: Free tool for generating database documentation from DBML
- **Command-line tools**: Convert between SQL and DBML
- **Open-source JavaScript libraries**: Programmatic conversion between DBML and SQL DDL
- **VS Code extensions**: DBML ERD Visualizer, DBML Viewer

