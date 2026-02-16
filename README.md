# oracle_pdb_ass_II_29198_kevin

# Oracle Pluggable Database Assignment II

**Course:** Database Development with PL/SQL (INSY 8311)  
**Student Name:** Kevin Gatete    
**Student ID:** 29198  
**Assignment Date:** February 9, 2026  
**Submission Date:** February 16, 2026

---

## Overview

This assignment demonstrates practical understanding of Oracle Multitenant Architecture, focusing on:
- Creation and management of Pluggable Databases (PDBs)
- User creation and management within PDBs
- PDB deletion and cleanup operations
- Oracle Enterprise Manager (OEM) configuration and usage
- Professional technical documentation practices

---

## Oracle Environment

- **Oracle Database Version:** Oracle 21c
- **Operating System:** Windows 10
- **Container Database (CDB):** EX
- **Oracle Enterprise Manager:** Single Instance.

---

## Task 1: Create a New Pluggable Database

### Objective
Create a permanent Pluggable Database (PDB) with a dedicated user account for future coursework.

### Naming Conventions Used
- **PDB Name:** `ke_pdb_29198`
- **Username:** `kevin_plsqlauca_29198`
- **Password:** [Secure password set]

### Steps Performed
1. Connected to the Container Database (CDB) as SYSDBA
2. Created the pluggable database using the CREATE PLUGGABLE DATABASE command
3. Opened the PDB in READ WRITE mode
4. Connected to the newly created PDB
5. Created the user account with necessary privileges
6. Granted required permissions (CONNECT, RESOURCE, DBA if needed)

### Evidence
- See screenshot: `screenshots/task1_pdb_creation.png`
- See screenshot: `screenshots/task1_pdb_open_state.png`
- See screenshot: `screenshots/task1_user_creation.png`

---

## Task 2: Create and Delete a PDB

### Objective
Demonstrate the ability to create and completely remove a temporary PDB.

### Naming Convention Used
- **Temporary PDB Name:** `ke_to_delete_pdb_29198`

### Steps Performed
1. Created the temporary pluggable database
2. Verified the PDB exists using `SHOW PDBS` or querying `V$PDBS`
3. Closed the PDB
4. Dropped the PDB including datafiles using the `DROP PLUGGABLE DATABASE` command
5. Confirmed successful deletion by verifying the PDB no longer appears in the list

### Evidence
- See screenshot: `screenshots/task2_temp_pdb_creation.png`
- See screenshot: `screenshots/task2_pdb_verification.png`
- See screenshot: `screenshots/task2_pdb_deletion.png`
- See screenshot: `screenshots/task2_deletion_confirmation.png`

---

## Task 3: Oracle Enterprise Manager (OEM)

### Objective
Configure and access Oracle Enterprise Manager to monitor the Oracle environment and completed tasks.

### Steps Performed
1. Started OEM service/process
2. Accessed OEM web interface via browser
3. Logged in with appropriate credentials
4. Navigated to the database overview dashboard
5. Verified PDB configurations and status

### Evidence
- See screenshot: `screenshots/task3_oem_dashboard.png`

---

## Task 4: Documentation & Reporting

### Repository Information
- **Repository Name:** `oracle_pdb_ass_II_29198_kevin`
- **Visibility:** PUBLIC
- **Repository URL:** 


*Note: If no challenges were encountered, state: "No significant challenges were encountered during this assignment."*

---

## Key Learnings

- Understanding of Oracle Multitenant Architecture
- Practical experience with PDB lifecycle management
- User administration within pluggable databases
- Database monitoring using Oracle Enterprise Manager
- Professional technical documentation practices

---

## Integrity Statement

I, Kevin (Student ID: 29198), declare that:
- All work submitted is my own and completed individually
- No AI tools (ChatGPT or similar) were used to generate commands or solutions
- No screenshots, commands, or repositories were copied from classmates
- All screenshots are authentic and taken from my own Oracle environment
- I have followed all academic integrity guidelines as outlined in the assignment

---

## Contact Information

**Student:** Kevin  
**Student ID:** 29198   
**Instructor:** Eric Maniraguha | eric.maniraguha@auca.ac.rw

---

*"Excellence is never an accident; it is the result of discipline, commitment, and integrity."*
