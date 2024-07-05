# airport-api
Description: RESTful API using Node.js, Express.js, Sequelize ORM, and SQLite to fetch airport information by IATA codes.

Installation:

Clone the repository: git clone <repository-url>
Navigate to project directory: cd airport-api
Install dependencies: npm install
Start the server: npm start
Access the API at http://localhost:3000
Database: SQLite database (alldata.db) with tables:

airport: Stores airport details.
city: Stores city details.
country: Stores country details.
API Endpoints:

Get Airport by IATA Code:
URL: /airport
Method: GET
Parameters: iata_code
Response: Detailed airport information in JSON format.
Dependencies:

express: Web framework for Node.js.
sequelize: Promise-based ORM for Node.js.
sqlite3: SQLite driver for Node.js.
