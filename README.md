Download Link: https://assignmentchef.com/product/solved-cse240-homework5-list-of-books-array-of-structures
<br>
Reading: Textbook Chapter 2, sections 2.5, and 2.6, and lecture slides covered.

Exercising: Complete the multiple choice questions in Textbook Section 2.10. The answers of the questions are available in course Web page.

You are expected to do the majority of the assignment outside the class meetings.   Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board.  However, do not share your answers or code in the course discussion board. Do not cooperate with your peers in doing the individual assignments.

<h1>Programming Assignment</h1>

<ol>

 <li>You are given a partially completed program hw05q1.c. You should follow the instructions given in the program to complete the functions so that the program executes as instructed. The program declares a struct ‘libraryRecord’ with elements for Book Title, Author’s Name, Book Type, Book Id, Aisle number in which the book should be kept. You will be completing a program that creates a list of books (array of structures). It is a menu-driven program where the user is given the following options:</li>

 <li>Add a new book to the list. When adding a new book to the list, the user is prompted for Book Title, Author Name, Book Type, Book Id and Aisle number of the book. The book should be added at the end of the list. If the book (name or ID) already exists in the list, then you should not add to the list. The book type is an enum type.</li>

 <li>Sort the list of books numerically by ID. The sorting should happen within the list. You should not create a new list (array of structs) of books having sorted books.</li>

 <li>Delete a book from the list. When deleting a book from the list, the user is prompted for Book ID only. The book should be removed from the list and the array structure should be preserved / restored afterwards. Attempting to delete a book who is not in the list should return 0. Otherwise, return 1 upon a successful removal of the record.</li>

</ol>




There is save() already implemented to write the books list to a file ‘Book_List.txt’. save() is executed at the end of the program when the user quits the program. You need to implement load() which is called at the start of the program. This function will read the saved file and fill in the array of structures. You need to read the file in the same order and manner that it is saved in save().




Expected output of each function:




<u>add:</u>




<u>display (given):</u>

(after adding 3 book details)




<u>sort:</u>

The books seen in display() output above are sorted in sort(). Use ‘d’ option to verify sorted result.

<u>delete:</u>

To verify that delete() worked as expected, use ‘d’ display option to display updated list. <u>load:</u>

Notice the message given by load() “Books record loaded from Book_List.txt” at the top. To verify that load() worked as expected, use ‘d’ display option to display loaded list.





