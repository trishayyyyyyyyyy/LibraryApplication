This is a c# object oriented programming library application which allows the users to save, edit, 
delete and search for Paper books, e-books, and audiobook. this is only the
design  adding functionality.
The project contains 3 different books: Paper Book, E-book and Audio book. 
Each type will have 4 common and 2 unique properties. The common 
properties are title, author, category and type. The unique properties are:
• Paper book: ISBN, Number of pages.
• E-Book: Format, File size
• Audio Book: Narrator, Duration
Since each class have 4 common properties, i used inheritance.
There is also a library class that add the books to our list and write them on 
the file. Also, this class will read all books from file and make object from each 
line. The way that the application creates objects is reading a line and check 
what type of the book it is. Depending on the type, it will create the object 
which is needed. For instance, if the type is e-book, it will create the e-book 
object and add it to the list of books. All books will be added to ONLY 1 FILE.
In add menu, the user writing the basic data of the book (the common 
properties) and then choose the type of the book. When type is chosen, the 
corresponding group box will be enabled and user can enter the data. You can 
see the example in the images.
