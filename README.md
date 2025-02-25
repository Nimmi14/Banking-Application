It is a console-based banking application developed using Python and MySQL. Python was used extensively to structure the application into modular components for better maintainability and scalability.
The core functionalities, such as user authentication, banking transactions, and security measures, were implemented using Python’s object-oriented programming (OOP) principles.
The application starts with an ASCII banner displayed using Python’s print functions. The main menu system is built using a loop that processes user inputs efficiently.
Account registration includes input validation functions for email and mobile numbers, ensuring data integrity before storing details in the MySQL database through Python’s MySQL connector library. 
Email-based OTP verification is handled using the smtplib module to enhance security.
For login authentication, passwords are securely hashed using Python’s hashlib module with added salt for encryption. Banking functionalities such as balance checking, deposits, withdrawals, 
and money transfers are structured into service modules, following a clean architecture approach. Python also manages transaction history, recording and retrieving data efficiently.
Security measures like login attempt tracking and timed resets utilize Python’s threading and time-based operations.
The application gracefully exits with a farewell banner, ensuring a smooth user experience.
