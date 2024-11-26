# Print Bill Master Database

The PBM database is a MySQL database that stores all information used in the application. The default script is contained in the file `init.sql`. The database is created with the name `PBM_Database`. The database contains the following tables:

![Schema](/assets/images/PBM_Database.png)

## Getting Started

### Configure the Database

You can configure the database connection by updating the `.env` file located in the `PBM-Database` directory. Modify the following variables:

- `MYSQL_USER`
- `MYSQL_PASSWORD`
