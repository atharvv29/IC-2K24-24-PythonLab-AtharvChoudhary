
# Python Dictionary: Part A (Programs)

## 📌 About This Project

This repository holds five Python programs that put dictionaries to practical use. Together they cover nested dictionaries, comprehensions, aggregation, searching, sorting, and input validation. Each program tackles a real-world scenario and follows the assignment's requirements.

## 🎯 Learning Goals

- Work confidently with dictionaries and nested dictionaries.
- Carry out CRUD operations (create, read, update, delete) on stored data.
- Use methods like `.get()`, `.setdefault()`, and `.update()` effectively.
- Apply dictionary and list comprehensions to transform data.
- Group, filter, sort, and aggregate records.
- Validate input and handle invalid actions without crashing.
- Produce summary reports from stored data.

## 📂 What's Inside

### Q1. Student Database

**Key concepts:** nested dictionaries, validation, comprehensions, reporting.

What it does:
- Lets you add, modify, remove, and look up student records.
- Stores each student's name along with subject-wise marks.
- Blocks duplicate roll numbers.
- Accepts only marks between 0 and 100.
- Computes every student's average.
- Finds the overall topper and the top scorer in each subject.
- Lists students who scored under 40 in any subject.
- Sorts students into grade groups: A, B, C, D, and F.

### Q2. Employee Database

**Key concepts:** dictionary operations, grouping, aggregation, sorting, comprehensions.

What it does:
- Supports adding, deleting, and searching employees, plus salary updates.
- Reports payroll totals and headcount per department.
- Finds the top earner in each department.
- Ranks employees by salary, highest first.
- Builds a new dictionary giving a 10% raise to anyone earning under ₹50,000.
- Determines which department has the highest average salary.
- Shows a clear message when the requested employee isn't found.

### Q3. Library Record System

**Key concepts:** nested dictionaries, lists, state tracking, validation.

What it does:
- Adds new books and increases the copy count when an ISBN already exists.
- Handles issuing and returning of books.
- Keeps track of which members currently hold each book.
- Checks availability and caps each member at two books.
- Stops duplicate issues and invalid returns.
- Provides book search and library-wide reports.
- Finds books by author, books with no copies left, books never issued, and members holding more than one book.

### Q4. Word Frequency Counter

**Key concepts:** string processing, dictionaries as counters, sorting, comprehensions.

What it does:
- Takes a paragraph as input.
- Lowercases the text and strips punctuation.
- Counts word occurrences using `.get()`.
- Shows the top N words, resolving ties alphabetically.
- Lists words that appear only once.
- Inverts the frequency dictionary.
- Groups unique words by their length.
- Searches for a word safely, even if it isn't present.
- Deals with empty input gracefully.

### Q5. Phone Directory

**Key concepts:** dictionaries with list values, reverse lookup, validation, grouping.

What it does:
- Adds and removes contacts.
- Attaches additional phone numbers to an existing contact.
- Updates email addresses and cities.
- Requires phone numbers to be exactly 10 digits.
- Rejects phone numbers already used by another contact.
- Searches names by partial match, ignoring case.
- Builds a reverse lookup from phone number to contact.
- Groups contacts by city.
- Finds contacts who have multiple numbers.
- Prints the directory in alphabetical order.

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Data structures:** dictionaries, nested dictionaries, lists
- **Skills practiced:** dictionary methods, comprehensions, loops, conditionals, functions, sorting, input validation

## ▶️ Running the Programs

1. Make sure Python 3.x is installed.
2. Open the project folder in VS Code or any editor you like.
3. Save each program as a separate `.py` file.
4. Open a terminal in the project folder.
5. Run a program with:

   ```bash
   python filename.py
   ```

   Swap `filename.py` for the name of the file you want to run.

## 🧪 Suggested Test Cases

Try each program with:
- Both valid and invalid inputs.
- Duplicate student IDs, employee IDs, ISBNs, and phone numbers.
- Records that don't exist during search, update, or delete.
- Edge values such as marks of exactly 0 and 100.
- Library issue and return rule violations.
- Empty paragraphs and words that aren't in the text.
- Reports generated from the provided sample data.

## 📚 What You'll Gain

By working through these programs, you will be able to:

1. Build and manipulate nested dictionary structures.
2. Create menu-driven applications.
3. Use comprehensions to filter and reshape data.
4. Search records efficiently and generate reports.
5. Enforce rules through input validation.
6. Handle common edge cases without the program crashing.

## 👨‍💻 Author

**Atharv**

---

*Python Dictionary: Part A (Programs) | Practice Assignment*
