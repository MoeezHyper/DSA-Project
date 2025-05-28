# DSA-Project
🚦Police Challan Management System

🧠 Core Data Structures:
1. BST (Binary Search Tree):
•	Used to store and manage vehicle records efficiently.
•	Enables fast insertion, deletion, and searching based on vehicle number plates.

3. Stack:
•Used to generate and manage traffic challans (tickets) in LIFO (Last In, First Out) order.
•Ensures the most recent challans are handled first.

💾 File Handling:
•	Ensures persistent data storage for vehicle records, violation logs, and challans.
•	Implements three file structures:
•	Sequential File – For orderly vehicle/violation record storage.
•	Indexed File – For quick lookups of specific data.
•	Stack File – To maintain chronological order of challans.

🔐 Login System:
•	Symmetric Encryption to securely store login credentials.
•	Role-Based Access Control:
•	Admin: Full system access (edit users, manage vehicles and challans).
•	User: Restricted access (add cars, pay challans).

📋 Functional Features:
1.	Add Vehicle: Input vehicle details and insert into BST.
2.	Delete Vehicle: Locate and delete a record using BST operations.
3.	Search Vehicle: Search a specific vehicle using number plate.
4.	View Speed Trap History: Check history of violations for any vehicle.
5.	Generate Challan: Auto-generate challans using stack on violation detection.
6.	View Challans: Access the latest challan first, using stack behavior.
7.	Data Persistence: All changes saved to files to ensure consistency between sessions.

🧑‍💻 User Interface:
•	Menu-driven console UI for easy navigation and functionality access.
•	Designed for both traffic authorities and public users.

📌 Technologies Used:
•	Language: C/C++
•	Data Structures: BST, Stack
•	File Handling: Text/binary file operations
•	Encryption: Symmetric key-based for login details
