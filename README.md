# AP/ITEC 4220: Modern Approaches to Data Management

## Overview
This repository contains project milestones and database implementations completed for **AP/ITEC 4220: Modern Approaches to Data Management (Database Management Systems)**. The project focuses on designing and implementing an advanced **Video Game Store Management System**, progressing from conceptual object-oriented database design to an object-relational Oracle implementation, and concluding with XML document generation and XQuery processing.

---

## Project Milestones & Deliverables

* **`4220-CLASS DIAGRAM.pdf`**  
  Conceptual object-oriented class diagram detailing entity relationships, inheritance hierarchies (`Videogame` and `Accessories` under `Product`), and business associations among customers, accounts, orders, inventory, and suppliers.

* **`ITEC 4220 Milestone 1.docx.pdf`**  
  Initial system requirements and domain analysis for the video game retail platform. Defines business rules, user views (customer and supplier workflows), catalog and inventory tracking specifications, and the foundational class diagram.

* **`ITEC 4220 Milestone #2.docx.pdf`**  
  Object-relational implementation in Oracle SQL. Features custom object types (`customer_t`, `accountorder_t`, `product_t`, etc.), object tables, typed `REF` associations, subtype inheritance, member procedures, and custom `MAP` / `ORDER` comparison methods.

* **`Milestone #3 ITEC 4220.docx.pdf`**  
  Hierarchical data management and semi-structured querying. Covers SQL/XML document generation queries (`XMLELEMENT`, `XMLAGG`, `XMLFOREST`), Oracle XML SQL Utility (XSU) extraction, and native XQuery scripts targeting XML documents stored in the database repository.

---

## Repository Notes
* All milestones include complete Oracle SQL scripts, type definitions, method bodies, XML generation routines, and terminal query execution logs.
* The system was designed and tested against an Oracle object-relational database instance (`studb10g`).
