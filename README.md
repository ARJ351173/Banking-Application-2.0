# Banking-Application-2.0
⸻

💳 ATM Management System in Java

This is a Java-based GUI application simulating an ATM system. It allows users to create an account, log in, and perform typical ATM transactions such as withdrawals, deposits, balance inquiries, and mini statements.

⸻

📁 Project Structure
	•	main_Class.java: Entry point that launches the login screen.
	•	login.java: Handles user login with PIN verification.
	•	Signup.java / Signup2.java / Signup3.java: Multi-step form to register a new user with personal, contact, and account details.
	•	Pin.java: Confirms PIN setup during sign-up.
	•	Deposit.java: Handles cash deposit transactions.
	•	Withdrawl.java: Handles cash withdrawal transactions.
	•	FastCash.java: Provides quick withdrawal options with predefined amounts.
	•	BalanceEnquriy.java: Displays current account balance.
	•	mini.java: Shows a mini statement of recent transactions.
	•	Con.java: Establishes JDBC connection with the database.

⸻

💻 Technologies Used
	•	Java (Swing for GUI)
	•	JDBC (Java Database Connectivity)
	•	MySQL (for data persistence)

⸻

⚙️ Setup Instructions
	1.	Clone the Repository

git clone https://github.com/your-username/ATM-Management-System.git
cd ATM-Management-System


	2.	Open in IntelliJ / Eclipse
	•	Import the project as a Java project.
	•	Ensure your MySQL server is running.
	3.	Database Setup
	•	Create a database (e.g., atmdb) in MySQL.
	•	Create required tables like login, signup, transaction, etc.
	•	Update database credentials in Con.java accordingly.
	4.	Run the Project
	•	Run main_Class.java to start the application.

⸻

🧪 Features
	•	🔐 Login/Signup: Secure user authentication with PIN.
	•	💰 Deposit/Withdraw: Allows adding or withdrawing money.
	•	⚡ Fast Cash: One-click quick withdrawals.
	•	🧾 Mini Statement: Displays transaction history.
	•	🧮 Balance Inquiry: View current balance.
	•	🎨 Swing GUI: Clean and user-friendly interface.

⸻

📜 License

This project is open-source and available under the MIT License.

⸻
