# Student Management System
• This is a simple desktop application built with Python, PyQt6, and SQLite that allows you to manage student records. It provides a graphical user interface (GUI) where you can add, edit, search, and delete students from a local database.
<br><br>

# Features
### View Students
• Displays all student records (ID, Name, Course, Mobile) in a table.<br><br>
<img width="560" height="530" alt="image" src="https://github.com/user-attachments/assets/ae074001-db29-459e-98fa-55e95288aeb3" /><br>
<br><br>
### Add Student
• Opens a dialog where you can enter a new student’s details (name, course, and mobile number) and insert them into the database.<br><br>
<img width="380" height="422" alt="image" src="https://github.com/user-attachments/assets/b820446a-593f-4141-8fe0-ee6f20f97f4b" /><br>
<br><br>
### Edit Student
• Allows you to select a row from the table and update the student’s information (name, course, or mobile).<br><br>
<img width="382" height="418" alt="image" src="https://github.com/user-attachments/assets/b601e2d1-3601-485c-a33e-0a0320ece1e4" /><br>
<br><br>
### Delete Student
• Prompts for confirmation before deleting the selected student from the database.<br><br>
<img width="377" height="162" alt="image" src="https://github.com/user-attachments/assets/ea03aeec-a677-49cd-9b60-ac5e045da520" /><br>
<br><br>
### Search Student
• Opens a search dialog where you can find a student by name and highlight the result in the table.<br><br>
<img width="478" height="422" alt="image" src="https://github.com/user-attachments/assets/075dba99-47d6-412f-9bd3-2d1827fd1215" /><br>
<br><br>
### Toolbar & Menu Integration
• Common actions (Add, Search, Edit, Delete) are available both in the menu bar and toolbar.<br><br>
<img width="413" height="135" alt="image" src="https://github.com/user-attachments/assets/76761045-8d83-4b8c-8d97-9726ee92c6ad" /><br>
<img width="481" height="186" alt="image" src="https://github.com/user-attachments/assets/691f143e-74ae-4090-a2d9-7328b8148030" /><br>
<br><br>
### Status Bar Actions
• When a row is selected, “Edit Record” and “Delete Record” buttons appear in the status bar for quick access.<br><br>
<img width="587" height="303" alt="image" src="https://github.com/user-attachments/assets/fd691bfa-0fdb-46bb-ba18-60afb118c781" />
<br><br>
# Tech Stack
• <b>Python 3</b><br>
• <b>PyQt6</b> → for the GUI<br>
• <b>SQLite3</b> → for local database storage<br>
<br><br>
# Project Structure
• <b>MainWindow</b> → The main application window with menus, toolbar, table, and status bar.<br>
• <b>InsertDialog</b> → Dialog for registering a new student.<br>
• <b>EditDialog</b> → Dialog for updating an existing student’s information.<br>
• <b>DeleteDialog</b> → Confirmation dialog to delete a student.<br>
• <b>SearchDialog</b> → Dialog for finding and highlighting a student.<br>
• <b>database.db</b> → SQLite database containing a students table.<br>
