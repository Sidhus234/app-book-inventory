<h1>Book Inventory App</h1>

Program to maintain a book inventory. Here we use Tkinter for GUI and postgresql to maintain the database. We will also generate an executable file for both windows and mac for other users (who donot have python or sqllite on their system) to use it.

Some of the key functionailities allowed are:
1. Find a book from the database.
2. Add a new book record.
3. Update an entry.
4. Delete an entry.
5. View all records
6. Close the program

Key areas of the project are:
1. Backend: [sqlite](https://www.sqlite.org/index.html) code to maintain the database
2. Frontend: GUI using [Tkinter](https://docs.python.org/3/library/tk.html) library

<h1>How to make executable file using pyinstaller</h1>
1. Install pyinstaller
2. Run command pyinstaller main.py (This will generate multiple files.)
3. Instead run pyinstaller --onefile main.py (This will generate one executable file)

