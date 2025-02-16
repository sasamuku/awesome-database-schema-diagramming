# Awesome Database Schema Diagramming

A curated list of tools for database schema visualization, modeling, and diagramming.

## Tools

### [dbdiagram.io](https://dbdiagram.io/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: [DBML (Database Markup Language)](https://dbml.dbdiagram.io/home/)
- **Schema Import**: MySQL, PostgreSQL, SQL Server, Snowflake, BigQuery, schema.rb
- **Schema Export**: MySQL, PostgreSQL, SQL Server, Oracle
- **Database Connection**: Not supported
- **Collaboration**: Link sharing (paid plan)
- **Visualization**: Drag & drop table positioning, auto-layout
- **Pricing**: Free (up to 10 diagrams), Paid ($14+/month)
- **Import/Export**: PNG, PDF, MySQL, PostgreSQL

### [drawSQL](https://drawsql.app/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: None
- **Schema Import**: MySQL, PostgreSQL, SQL Server
- **Schema Export**: MySQL, PostgreSQL, SQL Server, Laravel Migrations
- **Database Connection**: Supported
- **Collaboration**: Team collaboration, link sharing, embed links
- **Visualization**: 200+ templates
- **Pricing**: Free (up to 15 tables), Paid ($19+/month)
- **Import/Export**: SQL, JSON, images

### [drawDB](https://www.drawdb.app/)
- **Features**: ERD creation, table/column definition, relationship definition, TODO management, timeline
- **DSL**: None
- **Schema Import**: MySQL, PostgreSQL
- **Schema Export**: MySQL, PostgreSQL, SQLite, MariaDB, SQL Server, JSON, Markdown
- **Database Connection**: Not supported
- **Collaboration**: Link sharing
- **Visualization**: Customizable workspace, presentation mode
- **Pricing**: Free, Open Source
- **Import/Export**: JSON, images, SQL DDL, Markdown

### [Vertabelo](https://vertabelo.com/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: None
- **Schema Import**: SQL, XML
- **Schema Export**: SQL, XML
- **Database Connection**: Supported
- **Collaboration**: Team accounts, sharing, access control
- **Visualization**: Snowflake schema, star schema, zoom, visual search
- **Pricing**: Free (limited models), Paid (user-based pricing)
- **Import/Export**: SQL, PNG

### [Azimutt](https://azimutt.app/)
- **Features**: ERD creation, table/column definition, relationship definition, data preview, query execution
- **DSL**: [AML (Azimutt Markup Language)](https://azimutt.app/docs/aml)
- **Schema Import**: SQL, Prisma, AML, JSON
- **Schema Export**: AML, SQL (PostgreSQL), JSON, Markdown, Mermaid
- **Database Connection**: Supported
- **Collaboration**: Supported
- **Visualization**: Multi-layout, supports up to 1000 tables
- **Pricing**: Free (online-only, limited features), Paid (€9+/month), On-premise
- **Import/Export**: SQL, JSON, AML

### [QuickDBD](https://www.quickdatabasediagrams.com/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: Simple text-based DSL
- **Schema Import**: MySQL/MariaDB, Oracle, SQL Server
- **Schema Export**: ANSI SQL, MySQL/MariaDB, Oracle (12c+), PostgreSQL, SQL Server
- **Database Connection**: Not supported
- **Collaboration**: Online collaboration
- **Visualization**: Real-time preview
- **Pricing**: Free (1 diagram, up to 10 tables), Paid ($14+/month)
- **Import/Export**: PDF, SQL, CSV

### [ERD Plus](https://erdplus.com/)
- **Features**: ERD creation, table/column definition, relationship definition
- **DSL**: None
- **Schema Import**: JSON, SQL
- **Schema Export**: JSON, SQL
- **Database Connection**: Not supported
- **Collaboration**: Not supported
- **Visualization**: Chen notation, conceptual models, physical models, star schema
- **Pricing**: Free
- **Import/Export**: SQL, PNG

### [SqlDBM](https://sqldbm.com/Home/)
- **Features**: ERD creation, table/column definition, relationship definition, views, stored procedures
- **DSL**: None
- **Schema Import**: SQL, Excel
- **Schema Export**: SQL, Excel
- **Database Connection**: Supports Snowflake, Azure Synapse
- **Collaboration**: Team collaboration, comments, tagging
- **Visualization**: Conceptual models, physical models, views, stored procedures
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
- **Azimutt**: available in paid plans
- **VS Code extensions**: Design database schema and view ERD

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

