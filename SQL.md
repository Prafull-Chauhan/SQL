# What is SQL?

SQL stands for Structered Query Language,is the standardized programming language used to manage query,and manipultes data stored 
in relational databses.It allows users to easily communicate with database by writing commands called queries.

-> This happens because data in a relational database is stored cleanly in tables containing rows and columns.SQL acts like a
universal key to instantly retrieve or change specific pieces of information.

# Core Capabilities of SQL:-

SQL handles everything related to data infrastructure through standard operational tasks:

a.> DATA Retrieval: Fetching specific records using filters,sorting rules,and aggressions.

b.> DATA Modification: Inserting new records,updating existing data values,and deleting outdated rows.

c.> DATABASE Administration: Designing new data tables,establishing relationships betwenn tables, and modifying 
                     system structures.

d.> Access Control: Managing user permissions to restrict who can view or alter sensitive information.

# 5 Types of SQL Commands:-
```mermaid
flowchart TB

    SQL["SQL Commands"]

    SQL --> DDL["DDL"]
    SQL --> DML["DML"]
    SQL --> DCL["DCL"]
    SQL --> TCL["TCL"]
    SQL --> DQL["DQL"]

    DDL --> Create["Create"]
    DDL --> Drop["Drop"]
    DDL --> Alter["Alter"]
    DDL --> Truncate["Truncate"]
    DDL --> Rename["Rename"]

    DML --> Insert["Insert"]
    DML --> Update["Update"]
    DML --> Delete["Delete"]

    DCL --> Grant["Grant"]
    DCL --> Revoke["Revoke"]

    TCL --> Commit["Commit"]
    TCL --> Rollback["Rollback"]
    TCL --> SavePoint["Save Point"]

    DQL --> Select["Select"]

    %% Styling
    classDef title fill:#0b3d91,stroke:#0b3d91,color:#ffffff,font-size:24px,font-weight:bold;
    classDef group fill:#103c8b,stroke:#103c8b,color:#ffffff,font-weight:bold;
    classDef cmd fill:#6c63ff,stroke:#6c63ff,color:#ffffff;

    class SQL title;
    class DDL,DML,DCL,TCL,DQL group;
    class Create,Drop,Alter,Truncate,Rename,Insert,Update,Delete,Grant,Revoke,Commit,Rollback,SavePoint,Select cmd;
```
