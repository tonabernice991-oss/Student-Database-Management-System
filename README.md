# Student-Database-Management-System
The Student Database Management System is a database project designed to manage  student information in an educational institution. Many schools and training centers still rely on manual or poorly organized systems to store  student records, which leads to data duplication, inconsistency, and difficulty in accessing  information.

This project focuses on designing and implementing a relational database using MySQL to 
store, manage, and retrieve student data efficiently

🛠️Tools Used

.MySQL

.SQL (Structured Query Language)

.MySQL Workbench

.GitHub

.ER Diagram Tool (Draw.io or Lucidchart)

👉**Here is an example of a database:**

👾Problem Statement

Educational institutions need a reliable way to store and manage student information such 
as personal details, enrollment data, and academic programs.
Without a structured database system, institutions face challenges such as:

.Duplicate student records

.Difficulty updating student information

.Poor data organization

.Slow retrieval of student details

The goal of this project is to design a well-structured database that solves these problems 
using proper database design principles.

🔐Key terms to know before going deep:

1. Database model:The relational database model is a way of organizing and storing data in a database using tables (also called relations) that consist of rows (tuples or records) and columns (attributes).

2. why it is suitable for managing data:non-relational models might struggle with the dynamic, interconnected nature of student data, leading to inefficiencies in querying or updates whic is why to better use relational.

3.Comparison with other models such as hierarchical and network models: while hierarchical and network models were efficient for specific, predictable access patterns in early computing (e.g., bill-of-materials in manufacturing), they lack the relational model's simplicity and versatility. For student data, which often requires frequent, unpredictable queries and schema evolution, the relational model is far superior, explaining its dominance in modern database systems. If student data involves big data or unstructured elements (e.g., social media feeds), newer NoSQL models like document or graph databases might complement relational ones in hybrid setups.

4. Enties ate "student" and "departments" this means these are the tables will we have in our database. Their relationship is that a certain student enters a certain department in a certain year so we will combine all these."student"and "departments" will have attributes meaning columns.
