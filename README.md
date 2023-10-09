# Introduction to SQL Server
#### What is SQL Server
- RDBMS from Microsoft
- *Unmanaged box product* – you are responsible for running it

## SQL Server features:

### SQL Server Editions:
#### Express Edition-
- Max 1.4GB RAM
- 1 socket or 4 cores, whichever is lesser
- No analysis services
- No backup compression
- No integration with Python & R
#### Web Edition
#### Standard Edition-
- Max 128 GB RAM
- 4 sockets or 24 cores
- Only basic integration for Python & R
#### Enterprise Edition
- Unlimited RAM i.e., all the memory that OS can support
- Unlimited CPU
- Full integration of Python & R
- There are 2 subcategories of enterprise edition if needed:
#### Developer Edition
#### Evaluation Edition

### Accessing SQL Server
#### Authentication
You can authenticate a user using the following options:
- SQL Server Authentication
- Active Directory
- Azure Active Directory – Requires Azure Arc-enabled SQL Server 2022
#### Protocols used:
- TCP/IP **(Default port: 1433)**
- Shared memory
- Named pipes

## Disk configuration
SQL Server can in theory, run on a single disk that has all the DBs, SQL Server, OS etc. But in a production environment there a multiple disks that could have one disk for OS + App, one for data, one for logs, one for TempDB etc. that sits on multiple servers. 

## Database consists of 2 main components:
1. Data
2. Logs – Transactional logs. 
