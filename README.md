# DB-Engine-using-Linux

## About the project
The project aim is to build a database engine simulator, and I have used bash scripting to do that, through the project you will find: 

● Awk programming language that used to perform text processing and data extraction

● Functions for modularization and readability purposes

● Sed for searching, finding, and replacing

## Project Description


The database engine initially establishes the "DB" directory as the top-level container for housing various database folders. Within this structure, the engine systematically generates database directories designed to accommodate individual tables. At the table level, the engine systematically generates two distinctive files for each table within the Database Management System (DBMS):

Data File: This file serves as a repository for user-specific data.

Metadata File: This file encapsulates the table schema, comprising essential information such as the table name, primary key, and column types.

● A basic database engine capable of managing databases and tables, enabling actions like creation, dropping, listing, 
and connecting to databases.

● Users can perform a range of table operations, including creating, inserting, dropping, selecting, listing, deleting, and 
updating data.

## Running the DBMS 

● To run it make sure to set the project path to the .bashrc file
  
```bash
export PATH=$PATH:/the_projectpath_in_your_machine
```
- after that run it in your terminal
  ```bash
  MainMenu.sh
  ```
