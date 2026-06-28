# Oracle PDB Assignment 2 - Oracle Multitenant Architecture and PDB Management

## Student Submission Information

**Full Name:**
James Kalenzi

**Student ID:**
32606

**Group:**
[Enter your group]

**GitHub Repository Link:**
[Paste your public GitHub repository link]

**Created PDB Name:**

```text
ja_pdb_32606
```

**Created Username:**

```text
james_plsqlauca_32606
```

**Issues Encountered:**
Yes

---

# . Assignment Overview

This assignment focuses on the practical implementation of Oracle Multitenant Architecture and Pluggable Database (PDB) management. The main objective was to gain hands-on experience in creating and managing Oracle Pluggable Databases, creating database users inside a PDB, assigning privileges, configuring Oracle Enterprise Manager (OEM), and documenting database administration activities professionally using GitHub.

The assignment demonstrates practical Oracle Database Administration skills including PDB creation, user management, PDB lifecycle management, database security, and Oracle environment monitoring.

---

# . Oracle Environment

## Oracle Version Used

* Oracle Database 21c Express Edition
* Version: 21.3.0.0.0

## Operating System / Environment

* Microsoft Windows 10 (64-bit)
* Oracle Database XE environment

## Tools Used

* SQL*Plus for executing Oracle SQL and database administration commands
* Oracle Enterprise Manager Database Express (OEM) for database monitoring
* Command Prompt for Oracle database connections
* GitHub for documentation and screenshot management

---

# . Task Documentation

## Task 1: PDB Creation and User Configuration

### PDB Creation Process

A personal Pluggable Database was created inside the Oracle Container Database (CDB) using the required naming convention.

Created PDB:

```text
ja_pdb_32606
```

The PDB creation process involved:

1. Connecting to Oracle Database using SYSDBA privileges.
2. Creating the new Pluggable Database inside the Container Database.
3. Opening the PDB.
4. Verifying that the PDB was successfully created and available.

The created PDB was successfully opened and verified using Oracle SQL commands.

---

## User Creation Process

After creating the PDB, a database user was created inside the new Pluggable Database.

Created Username:

```text
james_plsqlauca_32606
```

The user creation process involved:

1. Switching the Oracle session into the created PDB.
2. Creating the user account with a password.
3. Granting required privileges.
4. Configuring user access permissions.
5. Testing successful login using the created user account.

The user was successfully created and verified inside the PDB.

---

# Task 2: Temporary PDB Creation and Deletion

A temporary Pluggable Database was created to demonstrate PDB lifecycle management.

The process involved:

1. Creating a temporary PDB using the required naming convention.
2. Verifying the existence of the temporary PDB.
3. Opening the temporary PDB.
4. Deleting the temporary PDB completely.
5. Confirming that the temporary PDB was removed successfully.

This demonstrated practical understanding of Oracle PDB creation, management, and deletion.

---

# : Oracle Enterprise Manager (OEM) Configuration

Oracle Enterprise Manager Database Express was successfully accessed and configured.

The OEM process involved:

1. Accessing OEM through a web browser.
2. Logging in using SYSDBA credentials.
3. Viewing database instance information.
4. Checking created PDB information.
5. Monitoring the Oracle database environment.

The OEM dashboard displayed:

* Oracle Database version
* Database instance status
* Platform information
* Created PDB details

---

# . Challenges and Solutions

## ORA-01031: Insufficient Privileges

**Problem:**
The PDB open command failed because the session did not have sufficient privileges.

**Solution:**
The issue was solved by reconnecting using SYSDBA privileges and executing commands from the correct Oracle container.

---

## ORA-00959: Tablespace Does Not Exist

**Problem:**
User quota configuration failed because the USERS tablespace was not available.

**Solution:**
A USERS tablespace was created and the required quota was assigned to the user.

---

---

**Short Reflection:**

This assignment provided practical experience in Oracle Database Administration, especially in creating and managing Pluggable Databases, configuring users, assigning privileges, and accessing Oracle Enterprise Manager. I improved my understanding of Oracle Multitenant Architecture and gained experience troubleshooting database errors and documenting technical work professionally using GitHub.

# 5. Lessons Learned

Through this assignment, I gained practical skills in:

* Understanding Oracle Multitenant Architecture.
* Creating and managing Pluggable Databases.
* Creating users inside PDB environments.
* Granting database privileges.


This practical work improved my understanding of Oracle Database Administration concepts and real-world database management processes.

---

# 6. Integrity Statement

I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged.
