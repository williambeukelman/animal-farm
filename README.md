# Animal Farm

Animal Farm is a Flask-based web application for creating and participating in forum discussions. Feel free to contribute to isses!

https://urchin-app-ihlrx.ondigitalocean.app/

## Features

- User registration and login system
- Posting and replying to threads
- Thread pagination
- Content character limit
- Cooldown period between posts

## Installation

1. Clone the repository:

```
git clone <repository-url>
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Set up the database:
- Create a SQLite database file named `users.db`.
- Run the database migration script to create the necessary tables:
```
python migration.py
```

4. Run the application:
  ```
  python app.py
  ```
## Usage

1. Access the application by visiting [http://localhost:5000](http://localhost:5000) in your web browser.

2. Register a new account or log in with existing credentials.

3. Explore the forum, view threads, and participate in discussions by creating new posts or replying to existing ones.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

