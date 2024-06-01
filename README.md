# Portfolio-Managing-Web-App
Developed and deployed a Portfolio Management System using MySQL, and HTML/CSS, enabling users to analyze portfolio performance, generate custom financial reports, and optimize investment strategies.

### Prerequisites
* Python 3.x installed
* MySQL or any other SQL database installed
* Required Python packages (listed in requirements.txt)

### Setup Guide
#### Step 1: Configure the db.yaml File
The `db.yaml` file contains the database configuration. Update this file with your database credentials.

Example `db.yaml` file:
```yaml
mysql_host: 'localhost'
mysql_user: 'root'
mysql_password: 'your_db_password'
mysql_db: 'portfolio'
secret_key: 'portnepseokay123'

mysql_host_server: 'sql6.freemysqlhosting.net'
mysql_user_server: 'sql6427353'
mysql_password_server: 'wZn9nL2Uat'
mysql_db_server: 'sql6427353'
```
Replace the placeholders with your actual database details.

#### Step 2: Run `query.sql`
The `query.sql` file contains the SQL queries needed to set up your database schema. Run this file to create the necessary tables and insert initial data.

`mysql -u root -p portfolio < query.sql`

#### Step 3: Run `main.py`
Ensure you have installed all required Python packages by running:
`pip install -r requirements.txt`

Run the main application:
`python main.py`

This will start the application, and you can begin using the portfolio management system.

#### Additional Information
* Ensure that your database server is running before starting the application.
* If you encounter any issues, check the database connection details in the db.yaml file and ensure they are correct.
* For any additional configuration or setup options, refer to the comments and documentation within the code files.