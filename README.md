Nginx + Flask + PostgreSQL Ansible playbook
-----------------------------------------------------------------------------
- Expects Ubuntu 18+ hosts

This playbook is simplified deployment of basic web application based on Python, Nginx web server and example PostgreSQL database.
It configures Nginx to listen on port 8080 and redirect requests to localhost port 5000, used by Flask 'Hello World' application.
It also installs PostgreSQL, creates database 'test' and user 'postgre' with all rights to this database.
