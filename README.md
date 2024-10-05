# Erlang REST API example
Simple example Erlang Cowboy REST API service
- Cowboy 2.0
- Cowboy sessions (fork)
- Emodel (validate user input)
- pgapp (poolboy and epgsql)
- sync (hotreload)
## To start

Install rebar  - (e.g. apt-get install rebar or yum rebar)

Then run
```
make
make run-local
```
Install Postgres and create database and postgres user.

Edit config /config/sys.config to connect db

init db in console:
```
persist:init_db(pgdb).
```
## To use
Url for API http://localhost:8080

