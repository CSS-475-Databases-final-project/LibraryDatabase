# LibraryDatabase
A library database created for CSS 475: Database Systems final project. It is for a library system encompassing multiple libraries. It contains an inventory of books. It tracks customers and their books on loan, the books in stock, how many of them are in stock, and where they’re found. It also tracks author information like the books they authored. The data itself is generated from AI, for all attributes of all tables. Similar to KCLS or Sno-Isle, this library system also contains several branches at different locations in the same metro area. 

Link to the library website:
https://paveldatabaseapp.azurewebsites.net/

The aforementioned link contains three pages: 
- Homepage: This page fulfills the first user scenario for searching our database of books. The queries this page uses include Searching by any filter, and finding a location of books, on what shelf in what library.
- Library: This page is where librarians would go to access the database from an administrative side. These pages satisfy the user scenarios of finding all or specific customers with overdue books, and adding a book to the library. The two queries regarding overdue books  are used in the first, and an INSERT statement is used to add books.
- Checkout: This page satisfies the user scenario of wanting to reserve a book to pick up at a certain library. This query checks if a book is available and then INSERTs a tuple to the relation.
