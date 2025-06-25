# Bank-Management-System
A Python CLI application simulating core banking operations with secure user authentication, account management, financial transactions (deposits, withdrawals, transfers), transaction history, and an admin panel for oversight.

Key Features:
• User registration, login, and password hashing.
• Create and manage multiple savings/checking accounts.
• Perform deposits, withdrawals, and inter-account transfers.
• View detailed transaction history.
• Admin panel: manage users (activate/deactivate), view all accounts and transactions.

Technologies Used:
• Python 3.x
• SQLAlchemy (ORM)
• SQLite (Database)
• bcrypt (Password Hashing)

File Structure:
• main.py → Main entry point handling CLI interactions, routing, and overall app control.
• auth.py → Handles registration, login, password hashing, and role management.
• bank_operations.py → Contains deposit, withdrawal, transfer, and transaction logic.
• admin_operations.py → Admin functionalities like user management and system audit.
• database.py → Sets up SQLite database models and session logic using SQLAlchemy.
• cli_app.py (optional) → CLI-specific logic (if implemented).
• urls.db → SQLite database file.

How to Run:
Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

Create and activate a virtual environment
python -m venv .venv
• Windows: ..venv\Scripts\activate
• macOS/Linux: source ./.venv/bin/activate

Install dependencies
pip install sqlalchemy bcrypt

Run the application
python main.py

Future Enhancements:

• GUI version using Tkinter or web interface with Flask/Django
• Two-Factor Authentication (2FA) for enhanced login security
• Password reset and account recovery
• Analytics and reports for users and admins
• Migration to PostgreSQL for production-level use
• Full unit test coverage and CI pipeline integration
