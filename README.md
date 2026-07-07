SYNAPSE FEST – Festival Management Database System

A PostgreSQL-based database system designed for managing a college
techno-cultural festival. The project models various aspects of
festival operations such as events, committees, attendees, tickets,
sponsors, accommodation, vendors, and lost-and-found management.

Features

* Designed and normalized a relational database schema up to BCNF.
* Implemented 30+ entities with appropriate primary keys, foreign keys, and integrity constraints on PostgreSQL.
* Developed PostgreSQL triggers for accommodation billing, room-capacity validation and handling event-venue conflicts.
* Created analytical SQL queries for ticket sales, sponsorships, committee funding, and accommodation management.

Tech Stack

* PostgreSQL
* SQL
* pgAdmin

Repository Structure

* `ER_drawio.pdf` – ER diagram (conceptual schema design)
* `ERD-Relational_mapping.txt` – ER-to-relational mapping and pre-normalized schema
* `Normalization.txt` – Functional dependencies and 1NF/2NF/3NF/BCNF normalization
* `create_tables.txt` – PostgreSQL DDL for all tables
* `triggers.txt` – PL/pgSQL triggers for business rules
* `Queries.txt` – Sample SQL queries and reports
* `SRS.txt` – Software requirements specification

Sample Queries

* Committee-wise fund allocation from budgets, sponsorships, and ticket revenue
* Most popular ticket types
* Accommodation and room occupancy details
* Event and committee analytics

Author

Dev Diyora
Email: 202403009@dau.ac.in
