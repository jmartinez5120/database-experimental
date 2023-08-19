# Database Experimental
This repository is intended to perform experiment on a series of diverse databases SQL/NOSQL. 


## #1 - Oracle Replication using GoldenGate (Oracle to Oracle | MongoDB to Oracle)

### Demo Steps 
1. Create the main Oracle Database in Primary Server.
2. Create another Oracle database in a Secondary Server.
3. Create a MongoDB database in the existing Secondary Server.
4. Populate dummy data into both primary and secondary databases.
5. Setup the GoldenGate replication service reading mutations from the Secondary Server (Oracle and MongoDB) and Upserting/transforming into the primary database.
6. Create a small Spring API to demostrate mutations from Secondary Database to Priumary, from both Oracle Secondary and MongoDB.
7. Record statistics.
8. Create a batch job that will insert millions of mutations into both Oracle and MongoDB and capture the replication to primary Oracle.

### TODOS:
  * Setup both servers with Linux and prepare for database installation. 
  * Re-search on setting up GoldenGate.
  * Prepare architecture diagrams for the functionality.
  * Document the setup of GoldenGate and also the transformation from one database to another.
  * Document both designs of Primary and Secondary server.

