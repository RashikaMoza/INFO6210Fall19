# INFO6210Fall19

link::https://dev.mysql.com/doc/sakila/en/sakila-installation.html

The sakila-schema.sql file contains all the CREATE statements required to create the structure of the Sakila database including tables, views, stored procedures, and triggers.

The sakila-data.sql file contains the INSERT statements required to populate the structure created by the sakila-schema.sql file, along with definitions for triggers that must be created after the initial data load.

The sakila.mwb file is a MySQL Workbench data model that you can open within MySQL Workbench to examine the database structure.

Installation of Sakila Database:

1) Download and extract sakila-db .zip file.

2) Open MySQL 8.0 Command Line Client and enter the password when prompted

3) Execute the command to create database structure:

	SOURCE C:/Users/Rashika/Downloads/sakila-db/sakila-db/sakila-schema.sql;

4) Execute the command to populate database structure:
	
	SOURCE C:/Users/Rashika/Downloads/sakila-db/sakila-db/sakila-data.sql;

5) Need to confirm if Database is installed correctly:
	
	USE sakila;
	SHOW TABLES;

6) Refresh the Database in MySQL Workbench to confirm that database is reflected in the workbench.

	
