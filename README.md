# MCA-Placement-Management-System
The MCA Placement Management System is a database that manages the full campus placement process for MCA students — from student and company registration through applications, interviews, and final job offers. It tracks which companies visit, which students apply to which drives, and how each application progresses to its outcome.

 Entities

* **STUDENT**
* **PLACEMENT_DRIVE**
* **COMPANY**
* **PLACEMENT_OFFICER**
* **APPLICATION**
* **INTERVIEW**
* **OFFER**

 Relationships

* Students submit applications
* Placement drives receive applications
* Companies post placement drives
* Placement officers manage placement drives
* Applications are scheduled for interviews
* Applications generate offers

 Cardinality

* **STUDENT → APPLICATION** — 1 : N
* **PLACEMENT_DRIVE → APPLICATION** — 1 : N
* **COMPANY → PLACEMENT_DRIVE** — 1 : N
* **PLACEMENT_OFFICER → PLACEMENT_DRIVE** — 1 : N
* **APPLICATION → INTERVIEW** — 1 : N
* **APPLICATION → OFFER** — 1 : 1

Concepts Used

* DBMS
* ER Diagram
* Database Design
* Entity-Relationship Modeling
* Primary Key (PK)
* Foreign Key (FK)
* Cardinality
* One-to-Many Relationship
* One-to-One Relationship

Objective

The objective of this ER model is to represent the relationships between students, companies, placement drives, applications, interviews, and offers in an organized database structure.

ER Diagram

The ER diagram represents all entities, their attributes, primary keys, foreign keys, relationships, and cardinalities of the MCA Placement Management System.
