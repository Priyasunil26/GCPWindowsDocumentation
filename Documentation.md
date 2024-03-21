# Steps to Install and Enable Backup Compatibility of Bold BI on GCP Windows instance

| SEO Details       |                                                                     |
|-------------------|---------------------------------------------------------------------|
| Meta Title        | Installing and Enabling Backup Compatibility for Bold BI on GCP Windows instance |
| Meta Description  | Learn how to install Bold BI on GCP Windows instance and enable backup compatibility with easy-to-follow steps. Ensure data protection and disaster recovery for your Bold BI installation. |

## Below are the steps that will help you to install Bold BI.

### 1. Launch an Windows instance on GCP
   - To create an Windows instance in GCP, refer to this [link](https://cloud.google.com/compute/docs/create-windows-server-vm-instance).

### 2. Setup RDS (Relational Database Service) for PostgreSQL
If you want to set up a PostgreSQL Database on  Windows instance, follow the first step. If you prefer using a managed Database in GCP, follow the second step.

#### a. Setting up PostgreSQL in a Windows instance
- Download the [PostgreSQL installer for Windows](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) and install it.
- For detailed installation steps, refer to this [guide](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/).

**Information:**
  - For installing a MySQL database in a Windows EC2 instance, refer to the steps outlined in this [guide](https://dev.mysql.com/doc/refman/8.3/en/windows-installation.html).
  - To install an MS SQL database in Windows EC2 instance, follow the instructions provided in this [guide](https://learn.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server?view=sql-server-ver16).

#### b. Setting up PostgreSQL Database in GCP
- For instructions on creating a PostgreSQL Database in GCP, please refer to this [link](https://cloud.google.com/sql/docs/postgres/create-instance/). Additionally, you can refer to this [link](https://cloud.google.com/sql/docs/postgres/instance-info) for instance information.


**Information:** 
  - To create a MySQL Database in GCP, you can follow the steps outlined in this [guide](https://cloud.google.com/sql/docs/mysql/create-instance). For information about your instance, refer to this [link](https://cloud.google.com/sql/docs/mysql/instance-info).

  - To create a SQL Database in GCP, refer to this [guide](https://cloud.google.com/sql/docs/sqlserver/create-instance). Additionally, for instance information, you can refer to this [link](https://cloud.google.com/sql/docs/sqlserver/instance-info).
