My Bank App
My Bank App is a simple React application that allows users to view a list of their recent bank transactions and perform basic operations such as adding new transactions and filtering transactions by description.

Features
View a table of all transactions with date, category, description, and amount.
Add new transactions using a form.
Filter transactions by typing into the search bar. Only transactions with descriptions matching the search term will be shown in the table.
Project Setup
To set up the project, follow these steps:

Clone the repository to your local machine.
Install the required dependencies by running npm install.
Create a db.json file and populate it with transaction data. The format of the JSON data should be an array of objects, where each object represents a transaction with properties like date, category, description, and amount.
Run the JSON server by executing json-server --watch db.json. The server will provide the data for the application to fetch and display.
How to Run
To run the application, use the command npm start. This will start the development server, and the app will be accessible at http://localhost:3000 in your web browser.

Usage
Upon launching the app, you will see a table displaying all your transactions. You can use the search bar to filter transactions by description, and the table will update in real-time as you type.

To add a new transaction, simply fill out the form with the appropriate date, category, description, and amount, and click the "Add Transaction" button. The new transaction will be added to the table instantly without the need to persist it to the backend.

To delete a transaction, click the "Delete" button in the corresponding row, and the transaction will be removed from the table.

Dependencies
This project uses the following dependencies:

React: A JavaScript library for building user interfaces.
Axios: A popular library for making HTTP requests.
JSON Server: A tool to create a fake REST API for development and testing purposes.
React Loader Spinner: A library for displaying loading spinners.
Tests
To run the tests, use the command npm test. The tests ensure that the components are rendering correctly and that basic functionality is working as expected.

Contributing
Contributions to this project are welcome! If you find any bugs or have ideas for improvements, please feel free to open an issue or submit a pull request.