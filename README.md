# Gym Management System

## Overview

The Gym Management System is a Flask-based web application designed to help gym owners efficiently manage their gym operations. Key features include tracking attendance, managing memberships, and monitoring payment deadlines and enrollment dates. The application uses session management for user authentication.

## Features

- **User Authentication**: Secure login and session management.
- **Attendance Tracking**: Record and track gym member attendance.
- **Membership Management**: Add, update, and view membership details.
- **Payment Deadlines**: Monitor and track payment deadlines.
- **Enrollment Dates**: View and manage member enrollment dates.

## Prerequisites

Before you get started, ensure you have the following installed:

- Python 3.6 or higher
- Flask
- SQLAlchemy (or another database ORM)
- SQLite (or another database of your choice)

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/gym-management-system.git
    cd gym-management-system
    ```

2. **Create and activate a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database**:

    Initialize the database schema by running:

    ```bash
    python create_db.py
    ```

5. **Run the application**:

    ```bash
    python app.py
    ```

    The application will be available at `http://127.0.0.1:5000/`.

## Usage

1. **Access the application**: Open your web browser and navigate to `http://127.0.0.1:5000/`.

2. **Login**: Use the provided login form to access the system.

3. **Manage Members**:
   - **Attendance**: Record and view attendance details.
   - **Membership**: Add, update, and view membership information.

4. **Check Deadlines**:
   - **Payments**: View upcoming payment deadlines.
   - **Enrollments**: Monitor enrollment dates.

## Configuration

The application configuration can be adjusted in the following files:

- **`config.py`**: Contains Flask settings and configuration options.
- **Environment Variables**: Set variables like `DATABASE_URI` for your database connection.

## Contributing

We welcome contributions to this project. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to [your.email@example.com](mailto:your.email@example.com).
