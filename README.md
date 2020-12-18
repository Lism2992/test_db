# test_db

Many people requested a solution (https://github.com/datacharmer/test_db/issues/5) for importation problems with the ".dump" files.

This fix solves importation problems and when running the query, MySQL Workbench should create all tables in the database and fill them with the proper data.

Upon importing "employees.sql" on MySQL Workbench you may receive an alert telling you that the file is massive, please select "Run SQL Script" option instead of "Open" to prevent errors.

It may take a while but it's still faster than executing all the ".dump" files queries by yourself.
