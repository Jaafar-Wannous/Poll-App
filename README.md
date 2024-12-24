# Poll Application

A Laravel-based Poll Application designed to create and manage polls dynamically using **Livewire**. This project highlights the power of PHP-driven interactivity without relying on JavaScript frameworks.

## Features

### 1. **Poll Creation**
   - Create polls dynamically without page refreshes.
   - Add a title for the poll with real-time validation (e.g., ensuring the title is long enough).
   - Add multiple options to the poll, such as:
     - Yes
     - No
     - Maybe
   - Avoid duplicate entries with robust validation.

### 2. **Live Updates**
   - Experience seamless interactivity powered by Livewire.
   - Polls are auto-updated without requiring a page reload.

### 3. **Voting System**
   - Vote on different poll options instantly.
   - See immediate updates to poll results dynamically.

### 4. **Multiple Polls**
   - Create and manage multiple polls.
   - Easily add, edit, or remove polls.

## Technologies Used

- **Laravel**: Backend framework for application logic and database handling.
- **Livewire**: For building dynamic components with PHP.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/poll-application.git
   ```

2. Navigate to the project directory:
   ```bash
   cd poll-application
   ```

3. Install dependencies:
   ```bash
   composer install
   npm install
   npm run dev
   ```

4. Set up the environment:
   - Create a `.env` file and configure your database connection.
   - Run migrations:
     ```bash
     php artisan migrate
     ```

5. Serve the application:
   ```bash
   php artisan serve
   ```
   Access the application at `http://localhost:8000`.

## Future Enhancements

- Add user authentication to limit poll creation and voting to registered users.
- Include poll expiration dates.
- Implement advanced statistics for polls (e.g., percentage of votes for each option).
- Allow users to edit existing polls.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for discussion.

## License
This project is open-source and available under the [MIT License](LICENSE).

