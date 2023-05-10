# api-create-project
This Flask application provides an API for managing a cafe database. The application stores cafe data using a SQLite database. The application has the following routes:

  /random: Returns random information about a cafe.
  /all: Retrieves a list of all cafes.
  /search: Retrieves information about a cafe located at a specific location.
  /add: Adds a new cafe to the database.
  /update-price/<cafe_id>: Updates the price of a specific cafe.
  /report-closed/<cafe_id>: Deletes a specific cafe from the database.
This Flask application interacts with the database using SQLAlchemy to perform database operations. It uses the jsonify function to generate JSON responses and renders HTML templates to display web pages.

To run this code, you need to install the Flask and SQLAlchemy libraries. Then, you can start the application by using the app.run(debug=True, use_reloader=False) statement.

The application runs on http://localhost:5000. You can perform the respective operations by sending HTTP requests to the /random, /all, /search, /add, /update-price/<cafe_id>, and /report-closed/<cafe_id> routes.

##
My main learning objective in this application was to create my own API using Postman, manipulate variables, and understand the basics of API functionality
