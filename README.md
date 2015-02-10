# Rails and React II: A real use case

This is a real use case application using:

* Rails 4.2.0 beta
* React.js
* PostgreSQL full-text search


## Installation

### Configuration Postgres DB
* sudo -u postgres psql
* CREATE DATABASE react_rails_dev OWNER developer;
* CREATE DATABASE react_rails_test OWNER developer;

### DB migrate & seeds
* rake db:migrate
* rake db:setup

