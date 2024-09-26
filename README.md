# EcomNexus

EcomNexus is the back end for your e-commerce website! Built with Express.js, this API uses Sequelize to interact with a PostgreSQL database. EcomNexus lets you easily manage products, categories, and tags.

- Connect to your PostgreSQL database by adding your database name, PostgreSQL username, and password to the environment variable file. Sequelize handles the connection for you.

- Set up a development database by running schema and seed commands, which create and populate the database with test data.

- Start your server with a single command. The application will sync the Sequelize models to the PostgreSQL database automatically.

- Access API GET routes for categories, products, or tags in Insomnia to see data displayed in a well-organized JSON format.


## Installation

To install EcomNexus:

- Clone this repository to your machine.

- Navigate to the project directory.

- Open the terminal and install the dependencies by running the command: `npm install`.

- Set up the PostgreSQL database:

  - Enter `psql -U postgres` to open the PostgreSQL command line interface. If prompted, input your password.
  - To set up the database, type `\i schema.sql` and press Enter. Now your database is ready to use!

- Remove '.EXAMPLE' from the .env.EXAMPLE file renaming it to .env.

- Configure that .env file with your database credentials.

- Seed data to your database so that you can test your routes, in the terminal run the command: `npm run seed`.

## Usage

- Start the application, in the terminal run the command: `npm start`.


## Credits

This project was made possible with the help of:

- **Joem Casusi (Tutor)** for guidance and support throughout the development process.

