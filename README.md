## Simple Sylius script pack that make every day work easier

*Exclude these files in your `/usr/local/bin` directory and make sure they have the exec privilege (+x)*

List of scripts:
* [build-plugin](build-plugin) - creates a plugin test environment from scratch and runs basic fixtures suite
* [run-plugin](run-plugin) - starts a local server with test env on localhost:8080
* [reload-fixtures](reload-fixtures) - loads a fresh database setup for a default fixture suite 
* [rebuild-db](rebuild-db) - Drops database, creates a new one with a schema and loads default fixtures suite
