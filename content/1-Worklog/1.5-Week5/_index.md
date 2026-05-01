---
title: "Week 5 Worklog"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Week 5 Objectives:

* Focused on integrating Amazon RDS into the PHP web application and performing necessary configurations to ensure a stable and secure database connection in the cloud environment.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Created an Amazon RDS MySQL instance <br> - Configured database name, username and password <br> - Enable public access for testing purposes                                                                                                   | 06/04/2026 | 06/04/2026      |
| 3   | - Configured inbound rules for MySQL port (3306) <br> - Allowed EC2 instance to connect to RDS                                              | 07/04/2026 | 07/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Exported local MySQL database <br> - Imported data into RDS using MySQL client | 08/04/2026 | 08/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Upload database connection parameters in PHP (host, user, password) <br> - Replaced localhost with RDS endpoint                            | 09/04/2026 | 09/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tested CRUD operations on the application <br> - Identified and fixed connection timeout issues <br> - Checked logs for errors                                                                                     | 10/04/2026 | 10/04/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 5 Achievements:

* Successfully integrated the Amazon RDS database into a PHP application running on Amazon EC2.
* Established a stable connection between EC2 and RDS via endpoint and configured appropriate Security Groups.
* Imported data from the local database to RDS and verified that queries worked correctly.
* Adjusted connection configuration in the PHP source code (hostname, port, username, password, charset).
* Handled common errors such as MySQL version, charset, and connection driver (php-mysqlnd).
* Built a database connection test file to check and debug the system.
* Ensured the application can reliably access and display dynamic data from RDS.
* Understood the process of integrating a cloud database into a real-world web application.
