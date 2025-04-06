# Productivity Calculator App 🕒

A simple console-based Java application that allows users to track their daily routine tasks, categorize them, and measure productivity based on time spent.

---

## 📌 Features

- 🔐 User login and registration
- ➕ Add tasks with duration and category
- ✏️ Update existing tasks
- ❌ Delete tasks
- 📋 Display all tasks in a formatted table
- 📊 Calculate and display productive vs non-productive time
- 💾 Persistent user data storage via `.txt` files

---

## 📂 File Structure

├── Task.java ├── README.md └── [username]_Productivity_Calculator.txt (generated per user)

yaml
Copy
Edit

---

## 🚀 How to Run

1. **Compile the program**  
   ```bash
   javac Task.java
Run the application

bash
Copy
Edit
java Task
🧠 Usage Flow
Choose to create a new user or log in as an existing one.

Add a task with a duration and a category (Health, Lifestyle, Miscellaneous).

Continue by updating, deleting, or displaying tasks.

Exit to view a final summary of productive vs non-productive hours.

🛡 Limitations
Max task duration per day is 1440 minutes (24 hours).

User data is stored as plain text without encryption.

Only console interface (no GUI or database integration).

📌 Sample Output
plaintext
Copy
Edit
___________________     PRODUCTIVITY CALCULATOR APP     __________________

|| THIS IS A PLACE WHERE YOU CAN KEEP TRACK OF YOUR DAILY ROUTINE TASKS  ||

Are you a new user? (yes/no): yes
Enter your new username: john
Enter your new password: 1234
* NEW ACCOUNT CREATED! *

BEGIN BY ADDING YOUR FIRST TASK
In which category do you want to add the task?
1. Health
2. Lifestyle
3. Miscellaneous
...

TOTAL TIME: 24 hours 0 minutes
Productive Time: 5 hours 30 minutes
Non-Productive Time: 18 hours 30 minutes
Thank you for using the productivity calculator!
📈 Future Enhancements
GUI using JavaFX or Swing

Cloud-based data storage

Daily/weekly productivity charts

Email summaries or notifications

📄 License
This project is open-source and free to use for educational purposes.

✨ Author
Developed by Satya
