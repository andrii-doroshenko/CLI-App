# CLI-App (Example Command-Line Application using yargs)

This is a simple command-line application (CLI) built using the `yargs` package for easy parsing of command-line arguments. It is a demonstration app that allows processing some arguments passed from the command line and outputting the result to the console or saving it to a file.

## Installation

1. Make sure you have Node.js installed (version 12 and above).

2. Clone the repository or download the zip:
   git clone https://github.com/andrii-doroshenko/CLI-App.git

3. Navigate to the project directory:
   cd CLI-App

4. Install the dependencies:
   npm install

or
yarn install

## Usage

The application supports the following command-line arguments:

# Get and display the entire contact list in the form of a table (console.table)

![node index.js --action list](img/actionList.png)

# Get contact by id - output contact object to console or null if contact with such id does not exist.

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6

# Add a contact and display the created contact in the console

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

# Delete the contact and display the deleted contact in the console or null if the contact with this id does not exist.

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
