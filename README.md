# World
Base de datos de los países

In the MySQL interactive client you can type:

source yourfile.sql
Alternatively you can pipe the data into mysql from the command line:

mysql < yourfile.sql
If the file doesn't specify a database then you will also need to add that:

mysql db_name < yourfile.sql
