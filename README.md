

# Chat App using PHP

This repository contains a simple chat app developed using PHP, allowing users to engage in real-time text-based conversations. The app utilizes basic HTML, CSS, and PHP along with a MySQL database to store messages and user information. This README.md provides an overview of the project, setup instructions, and basic usage guidelines.

![Chat App Screenshot](screenshot.png)

## Features

- User registration: Users can create accounts with unique usernames and passwords.
- Real-time chat: Registered users can send and receive messages in real-time.
- Message storage: Messages are stored in a MySQL database for future reference.
- Responsive design: The app is designed to work seamlessly on various screen sizes.

## Requirements

- Web server (e.g., Apache, Nginx)
- PHP 7.0 or higher
- MySQL database
- Modern web browser

## Installation and Setup

1. **Clone the Repository:** Start by cloning this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/chat-app-php.git
   ```

2. **Database Setup:**

   - Create a new MySQL database for the chat app.
   - Import the `database.sql` file provided in the repository to set up the necessary database structure.

3. **Configuration:**

   - Rename the `config-sample.php` file in the `includes` directory to `config.php`.
   - Open `config.php` and provide your MySQL database connection details (host, username, password, database name).

4. **Web Server Configuration:**

   - Ensure that your web server is configured to serve files from the cloned directory.
   - Make sure the server's document root points to the `public` directory of the project.

5. **Start Using the App:**

   - Open a web browser and navigate to your local server's address (e.g., `http://localhost/chat-app-php`).
   - Create an account and start using the chat app!

## Usage

- **Registration:** Users can sign up with unique usernames and passwords.
- **Login:** Registered users can log in using their credentials.
- **Chat Interface:** Upon logging in, users will be directed to the chat interface, where they can view and send messages in real time.
- **Sending Messages:** Type your message in the input field and press Enter to send it.
- **Viewing Messages:** The chat interface displays previous messages and new messages in real time.
- **Logout:** Users can log out by clicking the "Logout" button.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork: `git push origin feature-name`.
5. Create a pull request to the `main` branch of the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

---

