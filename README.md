# DSA-Project
🚦Police Challan Management System

🧠 Core Data Structures:
o	BST (Binary Search Tree):
o	Used to store and manage vehicle records efficiently.
o	Enables fast insertion, deletion, and searching based on vehicle number plates.
o	Stack:
o	Used to generate and manage traffic challans (tickets) in LIFO (Last In, First Out) order.
o	Ensures the most recent challans are handled first.

💾 File Handling:
o	Ensures persistent data storage for vehicle records, violation logs, and challans.
o	Implements three file structures:
o	Sequential File – For orderly vehicle/violation record storage.
o	Indexed File – For quick lookups of specific data.
o	Stack File – To maintain chronological order of challans.

🔐 Login System:
o	Symmetric Encryption to securely store login credentials.
o	Role-Based Access Control:
o	Admin: Full system access (edit users, manage vehicles and challans).
o	User: Restricted access (add cars, pay challans).

📋 Functional Features:
1.	Add Vehicle: Input vehicle details and insert into BST.
2.	Delete Vehicle: Locate and delete a record using BST operations.
3.	Search Vehicle: Search a specific vehicle using number plate.
4.	View Speed Trap History: Check history of violations for any vehicle.
5.	Generate Challan: Auto-generate challans using stack on violation detection.
6.	View Challans: Access the latest challan first, using stack behavior.
7.	Data Persistence: All changes saved to files to ensure consistency between sessions.

🧑‍💻 User Interface:
o	Menu-driven console UI for easy navigation and functionality access.
o	Designed for both traffic authorities and public users.

📌 Technologies Used:
o	Language: C/C++
o	Data Structures: BST, Stack
o	File Handling: Text/binary file operations
o	Encryption: Symmetric key-based for login details
