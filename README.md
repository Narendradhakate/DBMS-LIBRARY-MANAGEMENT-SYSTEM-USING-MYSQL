# DBMS-LIBRARY-MANAGEMENT-SYSTEM-USING-MYSQL
Database schema for a library management system, including tables for books, authors, publishers, branches, lending records, and book copies. SQL queries provided for retrieving book details, borrower information, data manipulation, partitioning, and creating a view for available book copies.

In this report: 

Database schema:
BOOK (Book_id, Title, Publisher_Name, Pub_Year)
BOOK_AUTHORS (Book_id, Author_Name)
PUBLISHER (Name, Address, Phone)
BOOK_COPIES (Book_id, Branch_id, No-of_Copies)
BOOK_LENDING (Book_id, Branch_id, Card_No, Date_Out, Due_Date)
LIBRARY_BRANCH (Branch_id, Branch_Name, Address)

Write SQL queries to
• Retrieve details of all books in the library – id, title, name of publisher, authors, number
of copies in each branch, etc.
• Get the particulars of borrowers who have borrowed more than 3 books, but from Jan
2017 to Jun2017
• Delete a book in BOOK table. Update the contents of other tables to reflect this data
manipulation operation.
• Partition the BOOK table based on year of publication. Demonstrate its working with a
simple query.
• Create a view of all books and its number of copies that are currently available in the
Library.
