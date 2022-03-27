Odoo with micro services
===
This Docker Compose file will deploy a Odoo application with isolated services ideal for testing purposes, be ready to use Odoo just with one command in seconds.

Architecture
===

* Web Server: Nginx
* Application: Odoo
* Data Base: PostgreSQL
* Data Base Administration (GUI): PGadmin

<p align="left">
 <img width="600px" src="https://nagsis.com/images/odoo.png" align="center" alt="Odoo Docker Compose" />
</p>


Configuration Process
===

Requirements:

- docker >= 20.10.13+
- docker-compose

Quick Start

- Clone or download this repository
- Go inside of directory, cd odoo
- Run this command docker-compose up -d