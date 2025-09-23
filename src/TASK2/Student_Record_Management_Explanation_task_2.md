Student Record Management System - Explanation

This is a Student Record Management System made in Java. It is a CLI-based CRUD system. CRUD means Create, Read, Update, and Delete — the four main operations we do with data.

1. I first created a Student class.
   - It has three fields: id, name, and marks.
   - I also added methods (getters & setters) to read and update the values.
   - I wrote a toString() method so that when I print a student, it shows the details nicely.

2. To store all the students, I used an ArrayList.
   - An ArrayList is better than arrays because its size can change when we add or remove students.

3. In the main class (StudentManagementSystem), I made a menu-driven program using a do-while loop.
   - The user gets choices like Add, View, Update, Delete, and Exit.
   - I used a Scanner to take input from the user.

4. For each option:
   - Add: The program asks for ID, name, and marks. Then it creates a new Student object and adds it to the ArrayList.
   - View: It prints all students from the ArrayList.
   - Update: The user enters an ID. If that student is found, we ask for new name and marks, and update them.
   - Delete: The user enters an ID. If found, we remove that student from the ArrayList.
   - Exit: Ends the program.

5. The outcome of this program is that I can manage student records directly from the terminal, just like a small database system, but in memory. It also helps me practice using classes, objects, and ArrayList in Java.

In short:
"This program lets me add, view, update, and delete student records using a menu. I used a Student class for data, an ArrayList to store records, and simple functions for CRUD operations."
